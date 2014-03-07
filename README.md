[![Build Status](https://travis-ci.org/twofortyfouram/android-annotation.png?branch=master)](https://travis-ci.org/twofortyfouram/android-annotation)

# Overview
android-annotation-lib implements annotations to improve the documentation of Android code.


# API Reference
JavaDocs for the library are published [here](http://twofortyfouram.github.io/android-annotation).


# Compatibility
The library is compatible and optimized for all Android API levels.


# Download
## Gradle
The library is published as an artifact to the two forty four a.m. maven repository.  To use the library, the two forty four a.m. maven repository and the artifact need to be added to your build script.

The build.gradle repositories section would look something like the following:

    repositories {
        maven { url 'https://dl.bintray.com/twofortyfouram/maven' }
    }

And the dependencies section would look something like this:
    
    dependencies {
        compile group:'com.twofortyfouram', name:'android-annotation', 'version:'[1.0.2,2.0[''
    }
