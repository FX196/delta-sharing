<img src="https://docs.delta.io/latest/_static/delta-lake-white.png" width="400" alt="Delta Lake Logo"></img>

[![Build and Test](https://github.com/delta-io/delta-sharing/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/delta-io/delta-sharing/actions/workflows/build-and-test.yml)

[Delta Sharing](https://delta.io/sharing) is an open API to share [Delta Lake](https://delta.io/) tables between data providers and data recipients.

# Introduction

This repo includes a Pandas connector and an Apache Spark connector that implement the [Delta Sharing Protocol](PROTOCOL.md), and a reference implementation of a Delta Sharing server.

## Data Share Profile



## Pandas Connector


## Apache Spark Connector

You can add the Spark connector as a dependency using your favorite build tool.

### Maven

```xml
<dependency>
  <groupId>io.delta</groupId>
  <artifactId>delta-sharing-spark_2.12</artifactId>
  <version>0.1.0</version>
</dependency>
```

### SBT

```scala
libraryDependencies += "io.delta" %% "delta-sharing-spark" % "0.1.0"
```
### Compatibility with Apache Spark Versions

Delta Sharing Spark Connector currently requires Apache Spark 3.0.0 and above.

## Delta Sharing Server


# Delta Sharing Protocol

[Delta Sharing Protocol](PROTOCOL.md) document provides a specification of the Delta Sharing protocol.

# Reporting issues

We use [GitHub Issues](https://github.com/delta-io/delta-sharing/issues) to track community reported issues. You can also [contact](#community) the community for getting answers.

# Building

Delta Sharing Spark Connector and Delta Sharing Server are compiled using [SBT](https://www.scala-sbt.org/1.x/docs/Command-Line-Reference.html).

To compile, run

    build/sbt compile

To generate artifacts, run

    build/sbt package

To execute tests, run

    build/sbt test

Refer to [SBT docs](https://www.scala-sbt.org/1.x/docs/Command-Line-Reference.html) for more commands.

# Contributing 
We welcome contributions to Delta Sharing. See our [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

We also adhere to the [Delta Lake Code of Conduct](CODE_OF_CONDUCT.md).

# License
Apache License 2.0, see [LICENSE](LICENSE.txt).

# Community

There are two mediums of communication within the Delta Lake community.

- Public Slack Channel
  - [Register here](https://dbricks.co/delta-users-slack)
  - [Login here](https://delta-users.slack.com/)

- Public [Mailing list](https://groups.google.com/forum/#!forum/delta-users)