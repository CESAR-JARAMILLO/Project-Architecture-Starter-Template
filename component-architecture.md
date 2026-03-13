# Component Architecture

## Overview

This document describes how UI components are structured and interact.

---

## Design Principles

- Components should have a single responsibility.
- Components should be reusable.
- Business logic should be separated from UI.

---

## Example Structure

DashboardPage
 ├ WorkoutList
 │   ├ WorkoutCard
 │   └ WorkoutFilters
 └ AddWorkoutModal

---

## Component Categories

Page Components
Top-level route components.

Feature Components
Components tied to a feature.

Shared Components
Reusable UI components such as buttons and cards.
