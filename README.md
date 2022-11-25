# Air Vehicle Detector

#Purpose

This project was made to detect air vehicles. It was made for military use. The AI detects the image of the vehicle then would give out 2 different outputs depending on the two conditions shown below: 

-First if the vehicle is a threat it would warn the military that a harmfull vehicle has entered the countries premises. 

-Second if the vehicle is not a threat it would inform the military that a harmless vehicle has entered the countries premises.

#How it works

The AI would be given an image of any air vehicle (For now the AI has been trained to recognize 2 vehicles Harmless: (Hot air ballon), Harmfull: (Fighter Jet)), then it would categorize it in to its respective folder.

The AI has been given many images and has been trained to recognize Hot air balloons and Jets

#Setting Up the AI

First (In VS code) you will need to set up the Jetson-inference
 
- https://student.idtech.com/courses/184/pages/build-the-project-from-source?module_item_id=20688

Once you have that set up you will need to create your folders.

You can do the in Two different methods.

*First method: to the left of your screen where all the folders (in VS code) are located, left click on jetson-inference, then on python, then training, then classification. 

will need folders in both data and models:

- To start Right data then click - New Folder - Rename it whatever you want (But for this project name it Hotairballoon_Jet with all capitals included as we use it in the code to run the program).

- inside your folder you will need 2 ore folders Input - Output

- Next in models just make a New Folder by Right clicking on models and New Folder Rename it whatever you want (But for this project name it Hotairballoon_Jet)

*Second method


