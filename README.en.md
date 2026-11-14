English | [简体中文](README.md)

# Personal Agent Skills

A personal collection of handy AI Skills I actually use—kept in one place so they're easy to pull and reuse with [`npx skills`](https://skills.sh).

## Installation

```bash
npx skills add martin-world/skills --list                              # List available skills
npx skills add martin-world/skills --skill decision-interviewer        # Install a specific skill (add -g for global)
npx skills add martin-world/skills --all                               # Install all skills
npx skills update                                                      # Update installed skills
```

## Directory Structure

```text
skills/
├── docs/                           # Skill conversation examples (for viewing only, not installed via npx skills)
│   └── decision-interviewer.md
├── skills/
│   └── life-skills/                # Life & decision-making
│       └── decision-interviewer/
│           └── SKILL.md
├── .gitignore
├── LICENSE
├── README.md
└── README.en.md
```

## Skills

| Skill | Category | Description | Install |
| :--- | :--- | :--- | :--- |
| [`decision-interviewer`](skills/life-skills/decision-interviewer/SKILL.md) | `life-skills` (Life & Decision) | Conducts step-by-step multiple-choice interrogation to strip away sunk costs and evaluate future prospects before delivering a single objective decision ([Example](docs/decision-interviewer.md)). | `npx skills add martin-world/skills --skill decision-interviewer` |
