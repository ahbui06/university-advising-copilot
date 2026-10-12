# University Advising & Degree Audit Copilot

An AI-powered full-stack application that will help university students understand degree progress, evaluate prerequisites, upload transcripts, and receive personalized semester recommendations.

Degree requirements, prerequisites, and graduation eligibility will be evaluated with deterministic C# logic. AI will support transcript extraction, retrieval of university policies through RAG, conversational explanations, and semester-plan suggestions.

## Planned technology stack

- **Frontend:** Angular and TypeScript
- **Backend:** ASP.NET Core Web API and C#
- **Database:** MongoDB, with potential future support for Azure Cosmos DB
- **AI service:** Python, FastAPI, LangChain, LangGraph, and OpenAI
- **Document processing:** PyMuPDF and Pydantic
- **RAG:** Vector search for university academic policies
- **Version control:** Git and GitHub

## Planned features

- Track degree progress and graduation eligibility
- Evaluate course prerequisites and requirements
- Upload and extract information from transcripts
- Retrieve relevant university academic policies
- Explain degree-audit results conversationally
- Recommend personalized semester plans

## Directory structure

- `frontend/` — Future Angular application.
- `backend/` — Future ASP.NET Core Web API.
- `ai-service/` — Future Python AI and RAG service.
- `data/` — Development data, sample documents, and future data resources.
- `docs/` — Project documentation, architecture notes, and planning materials.

Each directory currently contains a `.gitkeep` file so the initial structure is tracked by Git.

## Current status

Initial repository structure is in place. Applications, database configuration, dependencies, and integrations have not yet been initialized so the project can be implemented step by step.
