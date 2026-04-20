# Medical API System 🏥

A professional FastAPI-based system for managing patient health records and predicting medical emergencies in real-time.

## Features ✨

- **Patient Management**: Complete CRUD operations for patient profiles.
- **Emergency Prediction**: Real-time analysis of vital signs (Heart Rate, BP, Oxygen, Temp).
- **Vitals History**: Trace historical health data for any patient.
- **Interactive Documentation**: Built-in Swagger UI and ReDoc.
- **Persistence**: SQLite database with SQLAlchemy ORM.

## Getting Started 🚀

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Seed the Database
Initialize the database with sample data:
```bash
python seed.py
```

### 3. Run the API
Start the development server:
```bash
uvicorn backend.main:app --reload
```

## API Documentation 📖

Once the server is running, you can access the interactive documentation at:
- **Swagger UI**: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
- **ReDoc**: [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

## Tech Stack 🛠️

- **Framework**: FastAPI
- **Database**: SQLite
- **ORM**: SQLAlchemy
- **Validation**: Pydantic
- **Server**: Uvicorn
