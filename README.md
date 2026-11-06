# TOI Select — Immersive Stories

## Structure
- `shared/` — components used in every story (header, byline, share bar, footer)
- `stories/_template/` — starter; copy for each new story
- `stories/<story-name>/` — one folder per story

## Branches
- `main` — final, live-ready only. No direct edits.
- `story/<story-name>` — one per story, passed between collaborators
- `shared/<change>` — changes to common components

## Workflow
1. **New story:** copy `_template` to `stories/<story-name>`, create branch `story/<story-name>`.
2. **Handoff:** pull before you start, commit, push when done, tell the next person.
3. **Publish:** Pull Request `story/<name>` into `main`, one review, merge.
4. **Shared change:** own `shared/...` branch, owner approves, check 2-3 live stories before merging.

## Rules
1. One story = one folder = one branch.
2. Never touch `shared/` from a story branch.
3. Pull before you start, push when you stop.
4. Story images/data go in that story's `assets/`.
5. Folder names lowercase-with-hyphens.
