[English](README.en.md) | 简体中文

# Personal Agent Skills

平时自己常用的一些好用的 AI Skills，整理到一起，方便随时用 [`npx skills`](https://skills.sh) 拉取复用。

## 安装方式

```bash
npx skills add martin-world/skills --list                              # 查看可用 Skills
npx skills add martin-world/skills --skill decision-interviewer        # 安装指定 Skill（加 -g 全局安装）
npx skills add martin-world/skills --all                               # 安装全部 Skills
npx skills update                                                      # 更新已安装 Skills
```

## 目录结构

```text
skills/
├── docs/                           # Skill 对话示例与效果展示（仅作演示，不随 npx skills 安装）
│   └── decision-interviewer.md
├── skills/
│   └── life-skills/                # 人生决策类
│       └── decision-interviewer/
│           └── SKILL.md
├── .gitignore
├── LICENSE
├── README.md
└── README.en.md
```

## Skills 列表

| Skill | 分类 | 说明 | 安装命令 |
| :--- | :--- | :--- | :--- |
| [`decision-interviewer`](skills/life-skills/decision-interviewer/SKILL.md) | `life-skills`（人生决策类） | 面对纠结决策时，通过单步带选项的追问剥离沉没成本、算清未来前景，直到信息闭环再给出唯一客观决断（[对话示例](docs/decision-interviewer.md)）。 | `npx skills add martin-world/skills --skill decision-interviewer` |
