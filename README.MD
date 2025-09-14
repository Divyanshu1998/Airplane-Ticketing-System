# Airplane Ticketing System

> A project to book and manage flight tickets — web-based application (Front-end + Back-end)  

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Running the Project](#running-the-project)  
- [Project Structure](#project-structure)  

---

## Features

- Search for flights by source, destination, date  
- View available flights and fares  
- Book tickets (passenger details + payment)  
- Manage bookings (view / cancel etc.)  
- User authentication (login / signup)  
- Admin dashboard for managing flights (add/update/remove)  

---

## Tech Stack

| Component        | Technology / Language        |
|------------------|-------------------------------|
| Frontend         | HTML, CSS |
| Backend          | Java (Spring / Spring Boot) |
| Database         | MySQL        |              

---

## Getting Started

### Prerequisites

- Java 8  
- A relational database like MySQL / PostgreSQL installed and running  
- (Optional) IDE / Text Editor of choice  
- SpringBoot 2.2

### Running the project


mvn spring-boot:run

## Project Structure

Airplane-Ticketing-System/      ← main application code
├──  src/                    ← source files
├──  public/ / static/       ← frontend static assets
├──  resources/ etc.         ← config, views, etc.
├── README.md                ← this file
└── .gitignore
