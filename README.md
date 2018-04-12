# EEmotion-CSNE-Hackaton
The code for the EEG-based ML emotion recognition. 
1. Pictures.ipynb -- a script to setup an experiment for recording emotions. Uses OpenCV to present emotions-provoking pictures from the GAPED dataset. The pictures are presented for 8 seconds per picture, in a random order, followed by 4-sec black screen.
2. Mapping_time.ipynb -- data preprocessing, filtering, feature extraction and training the ML model. (The script aligns the time of the EEG recordings from the OpenBCI EEG headset with the time of presented pictures. Then it extracts alpha, beta, gamma and theta oscillations of the braing activity and trains SVM, Random Forest, GradBoosting on that data). This script is more of a draft code.
3. Presentation.ipynb -- cleaned version of the mapping script with the demo for the presentation. Trains Random Forest. Simulates a "live demo" and performs EEG-based emotion recognition on the simulated datastream. Presents the stimuli and the predicted emotion.
