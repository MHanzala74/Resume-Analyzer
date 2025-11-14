## Smart ATS Resume Analyzer
A Streamlit-based application that helps job seekers optimize their resumes for Applicant Tracking Systems (ATS). The tool analyzes resume-job description compatibility and provides actionable insights.

### Features
ATS Compatibility Score: Percentage match between resume and job description

Missing Keywords: Identifies critical keywords absent from your resume

Personalized Suggestions: Detailed improvement recommendations

PDF Support: Direct upload and text extraction from PDF resumes

Quick Start
Install Dependencies

bash
pip install streamlit streamlit-extras python-dotenv PyPDF2 google-generativeai
Set Up API Key

Get a Google Gemini API key

Create .env file:

text
GOOGLE_API_KEY=your_api_key_here
Run Application

bash
streamlit run app.py
Usage
Paste the job description in the text area

Upload your resume (PDF format)

Click "Analyze Resume" to get:

Match percentage score

Missing keywords list

Detailed improvement suggestions

Supported Fields
Software Engineering

Data Science

Data Analysis

Big Data Engineering

Technical roles

File Structure
text
smart-ats/
├── app.py              # Main Streamlit application
├── helper.py           # Core functionality utilities
├── .env               # Environment variables
└── README.md          # Documentation
Optimize your resume and increase your chances of getting noticed by ATS systems!
