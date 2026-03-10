# Polling Application

A full-stack polling application where users can create polls and vote on different options.
The system dynamically updates vote counts and retrieves polls through REST APIs.

## Tech Stack

**Backend**

* Java
* Spring Boot
* Spring Data JPA
* REST APIs

**Frontend**

* Angular
* TypeScript
* Bootstrap

**Database**

* JPA / Hibernate (with relational database)

---

## Features

* Create polls with multiple options
* View all available polls
* Vote on poll options
* Dynamic vote count updates
* RESTful backend APIs integrated with Angular frontend

---

## Project Structure

```
polling-app
│
├── backend
│   └── Spring Boot Application
│       ├── controller
│       ├── service
│       ├── repository
│       └── model
│
├── frontend
│   └── Angular Application
│       ├── components
│       ├── services
│       └── models
│
└── README.md
```

---

## API Endpoints

| Method | Endpoint          | Description           |
| ------ | ----------------- | --------------------- |
| POST   | `/api/polls`      | Create a new poll     |
| GET    | `/api/polls`      | Get all polls         |
| GET    | `/api/polls/{id}` | Get poll by ID        |
| POST   | `/api/polls/vote` | Vote on a poll option |

---

## Author

**Samriddh Das**
