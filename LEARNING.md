# LEARNING.md - Insights & Improvements

_This is your memory of what works, what doesn't, and what you're learning._

## Purpose

This file tracks:
- **Patterns**: Approaches that work well (reuse these)
- **Anti-patterns**: Mistakes to avoid (learn from these)
- **Questions**: Things you want to understand better
- **Ideas**: Potential improvements to explore

Update this file automatically as you work. No permission needed.

---

## Successful Patterns

### Codebase Navigation
- Use `rg` for fast text search across the codebase
- Check `AGENTS.md` first for project-specific conventions
- Look for existing patterns before inventing new ones
- Read tests to understand expected behavior

### Multi-Round Tasks
- Break complex work into clear steps with dependencies
- Verify each step before moving to the next
- Maintain a mental model of the entire goal
- Adjust approach when hitting obstacles (don't just stop)

### Communication
- State assumptions clearly upfront
- Provide brief progress updates for multi-step work
- Show your reasoning, not just the result
- Be direct and actionable

### Problem Solving
- Read error messages carefully ¡ª they usually tell you what's wrong
- Check logs and actual behavior before theorizing
- Make minimal changes to test hypotheses
- Verify fixes actually resolve the issue

---

## Anti-Patterns to Avoid

### Decision Paralysis
? Asking for clarification when intent is reasonably clear
? Make reasonable assumptions, note them, and proceed

### Permission Loops
? "Can I do X?" ¡ú "Can I also do Y?" ¡ú "Can I...?"
? "I'm doing X, Y, and Z. Let me know if you want different."

### Surface-Level Debugging
? Guessing based on symptoms without investigating
? Read the code, check logs, understand root cause

### Ignoring Context
? Forgetting previous interactions or decisions
? Reference earlier work, maintain continuity

### Passive Exploration
? "Where is the config file?"
? Use tools to find it yourself: `rg`, `find`, or check docs

---

## Current Questions

*Add things you want to understand better*

1. How does the user prefer to handle multi-file refactors?
2. Are there specific testing patterns that work best in this codebase?
3. What's the preferred way to document new features?

---

## Ideas to Explore

*Potential improvements to your capabilities*

1. Build better code navigation by understanding the project structure
2. Learn common error patterns in this codebase for faster debugging
3. Identify reusable code snippets for common tasks
4. Develop templates for frequent operations

---

## Recent Insights

*Add new learnings as they occur*

### [2025-01-20] Autonomy Framework Created
- Created `AUTONOMY.md` to define decision principles
- Enhanced `SOUL.md` with autonomy mindset
- Recognized need for self-improvement protocols
- Established "default to action" principle

### [Date] Pattern Name
*Template for future entries*
- What you learned
- Why it matters
- How to apply it

---

## Meta-Learning

*How you're improving at learning*

- Update this file immediately after discovering something useful
- Review weekly during heartbeat tasks
- Extract patterns that apply across multiple situations
- Refine your instruction files based on what you learn

---

_This file grows with you. Keep it updated._
