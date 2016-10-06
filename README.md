# r2dto3d
Source code and experimental results for "Robust Semi-Automatic 2D-to-3D Conversion via $\ell_1$ Optimization". The code will be released when the paper review is finished.

tsukuba    : experimental results of Tsukuba when user input is accurate.
tsukuba_err: experimental results of Tsukuba when errorneous input is present.

venus    : experimental results of Venus when user input is accurate.
venus_err: experimental results of Venus when errorneous input is present.

teddy    : experimental results of Teddy when user input is accurate.
teddy_err: experimental results of Teddy when errorneous input is present.

cones    : experimental results of Cones when user input is accurate.
cones_err: experimental results of Cones when errorneous input is present.

In each folder,
depth_gc  : estimated depth of graph-cuts [1].
depth_NRW : estimated depth of nonlocal random-walkers [2].
depth_ours: estimated depth of our method.
depth_rw  : estimated depth of random-walkers [3].
depth_rwgc: estimated depth of hybrid graph-cuts and random-walkers [1].
depth_sd  : estimated depth of static and dynamic filtering [4].
imglbls   : user labelled image
mask      : mask image where 1 denotes marked regions and 0 denotes unmarked regions.
strokes   : sparse depth map extracting from the user labelled image

Any question, please contact: yuanhx@mail.ustc.edu.cn
