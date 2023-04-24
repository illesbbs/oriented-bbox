# oriented-bbox
Use this code in SideFX Houdini in an Attribute Wrangle in detail mode. Don't forget to create the Spare Parameters. 
This code outputs the corner points of the bottom rectangular and the height of the bounding box.
You can extract your desired data with a blast node after the wrangle. Set the groupname to "bbox" and run it over points.
The height of the bbox is stored as a detail attribute >> @maxy
