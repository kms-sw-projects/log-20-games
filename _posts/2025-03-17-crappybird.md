---
title: Crappy bird logbook
layout: default
toc: true
---

<h1>Crappy bird</h1> 

{% toc %}

The second game to be made as part of the 20 games challenge is **Flappy Bird**, which I slightly rechristened to *Crappy Bird*.
More specific information can be found [here](https://20_games_challenge.gitlab.io/games/flappy/).

<h2>Overview</h2>
In principle the game contains only three things:
A bird that is flying left to right, and can be made to fly a little bit up, while being otherwise exposed to gravity.
Pairs of pipes that spawn on the right side of the screen, with a gap between them. The bird has to fly "in between" each pair of pipes, and gets one point for each pipe it has managed.
Lastly, there is a "scrolling" background that gives the illusion of movement.

My game looks like this:

**Main menu screen**



**Actual ingame screen**


<h2> Implementation</h2>

<h3> Getting started: A new project</h3>
To start we create an empty Godot project that we call Crappy Bird. I use the legacy renderer for hardware reasons (my dev device is too old for the vulkan renderer).