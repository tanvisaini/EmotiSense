# EmotiSense: A Deep Learning Approach to Speech Emotion Recognition.
This project aims to automatically recognize emotions from speech signals using different model approaches. 
This project is useful in various applications, such as mental health diagnosis, human-robot interaction, and 
speech-based emotion recognition in social media.

The project will use four publicly available datasets from different sources, namely:
1) Crowd Sourced Emotional Multimodal Actors Dataset (CREMA-D) : 
The CREMA-D is a collection of 7,442 unique video clips featuring 91 actors of different races, ethnicities, genders, and ages (20 to 74 years old). The actors recorded 12 different sentences expressing six different emotions (Anger, Disgust, Fear, Happy, Neutral, and Sad) at four different levels of intensity (Low, Medium, High, and Unspecified).
https://github.com/CheyneyComputerScience/CREMA-D

2) Emotional Speech Dataset: 
The RAVDESS dataset consists of 1440 recordings, which were made by 24 professional actors (12 female and 12 male). Each actor recorded two sets of statements with a neutral North American accent. The recordings cover seven different emotions, including calm, happy, sad, angry, fearful, surprise, and disgust, and each emotion is recorded at two levels of intensity: normal and strong. Additionally, there is a neutral expression included in the dataset. The total number of recordings comes from 60 trials per actor, multiplied by 24 actors.
https://zenodo.org/record/3255102#.ZD300S_MIdA

3) Surrey Audio-Visual Expressed Emotion (SAVEE):
The SAVEE database features recordings from four male native English speakers (named DC, JE, JK, KL), who were postgraduate students and researchers at the University of Surrey, aged between 27 to 31 years. The emotions captured in the database are based on discrete categories identified in psychological research, including anger, disgust, fear, happiness, sadness, surprise, and neutral. The aim is to provide recordings of seven distinct emotional categories. 
The text material consisted of 15 TIMIT sentences per emotion: 3 common, 2 emotion-specific and 10 generic sentences that were different for each emotion and phonetically-balanced. The 3 common and 2 × 6 = 12 emotion-specific sentences were recorded as neutral to give 30 neutral sentences. This resulted in a total of 120 utterances per speaker. https://tspace.library.utoronto.ca/handle/1807/24487

4) Toronto Emotional Speech Set (TESS):
Two female actresses, aged 26 and 64 years, recorded a set of 200 target words in the phrase "Say the word _" with each word spoken to convey one of seven emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral. 
This resulted in a total of 2,800 audio files. The dataset is structured such that each actress's recordings and emotions are in their own folder, 
and within each folder are the 200 target words' audio files in WAV format. https://tspace.library.utoronto.ca/handle/1807/24487               

# Hypothesis:

A deep learning approach using a Convolutional Neural Network (CNN) can accurately recognize emotions from speech signals 
with high performance when trained on diverse and comprehensive datasets such as Crema-D, Ravdess, Savee, and Tess. 
These datasets with different emotions can improve the model's generalization ability, making it suitable for real-world 
applications such as mental health diagnosis, human-robot interaction, and speech-based emotion recognition in social media.

# Data Mining and/or Machine Learning methods you plan to use (and why).
- Convolutional Neural Networks (CNN): CNNs are commonly used in image recognition tasks, but they can also be used for speech emotion recognition. CNNs can learn to extract features from the spectrogram of the speech signal, which can be used to classify the emotion.
- Data Augmentation: To enhance the performance of the model and to generalize the model, Data Augmentation is necessary. To make the model immune to perturbations, we have performed noise injection, shifting time, changing pitch and speed to our initial training set.
- Feature Extraction: Feature extraction is an important step in speech emotion recognition (SER) because it helps to transform raw speech signals into a set of relevant features that can be used to train machine learning models. 
- Sequential Model Building: In speech emotion recognition, sequential model building is beneficial because it allows the model to learn the temporal patterns in the audio signal.
- Confusion Matrix: Confusion matrix is an important evaluation metric for this project as it helps us to assess the performance of our speech emotion detection classifier and identify any areas where it may need improvement.





