# API Design

## Overview

Defines the API endpoints and how the frontend communicates with the backend.

---

## Authentication

POST /api/auth/login
POST /api/auth/register

---

## Workouts

GET /api/workouts
Returns all workouts for the user.

POST /api/workouts
Creates a workout.

DELETE /api/workouts/:id
Deletes a workout.

---

## Exercises

GET /api/exercises
Returns available exercises.
