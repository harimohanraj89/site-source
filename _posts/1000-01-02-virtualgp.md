---
layout: post
categories: music audio
title: "Virtual Guitar Processor"
thumb: "/images/virtualgp.png"
blurb: "A software guitar effects rack, including distortion, EQ, reverb, and
				delay based effects. Built in PureData."
---

{% include image.html path="/images/virtualgp.png" size="large" %}

This virtual guitar processor was the product of the final project assignment in
my Advanced Digital Signal Theory class. The class was dedicated to learning the
implementation of common musical effects from scratch. hence, for the final
project, I decided to consolidate all we had learned into a single PureData
patch that would serve as a virtual guitar processor.

The guitar processor implemented the following features.

* Distortion: A choice of sinusoidal, polynomial, or diode-modeled distortions
* Equalization: A 3-band parametric equalizer, with two shelf bands and a peak
	band in the middle
* Effects: A parametric effects rack, providing vibrato, flanger, chorus,
	doubling (like a slap-back echo)
* Delay: A parametric delay, with wet volume and feedback control
* Reverb: A reverb engine using a feedback delay network, with wet volume and
	reverb time control

The header image on this page looks pretty, but the sad reality of PureData (vs
MaxMSP, for example) is the absence of a presentation mode. Hence, the actual
patch looked something like this.

{% include image.html path="/images/virtualgpdetailed.png" size="large" %}

However, I was able to produce some cool sounds with this patch (mainly using my
bass guitar) and even used it for a live performance in a Distributed
Performances class.

<a class="distinct" href="/downloads/VirtualGP.zip">Download the patch</a>
