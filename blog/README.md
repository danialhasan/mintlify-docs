# Squad Blog Posts

This directory contains 17 blog post scaffolds transformed from the original markdown files in `/docs/blog-posts/`.

## Status: SCAFFOLDS

These are high-quality scaffolds ready for enhancement. Each post includes:
- ✅ Mintlify frontmatter with title, description, and icon
- ✅ AI-generated hero image (16:9, 2K resolution via Gemini 3 Pro)
- ✅ Core narrative structure from original scaffolds
- ✅ Related reading links
- ⏳ Placeholders for production metrics and case studies

## Featured Posts (Ready for Enhancement)

### 1. Meta AI Engineer Validation
**File:** `meta-ai-engineer-validation.mdx`
**Hero Image:** `/images/blog/meta-ai-engineer-validation.jpg`
**Status:** Detailed scaffold with full narrative
**Description:** Conversation with Kunal Malkan from Meta MSL validating Squad's receipt system architecture

### 2. How We Review 50+ Agent PRs
**File:** `how-we-review-agent-prs.mdx`
**Hero Image:** `/images/blog/how-we-review-agent-prs.jpg`
**Status:** Detailed scaffold with workflow outline
**Description:** Moving from 47-minute reviews to 4.2 minutes with 87% auto-merge rate

### 3. Temporal Coupling: Achilles' Heel
**File:** `temporal-coupling-achilles-heel.mdx`
**Hero Image:** `/images/blog/temporal-coupling-achilles-heel.jpg`
**Status:** Detailed scaffold with Parallel Monitor integration
**Description:** Solving the 37% failure rate from temporal coupling using Parallel's webhook system

### 4. Context Engineering vs Prompt Engineering
**File:** `context-engineering-not-prompt-engineering.mdx`
**Hero Image:** `/images/blog/context-engineering-not-prompt-engineering.jpg`
**Status:** Detailed scaffold with architecture diagrams
**Description:** Google ADK, Stanford ACE, and Squad independently converged on the same context architecture

## All Blog Posts

| # | Title | Slug | Status |
|---|-------|------|--------|
| 1 | Meta AI Engineer Validation | `meta-ai-engineer-validation` | Detailed |
| 2 | How We Review 50+ Agent PRs | `how-we-review-agent-prs` | Detailed |
| 3 | Receipts-First Governance | `receipts-first-governance` | Scaffold |
| 4 | Long-Running Agents | `long-running-agents` | Scaffold |
| 5 | Agent Orchestration Workloads | `agent-orchestration-workloads` | Scaffold |
| 6 | Agentic Distributed Systems | `agentic-distributed-systems` | Scaffold |
| 7 | Context Management Multi-Agent | `context-management-multi-agent` | Scaffold |
| 8 | Security, Observability, Governance | `security-observability-governance` | Scaffold |
| 9 | Reinforcement Learning Multi-Agent | `reinforcement-learning-multi-agent` | Scaffold |
| 10 | Temporal Coupling: Achilles' Heel | `temporal-coupling-achilles-heel` | Detailed |
| 11 | AI Tool Bake-Off | `bakeoff-claude-code-squad-cursor` | Scaffold |
| 12 | Context Engineering | `context-engineering-not-prompt-engineering` | Detailed |
| 13 | Code Review Liquidity Crisis | `code-review-liquidity-crisis` | Scaffold |
| 14 | Dogfooding Squad | `dogfooding-squad-with-primitive-squad` | Scaffold |
| 15 | Six Limitations Solved | `six-limitations-claude-code-squad-solves` | Scaffold |
| 16 | DAG Parallelization Problem | `dag-parallelization-problem` | Scaffold |
| 17 | Closing the Loop with Artifacts | `closing-the-loop-artifacts` | Scaffold |

## Hero Images

All 17 images generated using Gemini 3 Pro (Nano Banana Pro):
- **Model:** `gemini-3-pro-image-preview`
- **Aspect Ratio:** 16:9 (blog hero format)
- **Resolution:** 2K
- **Style:** Modern tech, futuristic, professional startup aesthetic
- **Location:** `/images/blog/*.jpg`

## Navigation Structure (docs.json)

Blog tab added with 4 groups:

### Featured
- Meta AI Engineer Validation
- How We Review 50+ Agent PRs
- Temporal Coupling: Achilles' Heel
- Context Engineering vs Prompt Engineering

### Architecture & Systems
- Receipts-First Governance
- Long-Running Agents
- Agent Orchestration Workloads
- Agentic Distributed Systems
- Context Management Multi-Agent
- DAG Parallelization Problem

### Governance & Operations
- Security, Observability, Governance
- Code Review Liquidity Crisis
- Closing the Loop with Artifacts

### Comparisons & Insights
- AI Tool Bake-Off: Claude Code vs Squad vs Cursor
- Six Limitations of Claude Code That Squad Solves
- Dogfooding Squad with Primitive Squad
- Reinforcement Learning in Multi-Agent Coordination

## Next Steps for Enhancement

### High Priority (Production Data Needed)
1. **Meta AI Engineer Validation** - Get Kunal's permission, exact quotes, ARE paper links
2. **How We Review Agent PRs** - Real metrics from production (currently estimated)
3. **Temporal Coupling** - Complete Parallel Monitor integration, gather before/after stats

### Medium Priority (Technical Deep Dives)
4. **Context Engineering** - Add complete processor code examples
5. **Receipts-First Governance** - Full receipt schema specification
6. **AI Tool Bake-Off** - Run actual benchmarks (5 tasks × 3 tools)

### Lower Priority (Can Publish as Scaffolds)
7-17. Remaining posts are solid scaffolds - can publish with "Coming Soon" status

## Publishing Checklist

Before publishing each post:
- [ ] Production metrics verified
- [ ] Code examples tested
- [ ] Screenshots/diagrams added
- [ ] External permissions obtained (e.g., Kunal for Meta post)
- [ ] Related reading links verified
- [ ] SEO metadata optimized
- [ ] Legal review for any claims

## File Structure

```
mintlify-docs/
├── blog/
│   ├── README.md (this file)
│   ├── meta-ai-engineer-validation.mdx
│   ├── how-we-review-agent-prs.mdx
│   ├── temporal-coupling-achilles-heel.mdx
│   ├── context-engineering-not-prompt-engineering.mdx
│   ├── receipts-first-governance.mdx
│   └── ... (13 more MDX files)
└── images/
    └── blog/
        ├── meta-ai-engineer-validation.jpg
        ├── how-we-review-agent-prs.jpg
        └── ... (15 more JPG files)
```

## Image URLs

All images stored at Composio R2 CDN and downloaded locally:
- Format: `https://pub-b70cb36a6853407fa468c5d6dec16633.r2.dev/184526/dynamic-module-load/GENERATE_IMAGE/response/{hash}`
- Local: `/images/blog/{slug}.jpg`

---

**Generated:** 2025-12-20
**Total Posts:** 17 MDX files
**Total Images:** 17 hero images (2K, 16:9)
**Navigation:** Added to docs.json
**Status:** Ready for content enhancement and publication
