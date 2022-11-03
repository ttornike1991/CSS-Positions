Absolutely Positioned Layouts.



Absolute positioning gives us full control over the size and position of any element, but it comes at a cost. An absolutely positioned element cannot affect the position of any other element on the page, so it can't push other elements out of the way if it expands.

If the position of an element doesn't need to affect the position of any other elements on the page, you have an absolute positioning candidate. Declare the element position absolute and optionally give it top and left values. If you don't need to worry about IE6, you can also give it bottom and right values.

You can create any layout you like using absolute positioning, provided you don't need the elements to jostle each other out of the way.

Absolute positioning is useful in any element where we know the height in advance. It the case of our header, we have fixed the height so we don't need to worry about elements interfering with each other. We're free to chuck the header's contents around as we see fit.