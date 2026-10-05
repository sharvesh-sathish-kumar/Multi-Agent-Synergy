import subprocess

readme_content = """# Multi-Agent Synergy: Predicting and Preventing Expertise Dilution

An empirical and forensic investigation into information contamination, provenance tracking, and coordination mechanisms in multi-agent large language model (LLM) reasoning systems.

Results

When scaling multi-agent LLM teams, combining inputs from diverse models can introduce **expertise dilution**, where valid conclusions from high-performing agents are discounted by lower-reliability outputs.

This repository hosts **60 constrained assignment problems** and over **500 forensic trial logs** evaluating baseline ($C_0: A + B$) vs. treatment ($C_1: A + B + C$) conditions.

### Benchmark Metrics

| Metric | Condition $C_0$ ($A+B$) | Condition $C_1$ ($A+B+C$) | Delta |
| :--- | :---: | :---: | :---: |
| **Accuracy** | 53.33% (32/60) | 63.33% (38/60) | **+10.00%** |
| **Paired Shift** | — | — | +6 net (14 improved, 8 regressed) |
| **Exact McNemar Test** | — | — | $p = 0.2863$ |

