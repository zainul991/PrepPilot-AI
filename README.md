# PrepPilot AI

PrepPilot AI is a GenAI-powered interview preparation platform that helps candidates prepare for job interviews using resume and job-role information.

## Features

- Resume-based interview preparation
- Job description analysis
- AI-generated interview questions
- Technical and behavioral preparation
- Skill-gap analysis
- Personalized preparation roadmap

## Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- Generative AI / LLM API

## Project Structure

Frontend/
Backend/

## Setup

### Frontend

```bash
cd Frontend
npm install
npm run dev
```

### Backend

```bash
cd Backend
npm install
```

Create a `.env` file inside the `Backend` folder with the following variables:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key


Then start the server:

```bash
npm run dev
```

- Backend runs on `http://localhost:3000`
- Frontend runs on `http://localhost:5173`