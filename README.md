# face-recognition-python3

## install these packages
  1. opencv
  2. numpy
  3. pillow

## There are three steps for face recognition:
  1. Collecting face data (your face pictures) and labels and save to dataset folder. (code 1)
  2. Input face data and labels into model to train a recognition model. (code 2)
  3. Open up your cam to start real time face recognition. (code 3)

## Instructions:
  1. Download this repository as a zip file and unzip it to a folder.
  
  2. Create two empty folders named 'dataset' and 'trainer' in the above folder.
  
  3. Run the first code, enter number '1' (for first person), then computer will take your face pictures and save into 'dataset' folder.
  When you finish taking pictures, "[INFO] Exiting Program and cleanup stuff" pops up.
  
  (3.5. Run the first code again, enter number '2' (for second person), follow the same procedure.) 

  4. Run the second code, just wait several seconds to train the model.
  
  5. Run the third code, it will open your camera and start realtime face recognition.
  
## Run the following commands in project root folder
    1. Dataset
       python3 dataset.py
    
    2. Training
       python3 training.py
       
    3. Face recognition
       python3 facerec.py
  
## Incase of issues while training on Macos or UNIX just run the command:
    cd into dataset folder then
    rm .DS_Store 
       
  7. enjoy!
 
 
  
