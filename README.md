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

## 🧪 Quick Start

1. Open the [live demo](https://pourdadp.github.io/DNA-Assembler/) or download `index.html` and open it in any modern browser.
2. Choose an **Assembly Mode** (Greedy or Alignment).
3. Paste your reads in **FASTA format** or as plain text (one sequence per line).
4. Adjust the **minimum overlap length** (and mismatch tolerance if using Greedy mode).
5. Click **Run Assembly**.
6. View the **contig**, **graphical alignment**, and **export** the result.

### 📥 Supported Input Formats

- **FASTA** (recommended)
  fasta
  >read1
  ATGCGT
  >read2
  TGCG


· Plain text (one sequence per line)
  
  ATGCGT
  TGCG
  GCGTAA
  
· Mixed (lines starting with > are treated as headers and stripped)

You can also load a .fasta file directly using the Load FASTA File button.

🛠️ Run on a Local Network (Optional)

The assembler is a single HTML file with no dependencies. To make it accessible on a local network:

1. Place index.html on a machine that is always on.
2. Start a simple HTTP server:
   bash
   python -m http.server 8000
   
3. Users on the same network can access it via http://<IP>:8000.

💡 For an even smoother experience, check out our LabFlow LIMS project—a full laboratory management system with Flask backend and mobile UI.
## 🛠️ Tech Stack
- HTML5 / CSS3 / JavaScript (Vanilla)
- No server, no dependencies

## 📸 Screenshots
*Add screenshots of both modes here*

## 👨‍🔬 Author

**Pourdad Panahi** – Biotechnologist & Bioinformatics Developer  
18+ years Startart wet‑lab experience (cell culture, real‑time PCR, virus cultivation, ELISA).  
Building digital tools for the life sciences.

- **Portfolio:** [pourdadp.github.io](https://pourdadp.github.io)
- **GitHub:** [github.com/pourdadp](https://github.com/pourdadp)
- **LinkedIn:** [linkedin.com/in/pourdad-panahi](https://linkedin.com/in/pourdad-panahi)

---

📄 **Powered By Pourdad Panahi**# 🧪 
