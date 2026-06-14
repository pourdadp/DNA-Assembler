# 🧬 DNA Overlap Assembler – Dual Mode

A browser‑based DNA sequence assembler with **two distinct algorithms**:
- **Greedy Overlap‑Layout‑Consensus (OLC)** — fast, educational, and ideal for small datasets.
- **Semi‑Global Alignment (Dynamic Programming)** — precise, robust, and closer to real‑world assemblers.

Both modes support **reverse complement checking**, **fuzzy matching** for long overlaps, and **graphical visualization** of read alignments.

## 🔬 Features

| Feature | Greedy OLC | Semi‑Global Alignment |
|:---|:---|:---|
| Algorithm | Overlap + Containment + Seed Retry | Smith–Waterman style DP |
| Speed | Very fast | Moderate |
| Handles contained reads | ✅ (explicit check) | ✅ (automatic via alignment) |
| Handles internal overlaps | ⚠️ Limited | ✅ Fully |
| Fuzzy mismatches | ✅ (configurable threshold) | ❌ (exact matching) |
| Graphical output | ✅ Colored overlap map | ✅ Simple contig view |
| Export | `.seq` file | `.seq` file |

## 🚀 Live Demo

👉 **[Try it here](https://pourdadp.github.io/DNA-Assembler/)**


## 🛠️ Tech Stack
- HTML5 / CSS3 / JavaScript (Vanilla)
- No server, no dependencies

## 📸 Screenshots
*Add screenshots of both modes here*

## 👨‍🔬 Author

**Pourdad Panahi** – Biotechnologist & Bioinformatics Developer  
18+ years of wet‑lab experience (cell culture, real‑time PCR, virus cultivation, ELISA).  
Building digital tools for the life sciences.

- **Portfolio:** [pourdadp.github.io](https://pourdadp.github.io)
- **GitHub:** [github.com/pourdadp](https://github.com/pourdadp)
- **LinkedIn:** [linkedin.com/in/pourdad-panahi](https://linkedin.com/in/pourdad-panahi)

---

📄 **Powered By Pourdad Panahi**# 🧪 
