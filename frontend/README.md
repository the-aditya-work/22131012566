# URL Shortener - Frontend

## Project Overview

This is a React-based frontend URL Shortener app. It allows users to shorten URLs with optional custom shortcodes and validity periods. It also provides click analytics.

## Folder Structure

- /logging-middleware — Contains custom LoggerContext used across the app.
- /frontend — React frontend application

## Features

- Shorten up to 5 URLs at once
- Optional custom shortcode and validity (default 30 min)
- Tracks clicks, location, timestamp, and source
- Responsive design (mobile + desktop)

## Tech Stack

- React (JavaScript)
- Material UI (MUI)
- Custom Logging Middleware (no console.log used)

## How to Run

```bash
cd frontend
npm install
npm start
