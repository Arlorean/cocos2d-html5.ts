cocos2d-html5.ts
================

Typescript version of cocos/cocos2d-html5 repository. Only HelloHTML5World is implemented in TypeScript so far and only then the src/myApp.ts file.

The latest cocos2d-html5 doesn't read the user agent string for IE11 correctly unless 'gecko' is added to the check.
IE11 WebGL has issues too so the file uses the CanvasRenderer instead. WebGL works with Firefox and Chrome correctly though.

The licenses for this project is the same as the cocos2d-html5 licenses.
