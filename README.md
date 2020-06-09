IsTablet Cordova/Phonegap Plugin
=================================
This Cordova/PhoneGap Plugin indicates whether the current device is a tablet.

Supported platforms: Android, iOS

## Contents

* [Using the plugin](#using-the-plugin)
* [Credits](#credits)
* [License](#license)
 
# Using the plugin
The plugin runs automatically when the app starts and sets an `isTablet` boolean property on the `window` object, so to use the plugin, simple inspect the value of `window.isTablet`.

For example:
    alert("This device is "+(window.isTablet?'':'NOT')+" a tablet");
    
# Credits
Android plugin code based on [this answer on stackoverflow](http://stackoverflow.com/a/18740974/777265) by [Pawan M](http://stackoverflow.com/users/648030/pawan-m)

License
================

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.