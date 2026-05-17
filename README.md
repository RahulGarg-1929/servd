# Servd

A full-stack web application built as a learning project by following a YouTube tutorial and implementing the project end-to-end with a separate frontend and backend architecture.

## Overview

Servd is a full-stack project with:

- **Frontend** in modern JavaScript (Next.js-style structure)
- **Backend** API server with configuration, database, and typed modules
- Environment-based configuration for local development

This project helped me practice full-stack development concepts including API integration, project structuring, state handling, and backend setup.

---

## Tech Stack

### Frontend
- JavaScript
- Next.js (App Router structure)
- CSS

### Backend
- Node.js
- JavaScript
- Config + Database + Typed module structure

---

## Project Structure

```bash
servd/
├── frontend/        # UI application
│   ├── app/
│   ├── components/
│   ├── actions/
│   ├── hooks/
│   └── lib/
├── backend/         # API / server
│   ├── src/
│   ├── config/
│   ├── database/
│   └── types/
└── README.md
```

---

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/RahulGarg-1929/servd.git
cd servd
```

### 2) Setup Backend

```bash
cd backend
npm install
```

Create environment file:

```bash
cp .env.example .env
```

Update `.env` with your local values.

Run backend:

```bash
npm run dev
```

### 3) Setup Frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

---

## Learning Goals

This project was built to learn and practice:

- Full-stack folder architecture
- Building reusable frontend components
- Connecting frontend to backend APIs
- Managing environment variables
- Organizing backend code with config/database/types modules

---

## Current Status

- [x] Frontend and backend setup
- [x] End-to-end local development structure
- [ ] Add deployment links
- [ ] Add screenshots
- [ ] Add tests

---

## Future Improvements

- Add authentication/authorization improvements
- Improve UI/UX and responsiveness
- Add error handling and loading states everywhere
- Add unit/integration tests
- Deploy frontend and backend

---

##  Acknowledgement

This project was inspired by a YouTube tutorial and recreated as a personal learning exercise.

---

## Contact

**Rahul Garg**  
GitHub: [RahulGarg-1929](https://github.com/RahulGarg-1929)
