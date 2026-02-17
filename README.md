# MomentumRegularizationData
Data for momentum equation based regularization and image registration method.
DataSharing Folder contains 1 image matfile and 3 subfolders, each containing 4 image matfiles each.

phantom.mat contains 3 variables. First, an RF US image variable (im) which is 2 spatial dimensions (axial and lateral), and a thrid temporal (frames) dimension which indexes frames of increasing displacement induced by transducer compression (see paper for more information). Next are 2 variables xi and yi that define the axial and lateral pixel positions of the RF image variable and are the same size as the first two dimensions of that variable.

subfolder "3D" contains 4 files which contain the image and spatial location variables from 4 different simulations of the 3D, volumetric simulation of a soft inclusion in a harder background (simulationSI), a homogeneous phantom (simulationHOM), a simulation of a medium hard inclusion (simulationmHI) in a softer background and a harder inclusion (simulationHI) in a softer background. See the accompanying paper for details.

subfolder "Pstrain" contains 4 files which contain the image and spatial location variables from 4 different simulations of a 2D plane strain simulation of a soft inclusion in a harder background (simulationSI), a homogeneous phantom (simulationHOM), a simulation of a medium hard inclusion (simulationmHI) in a softer background and a harder inclusion (simulationHI) in a softer background. See the accompanying paper for details.

subfolder "Pstress" contains 4 files which contain the image and spatial location variables from 4 different simulations of a 2D plane stress simulation of a soft inclusion in a harder background (simulationSI), a homogeneous phantom (simulationHOM), a simulation of a medium hard inclusion (simulationmHI) in a softer background and a harder inclusion (simulationHI) in a softer background. See the accompanying paper for details.
