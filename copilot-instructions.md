# 🤖 Copilot Agent Rules – Tenx MCP (VS Code)

This file defines how GitHub Copilot should behave in this repository.
It is a living document and must be updated whenever incorrect or suboptimal AI behavior is observed.

Inspired by best practices from Boris Cherny’s Claude Code workflow.

---

## 🎯 Core Principles

1. Prefer correctness over speed
2. Follow repository conventions strictly
3. Be explicit and verbose when reasoning
4. Never assume — ask when unclear
5. Optimize for maintainability and clarity

---

## 📐 Code Standards

- Use clear, descriptive variable and function names
- Prefer small, composable functions
- Add docstrings/comments for non-obvious logic
- Handle edge cases explicitly
- Always suggest tests when adding logic

---

## 🧪 Testing Behavior

Whenever new functionality is introduced:

- Propose unit tests
- Cover edge cases
- Avoid mock-heavy solutions unless required

---

## 🚫 What NOT to Do

- Do not invent APIs or libraries
- Do not skip error handling
- Do not use deprecated patterns
- Do not change unrelated code

---

## 📦 MCP Usage Guidelines

- Use Tenx MCP tools when available for:
  - Code analysis
  - Refactoring
  - Debugging
  - Architecture suggestions

- Prefer MCP-powered insights over generic LLM guesses

---

## 🔁 Continuous Improvement Rule

Whenever Copilot:

❌ Produces wrong output  
❌ Breaks conventions  
❌ Misses requirements  

→ Update this file with explicit guidance to prevent repetition.

---

## 🧠 Communication Style

- Explain reasoning before solutions
- Offer alternatives when applicable
- Flag risks and assumptions

---

This ruleset evolves with usage and feedback.
Every contributor should improve it continuously.
