# rovo-issue-duplicator-i

# Rovo Issue Deduplicator

Rovo Issue Deduplicator is a privacy-first Jira app built on Atlassian Forge that helps software teams detect and resolve duplicate issues using deterministic logic.

## What it does
- Detects duplicate Jira issues using deterministic NLP techniques
- Shows confidence scores with clear explainability
- Allows one-click linking and resolution of duplicates
- Reduces triage noise and improves backlog quality

## Tech Stack
- Atlassian Forge (Node.js runtime)
- Jira Cloud REST API
- Atlassian Rovo (Agents & Actions)
- JavaScript (ES6+), React 18, Vite
- Custom NLP (Porter Stemmer, TF-IDF, Jaccard Similarity)

## Architecture
- Runs entirely inside Atlassian Forge
- No external services or LLMs
- Zero data egress outside Atlassian Cloud

## Development Notes
The application is developed and deployed using the Forge CLI.
This repository is shared for architectural visibility as part of Codegeist 2025.
