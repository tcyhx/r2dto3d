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


[1] R. Phan and D. Androutsos, ”Robust semi-automatic depth map generation in unconstrained images and video sequences for 2D to stereoscopic 3D conversion,” IEEE Trans. Multimedia, vol. 16, no. 1, pp. 122-136, Jan. 2014.

[2] H. Yuan, S. Wu, P. Cheng, P. An and S. Bao, ”Nonlocal random walks algorithm for semi-automatic 2D-to-3D image conversion,” IEEE Signal Proc. Let., vol. 22, no. 3, pp. 371-374, Mar. 2015.

[3] R. Rzeszutek, R. Phan, and D. Androutsos, ”Semi-automatic synthetic depth map generation for video using random walks,” in Proc. IEEE Intl. Conf. on Multimedia and Expo (ICME), 2011, pp. 1-6.

[4] B. Ham, M. Cho, and J. Ponce, ”Robust image filtering using joint static and dynamic guidance,” in Proc. IEEE Conf. on Computer Vision and Pattern Recognition (CVPR), 2015, pp. 4823-4831.


Any question, please contact: yuanhx@mail.ustc.edu.cn
