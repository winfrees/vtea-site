## Volumetric Tissue Exploration and Analysis

We developed VTEA as a tool for 3D tissue cytometry(histocytometry, 3DTC) of large 3D fluorescence light microscopy image volumes ranging from 50-100s of microns thick.  The objective was to unify image processing, segmentation, data exploration and analyis in one package. Our solution is predicated upon the idea that *image processing, segmentation and analysis of 3D image volumes is best implemented with a bidirectional interactive user interface from image processing to analysis*.

**We tried to design a tool that is...**

**...free and easy to get.** We opted to use ImageJ/Fiji as the distribution platform because it has an excellent and robust community of contributors. Practically, it provides the mechanisms for updating, a number of image processing tools and is built on a simple and powerful extensible framework.

**..easy to use.** We designed VTEA to organize the most common workflow in 3DTC inclusive of image processing (to manage imaging artifacts), segmentation (extensible to bring in edge deep learning approaches into a common framework of analysis) and exploration and analysis with flow cytometry like plots, gating, mapping to image with ROI gating and tools for high dimensionality data.

**...compatible with mesoscale 3D analysis.** We built segmentation to handle massive datasets and to operate seamlessly on an embedded database to enable analysis of 100's of thousands of cells and will incorporate tools for clustering and dimensionality reduction.

**...built arround referencing the original image.** The power of 3DTC in VTEA enables the localization of identified cells in the analysis space in the original image, *in situ*, and in 3D with [ClearVolume](/plugins/clearvolume).

