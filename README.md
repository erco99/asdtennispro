# A.S.D. Tennis Pro

A.S.D. Tennis Pro is an academic project developed for the **Applications and Web Services**  ùcourse of the 
**Master’s Degree in Computer Science and Engineering** at the **University of Bologna**.

This project was developed to improve the web-based system used by **Forum Tennis Forlì**, addressing
real user needs while keeping the interface simple and familiar, especially for less tech-savvy users.

## Architecture

The application is built using the **MEVN stack**:

- **MongoDB** – NoSQL database
- **Express.js** – Backend REST API
- **Vue.js (Vue 3)** – Frontend
- **Node.js** – JavaScript runtime

The system is divided into:
- **Frontend**: Vue components, Vuetify UI, Vuex, Vue Router
- **Backend**: REST APIs, WebSocket communication, authentication and data persistence
- **Database**: MongoDB with Mongoose
- **Docker**: database containerization

Frontend and backend communicate via REST APIs and WebSockets for real-time updates.

## Technologies

### General
- Node.js
- MongoDB
- Docker
- WebSocket
- HTML, CSS, JavaScript, TypeScript

### Frontend
- Vue 3
- Vite
- Vuetify
- Vuex
- Vue Router
- Axios
- ECharts
- js-cookie
- Mitt
- Vee-Validate

### Backend
- Express.js
- Mongoose
- bcrypt
- JSON Web Token (jose)
- Nodemailer + Mailgen
- otp-generator
- dotenv
- cors

## Run the application
Make sure the following tools are installed on your system:

- **Node.js** (v16 or later recommended)
- **npm**
- **Docker** (Docker Desktop on Windows/macOS)

Clone the repository

```bash
git clone <repository-url>
cd <repository-folder>
```

Install `run-script-os`:
```bash
npm install run-script-os
```

Now start the application:

```bash
npm run start
```

## Disclaimer
This README has been derived from the original project report, which provides a detailed analysis of requirements, 
design decisions, architecture, and implementation details.

The complete project report is available in the report/ directory of this repository.

The application has never been deployed online, nor has it ever had any real-world or commercial application. 
After the completion and submission of the project, no further development, maintenance, or updates have been carried out, and none are planned.

The codebase is preserved in its original state as a reference for educational and documentation purposes only.
