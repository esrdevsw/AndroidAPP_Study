# AndroidAPP_Study
Android APP Study

Todo List app

Build A Simple Android App With Kotlin
https://www.youtube.com/watch?v=BBWyXo-3JGQ

This is just a Kotlin feature test.
I just made some corrections to make the program run with the most modern version.


https://stackoverflow.com/questions/34169562/unresolved-reference-kotlinx

Add kotlin-android-extensions in our buildscript's dependencies:

1. In your project-level build.gradle

buildscript {
    dependencies {
        classpath "org.jetbrains.kotlin:kotlin-android-extensions:$kotlin_version"
    }
}
and apply the kotlin-android-extensions plugin:

2. In your module-level build.gradle

apply plugin: 'kotlin-android-extensions'

->Next step is to fix the App and add the database functionality.

