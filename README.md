# YouTube Download API

A production-oriented Python backend service built with Flask that enables downloading YouTube videos through REST APIs. The project focuses on backend engineering concepts such as request handling, API design, modular architecture, file processing, and scalable service development.

---

## Features

- Download YouTube videos using a URL
- Retrieve available video formats and resolutions
- Download audio-only or video files
- RESTful API architecture
- Modular service-based backend structure
- Input validation and structured error handling
- Download history support (planned)
- Background processing support (planned)

---

## Tech Stack

### Backend

- Python
- Flask
- yt-dlp
- REST APIs

### Future Enhancements

- FastAPI Migration
- PostgreSQL
- JWT Authentication
- Redis
- Celery
- Docker
- WebSocket Progress Updates

---

## Project Structure

```
youtube-download-api/

├── app.py
├── requirements.txt
├── README.md
├── routes/
├── services/
├── utils/
├── downloads/
└── static/
```

---

## API Workflow

```
Client
   │
   ▼
Submit YouTube URL
   │
   ▼
Validate URL
   │
   ▼
Fetch Metadata
   │
   ▼
Select Format
   │
   ▼
Download Media
   │
   ▼
Return Download Response
```

---

## Planned API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/v1/analyze` | Retrieve video metadata |
| POST | `/api/v1/download` | Download selected media |
| GET | `/api/v1/formats` | List available formats |
| GET | `/api/v1/history` | View download history |
| GET | `/api/v1/health` | API health check |

---

## Goals

This project was built to strengthen backend engineering skills by exploring:

- REST API Design
- Python Service Architecture
- Request Handling
- File Processing Pipelines
- Modular Code Organization
- Backend Scalability

---

## Status

🚧 Currently being rebuilt with an improved architecture and additional backend features.
