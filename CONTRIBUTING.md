\# Contributing to getunstucked



Thanks for helping build getunstucked! This is a Tauri + React app for deliberate coding sessions and on-screen mentoring.



\## Quick rules (important)

\- \*\*No binaries\*\* in PRs (`.exe`, `.msi`, `.dmg`, `.app`, `.dll`, `.so`, `.zip` builds). PRs containing binaries will be closed.

\- Keep changes small and focused.

\- If adding dependencies, explain why in the PR description.



\## How to contribute

1\. Open an Issue first (Bug / Feature / Feedback).

2\. Fork the repo and create a branch: `feat/<name>` or `fix/<name>`

3\. Make changes and open a PR.



\## Development

\- `npm install`

\- `npm run dev`

\- `npm run build`



\## Security-sensitive areas

PRs that touch any of the following will be reviewed very strictly:

\- networking (HTTP calls, websockets)

\- filesystem access

\- process execution / spawning

\- new dependencies



\## Code of Conduct

Be respectful. Assume good intent. No harassment.

