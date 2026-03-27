# Agent Config

[![Package Agents](https://github.com/jr-dragon/agent-config/actions/workflows/package-agents.yml/badge.svg)](https://github.com/jr-dragon/agent-config/actions/workflows/package-agents.yml)

This repository includes my agent config.

## Usage

1. Access [Release](https://github.com/jr-dragon/agent-config/releases) Page
2. Choose the latest version
3. 
  - (Claude Code) Download `agents-claude.zip`
  - (Gemini, Opencode, Codex) Download `agents-open-agent.zip`
4. Move downloaded file into project or home directory
5. Unzip it, and don't forget to remove `.zip` file


## Skills

### Go Style Guide (`go-style-guide`)

This skill helps developers write clear, concise, maintainable, and idiomatic Go code by following [Google](https://google.github.io/styleguide/go/) and [Uber](https://github.com/uber-go/guide/blob/master/style.md) Go style guides.

**Core Principles:**
- **Clarity**: Code intent and rationale should be clear to the reader.
- **Simplicity**: Achieve goals in the simplest way possible.
- **Concision**: High signal-to-noise ratio.
- **Maintainability**: Easy to maintain with good tests and error handling.
- **Consistency**: Maintain consistency with the overall codebase.

*Note: Google Style takes precedence in case of conflicts.*

### Go Project Layout (`go-project-layout`)

This skill guides developers in organizing Go project structures based on the [Standard Go Project Layout](https://github.com/golang-standards/project-layout), ensuring scalability, encapsulation, and clarity.

**Core Principles:**
- **Express Intent**: Clearly define the purpose of directories (e.g., `cmd`, `internal`, `pkg`) through the structure.
- **Encapsulation**: Use `internal` directories to enforce access control and prevent unexpected dependencies.
- **Start Simple**: Begin with a simple structure and introduce complexity only as the project grows.
- **Idiomatic**: Follow Go naming and organization conventions, avoiding patterns from other languages (e.g., avoid `src` directories).
