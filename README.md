# Project Chatbot

## Overview
The **Project Chatbot** is a Streamlit-based conversational application that leverages Google’s Gemini API to generate AI responses in real time. This chatbot allows users to interact with a generative language model, receiving context-aware responses based on their input. Built with Streamlit, the application is user-friendly, web-based, and maintains chat history within the session.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Features
- Real-time conversation with Google’s Gemini language model.
- User-friendly interface with chat history display.
- Streamlined API management via `dotenv` for secure API handling.
- Error handling for API connection and message retrieval.

## Getting Started
To get a local copy up and running, follow these steps:

### Prerequisites
- **Python 3.7 or higher**
- Google’s Gemini API key

### Installation
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/username/project-chatbot.git
    cd project-chatbot
    ```

2. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Environment Variables**:
    - Rename `.env.example` to `.env` and replace the placeholder with your Google Gemini API key:
    ```plaintext
    GOOGLE_API_KEY=your_actual_google_api_key_here
    ```

## Usage
1. **Run the Application**:
    ```bash
    streamlit run app.py
    ```

2. **Interacting with the Chatbot**:
    - Enter your prompt in the input field and press "Enter the prompt."
    - The chatbot’s responses and chat history are displayed in real-time.

## Project Structure
- **app.py** - Main application file to run the chatbot.
- **requirements.txt** - List of dependencies.
- **.env** - File for environment variables, storing your API key securely.

## Troubleshooting
- **API Key Error**: Ensure your Google API key is set in `.env` file.
- **Connection Issues**: Check your internet connection or verify if the API key has access permissions.
- **Environment Configuration Error**: Ensure the `dotenv` package is correctly installed and `.env` file is configured.

## License
This project is licensed under the MIT License.
