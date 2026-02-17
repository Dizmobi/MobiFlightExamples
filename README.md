This is to help people building a replica G1000 for a flight simulator.   It is an example of an approach that can be used in mobiflight to overcome challenges with the pan/zoom controls available on the internet.   

To use:
You will have to either rename some stuff in these files, or map your own mobiflight board/controls to these names.    
-The board (mobiflight controller) it assumes it's hooking up to is called G1000
-Each of the controls it's got set up for that board are named JSMap_someting

This was created in a beta version of mobiflight.  You might need to pull a beta version to get it working.

Key factors:
Map prevent push is a variable triggered when the G1000 is put into pan mode (done by pushing the joystick in once).   Then the prevent push causes it to ignore the push command when using the pan controls (up, down, left, right).
Pushing the joystick in again will exit pan mode.   That's how these work in real life.   
