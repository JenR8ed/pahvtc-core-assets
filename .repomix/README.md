# Repomix Configuration

This folder contains configuration files for [Repomix](https://github.com/yamadashy/repomix), ensuring AI assistants always receive accurate, complete context about this repository.

## Purpose
- Define which files/folders to include or exclude from AI context packing
- Set output format preferences (XML, Markdown, plain text)
- Establish consistent prompting instructions for AI tools

## Files
- `repomix.config.json` – Primary Repomix configuration

## Usage
```bash
# Pack the full repo for AI context
npx repomix

# Pack with this config explicitly
npx repomix --config .repomix/repomix.config.json
```
