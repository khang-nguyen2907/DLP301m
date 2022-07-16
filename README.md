# DLP301m
## Wav2vec 2.0 model for Speech Emotion Recognition
- Notebook ```data_preprocessing.ipynb``` shows the code combining 2 kinds of dataset (TESS and RAVDESS), split data into train and validation dataset (8:2) and the way how to pre-processing the speech data in the dataset after combining. The library used to pre-process data is Huggingface - Transformers
- Notebook "EVMR_notebook.ipynb" shows the code of using model Wav2vec 2.0 model for the Speech Emotion Recognition task. It loads pre-processed data, initializes model, train and evaluate model, and predict samples. 

## LSTM-CNN
- Notebook ```voice_lstm.ipynb``` shows the code of preprocessing speech data before feeding to 2 kinds of RNN-CNN model, train and result after training progress that our team presented in the report. 
