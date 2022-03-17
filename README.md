# window-management
This is a set of window-management-api's and a stealify wrapper for them. This is maybe the first Implementation of this concepts that got ever done: https://github.com/breach/breach_core

## Basics
There are 3 main Implementations that you can consume

- Pupeteer - chrome-remote-interface - chrome-launcher => a ECMAScript api to controll existing Browsers that support the devtools protocol.
- Electron - => a ECMAScript api as CEF Replacement
- NWJS - => a ECMAScript api as CEF Replacement
- JCEF - JAVACEF => Running in GraalVM can be Scripted via ECMAScript. 

## Advanced
if you plan to distribute more then one app on a Singel Desktop you should always try out one of our Supported Stealify Platform Implementations
and if you want to use them all Simply install Open PWA which implements all 3
