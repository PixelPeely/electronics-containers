# Electronics Containers
This is a miny project I created to better organize my electronic components; it features tileable and customizeable parametric CAD models for storing and labeling various components.
![alt text](/images/preview.png)
##Customizing
To customize containers, open the FreeCAD project (containers.FCStd), in which you will find a datasheet named "Standards". Open this and modify parameters accordingly, then right click the model in the tree on the left and select "Recompute object".
![alt text](/images/datasheet.png)
##Printing
Once you have customized the container to your liking, select the object in the tree and go to file>export (I prefer 3mf, but any file type works so long as your slicer supports it).
I recommend printing the model vertically, with either the front or back on the plate to minimize the amount of support needed (You cannot print the lid and body seperately, as they utilize a print-in-place hinge).
![alt text](/images/3dp.png)
