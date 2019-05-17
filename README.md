# Facial-Landmarks-Detection using Deep Learning(CNNs)
Here the following code with generate the 15 landmarks of face(left_eye_center, right_eye_center, left_eye_inner_corner, 
left_eye_outer_corner, right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end, left_eyebrow_outer_end, 
right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip, mouth_left_corner, mouth_right_corner, mouth_center_top_lip, 
mouth_center_bottom_lip).

You can also apply different types of filters on your face like different types of Glasses.Here i had used 6 different types of Glasses.
In the above code the filters I had used are 6 different types of Glasses which can be changed by just waving a blue colored material
in your OpenCV image Window.
This changing of the glasses is done using color filtering using Open CV.
You can add different types of filters in the filters portion of the code.
This code is built for filters which can be applied in front of eyes, you can change the position if you want to apply different 
types of filters in the code(in place of sunglasses in the code file)

Facial Landmarks detection can also be used for various purposes like:-

Facial feature detection improves face recognition                                                                    
Male vs Female Distinction                                                                             
Facial Expression Distinction                                                                      
Head pose estimation                                                                                   
Face Morphing                                                                              
Virtual Makeover                                                                                                                
Face Replacement                                                                                                                                                                                                         

## Execution
Order of Execution is as follows:

Step 0 - Download the file from [here](https://www.kaggle.com/c/facial-keypoints-detection/data) and create a folder named data and 
extract into it, it is compulsory to run.

Step 1 - Execute ``` python buildingModel.py ```

Step 2 - This could take a while, so feel free to take a break.

Step 3 - Execute ``` python main.py ```

Step 4 - Choose filters of your choice(I had included 6 here which can be applied in front of eyes, i.e. Glasses)

Step 5 - And don't forget to SMILE !



## Demo 1

<img src="https://github.com/kampaitees/Facial-Landmarks-Detection-/blob/master/Test%20Images/2.png" >



## Demo 2

<img src="https://github.com/kampaitees/Facial-Landmarks-Detection-/blob/master/Test%20Images/3.png" >
