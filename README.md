# What beats Rock?

**Empowering the classic what-beats-rock game with Generative AI, build with FastAPI, Redis and Docker**

# Overview
"What-beats-rock" is an AI enhanced word game, where users attempt to beat rock in a conceptual or metaphorical sense. This is then evaluated by the genAI backend, providing AI-generated feedback, in a serious or cheery tone as chosen by user.

## Tech Stack
-**Frontend**: Streamlit
-**Backend**: FastAPI (Python)
-**LLM**: Gemini
-**Database**: Redis
-**Containerization**: Docker

## Project Structure
\\\
.
├── backend
│   ├── Dockerfile
│   ├── __pycache__
│   │   ├── main.cpython-310.pyc
│   │   ├── redis_client.cpython-310.pyc
│   │   └── test.cpython-310.pyc
│   ├── main.py
│   ├── redis_client.py
│   └── requirements.txt
├── docker-compose.yml
└── frontend
    ├── Dockerfile
    ├── frontend.py
    └── requirements.txt

## Set up Instructions
1. `git clone https://github.com/Eros483/arnab-mandal-wasserstoff-AiInternTask.git`
2. `cd arnab-mandal-wasserstoff-AiInternTask`
3. `docker-compose up --build`
