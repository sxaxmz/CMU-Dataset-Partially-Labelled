# CMU-Dataset-Partially-Labelled
Partially labelled, interpreted, and analyzed version of the [CMU dataset](http://mocap.cs.cmu.edu/).

This repository was created during thesis research that aims to apply Reccurrent Neural network (RNN) specially LSTM to classify motion activities.

The used tool to interpret and prase the dataset can be found [here](https://github.com/CalciferZh/AMCParser/).

The body contains in total of 31 joints, each represented in XYZ coordinates sums up the total of 93 features. Those features represent a full body joints skeleton.

The selected body joints were the lower body joints due to their importance compared with the other joints. The selected lower body joints were the ‘lfeumer’ joint, ‘lfoot’, ‘rfeumer’ joint, and ‘rfoot’ joint. The total number of features including the XYZ coordinate for each is 12 joints' features.

### Folder Structure
	CSV
  •	*.csv
	Rotations
  •	Training
    o	*.amc
  •	Testing
    o	*.amc
	XYZ
  •	Training
    o	*.csv
  •	Testing
    o	*.csv
	XYZ_Analysis
  •	*.png

### Encode classes in the file names 
SubjectNumber_TrialNumber_MotionCategory

[Read The Research Here!](https://www.researchgate.net/project/Recurrent-Neural-Network-Applied-to-Motion-Captured-Data)

[The Labelled Dataset Can Be Found Here!](https://drive.google.com/drive/folders/1op6_PMW6MrZphXTH72eueH6SA9wg4cOB)


