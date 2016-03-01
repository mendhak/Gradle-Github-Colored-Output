# Gradle Travis Colored Output (for tests)
Gradle script plugin.  It formats gradle test output in a slightly colorful way (made for Travis CI but works in terminal).  Also adds a summary at the end.

## Reference it

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
