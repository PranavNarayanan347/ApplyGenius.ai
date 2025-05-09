# ApplyGenius.ai
"AI-powered job application tracker with resume/cover letter generator and job recommendations"
# ApplyGenius.ai 💼🚀

ApplyGenius.ai is a full-stack, AI-powered job application platform that streamlines and personalizes the application process. It enables users to automatically rewrite their resumes and generate tailored cover letters based on job listings — while tracking application statuses, notes, and job recommendations in one place.

## 🔑 Key Features

- ✨ **AI Resume Rewriter**: Enhances user resumes using keywords extracted from job descriptions, improving ATS compatibility.
- 📝 **AI Cover Letter Generator**: Auto-generates professional, tailored cover letters aligned with the job listing.
- 📊 **Job Tracker**: Lets users track application progress, add notes, and auto-fill job details from pasted job links.
- 🔍 **Job Recommender**: Suggests personalized roles based on previously applied jobs using clustering and vectorization logic.

## ⚙️ Tech Stack

- **Frontend**: HTML, CSS (styled with light-orange/white theme)
- **Backend**: Python (Flask)
- **AI Integration**: OpenAI GPT (via API)
- **Web Scraping**: BeautifulSoup
- **Job Data**: JSearch API (for job recommendations)
- **Data Storage**: JSON-based state management (for simplicity in MVP)

## 🧠 Motivation

Built to solve a common pain point: job seekers spending countless hours tailoring documents for each role. ApplyGenius.ai automates the process while preserving professional standards — saving time and increasing match quality.

## 🚀 How to Run Locally

> **Note:** Requires Python 3.8+ and an OpenAI API key stored in a `.env` file.

1. Clone this repo:
   ```bash
   git clone https://github.com/pranavnarayanan347/ApplyGenius.ai.git
   cd ApplyGenius.ai
   python -m venv venv
   pip install -r requirements.txt
   OPENAI_API_KEY=your_openai_key_here
   flask run
