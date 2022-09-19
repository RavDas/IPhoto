# IPhoto
Semester 5 - CS3282 - Industrial Computer Engineering Project

# Introduction

Passport photo services can be expensive complex process. Obviously, not all photos taken at home with a smartphone camera will have the quality to meet photo ID requirements of International Civil Aviation Organization (ICAO) standards., but if you are on the budget and/or have the time to ensure you capture a picture of yourself with good resolution, proper focus and illumination, then this app will do the maths to prepare an output tiled photo ready to be printed for less than a dollar at your closest photo center. 

This app allows users to create passport photos with automatic picture size and rotation cropped to comply with the standards accepted in most countries. Users get a tiled photo in your required print format (e.g. 4"x6" or 5"x7") with the appropriate resolution ready for printing.


<br>
<br>

# Why IPhoto

Below are images taken labelled with the reasons why passport images should be taken with proper standards.
<br>
<br>

![3](https://user-images.githubusercontent.com/86109995/191017106-d29476d8-62f3-431f-a872-d2a088007679.png)

a) Asymmetric shadow on the left, b) Inhomogeneous background, c) Body parts

![6](https://user-images.githubusercontent.com/86109995/191017133-9aa43fb2-6d3e-4971-b4c3-b1c8589724c9.png)

a) Compliant portrait, b) Invisible crown, c) Invisible chin, d) Invisible crown and chin.


<br>
<br>
# Proposed System



![222](https://user-images.githubusercontent.com/86109995/191013628-266eadcf-1492-46e7-9d10-10296b79d84d.jpg)
 

<br>
<br>
# 

* Photo/Image should meet 65+ parameters in-order to be a valid photo/image 
(Pose angle, Lighting conditions, Background colour, Saturation, Symmetry etc. )
* High-definition cameras to provide the required resolution of the image.
* Real-time image analysis and processing
* Real-time feedback should be provided to the user 


<br>
<br>
# Project Tasks Plan


Tasks:

 * Detects face -> ML Kit Face Detection,
 
 * Verifies if the head is oriented straight, eyes are open and facial expression is neutral -> ML Kit Face Detection,
 
 * Segments person from the background -> TensorFlow lite munet model,
 
 * Verifies if background is plain and bright -> OpenCV,
 
 * Verifies if face does not contain shadows -> TensorFlow, OpenCv,
 
 TBD: verifies if eye pupils are directed towards camera,
 
 * Verifies if there are no objects partially covering face -> OpenCV,
 
 * After photo capturing attempts to improve face shadows -> TensorFlow lite GAN pix2pix model.
 
 * After photo capturing attempts to improve background -> OpenCv,
 
 * Adjust the photo to correct format and saves it to the phone,
 
 * If chosen, taken picture is saved multiple times on 15x10 cm paper for convinient printing.


Weeks	reserved for further testing (integration testing) and/or to catch up on any delays or faliures in prior weeks.





