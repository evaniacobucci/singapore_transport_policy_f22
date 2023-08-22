# Shifting Attitudes Toward Policies that Reduce Car Dependence: An Experiment in Singapore Using Multidimensional Scaling

This repository contains the full output of the Galileo analysis used in "Shifting Attitudes Toward Policies that Reduce Car Dependence: An Experiment in Singapore Using Multidimensional Scaling", as well as the study materials and software components necessary to replicate the workflow that produced those results.
A brief overview of these materials and their locations follows.

## Study Materials
The materials used in this study which are suitable for sharing are in the folder "trafficf22".
These include the following files:
- test.rs - This is the runstream that tells the Galileo program what options to run, where to look for data, etc.
- Control.dat - Flat text file containing pair comparison data for the control group
- Treatment.dat - Flat text file containing pair comparison data for the treatment group
- Control.q - Questionnaire filled out by the control group
- Treatment.q - Questionnaire filled out by the treatment group (with message printed at the top)
- Control1000.crd - Coordinates and labels for control group spatial projection (.crd files may be viewed with Big Galileo Viewer, available in the [Mac App Store](https://apps.apple.com/gw/app/big-galileo-viewer/id1054352847?mt=12)).
- study.lbl - Labels for the concepts used in the study
- Test1000.crd - Coordinates output directly by the Galileo run, including the unrotated sets of coordinates for both the control and treatment groups, followed by the rotated coordinates, and then the labels. This file contains all of the output from the program, and is therefore of academic interest, but will crash the viewer, which expects coordinates and labels in a very specific format.
- Test1000rot.crd - Modified version of Test1000.crd containing only the two sets of rotated coordinates and a set of labels for each, uppercase for the control and lowercase for the treatment. (Open this in the viewer to see the treatment and control groups simultaneously, and therefore the effects of the intervention)
- test1000.prt - Printout of the full Galileo analysis, including descriptive statistics for each pair comparison, means matrices, coordinates, rotated coordinates, warp factors, distances moved by each concept in space, and vector correlations for each concept across both conditions.

Note that the file extensions are for organization only.
Each file needs to be opened in a text editor with a non-proportional font in order to display properly.
On the Mac we prefer [BBEdit](https://www.barebones.com/products/bbedit/), but you can use your favorite text editor.

## Software to Replicate Analysis
The programs necessary to replicate the analysis are in the folder /galileo/RUNNER.
These are designed to be run in Unix-like operating systems, but have only been tested on macOS via the Terminal.
Versions compiled for the PC are also available, but were not used in this study.
Directions on how to perform the runs are in progress / available upon request.