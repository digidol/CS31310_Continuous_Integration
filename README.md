# CS31310 Continuous Integration

This project is setup to allow it to be run within Jenkins, a Continuous Integration server. 

## Build Script
This project uses Ant as the tool to build the project. [Apache Ant](http://ant.apache.org) is an open source tool that can be used to manage the build process for a Java project. Other, more recent, build tools include 
[Maven](https://maven.apache.org) and [Gradle](https://gradle.org). 

This project is using Ant simply because it shows how each of the steps are to be performed. Tools like Maven and Gradle are powerful and are more likely to be used on a project that is starting today. However, they rely on convention. That can seem like magic if you are using such tools. Therefore, Ant is transparent and you get to specify the necessary steps that you want to see in your build process.  