# 🤖 PM Claude Sub-Agents

A collection of specialized Claude Code sub-agents for Product Managers. Drop these into your `.claude/agents/` folder and get an instant AI-powered PM team.

## What are Claude Sub-Agents?

Sub-agents are permanent, specialized AI team members with distinct personalities and expertise. Unlike regular Claude, each sub-agent has a focused role, consistent behavior, and can be called on anytime.

## The Team

| Agent | Role | Best For |
|-------|------|----------|
| `product-manager` | Product strategy & vision | Feature prioritization, roadmap decisions, market analysis |
| `project-manager` | Delivery & execution | Sprint planning, risk tracking, stakeholder coordination |
| `scrum-master` | Agile facilitation | Retrospectives, sprint ceremonies, velocity improvement |
| `assumption-mapping` | Risk & validation | Identifying risky assumptions, de-risking decisions |
| `backlog-grooming` | Backlog refinement | Grooming user stories, sprint readiness, prioritization |
| `sales-engineer` | Product ↔ Sales bridge | Technical demos, objection handling, pre-sales support |
| `engineer` | Technical feasibility | Spec reviews, architecture feedback, implementation risks |
| `executive` | Strategic framing | Executive summaries, stakeholder communication, business cases |
| `user-researcher` | User insights | Interview synthesis, pain point analysis, persona refinement |

## How to Install

1. Copy any `.md` file from this repo
2. Paste it into your project's `.claude/agents/` folder
3. That's it — the agent is immediately available!

## How to Use

**Explicit invocation:**
```
Use the product-manager subagent to prioritize these features
Have the user-researcher subagent analyze these interview transcripts
Ask the engineer subagent to review this spec for technical feasibility
```

**Multi-agent review:**
```
Have the engineer, executive, and user-researcher subagents all review this PRD
```

## Sources

- Original PM course agents (engineer, executive, user-researcher) from [Claude for Everyone PM Course](https://fullstackpm.com)
- Additional agents sourced from [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents)

## Contributing

Found a great PM-focused sub-agent? PRs welcome! Keep the format consistent — YAML frontmatter + system prompt.

---

*Built for Product Managers using [Claude Code](https://claude.ai/code)*
