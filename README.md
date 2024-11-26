# 2024 bioinformatics workshop: Napari image viewer for exploring spatial transcriptomics

As more labs perform spatial transcriptomics experiments, there is a necessity for researchers to be able to visualize and explore the results.
For 10X genomics experiments, the Loupe Browser application is one option for exploring spatial data that does not require any coding.
While Loupe Browser offers an intuitive, polished, interactive interface, the functionality is limited. 
I recently started using the [Napari image viewer](https://napari.org/stable/) for visualizing spatial datsets. 
Napari is powerful, flexible, and customizable, and can be used not only to visualize tissue images, gene expression, and virtually any type of data or analysis resulting from spatial transcriptomics experiments.
Napari can also be used more generally for any type of imaging/microscopy data, but this workshop will focus on spatial transcriptomics. 
The following instructions can be used to install and run Napari with minimal coding required.

***Note for Windows users: while the following instructions should work on Windows, Mac, or Linux computers, I don't have a way of testing this on Windows and can't guarantee everything will work***

## Download this repository to your computer

This repository contains the necessary files to setup a software environment for 

**Option 1: Using git from the command line** If you are familiar with using the command line program git, open a terminal session and use the following code to clone this repository in a location of your choosing:

```         
git clone https://github.com/tjgibson/2024-napari-workshop.git
```

**Option 2: Download through github**
To download this repository through the web, do the following: 
1. navigate to the github page: https://github.com/tjgibson/2024-napari-workshop.
2. Click on the green code icon to open a dropdown menu.
3. Click download zip and save in a location of your choice.
4. Unzip the file and open the folder.


## Software Setup

1.  Python
2.  Spatialdata package
3.  Visual Studio Code

## Opening the example notebook in VS code

Although Napari is an interactive, graphical application, it is launched from a Python script/notebook rather than by opening an app on your computer.
