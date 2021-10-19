# State Farm Distracted Driver Detection
### Can computer vision spot distracted drivers?
---


## Background:
1. Nearly 4,000 people were killed in crashes involving distracted drivers in 2015. Distracted driving was the reported cause of death of 3,450 people in 2016. An estimated 391,000 drivers were injured in distracted driving crashes in 2017 (Motor Vehicle Crash report for 2019)
2. Available camera that could realtime monitoring the driver from distracted

## Methods:

### Approach:
We are going to use CNN to predict different type of distacted diver images. The model will have training and validation processes. 

### Data sources:
Dataset is available from  https://www.kaggle.com/c/state-farm-distracted-driver-detection

Image 1: ![imgs/driver_data_exmples.png](imgs/driver_data_exmples.png)

## Results:
Image 2: ![imgs/Confusion_matrix.png](imgs/Confusion_matrix.png)

Image 3: ![imgs/model_diagram.png](imgs/model_diagram.png)

Image 4: ![imgs/Train_val_epocs.png](imgs/Train_val_epocs.png)

Image 5: ![imgs/PredResult1.png](imgs/PredResult1.png)

Image 6: ![imgs/PredResult2.png](imgs/PredResult2.png)

## Conclusion:
Distracted drivers can be spotted by CNN model. The model prediction was pretty good in Training (0.991) as well as validation (0.990)

### Future imporvement
This ML model can be implemented in real-time simulation where as the camere is placed in the car. 
