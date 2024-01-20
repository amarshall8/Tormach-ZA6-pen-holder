# Tormach-ZA6-pen-holder
 A compact, low cost, high precision pen drawing module for Tormach ZA6 robotic arms.\
 More info on the design can be found here https://www.alecmarshall.com/articles/tormach-za6-pen-plotter-module/
 
![render](media/pen_holder_4x5_render.jpg?raw=true)

## Required materials:

  * [Compression spring](https://www.mcmaster.com/9657K332/)
  * [12mm steel pipe](https://www.mcmaster.com/6045N11/)
  * [12mm linear bearing with circular flange](https://www.mcmaster.com/6483K114/) (Cheap LM12UU bearing with the same circular flange on eBay are what I used)
  * [1/8" by 1" Steel pin](https://www.mcmaster.com/90145A475/) (for endstop cross bar)
  * __10x__ 6-32 1/4" heat set inserts:
    * [Amazon](https://www.amazon.com/dp/B076R7F3DJ) (select long option)
    * [McMaster](https://www.mcmaster.com/93365A132/)
  * __6x__ 6-32 1-3/4" bolts/screws (To attach the upper section to the lower section)
  * __6x__ M4 25mm bolts/screws (Ideally SHCS. Attaches the lower section to the robotic arm)
  * __4x__ 6-32 1/2" bolts/screws (To attach the linear bearing to the upper section)
  * __2x__ 6-32 3/8" bolts/screws (For compression pen mount)
  * __2x__ 6-32 nuts (For compression pen mount)

## Assembly:

First the 3D printed parts need to have the heatset inserts pushed into the relevant spots on the parts. This should be fairly straightforward.\
There is an [excellent guide](https://hackaday.com/2019/02/28/threading-3d-printed-parts-how-to-use-heat-set-inserts/) for it on Hackaday with recommendations for slicer settings as well.

Next, you may need to sand down a section of the pipe to fit properly. The pipe is not always less than 12mm, and can trend upwards of it, meaning that it will not fit into the linear bearing. To solve this, you can mount the pipe in a drill, and have a second person use 400-600 grit sandpaper to slowly make it thin enough to slide smoothly. Make sure you wipe it with an oiled cloth before running it through the bearing, otherwise this will put metal dust into the bearing, which is not good.
![sanding](media/sanding.jpg?raw=true)

Then, the section of pipe which has the correct diameter will need to be cut to the length specified in the drawing below. I recommend using a bandsaw or hacksaw for this.\
![tube](media/tube_drawing.png?raw=true)

To finish the pipe, a hole needs to be drilled at the distance from the edge specified in the drawing above to fit the 1/8 pin. This can be done by hand, but it is far easier with a drill press or a mill, since the pin can't be skewed much, otherwise it won't fit.
![drilling](media/drilling.png?raw=true)

Finally, the pin can be inserted into the pipe.
![pin](media/pin.jpg?raw=true)

The last step before assembling it onto the robot is to add the linear bearing to the upper housing 3D print and add the pipe. It should be semi press fit, just push it into the housing and add the four 6-32 1/2in screws to finish the upper housing.
![housing](media/upper_housing.jpg?raw=true)

Next, add the pipe with the cross-pin.
![housing with pin](media/fully_assembled_housing.jpg?raw=true)

### Robot Assembly:

To add the pen holder to the robot, the lower section must be screwed to the robot end-effector before the upper housing can be attached. Through experimentation by Sadiq, we found 3 screws is plenty. Then the spring needs to be inserted into the lower housing, and the plunger seperator piece can be installed.
![lower housing on robot](media/lower_housing_on_robot.jpg?raw=true)

Next, use the 6 1-3/4" 6-32 screws to attach the upper housing to the lower housing on the robot. Make sure to compress the spring and keep the plunger seperator in place between the spring and the pipe. Finally, add the pen mount with the two short 6-32 screws and nuts, and tighten them down on the pipe and on the pen. Too much force will break the print!.
Note: you may have to cut down your pen to fit inside the pipe without it sticking out a ton!
![final assembly](media/final_assembly.jpg?raw=true)

Congratulations, you now have a Tormach ZA6 robot capable of precise drawing!! :)
