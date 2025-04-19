# ks_mazda_miata__e87
This is an Assetto Corsa car model that simulates a BMW 116i racing car that races in the 116 Trophy series of the 750 Motor Club.
The model is a modified version of the standard Assetto Corsa model of a Mazda Miata NA (MX-5).

## Changes
* The transmission loss has been set to 0% to avoid a feeling of sluggishness
* The rear damper bump resistance has been increased to reduce the transition to mid-corner understeer
* A Damper tab has been added to the Setup display, which allows you to set the rear damper bump resistance
  * The default setting is 7
  * At this time the number of positions for this setting doesn't match the real life GAZ Shocks clicks
* The mod startup now reflects the year of production of this mod, i.e. BMW 116 Trophy '25
* The car weight detailed in the UI has been corrected - this does not affect performance or handling

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

## Installing a New Version
To install a new version of this mod:
* Save your setup using the Setup I/O tab in the Assetto Corsa Setup screen
* Exit Assetto Corsa
* Delete the folder `.\assettocorsa\content\cars\ks_mazda_miata__e87`
* Repeat the Install and Run steps

If you installed this mod using git, simply perform a `git pull`.  After the pull, delete the file `.\assettocorsa\content\cars\ks_mazda_miata__e87\data.acd' if it exists.
The data.acd file is an old packed data version of the configuration and would take precedence over the newly pulled version if not deleted.

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

The NS-2R tyre model is actually a copy of the semislicks used on the AC Lotus Exige.  Although I have adjusted diameters and widths,
I haven't attempted to change the characterisics of the rubber - I wouldn't know where to start.

Opportunities for improvement are:

* Define the model so that it can sit under the BMW brand rather than as a custom configuration of an MX-5
* Change the front suspension from double wishbone to strut - the handling of the model is a bit different to the real thing
* Gradually align the geometry with that of a real 116 Trophy Car
* Reposition the driver and instruments for a right hand drive car, although I note that, as of 2025, LHD cars are permissable in the 116 Trophy series.
