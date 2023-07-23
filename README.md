# php-web-sqlserver-ssl-simple

## Description
A PDO connection to a database.

Sql server uses self-signed ssl.

## Tech stack
- php
- jquery
- bootstrap

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- php-fpm

## To run
`sudo ./install.sh -u`  
http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
