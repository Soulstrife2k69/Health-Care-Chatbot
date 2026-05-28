<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d7377,50:14a085,100:0d7377&height=200&section=header&text=🏥+MedBot&fontSize=65&fontColor=ffffff&fontAlignY=50&desc=AI+Powered+Health+Care+Chatbot&descSize=24&descAlignY=75&descColor=d0f5e8&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=14A085&center=true&vCenter=true&width=750&height=45&lines=Symptom+Detection+powered+by+NLP;Medicine+suggestions+for+common+illnesses;100%25+Offline+%7C+No+API+required;Built+with+Python+%7C+TensorFlow+%7C+Keras;Desktop+GUI+via+Tkinter" alt="Typing Animation"/>

<br/><br/>

<a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/NLTK-NLP-14a085?style=for-the-badge"/></a>
<a href="#"><img src="https://img.shields.io/badge/Tkinter-GUI-0078D4?style=for-the-badge"/></a>
<a href="#"><img src="https://img.shields.io/badge/Offline-100%25-00b894?style=for-the-badge"/></a>

</div>

---

## 🏥 About The Project

<img align="right" src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="240"/>

**MedBot** is an AI-powered healthcare chatbot built using **Python**, **NLP**, and **TensorFlow**. It detects symptoms, provides basic healthcare guidance, and suggests common medicines — all from a clean desktop GUI, completely offline.

> 🚫 No internet required.  
> 🚫 No API keys needed.  
> ✅ Type your symptoms. Get guidance instantly.

<br clear="right"/>

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🔍 | **Symptom Detection** | Identifies symptoms and maps them to health conditions |
| 💊 | **Medicine Suggestions** | Recommends common medicines for general illnesses |
| 🧠 | **AI Intent Recognition** | NLP + neural network based intent classification |
| 🖥️ | **Tkinter GUI** | Clean, interactive desktop interface |
| 📴 | **Fully Offline** | Zero API or internet dependency |
| ⚡ | **Fast Responses** | Trained `.h5` model for instant predictions |
| 🩺 | **Multi-condition Support** | Fever, Cold, Cough, Headache, Acidity, Diabetes & more |

---

## 🏗️ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,tensorflow,vscode,github&theme=dark" />
</div>

<br/>

```
Health-Care-Chatbot/
│
├── 🧩  intents.json        → Chat intents, patterns & responses
├── 🏋️  training_py.py      → Model training script
├── 💬  chatbot_py.py       → Terminal-based chatbot
├── 🖥️  gui.py              → Tkinter GUI chatbot
├── 🤖  chatbotmodel.h5     → Trained neural network model
├── 📦  words.pkl           → Saved vocabulary
├── 📦  classes.pkl         → Saved intent classes
├── 📊  Data_Analysis.ipynb → Data analysis notebook
└── 💾  heart-disease.csv   → Dataset
```

---

## 🧠 How It Works

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=1800&pause=600&color=14A085&center=true&vCenter=true&width=600&lines=Step+1%3A+User+types+symptom...;Step+2%3A+NLTK+tokenizes+%26+lemmatizes+input...;Step+3%3A+Bag+of+Words+vectorization...;Step+4%3A+Neural+network+predicts+intent...;Step+5%3A+Response+selected+%26+displayed." alt="Pipeline"/>

</div>

<br/>

```
User Input  ──▶  Tokenize & Lemmatize  ──▶  Bag of Words
                                                  │
                                                  ▼
          Response Display  ◀──  Intent Match  ◀──  Neural Network (.h5)
```

### Concepts Used

- **NLP** — Tokenization and lemmatization via NLTK
- **Bag of Words** — Converts raw text into numeric feature vectors
- **Intent Classification** — Multi-class softmax neural network
- **Keras Sequential Model** — Dense layers trained on `intents.json`
- **Text Preprocessing** — Noise removal, stemming, vectorizing

---

## 🚀 Getting Started

### Prerequisites

- ✅ Python 3.8+
- ✅ pip
- ✅ Windows / Linux / macOS

### Setup

```bash
# 1️⃣ Clone the repo
git clone https://github.com/Soulstrife2k69/Health-Care-Chatbot.git
cd Health-Care-Chatbot

# 2️⃣ Install dependencies
pip install tensorflow nltk numpy pandas

# 3️⃣ Train the model
python training_py.py

# 4️⃣ Launch the GUI
python gui.py
```

---

## 💬 Example Queries

<div align="center">

```
 "I have fever"              →  Suggests fever medication & rest
 "My throat hurts"           →  Cold/infection guidance
 "I have a headache"         →  Headache remedies
 "High blood pressure"       →  BP management tips
 "I am having acidity"       →  Acidity relief suggestions
 "Dry cough and cold"        →  Cough + cold treatment
```

</div>

---

## 🔮 Future Improvements

- [ ] 🎙️ Voice assistant integration
- [ ] 📅 Doctor appointment recommendation
- [ ] 🌐 Real-time medical API integration
- [ ] 📱 Web and mobile deployment
- [ ] 🗃️ Expanded medical dataset
- [ ] 🌙 Dark / Light theme toggle

---

## ⚠️ Disclaimer

> MedBot is for **educational and informational purposes only**.  
> It is **not a substitute** for professional medical advice, diagnosis, or treatment.  
> Always consult a qualified healthcare professional for medical concerns.

---

## 📊 Project Stats

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/Soulstrife2k69/Health-Care-Chatbot?style=for-the-badge&color=14a085)
![GitHub last commit](https://img.shields.io/github/last-commit/Soulstrife2k69/Health-Care-Chatbot?style=for-the-badge&color=0d7377)
![GitHub stars](https://img.shields.io/github/stars/Soulstrife2k69/Health-Care-Chatbot?style=for-the-badge&color=00b894)

</div>

---

## 👨‍💻 Developer

<div align="center">

<img src="https://github.com/Soulstrife2k69.png" width="100" style="border-radius:50%;"/>

### Soulstrife2k69
**Computer Science Engineering — AI & ML**

<a href="https://github.com/Soulstrife2k69">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Soulstrife2k69&label=Profile+Views&color=14a085&style=for-the-badge"/>

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d7377,50:14a085,100:0d7377&height=120&section=footer&animation=twinkling" width="100%"/>
</div>
