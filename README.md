# Practice API

A small REST API built with FastAPI.

## Features

- Simple REST endpoints
- Health check endpoint
- Dependency management with virtual environment
- Version controlled with Git

## Tech Stack

- Python 3.11
- FastAPI
- Uvicorn

## Project Structure

practice_api/
│
├── app/
│ ├── init.py
│ └── main.py
│
├── requirements.txt
├── .gitignore
└── README.md


## Run Locally

### 1. Create virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```


### 3. Run server
```bash
uvicorn app.main:app --reload
```

Open:

http://127.0.0.1:8000

Swagger docs:

http://127.0.0.1:8000/docs