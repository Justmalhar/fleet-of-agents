# Fleet of Agents

This repository focuses on building 365 micro AI assistants over 365 days. Each assistant is a specialized component capable of handling a narrow set of tasks. The long-term goal is to develop a fully modular system that can be easily extended or updated.

## Project Status

- Day 1: Repo initialized, basic README created
- Day 2: Roadmap planning (categories, structure, daily tasks)
- Day 3: Project setup (directories, environment, initial code)
- Day 4–365: Building and refining the agents

## Directory & Module Structure

The structure below is a work in progress. As we proceed, it will evolve to include additional utilities, test suites, and configuration files.

```
fleet-of-agents/
├─ prompt-library/
│  ├─ prompts/
│  └─ ...
├─ agent-library/
│  ├─ agent-001-scheduler/
│  ├─ agent-002-time-tracker/
│  └─ ...
├─ tool-library/
│  ├─ ...
│  └─ ...
├─ frameworks/
│  ├─ ...
│  └─ ...
├─ requirements/
│  ├─ Dockerfile
│  ├─ requirements.txt
│  └─ ...
└─ README.md
```

1. **Prompt Library**

Contains curated prompts for different agents. Each file includes:
- Prompt definition in Markdown
- Use cases and few shot examples
- Relevant context or instructions

2. **Agent Library**

Houses the code for each micro AI assistant. Every agent might have:
- A specialized script or main file
- A README.md with usage details
- Possible Docker or environment configs

3. **Tool Library**

Provides reusable tools (e.g., text parsers, data fetching utilities) that multiple agents can share.

4. **Frameworks**

Includes any custom or third-party frameworks we’re integrating (like Phidata, Pydantic, CrewAI, LangChain or Haystack).

5. **Requirements & Config**
- **Dockerfile**: Defines a single container environment.
- **requirements.txt**: Python or other dependency listings.
- **Environment**: Potential .env files for secrets or API keys (excluded from version control).

# Dockerization

I aim to make each agent (and the entire fleet) runnable through a single Dockerfile. This will streamline:
- **Setup:** Clone the repo and build one container.
- **Execution:** Spin up any agent with minimal commands.
- **Scalability:** Deploy the container on cloud platforms or local environments with ease.

## Roadmap Highlights
1.	Category Planning (Day 2)
- Finalize how we categorize the 365 agents (e.g., Productivity, Writing, Finance).
- Create placeholders/folders for each category.
2. Project Setup (Day 3)
- Initialize the code scaffold, environment variables, Docker setup.
- Possibly integrate an orchestration layer to route tasks to the correct agent.
3. Agent Development (Day 4–365)
- Each day, introduce or refine a new agent (or multiple, if resources allow).
- Add usage documentation, tests, and any relevant domain-specific notes.

## Contributing

Interested in contributing?
- Feature Requests: Suggest new assistant ideas.
- Pull Requests: Improve existing agents or add modules to the libraries.
- Discussions & Issues: Provide feedback, report bugs, or propose design changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Stay Connected
- **Twitter/X**: [@justmalhar](https://twitter.com/justmalhar) 🛠
- **LinkedIn**: [Malhar Ujawane](https://linkedin.com/in/justmalhar) 💻

Made with ❤️ and AI by [@justmalhar](https://twitter.com/justmalhar)
