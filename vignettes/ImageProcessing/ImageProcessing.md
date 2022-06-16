<h2>Refining image processing</h2>

<table border="0">   
      <tr><td><span style="font-weight:bold">Level</span></td><td>Introductory</td> </tr>
         <tr><td><span style="font-weight:bold">Functionality</span></td> <td>Loading, Image Processing, Segmentation</td> </tr>
         <tr><td><span style="font-weight:bold">Time</span></td> <td> <5 min</td> </tr>
     <tr><td><span style="font-weight:bold">Image</span></td><td>Kidney_Cortex_Human.tif<br><a href="https://doi.org/10.5281/zenodo.5816199"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.5816199.svg" alt="DOI"></a></td></tr>
     </table>

This short sketch demonstrates how to add, preview and customize image processing of an image in VTEA.  

## Step 1: Start VTEA...

<table border="0"><tr><td>
VTEA runs as a FIJI (ImageJ) plugin.  Once VTEA is <a href = "https://vtea.wiki/starting.html">installed</a>, select the VTEA menu and then "VTEA 1.1.6" .  The version number will change with ongoing updates.  
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
    style="float:center;width:30px;height:auto;">.  This will open up a standard FIJI open image file menu and automatically load an image into the VTEA workflow.   
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
       
     
## Step 3: Add a image processing step...

<table border="0"><tr><td>
<p>Image processing steps can be added by selecting <img src="/vignettes/ImageProcessing/add.png"
     alt="add step"
    style="float:center;width:30px;height:auto;">.  Image processing steps are sequential and the position is given in the menu.</p>
      <p>Image processing techniques are accessible from the drop down menu labeled, "Method".  The available techniques included are designed to correct technical errors (noise, attenuation of intensity with depth) or facilitate contrast (background subtraction).  The techniques can be expanded using <a href = "https://vtea.wiki/develop.html#use-the-barebones-vtea-plugin-project">VTEA's extensible framework </a>.</p>
 </td></tr>
   <tr><td><div align="center">
<img class="rounded"
     src="/vignettes/ImageProcessing/select_processing.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
       </div></td></tr>
 </td></tr>
 <tr><td>
<p>Image processing steps can be previewed by selecting <img src="/vignettes/ImageProcessing/eye.png"
     alt="add step"
    style="float:center;width:30px;height:auto;"> and z-position, if applicable, scrolled.  
 </td></tr>
    <tr><td><div align="center">
<img class="rounded"
     src="/vignettes/ImageProcessing/preview_processing.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:300px;height:auto;">
       </div></td></tr>
       <tr><td>
       If multiple image processing steps are entered, selecting the second <img src="/vignettes/ImageProcessing/eye.png"
     alt="add step"
    style="float:center;width:30px;height:auto;"></p> button previews all image processing steps.
    </td></tr>
        <tr><td><div align="center">
<img class="rounded"
     src="/vignettes/ImageProcessing/preview_multiple.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:600px;height:auto;">
       </div></td></tr>
 </table>   
 
 ## Step 3: Start the image processing...

<table border="0"><tr><td>
<p>Start the processing by selecting <img src="/vignettes/ImageProcessing/process.png"
     alt="add step"
    style="float:center;width:120px;height:auto;">.  Image processing steps may be saved and reloaded via the "Start" menu for added reproducibility. 
      </p></td></tr>
        <tr><td><div align="center">
<img class="rounded"
     src="/vignettes/ImageProcessing/start.png"
     alt="Screenshot of VTEA in action."
    style="float:left;width:300px;height:auto;">
       </div></td></tr>
 </table>   
    
