# rasa-customer-FAQ
## Overview
The Rasa Tech Company FAQ Chatbot is designed to provide users with information and assistance related to tech company. This chatbot can answer frequently asked questions (FAQs) about the company, its services, contact details, working hours, history, and more. It aims to enhance user engagement and provide quick and helpful responses to common inquiries.

## Features
- FAQ Interaction: Users can ask questions about the tech company and receive informative responses.
- Company Insights: Get insights into the company's mission, vision, and values.
- Contact Information: Provide contact details, including email and phone number.
- Company History: Share the company's history and milestones.
- Business Hours: Inform users about the company's operating hours.

## Prerequisites
Before running the chatbot, ensure you have following prerequisites: 

- [Rasa](https://rasa.com/docs/rasa/installation)
- [Python](https://www.python.org/downloads/)

## Project Structure

- `data/`: Contains training data for the Rasa chatbot.
- `actions/`: Contains custom actions and logic for handling user data.
- `config.yml`: Configuration file for database and other settings.
- `domain.yml`: Defines the chatbot's domain, including intents, entities, and responses.
- `rules.yml`: Defines conversation rules for handling user interactions.
- `nlu.yml`: Contains NLU training data for intent recognition.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Set up the Rasa environment and install the necessary dependencies.
4. Configure PostgreSQL database connection in the `actions.py` file.
5. Train the chatbot with the provided training data using the 'rasa train' command in the command prompt. 
6. Once the model is trained, start the rasa run actions server using the 'rasa run actions' command.
7. To interact with the bot, use the 'rasa shell' command.
8. The bot can be interacted with on Postman using 'http://localhost:5005/webhooks/rest/webhook'.
9. The bot stores user information in PostgreSQL (the command can be found on the `actions/` file). 

## Usage
The "Rasa-Tech-Company-FAQ" chatbot can answer questions related to your tech company's:

- Insights and services.
- User feedback and support.
- Contact information.
- Business hours.
- Company history and milestones.

Users can interact with the bot by asking questions, and it will provide relevant answers based on the trained data. The bot can be customized based on the specific requirements and data for training.
