# 🟩 GitHub Contribution Keeper

This repository automatically makes a commit every day at noon (UTC) to keep the GitHub contribution graph green.

## How it works

A GitHub Actions workflow runs on a daily cron schedule and:
1. Updates a `log.txt` file with the current timestamp
2. Commits and pushes the change to `main`

## Setup

1. Push this repo to GitHub
2. Go to **Settings → Actions → General** and enable workflow permissions (Read and write)
3. That's it — GitHub Actions handles the rest automatically ✅

---
*Started: September 2026*
