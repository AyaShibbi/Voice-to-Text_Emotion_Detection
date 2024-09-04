# Voice-to-Text_Emotion_Detection
This project aims to replicate the natural human ability to interpret emotions transmitted in spoken words by developing models using different techniques and algorithms in Natural Language Processing (NLP), Machine Learning (ML), and Deep Learning (DL). The goal is to detect emotions from speech by converting audio into text and then analyzing the text to determine the underlying emotion.
In this project, I've built and compared multiple models. I've tackled the development of models that convert voice data into text data and subsequently detect emotions from the transcribed text.

## The project is divided into two major parts:
### Part 1: Voice-to-Text 
Converting audio recordings into text using various models and comparing their performance.

### Part 2: Text Emotion Detection
Analyzing the text, using Natural Language Processing (NLP) techniques, to predict the emotion using different Machine Learning (ML) and Deep Learning (DL) models.

## Project structure:
This repository is structured into two main folders, each corresponding to the two parts of the project.

### 1. Part1_Voice_to_Text
This folder contains the materials related to the Voice-to-Text conversion process.
- *Dataset:* This folder contains the dataset used in this part, specifically the WAV files converted from MP3 format, and their corresponding texts.
- *Notebooks:* This folder contains the notebooks used for building and testing the Voice-to-Text models.

### 2. Part2_Emotion_Detection
This folder contains the materials related to Text Emotion Detection.
- *Dataset:* This folder contains the datasets used for training and testing the emotion detection models. The datasets include both balanced and unbalanced versions, as well as lemmatized and non-lemmatized text data.
- *Notebooks:* This folder contains the notebooks used for preprocessing the text data, training, and evaluating the various ML and DL models.

## Methodology:
### Audio Data Processing🔉
I explored various aspects of audio data processing, developing Voice-to-Text models using tools such as SpeechRecognition, Vosk, and OpenAI's Whisper. These models laid the groundwork for accurate text conversion from audio inputs.

### Text Preprocessing with NLP💬
Once the text was generated, I employed Natural Language Processing techniques to preprocess the data. I experimented with various text-to-numerical conversion methods, such as text vectorization and word embedding techniques, which are critical for preparing the data for emotion detection.

### Emotion Detection Models🧠
In the next phase, I implemented and compared traditional Machine Learning algorithms alongside Deep Learning models, specifically Long Short-Term Memory (LSTM) networks, to detect emotions within the text. The specific emotions I focused on were Joy, Sadness, Fear, Anger, Surprise, and Love. Fine-tuning these models and optimizing their performance was both challenging and enlightening.

### Data Analysis and Visualization 📊
I utilized tools like Scikit-learn, Pandas, Seaborn, and Matplotlib for data analysis and visualization to gain deeper insights and ensure robust results. This process has strengthened my analytical skills and has provided a clear representation of the project's outcomes.

This project has been an incredible learning journey. It has significantly improved my research capabilities, model development proficiency, and data analysis techniques.
