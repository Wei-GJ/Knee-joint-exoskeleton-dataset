# Knee-joint-exoskeleton-dataset
Used for torque estimation control of knee exoskeleton

/////  OVERVIEW  /////
Knee_exo_data Dataset for Task_Agnostic_Control_of_a_Knee_Exoskeleton_via_Deep_Learning_Based_Biological_Joint_Moment_Estimation
Authors: Jijun Tong, molinarodean@gmail.com; Chen Wang, wangc@zstu.edu.cn; Yuwei Bian, bywjy0223@gmail.com
Details and explanation included in methods section of the associated publication
Date last modified: 02/06/2026

/////Knee_exo_data File Structure/////
Train and Valid both have the same structure shown below. 
Train contains training data for the model.
Valid contains the validation data for model performance. Three users (BT01, BT02, and BT13) returned but their data was witheld from the training data for their deployed model, and the final seven were new users (BT18-BT24). 

/////Declaration/////
1. Our data was selected from the public dataset released by Dean Molinaro in his paper "Task-Agnostic Exoskeleton Control via Biological Joint Moment Estimation" for the control of knee exoskeletons.

2. Our primary files are the csv files named "angle2moment-*" for each motion mode, while the remaining files are those used for dataset selection from Dean Molinaro's public dataset.
