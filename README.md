# R2D2 Team Leaderboard

Developer velocity metrics dashboard for the R2D2 team, powered by [Git Velocity](https://github.com/lukaszraczylo/git-velocity).

## Setup

1. Create a GitHub Personal Access Token (PAT) with `repo` scope
2. Add it as a repository secret named `GH_PAT`
3. Enable GitHub Pages (Settings > Pages > Source: GitHub Actions)
4. The dashboard will be generated daily and on config changes

## Configuration

Edit `config.yaml` to:
- Add/remove repositories to analyze
- Define teams and members
- Adjust date ranges
- Customize analysis options

## Manual Trigger

Go to Actions > Git Velocity Dashboard > Run workflow
