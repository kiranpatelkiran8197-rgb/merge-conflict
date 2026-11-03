# Experiment 2 — Git Branching and Merge Conflict

## Repository
https://github.com/kiranpatelkiran8197-rgb/merge-conflict

## Work completed
1. Created `index.html` on `main` with the Karnataka Chief Minister sample profile and the initial contact line: `Not yet added`.
2. Created `Raja` and `Pooja` from the same original `main` commit.
3. On `Raja`, changed the contact line to `943656789`. Commit: `337367fc926fb13d4d5f84c8c3bedee7061af219`.
4. On `Pooja`, changed the same original contact line to `9466677788`. Commit: `a353781997bd96f810df03602ca938b6b850291b`.
5. Opened and merged PR #1 (Raja -> main): https://github.com/kiranpatelkiran8197-rgb/merge-conflict/pull/1
6. Opened PR #2 (Pooja -> main) after PR #1 had merged. The two branches had competing edits to the same contact line, demonstrating the merge conflict.
7. Resolved the conflict on `Pooja` by keeping Raja's contact number, `943656789`. Resolution commit: `373424f10a9a672589d0ccd096056dce9ed6c0fb`.
8. Merged PR #2: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/pull/2

## Final verification
- Both pull requests are merged.
- The final `main/index.html` contains exactly `<p>Contact No: 943656789</p>`.
- No Git conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`) remain in the final file.

## Evidence links to show during evaluation
- Repository: https://github.com/kiranpatelkiran8197-rgb/merge-conflict
- Main HTML file: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/blob/main/index.html
- Raja branch: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/tree/Raja
- Pooja branch: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/tree/Pooja
- PR #1: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/pull/1
- PR #2: https://github.com/kiranpatelkiran8197-rgb/merge-conflict/pull/2

## Screenshot checklist for the lab record
Capture these screenshots from GitHub in your browser:
1. Repository page showing the files and branches.
2. `index.html` on the Raja branch showing contact number `943656789`.
3. `index.html` on the Pooja branch commit history showing its original change to `9466677788` (the later resolution commit is also visible).
4. PR #1 showing it is merged.
5. PR #2 showing the conflict-resolution commit and that it is merged.
6. Final `main/index.html` showing `943656789`.

These are links to the actual GitHub work. Screenshots must be captured from the browser on your computer; this evidence file does not claim that local VS Code screenshots were captured.
