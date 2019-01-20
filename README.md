# What is this?

It's my project/attempt at recreating the first board used in C64 production.
It's based on a schematic by Ruud Baltissen

# How?
I got one of these boards without much components, all chips where gone (almost)
I then removed the rest and clean out all holes and got it scanned at a local copy shop
Initial i used sprint layout which has a feature to trace on top of an image
But i wanted a more "complete" soloution so i imported the copper layers in to kicad and 
managed trace on top of that. 
But the schematic was not the same as the board and i got help from Fredric QJ Blåholtz
adjustning the schematic to the board, it's a bit backwards but i trust the board more.

# Why?
I have been asked that a lot. One reason is that i have always liked the C64 and i
wanted to get more intimate with it. One thing i have truly learned is that QA and QC 
was not that much used 37 years ago, anything that worked was ok. So boards could differ 
even thou they had the same number. So i decided to just stick with making a replica of
what i had. The other reason is that i have a lot of time on my hands so i wanted to make
something that at some point will come in as usefull. These boards will at some point fail.
They where not robust made 37 years ago and either a hole will break loose from the board
or a track will crack. Having a source for a new board would then come in handy. Simply
pick a PCB house that you trust and send them the gerber files. Most have a minimum order
so you will never have a problem again.

# Status?
I have verified the board by printing out the tracks on paper and used a needle to poke
through and see if things match up. ie does very close but since paper under the real board
can move it will not be precise, but its as good i can do it.
I have also added some "eyecandy" in the form of 3d shapes of most things on the board. 
there are some things i cant find thou and my skills are not up to doing that from scratch,
but if anyone wants to chip in i need step/stp files for these parts:


Modulator ( i might recreate this one from ground up at some point )

Expansion port connector

7 & 6 Pin Din connecots

L4 (common mode chocke / noise filter)

Power switch

DB9 connectors

Trim pot R25 & R27


These parts i have but not in stp format and i need that to edit them more easy in F360, 
the legs of them do not line up with the holes and all i can do in kicad is scaling them
so they end up looking wrong. If there was a good guide on how to convert from wrl format
i would be going


C97-C100 & C20+C21

C10 & C11

C48 & C93

All resistors (have them as step's with correct color rings but they do no show up correct)

# Plan?
At summer 2019 i will order 5 boards as that is the minimum from Elecrow. I will then
during fall/winter buy and add components. Since the chips are the most expensive parts
it might be as far as early 2020 before i can power it up

# Working on right now?
Moving logo's to copper layer