# Mentis Mirror: A Magical Emotion-Sensing Smart Mirror

Mentis Mirror is an intelligent emotion-aware smart mirror, inspired by the wizarding world of Harry Potter. It detects the user's facial emotions in real-time, logs environmental sensor data (temperature, sound, TVOC, CO₂), and reflects back personalized magical feedback. The prototype combines Machine Learning, Streamlit UI, DeepFace emotion recognition, and MySQL database integration.

## ✨ Project Highlights

- 🧠 *Emotion Detection* using DeepFace and OpenCV.  
- 📊 *Sensor Data Logging* (temperature, sound, CO₂, TVOC).  
- 🪄 *Harry Potter-Themed UI* with magical creatures and animations.  
- 🗃 *MySQL Integration* for logging and reviewing emotion-sensor data.  
- 🧾 *Interactive Viewer Tab* to explore historical data entries.  

---

## 🧰 Tech Stack

- *Frontend*: Streamlit (Python), Custom CSS, Animated Effects  
- *Backend*: Python, DeepFace, OpenCV, MySQL  
- *Database*: MySQL (with fallback to local file logging)  
- *Sensors (Simulated)*: ESP32 via Wokwi (for future IoT integration)  

---

## ⚙ Setup Instructions

1. *Clone the repository*:
   bash
   git clone https://github.com/your-username/mentis-mirror.git
   cd mentis-mirror

2. **Create and activate virtual environment**:

    bash
    python -m venv deepface_env
    source deepface_env/bin/activate  # On Windows: deepface_env\Scripts\activate

3. *Install dependencies*:

    bash
    pip install -r requirements.txt

4. **Run the application:

    bash
    streamlit run app.py

##  Key Functionalities

- Real-time Emotion Recognition via webcam.

- Magical Mirror UI: Emotions trigger animations, quotes, and popups.

- Environmental Awareness: Sensor values are displayed and logged.

- Log Viewer: Explore historical logs with timestamped data.

- Fallback Logging: If MySQL is not available, data is stored locally.


## 🔮 Future Enhancements
1. 🌐 IoT Simulation + Physical Prototype 
- Integrate Wokwi-based ESP32 simulation into a physical prototype.

- Use real sensors (DHT11, MQ135, Mic Sensor) for environmental data collection.

- Connect ESP32 data to Streamlit UI via MQTT or RESTful API.

2. 🔊 Sound-Based Emotion Detection 
- Implement voice tone analysis using pyAudioAnalysis, librosa, or speechbrain.

- Fuse facial and audio cues for multi-modal emotion recognition.

- Improve accuracy and response sensitivity with audio-visual analysis.

## 👩‍💻 Contributors

*Survi Mukherjee* – Developer, UI Designer, Emotion Logic, Integration


## "The Mirror shows not your face, but your heart's true reflection.” — Mentis Mirror"
