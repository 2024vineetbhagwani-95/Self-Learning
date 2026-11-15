# Theory of Computer Science (TCS) – JFLAP Self-Learning Assignment

**Student Name:** Vineet Bhagwani  
**Roll No:** 7  
**Class / Division:** D12A  
**Subject:** Theory of Computer Science (TCS) (26CMPC51)  
**Department:** Department of Computer Engineering  
**Institution:** Vivekanand Education Society's Institute of Technology (VESIT)  
**Faculty In-Charge:** Mr. Sanjay Mirchandani  

---

## 📌 Executive Summary

This repository contains the practical portfolio for the **JFLAP Self-Learning Assignment** in Theory of Computer Science. The portfolio covers **8 practical modules** based on core concepts of **Finite Automata and Transducers**, including DFA, NFA, automata conversion and minimization, regular expressions, grammar conversion, and Mealy and Moore machines.

All `.jff` files follow the standard JFLAP XML format and are organized using the institutional naming convention:
`Roll_No._Name_Topic_DOP` → `7_Vineet_Bhagwani_<Topic>_15-11-2026.jff`

---

## 📋 Master Practical Index & Verification Tracker

| No. | Directory | Topic / Concept Covered | Primary JFLAP File(s) | Machine / Formal Type | Verification Status |
|:---:|:---|:---|:---|:---:|:---:|
| **01** | [`01_DFA`](./01_DFA/) | Deterministic Finite Automata (Binary Divisible by 3) | `7_Vineet_Bhagwani_DFA_15-11-2026.jff` | DFA | **Validated & Verified** |
| **02** | [`02_NFA`](./02_NFA/) | Non-Deterministic Finite Automata (Contains `101`) | `7_Vineet_Bhagwani_NFA_15-11-2026.jff` | NFA | **Validated & Verified** |
| **03** | [`03_NFA_to_DFA`](./03_NFA_to_DFA/) | NFA to DFA Subset Construction (Ends in `ab`) | `NFA_Source`, `DFA_Converted` | FA Conversion | **Validated & Verified** |
| **04** | [`04_DFA_Minimization`](./04_DFA_Minimization/) | DFA Minimization using Equivalence Partitioning (Ends `01`) | `DFA_Original`, `DFA_Minimized` | FA Minimization | **Validated & Verified** |
| **05** | [`05_RE_to_DFA`](./05_RE_to_DFA/) | Regular Expression to DFA Conversion (`(a+b)*abb`) | `RE`, `DFA_from_RE` | RE / FA | **Validated & Verified** |
| **06** | [`06_DFA_to_Grammar`](./06_DFA_to_Grammar/) | DFA to Right-Linear Grammar Conversion (Starts 0, Ends 1) | `DFA_Source`, `Grammar_Converted` | FA → Grammar | **Validated & Verified** |
| **07** | [`07_Mealy_Machine`](./07_Mealy_Machine/) | Mealy Machine (Sequence Detector for `101` with Overlap) | `7_Vineet_Bhagwani_Mealy_15-11-2026.jff` | Mealy Transducer | **Validated & Verified** |
| **08** | [`08_Moore_Machine`](./08_Moore_Machine/) | Moore Machine (Binary Stream Residue Modulo 3 Evaluator) | `7_Vineet_Bhagwani_Moore_15-11-2026.jff` | Moore Transducer | **Validated & Verified** |

---

## 📂 Standard Repository Architecture

Each practical directory contains:
1. **Native JFLAP File(s) (`.jff`)** for direct execution in JFLAP.
2. **Comprehensive Report (`README.md`)** covering the problem statement, formal definition, transition logic, test cases, and execution instructions.
3. **Formal Test Log (`validation_log.md`)** documenting the verification process.

---

## 🚀 How to Run and Test in JFLAP

### Prerequisites
- Java Runtime Environment (JRE 8 or above).
- JFLAP `.jar` distribution.

### Execution Steps
1. Launch JFLAP:
   ```bash
   java -jar JFLAP.jar
   ```
2. Select **File → Open** and choose any `.jff` file from this repository.
3. To test multiple strings, select **Input → Multiple Run**.
4. Use the test vectors provided in the corresponding practical `README.md`.

---

## 👨‍🎓 Author Information

- **Student Name:** Vineet Bhagwani
- **Roll Number:** 7
- **Division / Batch:** D12A
- **Department:** Computer Engineering, Vivekanand Education Society's Institute of Technology (VESIT)
- **Course:** Theory of Computer Science (26CMPC51)
- **Academic Year:** 2026 – 2027
