## Volumetric Tissue Exploration and Analysis

We developed VTEA as a tool for tissue cytometry(histocytometry) of large 3D fluorescence light microscopy image volumes ranging from 50-100s of microns thick.  The objective was to unify image processing, segmentation, data exploration and analyis in one package. Our solution is predicated upon the idea that *image processing, segmentation and analysis of 3D image volumes is best implemented with a bidirectional interactive user interface from image processing to analysis*.

Importantly, our solution is in its infancy. In fact, the tools are relatively simple ones drawn from ImageJ's core functions. These first tools represent only the beginning of our vision for VTEA. We are currently planning to leverage the SciJava framework to make VTEA easily extensible and continue to build both upon existing tools in ImageJ/Fiji and our own novel approaches.

**Three-dimensional tissue cytometry.** Three-dimensional tissue cytometry(3DTC) enables the quantitative measurement of whole cells while retaining their morphology, localization and associations-think of it as *in situ* flow cytometry. How can we do 3DTC? Volumetric tissue exploration and analysis!

**Design Principals:**

**Free and easy to get.** We opted to use ImageJ/Fiji as the distribution platform because it has an excellent and robust community of contributors. Practically, it provides the mechanisms for updating, a number of image processing tools and is built on a simple and powerful extensible framework.

**Easy to use.** We designed VTEA to organize the most common workflow in 3DTC inclusive of image processing (to manage imaging artifacts), segmentation (extensible to bring in edge deep learning approaches into a common framework of analysis) and exploration and analysis with flow cytometry like plots, gating, mapping to image with ROI gating and tools for high dimensionality data.

**Compatible with mesoscale 3D analysis.** We built segmentation to handle massive datasets and to operate seamlessly on an embedded database to enable analysis of 100's of thousands of cells and will incorporate tools for clustering and dimensionality reduction.

**Original image referencing.** The power of 3DTC in VTEA enables the localization of identified cells in the analysis space in the original image, *in situ*, and in 3D with [ClearVolume](/plugins/clearvolume).






You can use the [editor on GitHub](https://github.com/winfrees/vtea-site/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/winfrees/vtea-site/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
