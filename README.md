# GetUnstucked
A desktop app for deliberate coding sessions with visible, local-first mentoring and forced end-of-session decisions.

## Feedback & feature requests
Watching from YouTube? Please don’t DM — open an Issue instead:

- 🐛 Bug: use **Bug report**
- 💡 Feature: use **Feature request**
- 🧠 UX thoughts: use **Feedback / UX**

I triage issues on stream and tag beginner-friendly tasks with `good first issue`.

## Contributing & Workflow

Thanks for your interest in contributing to **getunstucked**!  
This project follows a simple, safe workflow to keep `main` stable and reviewable.

### Ground rules
- **Do not push directly to `main`**
- All changes go through **Pull Requests**
- The maintainer reviews and approves all merges
- No binaries (`.exe`, `.dmg`, `.zip`, etc.) in PRs

---

## How to contribute (step by step)

### 1️⃣ Fork the repository
Click **Fork** on GitHub to create your own copy of the repo.

Clone your fork locally:
```bash
git clone https://github.com/<your-username>/getunstucked.git
cd getunstucked

2️⃣ Create a feature branch

Create a new branch for your work (never work on main):

git checkout -b feat/short-description

Branch naming convention:
feat/... → new features
fix/... → bug fixes
chore/... → cleanup, docs, tooling

Examples:
feat/session-timer
fix/overlay-render
chore/readme-update

3️⃣ Make your changes
Work freely on your branch:
Commit early
Commit often
Small, focused commits are preferred

Example:
git add .
git commit -m "feat: add basic session timer UI"

Push your branch:
git push -u origin feat/short-description

4️⃣ Open a Pull Request
On GitHub:
Base branch: main
Compare branch: your feature branch
In the PR description, explain:
What you changed
Why you changed it
Any tradeoffs or open questions

5️⃣ Review & merge
The maintainer will review your PR
You may be asked to make changes
Once approved, it will be merged into main
Protected rules:
PR review required
Approvals reset on new commits
CodeQL checks must pass
Force pushes are blocked
Reporting bugs or ideas (no code needed)
If you’re not contributing code, that’s totally fine.
Please use GitHub Issues:
🐛 Bugs → Bug report
💡 Ideas → Feature request
🧠 UX thoughts → Feedback / UX

Issues are triaged publicly and discussed on stream when relevant.
Security:
Do not include secrets or credentials in commits
Do not submit compiled binaries
If you find a security issue, use private vulnerability reporting
Thanks for helping make this project better 🚀

---

### What this gives you
- Clear contributor expectations  
- Zero ambiguity about branches & PRs  
- Matches your **branch protection + rulesets exactly**  
- Professional OSS vibe (this reads like real projects)

### Next step
Example:
After pasting this:
bash:
git add README.md
git commit -m "docs: add contribution workflow"
git push