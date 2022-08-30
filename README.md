# scala-web-bloop-sbt-spring-thyme-hello-world

## Description
A springboot web app with thymeleaf support.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - springboot
  - thymeleaf
  - bootstrap
  - jquery
  - datatable

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
