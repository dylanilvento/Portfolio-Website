---
title: Amalgama
layout: prototype
subtitle: A 2D hack-and-slash platforming prototype where you fight elemental imps and collect resources.
date: 2016-09-02 12:00:00
tags: [prototype, dev, design, games]
thumbnail_image: amalgama-screenshot-background.png
screenshot_1: amalgama-screenshot-1.png
screenshot_2: amalgama-screenshot-2.png
screenshot_3: amalgama-screenshot-3.png
secondary_button_text: itch.io
secondary_button_link: https://dylanilvento.itch.io/amalgama
background_rgb: rgb(46,81,132
made_using: [unity, aesprite]
---
Made during [Ludum Dare 36](http://ludumdare.com/compo/ludum-dare-36/), _Amalgama_ is a 2D hack-and-slash game prototype where you play an alchemic monk that fights against elemental imps. Collecting the elementally-attuned stones that they drop, you would be able to craft stronger weapons and progress through each level based around the four classical elements.

_Amalgama_ was a good learning exercise for me to work on player combat that felt satisfying, like having the player and enemies being thrown back whenever they were hit. The sole level I built is also very large, with a lot of vertical and horizontal space, so in my game tuning I thought about how to make sure the player only paid attention to what was currently on screen and not too worried about what was off-screen. An example of that tuning is when I adjusted the duration of enemy projectiles before they destroyed themselves, as to make sure the player wasn’t shot unfairly from offscreen.