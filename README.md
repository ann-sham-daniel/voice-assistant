# AI Voice Assistant using ElevenLabs Conversational AI

A real-time voice-interactive assistant built with the ElevenLabs Conversational AI API.  
This assistant listens to the user, understands context, and responds with natural AI-generated speech.



## Features

- Real-time Speech-to-Text
- High-quality Text-to-Speech responses
- Customizable prompts and personality
- Dynamic context awareness (user name, schedule, etc.)
- Live conversation loop using streaming audio
- Callback functions for user transcripts and agent responses
- Secure API key handling using '.env'
-  Interrupt handling** — assistant stops speaking when the user talks



## Technologies Used

- Python 3.10+
- ElevenLabs Conversational AI API
- python-dotenv
- WebSockets
- Real-time audio streaming
- Git & GitHub for version control



## Project Structure


voice-assistant/
│── voice_assistant.py       # Main program file
│── .gitignore               # Hides .env and cache files
│── requirements.txt         # Python dependencies
│── README.md                # Project documentation
└── .env                     # API key and agent ID (not uploaded)

