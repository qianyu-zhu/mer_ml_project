# mer_ml_project

This is the final project for CSCI-SHU 360 machine learning, focusing on music emotion recognition. We used self-collected dataset, containing 7193 songs from Spotifys Web API. We aminly employed librosa package to extract spectrum from midi file, and use both traditional models (SVM & random forest) and NN models (CNN, DNN, LSTM), and the experiment result shows the potential of spectrum analysis in music emotion recognition and more generalized tasks.

With the aim of classifying different songs based on the emotions they can inspire, this project trains different machine learning models with different sets of features. We stack traditional models including SVM and random forests, train it with the shallow features provided by Spotifys API, yielding an average precision of 0.76. recall 0.77, f1-score 0.76 for three-class classification task. This comparatively low accuracy can be attributed to the limited size of the dataset and the inherent errors in the labels. In comparison, the more complicated CLDNN model (CNN + LSTM + DNN), achieves an accuracy of 90.56% in binary classification.

A short presentation [slides](https://github.com/qianyu-zhu/mer_ml_project/blob/main/Final_presentation.pdf).
Details in [paper](https://github.com/qianyu-zhu/mer_ml_project/blob/main/Music_emotion_recognition.pdf).
