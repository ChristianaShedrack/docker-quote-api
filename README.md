# Docker Quote API 🐳
A simple quote generator app built with **Flask** and **Docker**.

## Features
- Get all quotes (`/quotes`)
- Get a random quote (`/quote`)
- Add a new quote (`POST /quotes`)
- Simple frontend at `/` to display random quotes

## Run with Docker
```bash
docker build -t quote-api .
docker run -d -p 5000:5000 --name quote-api quote-api
