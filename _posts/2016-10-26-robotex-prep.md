---
title: "Robotex 2016 prep"
author: Lauri Võsandi <lauri.vosandi@gmail.com>
categories:
tags:
layout: post
---

There is 5 weeks to go until Robotex 2016 and we've got
two robots more or less ready to go for software development.
Nice job on the second bot Joosep & Daniel.

<img src="/assets/img/bots.jpg"/>

We used eight PS3 eye cameras per robot with 3D printed mounts. Nice job Marek -
the last one was pretty much perfectly aligned.
With 4 USB hubs we can grab 30 frames per second at 3840x640 resolution
and it's ridiculously cheap for that resolution compared to the
widely used industrial cameras.

<img src="/assets/img/ui.png" style="max-width:100%;max-height:100%; display:block;"/>

For driving the DC motors we use our homemade H-bridges which this year
have been adapted to be used as [Arduino shields](https://github.com/eik-robo/bridgeino).
Thanks to Frank, Madis, Krista, Nika and others who bothered to show up for the soldering workshops
and actually managed to solder pretty descent H-bridges :)

<img src="https://raw.githubusercontent.com/eik-robo/bridgeino/master/doc/top.png" style="max-width:100%;max-height:100%; display:block;"/>

For the kicker electronics we use old-school Nixie power supplies, capacitor and
Arduino relay board. Kicker's mechanics is the most esoteric piece of hardware,
we're just going to stick to the ones made previously.

Batteries have been replaced with LiFePO4 packs to prevent hazardous fires
and 4 cells incidently fit our i5 motherboards so we don't need step-up or step-down converter for the motherboard.
To prevent glitches in the electronics we have separate battery packs - one for motherboard and other one for motors and inducutors.
Thanks to Arthur & Kaarel for soldering the remaining cells and
also repairing our cordless drill battery packs :)

Image recognition is shaping up and we've got a clue where we are on 
the field thanks to Fred.
Joosep & Daniel also set up cameras to record the field so we have reference
point for the calculations we make using on-board cameras.
Perhaps even one day we can apply machine learning algorithms on those measurements ;)

<img src="/assets/img/imgrec.png" style="max-width:100%;max-height:100%; display:block;"/>

The plywood/MDF boards shall be replaced with milled aluminium sheets and
I guess we need to come up with some elegant way to hide the robot's guts but
other than that the last step is to give the robots some character, make them play football and
test-test-test.
If you think that might be something you're into just pop in on Thursday 18:00
at Estonian IT College room 412! Free pizza to all contributors :)
