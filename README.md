# Medi-AI

## Purpose
Medi-AI is a comprehensive healthcare web application that provides AI-powered medical assistance, symptom checking, diagnosis support, and medicine information. The platform serves as a digital health companion offering 24/7 medical guidance and health management tools.

## Operational Flow
1. **User Access** - Users navigate through the responsive web interface
2. **Feature Selection** - Choose from AI Diagnosis, Symptom Checker, or Medicine Library
3. **Data Input** - Enter symptoms, medical history, or search queries
4. **AI Processing** - OpenAI GPT-3.5 processes medical queries via API
5. **Result Generation** - System provides diagnosis suggestions, symptom analysis, or medicine information
6. **User Interaction** - Interactive chat interface for follow-up questions
7. **Response Delivery** - Comprehensive medical insights and recommendations

## Project Structure
```
Medi-AI/
├── src/app/
│   ├── Home/                 # Landing page with chatbot
│   ├── ai-diagnosis/         # AI-powered diagnosis tool
│   ├── symptom-checker/      # Symptom analysis system
│   ├── medicine-library/     # Medicine database and search
│   ├── login/               # User authentication
│   ├── register/            # User registration
│   ├── components/          # Reusable UI components
│   ├── api/chatbot/         # OpenAI API integration
│   └── globals.css          # Global styling
├── public/                  # Static assets and images
├── package.json            # Dependencies and scripts
└── next.config.js          # Next.js configuration
```

## Language
**TypeScript** with **Next.js Framework**

## Tools & Technologies
- **Next.js 14** - React framework for web application
- **TypeScript** - Type-safe JavaScript development
- **Tailwind CSS** - Utility-first CSS framework
- **OpenAI API** - GPT-3.5 Turbo for medical AI responses
- **Lucide React** - Icon library for UI components
- **React Icons** - Additional icon components
- **Axios** - HTTP client for API requests
- **React Markdown** - Markdown rendering support
- **Poppins Font** - Google Fonts integration
