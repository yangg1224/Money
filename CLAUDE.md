# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Reference /docs/PRD.md for all project context

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

## Project Status

**Current State:** Planning phase - no code implementation yet
**Next Steps:** Set up iOS project structure and development environment

When development begins, this file should be updated with:
- update the Reference file /docs/PRD.md
- Build commands (e.g., `xcodebuild`, `swift build`)
- Test commands and framework
- Xcode project structure
- Dependency management details
- Development workflow
