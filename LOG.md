# LOG.md

## Done

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

## TODO

- [ ] Update site contents: replace placeholder name, bio, project cards, and contact links in `index.html`
- [ ] Make it the org's main page: rename repo to `mvcatsifma.github.io` (GitHub Settings → General → Repository name), then update local remote: `git remote set-url origin git@github.com:mvcatsifma/mvcatsifma.github.io.git`
