# GovScheme AI
### AI-Powered Multilingual Government Scheme Eligibility Recommender

GovScheme AI is an AI-powered platform that helps citizens discover relevant government welfare schemes, understand eligibility criteria, and access application guidance through a multilingual interface.

## Overview

Many citizens, particularly in rural areas, face difficulties accessing government welfare schemes because of language barriers, complex eligibility requirements, and time-consuming documentation.

GovScheme AI simplifies this process through intelligent scheme recommendations, profile-based eligibility filtering, and AI-powered assistance.

## Key Features

- **Scheme Discovery:** Find relevant government welfare schemes based on user profiles.
- **Eligibility Matching:** Filter schemes using demographic and financial criteria.
- **AI Assistant:** Understand scheme benefits, eligibility requirements, and application procedures.
- **Multilingual Support:** Access guidance in supported Indian languages.
- **OCR Document Processing:** Extract information from documents to reduce manual data entry.
- **Application Tracking:** Monitor application progress where supported.
- **Admin Dashboard:** Manage scheme information and monitor platform activity.

## Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React, TypeScript, Vite |
| Styling | Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI Integration | Gemini API |
| Document Processing | Tesseract OCR |
| Internationalization | i18next |

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB, if required by your configuration
- API keys for configured external services

### Installation

Clone the repository:

```bash
git clone https://github.com/subukavya/horizon_govscheme_ai.git
cd horizon_govscheme_ai
```

Install dependencies in the frontend and backend directories according to their respective `package.json` files.

Configure the required environment variables using `.env.example`, if available. Start both services using the development scripts defined in your project.

## Security

- Store API keys and credentials in environment variables.
- Never commit `.env` files or real personal identity documents.
- Use synthetic documents for OCR testing.

## Project Links

- **Live Demo:** https://govhelp.vercel.app/
- **GitHub Repository:** https://github.com/subukavya/horizon_govscheme_ai

## Project Objective

To improve access to government welfare information by making scheme discovery, eligibility understanding, and application guidance simpler and more accessible.

---

*GovScheme AI — Simplifying access to government welfare schemes.*
