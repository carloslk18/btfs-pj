# Better Than F# Sympla

**Better Than Sympla** is an experimental platform focused on **event discovery**.

The goal of this project is to build a modern ecosystem where users can easily **discover, follow and engage with events and communities** in one place.

Today, most platforms focus mainly on **ticket sales**, while event discovery happens across multiple places like LinkedIn, Instagram, WhatsApp groups, and newsletters.

BTFS aims to change that by becoming a **central hub for discovering events**.

---asdasdasdasahj

## Project Vision

Create a platform where users can:

* Discover events that match their interests
* Follow organizers and communities
* Explore events happening in their city
* Save and track upcoming events
* Receive smart event recommendations

Instead of focusing only on **buying tickets**, the platform focuses on **discovering events**.

---njjnjhvbaskkhgyhjj

## Tech Stack

| Layer           | Technology            |
| --------------- | --------------------- |
| Frontend        | Blazor + JavaScript   |
| Backend         | ASP.NET Core          |
| ORM             | EF Core + Dapper      |
| Database        | MySQL                 |
| Version Control | Git + GitHub          |

Future improvements may include:

* Event recommendation system
* Search optimization
* Caching layer
* Community features

---

## Project Structure

```bash
better-than-sympla
│
├─ backend
│   ├─ Btfs.Api
│   ├─ Btfs.Application
│   ├─ Btfs.Domain
│   └─ Btfs.Infrastructure
│
├─ frontend
│   └─ Btfs.Web
│
├─ database
│   ├─ Scripts
│   ├─ Seeds
│   └─ Diagrams
│
├─ infra
│   ├─ Docker
│
├─ docs
│   ├─ Architecture
│   ├─ Decisions
│   └─ Product
│
├─ scripts
│
├─ Btfs.sln
├─ README.md
└─ .gitignore
```

## Backend Layers

**Domain**
Contains the core business entities and rules.

**Application**
Contains application services and use cases.

**Infrastructure**
Handles external dependencies like database access.

**API**
Exposes HTTP endpoints used by the frontend.

---

## MVP Goals

The first version of the platform will include:

* Event listing
* Event search
* Event detail pages
* Event categories
* Save / favorite events

Future versions may include:

* Personalized event recommendations
* Community features
* Organizer dashboards
* Smart event feeds

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/carloslk18/better-than-sympla.git
```

Navigate to the project:

```bash
cd better-than-sympla
```

Restore dependencies:

```bash
dotnet restore
```

Run the API:

```bash
dotnet run --project backend/Btfs.Api
```

---

## Database Migrations

Create a new migration:

```bash
dotnet ef migrations add MigrationName
```

Apply migrations:

```bash
dotnet ef database update
```
---

## Project Philosophy

This project started from a simple idea:

> Discovering events should be as easy as discovering music or movies.
