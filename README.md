# 🤖 HNX26PSI08: Proof-Carrying Data Analyst (Agentic GenAI)

> **Agentic GenAI · Data Analytics · Code Generation · Automated Verification**

Welcome to the official repository for **HNX26PSI08: Proof-Carrying Data Analyst**. This project delivers an autonomous AI Agent designed to solve real-world, messy multi-table data analytics problems while strictly guaranteeing mathematical and logical correctness through re-runnable code proofs.

---

## 🎯 Problem Statement & Core Focus
In real-world data analytics, confident wrong answers are dangerous. Our Agent addresses messy, real-world data challenges (unit mismatches, ambiguous dates, duplicates, contradicting tables, and missing data) by providing **Proof-Carrying Answers**.

### Key Rules Implemented:
1. **Re-runnable Code Proofs:** Every numerical answer is backed by executable code (Python/Pandas) that reproduces the exact same result when run by a verifier.
2. **Adversarial & Ambiguity Guardrails:** The Agent intelligently detects unanswerable, ambiguous, or trick questions and declines with a clear reason rather than giving a hallucinated/confident wrong answer.

---

## 🛠️ Key Features
- **Multi-Table Data Handling:** Merges, cleans, and cross-verifies data across disjointed sources.
- **Dynamic Code Execution & Verification:** Auto-generates standard Python code to perform analytics and self-verifies output before delivering answers.
- **Data Anomaly & Trap Detection:**
  - Identifies unit mismatches (e.g., Currency $ vs €).
  - Handles date ambiguity (e.g., MM/DD vs DD/MM).
  - Filters duplicate records and conflicting row entries.
- **Fail-Safe Refusal Mechanism:** Gracefully refuses queries when data is insufficient or contradictory.

---

## 🏗️ Project Architecture & Workflow
1. **Query Input & Data Parsing:** Receives user prompt along with raw, messy datasets.
2. **Agentic Logic & Validation:** Checks for traps, ambiguity, and dataset sanity.
3. **Code Generation:** Generates concise, standalone Python script.
4. **Execution & Proof Attestation:** Runs code in a sandboxed environment to verify the numerical output against the logic.
5. **Final Output:** Returns Answer + Executable Code Proof.

---

## 👥 Team & Collaboration
Developed for the Hackathon by **S Danica** (CSE - Cyber Security, Karunya University) and Team.
