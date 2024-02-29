Back Channel Detection using explicit features extracted from Open Pose , Open Face and open Smile. Trying different features such as head pose, gaze, AU's from open face , pose estimates from open pose and voice from open smile to do the back channel prediction.

In our experiment we try to use different features from open face, open pose and open smile and try to analyze which features when comined or which features when used alone increases back channel prediction.

Use the Explicit.ipynb to generate features and then use those generated features in the svm.ipynb to evaulate the importance of those features. 
Below is the overview of diffferent experiments with different combination of features and different models
![image](https://github.com/gowtham07/Back_Channel_detection_using_Explicit_features/assets/15648676/d2117782-b90c-4fc6-980d-f76d16e11296)

For the updated project and paper please refer the repo ('https://github.com/gowtham07/Backchannel_detection'). This repo is more of a trying repo which we used to fix on feature selection and simple model for this cause before going on to transformer architecture)

Prerequisite: Need to extract features from video using OpenFace and OpenPose. Did not upload those files as they are confidential
