
# 🔍 Scam Message Investigator

# Demo link : https://gbm5vavcvcgn8rhmsbnpvg.streamlit.app/

An AI-powered application that investigates suspicious messages and helps users identify potential scams, phishing attempts, fraudulent offers, and misleading communications.

Built using **Python, Streamlit, Ollama, and Gemma 3 (1B)**, this application analyzes message content and generates an investigation report with risk indicators and safety recommendations.

## 🚀 Project Overview

With the increasing number of online scams through SMS, WhatsApp, emails, and social media, identifying fraudulent messages has become important.

Scam Message Investigator uses a locally running Large Language Model (LLM) to examine suspicious messages, identify warning signs, and provide recommendations to help users stay safe online.

## ✨ Features

- 🔎 **Message Investigation:** Analyze suspicious text messages.
- 🤖 **AI-Powered Analysis:** Uses Gemma 3 (1B) through Ollama.
- ⚠️ **Risk Assessment:** Identifies potential scam risks.
- 📋 **Warning Signs:** Highlights suspicious words, links, and requests.
- 🛡️ **Safety Recommendations:** Provides suggestions to avoid potential scams.
- 📊 **Investigation Report:** Generates an easy-to-understand analysis.
- 🔐 **Local AI Processing:** Runs the language model locally through Ollama.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Programming |
| Streamlit | Web Application Interface |
| Ollama | Local LLM Execution |
| Gemma 3 (1B) | AI-Powered Message Analysis |
| Requests | API Communication |

## 📁 Project Structure

```text
Scam-Message-Investigator/
│
├── app.py
├── requirements.txt
├── README.md
└── Scam_Message_Investigator_Project_Documentation.docx
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/suba-shini7/Scam-Message-Investigator.git
```

### 2. Navigate to the Project Folder

```bash
cd Scam-Message-Investigator
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Install Ollama

Download Ollama from:

https://ollama.com/download

Install Ollama on your system.

### 7. Download the Gemma 3 Model

```bash
ollama pull gemma3:1b
```

### 8. Run the Application

```bash
streamlit run app.py
```

### 9. Access the Application

Open your browser and visit:

http://localhost:8501

## 🧪 Example Input

```text
Congratulations! You have won a ₹50,000 lottery prize.
Pay ₹500 processing fees immediately.
Click this link to claim your prize.
```

The application analyzes the message and generates an investigation report containing potential warning signs, risk assessment, and recommended safety actions.

## 🔄 How It Works

1. The user enters a suspicious message into the Streamlit interface.
2. The application receives the message.
3. The message is sent to the locally running Ollama service.
4. Gemma 3 (1B) analyzes the message content.
5. The AI generates an investigation report.
6. The application displays the analysis and safety recommendations.

## 🔐 Privacy and Security

- Uses a locally running AI model.
- Does not require a paid LLM API key.
- Message analysis is performed through the local Ollama service.
- Users should avoid clicking suspicious links or sharing sensitive personal information.

## ⚠️ Limitations

- AI-generated results may not always be accurate.
- Some genuine messages may be flagged as suspicious.
- Sophisticated scams may not always be detected.
- The application provides guidance and should not replace independent verification.

## 🔮 Future Enhancements

- SMS and email integration.
- URL and website reputation checking.
- Multilingual scam message detection.
- Machine learning-based scam classification.
- Scam pattern detection and reporting.
- Message history and investigation analytics.

## 👩‍💻 Project Information

- **Project Name:** Scam Message Investigator
- **Category:** Artificial Intelligence / Cybersecurity
- **Domain:** Generative AI and Natural Language Processing
- **Interface:** Streamlit
- **Programming Language:** Python
- **AI Model:** Gemma 3 (1B)
- **LLM Runtime:** Ollama

## 👩‍💻 Author

**Afreen Nisha M**

B.Sc Computer Science with Artificial Intelligence

Interested in Artificial Intelligence, Python Development, and Cybersecurity.

---

⭐ Developed with passion by **Afreen Nisha M**.
