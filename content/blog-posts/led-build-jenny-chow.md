+++
date = 2019-10-01T00:00:00Z
draft = true
hero = "/images/jennychow/jennychow-15.jpg"
project_tags = ["Electronics", "Sculpture"]
title = "LED Build: Jenny Chow - t"

+++
# Goal

Our goal is to make the circuits function as dynamic visual elements in the set, such that they can change color, perform basic animation, and add to the scenic appeal overall. While more advanced effects could be achieved with more advanced fixtures, the following outlines a simple and lower budget option that still allows for the control of each individual circuit trace.

# Design

![](/images/jennychow/jennychow-diagram-01.png)   |   ![](/images/jennychow/jennychow-diagram-02.png)
:-:|:-:


Based on 

* 34 individual ‘circuits’
* 102 channels total (34 * 3 for Red, Green, and Blue)
* Rough total LED length of 43 m
* Power draw of .6A / m over \~43 m = 25.8A total max
* Can limit power to < 25A or about 80% of max brightness so that existing 25A power supply can be used safely

![](/images/jennychow/jennychow-diagram-03.png)

The power / data topology is set up like a tree - a single power source splits off to the three decoders, which interpret a DMX signal and then output power for each strip of LEDs.

These decoders are connected to each circuit individually, with 12 LED strips (36 channels total for R, G and B) per decoder. When the rig was installed, the set was still under construction, so I designed this setup for easy disconnect

# Build

![](/images/jennychow/jennychow-01.jpg)

![](/images/jennychow/jennychow-03.jpg)

![](/images/jennychow/jennychow-04.jpg)

# Installation

![](/images/jennychow/jennychow-05.jpg) | ![](/images/jennychow/jennychow-08.jpg)
:-:|:-:

![](/images/jennychow/jennychow-06.jpg)

![](/images/jennychow/jennychow-07.jpg) 

![](/images/jennychow/jennychow-09.jpg)

![](/images/jennychow/jennychow-10.jpg)

![](/images/jennychow/jennychow-11.jpg)

# Break a leg!

![](/images/jennychow/jennychow-16.jpg)![](/images/jennychow/jennychow-12.jpg)![](/images/jennychow/jennychow-15.jpg)