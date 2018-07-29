# lisn
An android application that extracts english text from images and allows to read aloud the text and also translates it into malayalam.
The app allows the users to select image by taking new picture or from gallery. 
The image can be cropped manually by user to select only needed portion of the image.
Before processing the image it will undergo preprocessing using OpenCv. The image is converted into Gray Scale and process the image using Tesseract API.
We use Google TextToSpeech API to read aloud the text an Translate API to get the malayalam translation of the text(*Translate temporarily unavailable since the trial period of API has expired*) 

**The app needs OpenCV Manager to be installed on the device in order to work**
