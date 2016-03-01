# Gradle Travis Colored Output (for tests)

When running Gradle tests on Travis CI, the terminal is usually set to `dumb` mode, so you get very plain looking output.  However, Travis does [allow for colors](https://blog.travis-ci.com/2014-04-11-fun-with-logs/) in their logs.

This Gradle script plugin formats the Gradle test output in a slightly colorful way (made for Travis CI but works in terminal).  It also adds a summary at the end.

## Usage

At the top of your `build.gradle`,

```java
apply from: 'https://raw.githubusercontent.com/mendhak/Gradle-Travis-Colored-Output/master/ColoredOutput.gradle'
```

Run your gradle tests.  

### Screenshots

**[Travis CI](https://travis-ci.org/mendhak/gpslogger/builds/112735526)**

![travis](screenshot-travis.png)

**Terminal**

![screenshot](screenshot-terminal.png)
