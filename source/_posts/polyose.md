---
title: Polyose
layout: project
subtitle: A dual joystick shooter where each enemy you destroy adds armor to your ship, making you harder to kill but easier to hit.
date: 2017-12-03 12:00:00
tags: [project, dev, design, games]
thumbnail_image: polyose-screenshot-screenshot-background.png
screenshot_1: polyose-screenshot-1.gif
screenshot_2: polyose-screenshot-2.png
screenshot_3: polyose-screenshot-3.png
secondary_button_text: itch.io
secondary_button_link: https://dylanilvento.itch.io/polyose
background_rgb: rgb(69,69,69
made_using: [unity, illustrator]
---
Made for [Ludum Dare 40's](https://ldjam.com/events/ludum-dare/40/polyose) theme of "The More You Have, The Worse It Is," _Polyose_ is a traditional dual joystick shooter with a bit of a twist: every enemy ship you destroy causes them to blow apart into a multitude of armor shards, allowing you to vacuum them up and attach them to your ship, increasing your overall health. However, each shard you pick up increases your overall size, making you easier to hit.

I implemented a traditional dual joystick control layout, with movement mapped to WASD and shooting mapped to the arrow keys. I had to create a small enemy AI system, where enemy ships follow and fire at you if you’re within a minimum and maximum range, taking into account the changing size of your ship as you grow. This was also my first time experimenting with Unity’s LineRenderer component, adding a trailing line to the player ship as it moved.