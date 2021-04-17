# Face-Recognition-Using-OpenCV
This is a basic face recognition program which captures the face using the webcam. The captured faces are stored and trained by python's OpenCV inbuilt function. 
The project also has a database to store the name and id. (SQL)
This project involves 3 phases.
1. Creating a DataSet
In this  phase the users face is captured and 20 different frames are stored in a folder to be trained later.
This is done using opencv's imwrite function which encodes the grayscale image and writes the data into folder.
2. Training the model
This phase focuses on traning the photos that are stored in the folder. Each model is given a new id and a name to correspond to in the final phase.
The system is trained to recognize the photos and a model is created in a new folder.
3. Detection
This is the final phase where the users face is captured and checked if the model has already trained to recognise the encodings.
If the id  is  found, the corresponding name is displayed on the  screen.


