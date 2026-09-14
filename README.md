# 11-python-Project-Build-the-Notes-API
A simple FastAPI Notes API built with Python and Pydantic to create, read, update, and delete study notes using CRUD operations.
# FastAPI Notes API

A beginner-friendly **Notes API** built with **FastAPI** and **Pydantic**. This project demonstrates how to create a simple REST API for managing personal study notes using CRUD operations.

## 📌 Project Overview

The Notes API allows users to manage study notes through four main operations:

* **GET** – View all saved notes
* **POST** – Add a new note
* **PUT** – Update an existing note
* **DELETE** – Delete a note

For this beginner project, an in-memory Python list is used to simulate database storage.

## 🛠️ Technologies Used

* Python
* FastAPI
* Pydantic
* Uvicorn
* REST API
* Swagger UI

## 📂 Project Structure

```text
Week11_Notes_API/
│
└── notes_api.py
```

## 🚀 Installation

Install the required packages:

```bash
pip install fastapi uvicorn
```

## ▶️ Run the Project

Run the API using:

```bash
uvicorn notes_api:app --reload
```

The API will start on the local server.

## 📖 API Documentation

FastAPI provides interactive Swagger documentation.

Open:

```text
http://127.0.0.1:8000/docs
```

From the Swagger UI, you can test all four API endpoints.

## 🔗 API Endpoints

| Method | Endpoint      | Purpose        |
| ------ | ------------- | -------------- |
| GET    | `/notes`      | Get all notes  |
| POST   | `/notes`      | Add a new note |
| PUT    | `/notes/{id}` | Update a note  |
| DELETE | `/notes/{id}` | Delete a note  |

## 📝 Note Model

Each note contains three fields:

```text
id       → Integer
title    → String
content  → String
```

Pydantic is used to validate the incoming data.

## 🎯 Learning Objectives

This project helps beginners understand:

* FastAPI application initialization
* Pydantic models
* Data validation
* API routes and endpoints
* HTTP methods
* CRUD operations
* Path parameters
* Interactive API testing with Swagger UI
* Basic API development with Python

## 👩‍💻 Author

**Asma Kanwal**
