# Smart Document Evaluator

A Next.js application that uses AI to compare, evaluate, and rank documents based on objective criteria.

## Features

- **Document Upload**: Support for multiple file formats (up to 5 documents)
- **Flexible Criteria**: Define evaluation criteria manually or upload via CSV
- **AI-Powered Analysis**: Integration with Oracle Generative AI for intelligent document evaluation
- **Real-time Feedback**: Visual indicators and progress tracking during evaluation
- **Modern UI**: Clean, responsive interface with Material UI components

## Tech Stack

- **Frontend**: Next.js 15, React 19, Material UI
- **Styling**: Emotion, Framer Motion for animations
- **Backend**: Oracle Generative AI APIs
- **Deployment**: Docker support included

## Quick Start

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your backend URL

# Start development server
npm run dev
```
