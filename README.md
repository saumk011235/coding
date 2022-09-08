# Saumya Kothari - Computer Vision Project 2

# Part 1

#### DOMAIN: 
Entertainment


#### CONTEXT: 
Company X owns a movie application and repository which caters movie streaming to millions of users who on subscription basis.
Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the
movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision
and multimedia experts who need to detect faces from screen shots from the movie scene.


#### DATA DESCRIPTION: 
The dataset comprises of images and its mask where there is a human face.

Acknowledgement for the dataset http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/

Mobile Net paper: https://arxiv.org/pdf/1704.04861.pdf


#### PROJECT OBJECTIVE: 
Face detection from training images.
Steps and tasks: [ Total Score: 20 points]
1. Import the dataset.
2. Create features (images) and labels (mask) using that data.
3. Mask detection model:
● Design a face mask detection model.
 Hint: Use U-net along with pre-trained transfer learning models
● Design your own Dice Coefficient and Loss function.
● Train, tune and test the model.
● Evaluate the model using testing data.
4. Use the “Prediction image” as an input to your designed model and display the output of the image.



# Part 2

#### DOMAIN: 
Face recognition

#### CONTEXT: 
Company X intends to build a face identification model to recognise human faces.

#### DATA DESCRIPTION: 
The dataset comprises of images and its mask where there is a human face.

#### PROJECT OBJECTIVE: 
Face Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken
from 'Pinterest' and aligned using dlib library. 

#### TASK:
In this problem, we use a pre-trained model trained on Face recognition to recognise similar faces. Here, we are particularly
interested in recognising whether two given faces are of the same person or not. Below are the steps involved in the project.
- Load the dataset and create the metadata.
- Check some samples of metadata.
- Load the pre-trained model and weights.
- Generate Embedding vectors for each face in the dataset.
- Build distance metrics for identifying the distance between two given images.
- Use PCA for dimensionality reduction.
- Build an SVM classifier in order to map each image to its right person.
- Import the the test image. Display the image. Use the SVM trained model to predict the face.
