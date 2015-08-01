[![Build Status](https://travis-ci.org/twofortyfouram/android-annotation.png?branch=master)](https://travis-ci.org/twofortyfouram/android-annotation)

# Overview
android-annotation-lib implements annotations to improve the documentation of Android code.


# API Reference
JavaDocs for the library are published [here](http://twofortyfouram.github.io/android-annotation).


# Compatibility
The library is compatible and optimized for all Android API levels.


# Download
## Gradle
The library is published as an artifact to jCenter.  To use the library, the jCenter repository and the artifact need to be added to your build script.

The build.gradle repositories section would look something like the following:

    repositories {
        jcenter()
    }

And the dependencies section would look something like this:
    
    dependencies {
        compile group:'com.twofortyfouram', name:'android-annotation', version:'[2.0.1,3.0['
    }


# History
* 1.0.0: Initial release
* 1.0.2: Update Android Gradle plugin, which changed the generated BuildConfig
* 2.0.0: Remove nullness annotations in favor of the Android support annotations
* 2.0.1: Reupload artifacts with source and JavaDoc for inclusion in jCenter
