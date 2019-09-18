# Speaker-Identification
implementing of binary Classifier to classify between two speakers Using train data contains about an hour, Achieving 100% Accuracy.
in spk_id_raw_data.ipynb, i feed the raw audio data to a NN of three Dense Layers and after just six epochs, the training accuracy reached 100% but the valdation was almost 65% which indicates that clearly there was Overfittin.
in spk_id_spectogram.ipynb, i used the spectrogram of the audio data as a feature extraction using LIBROSA, then i feed them to a NN of four Counvolutional Layers then two Dense layers and using Dropout to reduce Overfitting.
after just three epochs, the train and validation accuracies reached 100%  
