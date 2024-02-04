# Multimodal_Sign_Detection_Turtlebot

# Simple, SVM Image classifier. 

This project aims to use SVM to perform sign detection and apply on a Turtlebot and it will train and test each time you run the code.<be>

The major gap is mainly due to the size of the dataset.<be>

SignDetectionSVM.py - This code preprocesses each image, identifies the signs at a given distance, and crops the image based on the position of the signs. The SVM classifier acts on the cropped preprocessed image. The resulting model achieves around about 96.11% accuracy on 2022SignDataset1 and 90.32% on 2022SignDataset2 dataset.<be>

There are two ways to run this code:<be>

1) With visualization of fed images:<be>
python SignDetectionSVM.py<be>
3) Without visualization of fed images:<be>
python -O SignDetectionSVM.py<be>

NOTE: here the -O is the capital letter, not zero.<be>

The SignDetectionROS2.py can be used to run it on the turtlebot.

The implementation of Sign Detection is below.
<p align="center">
  <img src="https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/eb202be4-53ce-4929-b9fe-118b9291da05" alt="Image 1" width="500" height="250"/>
  <img src="https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/46e4723c-b132-4db4-ae5b-8fc74ea68c10" alt="Image 2" width="500" height="250/>
</p>

<!-- ![WhatsApp Image 2024-02-04 at 14 04 29](https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/eb202be4-53ce-4929-b9fe-118b9291da05) ![WhatsApp Image 2024-02-04 at 14 04 30](https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/46e4723c-b132-4db4-ae5b-8fc74ea68c10) -->



