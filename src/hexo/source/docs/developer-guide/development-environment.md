---
category: "developer-guide"
description: "What you need to do to start developing for sonar"
layout: "docs"
permalink: "docs/developer-guide/development-environment/index.html"
title: "Development Environment"
---
# Development Environment

This is a step-by-step guide to setting up a local development
environment that will let you contribute back to the project.

1. [Install Node.js](#step-1)
2. [Fork and checkout your own sonar repository](#step-2)
3. [Add the upstream source](#step-3)
4. [Run the tests](#step-4)

<!-- markdownlint-disable MD033 -->

## Step 1: Install Node.js <a name="step-1"></a>

<!-- markdownlint-enable MD033 -->

Go to [`nodejs.org`][nodejs] to download and install the latest stable
version of `Node.js` for your operating system.

**Note:** By installing `Node.js` you will also get [`npm`][npm], which
we will use to install packages that `sonar` depends on.

<!-- markdownlint-disable MD033 -->

## Step 2: Fork and checkout your own sonar repository <a name="step-2"></a>

<!-- markdownlint-enable MD033 -->

Go to <https://github.com/sonarwhal/sonar> and click the `Fork` button.
Follow the [GitHub documentation][github fork docs] for forking and cloning.

Once you've cloned the repository:

```bash
git clone https://github.com/sonarwhal/sonar.git
```

go into the project's directory:

```bash
cd sonar
```

and run `npm install` to get all the necessary dependencies:

```bash
npm install
```

You must be connected to the Internet for this step to work. You'll
see a lot of utilities being downloaded.

<!-- markdownlint-disable MD033 -->

## Step 3: Add the upstream source <a name="step-3"></a>

<!-- markdownlint-enable MD033 -->

The *upstream source* is the main `sonar` repository that active
development happens on. While you won't have push access to upstream,
you will have pull access, allowing you to pull in the latest code
whenever you want.

To add the upstream source for `sonar`, run the following in your
repository:

```bash
git remote add upstream git@github.com:sonarwhal/sonar.git
```

Now, the remote `upstream` points to the upstream source.

<!-- markdownlint-disable MD033 -->

## Step 4: Run the tests <a name="step-4"></a>

<!-- markdownlint-enable MD033 -->

Running the tests is the best way to ensure you have correctly set up
your development environment. Make sure you're in the `sonar` directory,
and then run:

```bash
npm test
```

The testing takes a a bit to complete. If any tests fail, that
likely means one or more parts of the environment setup didn't complete
correctly. The upstream tests always pass.

<!-- Link labels: -->

[github fork docs]: https://help.github.com/articles/fork-a-repo
[nodejs]: https://nodejs.org/en/download/current/
[npm]: https://www.npmjs.com/get-npm
