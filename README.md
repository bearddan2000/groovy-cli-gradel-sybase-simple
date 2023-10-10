# groovy-cli-gradel-sybase-simple

## Description
Creates a small database table
called `dog` and populates it
with a single row.

## Tech stack
- docker-wait
- groovy
- gradel
  - log4j
  - sybase driver

## Docker stack
- gradle:jdk11
- datagrip/sybase

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Sybase driver and connection example](https://razorsql.com/docs/help_sybase.html)
