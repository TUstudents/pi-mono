# Pi Monorepo

A fork of [badlogic/pi-mono](https://github.com/badlogic/pi-mono) by [Mario Zechner](https://github.com/badlogic).

Tools for building AI agents and managing LLM deployments.

## Installation

```bash
npm install -g @cargo-cult/pi-coding-agent
```

## Packages

| Package | Description |
|---------|-------------|
| **[@cargo-cult/pi-ai](packages/ai)** | Unified multi-provider LLM API (OpenAI, Anthropic, Google, etc.) |
| **[@cargo-cult/pi-agent-core](packages/agent)** | Agent runtime with tool calling and state management |
| **[@cargo-cult/pi-coding-agent](packages/coding-agent)** | Interactive coding agent CLI |
| **[@cargo-cult/pi-mom](packages/mom)** | Slack bot that delegates messages to the pi coding agent |
| **[@cargo-cult/pi-tui](packages/tui)** | Terminal UI library with differential rendering |
| **[@cargo-cult/pi-web-ui](packages/web-ui)** | Web components for AI chat interfaces |
| **[@cargo-cult/pi](packages/pods)** | CLI for managing vLLM deployments on GPU pods |

## Credits

This project is a fork of the original work by [Mario Zechner](https://github.com/badlogic). All credit for the original implementation goes to him.

## License

MIT
