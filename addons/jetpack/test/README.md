#Jetpack OpenWebApps add on unit tests#

These are the unit tests to test modules that are not shared with the HTML5 shim.
To test modules shared with the HTML5 shim, use the browser based test set located
in /site/tests/

The tests in this directory are run using the JetPack based unit test system. 
Docs on the various parameters can be found on (MDN - cfx - Add-on 
SDK Documentation)[https://addons.mozilla.org/en-US/developers/docs/sdk/1.0/dev-guide/addon-development/cfx-tool.html]

The basic command to run the tests must be run from the /addons/jetpack 
directory, and is:

    cfx test