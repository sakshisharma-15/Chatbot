AI Chatbot – Gemini Powered Assistant

## About the Project

This project is an AI-powered chatbot developed using Python, Streamlit, and Google Gemini API. It provides an interactive platform where users can ask questions, have conversations, and get AI-generated responses.

The chatbot can also recognize specific commands and perform simple tasks, such as opening websites like YouTube, Google, and Spotify.

 ## Features

AI-Powered Conversations: Generates intelligent responses using Google Gemini.

Interactive Chat Interface: User-friendly interface developed with Streamlit.

Greeting Responses: Responds to greetings such as Hello, Hi, and Good Morning.

Website Navigation: Opens YouTube, Google, and Spotify through specific commands.

Developer Information: Answers questions about who developed the chatbot.

Chat History: Maintains conversation messages during the active Streamlit session.

Error Handling: Displays an error message if the Gemini API connection fails.

## Technologies Used

Python – Core programming language.

Streamlit – For creating the interactive web interface.

Google Gemini API – For generating AI-based responses.

Google GenAI SDK – For connecting the application with Gemini.

OS Module – For accessing environment variables.

Webbrowser Module – For opening websites through commands.

 ## Project Structure

AI-assistant/
│
├── Chatbot/
│   └── chatbot.AI.py
│
└── README.md


## Installation and Setup

cd AI-assistant
pip install streamlit google-genai
$env:GEMINI_API_KEY="YOUR_API_KEY"
streamlit run Chatbot/chatbot.AI.py
