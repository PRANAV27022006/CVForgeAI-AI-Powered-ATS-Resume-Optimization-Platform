# CVForgeAI — AI-Powered ATS Resume Optimization Platform

CVForgeAI is an AI-powered resume analysis platform designed to help job seekers evaluate their resumes against job descriptions, identify skill gaps, and improve their applications with AI-driven insights.

🌐 **Live Demo:** https://cv-forge-ai-frontend.vercel.app/

💻 **Tech Stack:** React, Vite, Node.js, Express.js, MongoDB, JWT, Google OAuth, AI Services

---

## Features

- ATS resume scoring
- AI-powered resume insights
- Job description and skill matching
- Resume skill extraction
- Skill gap analysis
- User authentication
- Google OAuth integration
- Resume management

## Project Structure

```text
CVForgeAI/
├── 01-Frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── hooks/
│   └── package.json
│
├── 02-Backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── package.json
│
└── .gitignore
```

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB
- Required API credentials for AI and authentication services

### 1. Clone the Repository

```bash
git clone https://github.com/PRANAV27022006/CVForgeAI-AI-Powered-ATS-Resume-Optimization-Platform.git

cd CVForgeAI-AI-Powered-ATS-Resume-Optimization-Platform
```

### 2. Run the Backend

```bash
cd 02-Backend
npm install
```

Configure the required environment variables in a local `.env` file, using the variable names expected by the backend code.

Start the backend using the appropriate script defined in `02-Backend/package.json`.

### 3. Run the Frontend

Open a second terminal from the project root:

```bash
cd 01-Frontend
npm install
npm run dev
```

Open the local URL provided by Vite.

## Security

- Never commit API keys, passwords, or production secrets.
- Keep `.env` files private.
- Validate API inputs and uploaded files.
- Configure authentication and CORS appropriately.

## Future Improvements

- Resume version comparison
- Detailed ATS score explanations
- Downloadable analysis reports
- More AI-powered recommendations
- Automated testing and CI/CD

## Repository

GitHub: https://github.com/PRANAV27022006/CVForgeAI-AI-Powered-ATS-Resume-Optimization-Platform

---

*CVForgeAI — Smarter Resume Analysis for Better Job Applications.*
