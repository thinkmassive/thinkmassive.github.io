---
layout: post
category : projects
tagline: "Boomboxen prototype"
tags : [hardware, electronics, woodworking, music, audio]
---
{% include JB/setup %}


Last weeekend I assembled a working prototype, and it's been used a few hours at a time in various settings since. The sound is impressive, especially at moderate volume. There's some background noise that I'm still trying to track down, hopefully just the low quality amplifier. Originally I planned to have a USB outlet in parallel with the amp, but the interference is much worse with both audio and USB power connected to the source, so I'll need a workaround.

I'm surprised how long a single 5Ah battery lasts with the class A/B amp, and the class D should improve it significantly. For that the batteries will be in series to create 24V. Until then I had planned to run the batteries in parallel, but I might keep it simpler until then and just switch between the batteries, which I'll describe more below. This week I'll take some measurements over time to generate a baseline power profile.

The enclosure turned out a little less clean than I was hoping but it still serves its purpose, and I like the way it looks. I'm debating whether to bevel/round the edges and attach corner protectors.

## Construction Photos
<iframe class="imgur-album" width="100%" height="550" frameborder="0" src="//imgur.com/a/q6fqA/embed"></iframe>

## Up next
In the short term I'll expose the following so the back panel can be attached:

### Connectors
 - 3.5mm stereo audio input
 - 12V lighter socket
 - 5V USB socket

### Switches
 - SPST: Amp remote (on/off)
 - DPDT: Amp power (battery 1/2)
 - DPDT: Aux power (battery 1/2)

The Aux switch will determine which battery is connected to the 12V & 5V sockets, and an external 12V source can be connected for charging the boombox. Once I have the class D amp I plan to make a control panel that slides into a cutout on top. That will provide a nice volume, rather than always running at full throttle and depending on the source to regulate volume to a tolerable level. It's going to need some kind of handle too.
