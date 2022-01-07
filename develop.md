<h2>Developing VTEA</h2>

Changes and development of VTEA are welcome and ancouraged.  VTEA was rewritten with a SciJava framework to simplify the addtion of new functionality in image processing, segmentation and analysis.  Currently, there are three methods for suggesting or making changes or adding functionality. 

* TOC
{:toc}

-----

## Suggest a new functionality via the issue tracker

Using the [issue tracker](https://github.com/icbm-iupui/volumetric-tissue-exploration-analysis/issues) for VTEA is the simplest way to suggest new functionality.  Please be as thorough in your descriptions and expect a back-and-forth to make sure your idea is captured in the software.  For an example of a request for new functionality look [here](https://github.com/icbm-iupui/volumetric-tissue-exploration-analysis/issues/56).

*revision:*   *date:* 

## Use the barebones VTEA-plugin project

The SciJava underpinings of VTEA makes it easy to extend key functionality in the VTEA workflow. The classes that can be easily extended and incorporated with Scijava annotation are given below. To get started with a template project visit the [VTEA plugin repository](https://github.com/icbm-iupui/vtea_plugin).

|Functionality|Interface|Superclass|
|-------------|---------|----------|
|Image Processing|ImageProcessing|AbstractImageProcessing.class|
|Segmentation|Segmentation|AbstractSegmentation.class|
|Measured morphologies|Morphology|AbstractMorphology.class|
|Measurements to make on segmented objects|Measurment|AbstractMeasurment.class|
|Measurements to make on neighborhoods|NeighborhoodMeasurement|AbstractNeighborhoodMeasurement.class|
|Features derived from unsupervised analysis|Feature|AbstractFeature.class|
|Look up tables for plots|LUT|AbstractLUT.class|

*revision:*   *date:* 

## Clone and develop on the entire VTEA codebase

*revision:*   *date:* 


