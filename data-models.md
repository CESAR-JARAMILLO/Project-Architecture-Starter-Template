# Data Models

## Overview

This document defines the core entities stored in the system.

---

## User

id
email
createdAt

---

## Workout

id
userId
date
notes

---

## Exercise

id
name
muscleGroup

---

## WorkoutSession

id
workoutId
exerciseId
sets
reps
weight
