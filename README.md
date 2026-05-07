## Vehicle Rental System Organization

## Overview

This organization is dedicated to the development of a Vehicle Rental Service Platform as part of the WD 1.2 group project. The system enables customers to rent vehicles, manage bookings, and provide feedback, while administrators oversee operations.

---

## Team Structure

The project is developed by a team of six members, each responsible for a specific module:

* Customer Management
* Vehicle Fleet Management
* Rental Booking & Returns
* Admin & Driver Management
* Feedback & Review Management
* System Integration and Coordination

---

## System Components

### 1. Customer Management

Handles registration, login, profile updates, and account deletion.

### 2. Vehicle Fleet Management

Manages vehicle listings, updates, availability, and removal.

### 3. Rental Booking & Returns

Processes bookings, tracks rental periods, and manages returns.

### 4. Admin & Driver Management

Manages staff accounts, roles, and permissions.

### 5. Feedback & Review Management

Allows users to submit, edit, and view reviews.

### 6. Billing & Receipt Management

Generates receipts, calculates rental costs, and manages billing records.

---

## Architecture

The system follows a layered architecture consisting of:

* Controller Layer (REST APIs)
* Service Layer (Business Logic)
* Repository Layer (Database Access)
* MySQL Database

---

## Technologies Used

### Backend

* Java
* Spring Boot
* Spring Data JPA
* MySQL

### Frontend

* HTML
* CSS (Bootstrap)
* JavaScript

### Tools

* Git and GitHub
* Postman
* Draw.io or StarUML

---

## Git Workflow

A feature-branch workflow is used:

* main branch for stable code
* feature branches for module development

Example branches:

* feature/user-module
* feature/vehicle-module
* feature/rental-module
* feature/staff-module
* feature/feedback-module
* feature/integration

All changes are merged through pull requests after review.

---

## Project Management

* GitHub Projects (Kanban board)
* Issue-based task tracking
* Module-based responsibility assignment

---

## Objectives

* Implement CRUD operations for all modules
* Apply object-oriented programming principles
* Build a modular and scalable system
* Maintain collaboration using version control

---

## Documentation

The project includes:

* UML diagrams
* ER diagrams
* System architecture documentation
* Final report

---

## Status

Currently under development.

---

## Contribution Guidelines

* Create a separate branch for each feature
* Commit changes with meaningful messages
* Submit pull requests for merging
* Avoid direct commits to the main branch

---

## Note

# Vehicle Rental Management System

## UML Diagram

![UML Diagram](images/Vehicle-Rental-UML.png)

## ER Diagram

![ER Diagram](images/Vehicle-Rental-System-ER.png)

This project is developed for academic purposes as part of the WD 1.2 module.
