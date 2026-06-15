<img width="1536" height="1024" alt="SyntenyPair-Explorer-Logo" src="https://github.com/user-attachments/assets/997f9bf9-8f58-41d4-903d-c20904203ec1" />

**🔗 [Launch SyntenyPair Explorer](https://gibbonslabgenomics.github.io/SyntenyPair-Explorer/)** — runs directly in your browser, no installation needed.

# SyntenyPair-Explorer
A standalone, browser-based tool for interactive two-genome 
synteny visualization. No installation required -- open the 
HTML file in any browser.

## Features
- Accepts fasta genome, GFF3/GTF, BLAST outfmt6, and MCScan colinearity files
- Interactive zoom, pan, and gene search
- Automatic partner-genome alignment when searching genes
- Synteny block coloring, custom gene highlights, PNG export
- Full session save and restore

## Quick start
1. Download `index.html`
2. Open it in Chrome, Firefox, Safari, or Edge
3. Load your genome (fasta format), GFF3 and synteny files (MCscan
   colinearity file or blast outfmt6), or click "Load demo"

## Input formats
**GFF3/GTF:** Standard gene annotation files. Gene, mRNA, and 
transcript features are supported. Both NCBI RefSeq and 
Phytozome-style GFFs work.

**BLAST tabular (outfmt 6):** blastn output with -outfmt 6. 
Query/subject can be chromosome names (coordinates used to 
find overlapping genes) or gene IDs (direct match).

**MCScan colinearity:** Output from MCScan 
(.collinearity files). Detected automatically.

## Citation
Manuscript in preparation.

## License
MIT License — see LICENSE file.
