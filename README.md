🏥 MedBot - Health Care Chatbot



<img src="https://www.scnsoft.com/blog-pictures/healthcare/how-chatbots-and-ai-are-changing-the-healthcare-industry_1.png">
MedBot is an AI-powered health care chatbot built using Python, NLTK, and TensorFlow. It can identify symptoms, suggest common medicines, and provide general health advice — available 24/7 with a simple GUI interface.

🖥️ Features

Symptom detection and health advice
Medicine suggestions for common illnesses
Clean Tkinter GUI with multiple color themes
Fully offline — no API or internet required
Supports: Fever, Cold, Cough, Headache, Diabetes, BP, Acidity, and more


📁 Project Structure
Health-Care-Chatbot/
│
├── intents.json          # Chat intents, patterns and responses
├── training_py.py        # Model training script
├── chatbot_py.py         # Terminal chatbot
├── gui.py                # GUI chatbot (Tkinter)
├── chatbotmodel.h5       # Trained neural network model
├── words.pkl             # Saved vocabulary
├── classes.pkl           # Saved intent classes
├── Data_Analysis.ipynb   # Jupyter notebook for data analysis
├── heart-disease.csv     # Dataset
└── README.md

⚙️ Requirements

Python 3.8
TensorFlow 2.13
NLTK
NumPy
Pandas
Tkinter (usually pre-installed)


🚀 Installation & Setup
1. Clone the repository
bashgit clone https://github.com/Soulstrife2k69/Health-Care-Chatbot.git
cd Health-Care-Chatbot
2. Install dependencies
bashpip install tensorflow nltk numpy pandas
3. Train the model
bashpython training_py.py
4. Run the chatbot
bashpython gui.py

💬 Sample Questions to Ask
SymptomExample QueryFever"I have fever", "my body is hot"Cough"I have cough", "dry cough"Cold"runny nose", "blocked nose"Headache"I have headache", "migraine"Stomach"stomach pain", "acidity", "loose motions"Diabetes"I have diabetes", "high blood sugar"Blood Pressure"BP is high", "hypertension"Skin"skin rash", "itching", "skin allergy"

⚠️ Disclaimer
MedBot is for informational purposes only. It is not a substitute for professional medical advice. Always consult a qualified doctor for serious health issues.

👨‍💻 Developer
Shubhojit Nandy

⭐ If you found this helpful, please drop a star!
