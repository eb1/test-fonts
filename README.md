# test-fonts

A simple Cordova application that tests the cordova-plugin-fonts plugin.

## Installation

The cordova-fonts plugin uses the cordova-plugin-test-framework to run unit tests. Complete the following to run through the plugin unit tests:

1. Clone this app.
2. If you haven't already, install Cordova (this also requires installing node.js if you haven't done that -- see the [Cordova Getting Started documentation](https://cordova.apache.org/#getstarted) for more information). 
2. From the command line, add the cordova-fonts plugin and test / test framework plugins:

        cordova plugin add https://github.com/adapt-it/cordova-fonts.git
        cordova plugin add https://github.com/adapt-it/cordova-fonts.git#:/tests
        cordova plugin add http://git-wip-us.apache.org/repos/asf/cordova-plugin-test-framework.git

3. Build and run the application in an emulator or on the device.
