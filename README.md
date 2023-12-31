# StretchLabs 🤸 

🏁 Stretch properly with the help of computer vision.
Whether you're an athlete, a student, or just have some back pain, everyone's in need of stretching. However, properly stretching is incredibly important - it is the difference between no pain and potentially even more pain. This project leverages computer vision and angles suggested by numerous websites in order to help create the most impactful, yet safe stretch. 

# 🔑 Key Features
## Angle Detection 
* The project employs simple formulas to calculate angles and distance
Uses OpenCV and MediaPipe for ROI (Region of Interest) Detection

## Skeletal Estimation
* Mediapipe helps determine the ROI 
* Using Mediapipe's Pose Estimation package, the ML model allows us to correctly map 32 key joints on the human body - perfect for mapping any stretch imaginable.
* The tracker subsequently predicts the pose landmarks and segmentation mask within the ROI using the ROI-cropped frame as input.

<img width="550" alt="image" src="https://github.com/AggieSportsAnalytics/StretchLabs/assets/66052866/ee665bc0-0e19-4663-a4ec-45415f4f62b0">

## 🪴 Areas of Improvement
Sustainable UI: The project could be created into an app or have a cleaner user interface
Work with Doctors: Working hand in hand with doctors to improve the accuracy and liability of the model

## 🚀 Further Uses 
Machine Learned Approach: Develop a system where based on proficiency of the user, it machine learns one's capabilities and slowly pushes them to stretch further as they progress
Deep Sort: For purposes of a using the algorithm in a class setting, if multiple users wanted to stretch in the same frame and receive feedback on the quality of their strech after

## 💻  Technology 
Open CV
Mediapipe
Numpy
