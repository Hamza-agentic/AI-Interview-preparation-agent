# AI-Interview-preparation-agent
This project is an AI-powered interview preparation system built around a multi-agent workflow. It combines local LLM inference, live web research, and specialized AI agents to create personalized interview preparation.

## Key Features
1- Interactive Mock Interviews — Simulates multi-turn technical and behavioral interviews dynamically.

2- Domain-Specific Question Generation — Generates targeted questions covering:
 - Python programming
 - Machine learning fundamentals
 - Data structures
 - Algorithms
   
3- Technical and behavioral interview topics

4- Automated Response Evaluation — Evaluates candidate responses for:
  - Technical accuracy
  - Clarity
  - Completeness

### Areas for improvement

  - Personalized 7-Day Preparation Plan — Produces a structured preparation schedule based on the target role and research findings.

  - Structured Jupyter Environment — Implements the agents and workflow in .ipynb notebooks for easy experimentation, prototyping, and educational demonstrations.

## Technologies Used
- CrewAI
- Ollama + Llama 3
- SerperDevTool
- Jupyter Notebook

## How to Run
1. Install dependencies
2. Configure API key
3. Run the notebook

## Workflow
User / Target Role
       ↓
       
Interview Research Analyst
       ↓
       
Research & Interview Insights
       ↓
       
Interview Preparation Coach
       ↓
       
7-Day Preparation Plan

