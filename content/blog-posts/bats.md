+++
date = 2023-12-01T00:00:00Z
hero = "/images/bats-hero.jpeg"
project_tags = ["Acoustic Ecology","GIS", "Data Sonification", "Game Design"]
title = "Sharing Space with Copenhagen’s Bats"
type = ""

+++
What if we could explore our surroundings as a bat? What do our favorite landmarks sound like when mapped out in echolocation? Might this re-orient our approach to  sharing urban spaces with the more-than-human world? Using sound, this project aims to expand our sense of kin, to understand how design influences urban wildlife.

Field research for this project was conducted under mentorship from Copenhagen Municipality Bat Consultant Inger Kærgaard, MSc. Bat sounds collected by prior students in Inger's bat research group. All other work by me, in community with peer researchers. 

# Part 1: Bats at the Roundtower

![](bats-roundtower.jpg)

[Launch the experience](https://roundtower.jasperkatzban.com/)

This project features bat echolocation sounds sampled at Copenhagen’s Roundtower using ultrasonic mics, slowed to the range of human hearing. I used the Web Audio API to separate and map sounds to a quadraphonic setup of 4 Bluetooth speakers. Live visuals generated in p5.js software.

# Part 2: Flagermusikby — City of Bat Music

![](bats-city.jpg)

[Explore the city with sonar](https://bats.jasperkatzban.com/) (WIP)

What does a Copenhagener’s favorite street sound like in bat sonar? Combining a map of the city with research on urban bat behavior, this experience invites you to explore how urban design choices affect bats’ navigation through their musical calls.

# Process
The development of this experiment thus far has been a fun process. Initially, I knew I wanted to create something that could engage others more interactively than a paper, and with more visual appeal than a conventional data visualization. A website is a blank canvas that has the potential for both, and so much more: a game, a story, a body of research blended together without the constraints of other traditional formats. Field research into bats behavior around Copenhagen combined with analysis of field recordings of their vocalizations serve as the basis for this experience. In essence, Copenhagen’s bats understand their surroundings through echolocation. The mental map they build is certainly different from what we’d expect in something like Google Maps, but their goals are largely the same: find others and find food. Thus, this experience blends these ways of knowing the world into an abstract but recognizable journey through Copenhagen.

# Tech 
This project is built as a web experience, which is to say it is designed to run in a browser like Chrome or Safari. Though not mobile optimized (yet), the potential for social interactions with others in the world is vast considering most Copenhageners have a smartphone or tablet. Built in TypeScript, this web app uses Rapier for physics simulation, Three.js for rendering, and the Web Audio API for sound generation. With this tech stack, it’s a basic proof of concept for a more developed web experience – one I’d like to continue developing beyond the end of this program.

# What’s Next?
A joy of projects that are not-quite-science and almost-art is the amount of creative liberty available. While the sounds, places, and interactivity of the experience is inspired by the way urban bats explore the world, the web game format makes it possible to add aspects like color and custom sounds to the mix. Rather than a geographical map of Copenhagen, one can explore a compressed version of the city which features key landmarks but leaves out repetitive street spaces. In fact, the map used is a version of that used in the 2D platformer game Ynglet, which takes place in Copenhagen and has a similar gameplay experience. With this map format, I’m still working out how much educational text to include and, more broadly, how to structure a storyline that takes you on a journey towards conservation through your own authentic exploration.