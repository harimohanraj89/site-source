---
layout: post
categories: audio
title: Virtual Guitar Processor
---

<a class="imglink" href="/images/virtualgp.png" target="_blank">
	<img id="virtualgpimage" class="large boxsize" src="/images/virtualgp.png"/>
</a>

This virtual guitar processor was the product of the final project assignment in
my Advanced Digital Signal Theory class. The class was dedicated to learning the
implementation of common musical effects from scratch. hence, for the final
project, I decided to consolidate all we had learned into a single PureData
patch that would serve as a virtual guitar processor.

The guitar processor implemented the following features.

* Distortion: A choice of sinusoidal, polynomial, or diode-modeled distortions
* Equalization: A 3-band parametric equalizer, with two shelf bands and a peak band in the middle
* Effects: A parametric effects rack, providing vibrato, flanger, chorus, doubling (like a slap-back echo)
* Delay: A parametric delay, with wet volume and feedback control
* Reverb: A reverb engine using a feedback delay network, with wet volume and reverb time control

The header image on this page looks pretty, but the sad reality of PureData (vs
MaxMSP, for example) is the absence of a presentation mode. Hence, the actual
patch looked something like this.

<a class="imglink" href="/images/virtualgpdetailed.png" target="_blank">
	<img id="virtualgpdetailedimage" class="boxsize" src="/images/virtualgpdetailed.png"/>
</a>

However, I was able to produce some cool sounds with this patch (mainly using my
bass guitar) and even used it for a live performance in a Distributed
Performances class.

<a class="distinct" href="downloads/VirtualGP.zip">Download the patch</a>
