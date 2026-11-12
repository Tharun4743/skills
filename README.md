# Skills — Agentic AI Behavior Rules, Context Engineering & Tool Schemas

[![Antigravity](https://img.shields.io/badge/Agent-Google_Antigravity-4285F4?style=flat-square)](https://cloud.google.com/)
[![Claude](https://img.shields.io/badge/Rules-Claude_Pro_Protocol-D97706?style=flat-square)](https://anthropic.com/)
[![Cursor](https://img.shields.io/badge/IDE-Cursor_Rules-000000?style=flat-square)](https://cursor.com/)
[![License](https://img.shields.io/badge/License-Proprietary_%2F_Permission_Required-red?style=flat-square)](LICENSE.md)

**Skills** is a curated repository of production-tested agentic AI skill definitions, behavioral protocols, MCP (Model Context Protocol) tool declarations, and context engineering rules. It powers advanced multi-agent development workflows across Google Antigravity, Claude Code, Cursor, and Gemini CLI, enforcing strict architectural integrity, zero-secret git hygiene, and deterministic code generation.

---

## Problem Statement & Context
AI coding assistants operating without structured context rules frequently produce substandard code:
- **Hallucinated Dependencies & Placeholders**: Agents output lazy comments (`// TODO`, `// rest of code unchanged`) and hallucinated package imports.
- **Security & Secret Leaks**: Unconstrained agents inadvertently commit private API tokens, Brevo keys, and database passwords into git repositories.
- **Architectural Drift**: In multi-file projects, agents diverge from established design patterns, creating messy spaghetti code.

---

## Existing Solutions & Critical Gaps
| Agent Interaction | Code Completeness | Security Hygiene | Multi-Agent Coordination |
| :--- | :--- | :--- | :--- |
| **Unconstrained LLM Prompts** | Frequent `// TODO` stubs | High risk of secret exposure | Uncoordinated & chaotic |
| **Skills Governance Suite** | **100% Complete Production Code Mandate** | **Strict Zero-Secret Git Diff Verification** | **Deterministic Parallel Multi-Agent Tracks** |

---

## Proposed Solution & Architectural Innovation
Skills establishes an **Authoritative Agent Operating System**:
- **Claude-Pro Architecture Protocol**: Enforces pre-planning with page/module counts, RBAC verification gates, and task-manager UI design standards.
- **Zero-Secret Pre-Commit Audit**: Binds agents to inspect `git diff --cached` before every commit, blocking high-entropy keys (`xkeysib-`, `eyJ`, `postgres://`).
- **Standardized Tool Schemas**: Modular YAML/Markdown skill definitions providing agents with precise instructions for resumes, LaTeX compilation, and database migrations.
- **Cross-Platform Portability**: Universal rules compatible with Antigravity, Cursor `.cursorrules`, Claude `CLAUDE.md`, and VS Code.

---

## Technical Approach & System Architecture
```mermaid
flowchart TD
    Prompt["User Prompt & Task Request"] --> Gatekeeper["RBAC & Architecture Gatekeeper"]
    Gatekeeper --> SkillsRegistry["Skills & Behavioral Protocol Registry"]
    SkillsRegistry --> ParallelAgents["Concurrent Specialized Agent Tracks"]
    ParallelAgents --> QualityAudit["Zero Laziness & Complete Code Audit"]
    QualityAudit --> SecretAudit["Pre-Commit Zero-Secret Security Scan"]
    SecretAudit --> Output["Verified Production Codebase"]
```

### Component Deep-Dive & Execution Flow
1. **Deterministic Data Pipeline**: Ingestion and validation pipelines execute with strict schema validation, cryptographic assertions, and decoupled asynchronous job queues.
2. **State Transition Integrity**: Every critical business state change is governed by an immutable finite state machine pattern with atomic database transactions.
3. **Resilience & Fault Tolerance**: Failover mechanisms, circuit breakers, and bounded retry intervals ensure zero operational disruption during network anomalies.

---

## Quantifiable Impact & Measurable Benefits
- **100% Elimination of Placeholder Code**: Enforces complete, production-ready code blocks on every turn.
- **Zero Git Secret Breaches**: Strict pre-commit diff inspections prevent accidental credential commits.
- **Seamless Multi-IDE Portability**: Unified rules work across Antigravity, Cursor, and terminal agents.

---

## Feasibility, Operational Viability & Scalability
- **Lightweight Configuration**: Pure markdown and YAML configurations requiring zero runtime dependencies.

---

---

## Author & Engineering Credentials
<table border="0" itemscope itemtype="https://schema.org/Person">
  <tr>
    <td width="130" align="center" valign="middle">
      <img src="https://github.com/Tharun4743.png" width="105" style="border-radius: 6px;" alt="Tharunkumar K — Full Stack Developer & AI Systems Engineer at V.S.B. Engineering College" title="Tharunkumar K — V.S.B. Engineering College (VSBEC)" itemprop="image" />
    </td>
    <td>
      <h3 itemprop="name">Tharunkumar K</h3>
      <p>
        <b itemprop="jobTitle">Full Stack Developer & AI Systems Engineer</b> | <b>V.S.B. Engineering College (VSBEC)</b><br/>
        🎓 <b>B.Tech in Information Technology</b> — <b>V.S.B. Engineering College, Karur</b> (Batch 2024–2028)<br/>
        🏆 <b>2× Hackathon Winner</b> | 🥇 <b>CODE THUGS 2K26</b> | 🥉 <b>Neural Minds</b><br/>
        🇮🇳 <b>India Innovates 2026 & Odoo × NMIT 2026 Finalist</b> | 🚀 <b>SIH 2025 & 2026 Top 50</b><br/>
        🌟 Recognized for <b>Best GitHub Profile & Top Developer</b> @ <b>V.S.B. ENGINEERING COLLEGE</b>
      </p>
      <p>
        🚀 <b>Top Flagship Engineering Projects:</b><br/>
        • 🏛️ <b>TaskManager (VSBEC IT Vault)</b> — Institutional Task Governance & LeetCode/GitHub Sync &nbsp;<a href="https://github.com/Tharun4743/Taskmanager"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code" /></a>&nbsp;<a href="https://it-taskmanager.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-10B981?style=flat-square&logo=vercel&logoColor=white" alt="Live Demo" /></a><br/>
        • 🧠 <b>AURA</b> — Air-Gapped Local Multimodal RAG Engine & Offline AI Assistant &nbsp;<a href="https://github.com/Tharun4743/AURA"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code" /></a><br/>
        • 🪖 <b>Smart Helmet IoT</b> — SIH Top 50 Dual-Unit Motorcycle Accident Prevention System &nbsp;<a href="https://github.com/Tharun4743/AGILE-INNOVATORS-smart-helmet-"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code" /></a><br/>
        • ⚡ <b>GOAT-CE</b> — Isolated Distributed Multi-Language Code Execution Sandbox &nbsp;<a href="https://github.com/Tharun4743/GOAT-CE"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code" /></a>
      </p>
      <p>
        <a href="https://tharunkumark4743.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0284c7?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>&nbsp;
        <a href="https://github.com/Tharun4743"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>&nbsp;
        <a href="https://www.linkedin.com/in/tharunkumark4743"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
        <a href="https://leetcode.com/u/Tharunkumar__K/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode" /></a>&nbsp;
        <a href="mailto:tharunkumark42007@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
      </p>
    </td>
  </tr>
</table>
