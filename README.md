![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/new_header.png)

[GrainSizeTools script](http://marcoalopez.github.io/GrainSizeTools/) is a free open-source cross-platform script written in [Python](https://www.python.org/) that provides several tools to visualize and characterize the grain size in polycrystalline materials from thin sections. The script is suitable to use for paleopiezometry (paleowattmetry) studies and to derive the actual 3D grain size distribution using the Saltykov and the two-step methods. The script **does not require a previous experience with Python programming language** (see [documentation](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/tableOfContents.md) or [FAQ](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/FAQ.md)). For users with coding skills, the script is organized in a modular way using Python functions, which facilitates to modify, reuse or extend the code if needed.

## Screenshots

- *Estimation of different apparent grain size measures, in this example using a linear scale*  

![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/readme01.png)  

- *Plots showing the area-weighted, square-root, and logarithmic apparent grain size distributions using the same data set*  

![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/readme02.png)  

- *Estimation of actual (3D) grain size distribution and volume of a particular grain size fraction using the Saltykov method*  

![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/readme03.png)  

- *Applying the two-step method to estimate the shape of the best lognormal distribution*  

![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/readme04.png)  

- *Boxplot comparing different grain size distributions*

![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/readme05.png)  


## Features at a glance

- Load and extract data from txt and csv files generated by the ImageJ or any other application.
- Calculate the apparent diameters of the grain profiles via the equivalent circular diameter and correct, if required, the diameters by adding the perimeter of the grains.
- Estimate different apparent 1D grain size measures including the mean, median, area-weighted mean and frequency peak, the latter using the Gaussian Kernel Density Estimate method. Scales can be linear, logarithmic, or square root.
- It implements several algorithms to estimate the optimal bin size of histograms and the optimal bandwidth of the Gaussian KDE based on the population features.
- Derive the actual 3D grain size distribution from thin sections (2D data) using the Saltykov method, including to get an estimation of the volume of a particular grain size fraction.
- Estimate the shape of the 3D grain size distribution using the two-step method and a single parameter (the MSD).
- It produces different ready-to-publish plots, allowing to save the graphical output as a bitmap or vector images (see the image above for examples).

## Download

You can download the script at the following sites (**Last release 2017/08/04, v1.3.3**):  
https://github.com/marcoalopez/GrainSizeTools/releases  
http://figshare.com/articles/GrainSizeTools_script/1383130  
https://sourceforge.net/projects/grainsizetools/

[View the Project on GitHub](https://github.com/marcoalopez/GrainSizeTools)

## Documentation
Look at the [table of contents](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/tableOfContents.md). You can also download a manual in pdf format [here](http://figshare.com/articles/GrainSizeTools_script_manual/1371025).


## Citation guidelines
If you need to cite the script or the methods the following references are available:

***Script reference***   
Lopez-Sanchez, Marco A. (2017): GrainSizeTools script. figshare. http://dx.doi.org/10.6084/m9.figshare.1383130

***Frequency peak grain size based on Gaussian KDE***  
Lopez-Sanchez MA and Llana-Fúnez S (2015) An evaluation of different measures of dynamically recrystallized grain size for paleopiezometry or paleowattmetry studies. *Solid Earth* 6, 475-495. doi:[10.5194/se-6-475-2015](http://dx.doi.org/10.5194/se-6-475-2015)

***Two-step method***  
Lopez-Sanchez MA and Llana-Fúnez (2016) An extension of the Saltykov method to quantify 3D grain size distributions in mylonites. *Journal of Structural Geology*, 93, 149-161. doi:[10.1016/j.jsg.2016.10.008](http://dx.doi.org/10.1016/j.jsg.2016.10.008).

***Saltykov method***  
The method as implemented in the GrainSizeTools script is described in the Appendix A in Lopez-Sanchez and Llana-Fúnez (2016) doi:[10.5194/se-6-475-2015](http://dx.doi.org/10.5194/se-6-475-2015)
The procedure is partially based on general formulation developed by Sahagian and Proussevitch (1998) *J. Volcanol. Geotherm. Res.* 84, 173–196. doi:[10.1029/95JB02500](http://dx.doi.org/10.1016/S0377-0273(98)00043-2)

## License
GrainSizeTools script is licensed under the [Apache License, Version 2.0 (the "License")](http://www.apache.org/licenses/LICENSE-2.0)

The documentation of GrainSizeTools script is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).  

# 
*Last update* (website): 2017/10/17  
*This project is maintained by [Marco A. Lopez-Sanchez](https://marcoalopez.github.io/)*  
*Copyright © 2017 Marco A. Lopez-Sanchez*  

*Information presented on this website and the documentation of the script is provided without any express or implied warranty and may include technical inaccuracies or typing errors; the author reserve the right to modify or enhance the content of this website as well as the documentation of the script at any time without previous notice. This webpage and the documentation is not liable for the content of external links.*  

*Hosted on GitHub Pages — This website was created with [Typora](https://typora.io/)*  