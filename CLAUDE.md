# CLAUDE.md - AI Assistant Guide for Ty

This document provides guidance for AI assistants working with the Ty codebase.

## Project Overview

**Ty** is a new project in early development. This guide will be updated as the project evolves.

- **Repository**: blueprintai/Ty
- **Status**: Initial development phase

## Repository Structure

```
Ty/
├── README.md          # Project documentation
├── CLAUDE.md          # This file - AI assistant guide
└── (future directories and files)
```

## Development Workflow

### Git Conventions

- **Main Branch**: Use for production-ready code
- **Feature Branches**: Use descriptive names (e.g., `feature/add-auth`, `fix/login-bug`)
- **Commit Messages**: Write clear, descriptive commit messages
  - Use imperative mood: "Add feature" not "Added feature"
  - Keep first line under 72 characters
  - Reference issues when applicable

### Code Style (To Be Defined)

As the project develops, coding standards will be established here:

- Language-specific style guides
- Linting configuration
- Formatting rules

## Key Commands

```bash
# Git operations
git status                    # Check current state
git log --oneline -10         # View recent commits
git diff                      # View uncommitted changes

# (Additional commands will be added as the project develops)
```

## AI Assistant Guidelines

### Before Making Changes

1. **Read before editing**: Always read files before modifying them
2. **Understand context**: Explore related files to understand the impact of changes
3. **Check existing patterns**: Follow established conventions in the codebase
4. **Verify assumptions**: Don't assume file contents - read them first

### When Writing Code

1. **Keep it simple**: Avoid over-engineering; implement only what's needed
2. **Security first**: Never introduce vulnerabilities (XSS, SQL injection, etc.)
3. **No secrets**: Never commit credentials, API keys, or sensitive data
4. **Minimal changes**: Only modify what's necessary for the task
5. **Prefer edits over rewrites**: Use targeted edits rather than full file rewrites

### Testing

- Run existing tests before and after changes
- Add tests for new functionality
- Ensure all tests pass before committing

### Documentation

- Update relevant documentation when making changes
- Keep comments minimal - only explain non-obvious "why"
- Keep this CLAUDE.md file updated as the project evolves

### Pull Requests

- Create descriptive PR titles (under 70 characters)
- Include a summary of changes in the PR body
- Reference related issues when applicable

## Project-Specific Notes

### Architecture Decisions

(To be documented as the project develops)

### Dependencies

(To be documented as dependencies are added)

### Environment Setup

(To be documented as development environment is established)

## Common Tasks

### Starting Development

```bash
# Clone the repository
git clone <repository-url>
cd Ty

# (Additional setup steps will be added)
```

### Making Changes

1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Commit with descriptive message
5. Push and create PR if needed

## Troubleshooting

(Common issues and solutions will be documented here)

## Quick Reference

| Task | Command/Action |
|------|----------------|
| Check status | `git status` |
| View history | `git log --oneline -10` |
| Create branch | `git checkout -b feature/name` |
| Stage changes | `git add <files>` |
| Commit | `git commit -m "message"` |

---

*Last updated: October 2026*
*This document should be updated as the project evolves and new patterns are established.*
