# Gradle Travis Colored Output (for tests)

When running Gradle tests on Travis CI, the terminal is usually set to `dumb` mode, so you get very plain looking output.  However, Travis does [allow for colors](https://blog.travis-ci.com/2014-04-11-fun-with-logs/) in their logs.

This Gradle script plugin formats the Gradle test output in a slightly colorful way (made for Travis CI but works in terminal).  It also adds a summary at the end.

## Usage

Add the [ColoredOutput.gradle](ColoredOutput.gradle) to your project, for example at `buildtools/ColoredOutput.gradle`

At the top of your `build.gradle`,

```java
apply from: 'buildtools/ColoredOutput.gradle'
```

If you want Travis folding, you can enable it like so:

```java
apply from: 'buildtools/ColoredOutput.gradle'
project.ext.set("TRAVIS_FOLDING", true)
```

Run your gradle tests.  Run your gradle tests on Travis. 

### Screenshots

**[Travis CI](https://travis-ci.org/mendhak/gpslogger/builds/112735526)**

![travis](screenshot-travis.png)

**Terminal**

![screenshot](screenshot-terminal.png)
