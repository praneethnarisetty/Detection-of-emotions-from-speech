# Detection-of-emotions-from-speech
Voice Emotion - Decoding Feelings from Speech

## Project Title: Emotion Detection from Speech


### Description
This project focuses on detecting human emotions from speech using deep learning techniques. It leverages audio data from sources like RAVDESS, CREMA-D, and TESS datasets to train models that can classify emotions based on features extracted from speech. Technologies used include Python with libraries like Librosa for audio processing, Keras and TensorFlow for building and training neural network models, and Matplotlib and Seaborn for data visualization.

### Installation
Clone the repository:
git clone [https://github.com/yourusername/emotion-detection-from-speech.git](https://github.com/praneethnarisetty/Detection-of-emotions-from-speech)

Install required libraries:
pip install pandas numpy matplotlib seaborn librosa keras tensorflow

Make sure you have Python installed on your machine. 
This project is compatible with Python 3.x.Datasets
The project uses the following datasets:

RAVDESS: The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) dataset.
CREMA-D: Crowd-sourced Emotional Multimodal Actors Dataset (CREMA-D).
TESS: Toronto emotional speech set (TESS).

### Download and prepare the data by running:
kaggle datasets download -d uwrfkaggler/ravdess-emotional-speech-audio

kaggle datasets download -d ejlok1/cremad

kaggle datasets download -d ejlok1/toronto-emotional-speech-set-tess


### To run the project:

Navigate to the project directory.
Execute the main script:
python emotion_detection_script.py

Features
Audio signal processing and feature extraction.
Training deep learning models to classify emotions.
Visualization of training results and accuracy metrics.

### Contributions
Contributions are welcome! Please read the CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Thanks to Kaggle for providing the datasets used in this project.
Inspired by research in audio signal processing and emotional intelligence in speech.
