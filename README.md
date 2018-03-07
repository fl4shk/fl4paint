# fl4paint

FL4SHK's Paint Program

This is my second attempt at making a sprite paint program, but this time
it's not geared specifically towards the GBA.

My goal with this program is to make an enhanced clone of Usenti, which is
what I've been using so far to make most of my sprites.

For now, I'm going to shoot for support of paletted PNG images, with easy
ability to change the palettes.


## Motivations
While I really like Usenti, it's not open source, so there's no simple way
to tailor it to applications besides its original intended ones.

Usenti is also a 32-bit x86 Windows program, which means it won't easily
run on other architectures.  It at least runs well in Wine, which is how
I've been able to use it so far.


## Enhancement Ideas
* The ability to support both 15-bit RGB and 24-bit RGB colors.  Usenti only
appears to support 15-bit RGB because of its intended use case (GBA
graphics).
* The ability to support palettes with arbitrary numbers of colors
* The ability to support sub-palettes of arbitrary sizes
* The ability to have multiple tile grids at a time
* The ability to use an arbitrary color index as the transparent color for
transparent PNG support.
* Inherently cross platform.  fl4paint should work correctly on multiple
OSes and computer architectures.
* For paletted images, the ability to move colors around the palette with
ease.
