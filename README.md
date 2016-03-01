# Gradle-Travis-Colored-Output
Gradle script plugin which formats test output in a slightly colorful way (made for Travis CI but works in terminal)

## Reference it

At the top of your `build.gradle`,

    //Generating colorful output
    apply from: 'https://raw.githubusercontent.com/mendhak/Gradle-Travis-Colored-Output/master/ColoredOutput.gradle'

Run gradle tests.  

### Screenshots

**[Travis CI](https://travis-ci.org/mendhak/gpslogger/builds/112727616)**

![travis](screenshot-travis.png)

**Terminal**

![screenshot](screenshot-terminal.png)
