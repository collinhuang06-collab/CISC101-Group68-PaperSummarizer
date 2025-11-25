# CISC101-Group68-PaperSummarizer

This repository contains the system prompt and modular architecture for an AI-powered research paper summarizer based on our PS2 specification.

## PS2 Specification Basis
- **Inputs:** Sectioned academic paper, target audience level
- **Outputs:** Individual section summaries (75-150 words each), combined summary (<500 words)
- **Constraints:** Preserve section order, consistent terminology, no hallucination

## Contents
- `system_prompt.md`: Main system prompt
- `/modules/`: Internal reference framework
  - 01-04: Core modules
  - 05-06: Custom modules (Audience Adapter, Terminology Checker)
