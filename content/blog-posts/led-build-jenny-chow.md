+++
date = 2019-10-01T00:00:00Z
draft = true
hero = "/images/jennychow/jennychow-15.jpg"
project_tags = ["Electronics", "Sculpture"]
title = "LED Build: Jenny Chow - t"

+++
During my first semester at Olin College, I had the pleasure to design and build a custom lighting rig for the production "The Intelligent Design of Jenny Chow" at Babson's Sorenson Theater.

From start to finish, this project was a fantastic learning experience. I was thrilled to intersect my passion for theatrical tech and my interest in LED fixture design in way that others could see.

# Goal

The circuits serve as Jenny's cyber connection to the outside world, changing color and mood depending on who she's talking to throughout the show. Thus, it was crucial that I make the circuits function as dynamic visual elements in the set, changing color, performing basic animations, and adding to the overall scenic appeal.

# Design

Working with the lighting designer, technical director, and scenic designer, the design for the circuits was conceptualized as tendrils flowing out from Jenny's bedroom.

![Scenic Design by Jenna McFarland Lord](/images/jennychow/jennychow-diagram-0.jpg)
<div align="center">Scenic Design by Jenna McFarland Lord.</div>

![](/images/jennychow/jennychow-diagram-02.png)
<div align="center">Map of circuits and groupings.</div>

While more advanced effects could be achieved with more addressable LEDs or more expensive fixtures, I chose cheaper analog strips which still allowed each circuit trace to be controlled individually.

The LEDs are quite bright compared the rest of the set, so to get away with a smaller power supply, I limited power to 25A or about 80% of the circuits' max brightness.

Based on this arrangement, I designed for the following specs:

    - 34 individually controllable circuits
    - 102 channels total (34 * 3 for Red, Green, and Blue)
    - about 43 m of LEDs
    - Power draw of .6A / m over ~43 m = 25.8A total max

![](/images/jennychow/jennychow-diagram-03.png)
<div align="center">Power and data topology.</div>

The power / data topology is set up like a tree - a single power source splits off to the three decoders, which interpret a DMX signal and then output power for each strip of LEDs.

These decoders are connected to each circuit individually, with 12 LED strips (36 channels total for R, G and B) per decoder. When the rig was installed, the set was still under construction, so I designed this setup for easy disconnect

# Build

![](/images/jennychow/jennychow-01.jpg)

![](/images/jennychow/jennychow-03.jpg)

![](/images/jennychow/jennychow-04.jpg)

# Installation

![](/images/jennychow/jennychow-06.jpg)

|  |  |  |
| :---: | :---: | :---: |
| <div align="center">Heatshrink Joints</div> | <div align="center">Wire routing</div> | <div align="center">Hidden Connectors</div> |

![](/images/jennychow/jennychow-11.jpg)

# Break a leg!

![](/images/jennychow/jennychow-16.jpg)![]
<div align="center">My view from the lighting booth</div>

(/images/jennychow/jennychow-12.jpg)![](/images/jennychow/jennychow-15.jpg)
<div align="center">My view from the lighting booth</div>
