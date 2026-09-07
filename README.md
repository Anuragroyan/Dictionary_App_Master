🤖 Sarcasm Detector

Sarcasm Detector is a React Native application that uses a TensorFlow Lite (TFLite) machine learning model to analyze user-provided text and classify whether it contains sarcastic content. The application performs inference directly on the device, enabling real-time predictions without requiring a backend or external API.

✨ Key Features

* 🤖 Sarcasm detection using a TFLite model
* 📝 User-provided text analysis
* 🧠 On-device machine learning inference
* 📊 Text classification and prediction
* ⚡ Real-time prediction results
* 🔒 Offline processing without a backend
* 🧹 Text preprocessing for model inference
* 📱 Cross-platform React Native implementation

🏗️ Architecture & Workflow

The React Native interface collects and prepares the user’s text for machine learning inference. The TensorFlow Lite model processes the input directly on the device and returns a classification result indicating whether the content is sarcastic. The prediction is then presented through the React Native UI.

🛠️ Tech Stack

React Native • JavaScript • Expo • TensorFlow Lite • Machine Learning • Text Classification • On-Device AI

▶️ Run the App

1. Install dependencies

npm install

2. Start Expo

npx expo start

3. Run on Android

npx expo start --android

4. Run on iOS

npx expo start --ios

5. Run on Web

npx expo start --web

Note: If the TFLite implementation uses native modules, an Expo Development Build may be required instead of Expo Go.

🎯 Project Purpose

This project demonstrates how TensorFlow Lite models can be integrated into React Native applications to perform offline text classification. It provides practical experience with mobile AI integration, model inference, text preprocessing, Expo development, and real-time machine learning predictions without relying on backend services.
