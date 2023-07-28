# ks_mazda_miata__e87
This is an Assetto Corsa car model that simulates a BMW 116i racing car that races in the 116 Trophy series of the 750 Motor Club.  The model is a modified version of the standard Assetto Corsa model of a Mazda Miata NA (MX-5).

## Install and Run
To install and run:
* Download the zip file
* Locate the Assetto Corsa root directory, e.g. `C:\Program Files (x86)\Steam\steamapps\common\assettocorsa`
* Unzip the download into `.\assettocorsa\content\cars` - you should then have a folder `.\assettocorsa\content\cars\ks_mazda_miata__e87-main`
* Remove the "-main" suffix from the folder name by renaming it to give a folder `.\assettocorsa\content\cars\ks_mazda_miata__e87`
* Start AC
* Click on Drive (Steering Wheel icon) and then the "Select a car" icon
* Click into the Mazda group and hover over Mazda Miata NA
* On the right a speedo icon with the letter C under it will pop up -> click on this icon
* You'll now see the spec for a car called BMW 116 Trophy but which looks like an Mx-5 (Miata)
* Click on the back arrow
* Back in the Drive page, click on the Summary icon
* Click on the Realism panel and choose the Custom tab
* Set Traction Control and Stability Control to Off, and ABS to Factory
* Proceed as you normally would; practice or race

## Overview
This is a model for the 750 MC 116 Trophy car.  It's based on an MX5 (ks_mazda_miata) as it's the most similar standard car.
It's a work in progress and is not perfect but is closer to the real thing than the other AC models available; even closer than the BMW 1M model.

Work completed includes:

* Set the engine power curve to equate to the dyno readings for my car
* Corrected the gear ratios, final drive and rolling tyre diameters
* Disabled the LSD
* Set the track and wheel base to the 116 values - this makes the graphics image look slightly strange
* Set the Traction control defaults to off, although I think in game settings may override this
* Nankang NS-2R tyres have been added as a tyre option

Although the power curve and gear ratios should be right, the car bogs own a bit where it perhaps shouldn't. An example is Nelson at Snetterton which I take in third gear in my physical car
but the model seems to struggle.  The car weight without fuel should be around 1,215kg (1,130kg plus 85kg for driver) but I found the car to be sluggish.  I have reduced the total car weight by 100kg which produces handling and performance closer to a real Trophy car.

The NS-2R tyre model is actually a copy of the semislicks used on the AC Lotus Exige.  Although I have adjusted diameters and widths, I haven't attempted to change the characterisics of the rubber - I wouldn't know where to start.

Opportunities for improvement are:

* Define the model so that it can sit under the BMW brand rather than as a custom configuration of an MX-5
* Change the front suspension from double wishbone to strut - the handling of the model is a bit different to the real thing
* Gradually align the geometry with that of a real 116 Trophy Car
* Reposition the driver and instruments for a right hand drive car
