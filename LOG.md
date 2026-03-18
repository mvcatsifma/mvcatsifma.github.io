# LOG.md

## 2026-03-18

- Created plain HTML/CSS personal portfolio site
- Dark theme with CSS variables, responsive layout
- Sections: hero, about, projects, contact
- Added GitHub Actions workflow (`.github/workflows/deploy.yml`) for auto-deploy on push to `main`
- Pushed to `git@github.com:mvcatsifma/site.git`
- Site live at https://mvcatsifma.github.io/site/
- Created fine-grained GitHub PAT (Administration rw, Contents rw, Metadata r); stored in `~/.claude/settings.json` as `GITHUB_PERSONAL_ACCESS_TOKEN`
- Installed `gh` CLI and authenticated with the PAT
- Configured GitHub MCP plugin for Claude Code using the PAT
- Reviewed all 45 GitHub repositories one by one; deleted 25, kept 20
- Updated site with real content: profile picture (from GitHub avatar), name, tagline, subtitle, about section (from LinkedIn)
- Cleaned up hero section: removed nav name, GitHub button, view my work button
- Tightened spacing between sections
- Projects section left empty pending selection of repos to feature

