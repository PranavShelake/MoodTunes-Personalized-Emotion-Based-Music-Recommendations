# MoodTunes

**Description:**  
MoodTunes is an emotion-based music recommendation model designed to enhance your listening experience based on your current mood. By capturing your emotions through video, MoodTunes provides personalized song suggestions that match your feelings. Additionally, it offers details about the artists and the language of the music to enrich your discovery process.

**Technologies Used:**  
- **Streamlit:** For creating the interactive web application interface.
- **Streamlit WebRTC:** To handle real-time video streaming and processing.
- **OpenCV:** For video frame manipulation and emotion detection.
- **MediaPipe:** For extracting facial and hand landmarks to determine emotions.
- **Keras:** For loading and using a pre-trained emotion recognition model.

**Features:**  
- **Emotion Detection:** Uses video input to identify and analyze emotional states based on facial and hand gestures.
- **Personalized Recommendations:** Provides song suggestions tailored to the detected emotion, with options to specify the language and singer.
- **Real-Time Processing:** Captures and processes emotions in real-time, displaying recommendations instantly.
- **Artist and Language Details:** Enables users to discover information about artists and the language of the recommended music.

**Challenges Overcome:**  
Implementing real-time emotion detection involved integrating complex technologies for video processing and machine learning. Ensuring accurate and timely recommendations required efficient handling of video frames and model predictions.

**Outcome:**  
MoodTunes offers an innovative and interactive way to discover music based on your mood, combining advanced emotion recognition with personalized music recommendations. It provides an engaging user experience and enriches the music discovery process.
