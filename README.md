# 📄 ATS Resume Expert — AI Resume Analyzer

An AI-powered Streamlit application that evaluates resumes against job descriptions using **Google Gemini AI**.  
It helps candidates understand how well their resume matches a job and how to improve it.

---

##  Features

###  1. Resume vs Job Description Analysis
- Compares your resume with a given job description  
- Provides **strengths and weaknesses**  
- Gives professional HR-style feedback  

---

###  2. ATS Match Percentage
- Calculates how well your resume matches the job  
- Outputs:
  -  Match Percentage  
  -  Missing Keywords  
  -  Final Suggestions  

---

###  3. PDF Resume Processing
- Upload resume in PDF format  
- Converts PDF → Image → AI-readable format  

---

###  4. Fast AI Responses
- Uses **Google Gemini (gemini-1.5-flash)**  
- Quick and efficient analysis  

---

##  Tech Stack

| Layer       | Technology     |
|-------------|----------------|
| Frontend    | Streamlit      |
| Backend     | Python         |
| AI Model    | Google Gemini  |
| PDF Handling| pdf2image, PIL |
| Env Config  | python-dotenv  |

---

##  Project Structure
ats-resume-expert/
│── app.py
│── .env
│── requirements.txt
│── README.md


---

##  Installation & Setup

### 1️.  Clone Repository

```bash
git clone https://github.com/Kashish708/ATS
cd ats-resume-expert
```

### 2.  Install Dependencies
pip install -r requirements.txt

### 3.  Setup Environment Variables
GOOGLE_API_KEY=your_api_key_here

### 3.  Run the App
streamlit run app.py


