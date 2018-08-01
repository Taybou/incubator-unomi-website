Incubator Apache Unomi Website
====================

This project contains the Incubator Apache Unomi Website.

## Build

You need a machine with Maven to build the website.

Checkout:

```
git clone https://github.com/apache/incubator-unomi-website
```

Run Build:

```
mvn clean install
```

## Publish

To publish the local website to the production location (https://unomi.incubator.apache.org/), you have to use:

```
mvn install scm-publish:publish-scm
```
