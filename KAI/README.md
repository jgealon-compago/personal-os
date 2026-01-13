# KAI — Knowledge and Abilities Interface

This directory defines what Claude can do — the skills, tools, and capabilities available in your personal operating system.

## What KAI Does

**KAI gives Claude execution power.** Without it, Claude is smart but can't act. With it, Claude becomes a capable assistant that can:

- Query your database
- Create and update code
- Build and deploy applications
- Automate repetitive workflows
- Execute multi-step processes

## Structure

- `skills/` — Individual capabilities Claude can execute
- `tools/` — Reusable scripts and utilities
- `workflows/` — Multi-step processes and SOPs

## How It Works

When you ask Claude to do something:

1. Claude checks KAI for relevant skills
2. Executes the appropriate tools/workflows
3. Uses PAI context to personalize the execution
4. Logs the session to Supabase

KAI + PAI = Claude that knows you and can actually do things.

## Adding New Skills

As you build tools and workflows, document them here. Claude will reference them automatically in future sessions.