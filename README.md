# IronCore Labs IronOxide Scala SDK

[![scaladoc](https://javadoc-badge.appspot.com/com.ironcorelabs/ironoxide-scala_2.12.svg?label=scaladoc)](https://javadoc-badge.appspot.com/com.ironcorelabs/ironoxide-scala_2.12)

SDK for using IronCore Labs from Scala server side applications. This library wraps [ironoxide-java](https://github.com/IronCoreLabs/ironoxide-java)
with more Scala friendly interfaces and types. It presents two top level APIs:

- [`IO`](https://typelevel.org/cats-effect/) based
- [`Future`](https://docs.scala-lang.org/overviews/core/futures.html) based

## Installation

This project is [published to Maven central](https://search.maven.org/artifact/com.ironcorelabs/ironoxide-scala_2.12).

You'll also need to follow the library setup instructions in [ironoxide-java](https://github.com/IronCoreLabs/ironoxide-java#library) to ensure
you have the proper binary compiled and loaded.

Below you'll find a link of the ironoxide-scala version with which native component you need:

| ironoxide-scala | ironoxide-java                                                                |
| --------------- | ----------------------------------------------------------------------------- |
| 0.9.0           | [0.11.0](https://github.com/IronCoreLabs/ironoxide-java/releases/tag/v0.11.0) |
| 0.8.0           | [0.9.0](https://github.com/IronCoreLabs/ironoxide-java/releases/tag/v0.8.0)   |
| 0.7.x           | [0.8.2](https://github.com/IronCoreLabs/ironoxide-java/releases/tag/v0.8.2)   |
| 0.6.0           | [0.7.2](https://github.com/IronCoreLabs/ironoxide-java/releases/tag/v0.7.2)   |

## Usage

All the SDK classes can be imported from the `com.ironcorelabs.scala.sdk` namespace.

## Documentation

Further documentation is available on our [docs site](https://ironcorelabs.com/docs).

Copyright (c) 2019 IronCore Labs, Inc. All rights reserved.
