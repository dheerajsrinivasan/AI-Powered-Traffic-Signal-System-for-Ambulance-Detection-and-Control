# AI-Powered Traffic Signal System for Ambulance Detection and Control

## Project Overview

This project develops an intelligent traffic signal control system that detects ambulances approaching intersections using a combination of real-time audio classification, GPS tracking, and RFID authentication. Upon successful detection and verification, the system dynamically changes traffic signals to prioritize ambulance passage, thereby reducing emergency response times and improving urban road safety.

---

## Key Features

- Real-time classification of siren sounds using advanced audio feature extraction  
- Ambulance location tracking through GPS coordinates for proximity validation  
- Secure ambulance authentication via RFID tags to prevent unauthorized access  
- Dynamic traffic signal control to clear paths for emergency vehicles  
- Edge computing for low-latency audio processing combined with centralized decision making for safety and scalability

---

## Algorithms and Techniques Used

- **Audio Feature Extraction:**  
  - Mel-Spectrogram  
  - Chroma features  
  - Spectral Contrast  
  Extracted using the Librosa Python library

- **Machine Learning Model:**  
  - A fully connected neural network with three Dense layers  
  - Activation: ReLU and Softmax  
  - Regularization: Dropout layers to prevent overfitting  
  - Optimizer: Adam  
  - Loss Function: Categorical Cross-Entropy  

- **Geolocation Computation:**  
  - GPS data simulated and processed using the Geopy library  
  - Direction and distance calculated to estimate ambulance arrival

- **RFID Authentication:**  
  - Lookup against a predefined list of authorized RFID tags to verify ambulances  

---

## Performance and Accuracy

- Siren sound classification achieves approximately **75% accuracy** on test data  
- Non-siren recall reaches **100%**, with siren precision limited due to dataset size  
- GPS simulation has less than **5% error** in distance computation  
- RFID authentication is **100% accurate** on authorized tags  
- Traffic signal control responds in under **2 seconds** latency  

---

## Model Accuracy

<img width="1827" height="687" alt="image" src="https://github.com/user-attachments/assets/1934b3b7-fbd4-4226-8cf5-6c614c7fee0d" />

## Model Prediction
<img width="1820" height="308" alt="image" src="https://github.com/user-attachments/assets/22cfa270-e506-4446-9f89-d69800bc1939" />


