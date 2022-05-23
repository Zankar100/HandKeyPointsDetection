# HandKeyPointsDetection
Computer Vision Hand Cricket game implemented with Hand Key Points detection using a video camera interface. 

## For dataset:
1. Download the full images dataset for training from:
https://lmb.informatik.uni-freiburg.de/projects/freihand/
2. Use the training/rgb folder to get the images for training. Use training_K.json and training_xyz.json for getting the points. Additionally, since the json files give the information for all the images, if you want to train on just a few images, indexing can be used to get the data of those few images.
3. We have included our own test folder for testing. Put this test folder under the image dataset root folder.

## For training and testing:
We will be doing this in Hand_cricket_training.ipynb file
1. For initial check and testing, modify project root to reflect your local location, restart and run all cells.
2. If you want to do a fresh training, ensure that the project root doesn’t have the models folders.
3. To continue training on an existing cell, uncomment the cell if you want to run the training.

## For running the Game interface:
1. Run the Countfingers.ipynb
2. Show hand sign in the displayed rectangular box.
3. Hold the hand sign until the video capture pauses. Finger count is displayed for each
video frame.
4. To resume the video, press ‘r’ from the keyboard. Finger count is updated in the total
score and displayed as the previous play score.
5. Bot play continues automatically after the player is out.
6. New game starts automatically after the current game ends.
7. To stop the game UI, press ‘z’ while the UI is in video capture mode. If the UI is in pause
mode, press ‘r’ to resume and then press ‘z’ to stop.
 
