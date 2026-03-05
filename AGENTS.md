# AGENTS.md

## Project Overview

This repository contains a global `.gitignore` file intended to be symlinked as the user's global gitignore (`~/.gitignore`). It tracks patterns for files that should be ignored across all Git repositories on a machine.

## Conventions

- The `.gitignore` file at the project root is the single source of truth.
- Patterns should be OS-agnostic and editor-agnostic where possible. OS- or editor-specific patterns are acceptable when broadly useful.
- Keep patterns grouped logically (e.g., environment files, lock files, editor artifacts) and sorted within groups.
- Do not add project-specific patterns here; those belong in each project's own `.gitignore`.
