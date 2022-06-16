# Wavelet Transform-based Convolutional Neural Network (2D-CNN)
The aim of the project is to determine left hand and right hand of imaginations of the paralyzed people using convolutional neural network (CNN).
The EEG data is recorded from a single subject while imagining left hand right hand movements. The experiment consists of 7 runs with 40 trials each. Given are 280 trials of 9s length. The first 2s was quite, at t=2s an acoustic stimulus indicates the beginning of the trial, the trigger channel (#4) went from low to high, and a cross “+” was displayed for 1s; then at t=3s, an arrow (left or right) was displayed as cue. At the same time the subject was asked to move a bar into the direction of a the cue. Three bipolar EEG channels (anterior ‘+’, posterior ‘-‘) were measured over C3, Cz and C4. The EEG was sampled with 128Hz, it was filtered between 0.5 and 30Hz.

# Propsed technique 
The 1-D signals were converted into 2-D images using continous wavelet transform (CWT). Next, these images were used to train a convolutional neural network (CNN) to determine the imagination of the subject.
