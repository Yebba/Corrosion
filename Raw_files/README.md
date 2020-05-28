# Read Me:

In this folder are the raw files downloaded from Supervise.ly, the image annotation software used. On Supervise.ly, images added at the same time are considered a dataset. There are three folders because pictures were added at three different times.

Each folder is named with the number of images labeled inside of it ("Corrosion 7" means that there are seven labeled images). 

Each folder contains:

1. **subfolder**
2. **meta.json** file
3. **obj_class_to_machine_color.json** file

The subfolder contains the following folders:

1. **ann**: contains a json for each image. Each json file contains the vertices of each polygon plotted on the corresponding image
2. **img**: contains the original images that were annotated.
3. **masks_human**: contains a png file for each annotated image, showing a side-by-side comparison of the original image and the annotated image. The areas colored purple are the polygon annotations.
4. **masks_machine**: contains an image for every annotated image. However, these images are all black and show no data. This was probably created due to a feature of Supervise.ly that was not used.
