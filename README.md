<p align="center">
    <a href="https://www.graalvm.org/">
        <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
    </a>
    <br />
    <a href="https://maven.apache.org/">
        <img src="https://img.shields.io/badge/apachemaven-C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
    </a>
</p>

# Inverted Index
This repository contains an implementation of a simple Inverted Index.

## 1) Overview
TODO

## 2) Terminologies
TODO

# High Level Design
## 1) Problem Statement
The goal of this repository is to create a simple Inverted Index that is capable of:
* TODO

## 2) Constraints
This inverted index implementation will not:
* TODO

## 3) Implementation
TODO

# Prerequisites
This project requires the following:
* SDKMAN
* Java Runtime
* Maven

# Installation
Follow the instructions below to install SDKMAN:
```
https://sdkman.io/install
```

Run the following command to install the exact Java Graal version:
```bash
sdk env install
```

Run the following command to install the exact Maven Version:
```bash
sdk install maven 3.9.9
```

# Build
Run the following command to clean install dependencies:
```shell
mvn clean install
```

Run the following command to run unit tests via terminal:
```shell
mvn test
```

Run the following command to query the inverted index via Maven + terminal:
```shell
mvn exec:java -Dexec.mainClass="com.search.App"
```

Run the following command to query the inverted index via terminal:
```shell
java -cp target/incidence-matrix-1.0-SNAPSHOT.jar com.search.App
```

# License
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)