<h2>6-clicks from image to analysis</h2>

<table border="0">   
       <tr><td><span style="font-weight:bold">Level</span></td><td>Introductory</td> </tr>
       <tr><td><span style="font-weight:bold">Functionality</span></td> <td>Loading, Segmentation, Visualization</td> </tr>
       <tr><td><span style="font-weight:bold">Time</span></td> <td> <2 min</td> </tr>
       <tr><td><span style="font-weight:bold">Image</span></td><td>Kidney_Cortex_Human.tif<br><a href="https://doi.org/10.5281/zenodo.5816199"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.5816199.svg" alt="DOI">      </a></td></tr>
     </table>

This short sketch demonstrates how to analyze an image in VTEA with only seven mouse-clicks.  There are four steps in 7-clicks:

<ol>
  <li>Start VTEA: 2-clicks</li>
  <li>Load an image: 1-click</li>
  <li>Process an image: 1-click</li>
  <li>Segment an image: 2-clicks</li>
</ol>

## Step 1: Start VTEA...

<table border="0"><tr><td>
VTEA runs as a plugin inside of FIJI (ImageJ).  Once VTEA is <a href = https://vtea.wiki/starting.html>installed in FIJI<a/>, select the VTEA menu <b>(Click #1)</b> and then "VTEA 1.1.6" <b>(Click #2)</b>.  The version number will change with ongoing updates.  
 </td></tr>
  <tr><td>
<div align="center">
       
<img class="rounded"
     src="/vignettes/7Click/step_1.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
         </div>       
       </td>
       </tr>
 </table>      
       
## Step 2: Load an image...

<table border = "0"><tr><td>
If no images are open in FIJI/ImageJ, use the open image button <img src="/vignettes/7Click/step_2_button.png"
     alt="Open image with ImageJ"
    style="float:center;width:30px;height:auto;"> <b>(Click #3)</b>.  This will open up a standard FIJI open image file menu and automatically load an image into the VTEA workflow.   
 </td></tr>
  <tr><td>
<div align="center">
<img class="rounded"
     src="/vignettes/7Click/step_2.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
       </div>  
          </td>
       </tr>
 </table>      
       
     
## Step 3: Process an image...

<table border="0"><tr><td>
If the image quality is sufficient for segmentation, preprocessing can be skipped by selecting: <img src="/vignettes/7Click/step_2_process.png"
     alt="Process button"
    style="float:center;width:80px;height:auto;"> <b>(Click #4)</b>. A <a href = https://vtea.wiki/sketches.html#refining-image-processing)>separate sketch</a> describes image processing and VTEA's functionality including combining image processing steps and previewing.
 </td></tr>
   <tr><td><div align="center">

<img class="rounded"
     src="/vignettes/7Click/step_2_finish.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
       </div></td></tr>
 </table>     
    
## Step 4: Segment an image...
<table border="0"><tr><td>
Two windows are used to setup segementation in VTEA, the settings window and, if applicable, a threshold preview.  Segementation can be previewed by drawing an ROI on the threshold preview and selecting the eye button, <img src="/vignettes/7Click/eye.png"
     alt="Save and close settings."
    style="float:center;width:30px;height:auto;">. VTEA's default segmentation (in 2D or 3D) is a connected components approach that uses pixel intensity or threshold calculations to segment 2D regions with watershed spliting and in 3D fuses overlapping 2D regions based on the distance between centroids of nearby 2D regions.  To continue close the setup window by clicking  on the green checkmark button <img src="/vignettes/7Click/check_box.png"
     alt="Save and close settings."
    style="float:center;width:30px;height:auto;"> <b>(Click #5)</b>.  To start the segmentation selct the "Find Objects" button, <img src="/vignettes/7Click/find_objects.png"
     alt="FInd Objects."
    style="float:center;width:120px;height:auto;"><b>(Click #6)</b>.
    
 </td></tr>       
 <tr><td><div align="center">

<img class="rounded"
     src="/vignettes/7Click/step_4.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
           </div></td></tr>
 </table>     
    
## Analyze results...
        
<table border="0"><tr><td>
 </td></tr>       
 <tr><td><div align="center">

<img class="rounded"
     src="/vignettes/7Click/step_5_result.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
        </div></td></tr>
 </table>     