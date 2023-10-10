# java-cli-maven-ssl-postgresql-data-type-enum

## Description
Creates a small database table
called `dog`. Uses an enum user defined type.

Uses self-sign ssl.

## Tech stack
- java
- maven
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
