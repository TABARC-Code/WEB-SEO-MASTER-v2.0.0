# GitHub Repository Setup Guide

For TABARC-Code/web-seo-master

## Step 1: Create Repository on GitHub

1. Go to github.com → New Repository
2. Repository name: `web-seo-master`
3. Description: "Expert Claude AI skill for SEO, YouTube, UX, and conversion optimisation"
4. Visibility: **Public**
5. Initialize with: **Add .gitignore** (select Python or general)
6. Add **MIT License**
7. Click **Create Repository**

---

## Step 2: Repository Settings

### General
- **Default branch:** main
- **Require pull request reviews before merging:** Off (unless team)
- **Automatically delete head branches:** On
- **Allow auto-merge:** Off

### Code Security and Analysis
- **Dependabot alerts:** Enable
- **Dependabot security updates:** Enable
- **Secret scanning:** Enable (GitHub Pro feature, but recommended)

### Pages
- **Source:** Deploy from a branch
- **Branch:** main
- **Folder:** / (root)
- **Enforce HTTPS:** On

### Collaborators & Teams
- Add team members if applicable
- Default role: **Maintain** (not Admin)

---

## Step 3: Clone & Add Files Locally

```bash
git clone https://github.com/TABARC-Code/web-seo-master.git
cd web-seo-master

# Copy all files from the skill package
# SKILL.md, google-seo.md, youtube-seo.md, ux-design.md, cro.md
# README.md, LICENSE, CONTRIBUTING.md, package.json, .gitignore

git add .
git commit -m "Initial commit: web-seo-master v2.0.0"
git push origin main
```

---

## Step 4: GitHub Topics (for discoverability)

Add these tags to the repo:

- `claude-skill`
- `seo`
- `web-design`
- `youtube-seo`
- `conversion-rate-optimization`
- `ux-design`
- `landing-pages`
- `google-ranking`
- `ai`

(Settings → Options → Topics)

---

## Step 5: Enable Features

### Issues
- ✓ Enable (for bug reports, feature requests)
- Create issue templates (optional but helpful)

### Discussions
- ✓ Enable
- Category suggestions:
  - **General** — questions, how-tos
  - **Ideas** — feature requests
  - **Announcements** — updates, releases
  - **Show & Tell** — how users are using the skill

### Wiki
- ✗ Disable (README + docs are sufficient)

### Projects
- ✗ Disable initially (can add later if needed)

---

## Step 6: Create Release

1. Go to **Releases** → **Create a new release**
2. **Tag version:** v2.0.0
3. **Release title:** web-seo-master v2.0.0
4. **Description:** 
```
Kaizen edition: Human-written Claude AI skill for SEO, YouTube, UX, and conversion.

✓ Website audits (score across 6 dimensions)
✓ Landing page builds (production-ready HTML/CSS)
✓ Google SEO methodology (14 sections)
✓ YouTube creator framework (15 sections)
✓ UX/design system (15 sections)
✓ Conversion methodology (15 sections)

Research-backed. Human voice. Production-ready.

See README.md for installation and usage.
```
5. **Upload assets:** (optional) web-seo-master.zip
6. **Set as latest release:** ✓
7. **Create release**

---

## Step 7: Update README.md Badges (optional)

Add to top of README after h1:

```markdown
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/TABARC-Code/web-seo-master?sort=semver&style=flat-square)](https://github.com/TABARC-Code/web-seo-master/releases)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://github.com/TABARC-Code/web-seo-master/blob/main/LICENSE)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-blue.svg?style=flat-square)](https://claude.ai)
[![Research Backed](https://img.shields.io/badge/Research-Backed-orange.svg?style=flat-square)](https://github.com/TABARC-Code/web-seo-master)
```

---

## Step 8: Community Links (optional)

Add to bottom of README:

```markdown
## Community & Support

- **Issues:** [Report bugs or request features](https://github.com/TABARC-Code/web-seo-master/issues)
- **Discussions:** [Ask questions, share how you're using the skill](https://github.com/TABARC-Code/web-seo-master/discussions)
- **Contributing:** See [CONTRIBUTING.md](CONTRIBUTING.md)
```

---

## Step 9: Social Announcement

Post on:
- **Twitter/X** — See GITHUB_DESCRIPTIONS.md for template
- **LinkedIn** — See GITHUB_DESCRIPTIONS.md for template
- **Dev.to** (optional) — Cross-post README
- **Reddit** (optional) — r/webdev, r/SEO communities

---

## Maintenance Checklist

### Monthly
- [ ] Check GitHub Issues for bugs/questions
- [ ] Review Discussions for common questions
- [ ] Check Dependabot alerts

### Quarterly
- [ ] Review research for updates (Google algorithm, YouTube changes, etc.)
- [ ] Update version number if substantive changes
- [ ] Test skill with latest Claude version
- [ ] Update CHANGELOG (if using one)

### Annually
- [ ] Review all references for staleness
- [ ] Update "Latest update" date in documentation
- [ ] Plan v3.0 improvements (if applicable)

---

## Important Files & What They Do

| File | Purpose |
|---|---|
| **SKILL.md** | Core skill definition (how Claude behaves) |
| **google-seo.md** | Google ranking methodology |
| **youtube-seo.md** | YouTube creator framework |
| **ux-design.md** | UX/visual design system |
| **cro.md** | Conversion optimisation methodology |
| **README.md** | Main documentation & quick start |
| **LICENSE** | MIT License (open source) |
| **CONTRIBUTING.md** | How to contribute improvements |
| **package.json** | Metadata for npm/package managers |
| **.gitignore** | What git should ignore |

---

## Post-Launch Tasks

1. ✓ Send release announcement
2. ✓ Post on dev communities
3. ✓ Share with relevant creators (Backlinko, YouTube creators, etc.) if interested
4. ✓ Monitor Issues for initial feedback
5. ✓ Pin important/frequent issues
6. ✓ Create discussion topics to seed conversation

---

## Ongoing Community Management

### Responding to Issues
- Acknowledge within 24 hours
- Ask clarifying questions if needed
- Link to relevant docs/sections
- Close with "resolved" or "won't fix" + reason

### Answering Discussions
- Detailed, helpful responses
- Link to relevant sections of the skill
- Offer to expand if more detail needed

### Pull Requests (if accepting contributions)
- Review for accuracy of information
- Check writing voice matches existing docs
- Request changes politely if needed
- Merge with thanks

---

## Troubleshooting

**Issue: Files aren't showing in the repo**
- Verify `.gitignore` isn't blocking them
- Check file extensions (.md for markdown)
- Run `git status` to confirm files are tracked

**Issue: README formatting looks wrong**
- GitHub uses CommonMark markdown
- Test locally with `preview` if available
- Check for unclosed code blocks or lists

**Issue: Badge images aren't loading**
- Verify image URLs are correct
- Check if shields.io is accessible
- Try alternative badge service

---

## Reference Links

- GitHub Docs: https://docs.github.com
- Markdown Guide: https://guides.github.com/features/mastering-markdown
- Shields.io (badges): https://shields.io
- Keep a Changelog: https://keepachangelog.com
- Semantic Versioning: https://semver.org

---

**Setup completed by:** TABARC-Code  
**Setup date:** May 2026  
**Version:** 2.0.0
