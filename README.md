# GAM-GAMV-GUI-AND-K3TD

GAM/GAMV GUI & K3TD

The geostatistical mapping of anomaly density module for UXO applications in VSP requires these two additional software packages developed by Sandia National Laboratories. GAM/GAMV provides the estimation tools to calculate the appropriate spatial models (variogram) and provides the input necessary for KT3D. KT3D uses the spatial model to provide estimates of the anomaly densities at the unsampled locations within the sample area. Both of these packages must be installed in the appropriate directories for proper integration with VSP (Visual Sample Plan).

Note: Software will extract two separate installers for GAM/GAMV and KT3D. Each installer will continue after the previous one is finished installing.

"Copyright (2007) Sandia Corporation. Under the terms of Contract DE-AC04-94AL85000 with Sandia Corporation, the U.S. Government retains certainrights in this software."

SCR# 1081
SCR# 1082

McKenna, Sean; Peyton, Chad

The GAM/GAMV GUI provides a graphic user interface to public domain FORTRAN codes (gam, version 2.0 and gamv, version 2.0) that were developed at Stanford University in 1998 (see Deutsch and Journel, 1998). The gam and gamv codes allow for calculation of different measures of spatial variability and spatial correction from a set of available data. The GAM/GAMV GUI accesses the executable versions of the gam and gamv software, initiates the calculations by the executables and manages the outputs of the executables in a user friendly graphical manner. Additionally, the GAM/GAMV GUI code then provides the user with both automatic and interactive tools in a graphical interface to fit models to the calculations of the spatial variation/correlation of the data. The GAM/GAMV GUI software allows the user to get various parameters for the gam and gamv executables that do the actual calculations by using dialog boxes, it provides some error checking as these parameters are set and then allows the user to run the calculation by calling the executable compiled from the previously developed FORTRAN software. The resulting output of the gam or gamv codes can be visualized in the GAM/GAMV GUI interface. The visualization portion of GAM/GAMV allows for both automatic and manual fitting of the model of spatial variation/correlation. GAM/GAMV GUI can be run in batch mode from the command line without invoking the graphical interface.

The KT3D GUI provides a graphic user interface to a public domain FORTRAN code (kt3d) that was developed at Stanford University in 1998 (see Deutsch and Journel, 1998). The kt3d software contains the implementation of several kriging algorithms that complete spatial estimation onto a grid or a set of points from a set of available data and using a variogram model to describe the spatial variation of the data. The variogram model is calculated and modeled using the GAM/GAMV GUI software described separately. The KT3D GUI software allows the user to set various parameters for the FORTRAN code by using dialog boxes, it provides some error checking as these parameters are set and then allows the user to run the calculation by calling the executable compiled from the previously developed FORTRAN software. The resulting output of the kt3d code can be visualized in the KT3D GUI in several ways. If a gridded estimation problem is selected, color maps of the estimated values and the kriging variance are displayed in side by side images. If either jackknifing or cross-validation options are selected, then a series of user-defined X-Y plots can be created.

https://vsp.pnnl.gov/gam_gamv_k3td/index.stm
