# AI_Healthcare_Project

Dengue AI Assistant with Risk Prediction and Voice Interaction

title: Disease Prediction Of Dengue
emoji: 📊
colorFrom: gray
colorTo: pink
sdk: gradio
sdk_version: 5.23.0
app_file: app.py
pinned: false
Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

Project Overview

This project provides an AI-powered assistant that predicts dengue outbreak risk based on weather parameters. Featuring both voice interaction and a user-friendly web interface, it makes dengue risk assessment accessible to everyone.

Key Features

Multilingual Voice Interaction: Speak to the system and get voice responses in your language
Weather-Based Prediction: Uses machine learning to analyze temperature, humidity, rainfall, and season
Dual Interfaces: Access via voice assistant or web form based on preference
Regional Language Support: Voice responses available in Hindi, Tamil, Telugu, Bengali, and English
Real-time Processing: Quick responses for both voice and manual inputs

Technologies Used

Speech Processing: Wav2Vec2 for Speech-to-Text conversion
Machine Learning: Random Forest model trained on historical dengue data
Text-to-Speech: Google TTS for natural voice responses
Web Framework: Flask for backend API and web server
UI Framework: Gradio for interactive machine learning interface
Data Visualization: Interactive risk visualization

Installation & Setup

Clone this repository:
bashCopygit clone https://github.com/Pranay-Shaurya/AI_Healthcare_Project
cd dengue-ai-assistant

Install dependencies:
bashCopypip install -r requirements.txt

Run the application:
bashCopypython app.py

Access the web interface:

https://ai-healthcare-project.vercel.app

Flask interface: http://localhost:5000
Gradio interface: http://localhost:7860



Using the Voice Assistant

Click the microphone button in the web interface
Speak your weather parameters clearly:
Copy"Temperature is 32 degrees, humidity is 85 percent, rainfall is 120 mm, and month is 6"

The system will process your speech, extract parameters, and respond with a risk assessment
Choose your preferred response language from the dropdown menu

Using the Manual Interface

Enter the weather parameters in the form:

Temperature (°C)
Humidity (%)
Rainfall (mm)
Month (1-12)


Click "Predict" to get your risk assessment

🔍 How It Works

Voice Processing Pipeline:

Speech capture using browser's microphone API
Speech-to-Text conversion using Wav2Vec2
Parameter extraction using natural language processing
Risk prediction using the trained model
Text-to-Speech conversion for response


Prediction Model:

Random Forest classifier trained on historical dengue data
Features: temperature, humidity, rainfall, and month
Output: "High Risk" or "Low Risk" classification



📊 Dataset
The model was trained using historical dengue outbreak data from India spanning 1991-2022, combined with corresponding weather parameters. The dataset shows clear correlations between specific weather conditions and dengue outbreaks.
🔮 Future Enhancements

Geolocation Integration: Automatically fetch local weather data
Mobile App: Standalone application for Android and iOS
Offline Support: Function without internet connection
Expanded Language Support: Additional regional languages
Prediction Visualization: Graphical representation of risk factors

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
📧 Contact
For questions or feedback, please open an issue or contact your- pranayshaurya.pro@gmail.com .

Disclaimer: This tool provides risk assessment based on machine learning predictions and should not replace professional medical advice or public health initiatives. Always consult health authorities during dengue season.RetryClaude does not have the ability to run the code it generates yet. Claude does not have internet access. Links provided may not be accurate or up to date.Claude can make mistakes. Please double-check responses. 3.7 Sonnet
