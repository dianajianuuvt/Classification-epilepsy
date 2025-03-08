# Epileptic Seizure Prediction

This project uses machine learning to predict whether a person is having an epileptic seizure based on EEG data. It does this by classifying signals into two categories: healthy and epileptic

Install the necessary libraries:

pip install numpy tensorflow scikit-learn matplotlib seaborn

Put your EEG data (from the opensource BONN dataset) in the ML_dataset/ML_dataset folder:
        S/: Files with seizure (epileptic) data
        Z/: Files with healthy (non-epileptic) data

        
Preprocessing: The EEG data is read, and all signals are resized to be 1000 numbers long. The data is then split into training and testing sets.

Model 1 (Neural Network):
        A simple neural network is trained to predict if the signal is epileptic or healthy.
        The network has 1 hidden layer with 16 neurons and uses ReLU activation.
        The output layer uses sigmoid to predict 0 or 1 (healthy or epileptic).
        
Model 2 (MLP Classifier):
        Uses scikit-learn's MLPClassifier with 3 hidden layers (16, 8, and 1 neuron).
        The model is trained and evaluated 100 times to get better results.

        
Results
- The models will print the accuracy of their predictions.
- A confusion matrix (a table showing the number of correct and incorrect predictions) will also be shown.
  
How to Use

- Download the correct folders (S/ for epileptic and Z/ for healthy).
- Run the code to train and test the models.
- The accuracy and confusion matrix will be displayed as a heatmap.

## Schedule

- Week 1: Research possible conferences for submission + edit the introduction part// SYNASC conference - done
- Week 2: Edit the state-of-the-art part. Search for more appers about multiple sclerosis. Talk with advisor about possible conferences for submission.// Started applying ML models on MS dataset (simple ann) - done
- Week 3: Add relevant papers about MS, trim down papers about epilepsy from SOTA. More research conferences if necessary.
- Week 4: Look at the results I already have on the epilepsy dataset. Twitch the codes where needed, quantify all the results in one place.
- Week 5: Try a new model for the epilepsy dataset. Write some comparasions on the reulsts I have.
- Week 6: More comparasions and conclusions about the results on the epilepsy dataset.
- Week 7: Present what I have so far to my advisor. Implement any given suggestions.
- Week 8: Start applying the exact same algorithms on the MS dataset.
- Week 9: Apply all the algorithms used on the epilepsy dataset on the MS dataset. Some comparasions.
- Week 10: Finish comparasions and conclusions. Final conclusions. Start editing.
- Week 11: Talk with advisor. Implement any sugggestions.
- Week 12: Edit edit edit.

Schedule somewhat flexible due to the unknown availability of advisor and the necessary time of complition for some tasks.

