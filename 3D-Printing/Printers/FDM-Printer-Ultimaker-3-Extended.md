
# Ultimaker Printer  

Open the latest installed Cura Version.

## File Import  

Import .stl files through the Folder Icon in the top left Corner
![Import](uploads/9b2b2980942ca2d0b4193ca9484bf143/Import.png)

## Select Printer  

Select one of the not running printers.
![SelectPrinter](uploads/255a28524cb7f49f521452a0fa343f61/SelectPrinter.png)
Uni-DuE-ES is the left one.
Ultimaker002d26 is the right one.

## Select Filament  

If there is already Filament in the printer click on the filaments shown in Configurations to ensure that Cura has the same loaded.

![image](uploads/7530702ee055973e1b549f64d6fc6b89/image.png)

If using non Ultimaker Filament you have to go to Custom and Select the correct one there.

![image](uploads/3a01982bc2f5bb51fabc4ea03cc33b32/image.png)

If the specific one does not exist use the generic alternative and correct the settings. So that they match the settings shown on the spool.
![image](uploads/4804695038b3781f115186bc5c6dfbdf/image.png)

Some filaments might want to have retractions and or the fan disabled for better results. most standard filaments like Pla and Abs don't mind them but for better strength the fan could be disabled. A sideeffect of a dissabled fan is that overhangs and bridges print worse.

Make sure the model is printed with the Correct Extruder selected.
It´s preferred to use Extruder 1 for the main printing as the other one is primarely used for dissolvable supports.

![image](uploads/d1455afa2239c11360da8a68dad90c83/image.png)

## Support  

Supports are generally needed on non steep overhangs and parts that would be printed in thin air.
Cura marks areas where it thinks supports are necessary red.

![image](uploads/b1b8f0ee247e3cff2b9f2d14000c982e/image.png)

![image](uploads/a25731a6a064b0b017fe995815887963/image.png)

## Model Placement  

Depending on your model you might have to orientate your model so it fits and prints better.
If the model is greyed out it most likely does not fit the printable area of the printer.
You might be able get it to fit by rotating and or moving it. If not you can scale it
(might not be possible depending on use case of the printed model)  
XYZ Movement  
![Move_Modell__2_](uploads/a8a0504a708ae0d42687a797ee4c73e3/Move_Modell__2_.png)

### Rotation  

![Rotate_Modell__2_](uploads/41ae041838a65f8a13e9237a2813cbf1/Rotate_Modell__2_.png)

### Scaling  

![scale_Modell__2_](uploads/b5473aa6230be74ca68e8ce54f37eec3/scale_Modell__2_.png)

## Part strength  

As long as you don't need structural parts under load you don't have to adjust the settings.
Most of the time the standard settings are more then strong enough.  

![Strength_Settings](uploads/3b114123455da46d4a5c2c339cbf467a/Strength_Settings.png)

With lower infill Density you might have to increase the top layers for an even finish.

## Printing  

1. Make sure a glass Bed is installed.(If not its probably in the sink drying)  
2. Apply glue stick to the glass bed for better adhesion and release of model.  
3. Press print over Network in Cura.  
4. Watch the first few layers carefully as they tend to be the reason for failed prints.  
- If the print lifts of the Bed add a Brim in the Settings under Build Plate Adhesion and restart the print.  
- If the printer does not print continuous lines, then the filament might not be loaded Correctly.

## Cleanup  

1. Let the glass plate cool down.    
2. Remove Model from the glass plate.  
3. Wash the glue stick off the glass plate in the sink.  
4. Let the glass dry.  
