+++
date = 2019-10-01T00:00:00Z
draft = true
hero = "/images/jennychow-hero.jpg"
project_tags = ["Electronics", "Sculpture"]
title = "LED Build: Jenny Chow"

+++
# Design

The power / data topology is set up like a tree - a single power source splits off to the three decoders, which interpret a DMX signal and then output power for each strip of LEDs. 

These decoders are connected to each circuit individually, with 12 LED strips (36 channels total for R, G and B) per decoder. When the rig was installed, the set was still under construction, so I designed this setup for easy disconnect 