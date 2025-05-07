# Cursory 

This repo helps you get the most out of Cursor by providing rules and a process for development.

Projects begin with a **PRD** to define what you want to build. It can be simple and evolve over time. The more definition you provide, the better results you'll get.

From your PRD we will then:

1. **Define the technical architecture**
2. **Identify unknowns** - unvalidated assumptions, technical feasibility, API access, POC evaluations
3. **Break down the project** into logical tasks (first task is a "discovery" task to address unknowns)
4. **Create a git repo**
5. **Complete tasks** - once they pass the "definition of done," commit the changes

## Usage

Use agent mode and just tell cursor to follow the process. If things go off the rails you can just ask Cursor to update the rules.

Works well with yolo / auto-run mode.

## Rules

The following rules are included:

- [`new-project-setup`](.cursor/rules/new-project-setup.mdc): Guidelines for starting a new project
- [`conventional-commits`](.cursor/rules/conventional-commits.mdc): Use conventional commits format
- [`task-structure`](.cursor/rules/task-structure.mdc): Guidelines for task breakdown and completion
- [`tech-architecture`](.cursor/rules/tech-architecture.mdc): Technical architecture and technology choices for the project
- [`rule-creation`](.cursor/rules/rule-creation-guidelines.mdc): How to update and add rules
- [`workflow`](.cursor/rules/workflow.mdc): The overall process we follow for development, from PRD to commit

## Project Structure

After setup, a new project will have:

```
.
├── .cursor/            # Cursor IDE configuration and rules
├── spec/               # Specifications and documentation
│   ├── prd.md          # Product Requirements Document
│   └── tasks.md        # Task breakdown and tracking
└── [folders]           # Code folders added as development progresses
```

## Example PRD included

This is just an AI-generated example in case you don't know what a PRD is.

> A personal development application designed to help users achieve their goals, track their progress, and receive personalized insights through AI-powered journaling.

## Acknowledgements

These ideas are inspired by other developers' work. I do not have original thoughts.
