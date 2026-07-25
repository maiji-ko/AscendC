# AGENTS.md — AscendC

## What this is

Obsidian vault of Chinese-language study notes on **Ascend C 算子开发(初级)** (Ascend C Operator Development, Beginner Level). Covers basic operator concepts, Ascend C / CANN fundamentals, and the Ascend AI processor architecture.

## Structure

- `Ascend C算子开发(初级).md` (repo root) — table of contents / index
- `Ascend C算子开发(初级)/` — note files
  - `1.什么是算子/` — operator concepts, runtime demo, challenges
  - `2.什么是Ascend C/` — CANN, Ascend C, processor architecture
- Each subdirectory contains markdown files (`.md`)

## Notes

- Content is entirely in **Chinese (Simplified)**
- No code, no build tools, no test framework, no CI/CD
- `.gitignore` lists `.obsidian` but the directory is committed anyway
- All commits are automated Obsidian vault backups (`git log` shows "vault backup" messages)
- No npm, pip, or other package manifests exist
- `Ascend C算子开发(初级).md` at repo root is a table of contents with Obsidian wikilinks to each note

## No-op commands

The following standard actions do not apply here:
- `npm install` / `pip install` — no dependencies
- `npm test` / `npm run lint` / `npm run typecheck` — no code
- `npm run build` — nothing to build
