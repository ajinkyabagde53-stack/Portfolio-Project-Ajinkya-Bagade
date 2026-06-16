# Portfolio Project — Setup Log

## Tools Installed

- **Cursor IDE** — cursor.com
- **Claude Code** — Anthropic's AI coding extension for Cursor
- **Codex** — OpenAI's coding agent extension for Cursor
- **GitHub Desktop** — desktop application to connect GitHub repos locally
- **Git** — version control system (installed during setup)

## Method 1: Manual Setup

### Steps Completed

1. Installed Cursor IDE on my work system
2. Logged into Cursor using my GitHub account — automatically connected Cursor to GitHub
3. Opened the Extensions panel in Cursor
4. Searched and installed the Claude Code extension
5. Searched and installed the Codex extension
6. Created a public GitHub repository: Portfolio-Project-Ajinkya-Bagade
7. Initially accessed GitHub through Chrome — repository did not show up in Cursor
8. Downloaded and installed GitHub Desktop application
9. Repository automatically appeared in Cursor after GitHub Desktop was installed
10. Opened the repository inside Cursor
11. Attempted to create README using Cursor AI — not available on free plan
12. Could not find file explorer in Cursor — interface defaults to AI agent view
13. Used View menu to locate Terminal option
14. Tried creating README using bash command — failed because terminal runs PowerShell on Windows
15. Created README.md using PowerShell command: New-Item README.md
16. Opened file in Notepad via PowerShell: notepad README.md
17. Git commands failed — terminal was in wrong directory
18. Cloned the repository properly using git clone and navigated into correct folder
19. Pasted README content, saved, committed and pushed to GitHub

### Issues Encountered

**Problem 1:** Extensions tab missing on personal laptop after installing Cursor.
**Solution:** Switched to work system where Cursor loaded correctly.

**Problem 2:** GitHub repository did not show up in Cursor when using GitHub through Chrome.
**Solution:** Downloaded and installed GitHub Desktop. Repository appeared in Cursor immediately after.

**Problem 3:** Cursor AI prompted to create README but Cloud Agents require a paid plan.
**Solution:** Created the file manually using the terminal instead.

**Problem 4:** Could not find file explorer in Cursor — interface only showed AI agent view.
**Solution:** Used View menu to access Terminal.

**Problem 5:** Bash command to create README failed — terminal runs PowerShell on Windows.
**Solution:** Used PowerShell command New-Item README.md to create the file.

**Problem 6:** Git commands returned "fatal: not a git repository" error.
**Solution:** Terminal was running in wrong directory. Cloned the repo using git clone and navigated into the correct folder before running git commands.

---

## Method 2: Agentic Setup (Using Cursor AI Agent)

### Steps Completed

1. Created a new repository in GitHub account
2. Logged into Cursor using GitHub sign-in
3. Used Cursor's "Clone Repository" feature to clone the repo and save it locally
4. Gained full access to the repository directly inside Cursor
5. Prompted the Cursor AI agent to create the README file and push it to the repository
6. Modified and updated the README content through follow-up prompts — the agent handled all commits and pushes without any manual terminal work

### Key Difference

The agentic method eliminated all manual terminal commands. Once the repo was cloned and the agent was given instructions, it handled file creation, commits, and pushes autonomously — significantly faster and more efficient than the manual approach.

---

## Status

✅ Cursor IDE installed
✅ Claude Code extension installed and active
✅ Codex extension installed and active
✅ Git installed
✅ GitHub Desktop installed
✅ GitHub repository created and connected to Cursor
✅ README created and pushed to GitHub via both manual and agentic methods
