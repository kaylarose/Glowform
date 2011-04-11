# Glowform CSS3 Image-less Glowing Form Tech Demo

### [Demo](http://kaylarose.github.com/Glowform/ "The Glowform demo") (*requires Modern Webkit browser)

I thought Dragon Labs' Dragonfish Login Form Demo (http://labs.dragoninteractive.com/panel/demo/) was really neat. They implement the effect by using a rather large background image and a mask image and move the background image around via Javascript.

I wanted to see how close I could get with only CSS3 (and a little bit of helper JS).

## This is the First Iteration

[Checkout the demo](http://kaylarose.github.com/Glowform/ "Checkout the Glowform demo") (*Modern Webkit browser required). Though you can see an alternate implementation if you use Firefox 4, and non-animated mode in <4Firefox) [Not tested in IE]

## The Implementation

TODO Writeup inset shadow mask technique, and more in-depth impl. info.

On Webkit browsers - I got pretty close, with color transitions and keyframes and using a background gradient animation to simulate the "highlight" textures.

Firefox doesn't support keyframes for the color transitions, so I implemented a used fallback animation with simulated color transitions. IMO the fallback animation on Firefox 4 doesn't look too bad either - with older Firefox's falling back to non-animated glow mode.

## TODOs

### More variation in highlight and color angles
Dogfish has a much better variation of colors and highlight textures thank to the use of images.

### Better browser support for animations
You could probably hack around Firfeox's lack of keyframe support via color transitions and classes.

###IE Support????


