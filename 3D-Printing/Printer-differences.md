# Resin printer  

### Principle:  

Curing layers of Liquid Resin which then get lifted away to make space for a new Layer.

### Time:  

Mostly dependent on the height of what you print

### Slicer (Software):  

Converts modell to 2D Images along the Z-Axis and tells the printer how long it has to expose the resin to the image, how long it has to wait between layers and how high it has to move the bed between layers.

### Usecases:  

High detail and precise parts.

### Postprocessing:  

- Washing in IPA (Isopropal Alcohol)  
- Removing Supports  
- Curing the print in sunlight  
- Cleaning build plate and Vat of remaining Resin  
Safety equipment is a must. Sanding possible but not recommended as dust is not safe.

### Pros:  

- XY Dimensions don't affect print Time(Longer wait Time may be required if > 50% of space is filled)  
- Z Dimension usually as precise as XY Dimension

### Cons:  

- Prints may Crack with uneven curing.  
- Generally brittle  
- Print times are generally longer then FDM Printers.  
- Post processing needs safety equipment.

# FDM Printer  

### Principle:  

Melting plastic through a nozzle to layer ontop of each other.

### Time:  

Depends on Material max speed, Volume of print and infill density.

### Slicer (Software):  

Converts modell to GCode which tells the printer how to move the nozzle and at what temperatures the printer should print.

### Usecases:  

Large simple parts.

### Postprocessing:  

Remove supports by breaking them of or using plyers and cutters. Sanding is possible but not to a high grit. Clean Build plate.

### Pros:  

- Dual material printing possible  
- most materials have great impact resistance  
- High possible Variety of materials:
  * Pla
  * Abs
  * Petg
  * Nylon

### Cons:  

- Supports generally use more material.  
- Limited Z Axis Resolution.