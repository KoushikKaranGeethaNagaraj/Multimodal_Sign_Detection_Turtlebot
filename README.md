# Multimodal_Sign_Detection_Turtlebot

# Simple, SVM Image classifier. 

It will train and test each time you run the code

The major gap is mainly due to the size of the dataset.

bot_vision.py - This code preprocesses each image, identify the signs at a given distance and crops the image based on the position of the signs. The SVM classifier acts on the cropped preprocessed image. The resulting model achieves around about 96.11% accuracy on 2022Simgs and 90.32% of 2022Figms dataset.

There are two ways to run this code:

1) With visualization of fed images:
python bot_vision.py
![WhatsApp Image 2024-02-04 at 14 04 29](https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/eb202be4-53ce-4929-b9fe-118b9291da05) ![WhatsApp Image 2024-02-04 at 14 04 30](https://github.com/KoushikKaranGeethaNagaraj/Multimodal_Sign_Detection_Turtlebot/assets/116392599/46e4723c-b132-4db4-ae5b-8fc74ea68c10)


2) Without visualization of fed images:
python -O bot_vision.py

NOTE: here the -O is the capital letter not zero.
