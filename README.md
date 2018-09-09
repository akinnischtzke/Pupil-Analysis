# Pupil-Analysis
MATLAB code for tracking and measuring mouse pupil during experiment

This code will track both the location (centroid) and the diameter of the pupil of a mouse eye. Pupil diameter changes with the behavior of the animal (e.g. increases during locomotion, decreases during sleep/quiesence) and therefore serves as a reliable physiological readout of the internal brain state of the animal.

This code will save the pupil diameter across each frame, this information can than be combined with additional information that was collected during the experiment (i.e. neural data, other behavior data, etc).

To run:

- run the GUI file (analyzePupilSetup_gui.m) which will guide you through the steps and parameters for analyzing the video. 
- the file 'pupilTracking.m' contains the basic analysis steps.

