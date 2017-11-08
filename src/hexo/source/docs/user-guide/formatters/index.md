---
category: "user-guide"
description: "List of core formatters and how they look like"
layout: "docs"
permalink: "docs/user-guide/formatters/index.html"
title: "List of official formatters"
tocTitle: "formatters"
---
# List of official formatters

The current supported `formatter`s are:

* `json` does a `JSON.stringify()` of the results. Output
  is not user friendly:

![Example output for the json formatter](./json-output.png)

* `stylish` prints the results in table format indicating the resource,
  line, and column:

![Example output for the stylish formatter](./stylish-output.png)

* `codeframe` shows also the code where the error was found if: Will
  show the piece of code where the error was found (if applicable):

![Example output for the codeframe formatter](./codeframe.png)

* `summary` shows just a summary of all the warnings and errors found
  for all the resources:

![Example output for the summary formatter](./summary-output.png)
