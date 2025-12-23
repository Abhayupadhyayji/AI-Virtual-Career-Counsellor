# AI-Virtual-Career-Counsellor
This project is an AI-powered NLP chatbot that recommends suitable career paths based on user interests using Rasa, NLTK, and Streamlit.
AI-Virtual-Career-Counsellor/
│
├── rasa_bot/
│   ├── data/
│   │   ├── nlu.yml
│   │   ├── stories.yml
│   │   └── rules.yml
│   │
│   ├── domain.yml
│   ├── config.yml
│   ├── actions.py
│   └── endpoints.yml
│
├── streamlit_app/
│   └── app.py
│
├── nlp_utils/
│   └── text_preprocessing.py
│
├── requirements.txt
├── README.md
└── report/
    └── AI_Virtual_Career_Counsellor_Report.docx
# AI Virtual Career Counsellor

This project is an AI-powered NLP chatbot that recommends suitable career paths
based on user interests using Rasa, NLTK, and Streamlit.

## Features
- Career recommendation for Tech, Arts, and Commerce
- NLP-based intent detection
- Interactive chatbot interface
- Streamlit frontend

## Technologies Used
- Python
- Rasa
- NLTK
- Streamlit

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Train Rasa model:
   rasa train
3. Run chatbot:
   rasa shell
4. Run Streamlit app:
   streamlit run streamlit_app/app.py

