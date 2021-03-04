---
title: Analog Modeling Synthesizer
date: May, 2018
type: ''
hero: "/images/synth-hero.jpg"
author: Allen Ginsberg
project_tags: []
draft: true

---
Since a young age, I've had a fascination with electronic music and audio - I could nerd out to you for hours about the ways sound travels through space, why your headphones don't sound as good as they could, and how you're probably missing out on lots of audio fidelity in your day to day music listening.

As a casual musician, I'd always been interested in the science of audio and why things sound they way they do. After years of experimentation in Logic Pro with various music creation tools, I knew I wanted to create my own. With my growing interest in electronics and engineering, I figured that building my own synth would be a fun exploration into the inner workings of the musical devices that continue to amaze me.

![](/images/synth-1-s-copy.jpg)

Using the [Mozzi](https://sensorium.github.io/Mozzi/) sound synthesis library on an [Arduino Mega](https://store.arduino.cc/usa/mega-2560-r3), I designed and built a simple digital analog modeling synthesizer complete with 4 waveforms, a filter, vibrato, an envelope, and an LFO. Housed inside a cheap wooden box from the crafts store, this quirky little sound box comes in at a fraction of the cost of commercial synthesizers, but sacrifices much the sonic fidelity and reliability found in the state-of-the-art products out there.

![](/images/synth-2.jpg)

Check out this brief presentation for some basic sound synthesis info and an overview of the project:

<iframe src="[https://docs.google.com/presentation/d/e/2PACX-1vS-mpK0e4ZErw582ndguATDY4TfpFGlfao0bSU5eKwLv8crZvyeopRxYaiwYD1IpnGmK8W1GwCS8Qkl/embed?start=true&loop=true&delayms=5000](https://docs.google.com/presentation/d/e/2PACX-1vS-mpK0e4ZErw582ndguATDY4TfpFGlfao0bSU5eKwLv8crZvyeopRxYaiwYD1IpnGmK8W1GwCS8Qkl/embed?start=true&loop=true&delayms=5000 "https://docs.google.com/presentation/d/e/2PACX-1vS-mpK0e4ZErw582ndguATDY4TfpFGlfao0bSU5eKwLv8crZvyeopRxYaiwYD1IpnGmK8W1GwCS8Qkl/embed?start=true&loop=true&delayms=5000")" frameborder="0" width="100%" height="400px" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

This project is far from complete - and I'd say this is only the start of my work in audio hardware. Future work includes optimization of the audio generation for smoother playback, utilizing the display for feedback and navigation, and adding MIDI over USB. I'd love to program a mini OS complete with user writable presets, configuration remapping, random preset generation. Stay tuned for future updates!