# Speech_Emotion_Recognition
This project uses Machine Learning to classify speech audio into three emotion categories: Happy, Sad, and Angry.

## About the Project
This project uses Machine Learning to classify speech audio into
three emotion categories: Happy, Sad, and Angry.

## Technologies Used
- Python
- Librosa for audio feature extraction
- NumPy
- Scikit-learn
- Random Forest Classifier
- Gradio for the web interface
- Google Colab

## Features
- Upload an audio recording
- Extract MFCC and other audio features
- Predict the likely emotion
- Display prediction scores through a Gradio interface

## Model Performance
The model achieved approximately 66.67% accuracy on the
speaker-disjoint test split used during development.

Results are experimental and may not generalize to real-world speech.

## How to Run
1. Install dependencies using requirements.txt.
2. Place app.py and speech_emotion_model.pkl in the same directory.
3. Run:

   python app.py

## Dataset
RAVDESS speech audio dataset.

## Limitations
The model was trained on acted emotional speech and predicts
only Happy, Sad, or Angry. Predictions may be inaccurate.
