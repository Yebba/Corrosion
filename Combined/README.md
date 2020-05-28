# Read Me:

This folder contains:
1. folder named **Corrosion Dataset**
2. **meta.json** file: contains metadata about the polygons used for annotations in json object format.
3. **obj_class_to_machine_color.json** file: contains metadata in json object format. This may be part of a feature in Supervise.ly that was not used.

The **Corrosion Dataset** contains the following folders:
1. **ann**: contains a json for each image. Each json file contains the vertices of each polygon plotted on the corresponding image
2. **img**: contains the original images that were annotated.
3. **masks_human**: contains a png file for each annotated image, showing a side-by-side comparison of the original image and the annotated image. The areas colored purple are the polygon annotations.
4. **masks_machine**: contains an image for every annotated image. However, these images are all black and show no data. This was probably created due to a feature of Supervise.ly that was not used.

