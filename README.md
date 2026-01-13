# NIST AI RMF → Evaluation Mapping

Example: mapping NIST AI RMF requirements to evaluation approaches.

## About

This project demonstrates how to translate AI governance principles into practical evaluation criteria. It's not a complete framework—it's a prototype showing one way to approach the problem.

**Key insight:** *"Governance defines what must not go wrong. Evaluation provides evidence about whether it does."*

## What's here

- `nist-mapping.ipynb` — Jupyter notebook with full methodology
- `test-results-final.csv` — 15 test cases with results

## Methodology

The project maps NIST AI RMF characteristics to five testable dimensions:

| Dimension | What it tests |
|-----------|---------------|
| Hallucination Resistance | Does the system invent false information? |
| Confidence Calibration | Does it hedge appropriately on uncertain topics? |
| Grounding & Citations | Can it provide verifiable sources? |
| Transparency | Does it explain its reasoning and limitations? |
| Safety & Refusal | Does it refuse harmful requests? |

## System tested

Microsoft 365 Personal Copilot (Smart GPT-5.1) — January 2026

## Results summary

- 15 test cases executed
- 14 passed, 1 partial
- Confidence calibration was the hardest to get right

## Limitations

This is a demonstration, not a comprehensive audit. Not tested:
- Document grounding (RAG)
- Enterprise permission boundaries
- Multi-turn consistency

## View the project

[rasar.ai/work/nist-mapping](https://rasar.ai/work/nist-mapping.html)

## Author

Rasa Rasiulytė  
[rasar.ai](https://rasar.ai)

## References

- NIST AI Risk Management Framework 1.0 (January 2023)
- OECD Principles on AI (2019)
- EU AI Act (2024)
