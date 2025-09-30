# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Reference `/docs/PRD.md` for all project context and the following documentation structure:

```
/docs/
├── COMPONENTS.md          # Component catalog with usage examples
├── MILESTONES.md         # Development history and lessons learned
├── ARCHITECTURE.md       # How everything connects and why
├── DECISIONS.md          # Technical choices and their rationale
├── PATTERNS.md           # Reusable code patterns and conventions
└── TROUBLESHOOTING.md    # Common issues and solutions
```

This is a Spending Tracker iOS app project with iOS Shortcuts integration. Currently in planning phase with only the PRD (Product Requirements Document) available.

**Key Features:**
- Quick expense entry via iOS Shortcuts
- Local-only data storage (privacy-focused)
- Manual expense editing and categorization
- Analytics dashboard with charts
- CSV export functionality

## Development Notes

**Target Platform:** iOS (Swift/SwiftUI)
**Data Storage:** Local-only (Core Data or secure file storage)
**Key Integrations:** iOS Shortcuts, SiriKit, Files app

**Architecture Priorities:**
- Privacy-first design (no cloud sync)
- Shortcut parameter handling (amount, category, note)
- Accessible UI following Apple HIG
- Performance for thousands of local entries

**Core Data Model:** Expense entries with amount, category, note, timestamp

**Development Phases (per PRD):**
1. Foundation & Shortcut Integration (4 days)
2. Editing, Visualization & Export (3 days)
3. Final Polish & User Testing (3 days)
4. Launch Readiness (1-2 days)

## Documentation Maintenance

**CRITICAL COMMITMENT:** Every change to the codebase requires updating the relevant documentation files:

- **COMPONENTS.md** - Update when adding/modifying UI components
- **MILESTONES.md** - Record significant development milestones and lessons learned
- **ARCHITECTURE.md** - Update when making architectural changes or design decisions
- **DECISIONS.md** - Document all technical choices and their rationale
- **PATTERNS.md** - Add new reusable patterns as they emerge
- **TROUBLESHOOTING.md** - Document solutions to issues encountered during development

This ensures comprehensive project knowledge is maintained and accessible throughout development.

## Project Status

**Current State:** Planning phase - no code implementation yet
**Next Steps:** Set up iOS project structure and development environment

When development begins, documentation should be updated with:
- **ARCHITECTURE.md** - Project structure and dependencies, update the drawio flow chart 
- **DECISIONS.md** - Build system choices and development workflow
- **COMPONENTS.md** - Core components as they're built
- **PATTERNS.md** - Established coding patterns
- **TROUBLESHOOTING.md** - Common development issues
- **MILESTONES.md** - Key development achievements
