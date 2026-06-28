# 🤖 Claude Platform 101

> **Official Anthropic Course Completion**
>
> A comprehensive learning journey through the Claude Developer Platform, covering API fundamentals, agentic AI, tool use, MCP, managed agents, and Claude Code.

![Anthropic](https://img.shields.io/badge/Anthropic-Claude-orange)
![AI](https://img.shields.io/badge/AI-Claude%20Platform-blue)
![Status](https://img.shields.io/badge/Course-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 About

This repository contains my learning notes, practical understanding, and key takeaways from **Claude Platform 101**, an official Anthropic course designed for developers who want to build AI-powered applications using the Claude API.

The course bridges the gap between simply chatting with Claude and building production-ready AI applications using agents, tools, MCP, and managed workflows.

---

# 🎯 Learning Objectives

After completing this course, I learned how to:

- Build applications using the Claude API
- Structure Messages API requests
- Choose the right Claude model
- Build autonomous AI agents
- Implement the Agent Loop
- Enable Tool Use
- Use Extended Thinking
- Manage Context Windows
- Build with MCP (Model Context Protocol)
- Work with Skills
- Build Managed Agents
- Develop using Claude Code
- Optimize cost, latency, and performance

---

# 📚 Course Modules

## Module 1 — Claude Developer Platform

- What is Claude Developer Platform?
- API Architecture
- Request & Response Lifecycle
- Messages API
- Authentication
- API Keys

### Key Learnings

- Claude applications communicate through API requests.
- Every request contains:
  - Model
  - Messages
  - Max Tokens
  - Optional System Prompt
- Responses contain generated content and metadata.

---

## Module 2 — Your First API Call

Topics Covered

- Installing SDK
- Creating Client
- Messages API
- Reading Responses
- Handling Tokens

Example Flow

```

Client
↓
messages.create()
↓
Claude
↓
Response

```

---

## Module 3 — Choosing the Right Model

Learned how to choose among:

| Model | Best For |
|---------|-----------|
| Claude Opus | Complex reasoning |
| Claude Sonnet | General-purpose applications |
| Claude Haiku | Fast, lightweight tasks |

Selection Factors

- Speed
- Cost
- Quality
- Latency
- Context Window

---

# 🤖 Module 4 — Agent Loop

One of the most important concepts.

```

User Request
↓
Claude Thinks
↓
Tool Decision
↓
Tool Executes
↓
Tool Result
↓
Claude Responds

```

The Agent Loop enables Claude to:

- Reason
- Use tools
- Observe results
- Continue until task completion

---

# 🛠 Module 5 — Tool Use

Claude can request external tools.

Examples

- Database lookup
- Weather API
- Search
- Calculator
- File operations

Important Concept

**Claude never executes tools directly.**

Instead:

```

Claude
↓
Requests Tool
↓
Your Code Executes Tool
↓
Returns Result
↓
Claude Continues

```

---

# 🧠 Module 6 — Extended Thinking

Extended Thinking allows Claude to spend additional computation on difficult problems.

Useful for:

- Planning
- Coding
- Math
- Logic
- Research
- Multi-step reasoning

---

# 📦 Module 7 — Built-in Tools

Anthropic provides built-in tools such as:

- Web Search
- Web Fetch
- Code Execution

Benefits

- Less custom implementation
- Secure execution
- Better developer experience

---

# 🔥 Module 8 — Skills

Skills package reusable workflows.

Instead of rewriting prompts:

```

Skill
↓
Reusable Instructions
↓
Claude Executes

```

Benefits

- Reusability
- Consistency
- Faster development

Example

```

/anthropic-api

```

Invokes Claude's built-in API skill inside Claude Code.

---

# 🔗 Module 9 — MCP (Model Context Protocol)

MCP standardizes communication between Claude and external tools.

Instead of creating custom integrations for every application:

```

Claude
↓
MCP
↓
External Tool

```

Benefits

- Standardized protocol
- Easy integrations
- Extensible architecture

---

# 🧠 Module 10 — Context Management

Context Windows are finite.

Important lessons:

- Every token costs money.
- Long conversations increase cost.
- Keep only relevant information.
- Summarize old context.
- Remove unnecessary history.

Goal

> Fit the **right information**, not **all information**, into the context window.

---

# 🚀 Module 11 — Managed Agents

Managed Agents allow Anthropic to manage the agent loop.

Best for:

- Background jobs
- Long-running workflows
- Sandboxed execution
- Autonomous tasks

Instead of:

```

Developer
↓
Runs Loop

```

Managed Agent

```

Anthropic
↓
Runs Loop
↓
Streams Events
↓
Returns Results

```

---

# 💻 Module 12 — Claude Code

Claude Code enables developers to work with codebases using Claude directly.

Topics Covered

- Code generation
- Refactoring
- Debugging
- API development
- Terminal workflows
- Built-in Skills
- Slash Commands

Example Command

```

/anthropic-api

```

---

# 📈 Best Practices Learned

- Choose the right model
- Keep prompts structured
- Use system prompts wisely
- Minimize token usage
- Manage context efficiently
- Reuse Skills
- Prefer MCP over custom integrations
- Build autonomous agent loops
- Use Managed Agents when appropriate

---

# 📂 Concepts Covered

- Claude API
- Messages API
- Agent Loop
- Tool Use
- Extended Thinking
- Built-in Tools
- Skills
- MCP
- Context Management
- Managed Agents
- Claude Code
- Cost Optimization
- Token Management

---

# 🏆 Key Takeaways

- Claude API is much more than prompting.
- Agentic AI relies on reasoning, tools, and structured workflows.
- Effective context management improves both quality and cost efficiency.
- Managed Agents simplify long-running, autonomous tasks.
- MCP provides a standard way to integrate external tools.
- Claude Code accelerates software development through AI-assisted workflows.

---

# 📜 Certificate

Completed the **Claude Platform 101** course provided by Anthropic.

---

# 🙌 Acknowledgements

Special thanks to **Anthropic** for providing this learning experience and helping developers understand how to build production-ready AI applications with the Claude Developer Platform.

---

## ⭐ If you found this repository useful, consider giving it a Star!
