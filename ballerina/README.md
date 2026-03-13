## Overview

The H2 driver provides a reliable and high-performance connectivity to H2 databases. It enables efficient execution of SQL queries, updates, and other database operations. The driver is designed to provide a seamless experience for interacting with H2, supporting various data types and advanced features of the database.

### Key Features

- High-performance and reliable database connectivity
- Support for various SQL operations (Query, Execute, Batch)
- Efficient handling of database connections and resources
- Support for database-specific data types and features
- Secure communication with TLS and authentication
- GraalVM compatible for native image builds

## Compatibility

| |   Version    |
|:---|:------------:|
|Ballerina Language | **2201.7.0** |
|H2 Driver* |  **2.2.220**  |

> *H2 is dual licensed and available under the MPL 2.0 (Mozilla Public License Version 2.0) or under the EPL 1.0 (Eclipse Public License).

## Usage

To add the H2 driver dependency the project simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/java.jdbc;
import ballerinax/h2.driver as _;
```
