# AI Project Planner

An AI-powered toolkit for creating comprehensive project documentation before writing code.
Compatible with **Cursor** and similar IDE's and also with terminal-based agents like **Claude Code**.

## What It Does

Generates three essential project documents:

- **FOUNDATION.MD** - Problem, vision, constraints, and success criteria
- **ARCHITECTURE.MD** - Technical structure, components, and technology choices  
- **ROADMAP.MD** - Phased implementation with milestones and timelines

## Why Use This?

**Think before you code.** Upfront planning helps you:

- Clarify requirements and scope
- Make better architectural decisions
- Identify risks and dependencies early
- Communicate vision clearly
- Avoid costly refactoring

## Getting Started

1. Clone this repository: `git clone <repo-url>`
2. Open the `project-planner` folder in Cursor/Claude Code
3. Type `/` in chat to see available commands
4. Generate your planning documents
5. Copy outputs (FOUNDATION.MD, ARCHITECTURE.MD, ROADMAP.MD) to your project

## How It Works

Three sequential commands that build on each other:

**1. `/plan-foundation`** - Define project fundamentals

- Articulate the core problem
- Define success criteria and constraints
- Identify target users and needs
- Establish project boundaries

**2. `/plan-architecture`** - Design technical structure

- System components and interactions
- Data models and API contracts
- Technology stack with rationale
- Scalability and security

**3. `/plan-roadmap`** - Create implementation timeline

- Development phases
- Milestones with deliverables
- Dependencies between components
- Risk mitigation strategies

## Output Files

Documents are generated in the repository root:

- `FOUNDATION.MD`
- `ARCHITECTURE.MD`  
- `ROADMAP.MD`

Once satisfied, copy these to your project repository. You can overwrite them when planning a new project.

## Best Practices

- **Complete in sequence**: Foundation → Architecture → Roadmap
- **Iterate freely**: Chat with the agent to find the best solutions
- **Answer honestly**: Your answers improve output quality
- **Be specific**: Vague requirements lead to vague plans
- **Share drafts**: Get stakeholder feedback early
- **Keep updated**: Documents are living artifacts

## License

MIT License - Use freely in your projects.

---
