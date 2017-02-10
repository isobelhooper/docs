---
title: Downloads
keywords: setup, getting started, download
last_updated: October 1st, 2016
tags: [getting-started]
summary: "
This is a list of Grakn releases. It's the place to come to download the most recent versions of Grakn."
sidebar: documentation_sidebar
permalink: /documentation/resources/downloads.html
folder: documentation
comment_issue_id: 25
---


## Download Grakn Latest Version

[![download](/images/download.png)](https://grakn.ai/download/latest)


### Past Versions
A list of previously released versions of Grakn can be found on [Github](https://grakn.ai/download).


## Prerequisites

{% include note.html content="We currently support Mac OS X and Linux. Grakn requires Java 8 (Standard Edition) with the `$JAVA_HOME` set accordingly. Grakn also requires Maven 3." %}

## Code
We are an open source project. If you want to look at our code, we are on Github at [https://github.com/graknlabs/grakn](https://github.com/graknlabs/grakn).

### Building the Code

To build Grakn, you need Maven, node.js and npm. Make sure you have the most recent version of node.js and npm.

Using git, clone the [Grakn repository](https://github.com/graknlabs/grakn) to a local directory.  In that directory:

```bash
mvn package -DskipTests
```

When the build has completed, you will find it in the `grakn-dist` directory under `target`. The zip file built into that directory is the same as that distributed as a release on [Github](https://grakn.ai/download).

### Example Code
You can find an additional repo on Github containing our [example code](https://github.com/graknlabs/sample-projects), while further information about the examples is [here](../examples/examples-overview.html).


## Grakn Java API

Inside the `lib` directory of Grakn.zip are the jars you will need to
develop with Grakn.

If you would like to start developing with minimal effort you can integrate the jar file, e.g.
`graql-shell-x.y.z-jar-with-dependencies.jar` into your project. This however
may be a bit inflexible as all dependencies are compiled in.

If you would like more flexibility, in the `lib` directory all the Grakn
jars are provided with no dependencies. Using these would require you to use
Maven to acquire the other dependencies.

Here are some links to guides for adding external jars using different IDEs:

- [IntelliJ](https://www.jetbrains.com/help/idea/2016.1/configuring-module-dependencies-and-libraries.html)
- [Eclipse](http://www.tutorialspoint.com/eclipse/eclipse_java_build_path.htm)
- [Netbeans](http://oopbook.com/java-classpath-2/classpath-in-netbeans/)

## Questions?
Please see our [FAQ](../resources/faq.html) page if you encounter any problems when installing and running Grakn. If our guide doesn't cover the issue, please do get in touch on our [discussion forums](http://discuss.grakn.ai), on [Stack Overflow](http://www.stackoverflow.com) or via our [Slack channels](https://grakn.ai/slack.html).

{% include links.html %}

## Comments
Want to leave a comment? Visit <a href="https://github.com/graknlabs/docs/issues/25" target="_blank">the issues on Github for this page</a> (you'll need a GitHub account). You are also welcome to contribute to our documentation directly via the "Edit me" button at the top of the page.