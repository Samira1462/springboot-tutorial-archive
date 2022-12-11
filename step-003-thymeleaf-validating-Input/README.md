# Flightright Group challenge

## Prerequisites

* Java 11
* Maven 3
* thymeleaf
* validation
* spring boot

## Description

The Purpose of a simple Spring MVC application that takes user input and checks the input by using standard validation annotations.

### The rules:
@Size(min=2, max=30): Allows names between 2 and 30 characters long.

@NotNull: Does not allow a null value, which is what Spring MVC generates if the entry is empty.

@Min(18): Does not allow the age to be less than 18.

## Build

```shell
mvn clean package -DskipTests=true
mvn test
```
##Run
```shell
mvn spring-boot:run

```


## Install

```shell
mvn clean install
```

