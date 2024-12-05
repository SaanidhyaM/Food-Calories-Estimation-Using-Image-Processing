#Minimum Requirements
1)	Windows 10 Pro CPU
2)	Anaconda Distribution 4.6.11
3)	Python
4)	Tensorflow
5)	Tflearn
#Dataset Used
FOODD - (https://www.kaggle.com/datasets/darsh22blc1378/foodd-ieee-datasets)
#Setup
1.	Run the following command in the terminal
“!pip uninstall tflearn
  !pip install git+https://github.com/MihaMarkic/tflearn.git@fix/is_sequence_missing
  !pip install Pillow==9.5.0” 
2.	Download data from the above FOODD link under the folder FOODD and run
“train.py”
3.	This trains the model present in “cnn_model.py”
4.	Calorie calculation and food item detection is done by “calorie.py” and “image_segment.py”. A separate folder will be created named images, showcasing the actions done on test image once you follow the next setup instruction. 
5.	Run “demo.py” to see the model result for “test_image.jpg”
#Limitations
1.	Actual weight and calories can’t be found due to image quality
2.	Difficult to find an appropriate angle between the fruit and the camera
3.	Lighting conditions i.e pixel changes with respect to light
#Scope Of Improvement
1.	Estimate the calories from all types of fruits and foods.
2.	Minimize error of calorie estimation

