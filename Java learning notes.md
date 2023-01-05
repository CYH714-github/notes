# Java learning notes

## installation and settings

First we need to download JDK 19 from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) and install it. Then get into This PC -> Properties -> Advanced system settings -> Environment Variables. In the `system variables` you should add `JAVA_HOME` as its name and the enter its installation path(remember to add `\bin` in the end of the path).

If lucky, open powershell and input `java -version`, you will see the output like this:

```
C:\> java -version
java version "19" ...
Java(TM) SE Runtime Environment
Java HotSpot(TM) 64-Bit Server VM   
```