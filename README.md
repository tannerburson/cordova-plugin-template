PhoneGap/Cordova Plugin Template
==========================

This is a simple directory structure, and set of build scripts to make creating an Android Plugin for PhoneGap/Cordova easier.

Supported Platforms
-------------------
* Android

Using the Template
-------------------

* Change package.name variable in build.xml and android/build.xml to be the name of your project
* Drop your plugin source into android/src/ 
* Add the Javascript for your plugin into www/
* Update android/lib/cordova-VERSION.jar if it is out of date
* Set VERSION to hold the version number of your project
* Update the README

Building your project
---------------------

Run `ant dist`, that will create a dist directory with a jar, and a js file of your plugin.
