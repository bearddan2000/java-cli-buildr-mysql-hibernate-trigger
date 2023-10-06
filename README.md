# java-cli-buildr-mysql-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- buildr
  - hibernate
  - hql
  - log4j
  - mysql driver

## Docker stack
- vanto/apache-buildr:latest-jruby-jdk8
- mariadb

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
