# EEmotion-CSNE-Hackaton
The code for the EEG-based ML emotion recognition. 
1. Pictures.ipynb -- a script to setup an experiment for recording emotions. Uses OpenCV to present emotions-provoking pictures from the GAPED dataset.
2. Mapping_time.ipynb -- data preprocessing, filtering, feature extraction and training the ML model. (The script aligns the time of the EEG recordings from the OpenBCI EEG headset with the time of presented pictures. Then it extracts alpha, beta, gamma and theta oscillations of the braing activity and trains Random Forest on that data)
3. Presentation.ipynb -- version of the above script with the demo for the presentation. Simulates live demo and performs EEG-based emotion recognition. Presents the stimuli and the predicted emotion.
