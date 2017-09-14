---
layout: post
title: "Residency Report: Marije Baalman and Chrysalis"
categories: blog
tags: [emutelab, event, machine learning, live coding]
author: Chris Kiefer
date: 2017-09-14
---

For the past six days, <a href="https://www.marijebaalman.eu">Marije Baalman</a> has been visiting Sussex for part one of a residency with by EMuteLab and Sussex Humanities Lab.   We've been exploring serendipity in mappings for interactive instruments, and focusing on her recent piece <a href="https://www.marijebaalman.eu/projects/chrysalis.html">Chrysalis<a>.

Chrysalis is a cocoon like instrument made from stretch fabric and poles. You climb into the structure, and when you move around, the wireless accelerometers and stretch sensors (using Marije's SenseStage system) are mapped to sound and to RGB lights which light up the chrysalis.  Marije wanted to explore new mappings which were less predictable and more engaging to interact with, while at the same time, did not risk moving into modes that were too random or out of keeping with the broad aesthetics of the piece.  Following from some of my <a href="https://sro.sussex.ac.uk/51860/1/NIME2014-ESN.pdf">previous work using Echo State Networks</a> to create complex mappings, we explored Jaeger's more recent innovations in this area, using a new technique: <a href="http://minds.jacobs-university.de/conceptors">Conceptors</a>.  

Conceptors essentially capture modes of behaviour of a reccurrent neural network, after which they can be used for pattern generation and for sequence recognition.  When used for pattern generation, they have some very interesting properties: you can mix and morph between patterns and also extrapolate new pattern variations.  This fitted in really well with our aim of encouraging interesting variation in mappings, while staying within a broader aesthetic.  Conceptors allow the creation of new and interesting pattern variations, but without moving too far from the original pattern. In other words, we can create surprises without the risk of them being too surprising.  The addition bonus is that these patterns are generated in real time, and can interact intuitively with sensors. We mapped them to control lighting patterns, and also used the network activations as wavetables to synthesise sound.

Another innovation was to adapt conceptors for realtime sequence recognition.  This worked successfully with accelerometer data. The way in which conceptors can be used with boolean logic make them a very powerful tool for pattern classification which we will be exploring more before Marije returns for part 2 of her residency in January.





![Chrsalis](/img/chrysalis2.jpg)
![Chrsalis](/img/chrysalis3.jpg)
![Chrsalis](/img/chrysalis_shl_lightson.jpg)
![Chrsalis](/img/chrysalis-diag.jpg)
