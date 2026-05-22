# American Sign Language (ASL) Fingerspelling Recognition System
------------------------------------------------
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/ea2349c99e3a9b73bc38ddb292f5a5903cd31788/ASLAlphabet-3.jpg)

------------------------------
 Project Objective:
 -------------------
Develop an intelligent deep learning system that recognizes and translates American Sign Language (ASL) alphabet gestures from images and real-time video into text, promoting accessibility and communication for the deaf and hard-of-hearing community.
----------------------

📊 Dataset & Problem Statement:
-------------------------------
Dataset: ASL Alphabet Dataset with 87,000 images (29 classes: A-Z, space, delete, nothing)

Classes: 26 letters (A-Z) + 3 special gestures (space, delete, nothing)

Challenge: Real-time recognition of dynamic hand gestures with varying lighting, backgrounds, and hand orientations

Real-world Impact: Bridge communication gap between ASL users and non-signers.
-------------------------------------

🏗️ Technical Architecture:
----------------------------
1.Model Development 
------------------
2.Preprocessing Pipeline:
---------------------
-Hand Segmentation: MediaPipe Hands for robust hand detection.
-Data Augmentation.
--------------------------
3.Model Evaluation:
==================
Firstly:Squeeze net accuracy:
=====================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/3af627701fefd6d8e44c0e90978fd98add5798e1/images/Screenshot%202025-12-19%20202141.png)

Secondly:Mobile net accuracy:
===========================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/0aeed175884789ebaca1094c08649213db5cbd39/images/WhatsApp%20Image%202025-12-19%20at%2019.53.51.jpeg)

Thirdly: Efficient Model B1:
===========================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/5cf9e058f60e722849170fd185b97e1e531dcfe7/images/nada%20model%20effiencient%20net.jpeg)

Fourthly:Inception Model
==========================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/50314f6a5174318c8a3e9658193f62f07f234f5f/images/WhatsApp%20Image%202025-12-19%20at%2021.36.15.jpeg)

Fifthly: Efficient net P0:
========================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/39d1e1a170c6b73a0dad6a7f4c2a9a41b1cc869b/images/download.png)
============
Lastely: CONVNEXTTINY:
==================
![image](https://github.com/Salma-Salah420/Sign-Language-Fingerspelling-Assistant-ASL-Alphabet-Project-/blob/a7a9e5f74ea16239470d401bc8a1a9f9eda97d63/images/training_history%20convnettiny.png)

=========

-----------------
Performance Metrics
Architecture Comparison Tables
such as precision, Recall , F1 score
---------------------------
4.Grad-CAM Visualization
========================
as user can make an ASL to capture a photo for any letter then see the accuracy of each model and who can predict him.
---------------------
5.GUI Implementation:
====================
We will upload a photo for a letter in ASL.
then wait the results as how each model can identify this letter.
each model can predict according to its accuracy

------------------------
6.Real-time Sentence Builder
----------------------------------
Roles of Members:
-----------------
Mariam Abdelfattah>> Preprocessing + MobileNet Model

Salma Salah>> SqueezeNet Model+ Github Managment

Fatema Tarek>> Inception(V3) Model + GUI

Nada Walied>> EfficientNet Model(B0)

Shahd Mamdouh>> EfficientNet Model(B1) + Documentation

Shahd Mohamed>> Model + GradCam

========================
