# CLAUDE.md - AI Assistant Guidelines

This document provides guidance for AI assistants working with this repository.

## Repository Overview

**Name:** my_test
**Type:** Learning/Practice Repository
**Purpose:** A test repository for practicing Git and GitHub workflows
**Primary Language:** Text files (no programming language)

## Directory Structure

```
/home/user/my_test/
├── CLAUDE.md                    # AI assistant guidelines (this file)
├── README.md                    # Repository description (Japanese)
├── hello_from_antigravity.txt   # Test file for Git practice
└── GitHub_practice.txt          # Placeholder file for practice
```

## File Descriptions

| File | Description |
|------|-------------|
| `README.md` | Main documentation - contains Japanese text: "これはテスト用のリポジトリです！" (This is a repository for testing!) |
| `hello_from_antigravity.txt` | Test file with greeting message |
| `GitHub_practice.txt` | Empty placeholder file for Git practice |
| `CLAUDE.md` | Guidelines for AI assistants working with this repo |

## Development Workflows

### Git Workflow

This repository uses a simple Git workflow:

1. **Main Branch:** `main` - primary branch for stable content
2. **Feature Branches:** Use `claude/` prefix for AI-generated changes

### Making Changes

```bash
# Check current status
git status

# Stage changes
git add <filename>

# Commit with descriptive message
git commit -m "Description of changes"

# Push to remote
git push -u origin <branch-name>
```

## Conventions

### Commit Messages

- Use clear, descriptive commit messages
- Start with a verb (Add, Create, Update, Fix, Remove)
- Keep subject line under 50 characters when possible

### File Naming

- Use lowercase with underscores for text files (e.g., `hello_from_antigravity.txt`)
- Use standard names for documentation (e.g., `README.md`, `CLAUDE.md`)

### Language

- Documentation may include Japanese text
- English is acceptable for technical content and AI-generated documentation

## AI Assistant Guidelines

### When Working on This Repository

1. **Understand the Context:** This is a minimal practice repository, not a production codebase
2. **Keep Changes Simple:** Match the repository's straightforward nature
3. **Document Changes:** Update relevant documentation when adding files
4. **Follow Git Best Practices:** Use meaningful commit messages and proper branching

### What AI Assistants Should Know

- No build system or package manager is configured
- No tests or CI/CD pipelines exist
- The repository is primarily for learning Git operations
- Files are plain text with no special formatting requirements

### Recommended Actions for AI Assistants

- **DO:** Create clear documentation, practice Git workflows, add helpful text files
- **DO:** Follow the existing simple structure
- **DON'T:** Over-engineer solutions for this practice repository
- **DON'T:** Add complex build systems unless specifically requested

## Configuration

### No Configuration Files Present

This repository intentionally has no configuration files:
- No `package.json`, `requirements.txt`, or build files
- No `.gitignore` (consider adding one if binary files are introduced)
- No CI/CD configuration

### If Adding Code in the Future

Consider adding:
- `.gitignore` - to exclude generated files
- Appropriate package manager config for the chosen language
- Test configuration if implementing testable code

## Quick Reference

| Task | Command |
|------|---------|
| Check status | `git status` |
| View history | `git log --oneline` |
| Create branch | `git checkout -b branch-name` |
| Push changes | `git push -u origin branch-name` |

## Repository Metadata

- **Created by:** shinsaku14252-cell
- **Creation Date:** January 2026
- **License:** Not specified
- **Remote:** GitHub (via proxy)

---

*This CLAUDE.md was created to help AI assistants understand and work with this repository effectively.*
