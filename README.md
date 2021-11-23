# Persian Digit Recognizer Pytesseract

Pytesseract is recognized as a tool that can recognize the text objects in a given image and can translate them to their corresponding strings. 
- in the first part, I installed it on my collab. 
- I loaded the Pytesseract for the Persian language in the second part. 
- Then, I made a function which prob the images for objects that pytesseract consider tham similar to special charachters (Persian digits in this case).   ['1','2','3','4','5','6','7','8','9','0','٠','١','٢','٣','٤','۴','٥','۵','٦','۶','٧','٨','٩']
- Then, I used the coordinates of these objects in Pytesseract and applied a rectangle to the image in those coordinates.
- I show the image with drawn rectangles.   

You can see an example of using this method in the bellow image:    

![image](https://user-images.githubusercontent.com/67642255/142974549-d7340e54-fdf4-4218-bccf-8cfd17c303a7.png)    

