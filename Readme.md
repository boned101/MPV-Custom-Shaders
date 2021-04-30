My own preset shaders that i uses daily to enhance image quality when using MPV , an open source and very customisable media player.
The shaders included in this are 
  1. KrigBilateral by Shiandow
  2. Luma Sharpen Hook (basic package only)
  3. Adaptive Sharpen
  3.SSimSuperRes
  
You may find these shaders individually at :
 1. https://github.com/classicjazz/mpv-config/blob/master/shaders/KrigBilateral.glsl
 2. https://github.com/classicjazz/mpv-config/blob/c747aed28d0f811dc84bd5edc4f4feaf19ac8b27/shaders/SSimSuperRes.glsl
 3. https://github.com/deus0ww/mpv-conf/blob/feab7ef3d848deb0d77d5f8316c27ac492b0b806/scripts/Shaders.lua
  


Now you will need to change/add the following line to your MPV's input.conf : 
CTRL+(number) no-osd change-list glsl-shaders set "~/shaders/SSimSuperRes.glsl;~/shaders/KrigBilateral.glsl;~/shaders/adaptive-sharpen.glsl";
show-text "SSimSuperRes+KrigBilateral+AdaptiveSharpen"

alternatively i have included my input.conf file for use, if necessary.  You cna put these in the directory C:\Users\(USERNAME)\AppData\Roaming\mpv  on 
Windows 10. For Linux users you can find it elsewhere,it shouldn't be a problem once you look up MPV's main archive on :https://mpv.io/manual/
