# GitHub Profile README Redesign Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Rewrite the GitHub profile README with a fusion-balanced design: clean professional layout with Miku-green accents, accurate tech stack badges, and dynamic elements.

**Architecture:** Single markdown file (`README.md`) rendered by GitHub. Uses external services (shields.io, github-readme-typing-svg, github-readme-stats, github-readme-activity-graph) for dynamic visuals — no local build step required.

**Tech Stack:** Markdown, shields.io badges, GitHub-flavored markdown tables/dividers

---

## File Structure

| File | Action | Purpose |
|---|---|---|
| `README.md` | Rewrite | GitHub profile README — all content |

---

### Task 1: Write Header + About Me + Tech Stack

**Files:**
- Rewrite: `README.md`

- [ ] **Step 1: Write the header and About Me section**

Replace the entire `README.md` with the following content (first half):

```markdown
# Hi, I'm 玖驻zsxy 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=39C5BB&width=435&lines=Designer+%2F+Developer+%2F+Otaku;Building+warm+products+with+code)](https://git.io/typing-svg)

---

## 🌍 About Me

Hi, I'm **玖驻zsxy** (**ZSylph**), a passionate creator at the intersection of **design, frontend engineering, and creative coding**.

- 🌱 Currently exploring Next.js ecosystem, edge computing, and visual interaction design.
- 💡 Love building products that balance engineering rigor with expressive visuals.
- 🎨 Enjoy studying open-source projects, writing tech blogs, and collecting design inspiration.
- 🤝 Always open to collaboration and building something interesting together.

<p align="left">
  <a href="https://github.com/ZSylph"><img src="https://img.shields.io/badge/GitHub-ZSylph-181717?logo=github" /></a>
  <a href="https://space.bilibili.com/277755137"><img src="https://img.shields.io/badge/Bilibili-277755137-00A1D6?logo=bilibili" /></a>
  <a href="https://twitter.com/ZSylph"><img src="https://img.shields.io/badge/Twitter-@ZSylph-1DA1F2?logo=twitter" /></a>
</p>

---

## 🔍 Tech Stack

Technologies I actually use and work with:

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?logo=next.js)
![React](https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?logo=tailwindcss)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?logo=shadcnui)

**Backend & Data**

![Prisma](https://img.shields.io/badge/Prisma_7.8-2D3748?logo=prisma)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare_D1-F38020?logo=cloudflare)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod)

**DevOps & Edge**

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare)
![Wrangler](https://img.shields.io/badge/Wrangler-F38020?logo=cloudflare)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)
```

- [ ] **Step 2: Commit**

```bash
git add README.md
git commit -m "feat: redesign profile README header, about me, and tech stack"
```

---

### Task 2: Write Goals + GitHub Stats + Activity Graph

**Files:**
- Modify: `README.md` (append to end)

- [ ] **Step 1: Append remaining sections**

Append the following to `README.md`:

```markdown
---

## 📃 Goals & Interests

- 🔍 Exploring the boundary between **frontend engineering** and **creative coding**.
- 🧠 Deepening knowledge in **edge computing**, **modern web architecture**, and **distributed systems**.
- 🚀 Making more **open-source contributions** and sharing learnings through writing.
- ✨ Believing good tools should be transparent — letting people focus on creating, not complexity.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ZSylph&theme=transparent&hide_border=true&stroke=39C5BB&ring=39C5BB&fire=39C5BB&currStreakNum=39C5BB" height="165" />
  <img src="https://github-readme-stats.vercel.app/api?username=ZSylph&show_icons=true&theme=transparent&hide_border=true&icon_color=39C5BB&title_color=39C5BB" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZSylph&layout=compact&theme=transparent&hide_border=true&title_color=39C5BB" height="165" />
</p>

---

## 🏔️ GitHub Activity

[![ZSylph's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=ZSylph&bg_color=ffffff&color=708090&line=39C5BB&point=39C5BB&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
```

- [ ] **Step 2: Commit**

```bash
git add README.md
git commit -m "feat: add goals, github stats, and activity graph"
```

---

### Task 3: Push to Remote

- [ ] **Step 1: Push**

```bash
git push origin main
```

Expected: branch `main` pushed to `https://github.com/ZSylph/ZSylph.git`

---

## Self-Review Checklist

- [x] Spec coverage: all 6 sections (header, about, tech stack, goals, stats, activity) mapped to tasks
- [x] No placeholders — all content is concrete markdown
- [x] Tech stack is accurate and limited to confirmed technologies from `zsxy` project
