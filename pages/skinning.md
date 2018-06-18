---
layout: page
permalink: "/help/"
path: "help"
css: "skinning"
title: "Skinning guide"
---
> Page is in rewriting
## Sections
- [Simple skin layout](#simple-skin-layout)
- [Complex skin layout](#complex-skin-layout)

## Simple skin layout
The simple skin layout uses the pre-1.8 skin template and is a good place to start if you have little or no experience making Mine Little Pony skins. Basic components like the head, hair, arms, legs and torso are kept in the same place and non-human parts such as the horn, wings, ears and extra textures are squeezed into unused areas. Below is a scaled-up and labeled template of Mine Little Pony skin

The blue pixels in the upper left corner are trigger pixels, read more about them below

> **T** - top, **BT** - bottom, **F** - front, **B** - back, **R** - right, **L** - left

![Simple skin template]({{ '/assets/skinning/simpletemplate.png' | relative_url }})

A comparison between a standard definition (SD) Twilight Sparkle skin and the default Steve skin shows where the extra parts go:

{:.images}
![Twilight Sparkle simple skin layout]({{ '/assets/skinning/twilight_simple_template.png' | relative_url }})
![Steve simple skin layout]({{ '/assets/skinning/steve_simple_template.png' | relative_url }})

{:.button}
[Download Twilight Sparkle simple skin]({{ '/assets/skinning/twilight_simple.png' | relative_url }}){:.download-button download="TwilightSparkle_simple.png"}

> The foreleg and hind leg textures are mirrored for the other side of the body as well as the body side textures. For more detailed skins, pay close attention to how some textures are flipped and mirrored around the player model. Use the guide below to see how body textures are matched up. Red color marks flipped textures
![Flipped textures of the body]({{ '/assets/skinning/flippedtextures.png' | relative_url }})

## Complex skin layout
As of Minecraft 1.8, skins now have an extra layer all over the body as opposed to just the head. This means that player models can now have sleeves and pants. The complex skin layout is twice the size of the older layout with a dimension of 64x64 pixels whereas the old layout is sized at 64x32 pixels. Blue color marks the extra layer of texture

![Complex skin layout]({{ '/assets/skinning/complextemplate.png' | relative_url }})

> As far as making skins for Mine Little Pony is concerned, the process remains the same for most part. It is important to note that leg textures are no longer mirrored, all legs now have their own texture space. Also left and right legs have different sides that face outward as well as sides that face inward; simply copying right leg textures to use on the left side won't work

![Twilight Sparkle complex skin layout]({{ '/assets/skinning/twilight_complex_template.png' | relative_url }})

{:.button}
[Download Twilight Sparkle complex skin]({{ '/assets/skinning/twilight_complex.png' | relative_url }}){:.download-button download="TwilightSparkle_complex.png"}

> Notice the bottom leg textures and how their faces are differently positioned. For right legs, the faces are, from left to right, inward > front > outward > back whereas left leg faces are inward > front > outward > back\\
> Body alignment is the same as the older skin layout

> Download the converter to quickly convert skins and resource packs to the new format\\
> Later versions of the mod will convert textures for you. The converter is not needed to simply use the old skins\\
> \\
> [Download converter]({{ '/assets/files/SkinConverter-1.0.1.jar' | relative_url }}){:.download-button}