## Master

*  Added `heroku:run-war` goal to run a WAR file locally with a command similar on Heroku

*  Added `heroku:dashboard` goal to open the Heroku dashboard for the configured application

*  Began enforcement of `war` packaging when using `-war` goals

*  Added `heroku:eclipse-launch-config` goal to generate Eclipse launch configuration files

## 0.3.0

*  Jumping to 0.3.x version to align with sbt-heroku

*  [#4] Use explicit versions in pom.xml

*  [#1] Remove support for Java 1.6

## 0.1.9

*  Improved detection of Heroku API key. Now uses .netrc first.