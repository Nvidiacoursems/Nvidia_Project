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

- inside Output make two more folders in the same way but name them "Jet" and "Hotairballoon"

- Next in models just make a New Folder by Right clicking on models and New Folder Rename it whatever you want (But for this project name it Hotairballoon_Jet)

*Second method

- in your terminal write - cd jetson-inference/python/training/classification - without the -'s in the begining or end

- for data write - cd data - , then write - mkdir _name_ (for this project I recomend using Hotairballoon_Jet) then cd into it (by writing - cd Hotairballoon_Jet -) then write - mkdir input - and - mkdir output -  then make 2 more folders in Output (- cd Output -) (- mkdir name -) but name one - Hotairballoon- and one -Jet- then cd out three times by wirting cd .. 3 times after eachother

- next write - cd models - and write - mkdir Hotairballoon_Jet - and then - cd .. - then you should be all set.  

*Placing the files

- From https://github.com/Nvidiacoursems/Nvidia_Project open models/Hotairballoon_Jet and download each file by opening them and clicking the download button

- Once they are downloaded take the files from there dowloaded location in file explorer and select them, drag and drop them into the Hotairballoon_Jet you created in the models folder

- Next we will need images for the AI to run

- in google search hot air balloon and download images (Do the same for the Jet) (be sure they are .png files) then move the images to there coresponding folders in data/Hotairballoon_Jet/Input (Jet/Hotairballoon)

- Rename them:
 
 - if they are in the Jet folder (Jet01) if you have 2 images then the second one should be 02 and so on.
 
 - if they are in the Hotairballoon folder (Hotair01) if you have 2 images then the second one should be 02 and so on.
 
*Running the program

- done

