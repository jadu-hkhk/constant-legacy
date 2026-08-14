# Constant – Legacy

> The original implementation of Constant, built with the MERN stack. This project has been superseded by the current version of Constant.

Constant is a website uptime monitoring platform designed to track website availability and response times using a microservices architecture.

This repository contains the **original MERN implementation** of the project. The current version of Constant is being rebuilt with **Spring Boot and Java**, with a stronger focus on production-grade architecture, reliability, and engineering practices.

## Architecture

![Architecture Diagram](https://github.com/user-attachments/assets/bf7b1164-fb30-46d3-bac3-29e7840d5746)

### Services

* **API Service** – Handles user authentication and website management through RESTful APIs
* **Pusher Service** – Pushes website monitoring jobs into the queue every 3 minutes
* **Worker Service** – Performs health checks and updates the database with status and response times
* **Web Frontend** – Displays website status and response times in real time

## Tech Stack

* **Backend:** Node.js, Express.js, TypeScript
* **Frontend:** Next.js 15, React, Tailwind CSS
* **Database:** PostgreSQL with Prisma ORM
* **Message Queue:** Redis Streams
* **Authentication:** JWT with httpOnly cookies

## Features

* User authentication (signup/signin)
* Add websites for monitoring
* Automated health checks every 3 minutes
* Response time tracking
* Real-time monitoring dashboard
* Microservices-based architecture
* Asynchronous job processing using Redis Streams

## Project Status

This repository is **no longer actively developed** and is preserved as the original implementation of Constant.

The project has since been re-engineered from the ground up as a new version using **Java and Spring Boot**, incorporating lessons learned from this implementation and a stronger focus on production-grade engineering practices.

**Current version:** [`Constant`](https://github.com/jadu-hkhk/constant)
