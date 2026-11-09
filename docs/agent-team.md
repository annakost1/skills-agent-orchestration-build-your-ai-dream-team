# Project Pulse Agent Team

## Agent Team Overview

### 1. Orchestrator
- **File**: `.github/agents/orchestrator.agent.md`
- **Model**: Opus 5.5
- **Responsibility**: Coordinates requests, routes tasks, and oversees the overall Project Pulse dashboard workflow.

### 2. Planner
- **File**: `.github/agents/planner.agent.md`
- **Model**: GPT-5.5
- **Responsibility**: Breaks down high-level requirements into implementation phases and defines file ownership.

### 3. Designer
- **File**: `.github/agents/designer.agent.md`
- **Model**: Gemini 3.7 Flash
- **Responsibility**: Guides the dashboard UI/UX experience and ensures consistent styling and layout.

### 4. Coder
- **File**: `.github/agents/coder.agent.md`
- **Model**: GPT-5.5
- **Responsibility**: Implements the static application files, code structure, and functional components.

## How the Team Works Together
The Orchestrator receives the initial goal, passes requirements to the Planner to establish structure, consults the Designer for layout guidance, and delegates implementation tasks to the Coder to complete the Project Pulse dashboard.