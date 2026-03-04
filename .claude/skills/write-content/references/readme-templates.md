# README Templates and Components

## Project README structure

### Header section

Center-aligned logo/banner + title + tagline:

```markdown
<div align="center">
  <img src="assets/logo.png" alt="Project Name" width="200" />
  <h1>Project Name</h1>
  <p>One-line description of what it does in plain language.</p>
</div>
```

### Badges

4-6 max, one row, immediately below title:

```markdown
![Build](https://img.shields.io/github/actions/workflow/status/USER/REPO/ci.yml?branch=main)
![Version](https://img.shields.io/npm/v/PACKAGE)
![License](https://img.shields.io/github/license/USER/REPO)
![Downloads](https://img.shields.io/npm/dm/PACKAGE)
```

#### Shields.io syntax

Basic: `https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>`

With logo: `https://img.shields.io/badge/<TEXT>-<HEX>?style=for-the-badge&logo=<LOGO>&logoColor=white`

Styles: flat (default), flat-square, plastic, social, for-the-badge

Colors: brightgreen, green, yellowgreen, yellow, orange, red, blue, lightgrey

#### Common tech badges

```markdown
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
```

#### Social badges

```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/USERNAME)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/USERNAME)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/USERNAME)
```

Logo names come from simpleicons.org.

### Quick Start section

Get the user running in under 60 seconds. Copy-paste ready:

```markdown
## Quick start

\```bash
npm install project-name
\```

\```typescript
import { Thing } from "project-name";

const result = Thing.doSomething("input");
console.log(result);
\```
```

### Features section

Bullet list, specific, no buzzwords:

```markdown
## Features

- Parse 10K documents per second on a single core
- Zero dependencies, 14KB gzipped
- TypeScript types included
- Works in Node.js 18+ and all modern browsers
- Streaming API for large files
```

### Roadmap section

Checkbox format:

```markdown
## Roadmap

- [x] Core parsing engine
- [x] TypeScript support
- [ ] Streaming API
- [ ] Browser WASM build
- [ ] Plugin system
```

---

## Profile README

### GitHub stats widgets

Stats card:
```markdown
[![Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)
```

Top languages:
```markdown
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)
```

Streak stats:
```markdown
[![GitHub Streak](https://streak-stats.demolab.com/?user=USERNAME&theme=dark)](https://git.io/streak-stats)
```

Profile trophy:
```markdown
[![trophy](https://github-profile-trophy.vercel.app/?username=USERNAME&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)
```

Activity graph:
```markdown
[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=USERNAME&theme=react-dark)](https://github.com/ashutosh00710/github-readme-activity-graph)
```

Typing SVG:
```markdown
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7F7F7&width=435&lines=Full+Stack+Developer;Open+Source+Contributor)](https://git.io/typing-svg)
```

Available themes: default, dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

### Profile README template

```markdown
# Hi, I'm [Name]

## About me
- Building [current project]
- Exploring [current interest]
- Ask me about [expertise area]
- Reach me at [contact]

## Tech stack
[badges here]

## Stats
[widgets here]

## Connect
[social badges here]
```

---

## README writing rules

1. Write in a human voice. Not corporate, not sterile.
2. The first paragraph should tell someone what the project does and why they'd use it, in plain language.
3. Quick start comes before detailed installation. People want to try it first.
4. Code examples should be real, runnable code. Not pseudo-code.
5. Don't oversell. Let the features speak. "Parse 10K docs/sec" is better than "blazing fast performance."
6. Sentence case for headings, not Title Case.
7. Keep it scannable. Someone should get the gist in 30 seconds.
8. Include a GIF or screenshot if the project has a visual component.
