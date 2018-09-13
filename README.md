# openFrameworks-clion
sherwyn's personal template project for openframeworks and clion, with a built in CLion debug configuration. 

stole ideas from around the internet and https://forum.openframeworks.cc/t/are-there-any-plan-for-supporting-clion/17188/52

i'll make an actual readme if someone asks me to, add an issue if you want it

## basic instructions (assumes you already know how to use CLion)
1. clone this
2. <code>rm -rf .git</code>
3. have fun

## using existing openFrameworks files
1. clone this
2. rm -rf .git
2. delete everything in src and replace them with your own (or clone your files inside src)
3. if you want to use git, <code>git init</code> inside src 

## hey it doesn't work this is a scam!!
1. *Install Linux*
2. use your package manager to find any missing dependencies (ex: <code>apt search [thing]</code>)
3. install the appropriate packages you find (usually they are something like "libthing-dev" although for gst/gst.h problems you might as well just do <code>sudo apt install gstreamer*</code>)
