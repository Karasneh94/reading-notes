# Local Storage

## INTRODUCING HTML5 STORAGE

Its a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

### HTML5 STORAGE SUPPORT

* Internet Explorer 8.0+

* FireFox 3.5+

* Safari 4.0+

* Chrome 4.0+

* Opera 10.5+

* Iphone 2.0+

* Android 2.0+

### Detecting the support of HTML5 Storage

`if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}`

## USING HTML5 STORAGE

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

## LIMITATIONS IN CURRENT BROWSERS

1. “5 megabytes” is how much storage space each origin gets by default.
1. “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.
1. “No“ no browser supports any mechanism for web developers to request more storage space.
