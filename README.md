# ChatBot

This repository contains a simple chatbot application built using Flask, Transformers, and Torch.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)

## Project Overview

This project is a web-based chatbot interface that allows users to interact with a chatbot using a sleek and modern design. The chatbot is built with Flask as the backend framework and uses pre-trained transformer models to handle natural language processing tasks.

## Features

- Responsive and user-friendly chat interface
- Real-time message exchange
- Integration with a powerful NLP model for generating responses
- Easy to set up and deploy

## Installation

### Prerequisites

- Python 3.x
- Flask
- Transformers
- Torch

### Steps

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/chatbot-project.git
    cd chatbot-project
    ```

2. Create and activate a virtual environment:

    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask app:

    ```sh
    python app.py
    ```

2. Open your browser and go to `http://127.0.0.1:5000` to start interacting with the chatbot.

## File Structure

```
chatbot-project/
│
├── app.py                  # Main Flask application file
├── templates/
│   └── chat.html           # HTML file for the chat interface
├── static/
│   ├── style.css           # CSS file for styling the chat interface
├── requirements.txt        # List of dependencies
└── README.md               # Project README file
```

## Technologies Used

- **Backend**: Flask
- **Frontend**: HTML, CSS (Bootstrap), JavaScript (jQuery)
- **NLP**: Transformers, Torch

---
