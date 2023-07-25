# Metal Arcade Stick Tutorial

## Items/tools Needed
### Items with an (o) are optional but recommended
- Metal Electrical Enclosure, Hammond 1441 series recommended.
- Laser-Cut Top Panel (Which will be shown in the guide)
- (o) 4x 6-32 x ¼” Self-Tapping Panhead Screws. (if using hammond 1441)
- Arcade Stick Wiring (for hooking up buttons/lever to Encoder)
- Encoder PCB, Brook or GP2040-CE recommended.
- (o) Fusion360 or other CAD program
- (o) Adhesive PCB Feet
- (o) Foam or Mouse/Game mat (for non-slip surface on the bottom of the stick)
- 24mm Hole Saw or Step Drill (for USB passthrough hole and auxillary buttons)
- (o) 1/8th inch Drill Bit 
- Drill

## Instructions

### Size
First, you will need to decide on what size you would like your arcade stick to be. For small all-button style sticks, I recommend a panel size of around 10in x 6in. For levered sticks, I recommend a panel size of around 12in x 8in. For either of these, I recommend a depth of 2 or 3 inches, depending on preference. The Hammond 1441 series is also available with wood sides (walnut), which may be an attractive option. 

### Top Panel First Steps
Next, you’ll want some form of CAD software for this guide, specifically one that works well with DWG/DXF files (2d drawing files.) **Alternatively, I also have pre-made files made in the Samples folder in this repository, with images available. If using one of these, skip to the "Manufacturing the Top Panel" section.** Go to the page for the enclosure you picked (I chose the 1441-22BK3) and download the “2d cad” file they provide. Unzip it and open it in your CAD software (This guide uses Fusion360). You should see an image similar to figure 1, which contains the drawing you should edit for your top panel in the bottom left. You remove everything except the Sketch layer called “Visible (ANSI)”, and then make a new project. Copy just the panel part (in this file, the bottom left part) into a new Sketch in said project. Then, using [these layouts](https://www.slagcoin.com/joystick/layout.html), recreate the layout you want (I picked the one modeled after the Sega second player layout). If making a levered arcade stick, this will need the [layout for the mounting plate.](https://www.slagcoin.com/joystick/mounting_layering.html)
![Image of seven drawings contained within a single CAD DWG file.](/img/fig1.png) <center><sub>Figure 1.</sub></center>


### Finishing up top panel in CAD
After placing all the holes and making sure there's enough clearance for the flanges of the enclosure (approx. 10mm away from each edge, and 15mm from the corners), you should be good to go! For some last steps, you need to extrude the Sketch you made and Project the geometry from your original sketch. Your workspace should look similar to figure 2, with your custom layout.
 The extrusion and making a new Sketch removes any construction lines or similar that would otherwise be saved in a DXF. Then, export this new Sketch as a DXF. If you wish to add a plexiglass overlay for art, you can do something similar, making a clearance hole for a 6-32 self-tapping panhead on the new sketch instead of the slot, as shown in figure 3.
 ![Image of a finished arcade stick top panel.](/img/fig2.png) <center><sub>Figure 2.</sub></center>
![Image of a finished arcade stick plexiglass panel.](/img/fig3.png) <center><sub>Figure 3.</sub></center>


### Manufacturing the Top Panel
For making the top panel, I highly recommend [SendCutSend](https://www.Sendcutsend.com), as they can do basically anything you need to do to finish the stick up, including inserting flush posts for the lever, countersinking, and even powder coating! Open your exported DXF file in SendCutSend’s instant quote page. For bare panels (no Plexiglass overlay) I recommend 1.2 or 1.5mm 305 Stainless Steel, or (for panels you are going to paint,) I recommend A36 Mild Steel, with the same thickness. On the next page, select “Hardware Insertion” and open the catalog. You want the longest m5 x 0.8 stud they offer, which is normally near the bottom of the list. If making a plexiglass overlay, I recommend 3.0mm (thinnest available) Clear Acrylic. My cart with an acrylic overlay and a top panel is included in figure 4.

![Image of a finished arcade stick plexiglass panel.](/img/fig4.png) <center><sub>Figure 4.</sub></center>

### Finishing Enclosure
Usually, you will also need to drill a Neutrik D-Sized hole in the side of your enclosure to allow for USB passthrough. This is a standard even outside of the fighting game community, and allows for easily connecting a USB device through to your enclosure. This can be done with the layout in figure 5, which is in mm. I recommend a carbide hole saw, and not a step drill bit for this. You may also wish to add auxiliary buttons, which can be done with the same 24mm hole saw.
![Image of a template for a Neutrik D-Series Passthrough Cutout.](/img/neutrik.png) <center><sub>Figure 5.</sub></center>