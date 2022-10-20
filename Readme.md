.Following are the list of mixin and parameters:

1)@include  wrapper(suffix(optional), width);
  Create wrapper with any suffix if not passed then normal  wrapper is created or overwrite
  existing wrapper.params:str|null,%|px|null

2)@include icon(content, textIndent(optional));
  Adds icon to element , accepts unicode .Params:str,boolean

3)@include flex(isFlex, flexBasis, justify-content, align-items, flex-direction,wrap, flexOrder);
  Flex property.

4)@include img(object-fit);

5)@include boxModel(width, height);

6)@include display(display, float, overflow, zIndex);

7)@include position(position, top, right, bottom, left);

8)@include font(color, family, size, weight, text-transform, text-align) ;

9)@include border(border, borderRadius) ;

10)@include prefix(property, value);

11)@include transition(property, time, func);

12)@include breakpoint(min, max);

13)@include responsive(device) ;

14)@include reverseResponsive(device);

15)@include background(color,url, rgba, overlay);

16)@include clickable(bgcolor, color);

Maps :
use sass:map;
Getting value from map:map.get($map_name,key);
1)
$devices:(
  "desktop":"1024px",
  "tablet":"995px",
  "ipad":"768px",
  "largePhone":"540px",
  "mediumPhone":"480px",
  "smallPhone":"320px"
);

$social:(
  "fb":"\f39e",
  "fb-sq":"\f082",
  "fb-ro":"\f09a",
  "twitter":"\f099",
  "twitter-sq":"\f081",
  "insta":"\f16d",
);