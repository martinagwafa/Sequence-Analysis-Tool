# 🧬 Sequence Analysis Tool

A quick-and-clean command-line utility written in Python that helps you:

1. **Count records & sequences** in a FASTA or GenBank file  
2. **Extract an ORF** (using start/stop codon positions)  
3. **Translate DNA to protein**  
4. **Simulate a mutation** and compare the original vs mutant protein  
5. **Classify mutations** as synonymous, non-synonymous, or nonsense (early stop codon)

---

## 📦 Requirements

| Package    | Version (tested) | Install with               |
|------------|------------------|----------------------------|
| Python     | ≥ 3.8            | —                          |
| Biopython  | ≥ 1.83           | `pip install biopython`   |

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/sequence-analysis-tool.git
   cd sequence-analysis-tool
Install dependencies:

bash
Copy
Edit
pip install biopython
Run the script:

bash
Copy
Edit
python seq_analysis.py
🧪 Example Workflow
console
Copy
Edit
Welcome to your sequence analysis tool
Instructions:
  1. Enter all codon positions in biological format...
  2. Know your start/stop codon positions if using a full-length gene
  3. Be aware of which sequence number you want to analyze in multi-sequence files

Please enter the file name: sample.fasta
There are 2 records and 2 different sequences in the file you provided.

Which sequence would you like to analyse? 1
What is the position of the first nucleotide of the start codon? 61
What is the position of the last nucleotide of the stop codon? 888

Sequence length: 828
Amino acid 94 in the original is G
Amino acid 94 in the mutant is D
This is a non-synonymous mutation and is likely to have an effect on protein structure and function.
🧠 How It Works
Input a sequence file (.fasta or .gb)

Choose which record/sequence to analyze

Extract a region (start to stop codon) and translate it

Introduce a mutation (change the nucleotide string between any two positions)

Output the result — protein before & after, and classification of the mutation

🎯 Why I Built This
As a learning tool for understanding DNA → protein translation

To practice Python and Biopython

As a quick script for researchers doing early-stage DNA mutation checks

📄 License
MIT License – use freely, modify, and share. Credit is appreciated.

🙌 Contributing
Pull requests, feedback, and ideas are always welcome.
Fork the repo, star it ⭐, or submit an issue if you’d like to collaborate!
