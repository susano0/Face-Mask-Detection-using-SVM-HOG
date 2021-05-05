# Real-Time Face Mask Detection with SVM and HOG Features

## Summary
In this project, an attempt has been made to extract HOG features and train a model with SVM to recognize people with a mask. This model is also compared with various other classifiers. It is found that the model performed better than other machine learning techniques and had similar performance with the MobileNetV2 deep learning model. The SVM model trained on HOG features of RGB images achieved accuracy, F1-score, and AUC of 0.98, 0.98, and 0.995 on the test set, respectively.

## Metadata 

| File Name     | Content    |
| ------------- |:-------------:| 
| [`Face Mask Detection-Final.ipynb`](../main/Face%20Mask%20Detection-Final.ipynb)      | Final Code | 
| `FaceMask-MobileNetV2-v3.h5`      | MobileNetV2 trained model      | 
| `FaceMask-MobileNetV2-v6.h5` | MobileNetV2 trained model      |   
| `haarcascade_frontalface_default.xml` | Haar Cascade for face     |   
| `lsvc_h` | Linear-SVM + HOG trained model      |   
| `rm_h` | Random Forest + HOG trained model      |   
| `rm_h_g` | Random Forest + HOG trained model on grayscale images     |   
| `svc_g` | SVM trained model  on grayscale images    |   
| `svc_h` |  SVM + HOG trained model     |   
| `svc_h_g_v2` | SVM + HOG trained model  on grayscale images   |   
