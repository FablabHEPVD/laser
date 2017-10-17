name: inverse
layout: true
class: center, middle, inverse
---

# Laser 101
.footnote[Go and see [this presentation's source code](https://github.com/FablabHEPVD/laser)]
---
## Laser101 Training Goals
![](https://i.imgur.com/DqSqFUT.png)

???
- Lasercutter is NOT a printer; it is a CNC machine
- It is a tool that requires experience and craftsmanship to master
- Each job is unique and may require adjustments:
  - Characteristics of the specific material
    - Variations in thickness, Variations in construction...
  - The current condition of the laser can affect performance
    - Cleanliness of mirrors and lens, Aging of the tube, Bed alignment, Mirror alignment...
---

## What do laser cutters do?
---
layout: false
.left-column[
### CO2 Laser Cutting Mechanics and Bodor
]
.right-column[
![](https://i.imgur.com/fUxVRpL.png)
  ]

???
- Inspire awe. ([Nice explanation video](https://www.youtube.com/watch?v=lW4Uq_2VPhE)) and a nice one [on the physics of it. ](https://www.youtube.com/watch?annotation_id=annotation_3029&feature=iv&src_vid=lW4Uq_2VPhE&v=y3SBSbsdiYg)
- In essence, Laser cutters take light, focus it with a lens and burn whatever is in their way. It's like using a magnifying glass to catch paper on fire; just much more intense. 
- Unlike the sun, the laser beam is a single wavelength - it's a single color in the light spectrum and in case of a typical CO2 laser, that wavelength is in the Infra-Red part of the light spectrum, so it is INVISIBLE to the human eye.
---
layout: false
.left-column[
### CO2 Laser Cutting Mechanics and Bodor
]
.right-column[
![laser like biology](https://i.imgur.com/fjEWSzy.png)

(really here it's better to just draw on a sheet of paper and/ or show Bodor)
  ]

???
- Now how do we get this light? It is a glorified neon sign. You have a gas, excite it with electricity, and you get photons (light) getting emitted by excited gas electrons. 
- The gas mixture in our machine is comprised of carbon dioxide, nitrogen, hydrogen and helium. That's why it's called CO2 laser. The gas is being used up as we cut, and every now and then we need to get the laser-tube refilled or purchase a new one. 
---
### Gas Filled Laser Tube
![laser mirrors](https://i.imgur.com/hfNC1qB.png)
???
- In the tube, there's a mirror on one side, and a partially-permeable mirror on the other side. The emitted light is bouncing between these two mirrors, and each time it passes through the tube, it gets amplified. But one of the mirrors is made to let through a bit of this light, about 2%, and that's our useful laser beam.
- The beam is only about 1cm in diameter as it travels from the laser resonator.
---
### Focusing
show bodor

???
- It is focused with a lens at the end of the nozzle. 
- We also blow air onto the cutting area through the nozzle, (oxygen + nitrogen) which helps to put out little fires and most importantly gets the smoke off the way and reduced build up of debris on the focus lens.
- It also helps create an exothermic reaction and cut more effectively. 
---

## Introduction Bodor main components
- Our Machine Bodor
  - Vendor: Bodor
  - Model: BCL-1006XU
  - Power: 100W Nominal 120W Max sealed glass CO2
  - Max Cutting area: ??
  - Water Cooler System, Compressor, Filter, PC
   
 ![laser pizza](https://i.imgur.com/mP6AplB.png)

???
- Show Laser Path (reinforce laser mechanics)
- Mention that the red laser is NOT the cutting one.
---

## Laser Usage Guidelines
---
### Essential Rules
- Everyone must be trained
- You must not cut forbidden materials.
- If you're ever unsure about anything, talk to a superuser. 
- You have to use the Logbook. ➡️
---
### Logbook
 - Keep track of time used in the logbook on the laser.
 - Use the machine timer available on the computer desktop.
 - Calculate time that you are occupying the laser cutter computer, not just the time the laser is powered on. (Seat Time)
 - Failure to do so may result in suspending lasercutter privileges.
---
class: middle center
### Pricing

???
 - There's currently NO hourly rate. 
   - FREE with the general yearly charge for maintenance. 
 - (Maybe in the future: Usage limits included in membership/ 2 hrs/day and 8hrs/ week.)
 - Users can buy the material they use from us (mdf/ wood) OR bring their own.

---
## What can you do with a laser? 
Lasers are computer controlled machines that can either cut or engrave shapes.
---
### Vector? 
- ![vector vs raster](https://i.imgur.com/J5RBm9G.png)
---
### Cut vs. Engrave
- ![cut vs engrave](https://i.imgur.com/9G2Nv2i.png)

???
- Cutting:
 - laser follows vectors in your art work
- Engraving:
 - laser “fills” polygons with a scanning motion
 - polygons must be closed
 - It's also possible to engraving Raster Images; this is used for variable depth engraving. 
---
### Big showcase of photos :-)

[link to google slides](https://docs.google.com/presentation/d/e/2PACX-1vSjxLkzcj7qRxYBM_2fKS50iLK7ocNEYm8I8dH1t1Cy2Tr8VHr5SbMIKqgYRdHmzy56-D4QSECuw7qB/pub?start=false&loop=false&delayms=3000&slide=id.g1f740948e3_0_54) (convert to .md in time)

---
## Basic Cut Flow

Here we come!

1. Get some design
2. Select material
3. Get it into RDWorks on the computer and set the laser settings (Open a prepared .rld file)
4. Start the laser, water cooler, filer, compressor
5. Cut the thing. 
6. Power the laser down
7. Clean up after yourself
8. Note the time in logbook. Can't leave the fablab without it. 

???
- in this section, WALK THROUGH THE WHOLE THING, but do it fast. do not stop much at all. we'll do it more in detail afterwards. 
- Set up the gear file. Include various settings
- Use some cool desktop timer???

---
## Laser Safety - MOST important part. 
- Lid. No overriding. 
- Don't be looking straight into the cut intently for too long.  Not dangerous but can be very bright. The windows shield harmful light
- Don't cut materials that produce toxic gases
- Wear ear protectors if noise is a concern
- Fire ...? 
---
### Fire
![burnt laser](https://i.imgur.com/PNF8Qyy.png)

???
- todo: BUY A SMALL FIRE EXTINGUISHER.
- Lasers cut by burning the material
- Fire will happen (Don't Panic!)
- Never leave the laser cutter unattended while it is operating. 
- Most of the materials used with the laser cutter are combustible and WILL ignite when in contact with the laser beam. If a fire should start inside the machine turn it off with the big red knob, then foot switch. Then alert staff. AND/ OR extinguish the fire.
- Check cutting bed for debris from previous use that might catch fire (use the Shop Vac)

---

## Materials: 
???
- It's on the wiki (but not as I like it yet)
- http://atxhackerspace.org/wiki/Laser_Cutter_Materials
- This list is comprised of only the most commonly used materials.
- Any other material you may want to cut **MUST be approved by the a staff member** prior to cutting! This is strictly enforced and will result in immediate loss of laser access.

- You CAN cut: 
  - Chipboard
  - Matte board
  - Corrugated cardboard
  - Poster board
  - Foam core (poor results with small pieces)
  - Acrylic (cast acrylic is recommended, extruded acrylic (which is cheaper) results in imprecise and soft edges). Plexiglas and Lucite are brands of acrylic.
  - Leave protective paper on while cutting and engraving
  - Woods: Bass, balsa, maple, cherry, poplar, walnut, oak, birch are the most common
  - MDF
  - Plywood
  - Hardboard (masonite)
  - Leather
  - Cork
  - Rubber (engraving only)
  - Glass (engraving only, ¼ inch minimum thickness)
- You MUST NOT cut: 
  - These materials are strictly prohibited because they are hazardous to both your health and the equipment. Anyone knowingly using these materials in the lasercutter will lose laser access and be held liable for any damage caused to equipment.
  - No polycarbonates (Lexan, mylar, acetate, etc.)
  - Polycarbonates are very similar to acrylic. When in doubt, ask staff!
  - No soft woods and some hardwoods with high resin content
  - These catch on fire easily. Examples: Pine, cedar, spruce, fir, cypress.
  - No ABS plastic
    - ABS does not cut well in a laser cutter. It tends to melt rather than vaporize, and has a higher chance of catching on fire and leaving behind melted gooey deposits on the vector cutting grid. It also does not engrave well (again, tends to melt). Also, cutting ABS plastic emits hydrogen cyanide, which is unsafe at any concentration.
    - http://atxhackerspace.org/wiki/Laser_Cutter_Materials
  - No vinyl (this includes PVC and PCV)
  - No fiberglass
  - No polyester
  - No styrene
---