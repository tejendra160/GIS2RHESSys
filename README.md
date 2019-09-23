# GIS2RHESSys
Quick notes: 
- Most tools here are coded in R with pacakage "rgrass7" to access GRASS GIS data

**To start**, please look at the guide on workflow script (try the links below) https://nbviewer.jupyter.org/github/laurencelin/GIS2RHESSys/blob/master/GIS2RHESSys_workflow_script_master.ipynb 
https://colab.research.google.com/github/laurencelin/GIS2RHESSys/blob/master/GIS2RHESSys_workflow_script_master.ipynb


**Understanding project and RHESSys model directory structure**
![Alt text](rhessys_filesystem.png?raw=true "Title")




Below diagram shows the relationship between GRASS dataset and RHESSys model.

![Alt text](GIS2RHESSys.png?raw=true "Title")

Other links:

RHESSys github: https://github.com/RHESSys/RHESSys

RHESSys wiki: https://github.com/RHESSys/RHESSys/wiki

RHESSys tools by Will from U.S. west coast https://github.com/RHESSys/RHESSys/tree/master/RHESSysPreprocessing
Will's RHESSys tools are also written in R with R-studio. Major difference between GIS2RHESSys and Will's is that GIS2RHESSys is designed to simplify the existing code and be friendly to command line/Jupyter notebook/server-client environment.
