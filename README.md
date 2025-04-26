Title: Machine Learning for Human Scream Detection 
Name: Molly Vitkevich
Datasets: Audio Files Obtained from https://www.freesoundeffects.com/

Methods:
- Librosa Library was used to load audio files and extract features
- A fully connected network, SVC, and KNN model were trained on the datasets and evaluated for accuracy
- Noise of varying standrd deviations was added to create testing datasets for the models to be tested on

Running the Code:
1. Download Datasets into two folders: "MLE_human_scream" and "MLE_nonscream"
2. Run the FinalProjectNoise1.pynb. Upload the contents of each folder (May need to run upload block twice)

Results:
1. All models performed similarly, about 87-89% accuracy
2. The addition of noise did not impact accuray of any model
