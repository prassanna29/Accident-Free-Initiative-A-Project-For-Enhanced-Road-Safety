# Accident-Free-Initiative-A-Project-For-Enhanced-Road-Safety

This project presents an AI-powered Driver Drowsiness Detection System that integrates computer vision, deep learning, and environmental awareness to minimize road accidents caused by driver fatigue. The system monitors eye closure, yawning behavior, and weather conditions in real-time to identify signs of drowsiness and alert the driver through alarms.

Unlike conventional methods that rely only on facial features, this system provides context-aware fatigue detection by incorporating multi-modal data and weather-based analysis, enhancing safety in diverse real-world driving conditions.

-> Problem Statement

Millions of road accidents occur annually due to driver fatigue and lack of real-time alert systems. Traditional models fail to consider external factors like weather or adapt to individual driving behaviors.
This project addresses these limitations by building an adaptive, intelligent monitoring system capable of recognizing fatigue symptoms and predicting risks dynamically.

-> Proposed System

The Enhanced Driver Drowsiness Detection System introduces several innovative features:

🔹 Multi-modal Feature Integration: Combines eye, mouth, and weather indicators for improved accuracy.

🔹 Weather-Aware Detection: Considers external environmental factors such as rain, fog, and lighting that may impact drowsiness.

🔹 Deep Learning Integration: Uses CNN for accurate detection of eye closure and yawning patterns.

🔹 Haar Cascade Classifiers: Precisely localizes facial regions (face, eyes, mouth) even under varying lighting conditions.

🔹 Real-Time Risk Prediction: Continuously analyzes driver behavior and environment to anticipate risk scenarios.

🔹 Adaptive User Learning: Tailors alerts to individual driver behavior patterns over time.

🔹 Instant Alert System: Triggers an audible alarm whenever drowsiness symptoms are detected.

-> Methodology

The system workflow consists of several stages:

Model Loading:
Loads pre-trained CNN models for eye and yawn detection along with Haar Cascade classifiers for facial recognition.

Camera Input:
Captures real-time video feed from two cameras – one monitoring the driver’s face, another capturing the vehicle’s exterior weather conditions.

Feature Extraction:
Processes video frames to detect eye closure duration, yawning frequency, and weather-related parameters.

Classification:
Classifies driver’s state (alert, drowsy, yawning) using CNN predictions and evaluates weather influence.

Decision Module:

If eyes are closed or yawning detected, the system activates an alarm.

If driver is alert, no action is taken.

The system resets and continues monitoring continuously.

Alert Mechanism:
An audio alarm plays instantly to wake the driver and prevent accidents.

-> Technologies Used

Languages: Python

Libraries: OpenCV, TensorFlow/Keras, NumPy, Matplotlib

Models Used: CNN, Haar Cascade Classifiers

Hardware: USB Camera / Vehicle Camera Feed

-> Results

Eye and Yawning Detection Accuracy: ~96.18%

Weather Module Accuracy: 90%

Macro Average Precision: 0.91

Recall: 0.89

F1-score: 0.90

These results demonstrate the model’s ability to accurately identify fatigue patterns under varied weather and lighting conditions.

-> System Output

Displays “Eyes Opened” or “Eyes Closed” in real-time.

Shows “Yawning Detected” or “Not Yawning” status.

Triggers an alarm sound if drowsiness is detected.

Monitors weather influence and integrates it into risk estimation.

-> Future Scope

Expanding dataset for better generalization across demographics.

Integration with IoT-based in-vehicle systems and wearable sensors.

Implementing continuous video monitoring for long drives.

Collaboration with automotive companies to deploy the model in real vehicles.
