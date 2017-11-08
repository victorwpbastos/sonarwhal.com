---
category: "developer-guide"
description: "All the things to take into account if you are going to develop a new formatter"
layout: "docs"
permalink: "docs/developer-guide/formatters/index.html"
title: "How to develop a formatter"
tocTitle: "formatters"
---
# How to develop a formatter

A `formatter` formats the results of `sonar`: from crafting `JSON` to
connecting to a database and storing the results in it.

To create one, you will need a module that exports an object with a
method named `format()`. This method will receive an array of `message`s
if any issues have been found.

The following is a basic `formatter` that `.stringify()`s the results:

```js
const formatter = {
    format(messages) {
        console.log(JSON.stringify(messages, null, 2));
    }
};

export default formatter;
```

A `message` looks like this:

```json
{
    "column": "number", // The column number where the issue was found if applicable.
    "line": "number", // The line number where the issue was found if applicable.
    "message": "string", // The human friendly detail of the error.
    "resource": "string", // The URL or name of the asset with the issue.
    "severity": "number" // 1 (warning), 2 (error).
}
```

With this, you can group the issues by `resource` and sort them by
`line` and `column`. Using the previous example and `lodash` will
look as follows:

```js
import * as _ from 'lodash';

const formatter = {
    /** Format the problems grouped by `resource` name and sorted by line and column number */
    format(messages) {
        const resources = _.groupBy(messages, 'resource');

        _.forEach(resources, (msgs, resource) => {
            const sortedMessages = _.sortBy(msgs, ['line', 'column']);

            console.log(`${resource}: ${msgs.length} issues`);
            console.log(JSON.stringify(sortedMessages, null, 2));
        });
    }
};

export default formatter;
```

You can always check the code of any of the official `formatter`s for
more complex scenarios.
