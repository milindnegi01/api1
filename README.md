# Meal API

A FastAPI-based service that combines meal data from TheMealDB API and a custom Supabase database.

## Features

- Search meals from multiple sources
- Add custom meals to the database
- Balanced results from both sources
- RESTful API endpoints

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables in `.env`:
   ```
   SUPABASE_DB_URL=your_database_url
   PORT=8000 (optional)
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## API Endpoints

- GET `/meals/{meal_name}`: Search for meals
- POST `/add_meal/`: Add a new meal to the database

## Deployment

This application is configured for deployment on Render. 