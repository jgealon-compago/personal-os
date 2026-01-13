# PAI — Personal AI Interface

This directory contains context about you — who you are, how you work, and what Claude should know to assist you effectively.

## What PAI Does

**PAI gives Claude personalized context.** Without it, Claude treats every session like meeting someone new. With it, Claude knows:

- Your preferences and working style
- Your current projects and priorities
- Rules and guardrails you want enforced
- Patterns and decisions you've made before

## Structure

- `profile.md` — Who you are, how you work
- `preferences.md` — Your defaults and style choices
- `projects.md` — Active projects and context
- `rules.md` — Guardrails and constraints

## How It Works

At the start of each session, Claude reads PAI to understand:

- What you're working on
- How you prefer things done
- What to watch out for
- Relevant context from past work

Combined with session logs from Supabase, Claude picks up exactly where you left off.

## Keeping It Updated

As you work:

- Tell Claude about preferences: "I prefer X over Y"
- Document decisions: "We decided to use approach Z"
- Define rules: "Always check with me before deleting data"

Claude will update PAI automatically, and it becomes your persistent context.