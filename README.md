# Speech Emotion Recognition
This is a Speech Emotion Recognition based on RAVDESS dataset, project repository for summer 2021, Brain and Cognitive Science Society.

Clone repo using:
```bat
git clone https://github.com/Aaka3021/Speech-Emotion-Recognition--1.git
```

## Abstract:

Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and the associated 
affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. 
Emotion recognition is a rapidly growing research domain in recent years. Unlike humans, machines lack the abilities to perceive 
and show emotions. But human-computer interaction can be improved by implementing automated emotion recognition, thereby 
reducing the need of human intervention.

In this project, basic emotions like calm, happy, fearful, disgust etc. are analyzed from emotional speech signals. We use machine learning techniques like Multilayer perceptron Classifier (MLP Classifier) which is used to categorize the given data into respective groups which are non linearly separated. We will also use CNN (Convolutional Neural Networks) and RNN-LSTM model. Mel-frequency cepstrum coefficients (MFCC), chroma and mel features are extracted from the speech signals and used to train the MLP classifier. For achieving this objective, we use python libraries like Librosa, sklearn, pyaudio, numpy and soundfile to analyze the speech modulations and recognize the emotion. 

Using RAVDESS dataset which contains  around 1500 audio file inputs from 24 different actors (12 male and 12 female) who recorded short audios in 8 different emotions, we will train a NLP- based model which will be able to detect among the 8 basic emotions as well as the gender of the speaker i.e. Male voice or Female voice.  
After training we can deploy this model for predicting with live voices.

## Deliverables:

Learn the basics of Python, ML/DL, NLP, librosa, sklearn, etc , Literature Review , analyzing the dataset and Feature extraction. Building and training the model on the training data, followed by testing on test data. And finally, testing the model on live audio input (unseen) and collecting the results:)


## Schedule:

Week1: 
  - covering ml\dl basics

Week 2:   
  - plotting waveform and spectrogram
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/waveform.png' width='50%' height='50%'>

  - learning audio preprocessing for feature extraction
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/spectrogram.png' width='50%' height='50%'>


Week 3:
  - Implementing the code for feature extraction using Librosa library
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/feature%20extract.png' width='50%' height='50%'>

<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/chroma.png' width='50%' height='50%'>

Week 4:
  - Implement the MLP model for emotion recognition
  - Evaluating it on test set
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/mlp.png' width='50%' height='50%'>

Week 5:
  - Implementing LSTM model
  - Starting to implement CNN model
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/cnn.png' width='50%' height='50%'>
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/cnn2.png' width='50%' height='50%'>

Week 6:
  - Complete the CNN model implementation.
  - Model will be evaluated on our voice
<img src='https://github.com/Shreyasi2002/SpeechEmotionRecognition/blob/master/images/record.jpg' width='50%' height='50%'>
    
    
## Results:

  - CNN model gave an accuracy of 71% 
  - LSTM model gave an accuracy of 66%
  - MLP model gave an accuracy of 62%

## References:

   - <a href='http://aishelf.org/audio-recog/'> http://aishelf.org/audio-recog </a> 
     
   - <a href='https://ijesc.org/upload/bc86f90a8f1d88219646b9072e155be4.Speech%20Emotion%20Recognition%20using%20MLP%20Classifier.pdf'> https://ijesc.org/upload/Speech_Emotion_Recognition </a>
     
   - <a href='https://rramnauth2220.github.io/blog/posts/code/200525-feature-extraction.html'> https://rramnauth2220.github.io/blog/posts/code/200525-feature-extraction.html </a>
   - <a href='https://musicinformationretrieval.com/spectral_features.html'> https://musicinformationretrieval.com/spectral_features.html </a>
   - <a href='https://www.machinecurve.com/index.php/2019/07/27/how-to-create-a-basic-mlp-classifier-with-the-keras-sequential-api/'> https://www.machinecurve.com/how-to-create-a-basic-mlp-classifier-with-the-keras-sequential-api/ </a>
   - <a href='http://www.jcreview.com/fulltext/197-1594073480.pdf?1625291827'> http://www.jcreview.com/fulltext/197-1594073480.pdf?1625291827 </a>
   - <a href='https://machinelearningmastery.com/k-fold-cross-validation/'> https://machinelearningmastery.com/k-fold-cross-validation/ </a>
   - <a href='https://towardsdatascience.com/multi-layer-perceptron-using-tensorflow-9f3e218a4809'> https://towardsdatascience.com/multi-layer-perceptron-using-tensorflow-9f3e218a4809 </a>
   - <a href='https://machinelearningmastery.com/k-fold-cross-validation/'> https://machinelearningmastery.com/k-fold-cross-validation/ </a>


     
