# Team of AI Agents

Welcome to the **Team of AI Agents** repository! This project focuses on building and orchestrating multi-agent systems using the [crewAI](https://www.crewai.com/) framework. Our agents collaborate to achieve specific goals, leveraging various tools and tasks.

## Repository Structure

- `src/instagram/tools/search.py`: This Python script contains tools for searching the internet and Instagram. 
- `src/instagram/crew.py`: The heart of our system! This file defines different AI agents, such as market researchers, content strategists, visual creators, and copywriters. Each agent has specific roles and tools.
- `src/instagram/main.py`: The entry point for running our multi-agent system. It initializes the agents, assigns tasks, and orchestrates their collaboration.
- `config/agents.yaml`: Configuration file defining agent properties (e.g., roles, tools, verbosity).
- `config/tasks.yaml`: Configuration file specifying task details (e.g., output files, associated agents).

## Getting Started

1. Clone this repository.
2. Customize the agents and tasks in `agents.yaml` and `tasks.yaml`.
3. Run `main.py` to see your AI agents in action!

Feel free to explore and enhance this repository based on your specific use case. Happy coding! 🚀🤖
