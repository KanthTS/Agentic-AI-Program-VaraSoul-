# 🤖 Claude Code 101

> Learn how to build, debug, and ship software faster using Claude Code — Anthropic's agentic AI coding assistant.

![Claude Code](https://img.shields.io/badge/Claude-Code-blue)
![Anthropic](https://img.shields.io/badge/Powered%20By-Anthropic-orange)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-green)

---

## 📖 Overview

Claude Code 101 introduces developers to **Claude Code**, an AI-powered coding agent that works directly inside your development environment.

Unlike traditional chat-based AI tools, Claude Code can:

* Explore entire codebases
* Read and edit files
* Execute terminal commands
* Run tests
* Interact with Git
* Create commits
* Delegate work to subagents
* Integrate with external tools

The course teaches developers how to collaborate effectively with AI throughout the software development lifecycle.

Claude Code is available in:

* Terminal CLI
* VS Code
* JetBrains IDEs
* Claude Desktop
* Web
* Slack

---

# 🎯 Learning Objectives

By completing Claude Code 101, you will be able to:

* Understand how agentic coding differs from chat-based coding.
* Install and configure Claude Code.
* Write effective prompts for development tasks.
* Use Plan Mode to guide AI behavior.
* Navigate unfamiliar codebases.
* Apply the Explore → Plan → Code → Commit workflow.
* Manage long-running contexts efficiently.
* Use project memory effectively.
* Delegate tasks to subagents.
* Extend Claude using MCP servers and hooks.
* Build reliable AI-assisted development workflows.

---

# 🧠 What is Claude Code?

Claude Code is an **agentic coding assistant**.

Traditional AI Chat:

```
You ask → AI answers
```

Claude Code:

```
You ask
↓
Claude explores
↓
Claude plans
↓
Claude edits files
↓
Claude runs commands
↓
Claude verifies results
↓
Claude commits changes
```

It actively participates in software development rather than simply generating text.

---

# ⚙️ How Claude Code Works

Claude Code operates through an **Agentic Loop**.

```
Understand Request
       ↓
Gather Context
       ↓
Use Tools
       ↓
Reason
       ↓
Take Action
       ↓
Verify
       ↓
Repeat Until Complete
```

This loop enables Claude to solve multi-step problems autonomously while keeping the developer in control.

---

# 🛠 Installation

## Requirements

* macOS, Linux, or Windows
* Terminal access
* Claude subscription or Anthropic Console account

---

## Install (macOS/Linux)

```bash
curl -fsSL https://claude.ai/install.sh | bash
```

---

## Install (Windows PowerShell)

```powershell
irm https://claude.ai/install.ps1 | iex
```

---

## Start Claude Code

Navigate to your project:

```bash
cd my-project
```

Launch Claude:

```bash
claude
```

---

# 💬 Your First Prompt

Example:

```text
Explore this repository and explain its architecture.
```

Claude will:

* Scan the repository
* Identify major components
* Explain relationships
* Summarize functionality

---

# ✨ Prompting Best Practices

## Be Specific

❌ Bad:

```text
Fix this.
```

✅ Good:

```text
Investigate why the login API returns 500 errors and suggest fixes.
```

---

## Define Constraints

Example:

```text
Implement this feature without modifying authentication modules.
```

---

## Provide Context

Example:

```text
This is a React frontend using TypeScript and Redux Toolkit.
```

---

## Break Complex Tasks

Instead of:

```text
Build the whole system.
```

Use:

```text
1. Explore the codebase.
2. Design the approach.
3. Implement changes.
4. Run tests.
```

---

# 🗺 Plan Mode

Plan Mode helps developers review Claude's intended actions before execution.

Example:

```text
Plan how you would implement password reset functionality.
```

Claude generates:

* Analysis
* Design decisions
* Files affected
* Risks
* Implementation steps

before making changes.

Benefits:

* Better control
* Fewer mistakes
* Increased transparency

---

# 🔍 Explore → Plan → Code → Commit

This is the core Claude Code workflow.

## 1. Explore

Understand the project.

Examples:

```text
Explain this repository.
```

```text
Find authentication logic.
```

```text
Trace the payment flow.
```

---

## 2. Plan

Design before coding.

Examples:

```text
Propose an implementation strategy.
```

```text
Identify impacted modules.
```

---

## 3. Code

Implement the solution.

Examples:

```text
Add JWT refresh token support.
```

```text
Refactor duplicated functions.
```

---

## 4. Commit

Finalize changes.

Examples:

```text
Generate a commit message.
```

```text
Commit all verified changes.
```

---

# 📂 Working With Repositories

Claude can:

## Navigate Codebases

```text
Where is the order processing logic?
```

---

## Trace Dependencies

```text
Show how this module interacts with others.
```

---

## Explain Legacy Code

```text
Explain this function line by line.
```

---

## Identify Technical Debt

```text
Suggest refactoring opportunities.
```

---

# 🧪 Testing Workflows

Claude can assist with testing.

## Generate Tests

```text
Write unit tests for this service.
```

---

## Run Existing Tests

```text
Execute test suites and summarize failures.
```

---

## Debug Failures

```text
Investigate why these tests are failing.
```

---

## Improve Coverage

```text
Identify untested edge cases.
```

---

# 🧠 Context Management

Large projects require efficient context handling.

Claude Code teaches developers to manage context intentionally.

Strategies include:

## Keep Sessions Focused

Avoid mixing unrelated tasks.

---

## Refresh Context

Reintroduce objectives periodically.

Example:

```text
We are still working on optimizing authentication performance.
```

---

## Use Summaries

Summarize progress before switching tasks.

---

## Start New Sessions

When discussions become too broad.

Benefits:

* Better accuracy
* Reduced confusion
* Improved productivity

---

# 📝 Project Memory

Project Memory stores reusable project knowledge.

Examples:

* Coding standards
* Architectural patterns
* Naming conventions
* Team preferences
* Frequently used workflows

Benefits:

* Consistency
* Faster onboarding
* Reduced repetition

---

# 👥 Subagents

Claude can delegate specialized work.

Examples:

### Documentation Agent

Generates documentation.

---

### Testing Agent

Focuses on test creation.

---

### Refactoring Agent

Improves maintainability.

---

### Research Agent

Investigates unfamiliar libraries.

Benefits:

* Parallel thinking
* Separation of concerns
* Improved organization

---

# 🔌 MCP (Model Context Protocol)

MCP extends Claude's capabilities.

It allows Claude to interact with external systems safely.

Examples:

* GitHub
* Databases
* APIs
* Internal tools
* Documentation platforms

Benefits:

* Tool integration
* Automation
* Richer workflows

---

# 🪝 Hooks

Hooks execute actions automatically.

Examples:

Before coding:

```text
Run static analysis.
```

After coding:

```text
Execute tests.
```

Before commits:

```text
Validate formatting.
```

Benefits:

* Consistency
* Reliability
* Automation

---

# 🔒 Safety and Human Oversight

Claude Code prioritizes developer control.

Principles include:

* Ask permission before sensitive actions.
* Keep humans in decision loops.
* Review generated changes.
* Verify outputs through testing.
* Use Plan Mode when uncertainty exists.

AI assists developers.

It does not replace engineering judgment.

---

# 🚀 Practical Use Cases

Claude Code excels at:

## Feature Development

* Building new functionality
* Implementing enhancements

## Bug Fixing

* Root cause analysis
* Applying fixes

## Refactoring

* Improving readability
* Removing duplication

## Documentation

* README generation
* API explanations

## Testing

* Creating tests
* Diagnosing failures

## Learning

* Understanding unfamiliar repositories
* Explaining concepts

---

# 💡 Best Practices

✔ Start with exploration.

✔ Use Plan Mode often.

✔ Provide detailed prompts.

✔ Review generated code.

✔ Test everything.

✔ Commit incrementally.

✔ Manage context carefully.

✔ Treat Claude as a collaborator.

---

# 📚 Key Takeaways

Claude Code transforms software development from:

```text
Developer → Tool
```

into:

```text
Developer ↔ Intelligent Coding Partner
```

The most effective developers are not those who surrender control to AI, but those who learn how to guide, supervise, and collaborate with it effectively.

Master the workflow:

```
Explore
↓
Plan
↓
Code
↓
Test
↓
Commit
```

and you'll unlock the full potential of agentic software development.

---

## 📜 Certificate

Claude Code 101 provides a certificate of completion through Anthropic Academy after successfully completing the course requirements.

---

## 📖 References

* Anthropic Academy
* Claude Code Documentation
* Claude Code Quickstart Guide
* Claude Product Documentation

---

## ⭐ Final Thought

> "AI won't replace developers. Developers who know how to work effectively with AI will redefine what great software engineering looks like."

Happy Coding! 🚀
