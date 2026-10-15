# SQL Agent for Daily Task Management

## About the Project

This project is a simple AI-powered task management application that helps users manage their daily tasks using natural language. Instead of manually writing SQL queries, users can type what they want to do, and the application processes their requests to perform the required database operations.

I built this project using Python, Streamlit, SQLite, and Groq. The main idea was to explore how Generative AI can be connected to a database to make everyday tasks easier to manage.

## Features

- **Add Tasks:** Create new tasks for daily activities.
- **View Tasks:** Check existing tasks and their current status.
- **Update Tasks:** Change task details or mark tasks as completed.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Natural Language Input:** Give instructions in simple English instead of writing SQL queries manually.
- **Database Integration:** Store and manage task information using SQLite.
- **Interactive Interface:** Use the application through a Streamlit web interface.

## Technologies Used

- **Python** – Handles the application logic.
- **Streamlit** – Provides the user interface.
- **SQLite** – Stores task details in a database.
- **Groq API** – Connects the application to a large language model.
- **SQL** – Performs database operations.

## How It Works

1. The user enters a request through the Streamlit interface.
2. The Groq-powered model helps interpret what the user wants to do.
3. The application processes the request and determines the required database operation.
4. SQLite is used to add, retrieve, update, or delete task records.
5. The result is displayed to the user.

Example Usage

Here are a few examples of requests that can be handled by the application:

"Add a task to complete my Python assignment today."

"Show me all my pending tasks."

"Mark my project work as completed."

"Update the deadline of my assignment."

"Delete a task that I no longer need."
