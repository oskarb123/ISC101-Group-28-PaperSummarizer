# ISC101 Group 28 – Paper Summarizer

This repository contains Paper summarizer 3 for CISC 101: a modular Research Paper Summarizer.

## Repository Contents

system_prompt.md 
  The full system prompt generated from our meta-prompt. It defines inputs, outputs, constraints, and the overall summarizer behavior.

 **modules/**  
  Contains the internal modules used by the summarizer:
  - `01_intake_setup.md` – Collect inputs and apply word limits.  
  - `02_section_loop.md` – Loop through sections and create ≤50-word summaries.  
  - `03_guardrails.md` – Enforce no-hallucination rules and handle missing/short sections.  
  - `04_rendering.md` – Produce ordered section summaries and a ≤200-word final summary.  
  - `05_terminology_harmonizer.md` – Keep terminology consistent.  
  - `06_summary_quality_enhancer.md` – Improve clarity and coherence.


