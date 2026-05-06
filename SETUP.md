# Setup Guide

Get running in 5 minutes.

## Prerequisites
- Git installed
- GitHub account (you're already a collaborator if you can see this)
- Your AI agent ready (Claude or Codex)

---

## Step 1 — Clone the repo

```bash
git clone https://github.com/Nirmoran1/Nir-Orel-Fun-House.git
cd Nir-Orel-Fun-House
```

## Step 2 — Set up your AI agent

### If you're Nir (Claude / Cowork)
- Open Claude Desktop → select this folder as your workspace
- Claude can read/write all files directly
- Use Claude to write code, update WORKSPACE.md, commit changes

### If you're Orel (Codex)
- Open your terminal in the repo folder
- Run Codex pointed at this directory
- Codex can read/write files, run commands, commit and push
- Tell Codex to read WORKSPACE.md first before starting any task

## Step 3 — Before you start working
Always do this:
```bash
git pull
```
Then read WORKSPACE.md to see what Nir is doing.

## Step 4 — Working flow
```bash
# Start a new feature
git checkout -b feature/orel-[description]

# Work, commit often
git add .
git commit -m "short description of what you did"

# When done, push
git push origin feature/orel-[description]

# Open a PR on GitHub to merge into main
```

## Step 5 — Communicate via WORKSPACE.md
Update your row in the Status table whenever your status changes.
This is how we avoid stepping on each other.

---

## Questions?
Ping Nir on WhatsApp or update WORKSPACE.md with a note.
