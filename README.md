# Hybrid-CNN-Dilated-Attention-model-for-gym-workout-recognition


This repository supplyies the basic concept of human body capacitance sening and the hardware platform, the firmware, the collected datasets from experiments that combines HBC sensing and IMU sensing for human activity recognition, and the used machine learning algorithms for human activity classification. 

## Hardware

<img width="266" alt="Board_1" src="https://user-images.githubusercontent.com/12549420/136019960-b8bdf3e0-5ddf-455c-8c63-4a171c2dda4a.png" >

The hardware combines IMU and HBC sensing modality on a cutomised board, with ESP32 as the controller, and a 3.7V battery as the power source. 

The schematic and geber files can be found in the Hardware directory. PCB/Prototype can be manufactured directly.

## GymExercise

<img width="450" alt="Calos_Gym" src="https://user-images.githubusercontent.com/12549420/136020221-a32689d2-7c01-42a5-8b1c-68694b6b18b8.png" >

11 gym exercises: Adductor, Armcurl, Benchpress, Legcurl, Legpress, Riding, Ropeskipping, Running, Squat, Stairsclimber and Walking



## Classifcation Result Example

### Gym Exercise Recognition: Hybrid CNN-Dilated-Attention model

![Screenshot from 2024-07-26 12-16-01](https://github.com/user-attachments/assets/ddefb1fd-dcbe-48ce-8c53-f01cd75607bc)


### Gym Exercise Recognition: Random Forest with 615 abstracted features

<img width="900" alt="Screenshot 2021-10-05 at 14 22 43" src="https://user-images.githubusercontent.com/12549420/136021710-d045e318-1fff-47cc-8626-19b3f9f696c9.png" >

Gym Exercise classification result with sensing units on different body locations(pocket, leg, and wrist).


### Gym Exercise Recognition: Deep models result

<img width="741" alt="Screenshot 2022-06-15 at 11 14 01" src="https://user-images.githubusercontent.com/12549420/173791120-9f0ee57e-f1d6-4ffa-ab9e-3f6f92593887.png">



