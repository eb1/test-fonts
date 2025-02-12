# test-fonts

A simple Cordova application that tests the cordova-plugin-fonts plugin.

## Installation

The cordova-fonts plugin uses the cordova-plugin-test-framework to run unit tests. Complete the following to run through the plugin unit tests:

1. Clone this app.
2. If you haven't already, install Cordova (this also requires installing node.js if you haven't done that -- see the [Cordova Getting Started documentation](https://cordova.apache.org/#getstarted) for more information). 
3. From the command line, add the cordova-fonts plugin and test / test framework plugins:

        cordova plugin add https://github.com/adapt-it/cordova-fonts.git
        cordova plugin add https://github.com/adapt-it/cordova-fonts.git#:/tests
        cordova plugin add cordova-plugin-test-framework

    OR, if you are modifying the source for cordova-plugin-fonts, you can refer to your local clone instead of the version on GitHub (this example assumes `test-fonts` is in a sibling directory to `cordova-fonts`):

        cordova plugin add ../cordova-fonts
        cordova plugin add ../cordova-fonts/tests
        cordova plugin add cordova-plugin-test-framework

4. Build and run the application in an emulator or on the device.
