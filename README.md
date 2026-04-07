🚍 BusBuddy – Smart Bus Assistant Chatbot

📖 Overview
BusBuddy is an NLP-powered smart bus assistant chatbot designed to help users with fare prediction, route discovery, and transit-related queries. It integrates machine learning models with a Flask-based web application to deliver accurate, real-time, and user-friendly responses.

🚀 Key Highlights
Built an end-to-end ML-powered chatbot system
Integrated intent classification + fare prediction models
Implemented fuzzy matching to handle real-world input errors
Designed a Flask-based web interface for seamless interaction
Handles multiple query types: fare, routes, and transfer suggestions

✨ Features
🤖 Interactive NLP Chat Interface for natural language queries
💰 Bus Fare Prediction (Adult & Child fares)
🚌 Route Availability & Direct Bus Detection
🔁 Transfer Route Suggestions
🔍 Robust Fuzzy Matching for incorrect stop names
🌐 Web-based UI using Flask

🛠️ Tech Stack
Backend: Python, Flask
Machine Learning: TensorFlow (Keras), Scikit-learn
NLP: NLTK
Data Handling: Pandas, NumPy
Matching: FuzzyWuzzy
Frontend: HTML, CSS, JavaScript

🧠 How It Works
User enters a query through the web interface
Text is preprocessed using tokenization and lemmatization
Converted into features (bag-of-words representation)
ML model predicts user intent
Fare/route logic is applied based on query type
Response is generated and displayed in real-time

📊 Dataset & Models
Bus route dataset for route and stop mapping
Fare dataset for price prediction
Trained NLP model for intent classification
Separate ML model for fare prediction

📂 Project Structure
bus-buddy-main/
│
├── chatbot.py                  # Main Flask application
├── train_chatbot.py           # Chatbot training script
├── intents.json               # Intents & responses
├── chatbot_model.keras        # Trained NLP model
├── fare_prediction_model.pkl  # Fare prediction model
├── words.pkl                  # Vocabulary
├── classes.pkl                # Intent classes
├── surat_bus.csv              # Route dataset
├── SURAT5.csv                 # Fare dataset
│
├── templates/
│   └── index.html             # Chat UI
│
├── requirements.txt
└── README.md

📊 Use Cases
Smart public transport assistance
Fare estimation systems
Route planning tools
Base for conversational AI applications

🎓 Academic Relevance
NLP-based chatbot development
ML model integration in real-world applications
Backend + frontend system design using Flask
Handling real-world noisy input data

🔮 Future Enhancements
Real-time bus tracking integration
Database connectivity for dynamic updates
Voice-based interaction
Mobile application version
Multi-city transport support

👤 Author
Vishishta Shenoy

📜 License
This project is for educational purposes only.
