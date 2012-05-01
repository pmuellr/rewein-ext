rewein-ext : REmote WEb INspector EXTensions for iOS
====================================================

If you're developing webby bits on iOS, you can use one of the
following tools/techniques to enable Remote Web Inspector debugging,
currently just under the iOS Simulator on iOS >= 5.x:

* [iWebInspector](http://www.iwebinspector.com/)
* [Cordova Web Inspector plugin](https://github.com/pmuellr/phonegap-plugins/tree/web-inspector/iOS/WebInspector)
* [manual enablement](http://atnan.com/blog/2011/11/17/enabling-remote-debugging-via-private-apis-in-mobile-safari/)

There are issues, and this Safari extension is supposed to help with them

installation
============

Not quite sure yet what the best mechanism is.
For now, clone the repo locally, then add the 
extension manually from the Safari Develop / Show Extension Builder menu.

extensions
==========

List of things that this extension "fixes".

fix the monospace font
----------------------

The default monospace font is Monoco 10px, which looks like crap on my boxes.

The extension changes this to use monospace 12px instead, which means it should
also take into account whatever your default monospace font is set to 
in Safari preferences.