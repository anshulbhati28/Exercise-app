# Exercise-Easy

## Table of Contents
- [Introduction]
- [Features]
- [Tech Stack]
- [Installation]
- [Usage]
- [API Endpoints]

## Introduction
This is a Workout Tracker application that allows users to keep track of their workouts. Users can log their workout details, including title, load, and reps. The app provides features to view, add, update, and delete workouts.

## Features
- User authentication (signup, login)
- Logging workouts (title, load, reps)
- Viewing all workouts
- Viewing a single workout
- Updating a workout
- Deleting a workout

## Tech Stack
- MongoDB: Database to store workout data
- Express.js: Backend framework for handling API requests
- React: Frontend library for building the user interface
- Node.js: Runtime environment for server-side logic

## Installation
1. Clone the repository: `git clone https://github.com/your-username/workout-tracker-app.git`
2. Navigate to the project directory: `cd workout-tracker-app`
3. Install dependencies: `npm install`

## Usage
1. Start the server: `npm start`
2. Access the application at: `http://localhost:3000`

## API Endpoints
- `GET /api/workouts`: Get all workouts
- `GET /api/workouts/:id`: Get a single workout
- `POST /api/workouts`: Create a new workout
- `DELETE /api/workouts/:id`: Delete a workout
- `PATCH /api/workouts/:id`: Update a workout
