# AI Enabled Product Management
This repository documents how Product Managers can leverage Claude (Anthropic's AI assistant) across the full product lifecycle — from discovery and strategy to execution and post-launch analysis. Each use case includes the business context, prompt patterns, sample inputs/outputs, and where applicable, integration code using the Anthropic API.

Built and maintained by Praveen Narendran — a Product Manager with experience in IoT platforms, connected vehicle ecosystems, and embedded software. This repo reflects real workflows I've used or prototyped, not theoretical exercises.

Use Cases Covered

**1. Discovery & Research**
  
Customer Interview Synthesis — Cluster themes across dozens of transcripts and surface unmet needs
Competitive Teardown — Generate structured feature/positioning matrices from public sources
Market Sizing Drafts — Build TAM/SAM/SOM first drafts with assumptions called out
Jobs-to-be-Done Extraction — Convert raw user feedback into JTBD statements

**2. Strategy & Planning**

PRD Generation & Critique — Draft PRDs from a one-liner; or have Claude red-team your existing PRD
OKR Drafting — Translate strategic themes into measurable objectives and key results
Roadmap Prioritization — RICE / WSJF / MoSCoW scoring with reasoning
Strategy Memos — Amazon-style 6-pagers and narrative memos from bullet points

**3. Specification & Design**
  User Story Generation — Convert features into Gherkin-style acceptance criteria
  Edge Case Discovery — Systematically surface failure modes and non-happy paths
  API Spec Drafting — Generate OpenAPI specs from product requirements
  Wireframe Annotation — Describe and critique UI flows

**4. Stakeholder Communication**
  Exec Updates — Compress weekly progress into stakeholder-appropriate summaries
  Cross-functional Briefs — Tailor the same update for engineering, sales, and leadership
  Customer-facing Release Notes — Generate tone-appropriate changelogs
  Difficult Conversations — Draft escalations, scope-cut messages, and pushback responses

**5. Data & Analytics**
  SQL Query Drafting — Translate PM questions into queries for product analytics
  Funnel Hypothesis Generation — Read drop-off data and propose explanations
  A/B Test Readouts — Summarize experiment results with statistical caveats
  Survey Analysis — Classify open-ended responses at scale

**6. Go-to-Market**
  Positioning & Messaging — Generate value prop variants by persona
  Sales Enablement Snippets — Battlecards, objection handling, demo scripts
  Launch Checklists — Tailored to product type and risk profile

**7. Post-Launch & Ops**
  Support Ticket Triage — Classify and route incoming feedback
  Churn Reason Clustering — Surface themes from cancellation data
  Incident Postmortems — Structure blameless retrospectives from raw notes

🛠️ How to Use This Repo
Each folder contains:
  README.md — the use case, when to apply it, and limitations
  prompt.md — the prompt template (with variables marked)
  example/ — sample input and output
  code/ (optional) — Python or JavaScript snippets using the Anthropic API for automation

⚙️ Tech Stack
  Claude API (claude-opus-4-7, claude-sonnet-4-6) via Anthropic SDK
  Python / Node.js examples
  Markdown-based prompt library
