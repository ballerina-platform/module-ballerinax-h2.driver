## Package overview

This Package bundles the latest H2 driver so that `java.jdbc` connector can be used in ballerina projects easily.

## Compatibility

| |   Version    |
|:---|:------------:|
|Ballerina Language | **2201.7.0** |
|H2 Driver* |  **2.2.220**  |

> * H2 is dual licensed and available under the MPL 2.0 (Mozilla Public License Version 2.0) or under the EPL 1.0 (Eclipse Public License).

## Usage

To add the H2 driver dependency the project simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/java.jdbc;
import ballerinax/h2.driver as _;
```
