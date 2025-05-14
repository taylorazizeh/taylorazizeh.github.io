---
title: Foraging ecology of emperor penguins
subtitle: My master's work focuses on using accelerometers to detect potential prey capture signals.
summary: My master's work focuses on using accelerometers to detect potential prey capture signals.
authors:
- admin
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: 'Image credit: [**Taylor Azizeh**]'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Set captions for image gallery.
gallery_item:
- album: gallery
  caption: Default
  image: theme-default.png
- album: gallery
  caption: Ocean
  image: theme-ocean.png
---

## Investigating the foraging ecology of late chick-rearing emperor penguins

Emperor penguins (Aptenodytes forsteri) are a non-volant, ice obligate seabird species endemic to Antarctica. This makes them especially vulnerable to climate change. Especially as the projected climate scenarios predict that a large percentage of the emperor penguin population will be extinct by the end of the century under a business-as-usual scenario [(Jenouvrier et al. 2019](https://onlinelibrary.wiley.com/doi/10.1111/gcb.15806). Cape Crozier, Ross Sea, is the southernmost colony in the Ross Sea, meaning that it may act as a refuge for climate-impacted emperor penguin populations [(Trathan et al. 2020)](https://www.sciencedirect.com/science/article/pii/S0006320719309899?via%3Dihub).

My thesis work uses accelerometer data for foraging penguins collected during the 2019 and 2022 field seasons at Cape Crozier. Tags collected depth, acceleration, GPS data, and more. I followed the basic workflow outlined below.

### Data cleaning
Biologging tag data can be very messy, and often requires many steps to ensure there are no outliers or erroneous values. Therefore, I wrote these [custom functions](https://github.com/taylorazizeh/EmperorPenguins/tree/main/code/data_cleaning) to help prepare the data for analysis:  

*Depth data was zero-offset in an unpublished program but can be done using the package [diveMove](https://cran.r-project.org/web/packages/diveMove/diveMove.pdf).  

00. Concatenate data  
   This code concatenates the zero-offset corrected (ZOC) depth data* with the acceleration data.  
01. Interpolate depth  
   To match the resolution of the other data, the 1Hz ZOC data needs to be interpolated to 100Hz or 50Hz.  
02. Decimate acceleration  
   To match the sampling frequencies of the lower resolution data from 2022, the 2019 data needs to be decimated from 100Hz to 50Hz. I did this using the [decimate()](https://www.mathworks.com/help/signal/ref/decimate.html) function in MATLAB.  
03. Convert .csv to .nc files
    netCDF files are much easier to use than .csv files, so this code exports each column as a new .nc file.

Optional + helpful scripts
> Downsample timestamps: can be used to manually downsample timestamps (extract every nth row)  
> Fix erroenous timestamps: can be used to identify individual problem animals and adjust timestamps  
> Rename netCDF file variable: used to rename the file variable in .nc files  
> Standardize GPS timestamps: used to convert all GPS timestamps to one format  

### Data analysis
COMING SOON!

![Image credit: [**Taylor Azizeh**]](https://github.com/taylorazizeh/EmperorPenguins/blob/main/images/empe_close_up.JPG)

[Check out the Vertebrate Ecology Lab blog for more information!](https://mlml.sjsu.edu/birdmam/emperor-penguin-expedition-2022-season/)
