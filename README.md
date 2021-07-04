# Dog Poop Bag Dispenser

Design is on https://www.thingiverse.com/thing:4899209

## Overview

Designing a dog poop bag dispenser.

After trying a few dispensers out on the market, I decided to
try designing my own. A few of the challenges I faced with dispensers 
I've owned:

* Cap falls off the container.
* Ring can be small for certain leash clips.
* Ring snaps off container.
* Difficult to grab first bag through opening.
* No way to know how much of the roll is left without opening the container.
* Oversized container, making the roll shake when moving.

The design is an attempt to address all of these challenges. It also provides the
opportunity to engrave the container with your pet's name!

![dog-dispenser-gif](https://user-images.githubusercontent.com/6743515/124319785-c7bb4800-db48-11eb-86ee-648e45dda4b9.gif)

<img src="https://user-images.githubusercontent.com/6743515/124312076-be2be300-db3c-11eb-81c5-5ee2d98367aa.PNG" width="300"><img src="https://user-images.githubusercontent.com/6743515/124312068-bb30f280-db3c-11eb-8bfa-4cc88c3df2ac.PNG" width="300">

## Usage
You can adjust the scad file to customize the design to your own needs. The following parameters
are particularly relevant:

* `diameter` - inner diameter (mm) of container.
* `opening_width` - width (mm) of opening for bags.
* `name` - name to engrave. 
* `additional_line` - additional line to engrave.

Use OpenSCAD a export objects to stl. You need to print two parts, a lid and a container. 
Using the customizer change Expert -> part to "Container" and export to stl.
Using the customizer change Expert -> part to one of the lid options, my personal preference
is "Lid - Vertical Knurled" and export to stl.

Recommended settings for printing are:

* `infill` - 20%
* `layer_height` - .2 mm
* `supports` - yes

## Credits

This holder was designed off a base container.
Original container from https://www.thingiverse.com/thing:612709.
