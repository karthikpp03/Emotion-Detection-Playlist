# 🎵 Emotion-Based Music Recommendation System 🎵

![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Framework-red.svg)

## Technologies Used

<div align="center">
<p align="center">  <img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
<img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="100">
<img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="100">

<img src="https://user-images.githubusercontent.com/74038190/212281775-b468df30-4edc-4bf8-a4ee-f52e1aaddc86.gif" width="100">

  
<img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/de038172-e903-4951-926c-755878deb0b4" width="100">


</div>
<br><br>    

## Sample Images

<img src="Images/1.jpeg" alt="Dashboard Screenshot" width="600"/>
<img src="Images/2.jpeg" alt="Dashboard Screenshot" width="600"/>
<img src="Images/3.jpeg" alt="Dashboard Screenshot" width="600"/>
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


Feel free to customize this README file according to your specific project details and preferences.

Happy coding!

# 🌐 Contact Through: 
<p align="left">
  <a href="https://www.facebook.com/ruban.swe.3" target="blank"><img align="center" src="https://user-images.githubusercontent.com/74038190/235294010-ec412ef5-e3da-4efa-b1d4-0ab4d4638755.gif" alt="karthik03" height="100" width="100" /></a>
  <a href="https://www.linkedin.com/in/karthik-pp-b80b38237/" target="blank"><img align="center" src="https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif" alt="karthik pp" height="100" width="100" /></a>
  <a href="https://www.instagram.com/ig_._karthik/" target="blank"><img align="center" src="https://user-images.githubusercontent.com/74038190/235294013-a33e5c43-a01c-43f6-b44d-a406d8b4ab75.gif" alt="karthik" height="100" width="100" /></a>
  <a href="https://instagram.com/ig_._karthik" target="blank"><img align="center" src="https://user-images.githubusercontent.com/74038190/235294015-47144047-25ab-417c-af1b-6746820a20ff.gif" alt="ig_._karthik" height="100" width="100" /></a>
  <a href="https://www.youtube.com/@KARTHIK4332" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="karthik plays" height="100" width="100" /></a>
</p>

