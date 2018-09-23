# ocr_watermeterreading

1) Original Image
<img src="images/originalimage.jpg" width="500">

2) Rotated Image 
<img src="images/rotatedimage.jpg" width="500">

3) Cropped Image 
<img src="images/croppedimage.jpg">

4) Extracting  black pixel region from the image.
<img src="images/firstpart_noise.jpg">

5) Removing Noise(unwanted black blocks) in the image. 
<img src="images/firstpart_noiseremoved.jpg">

6) Removing noise (small blocks) using filters. 
<img src="images/eroded.jpg">

7) Extracting red pixel region from the image.
<img src="images/secondpart.jpg">

8) Combining images from 6 and 7 stages
<img src="images/combinedimage.jpg">

9) Applying ocr on this combined image. 
<img src="images/finalimage.jpg">

10) Setup Installation

            ****  Software required :         1)opencv
                                        2)visual studio


            ****  Install visual studio and link opencv to visual studio.


            ****   Add deskew.h file to the project folder.


            ****  Create new .cpp file in the project
         
            **** copy trainingknnc++.txt  to the .cpp file created above.(Make sure that directory inside the imread points to the images in ocrknn folder)

            ****  copy watermeter_gaia.txt  to c++ file and change the directory to image of watermeter reading. 


=============================================================================================================================

•	It is one of the solution of Internet of Things where there is a requirement to implement OCR through  Computer Vision to digitalize the data on Watermeter.<br>
•	Implemented Region Growing Algorithm for the removal of Noise blobs and performed Noise reduction techniques like Dilation and Erosion.<br>
•	Applied K-Nearest Neighbours(supervised) Algorithm for the classification of digits.

==================================================================================================================


