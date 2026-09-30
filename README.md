# App Project

Full-stack application with a Python backend and a React frontend. Provides a modular foundation for building scalable web applications.

## Features

- Modular architecture with clearly separated frontend and backend
- RESTful API served by a Python backend
- Modern, responsive React user interface
- Tailwind CSS for rapid UI development
- Test infrastructure and reporting

## Tech Stack

| Layer     | Technology                          |
|-----------|-------------------------------------|
| Frontend  | JavaScript, React, Tailwind CSS     |
| Backend   | Python (Flask/FastAPI-style server) |
| Styling   | Tailwind CSS, PostCSS, CRACO        |

## Project Structure

```
.
├── backend/           # Python backend
│   ├── requirements.txt
│   └── server.py
├── frontend/          # React frontend
│   ├── public/
│   ├── src/
│   └── package.json
├── memory/            # Application state / data helpers
├── tests/             # Test suite
├── test_reports/      # Generated test reports
└── test_result.md
```

## Prerequisites

- Node.js and npm (or yarn)
- Python 3.x and pip

## Installation and Setup

### Backend

```bash
cd backend
pip install -r requirements.txt
python server.py
```

### Frontend

```bash
cd frontend
npm install
npm start
```

The frontend typically runs at `http://localhost:3000` and communicates with the backend API.

## Usage

Start both services, then open the frontend URL in a browser. The React application will interact with the Python API endpoints.

## License

This project is provided for development and experimentation.
