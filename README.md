# Igloo64 #

PCB design to adapt a 64-pin TQFP part to a standard solderless breadboard.

VERY MUCH A WORK-IN-PROGRESS AND NOT TESTED BY MAKING A PCB YET.

## The Problem ##

Many modern chips are only available in surface-mount packages.
Some have the audacity to have 64 pins, and not only that, pins on all four sides.
How can we make such a package fit onto a standard solderless breadboard?

## The Solution ##

This PCB design mounts the SMD part on a vertical board that plugs into a second board
that fits on the breadboard.
The vertical board has a rounded top, reminiscent of an igloo, hence the name.

## KiCad ##

This design has been created using the Open Source CAD package KiCad, V6.0.

To install it on Ubuntu Linux:

`sudo apt install kicad`

To make the snazzy 3D rendering work, install the additional package:

`sudo apt install kicad-packages3d`

I'm using Ubuntu 22.04 LTS which gives me KiCad V6.0.
As I write this, the latest KiCad is V7.0,
so I expect I'll upgrade when the next LTS release comes out.

## PCB Screenshot ##
![PCB screenshot](Igloo64_pcb.png "PCB screenshot")


