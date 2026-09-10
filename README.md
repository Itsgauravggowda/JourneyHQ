# 🌍 JourneyHQ

> **The collaborative workspace for planning unforgettable journeys.**

JourneyHQ is a full-stack, real-time travel planning and presentation platform designed to bring every aspect of trip planning into a single collaborative workspace. Instead of juggling WhatsApp chats, shared notes, spreadsheets, and maps, JourneyHQ enables travellers, planners, and agencies to brainstorm destinations, vote on ideas, manage budgets, generate optimized routes, visualise journeys, and collaborate live—all from one application.

---

## ✨ Vision

Planning a trip with friends is often chaotic.

Discussions happen in chat applications, destinations are saved in notes, expenses are tracked in spreadsheets, routes are created separately in mapping applications, and final trip plans are often presented using static documents or presentations.

JourneyHQ solves this by becoming the **central headquarters for every journey**, while also providing an interactive way to demonstrate and experience the planned trip.

---

## 🚀 Core Features

### 🗺️ Collaborative Planning Board

* Create shared trips
* Invite collaborators
* Suggest destinations
* Contextual discussions for every suggestion
* Polls and voting
* Host approval workflow

### 👥 Role-Based Collaboration

* **HOST** – Full administrative control
* **COHOST** – Assists with trip management
* **MEMBER** – Suggests, comments, and votes
* **PLANNER** – Creates and manages trips for customers

### 💰 Budget Planner

* Estimated trip budget
* Cost per person calculation
* Expense tracking
* Remaining budget calculation
* Shared financial planning

### 📍 Interactive Maps

* OpenStreetMap integration
* Automatic destination pin generation
* Driving route generation
* Distance and travel time estimation
* Route visualization
* Interactive trip route exploration

### ⚡ Real-Time Collaboration

* Live destination updates
* Instant comments
* Real-time voting
* Live budget synchronization
* Socket.IO powered collaboration

### 🎬 Animated Trip Preview

* Smooth route fly-through
* Animated map transitions
* Progressive route highlighting
* Destination-by-destination journey visualization
* Interactive trip preview experience
* Trip presentation for customers, friends, or other travellers

### 🤖 AI Travel Assistant

* AI-generated trip summaries
* Day-by-day itinerary narration
* Budget insights
* Travel suggestions
* Planning assistance

---

# 🏗️ System Architecture

```text
                   JourneyHQ

                        │
                        ▼

                   Next.js App
          (Next.js + React + JavaScript)

                        │
                 API + JWT

                        ▼

              Next.js Server / API

                        │

        ┌───────────────┼───────────────┐
        │               │               │
        ▼               ▼               ▼

     MongoDB        Socket.IO      OpenRouteService
    (Mongoose)    Real-Time Sync      Routing API

                        │
                        ▼

                  OpenAI API
```

---

# 🛠️ Tech Stack

## Frontend

* Next.js
* React
* JavaScript
* Tailwind CSS
* Axios
* React Leaflet

## Backend

* Next.js
* Node.js

## Database

* MongoDB
* Mongoose

## Authentication

* JWT
* bcrypt

## Real-Time

* Socket.IO

## Maps

* OpenStreetMap
* React Leaflet
* OpenRouteService (or OSRM)

## AI

* OpenAI API

## Development

* Git
* GitHub
* ESLint
* Prettier
* Postman / Bruno

## Deployment

* Vercel
* MongoDB Atlas

---

# 📂 Project Structure

```text
JourneyHQ/

├── app/
│
├── components/
│
├── controllers/
│
├── db/
│
├── middleware/
│
├── models/
│
├── utils/
│
├── validators/
│
├── public/
│
├── .env.local
├── .gitignore
├── next.config.js
├── package.json
└── README.md
```

---

# 📋 Development Roadmap

* ⬜ Product Design & Planning
* ⬜ Project Foundation
* ⬜ Authentication
* ⬜ Frontend Foundation
* ⬜ Trip Workspace
* ⬜ Planning Board
* ⬜ Budget Planning
* ⬜ Interactive Maps
* ⬜ Real-Time Collaboration
* ⬜ Animated Trip Preview
* ⬜ AI Assistant
* ⬜ Testing & Optimisation
* ⬜ Deployment & Showcase

---

# 🧩 Core Modules

## Authentication

Secure user registration and login using JWT authentication and bcrypt password hashing.

## Trip Workspace

Create trips, invite members, and manage collaborative travel planning.

## Planning Board

Suggest destinations, discuss ideas, create polls, and approve locations for the final itinerary.

## Budget Planner

Estimate expenses, divide costs, and track actual spending.

## Maps

Generate interactive routes and visualise approved destinations on an interactive map.

## Live Collaboration

Real-time synchronization of trip updates using Socket.IO.

## Animated Trip Preview

Create an animated visual representation of the planned journey, including routes, destinations, and travel progression.

## AI Assistant

Generate itinerary summaries, travel insights, and intelligent planning suggestions.

---

# 🔒 Security

* Password hashing with bcrypt
* JWT authentication
* Protected API routes
* Role-based authorization
* Input validation
* Secure environment variables
* CORS protection
* Centralised error handling

---

# 🎯 Goals

JourneyHQ aims to:

* Simplify collaborative travel planning.
* Replace scattered planning tools with a unified workspace.
* Provide interactive maps and animated trip presentations.
* Allow travel planners and agencies to demonstrate trip plans to customers.
* Deliver a modern, scalable full-stack application.
* Demonstrate production-level software engineering practices.

---

# 🚧 Future Enhancements

* Offline trip support
* Push notifications
* Shared photo albums
* Calendar integration
* AI route optimisation
* Weather forecasts
* Expense settlement
* Mobile application
* Public trip templates
* Multi-language support

---

# 🤝 Contributing

Contributions, suggestions, and feedback are always welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed as a full-stack software engineering project demonstrating modern web development, scalable architecture, real-time collaboration, mapping technologies, interactive trip visualisation, and AI integration.

---

## ⭐ If you like this project

Give the repository a **Star ⭐** and follow the development journey of **JourneyHQ**.
