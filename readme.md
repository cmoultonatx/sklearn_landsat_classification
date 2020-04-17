This repository is meant to serve as a platform to start with open source image classification via the open source python stack. 

In order for these scripts to work, you need to first download any Landsat image and add the .TIF files into a known folder on your local workstation. All uses of "in_dir" as a variable must be replaced with the folder which contains these separate geotiff images (raw n band images from USGS) or the known pre-merged geotiff.

To download Landsat imagery, I've found the best way is through Glovis via https://glovis.usgs.gov/ or the USGS Earth Explorer  via https://earthexplorer.usgs.gov/. 

You must sign up for a free account first with the United States Geological Survey (USGS), but unless you are a conspiracy theorist, your data won't be used for much ;)

Pretty much all you need to start off with these notebooks is an unzipped folder of Landsat images. Typically, each band (Red, Blue, Green, Near IR, Coastal Aerosol, etc), will be saved in a separate TIF. I will do my best to comment out where these are able to be interchanged with separate spectral bands. 