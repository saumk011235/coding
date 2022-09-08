# Saumya Kothari - Introduction to Neural Networks and Deep Learning Project 


## Part 1

#### DOMAIN: 
Electronics and Telecommunication

#### CONTEXT: 
A communications equipment manufacturing company has a product which is responsible for emitting informative signals. Company wants to build a machine learning model which can help the company to predict the equipment’s signal quality using various parameters.

#### DATA DESCRIPTION: 
The data set contains information on various signal tests performed:
1. Parameters: Various measurable signal parameters.
2. Signal_Quality: Final signal strength or quality

#### PROJECT OBJECTIVE: 
The need is to build a regressor which can use these parameters to determine the signal strength or quality [as number].
Steps and tasks: [ Total Score: 10 points]
1. Import data.
2. Data analysis & visualisation
• Perform relevant and detailed statistical analysis on the data.
• Perform relevant and detailed uni, bi and multi variate analysis.
Hint: Use your best analytical approach. Even you can mix match columns to create new columns which can be used for better
analysis. Create your own features if required. Be highly experimental and analytical here to find relevant hidden patterns.
3. Design, train, tune and test a neural network regressor.
Hint: Use best approach to refine and tune the data or the model. Be highly experimental here.
4. Pickle the model for future use.


## Part 2

#### DOMAIN:
Electronics and Telecommunication

#### CONTEXT: 
A communications equipment manufacturing company has a product which is responsible for emitting informative signals. Company wants to build a machine learning model which can help the company to predict the equipment’s signal quality using various parameters.

#### DATA DESCRIPTION: 
The data set contains information on various signal tests performed:
1. Parameters: Various measurable signal parameters.
2. Signal_Quality: Final signal strength or quality

#### PROJECT OBJECTIVE: 
The need is to build a classifier which can use these parameters to determine the signal strength or quality [as number].
Steps and tasks: [ Total Score: 10 points]
1. Import data.
2. Data analysis & visualisation
• Perform relevant and detailed statistical analysis on the data.
• Perform relevant and detailed uni, bi and multi variate analysis.
Hint: Use your best analytical approach. Even you can mix match columns to create new columns which can be used for better
analysis. Create your own features if required. Be highly experimental and analytical here to find relevant hidden patterns.
3. Design, train, tune and test a neural network regressor.
Hint: Use best approach to refine and tune the data or the model. Be highly experimental here.
4. Pickle the model for future use.



## Part 3
#### CONTEXT: 
Develop a clickable GUI [desk application or web service application] which can automate Part I & II of this project.




## Part 4
#### DOMAIN:
Autonomous Vehicles

#### BUSINESS CONTEXT: 
- A Recognising multi-digit numbers in photographs captured at street level is an important component of modern-day map making. A classic example of a corpus of such street-level photographs is Google’s Street View imagery composed of hundreds of millions of geo-located 360-degree panoramic images.
- The ability to automatically transcribe an address number from a geo-located patch of pixels and associate the transcribed number with a known street address helps pinpoint, with a high degree of accuracy, the location of the building it represents. More broadly, recognising numbers in photographs is a problem of interest to the optical character recognition community.
- While OCR on constrained domains like document processing is well studied, arbitrary multi-character text recognition in photographs is still highly challenging. This difficulty arises due to the wide variability in the visual appearance of text in the wild on account of a large range of fonts, colours, styles, orientations, and character arrangements.
- The recognition problem is further complicated by environmental factors such as lighting, shadows, specularity, and occlusions as well as by image acquisition factors such as resolution, motion, and focus blurs. In this project, we will use the dataset with images centred around a single digit (many of the images do contain some distractors at the sides). Although we are taking a sample of the data which is simpler, it is more complex than MNIST because of the distractors.

#### DATA DESCRIPTION: 
The SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with the minimal requirement on data formatting but comes from a significantly harder,
unsolved, real-world problem (recognising digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images. Where the labels for each of this image are the prominent number in that image i.e. 2,6,7 and 4 respectively.
The dataset has been provided in the form of h5py files. You can read about this file format here: http://docs.h5py.org/en/stable/high/dataset.html

Acknowledgement: Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng Reading
Digits in Natural Images with Unsupervised Feature Learning NIPS Workshop on Deep Learning and
Unsupervised Feature Learning 2011. PDF
http://ufldl.stanford.edu/housenumbers as the URL for this site when necessary

#### PROJECT OBJECTIVE: 
We will build a digit classifier on the SVHN (Street View Housing Number) dataset.
Steps and tasks: [ Total Score: 30 points]
1. Import the data.
2. Data pre-processing and visualisation.
3. Design, train, tune and test a neural network image classifier.
Hint: Use best approach to refine and tune the data or the model. Be highly experimental here to get the best accuracy out of the model.
4. Plot the training loss, validation loss vs number of epochs and training accuracy, validation accuracy vs number of
epochs plot and write your observations on the same.
