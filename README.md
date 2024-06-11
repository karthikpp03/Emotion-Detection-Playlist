# 🎵 Emotion-Based Music Recommendation System 🎵

![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Framework-red.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep_Learning-orange.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-blue.svg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the Emotion-Based Music Recommendation System! This project captures the user's facial expressions, detects their emotions in real-time using a webcam feed, and recommends music tracks based on the detected emotions. The recommendation engine leverages a pre-trained emotion detection model and a curated music dataset.

## Features
- **🎥 Real-time Emotion Detection**: Capture and analyze facial expressions using a webcam.
- **🎶 Music Recommendation**: Recommend songs based on detected emotions.
- **🌐 Interactive Web Interface**: Built with Streamlit for a seamless user experience.
- **🖼️ Aesthetic Background**: Visually appealing UI with a dynamic background.

## Setup and Installation

### Prerequisites
- 🐍 Python 3.x
- 📦 Streamlit
- 📷 OpenCV
- 🧠 TensorFlow/Keras
- 📝 Pandas

### Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/EmotionMusicRecommendation.git
    cd EmotionMusicRecommendation
    ```

2. **Install required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download pre-trained model weights**:
    Place the pre-trained model file (`model.h5`) in the appropriate directory as specified in the code. Download the model from [here](https://yourcloudlink.com/model.h5).

### Configuration
1. **Update Dataset Path**: Ensure the path to your music dataset CSV file is correctly set in the script (`df = pd.read_csv("E:/PROJECT/PROGRAMS/emotio playlist detect/muse_v3.csv")`).
2. **Update Model Path**: Ensure the path to your pre-trained model is correctly set in the script (`model.load_weights('E:/PROJECT/PROGRAMS/emotio playlist detect/model.h5')`).

## Usage

### Running the Application
1. **Start the Streamlit App**:
    ```bash
    streamlit run app.py
    ```
2. **Interact with the Application**:
    - Click the "SCAN EMOTION(Click here)" button to start the webcam and detect emotions.
    - The detected emotions will be displayed along with recommended songs.

### Interacting with the Recommendations
- The recommended songs will be displayed with clickable links that redirect to the respective music websites.
- Each recommendation includes the song name and artist.

## Project Structure
```
EmotionMusicRecommendation/
│
├── app.py                        # Main application script
├── requirements.txt              # List of dependencies
├── model.h5                      # Pre-trained model file
├── muse_v3.csv                   # Music dataset
├── README.md                     # Project documentation
└── haarcascade_frontalface_default.xml # Haarcascade classifier for face detection
```

## Dataset
The music dataset (`muse_v3.csv`) contains tracks with associated emotional tags, valence tags, and other relevant information:
- `name`: Track name
- `emotional`: Number of emotion tags
- `pleasant`: Valence tags
- `link`: URL to the track
- `artist`: Artist name

## Contributing
We welcome contributions to enhance the functionality and features of this project. Please fork the repository, create a new branch, and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file according to your specific project details and preferences.
