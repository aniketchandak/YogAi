# Real Time Classification of Yoga Poses using SimpleHRNet

Using a simplified implementation of HRNet [Deep High-Resolution Representation Learning for Human Pose Estimation
](https://arxiv.org/abs/1902.09212) we created a app that takes real time recording from a webcam, performs pose estimation of each frame of the recording, and displays the clostest approximated yoga pose that the person is performing. 

Note: A Webcam is required to be connected and functional on your laptop/desktop for this app to work.

## Requirements:
- First clone and follow the instructions to install SimpleHRNet from this repository https://github.com/stefanopini/simple-HRNet
  - Be sure to you are able to run the demos listed in their directions
- After that is done clone the files from this repository and copy/paste them into the HRNet folder
- Run pip to install
```
pip install scikit-learn
```
- Run *MLP.py* to generate our MLP model
 
```
python MLP.py
```
- Run *app.py* to start the webcam application
   - Note you may have to pip install extra libraries if import errors come up
```
python app.py
```

## Additional files/folders that are optional to run/see
*get_keypoint_data.py* is used for extracting the raw kepoint data from the data located in the yogads folder
Run it if you want to see how the raw data is extracted
*keypoint_data.txt* is the output of this file

*gridsearch.py* is used for MLP optimization and you may run it to find to see how we found the best parameters to train our MLP

*sampleposes* just contains the yoga pose images used in conjunction with app.py to display correctly classified yoga poses

*Final Report and Efficient Net Report are the reports for our project* 

## Slides
https://docs.google.com/presentation/d/1pwgeNmPPewbE9TFqNUettRD5vyq0Fc5I4fMX1u-p0ws/edit?usp=sharing

## About
This page (code, report and presentation) is the group D submission for Final project for CS256: Selected Topic in Artificial Intelligence, Section 2. Led by Instructor: Mashhour Solh, Ph.D.

The group members are Aniket Chandak, Ashraf Saber, David Bui, Deanne Kshipra Charan, Hardik Kumar, and Siddartha Thentu

The code maybe used for educational and commercial use under no warranties. For questions on this project and code please reach out to: david.bui01@sjsu.edu

## Credits
This project was conducted with free credits provided by AWS educate team.

