# Medical Research Assistant

A comprehensive medical research chatbot that helps users find publications, clinical trials, and research insights using natural language queries.

## Features

- 🩺 **Natural Language Queries**: Ask questions in plain English about medical conditions
- 📚 **Publication Search**: Find latest research papers from OpenAlex and PubMed
- 🧪 **Clinical Trials**: Discover relevant clinical trials and studies
- 🤖 **AI-Powered Analysis**: Get intelligent summaries and insights
- 💬 **Interactive Chat**: Conversational interface for follow-up questions
- 📱 **Responsive Design**: Works on desktop and mobile devices

## Demo Use Cases

- "Latest treatment for lung cancer"
- "Clinical trials for diabetes"
- "Top researchers in Alzheimer's disease"
- "Recent studies on heart disease"

## Tech Stack

### Frontend
- React 18 with Vite
- Modern CSS with responsive design
- Axios for API calls

### Backend
- Node.js with Express
- MongoDB for session storage
- Ollama with TinyLlama for AI analysis

### APIs
- OpenAlex for academic publications
- PubMed for medical research
- ClinicalTrials.gov for clinical trials

## Installation

### Prerequisites
- Node.js 18+
- MongoDB
- Ollama with TinyLlama model

### Backend Setup
```bash
cd backend
npm install
npm start
```

### Frontend Setup
```bash
cd medical
npm install
npm run dev
```

## Environment Variables

Create a `.env` file in the backend directory:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
LLM_MODEL=tinyllama
```

## Deployment

### Vercel (Frontend)
1. Connect your GitHub repository to Vercel
2. Set build command: `npm run build`
3. Set output directory: `dist`

### Backend Deployment
Deploy to services like Railway, Render, or Heroku with the following considerations:
- Ensure MongoDB is accessible
- Set up Ollama or use cloud LLM service
- Configure environment variables

## Usage

1. Start the backend server
2. Start the frontend development server
3. Open the application in your browser
4. Click the chat button and ask medical research questions

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT License - see LICENSE file for details