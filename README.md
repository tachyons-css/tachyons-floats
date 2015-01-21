# TACHYONS-FLOATS

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-floats
```
or download the css on github and include in your project.

## The Code
```

/*

   FLOATS

   1. Floated elements are automatically rendered as block level elements.
      Setting floats to display inline will fix the double margin bug in
      ie6. You know... just in case.

   Legend

   f = float
   l = left
   r = right
   n = none

*/



.fl { float: left;  display: inline; }
.fr { float: right; display: inline; }
.fn { float: none; }

@include break(not-small) {
  .fl-ns { float: left; display: inline; }
  .fr-ns { float: right;display: inline; }
  .fn-ns { float: none; }
}

@include break(medium) {
  .fl-m { float: left; display: inline; }
  .fr-m { float: right;  display: inline; }
  .fn-m { float: none; }
}

@include break(large) {
  .fl-l { float: left; display: inline; }
  .fr-l { float: right;  display: inline; }
  .fn-l { float: none; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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

