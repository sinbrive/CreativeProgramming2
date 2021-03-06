# LASER CUTTING RUBBER STAMPS  

The laser-cutter is an amazing tool: not only can it cut and engrave wood and plastic, but we can also use it to create rubber stamps!

## CREATE YOUR FILE  

* Your file should be a `png`, `jpg`, or `tiff` at `300 dpi` — lower resolution will mean a poorer quality stamp  
* White areas will be left behind and will be part of your print  
* Black areas will be cut away  
* No grayscale, just black and white  
* No vector cutting  
* You can experiment with vector engraving but the lines will be very thin  

**Remember!** The image you cut into your stamp will be reversed when printed! You can mirror the image before you cut it in Photoshop, or use this code at the end (right before you save the image) to mirror it automatically:  

    pushMatrix();
    translate(width/2, height/2);
    scale(-1, 1);
    popMatrix();

You can also add `filter(INVERT)` if you want to preview your colors the way they'll print.

As your last step, you'll need to resize the image in Photoshop. Everything in Processing exports at `72 dpi`, but it will scale to `3x3"` at `300 dpi`. We'll do this in class next week so no need to worry about it yet.

## CUT YOUR STAMP  

1. Load your file on the Fab Lab PC  
2. Open in Acrobat  
3. `File > Print...` and choose `VLS4.60` as the printer  
4. Click `Print` (nothing will happen yet, this just sends it to the laser software) and hide Acrobat  
5. Open the VLS software; your image should show up at the right size and as a black-and-white image  
6. Place your piece of rubber at `0,0` on the laser bed, close the lid and turn on the fume extractor  
7. Open the `Settings` menu  
	* `Material > Rubber > Silicone Rubber`  
	* Set `Thickness` to `0.098 inches` (you can measure your rubber with a caliper to double-check)  
	* Increase `Raster Engraving` power to `+30%`  
8. Turn on the air compressor  
9. Click the `Play` button in the laser software to start the cut  
10. **You must stay at the laser cutter during any cutting operation!** This makes sure everything is running ok. Do not step out for a snack or wander off – fire can happen very quickly!  
11. When the cut is done, let the fume extractor run for a minute or two before removing your piece  

## CLEANING YOUR STAMP  

1. Remove the stamp from the laser cutter – it should have a fine white powder on it  
2. Put the stamp in a tray with soapy water and let sit for a few minutes  
3. Gently scrub the surface with a toothbrush to remove debris; it's best to do this underwater, periodically checking your progress  
4. Rinse in fresh water and let dry completely  

## MOUNTING YOUR STAMP  

1. If you have any misalignment or margin showing, you may want to trim your stamp with a very sharp knife (take several light cuts to avoid distorting the rubber) or a pair of scissors before mounting  
2. Lightly sand the back of your stamp with sandpaper to rough up the surface  
3. Apply Barge's contact adhesive to the back of your stamp and your wooden block, spreading it evenly and avoiding any pooling  
4. Let the adhesive sit for 15-20 minutes – do not skip this step! Contact adhesive works by letting the glue partially cure first  
5. When the adhesive looses its shininess, carefully attached your stamp to the wooden block – once stuck down it will be impossible to reposition  
6. Lightly clamp with a block on top to avoid marring the stamp's surface – do not apply too much pressure or you'll distort your stamp  
7. Let sit for another 10 minutes or so before removing the clamp; let sit overnight before printing  





