# HireMATE AI

HireMATE AI is an AI-powered resume analysis and job-matching
assistant built with Python and Streamlit.

## Features

- Upload PDF and TXT resumes
- Extract text from resumes
- Compare resumes with job descriptions
- Generate an estimated job-match score
- Identify matched and missing or unclear skills
- Recommend resume improvements
- Generate a personalized learning roadmap
- Prepare job-specific interview questions
- Download the analysis report

## Technology Stack

- Python
- Streamlit
- Groq API
- OpenAI-compatible chat completions through Groq
- pypdf
- python-dotenv

## Installation

1. Install Python 3.11 or another version compatible with
   the selected package versions.

2. Clone this repository and enter the project directory.

3. Create a virtual environment:

   python3 -m venv .venv

4. Activate it on macOS:

   source .venv/bin/activate

5. Install dependencies:

   python -m pip install -r requirements.txt

6. Create a .env file containing:

   GROQ_API_KEY=your_actual_groq_api_key

7. Start the application:

   python -m streamlit run app.py

## Security

Never commit your real API key, personal resumes, or other
sensitive information to GitHub.

## Disclaimer

The match score is an estimate of alignment with a job
description, not a prediction of hiring success.
# HireMate-AI
