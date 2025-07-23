# Smart Visual Learning Portal

A comprehensive visual learning platform with AI-powered features for education.

## Features

- Image captioning and analysis
- Video processing and transcription
- Text summarization using LSTM and T5 models
- Smart tutoring with AI assistance
- YouTube video processing
- Multi-language support

## Setup

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables in a `.env` file:
   - GEMINI_API_KEY
   - OPENAI_API_KEY
   - APP_PASSWORD
   - SENDER_MAIL_ID
4. Run the application: `streamlit run app.py`

## Technologies Used

- Streamlit for the web interface
- OpenAI and Google Gemini for AI capabilities
- TensorFlow and Keras for machine learning models
- Transformers for NLP tasks
- Various Python libraries for multimedia processing