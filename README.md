![emm](demo0.jpg)
![emmm](demo1.jpg)
![emmmm](demo2.jpg)
![emmmmm](demo3.jpg)
# Stochastic Screen Space Reflection
## Why?
* Although we do have Unity's official Postprocessing Stack V1 and V2, there are still many defects inside. Like the unperfact roughness present at V1 package and the fallback(to reflection probe) leak in V2. So, by implementing the Stochastic Screen Space Reflection algorithm published by FrostByte(SIGGRAPH 2015).
## How?
* 1. Add Stochastic Screen Space Reflection Component to you camera.
