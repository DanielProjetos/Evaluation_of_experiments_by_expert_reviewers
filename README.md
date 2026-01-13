# Evaluation of experiments by expert reviewers (v2.0)

São Paulo, 13 de janeiro de 2026  
Engenheiro de Software: Daniel Oliveira Leal

## Overview

**Evaluation of experiments by expert reviewers** is a formal logical-evaluation protocol designed for the rigorous assessment of scientific experiments, research proposals, and methodological claims.

It is intended for **expert reviewers**, **research auditors**, and **high-stakes scientific evaluation**, where ambiguity, informal reasoning, or heuristic inference are unacceptable.

The protocol prioritizes **logical consistency, formal validity, and replicability** over flexibility or conversational fluency.

---

## Core Objective

Guarantee the **maximum possible level of precision** in the evaluation of scientific experiments and projects by:

- Eliminating modal and inferential ambiguity  
- Preventing undocumented assumptions  
- Enforcing explicit formal structure  
- Ensuring stable and deterministic evaluations  

---

## Operating Regime

- **🟢 Single Regime: High Precision Only**
- No automatic or implicit mode switching
- No concurrency between permissive and strict reasoning modes

This design **removes modal competition**, ensuring logical stability and consistent outcomes.

---

## Functional Capabilities

- Logical coherence and consistency analysis  
- Formal validation of experimental premises and conclusions  
- Detection of:
  - missing variables,
  - undefined criteria,
  - ambiguous or normative terms
- Explicit interruption when evaluation is not formally possible  

---

## Mandatory Response Structure

1. **Premissas**  
2. **Verificação**  
3. **Conclusão**

---

## Formal Evaluation States

- 🟢 ✅ **VÁLIDO** — Supported strictly by explicit premises  
- 🟢 ❌ **INVÁLIDO** — Contradicts premises or violates logic  
- 🟢 🟡 **CONDICIONAL / INCOMPLETO** — Missing data, undefined terms, or insufficient structure  

Additional interruption states:
- 🟡 **DADOS FALTANDO**
- 🟡 **INTERROMPER**

---

## Precision Rules (Preventive)

- Every normative or comparative term must be **defined operationally at first occurrence**.
- If not possible, mark as 🟡 and request the **minimum necessary clarification**.

---

## Inference Policy

- ❌ No assumption-based completion of gaps  
- ❌ No contextual or narrative inference  
- ✅ Only strict logical inference from explicit premises  

---

## License

This project is licensed under the  
**LICENSA_apps**.

**Summary:**
- ✅ Free for academic, scientific, and non-commercial use  
- ❌ Commercial use only with explicit authorization  
- ❌ Modified or adapted versions may not use the original name  
- ✅ Attribution required  

See the `LICENSE` file for full terms.

---

## Status

🟢 **Stable — Ready for high-rigor scientific evaluation**
