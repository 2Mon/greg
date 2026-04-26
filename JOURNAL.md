---
title: "greg"
author: "1Mon"
description: "120mm build volume NEMA 14 cross gantry made to be extra compact. 220mm outer dimensions"
created_at: "2026-04-25"
---

# April 25 - Motor Stacks

I started this project with the motor stacks. I wanted to have a very compact way of putting a pulley and idler within the size of a nema 14, so I ended up just putting both on the motor shaft. This means that I needed to use motors with longer shafts, ie LDO 35STH52-2004AH (S35). These are very nice NEMA14s with 35mm long shafts. Unfortunately, the shafts themselves have a cutout. This may end up killing the idlers after a while, but luckily those are cheap. Overall not worried. 

<img width="153" height="363" alt="Screenshot 2026-04-26 at 11 51 51 AM" src="https://github.com/user-attachments/assets/9ef14e07-dd85-4553-b3d7-bc9a451a111e" />

You can see how the pulley and idler both run on the same shaft, which makes this ultra compact. I also have enough room for a small double shear bearing. nice. no more bent shafts! 
There were a couple iterations here. I had to make sure that the idler and pulley line up with eachother, as in the final design the belt needs to go between the pulley and idler. I have two variations, one with the idler on top and one with the idler on the bottom. This lets me actually belt this up. 

I also added a printed part that supports the motor and makes the spacing correct. Its a very simple part and I will probably change it to make it nicer eventually. 
Here you can see the whole thing, including the belt. 

<img height="300" alt="Screenshot 2026-04-26 at 11 55 06 AM" src="https://github.com/user-attachments/assets/ca3c6fe8-99a6-4da1-9407-e184d3ddac35" />

You can also see the double shear bearing mount. This is a steel part that screws into the halo (more info soon) and holds the bearing in place. I did this for two main reasons. 

1. I needed to raise the motor up a little to clear the belts. More info later
2. I wanted the bearing pockets to be seperate from the expensive halo. I dont want to mess up the tolerances on it. If something is wrong with the bearing pocket size, its easy to swap now. 

Overall really happy with how this part looks. I may explore ways to allow this to use 9mm belts in the future. 

**Total time spent: 5 hours** 

# April 26 - Halo Design

The halo is one of the most important parts of this printer. Its an inch of CNC machined steel. fun! I need to get this right or it will be a very expensive mistake. The halo mounts the motors, rails, and the rest of the frame. It needs to be steel because the mass of the halo helps to absorb vibrations and improve print quality. It also gives a super accurate surface for all parts to interface with, which helps a lot with getting everything aligned. 

The halo itself is fairly simple. It has mounting for the four motor pods, tapped holes for the rails, and a big hole through the center for the toolhead to move in. 

<img width="767" height="640" alt="Screenshot 2026-04-26 at 12 04 49 PM" src="https://github.com/user-attachments/assets/9e8f7fa7-05a2-4992-96c1-4d289554623a" />

Currently it weighs 5kg. The thickness may be a bit overkill, but the steel isnt actually that expensive. Ill see if i want to go down to 1/2 inch or something eventually. 

Next I added the rails and the motors to the halo to make sure everything fit correctly. There are still a ton of things that are subject to change as I develop the rest of the printer. I still need to add some mounting for a Z axis, as well as other various QOL things. 

<img width="876" height="711" alt="Screenshot 2026-04-26 at 12 07 31 PM" src="https://github.com/user-attachments/assets/b4752c55-dd74-4185-b3ea-67a0bf62946d" />

TO DO: 
Z Axis (maxwell coupling?)
Belt Clamps (k3 style)
XY Rails (no clue yet)
Toolhead (SLM probably?)

**Total time spent: 7 hours** 
