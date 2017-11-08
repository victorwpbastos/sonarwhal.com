---
category: "user-guide"
description: "no-disallowed-headers warns against responding with certain HTTPheaders."
layout: "docs"
permalink: "docs/user-guide/rules/no-disallowed-headers/index.html"
title: "Disallow certain HTTP headers"
tocTitle: "rules"
---
# Disallow certain HTTP headers (`no-disallowed-headers`)

`no-disallowed-headers` warns against responding with certain HTTP
headers.

## Why is this important?

Servers, frameworks, and server-side languages (e.g.: ASP.NET, PHP),
often set, by default, HTTP headers with values that contain information
about them: their name, version number, etc.

Sending those types of HTTP headers does not provide any value to
users, contributes to header bloat, and just gives more information
to any potential attackers about the technology stack being used.

## What does the rule check?

By default, the rule checks if responses include HTTP headers that
provide information about the technology stack, namely, it checks
for the presence of the following headers:

* `Server`
* `X-AspNet-Version`
* `X-AspNetMvc-version`
* `X-Powered-By`
* `X-Runtime`
* `X-Version`

### Examples that **trigger** the rule

```text
HTTP/... 200 OK

...
Server: Apache/2.2.27 (Unix) mod_ssl/2.2.27 OpenSSL/1.0.1e-fips mod_bwlimited/1.4
X-Powered-By: PHP/5.3.28
```

### Examples that **pass** the rule

```text
HTTP/... 200 OK

...
```

## Can the rule be configured?

Yes, you can use:

* `include` to specify additional HTTP headers that should
  be disallowed
* `ignore` to specify which of the disallowed HTTP headers
  should be ignored

E.g. The following configuration will make the rule allow responses to
be served with the `Server` HTTP header, but not with `Custom-Header`.

```json
"no-disallowed-headers": [ "warning", {
    "ignore": ["Server"],
    "include": ["Custom-Header"]
}]
```
