ONCE SET UP, NEED ONLY THIS:
===========================


cd ~/Documents/Git/OctoPi/src
../../CustomPiOS/src/update-custompios-paths
sudo modprobe loop
sudo bash -x ./build_dist


SETUP
=======

is in the readme...


Building OctoPi Variants
OctoPi supports building variants, which are builds with changes from the main release build. An example and other variants are available in [CustomPiOS, folder src/variants/example](https://github.com/guysoft/CustomPiOS/tree/CustomPiOS/src/variants/example).



To build a variant use:

sudo bash -x ./build_dist [Variant]
