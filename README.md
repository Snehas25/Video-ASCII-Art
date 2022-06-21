##VIDEO-ASCII-ART

## Project Description
ASCII(American Standard Code for Information Interchange) is a common encoding format used for representing text data in computers. Originally, the project is dedicated to transforming digital images to ASCII art. Digital images are stored in computers as two-dimensional rectangular array of pixels. Grayscale images have eight bits per pixel. Each pixel has value from 0 to 255, representing different shades of that color. These values from the digital image are converted in a manner forming ASCII art. The addition to the project is such that you can generate an ASCII art from a video clip.

## How to run the project
Download the zip file from github, run the ascii_image.py file to generate greyscale ascii art and similarily run the ascii_video.py file to generate video ascii art.
The ascii_video.py file is supported by Windows OS only.
You can change the input image and video files by adding your files in the 'data' folder and changing the name of the file in the code file accordingly.

## The internal working of the project
Each shade of the digital image color is represented by a number in the interval of 0 to 255 which can be denoted by an ASCII character.
In this project firstly the image is converted to grayscale (B/W). We’ll have a list that will contains ASCII characters based in ascending order of their luminosity.openCV is used to read the image data and load the image as an array. Now we use character mapping to convert the grey area into ASCII charcters based on the luminosity of each pixel.
In the video part of the project, the video is being broken down into different frames and each frame is then being converted into its ascii art form using character mapping and then displayed all together as a whole in the end.

## My learnings from the project
* Learnt about how images are stored in a computer. 
* Learnt about the character mapping and how in RGB images different channels in three different scales are fed to the display screen.
* Learnt about python libraries like opencv and pillow for image manipulation.
* Learnt how to asciify a video.

## Resources
* [How images are stored in a computer](https://alekya3.medium.com/how-images-are-stored-in-a-computer-f364d11b4e93)
* [ASCII Art](https://en.wikipedia.org/wiki/ASCII_art#Types_and_styles)
* [ASCII video art](https://medium.com/nerd-for-tech/doing-networked-video-ascii-art-in-python-4725b3ee552b)
