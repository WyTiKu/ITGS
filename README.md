MAKING A VISUAL REPRESENTATION OF BATHYMETRY DATA IN BLENDER
===

## SECTION 1 - Making a Blender Model From A Heightmap

### PREPARE BLENDER BY:

 1. Opening Blender 2.97
 
 2. Deleting the existing cube in the 3D viewport by right-clicking it, pressing Delete or X to open the Delete menu, and select Delete.
 
 3. Having the heightmap picture available on the computer

### MAKE THE BLENDER MODEL:
   1. Press **SHIFT+A** to open the Add menu 
       *(Note: The mouse pointer must be in the 3D viewport)* 
     
   2. Select **Mesh -> Grid**
   
   3. Under the Tool shelf Tab, under Add Grid, change the values of “X subdivisions” and “Y subdivisions” to AAA 
   
   *(The Toolshelf tab is typically open by default and can be found on the left side of the screen. If it is not open, press T on the 
   keyboard to open or close it while the mouse hovers anywhere over the 3D viewport.)*

   4. Click on Textures under the Properties Viewport (Right side of the screen)
   
   5. Click on the *New button* to add a new texture

   6. Click on the *Open* button to select an image
   
   7. Locate the heightmap for the blender creation in the filesystem, and select it
   
   8. Under *Image Mapping* on Blender under Textures, click on the *extension Repeat*, and select **Extend** instead
   
   9. Go to Modifies under the Properties Viewport
   
   10. Click on *Add Modifier* and select *Displace* to add a displace modifier
   
   11.Click the *texture icon* (directly to the left of the *new* button under the new window that appeared from the Displace modifier) and select the *heightmap texture*
   
   *This should result in the flat square changing shape into an exaggerated version of the heightmap model*
   
   12. Change the *Midlevel* value to 0
   
   13. Change the *Strength* value to X
   
**Section 1 is Finished.**
   
## SECTION 2 - Adding the Textures and refining the model

### REFINE THE MODEL:

   1. Click on *Add Modifier* and select the *Subdivision Surface* modifier
   
   2. Under *Subdivision Surface* click the upwards pointing triangle to change its position to be above the Displace modifier.
   
   3. Select *Simple* instead of Catmull-Clark
   
   4. Change *Subdivisions View* to 2, make the value lower if the computer cannot handle it and higher if the computer can 
   handle it, but more than 0 is not necessary.
   
   5. Change the *Subdivision Render* to 3.
   
   6. Under the *Toolshelf*, under *Tools*, under *Edit*, under *Shading*, select *Smooth*.
