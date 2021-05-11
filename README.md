# 🔌 Plugin: Blender to Pico CAD

A simple plugin that export blender models as picoCAD model .txt file

![blender2picoCAD](imgs4readme/model_from_blender_9.gif)


How?

1. Open viewVertScript.blend in examples folder
2. open the script panel
3. change the output destination.
4. select the model that you want to export ( make sure that all the transforms are applied. )
5. run the script in the script panel.
6. open the model.txt in picoCAD


<hr/>

TODO:

1. Automatically recalculate and then flip the normals.
2. use the image texture of active uv layer.
3. Throw warnings about:
    * Make sure all the transforms are applied.
    * Make sure model is centered/near to the (0,0,0) coordinate
    * the texture must be of 128px 128px
    * PicoCAD only use first 120px in texture.
4. Create an Export interface.
5. Comment the code.
6. Write tests.
