# Basic Settings Profile

## Quality

### Layer Height

A smaller Layer height will decrease the visibility of the printed Lines.
Whilst a bigger layer height usually increases Strength.

Generally this setting is kept within 20%-80% of the nozzle diamater.
- Printing smaller usually doesn't make much of a visual change but increases points 
of Failure.

- Printing bigger than 80% of the nozzle diameter means that the extruded Filament
will not make sufficient contact with the last layer.
As the layers will be only barely touching.

## Walls

### Wall Thickness

Determines how many lines thick the wall should be printed by dividing
the value by the nozzle diameter.  
This setting is mostly used to increase impact strength in parts.  

### Horizontal expansion

Calibration setting to offset dimensional inaccuracies on the XY-Plane.  
Generally a value that is automatically calculated from the layer height.

## Top/Bottom

### Top/Bottom Thickness

Setting to controll the amaount of solid lines below and above the infill.  
Used to hide the initial bridging over the empty parts of the infill.
Might need to be increased if a Infill density lower then 20% is used.

## Infill

### Infill Density

Changes the Infill density by adjusting the width of the empty space between the infill lines.  
Actual density also depends on type of Infill Pattern

### Infill Pattern

- Triangles
  - Easy to print
  - Doesn't uniformally distribute force
- Cubic
  - Fairly easy to print
  - Uniformal force distribution
  - Might leave visable spots on the top layer as the distance between lines is not constant.
- Cross
  - Used to allow xy rotation in flexible parts Printed with flexible filaments
- Cross 3D 
  - Allows xyz rotation in flexible part Printed with flexible filaments
  - Might leave visable spots on the top layer as the distance between lines is not constant.
- Gyroid
  - Even Force distribution
  - Constant distance between lines
  - Does not trap air
  - Ideal for filling with sand
- Lightning
  - Only to support the top layers
  - Decreases print time for decorative modells
  - Moderately hard to print

## Material

### Printing Temperature

Determines the temparature of the nozzle that melts the filament.
Should be in range of the material defined temperature range.
Most of the time a lower temperature is better for print accuracy and a higher one is better
for layer adhesion. A lower print temp will also increase the distance the printer can bridge 
without supports

### Build Plate Temperature

Determines the temperature of the heated Bed on wich the first layer is printed.
Should be in range of the material defined temperature range. Used to prevent thermal
shock induced stresses that peel the model of the plate.

## Speed

### Printing Speed

The maximum speed at wich the nozzle will move.
Physically limited by the amount of meltable filament and hardware limited by the max acceleration
and speed of the stepper Motors.  
Typically at around 60mm/s for Pla. A higher print speed will decrease dimensional
accuracy and surface finish of the walls. It also increases the likelyhood of small and or
tall objects tipping over during printing.

## Travel

### Enable Retraction

Retractions pull the filament back out of the nozzle so that no filament is "Dripping"
out of the nozzle when its not supposed to. If dissabled you get fine strings when the
nozzle moves between parts.

### Retraction Distance

Usally the amount retracted is between 3 and 5 mm. A higher value would result in an increased chance of a clogged
nozzle and a longer print time. On the other hand a to small retraction may not remove 
enough filament from the nozzle to eliminate strings between parts.

### Z Hop when retracted

If enabled the printer will go up a bit so as the nozzle will not "hit" anything.  
- significantly increases print time
- Only really necessary with abrasive filaments as the hot nozzle will melt over the existing plastic
- Increases possible failurepoints as the z axis has to move twice every retraction.

## Cooling

### Enable print Cooling

Cooling fans enable you to better print overhang and sharper angles.  
Might decrease the layer adhesion thus decreasing part strength.

### Fan speed

Fine tuning for the amount of cooling realised with the part cooling fan.  
Compromise between part strength and overhang accuracy.

## Support

### When to Use

Generally you want supports whenever a part of the model would be printed in the air.
This includes anything that would be printed at an angle of over 60° to the buildplate.
Otherwise there would not be enough previously extruded filament to support the next layer, 
which would then sag down.

### Generate Support

Enables Supports.

### Support Placement

Constrains where the start of supports can be placed.
- Everywhere
  - Support will be placed on model and Buildplate
- Touching Buildplate
  - Cura will completely avoid placing supports on the model
  - Without using tree supports none of the normal supports that touch the model
at there base will be printed
  - With tree support most will be supported.
    - needs to be checked as it's not always possible to reach the overhang with trees

### Support Overhang Angle

The angle that determines where supports are needed. The range from Value to 90° will be supported.  
Lower than 45° does not make sense as the layers are always at least half overlaying.

### Support Horizontal Expansion

Scales the support across the xy Plane

## Build Plate Adhesion

### Enable Prime Blob

Ensures that the nozzle is full of plastic at the start

### Build Plate Adhesion Type

- Skirt
  - Prints a few lines around the model
  - Wipes the nozzle at the beginning
  - Can check level before the print starts
- Brim
  - Prints a single layer that extends the models footprint
  - Helps against the model peeling of the buildplate
  - Needs to be removed from the model afterwards
- Raft
  - Prints a Raft with a solid top layer
  - Helps against the model peeling of the buildplate
  - Can be a pain to remove if the model sticks too well to the raft

## Dual Extrusion