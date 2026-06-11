# 🧬 DNA Overlap Assembler

A **browser-based DNA sequence assembler** using a **Greedy Overlap-Layout-Consensus (OLC)** algorithm with **Fuzzy Matching** and **Seed Retry**. Built entirely with HTML, CSS, and JavaScript—no installation required.

## 🔬 Key Features

| Feature | Description |
|:---|:---|
| **Greedy OLC Algorithm** | Assembles reads by repeatedly merging the pair with the longest overlap |
| **Seed Retry** | If the initial seed fails, tries alternative starting reads to escape local optima |
| **Fuzzy Matching** | Allows up to 3 consecutive mismatches for overlaps ≥ 50 bp (mimics real sequencing errors) |
| **Exact Matching** | For overlaps < 50 bp, enforces 100% identity to prevent false joins |
| **Reverse Complement** | Automatically checks the reverse complement of each read for overlaps |
| **Graphical Visualization** | Color-coded overlap map: 🟥 non-overlap, 🟩 overlap, 🟨 mismatches |
| **Mobile-Friendly UI** | Responsive Bootstrap interface with right-click context menu |
| **Export** | Save assembled contig as `.seq` file |

## 🎯 How It Compares to Other Assemblers

| | **DNA Assembler** | **CAP3** | **SPAdes** |
|:---|:---|:---|:---|
| **Algorithm** | Greedy OLC + Seed Retry | OLC (phrap) | De Bruijn Graph |
| **Error Handling** | Fuzzy Matching (≥50 bp) | Quality-based trimming | Bayesian error correction |
| **Scale** | Small (tens of reads) | Medium (hundreds) | Large (millions) |
| **Interface** | 🌐 Web (no install) | ⌨️ Command-line | ⌨️ Command-line |
| **Visualization** | ✅ Built-in color map | ❌ None | ❌ None |
| **Best For** | Education, small lab assemblies, portfolio | EST assembly | Whole-genome assembly |

> ⚠️ **DNA Assembler is not a replacement for SPAdes or Canu.** It is a **teaching tool** and a **portfolio piece** that demonstrates algorithmic thinking, UI design, and full-stack development skills.

## 🚀 Live Demo

👉 **[Try it here](https://pourdadp.github.io/DNA-Assembler/)**

## 🛠️ Tech Stack

- **HTML5**
- **CSS3 / Bootstrap 5**
- **JavaScript (Vanilla)**
- **No server, no dependencies** – runs entirely in the browser

## 📸 Screenshots

| Assembly View | Graphical Overlap Map |
|:---:|:---:|
| *Add screenshot here* | *Add screenshot here* |

## 🧪 Sample Data

Click the **🔬 Try Sample Reads** button to test wAssemblymbly
