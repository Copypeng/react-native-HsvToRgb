## Introduction

A helper to convert HSV(HSB) color to RGB.

As in react native framework, only #hex|rbg|rbga colors are accepted，I made this helper to convert HSV to RGB.

## Install

just download <code>HsvToRgb.js</code> Please.


## Usage

<pre><code>
var HsvToRgb = require('../helper/HsvToRgb.js');
...

// accepts parameters
// h, hue, 0.0 to 1.0
// s, saturation, 0.0 to 1.0
// v, lightness or brightness, 0.0 to 1.0

var colorString = HsvToRgb.getRGBString(h,s,v);     //retun "rbg(r,g,b)"

var color =  HsvToRgb.getRGB(h,s,v);         //return {r,g,b}


</code>
</pre>
