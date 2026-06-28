# Awesome Skills & Plugins for Students

A curated list of Claude Code, Cursor, and Copilot skills and plugins built for students: IB, IGCSE, college-bound, and anyone studying with an AI coding agent at their side.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

This is a curation list, not a code library. Every entry below links out to a skill or plugin maintained in its own repo. Add yours by opening a PR, see [CONTRIBUTING.md](CONTRIBUTING.md).

Maintained by [StudentSuite](https://github.com/StudentSuite).

## Table of Contents

- [IB & IGCSE Coursework](#ib--igcse-coursework)
- [Study & Productivity](#study--productivity)
- [Coding & CS Education](#coding--cs-education)
- [STEM Subjects](#stem-subjects)
- [Writing & Humanities](#writing--humanities)
- [College Applications & Career](#college-applications--career)
- [Plugins](#plugins)
- [Security Notice](#security-notice)
- [Skill & Plugin Paths for Other AI Coding Assistants](#skill--plugin-paths-for-other-ai-coding-assistants)
- [Quality Standards](#quality-standards)
- [Contributing](#contributing)
- [License](#license)

## Skills

### IB & IGCSE Coursework

IA, EE, and TOK helpers, citation formatting, rubric-aligned essay feedback.

<details open>
<summary>Show skills</summary>

- **[saulmcphd/apa-style](https://github.com/saulmcphd/apa-style)** - Proofreads papers against APA 7th edition rules with inline corrections.

Know an IB- or IGCSE-specific skill? Be the first to add one, see [Contributing](#contributing).

</details>

### Study & Productivity

Spaced repetition, time and task management, focus.

<details open>
<summary>Show skills</summary>

- **[jakedahn/pomodoro](https://github.com/jakedahn/pomodoro)** - Pomodoro timer skill that tracks and learns from your focus sessions.
- **[hluaguo/learn-faster-kit](https://github.com/hluaguo/learn-faster-kit)** - AI learning coach with spaced repetition, syllabi, and progress tracking.

</details>

### Coding & CS Education

Algorithm and debugging explainers, learn-to-code starters; distinct from professional dev tooling.

<details open>
<summary>Show skills</summary>

- **[zarazhangrui/codebase-to-course](https://github.com/zarazhangrui/codebase-to-course)** - Turns any codebase into an interactive HTML course for beginners.
- **[kirilxd/claude-tutor](https://github.com/kirilxd/claude-tutor)** - Personal tutor with adaptive quizzes and SM-2 spaced repetition.
- **[AnayDhawan/oss-launch](https://github.com/AnayDhawan/oss-launch)** - Scans a repo and generates a complete open source file set.

</details>

### STEM Subjects

Math, physics, and chemistry problem-solving helpers.

<details open>
<summary>Show skills</summary>

- **[googlarz/math-skill](https://github.com/googlarz/math-skill)** - Solves math problems step by step with built-in verification.

Know a physics or chemistry skill worth adding? Be the first, see [Contributing](#contributing).

</details>

### Writing & Humanities

Essay structuring, literature analysis, language learning.

<details open>
<summary>Show skills</summary>

- **[Master-cai/Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills)** - Skill package for planning and writing research papers.

Know a literature analysis or language-learning skill? Be the first to add one, see [Contributing](#contributing).

</details>

### College Applications & Career

Personal statements, resume, interview prep.

<details open>
<summary>Show skills</summary>

- **[Paramchoudhary/ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills)** - Resume optimization, ATS scoring, and interview prep skills.
- **[varunr89/resume-tailoring-skill](https://github.com/varunr89/resume-tailoring-skill)** - AI-powered resume tailoring for specific job descriptions.

</details>

## Plugins

Full Claude Code, Cursor, or Copilot plugins for students: bundles of commands, agents, hooks, or MCP servers, not a single skill file.

<details open>
<summary>Show plugins</summary>

- **[olegvg/resume-tailor-plugin](https://github.com/olegvg/resume-tailor-plugin)** - Claude Code plugin that tailors your resume to a job post.
- **[JeanDiable/academic-research-plugin](https://github.com/JeanDiable/academic-research-plugin)** - Plugin for literature surveys, paper reviews, and citation management.

</details>

## Security Notice

This list curates links, it does not vet or host the code behind them. Before installing any skill or plugin from this list:

- Read the source. A skill or plugin runs with the same permissions as your coding agent.
- Check the author and repo activity. Prefer maintained repos with real usage over brand-new, unreviewed ones.
- Never paste credentials, exam content, or personal data into a skill you have not read.

If you find a listed entry that looks unsafe or abandoned, open an issue or PR removing it.

## Skill & Plugin Paths for Other AI Coding Assistants

| Tool | Project path | Global path | Docs |
|---|---|---|---|
| Claude Code | `.claude/skills/` | `~/.claude/skills/` | [Agent Skills docs](https://code.claude.com/docs/en/skills) |
| Cursor | `.cursor/rules/` | `~/.cursor/rules/` | [Cursor rules docs](https://docs.cursor.com/context/rules) |
| GitHub Copilot | `.github/copilot-instructions.md` | N/A | [Copilot custom instructions](https://docs.github.com/en/copilot/customizing-copilot) |
| Gemini CLI | `.gemini/` | `~/.gemini/` | [Gemini CLI docs](https://github.com/google-gemini/gemini-cli) |

Claude Code plugins (full bundles, not single skills) install via a marketplace `.claude-plugin/marketplace.json`, see the [Claude Code plugin docs](https://code.claude.com/docs/en/plugins).

## Quality Standards

An entry should meet all of the following before being added:

- **Public repo.** Anyone can clone it without requesting access.
- **Documented.** Has a README or SKILL.md explaining what it does and how to install it.
- **Works.** Tested against at least one of the tools in the path table above.
- **Real, not a stub.** Built for actual use, not a placeholder created just to pad this list.
- **Short description.** One line, plain language, no marketing copy.

## Contributing

PRs adding a skill or plugin are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and PR checklist.

## License

This repository is released under the [MIT License](LICENSE). The license covers this list itself: the README, CONTRIBUTING.md, and curation structure. It does not cover the skills and plugins linked from it, each of those is owned and licensed by its own author in its own repo.
