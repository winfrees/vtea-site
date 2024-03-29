## Getting Started
-----

### Installation

**Method 1.** The easiest method for installing VTEA is with the [FIJI updater](https://imagej.net/plugins/updater).  To install VTEA select the update site: “Volumetric Tissue Exploration and Analysis.”

Unfortunately, the Renjin libraries, "jars", that come with FIJI interfere with plotting of heatmaps and violin plots in VTEA.  Importantly,  the core VTEA functions, image processing, segmentation, cell classification and neighborhood analysis are not affected by this bug. The current fix is to remove the jar listed below. This is not an ideal approach and may _**break**_ other FIJI functionality.  Fortunately, [efforts](https://forum.image.sc/t/updating-version-of-renjin-supported-in-scijava/48497) are being made to bring FIJI up-to-date with the most recent releases of Renjin.  

The following jar need to be removed from the Fiji/jars/ folder:

1. datasets-0.8.1906.jar
2. gcc-runtime-0.8.1906.jar
3. graphics-0.8.1906.jar
4. grDevices-0.8.1906.jar
5. methods-0.8.1906.jar
6. renjin-appl-0.8.1906.jar
7. renjin-core-0.8.1906.jar
8. renjin-gnur-runtime-0.8.1906.jar
9. renjin-script-engine-0.8.1906.jar
10. stats-0.8.1906.jar
11. utils-0.8.1906.jar

And replaced with the dependencies on <a href = "https://github.com/icbm-iupui/volumetric-tissue-exploration-analysis/releases/download/v1.2.3/Dependencies.zip"> github</a>.

**Method 2.**  VTEA can also be run inside an IDE such as Netbeans.  The easiest approach is to clone the maven project from [github](https://github.com/icbm-iupui/volumetric-tissue-exploration-analysis).  

If there is any difficulty or concerns please feel free to submit an [issue](https://github.com/icbm-iupui/volumetric-tissue-exploration-analysis/issues), or contact [us](mailto:swinfree@unmc.edu).

**Additional links:**

Original publication, [https://doi.org/10.1681/ASN.2016091027](https://doi.org/10.1681/ASN.2016091027).

Manuscript for version 1.0 on Bioarchives, [https://doi.org/10.1101/2021.12.27.474025](https://doi.org/10.1101/2021.12.27.474025).

Software release on Zenodo, [https://doi.org/10.5281/zenodo.5110084](https://doi.org/10.5281/zenodo.5110084).




