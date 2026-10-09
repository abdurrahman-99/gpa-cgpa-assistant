# GPA/CGPA Assistant

A conversational agent that helps a PUCIT BS(CS) student with GPA and CGPA questions.
All calculations are done through tools; the agent never computes anything itself.

## Setup

1. Create a virtual environment and activate it:

python -m venv venv
venv\Scripts\activate

2. Install dependencies:

pip install langchain langchain-groq python-dotenv

3. Copy .env.example to .env and add your Groq API key:

GROQ_API_KEY=your_key_here

4. Run the agent:

python agent.py

5. Type your questions at the You: prompt. Type quit to exit.