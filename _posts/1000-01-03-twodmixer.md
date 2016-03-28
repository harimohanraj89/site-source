---
layout: post
categories: music audio
title: "Two Dimensional Mixer"
thumb: "/images/thumbtwodmixer.png"
blurb: "A two-dimensional mixer that blends four separate audio sources. Built
				in PureData."
---

{% include image.html path="/images/thumbtwodmixer.png" size="large" %}

This two dimensional mixer was the product of the final project assignment in my
Advanced Game Audio class. The class was dedicated to learning the sound design
and implementation aspects of popular video game engines such as Unity3D and the
UnrealEngine. This two-dimensional mixer is mockup of a possible sound design
tool to blend various sound sources to form a convincing sound for a game object
(for example, to model the sound of a crowd at a football game).

The blue XY-pad is the mixer, which is manipulated with the mouse. The user can
choose between various panning methods, such as equal power or equal gain. There
are individual channel controls (gain, solo, mute, play, pause) for each of the
four audio sources. Another cool feature of this patch is that it has a
framework to communicate via UDP, so in theory, it can be controlled remotely.

The header image on this page looks pretty, but the sad reality of PureData
(vs MaxMSP, for example) is the absence of a presentation mode. Hence, the
actual patch looked something like this.

{% include image.html path="/images/twodmixerdetailed.png" size="large" %}

The patch is available for download below, if you feel like taking this patch
for a ride. The download also contains some sample audio to get up and running.
Remember, all user controls are in red!

<a class="distinct" href="downloads/TwoDMixer.zip">Download the patch</a>
