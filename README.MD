# Photoshop shadow to CSS

标签（空格分隔）： photoshop cs shadow text-shadow box-shadow

---------

Well, this is a LESS mixin collection for people who need:

 - To convert a photoshop shadow to CSS shadow.
 - To write CSS shadow mark but ONLY KNOW PHOTOSHOP design.

----------
.photoshop-drop-shadow (@angle: 120deg, @distance: 0, @spread: 0, @size: 0, @color: #000, @inner: false, @type: 'box')
------------------------------------------------------------------------

*example:*
> .photoshop-drop-shadow(145deg, 5px, 6%, 10px, rgba(118, 113, 113, .75), false);

----------
.photoshop-inner-shadow (@angle: @default-angle, @distance: 0, @spread: 0, @size: 0, @color: #000)
------------------------------------------------------------------------

*example:*
> .photoshop-inner-shadow(145deg, 5px, 6%, 10px, rgba(118, 113, 113, .75));

----------

.photoshop-text-shadow (@angle: 120deg, @distance, @spread, @size, @color)
------------------------------------------------------------------------

*example:*
> .photoshop-text-shadow(145deg, 5px, 6%, 10px, rgba(118, 113, 113, .75));

----------

.photoshop-outer-flow (@choke: 0, @size: 0, @color: #fff)
------------------------------------------------------------------------

*example:*
> .photoshop-outer-glow(1px, 1px, red);

----------

.photoshop-inner-flow (@choke: 0, @size: 0, @color: #fff)
------------------------------------------------------------------------

*example:*
> .photoshop-inner-glow(1px, 1px, red);

----------
OK...then...

It's maybe... not... a... very... useful... thing..

But some people WILL LOVE IT...Or...Do They?

Buy me a drink: wod8@163.com