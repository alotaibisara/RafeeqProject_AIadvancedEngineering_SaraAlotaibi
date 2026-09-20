# RafeeqProject_AIadvancedEngineering_SaraAlotaibi
# 🚚 Rafeeq Mini — Agentic AI Systems Engineering

A practical and cumulative project to build, secure, and monitor an intelligent bilingual (Arabic/English) delivery support agent, designed as a comprehensive progressive notebook split across 3 training days.

# 📌 Project Concept

The Rafeeq Mini project simulates a real-world Agentic AI Systems environment in the domain of delivery services and customer support.

The core idea relies on a step-by-step progression from a basic, low-privilege agent to a multi-skilled agent, and finally into a Multi-Agent System that features:

Tools & Memory Integration: Querying orders, updating addresses, and retrieving policy guidelines.

Safety & Governance Boundaries: Isolating customer identity and sensitive approvals from the LLM context to prevent prompt injection attacks.

Observability & Production Packaging: Execution logging, metric tracking, and exporting machine-readable proofs (JSON Evidence).

⚠️ Safety Boundary: This project is a fully synthetic training simulation and does not connect to any real-world delivery, payment, or customer systems.

# 🎓 Training Program

This hands-on laboratory was presented by Instructor: Meaad Al-Marri and sponsored by SDAIA Academy.

The curriculum consists of 14 Guided Exercises distributed over 3 training days:

    [Day 1: Architecture & Tools]
                │
                ▼
    [Day 2: Security, Observability & Governance]
                │
                ▼
    [Day 3: Multi-Agent Systems & Production Packaging]


🗓️ Training Schedule Overview:

 Day 1 — Architecture → Tools → Bounded Single Agent:

Understanding core AI agent architectures.

Building and integrating custom tools with the agent.

Creating a single, scope-bound agent with enforced guardrails.

 Day 2 — Security, Observability & Human Approval:

Enforcing security guardrails and the Principle of Least Privilege.

Designing an observability and audit logging framework.

Incorporating Human-in-the-Loop workflows for sensitive actions.

 Day 3 — Multi-Agent System, Packaging & Deployment:

Evolving the project into multi-agent workflows.

Architecting agent-to-agent handoffs and transition logic.

Verifying evidence artifacts and packaging the project for deployment.

# 💻 Setup & Environment

This lab is engineered to run in a 100% deterministic and offline mode, allowing trainees to complete all modules without requiring API keys or active internet access.

Environment Key Features:

LLM Mode: Powered by a built-in synthetic stub engine (LLM_MODE=stub).

No API Keys Required: Operates without external keys (e.g., OpenAI or Google Gemini).

Fully Offline Capable: No external downloads or models required during runtime.

Zero Hardware Costs: Runs smoothly on Google Colab's free CPU tier.

Dependencies: Built primarily on Python's Standard Library, with optional Matplotlib for visual reporting.

# 🚀 How to Use

Open the Notebook: Load the notebook file into Google Colab or a local Jupyter Notebook environment.

Environment Check (C0_ENV_DOCTOR): Run the first cell to perform a system health check and extract bundled files.

Sequential Execution: Run the cells in sequential order from top to bottom.

Complete Exercises: Focus on solving the numbered Learner Exercises.

Generate Day Gates: At the end of each training day, ensure you generate and export the JSON Evidence file to confirm your completion.

# 🔗 Important Links

Saudi Data & AI Authority (SDAIA) & SDAIA Academy Official Website: https://sdaia.gov.sa
