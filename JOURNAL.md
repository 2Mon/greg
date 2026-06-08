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

# April 27 - Belt Tensioners

This part was a struggle, and I'm still not happy with it, but im tired and need a break from cad so, here we go. The belt tensioners on this printer need to be able to clamp both ends of the belt, with one being able to be pulled to increase tension with a screw. I did this by looping one of the belt ends around a screw (the same one that holds the part down to the carriage), and the other one gets wedged into a belt tensioner setup. It was really difficult to fit both of these in the tiny carriage assembly, but it was kinda needed to keep this compact. 

I was inspired by Splendacross and K3, as well as Parker's tiny cross gantry. These are really clean designs and I was very impressed by how compact they are. I may end up redesigning some parts to make it easily CNC machinable. 

<img width="308" height="356" alt="Screenshot 2026-04-26 at 9 05 54 PM" src="https://github.com/user-attachments/assets/3c4eed36-f5d9-47fc-a167-5754fd2afd88" />

I went through about 12 iterations before landing on what you see above. It was really difficult to be able to fit all the parts of the tensioner into the small size. 

I need to put one of these on each of the belts. The cross rails will go on top of these. yay!

**Total time spent: 5 hours** 

# Cross Rails - April 26-27 (time is not real anymore)

The cross rails on this printer are fairly simple so far. They are currently steel plates, 6mm thick, with pockets cut in them to save weight. The point of these backers is to improve the rigidity of the whole printer, as well as counteracting thermal expansion from the rails. Currently the X rails are mounted between a spacer and the belt tensioner, and the Y rail is mounted on top of the belt tensioner. Right now the two rails are colliding with eachother. sub optimal! I need to figure out a better solution, but overall its not bad so far. Looks nice and rigid. 

<img width="628" height="648" alt="Screenshot 2026-04-27 at 7 57 04 AM" src="https://github.com/user-attachments/assets/eb16f3a1-5070-44ad-803d-5d880b490b94" />

**Total time spent: 5 hours** 

# Motor + Belt Changes - June 7 

Casually took a break from this project for like over a month but were back! I made a couple changes to basically every part of this printer. 

First, I changed basically everything with the motor mounts. I discovered these cool pulleys with set screws that have the same form factor as idlers. This lets me run 9mm belts on this machine! very cool very swag. 

Here you can see how those motor mounts actually work with the new pulleys as well as the thicker 9mm belts. Looks really nice IMO!

<img width="191" height="206" alt="Screenshot 2026-06-08 at 12 32 07 PM" src="https://github.com/user-attachments/assets/49e71f0b-136d-4851-8f24-b4f3ad2b134c" />

Second, I changed the way that the mounts actually connect to the motors. Im using these nicer more slim motor mounts which ill get milled out of aluminum. This gives me more room for the cross rails (more on that later). This block connects to another block which connects to the halo. 

<img height="300" alt="Screenshot 2026-06-08 at 12 33 23 PM" src="https://github.com/user-attachments/assets/659b94c4-3199-4788-9f02-9f2e1ac92ecc" />

When I changed the belts, I also had to change the belt clamps. Here they are now. The weird cutout on the side is so that the other side of the belt is able to go past the clamp without it colliding. Im not sure if I want to split these into two parts for CNC machining or if printing them is fine. One advantage of machining them is that its a lot more rigid but it would also add a lot of extra cost, as well as probabl lead to slightly worse print quality because every imperfection gets transfered into the cross rails instead of being absorbed.
<img width="200" alt="Screenshot 2026-06-08 at 12 35 54 PM" src="https://github.com/user-attachments/assets/73d7f41d-8641-4e35-a3e2-b6739a28ffc1" />

**Total time spent: 5 hours** 

# Cross Changes - June 7

There are a couple changes I made to the cross rails themself too. Now, one of them is upside down. This reduces the distance between them, while allowing for higher rigidity in the toolhead. Previously the toolhead needed to be some weird SLM stuff with different heights but now since the rails are exactly 4mm apart I can just use a single 4mm sheet of aluminum. I can also mount the hotend to this piece. YAY!

<img width="400" alt="Screenshot 2026-06-08 at 12 41 00 PM" src="https://github.com/user-attachments/assets/991be2ae-dfb4-4536-ae86-126642259239" />

Here you can see how that looks in practice. To get here I had to change the dimensions of most of the parts to get everything to fit. 

<img width="300" alt="Screenshot 2026-06-08 at 12 41 39 PM" src="https://github.com/user-attachments/assets/c9e62e8a-c78f-4eba-b9f1-c357d22d3c23" />

And this is the toolhead itself. I need ducts. thats gonna be painful. :(

**Total time spent: 4 hours** 

# Frame - June 8

This part was pretty simple. I basically just took a second halo, slapped it on the bottom, and put some extrusions to conenct it. The extrusions are misumi HFS5-404020, which are these cool corner pieces. Yay. 

<img width="524" height="676" alt="Screenshot 2026-06-08 at 12 44 08 PM" src="https://github.com/user-attachments/assets/6232fb81-a091-4b0d-892c-cee1562c39b0" />

And here you can see the current printer, complete with banana for scale. YAY. 

**Total time spent: 4 hours** 


