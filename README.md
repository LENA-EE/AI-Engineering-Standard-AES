<p align="right">
🌍 Languages:
<a href="./README.md">English</a> |
<a href="./README.ru.md">Русский</a>
</p>

AES Standard: v1.0  
Execution Contract: CLAUDE.md  
Compliance: L3 Ready

# 🧭 AI Engineering Standard (AES)

> **A standard for building software with AI agents.**

**AI Engineering Standard (AES)** is a structured methodology for human–AI collaboration in software development.

AES transforms AI from a code generator into a **predictable engineering partner**.

---

<p align="center">
<strong>From prompts → to engineering.</strong>
</p>

---

## 📜 Required Contracts

AES requires two files:

- `PROJECT_CONSTITUTION.md` — defines WHAT is built
- `CLAUDE.md` — defines HOW AI builds it

Both contracts are required for AES compliance.

## 🌍 Why AI Development Needs a Standard

Modern AI-assisted development often leads to:

- architectural chaos
- context loss between sessions
- unpredictable regressions
- inconsistent implementations
- continuous rewrites

AES introduces **execution contracts, engineering rules, and operational boundaries**, making AI development controlled and scalable.

---

## 🧠 Core Principle

> AI executes decisions — it does not invent them.

Clear separation of responsibilities:

| Role     | Responsibility                           |
| -------- | ---------------------------------------- |
| Human    | Product vision, architecture, priorities |
| AI Agent | Analysis, implementation, validation     |

---

## 🧩 AES Specification

AES consists of **two mandatory contracts**.

---

### 1️⃣ PROJECT_CONSTITUTION.md — Product Contract

Defines:

- project scope & non-goals
- architecture decisions
- technology stack
- domain model
- security boundaries
- deployment strategy
- definition of done

Answers:

➡️ **What are we building?**

---

### 2️⃣ CLAUDE.md — Execution Contract

Defines:

- AI agent role
- development workflow
- engineering constraints
- forbidden practices
- development priorities
- command system

Answers:

➡️ **How must AI build it?**

---

## ⚙️ Standard Agent Commands

| Command         | Behavior                     |
| --------------- | ---------------------------- |
| `/constitution` | Create project constitution  |
| `/explore`      | Analyze repository           |
| `/plan`         | Generate implementation plan |
| `/status`       | Show project status          |
| `/fix`          | Detect & fix errors          |
| `/review`       | Perform code review          |
| `/deploy`       | Prepare deployment           |

AI **never starts implementation without an approved plan**.

---

## 🔄 AES Development Lifecycle

### Phase 1 — Alignment

- project analysis
- constitution creation
- context validation

### Phase 2 — Planning

- step-by-step execution plan
- risk identification
- human approval

### Phase 3 — Execution

- iterative implementation
- architectural compliance
- continuous validation

### Phase 4 — Delivery

- stability verification
- debug cleanup
- production readiness

---

## 🧱 Engineering Requirements

### Code Quality

- strict typing
- single responsibility per file
- ≤150 lines per module
- meaningful naming

### Architecture

- layered separation
- dependency isolation
- configuration via environment variables

### Reliability

- guarded external calls
- graceful degradation
- structured logging
- failure recovery

### UX Baseline

- loading state
- empty state
- error state
- confirmation for destructive actions

---

## ⛔ AES Violations

❌ Type suppression (any, ts-ignore, type: ignore)
❌ Hardcoded configuration
❌ Debug logs in production
❌ Dead or commented code
❌ Empty catch blocks
❌ Logic duplication
❌ TODO without description

---

## 🎯 Development Priorities

Works

Reliable

Typed

Maintainable

Clean

Optimized

---

## ✅ AES Compliance Levels

| Level  | Description                |
| ------ | -------------------------- |
| AES-L1 | Constitution defined       |
| AES-L2 | Implementation plan exists |
| AES-L3 | Architecture enforced      |
| AES-L4 | Production Ready           |

Projects may declare:

AES: L3 Compliant

---

## 🚀 Quick Start

```bash
cp PROJECT_CONSTITUTION.template.md your-project/PROJECT_CONSTITUTION.md
cp CLAUDE.md your-project/
```

1. Define project constitution
2. Establish execution context
3. Start your AI agent

---

## 🧰 Compatibility

Works with:
- Claude Code
- Cursor
- GitHub Copilot
- Local LLM agents
- Enterprise AI IDEs

Suitable for:
- frontend
- backend
- mobile
- ML systems
- DevOps

---

## 🌐 Where AES Fits

- AI-native startups
- engineering teams
- production systems
- solo developers
- research projects
- pet projects

---

## 🧭 Philosophy

> Humans design systems. AI executes them.

AES formalizes this boundary.

---

## 📄 License

MIT — use, adapt, extend.

---

<p align="center">
<strong>⭐ If AES improves your workflow — consider starring the repository.</strong>
</p>
