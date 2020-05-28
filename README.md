# Patches
This repository contains a selection of patches for suckless projects.

Most of these are derived from the flexipatch projects, e.g. [dwm-flexipatch](https://github.com/bakkeby/dwm-flexipatch), and it should be noted that some of them have cross-patch compatibility built-in using the same preprocessor directives as used in the flexipatch builds.
One good example of this is the [dragmfact](https://github.com/bakkeby/patches/blob/master/dwm/dwm-dragmfact-6.2.diff) patch which can involve up to 11 additional patches. Due to the many possible patch combinations I have decided to leave these preprocessor directives in there as a form of guide for integrating this into your own build - the idea being that you manually delete the code that you don't need.

For cases where one patch changes another, e.g. adding additional fields on top of pertag, individual patches should exist as far as feasible.
