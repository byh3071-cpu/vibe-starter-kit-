# 🚀 Vibe Starter Kit

> Start any vibe coding project in 15 minutes — a full-cycle kit from idea validation to deployment.

바이브코딩 프로젝트를 15분 안에 시작하는 풀사이클 스타터킷.
아이디어 검증부터 배포·자율운영까지, 단일 워크플로우로 끊김 없이 진행합니다.

## ⚡ Quick Start
# 1. Use this template (GitHub 우측 상단 초록 버튼)

# 2. Clone your new repo

git clone https://github.com/byh3071-cpu/vibe-starter-kit-.git

cd YOUR_PROJECT

# 3. Bootstrap with vibeinit (optional — alias setup)

# See docs/[vibeinit-setup.md](http://vibeinit-setup.md) for alias configuration

# 4. Install multi-agent preset

bunx oh-my-agent@latest

# → Select preset: Fullstack (recommended)

# 5. Start coding!

```

## 📦 What's Included

```

.

├── [CLAUDE.md](http://CLAUDE.md)              # AI context file (v2 template)

├── .cursorrules           # Cursor AI rules + design constraints

├── docs/

│   ├── adr/               # Architecture Decision Records

│   │   └── [ADR-000-template.md](http://ADR-000-template.md)

│   └── [vibeinit-setup.md](http://vibeinit-setup.md)  # vibeinit alias setup guide

├── [CREDITS.md](http://CREDITS.md)             # Open source attributions

├── LICENSE                # MIT License

└── [README.md](http://README.md)              # This file

```

## 🏗️ Phase Architecture

This kit follows a 6-phase workflow designed for solo vibe coders:

```

Phase 0  IDEA GATE     →  13-step validation checklist

Phase 1  STACK         →  Tech stack selection guide

Phase 1.5 DESIGN       →  AI design anti-pattern prevention

Phase 2  HARNESS       →  Triple harness setup (vibeinit + oh-my-agent + claude-md-mgmt)

Phase 3  BUILD         →  Sprint-based development

Phase 4-5 SHIP+OPERATE →  Deploy → Launch → Weekly review autopilot


## 🤖 Triple Harness System

| Layer | Tool | Role |
|-------|------|------|
| 📝 Record & Rules | `vibeinit` → CLAUDE.md + .cursorrules | Generate project context files |
| 🤖 Agent Team | `oh-my-agent` → .agents/ | Multi-agent preset (arch, fe, be, qa, pm...) |
| 🔧 Maintenance | `claude-md-management` plugin | Auto-revise + quality scoring |

Three layers, zero overlap. Each handles a different concern.

## 🎨 Design Guide (Phase 1.5)

The #1 reason AI-generated designs look "AI-ish" isn't the prompt — it's the lack of constraints.

**3-Step Design Decision (8 min):**
1. **Collect references** — 3~5 screenshots of "this vibe"
2. **Write constraints** — Color, font, spacing, anti-patterns in `.cursorrules`
3. **Evaluate & iterate** — Point out what's *wrong*, not what's right

## 📐 CLAUDE.md v2 Template Features

- YAML frontmatter with project metadata
- ADR status lifecycle tracking
- File naming conventions
- Notion MCP integration rules
- Auto-maintained by claude-md-management plugin

## 🔗 Related

- [oh-my-agent](https://github.com/nicepkg/oh-my-agent) — Portable multi-agent harness
- [claude-md-management](https://github.com/anthropics/claude-plugins-official) — CLAUDE.md auto-maintenance
- [Lazyweb MCP](https://github.com/aboul3ata/lazyweb-skill) — Design reference search

## 📝 License

MIT License. See [LICENSE](LICENSE) for details.
See [CREDITS.md](CREDITS.md) for third-party attributions.

## 🙋 Author

**Yohan Baek** ([@yohan-baek](https://github.com/yohan-baek))
- Building AI-powered solo business infrastructure
- Vibe coder & system architect
