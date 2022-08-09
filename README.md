# Supervised_Contrastive_learning_for_onset_detection
Using Supervised contrastive learning for onset detection

This repository provides the code for implementing and testing the supervised contrastive model and the model from https://github.com/rohitma38/cnn-onset-detection for comparison.

Due to time and memory limitations only the contrastive model trained on the sythesized data set has been adde and the synthesized data set has been added.

Synthesized data set:

A synthesized data set has been uploaded for the purposes of running the code. Both a song list and a test list have also been provided. It should be noted that in all the code fles specific paths need to be set for the code to run properly. These paths should point to where the data has been saved.

Process Data:

The ProcessData code produces the data for training and testing the models. Once the correct paths has been set this should be able to be run without any adjustments.

Create training and test data:

The Create_training_and_test_data code takes the outputs from ProcessData and creates training and validation sets for training purposes. Once again, the correct file names must be used.

Create innacurate data:

The Create_innacurate_dataset code takes the training labels from Create_training_and_test_data and adds innacuracies.

Midi to Onsets:

Miditoonset code turns the midi data into onsets

Contrastive model and encoddings:

The Contrastive_model_and_encoddings code trains the supervised contrastive model and produces grouped vectors from this training. With correct file paths this should run without any change. 

Shulter_model:

The Shulter_model code implements the CNN found in https://github.com/rohitma38/cnn-onset-detection.

test:

The test code produces results from a given code for a given test set of songs. Any trained models can be used in this code.



