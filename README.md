# Conversation with GitHub Copilot (GPT-5.1-Codex-Max)

This repository captures the conversation I had with GitHub Copilot in VS Code using the GPT-5.1-Codex-Max model. The session was driven through the agent workflow provided by the AI Toolkit.

## How this conversation unfolded

- **Starting point:** I selected the **analyse-agent** and typed the first prompt to kick off the session.
- **Agent handoff:** From there, I followed the agent handoff through the conversation (analyse → plan → implement → validate), letting each agent guide the next step.

## What’s in this repo

- `Conversation.md` — the full transcript of the exchange.
- `agents/` — agent configuration files used during the workflow:
  - `analyse-agent.agent.md`
  - `plan-agent.agent.md`
  - `implement-agent.agent.md`
  - `validate-agent.agent.md`

## How to read this

1. Open `Conversation.md` to see the dialogue as it happened.
2. Browse the `agents/` folder to understand the roles and prompts each agent used.
3. Follow the sequence to see how the agents collaborated from the first prompt through completion.

## Notes

- Model: **GPT-5.1-Codex-Max (Preview)** via GitHub Copilot in VS Code.
- Purpose: Document the workflow and handoff between agents during a real Copilot session.
