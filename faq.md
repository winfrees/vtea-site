# FAQ
----

### General Use
-----
#### Can I analyze 2D data with VTEA?

Yes.  VTEA supports 2D and 3D image processing, segmentation and mapping to the image volume.  The segmentation methods provided in VTEA will operate on 2D images.  It is recommended to use "Connect 2D/3D with kDTree."

#### What is the upper limit of channels that VTEA can handle? 

We have successfully tested VTEA on CODEX datasets with >40 channels.  VTEA is limited only by what ImageJ/FIJI/Bioformats can load.  Because VTEA relies on ImageJ/FIJI for image rendering, images with more than 7 channels can be difficult to visualize (ref).

#### What is the largest image(filesize) VTEA can operate on?

Our experience has only been limited to how large an image we can load into RAM.  The development of more efficient image loading strategies to circumvent this limitation is a topic of ongoing development.

#### Can I import my own segmentation map generated in a different tool (StarDist, illastik, etc.)?

Yes.  This can be done by using the segmentation option, "Prelabelled Nuclei."

#### Can I import features I've calculated in other tools (MorpholibJ, illastik, etc.)?

Yes.  

### Segmentation and Morphology
-----
#### Can I adjust the image processing to improve the segmentation?

#### 

### Explorer windows and gating
-----
#### Can I export images of my gated cells? 

#### 





