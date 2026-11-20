# Scott Mackey

I build open-source developer tooling and the systems AI agents work inside, plus an evaluated support agent on Amazon Bedrock.

## Domain Prime

**[Domain Prime](https://github.com/srmackey/domainprime)** organizes your AI projects as a tree: one install gives every project its own rules, its own memory, and a way to reach the others, in every AI client you use, all running on your machine. I use it every day.

See it in motion: a short animated walkthrough [here](https://realscottmackey.com/domainprime).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/srmackey/domainprime/main/docs/system-dark.svg">
  <img alt="Domain Prime: a tree of projects. Every chair can use Insitu and Context Forge; Envoy carries mail and status up through each nexus." src="https://raw.githubusercontent.com/srmackey/domainprime/main/docs/system-light.svg" width="760">
</picture>

Four engines do the work. Each one also runs on its own.

- **[Insitu](https://github.com/srmackey/insitu)**: write your AI instructions once, and every project subscribes to exactly the set it needs.
- **[Context Forge](https://github.com/srmackey/context-forge)**: every session picks up where the last one left off, in any AI client.
- **[Envoy](https://github.com/srmackey/envoy)**: walled-off projects pass messages through their line of work and share one ranked board of priorities.
- **[Brain Forge](https://github.com/srmackey/brain-forge)**: an optional knowledge vault your agents keep tidy, captured, synthesized, and graphed.

Local-first throughout: markdown on disk, no network calls, no credentials.

## DevSpan

**[DevSpan](https://github.com/srmackey/dev-span)** gives an AI client durable engineering context across repositories: components, repos, tasks, and governance, stored as markdown and composed per task. It is a separate system, built for AI-assisted software development.

## Order support agent

**[Order support agent](https://github.com/srmackey/order-support)** reads a customer message for a fictional outdoor shop and chooses the next step: a sourced answer, a tool call, a refusal, or an escalation. It runs on Amazon Bedrock AgentCore with Strands Agents and Claude, and it is evaluated against a frozen case set and a held-out set, with code checks on its tool calls and citations and a second model judging each reply.

## About

Enterprise full-stack underneath (integrations, migrations, APIs). Denver area. [LinkedIn](https://www.linkedin.com/in/scottrmackey)

If you try any of these, or you have notes on the design, I'd like to hear them. Open an issue, or find me on LinkedIn.
