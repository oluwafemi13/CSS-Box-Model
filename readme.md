CSS BORDER BOX
everything Displayed by css is a box no matter what shape it comes in form of or even a text
intrinsic box sizing allows the browser to make the decision based on the content of the box. This is also the default flexible behaviour of the browser.

Extrinsic box sizing gives a fixed size to the box and no room for adjustmant based on the content of the box. if the content of the box is larger that the extrinsic size of the box, then the content will overflow form the box. This also gives more control to the surface of the box.

AREAS OF THTE BOX MODEL:

CONTENT BOX: THis is the Area that the content lives with the box. This is the most flexible part of the box because it's size usually affects the box itself.

PADDING BOX: This is the area directly sorrounding the content box and is the space created by the padding property. This also makes the background of the box visible because it creates space away form the content itself.
If the box has overflow set, like( overflow: auto) or (overflow: scroll), the scrollbars will occupy this space too.


BORDER BOX: THis box sorrounds the padding box and is set using th border value. This is also used to set a frame for the box.

MARGIN BOX: This is the space outside the Box itself. it is also the space around the border box.