<h2>7-clicks from image to analysis</h2>

<table border="0">   
       <tr><td><span style="font-weight:bold">Level</span></td><td>Introductory</td> </tr>
       <tr><td><span style="font-weight:bold">Functionality</span></td> <td>Loading, Segmentation, Visualization</td> </tr>
       <tr><td><span style="font-weight:bold">Time</span></td> <td> <2 min</td> </tr>
       <tr><td><span style="font-weight:bold">Image</span></td><td>Kidney_Cortex_Human.tif<br><a href="https://doi.org/10.5281/zenodo.5816199"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.5816199.svg" alt="DOI">      </a></td></tr>
     </table>

This short sketch demonstrates how to analyze an image in VTEA with only seven mouse-clicks.  There are four steps in 7-clicks:

<ol>
  <li>Start VTEA: 2-clicks</li>
  <li>Load an image: 3-clicks</li>
  <li>Process an image: 1-click</li>
  <li>Segment an image: 2-clicks</li>
</ol>

## Step 1: Start VTEA...

<table border = "0"><tr><td>
VTEA runs as a plugin inside of FIJI (ImageJ).  Once VTEA is <a href = https://vtea.wiki/starting.html>installed in FIJI<a/>, select the VTEA menu and then "VTEA 1.1.6".  The version number will change with ongoing updates.  
 </td></tr>
  <tr><td>

<img class="rounded"
     src="/vignettes/7Click/step_1.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
       </td>
       </tr>
 </table>      
       
## Step 2: Load an image...

<table border = "0"><tr><td>
If no images are open in FIJI/ImageJ, use the open image button <img src="/vignettes/7Click/step_2_button.png"
     alt="Screenshot of VTEA in action."
    style="float:center;width:30px;height:auto;">.  This will open up a standard FIJI open image file menu and automatically load an image into the VTEA workflow.   
 </td></tr>
  <tr><td>

<img class="rounded"
     src="/vignettes/7Click/step_2.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
          </td>
       </tr>
 </table>      
       
     
## Step 3: Process an image...

<table border = "0"><tr><td>
Assuming the image quality is sufficient for segmentation, preprocessing can be skipped. A <a href = https://vtea.wiki/sketches.html#refining-image-processing)>separate sketch</a> describes image processing and VTEA's builtin functionality that borrows from FIJI.
 </td></tr>
  <tr><td>

<img class="rounded"
     src="/vignettes/7Click/step_2_finish.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:800px;height:auto;">
                   </td>
       </tr>
 </table>     
    
## Step 4: Segment an image...

<img class="rounded"
     src="/vignettes/7Click/step_4.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:400px;height:auto;">
    
## Analyze results...

<img class="rounded"
     src="/vignettes/7Click/step_5.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:400px;height:auto;">
