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

#### Is there a citation for the VTEA?

Citations are much appreciated.  Citations can be one or many of the following:

Original publication, [https://doi.org/10.1681/ASN.2016091027](https://doi.org/10.1681/ASN.2016091027).

Manuscript for version 1.0 on Bioarchives [https://doi.org/10.1101/2021.12.27.474025](https://doi.org/10.1101/2021.12.27.474025).

Software release on Zenodo [https://doi.org/10.5281/zenodo.5110084](https://doi.org/10.5281/zenodo.5110084).

#### Do you have examples of VTEA use in publications?

1. Lake BB, Menon R, Winfree S, et al. An Atlas of Healthy and Injured Cell States and Niches in the Human Kidney. Genomics; 2021. [doi:10.1101/2021.07.28.454201](https://doi.org/10.1101/2021.07.28.454201)
2. for the Kidney Precision Medicine Project, Ferkowicz MJ, Winfree S, et al. Large-scale, three-dimensional tissue cytometry of the human kidney: a complete and accessible pipeline. Lab Invest. 2021;101(5):661-676. [doi:10.1038/s41374-020-00518-w](https://doi.org/10.1038/s41374-020-00518-w)
3. Black LM, Farrell ER, Barwinska D, et al. VEGFR3 tyrosine kinase inhibition aggravates cisplatin nephrotoxicity. Am J Physiol-Ren Physiol. 2021;321(6):F675-F688. [doi:10.1152/ajprenal.00186.2021](https://doi.org/10.1152/ajprenal.00186.2021)
4. Black LM, Winfree S, Khochare SD, et al. Quantitative 3-dimensional imaging and tissue cytometry reveals lymphatic expansion in acute kidney injury. Lab Invest. 2021;101(9):1186-1196. [doi:10.1038/s41374-021-00609-2](https://doi.org/10.1038/s41374-021-00609-2)
5. Varberg KM, Winfree S, Chu C, et al. Kinetic analyses of vasculogenesis inform mechanistic studies. Am J Physiol-Cell Physiol. 2017;312(4):C446-C458. [doi:10.1152/jpcell.00367.2016](https://doi.org/10.1152/jpcell.00367.2016)
6. Makki MS, Winfree S, Lingeman JE, et al. A Precision Medicine Approach Uncovers a Unique Signature of Neutrophils in Patients With Brushite Kidney Stones. Kidney Int Rep. 2020;5(5):663-677. [doi:10.1016/j.ekir.2020.02.1025](https://doi.org/10.1016/j.ekir.2020.02.1025)
7. Woloshuk A, Khochare S, Almulhim AF, et al. In Situ Classification of Cell Types in Human Kidney Tissue Using 3D Nuclear Staining. Cytometry A. 2021;99(7):707-721. [doi:10.1002/cyto.a.24274](https://doi.org/10.1002/cyto.a.24274)

### Segmentation and Morphology
-----
#### Can I adjust the image processing to improve the segmentation?

#### 

### Explorer windows and gating
-----
#### Can I export images of my gated cells? 

#### 





