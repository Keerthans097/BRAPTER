# BRAPTER
BRAPTER: A Compact Braille Transput Communicator     

[BRAPTER.zip](https://github.com/Keerthans097/BRAPTER/files/10165461/BRAPTER.zip)

LINK: https://www.youtube.com/watch?v=Ci2CuKOAFfs


![IMG_20170829_141519201](https://user-images.githubusercontent.com/119934119/206006078-850704a7-a94e-4293-bf7b-09ec96e2057d.jpg)


![IMG-20170629-WA0044](https://user-images.githubusercontent.com/119934119/206006104-0a6b26bb-3e0a-403b-963f-a1d845d43ad8.jpg)


![IMG-20170529-WA0012 (1)](https://user-images.githubusercontent.com/119934119/206006132-ddee747d-49a3-458f-8b7b-7639f18520f7.jpg)



This project helps blind people in communication and also it has a storage mechanism where can take notes. The data stored can be either printed on braille paper or he can listen the stored content using headsets.
•	Model 1 – e-Notebook comprising of Braille Keys to input data in the Braille language and store it in the SD card.
•	Model 2 – Braille Printer used the data from the Notebook to print on the Braille paper
•	Implementation of audio mechanism to e-Notebook so that visually impaired person can also hear the words while typing.

The video link is available here

 1) https://www.youtube.com/watch?v=xllNP16e5_Q&list=PLMJokqjqAR_gH-KbJe5b01WSkan27ysAj&index=2

 2) https://www.youtube.com/watch?v=Sqaj03FUE5k&list=PLMJokqjqAR_gH-KbJe5b01WSkan27ysAj&index=3

 3) https://www.youtube.com/watch?v=3GqElYuGk40

Other Links : 

1) https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiSxMCE6uT7AhWc23MBHbTHAEgQFnoECBQQAQ&url=https%3A%2F%2Fieeexplore.ieee.org%2Fdocument%2F8309319&usg=AOvVaw1mQUBIu-axuiL5eQca7ZXO


2) https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiSxMCE6uT7AhWc23MBHbTHAEgQFnoECBcQAQ&url=https%3A%2F%2Ftransmitter.ieee.org%2Fmakerproject%2Fview%2Ff389e&usg=AOvVaw2FW9qMRe3B_LeYzKksrd-I


A handy device which is a set of braille e-notepad and an embosser that helps blind people to make notes
Code for Braille e-Notepad:

This is the code developed for the Braille e-Notepad Code Description The code is developed to implement the following functions:

1.Check if SD card is initialized

2.Take-in the braille input pattern and save it when '#' key is pressed

3.Compare the entered Braille pattern to the corresponding English abphabet and store it in a variable

4.Open the text file if exist, else create a new text file named Input_File.txt

5.If the file is successfully created, the write the alphabet to the file and close it

6.Play the audio response for the corresponding alphabet; The audio files are stored in the same SD card if the character is invalid, then print 'error'
Code for Braille embosser

This code is developed to operate the 'Braille Embosser'. Braille embosser is a custom made printer that reads the SD card and embossses the characters in Braille language. Two stepper motors used to traverse the punching head along X and Y axes. A servo motor is used to punch holes on the paper to emboss the braille characters on the paper along the Z axis.

The code works as follows:

1.initialize the SD card

2.open the file. note that only one file can be open at a time, so you have to close this one before opening another.

3.open the file for reading: Enter the file name that contains the characters to be printed If the file is opened successfully, read character by character and store it in an array and close the file

4.Punch the characters on the paper row by row; 30 characters per line Braille characters have 6 dots as shown- .. row 1, .. row 2, .. row 3 This algorithm prints the characters row by row.
