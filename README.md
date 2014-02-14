sample-android-TabChildView
=======================

This example shows you how to __embed__ a CoronaView into a fragment.  The fragment is then put into a tab.

# Code Overview

## CoronaView setup (Java)

The CoronaView is instantiated just like any normal view.

## CoronaView contents (Lua)

The contents of the `CoronaView` are determined via Lua. In this project, the `CoronaView` is told to look for Lua files in the `Corona` subfolder of the .app bundle. 

NOTE: The Xcode project is setup to automatically copy the contents of `TabChildView/Corona` to a `Corona` subfolder in the destination .app bundle, so you are free to modify/add/delete the Lua files as well as other asset files.


# Setup

The sample expects the Corona .jar files to be placed in app/libs and the Corona .so files to be placed in app/src/main/jniLibs.


# Requirements

# Version Notes
