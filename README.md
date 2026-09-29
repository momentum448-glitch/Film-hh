# FILM HH — Hai Kẻ Hành Tẩu

AI animation production project using GPT + Google Flow.

## Storage model

- **Google Drive** = source of truth for media/assets: character images, environment references, props, storyboards/keyframes, Flow QC videos, exports.
- **GitHub** = version control for text/control plane: canon mirror, handoff mirror, prompts, shot specs, production logs, changelog.

## Google Drive

Project root: https://drive.google.com/drive/folders/1afcnCJerfN69GN6ZnoKDWsT8260q7zAO

Drive structure:
- `00_PROJECT_CONTROL`
- `01_ASSETS`
- `02_VIDEO_QC`
- `03_EXPORTS`
- `99_ARCHIVE`

## Resume protocol

User trigger phrase: **“tiếp quản dự án đi em”**

Resume order:
1. Read `docs/HANDOFF_CURRENT.md`.
2. Read `docs/PROJECT_CANON.md`.
3. Verify handoff's expected canon version.
4. Check Drive asset references.
5. Continue from `NEXT ACTION EXACT`; do not redo locked discovery unless there is a conflict.

## Tool policy

For project storage/management, use only:
- Google Drive plugin
- GitHub plugin

Do not use Remote Desktop Commander for FILM_HH.

## Current phase

Pre-production → Character Design Sprint #01 → clean production character references.
