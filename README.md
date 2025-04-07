# Rasa & Python Chatbot

Developed by Matteo De Moor

---

## Project Description

This project is a chatbot built using Rasa and Python. It leverages machine learning to provide a contextual AI assistant capable of understanding and responding to user inputs.

## Tools & Technologies

- **Python**: Programming language used for the chatbot development.
- **Rasa**: Open-source machine learning framework for building contextual AI assistants and chatbots.

## Getting Started

Follow these steps to set up the project on your local machine.

### 1. Create a Virtual Environment

```bash
py -3.9 -m venv ./venv
```

### 2. Activate the Virtual Environment

```bash
.\venv\Scripts\activate
```

### 3. Initialize the Rasa Project
  
```bash
rasa init
```

### 4. Training the Models

```bash
rasa train
rasa train nlu
```

### 5. Running the Chatbot

```bash
rasa shell
```