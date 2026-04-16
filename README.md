# FastAPI Blog Project

This repository contains my implementation of a FastAPI-based blog application, built by following Corey M. Schafer’s FastAPI tutorial series. The project demonstrates how to build a full-featured, production-ready web application using FastAPI and modern backend development practices.

## Overview

The goal of this project is to progressively develop a blog platform while learning key backend concepts such as API design, database integration, authentication, deployment, and scalability. Each stage of the project corresponds to a topic covered in the tutorial series.

## Features

- RESTful API built with FastAPI  
- Template rendering for dynamic pages  
- Full CRUD functionality  
- Database integration  
- User authentication and authorization  
- File uploads and image handling  
- Pagination support  
- Background tasks (e.g., password reset)  
- Cloud storage integration (AWS S3)  
- PostgreSQL database support  
- Automated testing with Pytest  
- Deployment to VPS and Google Cloud Run  
- Rate limiting and CORS configuration  
- Frontend interaction via forms and React  

## Tutorial Breakdown

The project follows the structure of the FastAPI series:

1. Getting Started  
2. Templates  
3. API Setup and Path Parameters  
4. Pydantic Schemas  
5. Adding a Database  
6. Completing CRUD (PUT, PATCH, DELETE)  
7. Async/Await vs Synchronous  
8. APIRouters  
9. Frontend Forms to Interact with the API  
10. Authentication  
11. Authorization  
12. File Uploads and Images  
13. Pagination from the API  
14. Password Reset and Background Tasks  
15. Switching to PostgreSQL  
16. Using AWS S3 for Image Storage  
17. Testing with Pytest  
18. Deployment #1 (Manual Deployment to VPS)  
19. Deployment #2 (Containerized Deployment to Google Cloud Run)  
20. Rate Limiting  
21. CORS and React Frontend  

## Tech Stack

- FastAPI  
- Python  
- SQLAlchemy  
- PostgreSQL  
- Jinja2 Templates  
- AWS S3  
- Pytest  
- Docker  
- Google Cloud Run  

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fastapi-blog.git
   cd fastapi-blog

2. Create and activate virtual environment:
   python -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows

3. Install Dependencies:
   pip install -r requirements.txt

4. Run the Application:
   uv run fastapi dev main.py

5. Open your browser and navigate to:
   http://127.0.0.1:8000
