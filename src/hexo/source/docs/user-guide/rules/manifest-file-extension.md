---
category: "user-guide"
description: "manifest-file-extension warns against using non-standard fileextensions for the web app manifest file."
layout: "docs"
permalink: "docs/user-guide/rules/manifest-file-extension/index.html"
title: "Disallow non-standard file extension for the web app manifest file"
tocTitle: "rules"
---
# Disallow non-standard file extension for the web app manifest file (`manifest-file-extension`)

`manifest-file-extension` warns against using non-standard file
extensions for the [web app manifest][spec] file.

## Why is this important?

While the [`.webmanifest`][file extension] file extension is not
enforced by the specification, nor is it required by browsers, using
it makes it:

* [easier to set custom server configurations][server configs] for
  the web app manifest file
* possible to benefit from [existing configurations][other configs]

## What does the rule check?

The rule checks if the recommended [`.webmanifest`][file extension]
file extension is used for the web app manifest file.

### Examples that **trigger** the rule

```html
<link rel="manifest" href="site.json">
```

```html
<link rel="manifest" href="site.manifest">
```

### Examples that **pass** the rule

```html
<link rel="manifest" href="site.webmanifest">
```

## Further Reading

* [Web App Manifest Specification][spec]

<!-- Link labels: -->

[file extension]: https://w3c.github.io/manifest/#media-type-registration
[other configs]: https://github.com/jshttp/mime-db/blob/67a4d013c31e73c47b5d975062f0088aea6cd5cd/src/custom-types.json#L85-L92
[server configs]: https://github.com/w3c/manifest/issues/346
[spec]: https://www.w3.org/TR/appmanifest
