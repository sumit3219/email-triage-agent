# Email Triage Agent using Generative AI

## 📌 Project Overview
This project implements a **Student-Level Email Triage Agent** using Generative AI.
The system automatically classifies incoming emails, assigns priority, retrieves relevant information, and generates appropriate responses.

## 🎯 Objectives
- Classify email intent (Support, Complaint, Sales, Feedback, Spam)
- Assign priority (High / Medium / Low)
- Generate professional email replies
- Decide whether to auto-reply or escalate

## 🧠 Workflow
1. Email input is provided
2. Intent is classified using an LLM (Groq)
3. Priority is assigned using rule-based logic
4. Relevant information is retrieved using keyword matching
5. A response is generated
6. Action is decided (Auto-reply / Escalate)

## 🛠️ Technologies Used
- Python
- LangChain
- Groq LLM (Llama 3.1)
- Prompt Engineering

## 🚀 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/sumit3219/email-triage-agent.git
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook
   ```
   email_triage_agent.ipynb
   ```
4. Set your Groq API key
   ```python
   os.environ["GROQ_API_KEY"] = "YOUR_API_KEY"
   ```

## 📊 Sample Results
- High priority emails → Escalated to human support
- Low priority emails → Auto-reply generated

## 🎓 Academic Use
This project is intended for **educational purposes** and demonstrates the application of Generative AI in automation.

## 👤 Author
- Sumit Mishra 
- B.Tech CSE (Student)

## 📄 License
Educational use only.
