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
what-beats-rock/
├── backend/
│   ├── main.py              # FastAPI powered app
│   ├── requirements.txt     # backend dependencies
│   ├── Dockerfile           # Dockerfile for backend service
│   └── __pycache__/         
├── frontend/
│   ├── requirements.txt     # dependencies for frontend
│   ├── frontend.py          # streamlit UI to play the game
│   ├── Dockerfile           # Dockerfile for frontend services
├── docker-compose.yml       
├── .gitignore               
├── .env                     #Stores gemini API key
└── README.md                #Documentation

## Set up Instructions
1. `git clone https://github.com/Eros483/arnab-mandal-wasserstoff-AiInternTask.git`
2. `cd arnab-mandal-wasserstoff-AiInternTask`
3. `docker-compose up --build`
