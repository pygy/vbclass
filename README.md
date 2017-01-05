## vbclass.js

vbclass.js is a deprecated, getter/setter implementation for ie8- that relies on vbscript to perform its magic.

Originally written by @webreflection ([blog describing the API](http://webreflection.blogspot.fr/2011/03/rewind-getters-setters-for-all-ie-with.html)). Please note that this cannot be used to fully polyfill the ES5 behavior.

The original SVN history has not been preserved here, see https://code.google.com/archive/p/vbclass/

## Original README

### What

VBClass is a cross browser function able to define VBScript like classes via JavaScript.

### Where

All Internet Explorer version I could test, included 5.5, 6, 7, 8, plus all ES5 ready browsers, plus all browsers with defineGetter and defineSetter support.
### Why

Getters and Setters are semantically perfect and totally transparent for users. We may choose some convention that pretends to simulate them or we can use full support through a proper class definition where methods are immutable and properties must have been defined in advance. VBClass brings a robust way to create objects that follows stricter rules, object that could be used whenever we would like to add getters and setters power in our framework, library, application.

### License

The MIT License

Copyright 2011 WebReflection

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.