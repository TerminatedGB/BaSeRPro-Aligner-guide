<img src="https://github.com/user-attachments/assets/f7f9a00f-c9c0-4983-9b8b-e835b6ff5cb8" width="80" align="left" />

# BaSeRPro Aligner - Standalone Aligner & Trimmer

### Application Preview

<img src="https://github.com/user-attachments/assets/442797fb-b0aa-4568-95da-75749dcf1e6a" width="720" />

### Features
* Automatically aligns sequences using FAMSA alignment
* Automatically trims gaps in sequence using gap threshold (0-1)
  * Example: If gappyness threshold is 0.7, at least 70 % of sequences must contain a gap in a position for EACH species for it to be trimmed
* Automatically generates consensus sequence based on trimmed alignment using consensus threhsold (0-1)
  * Example: If consensus threhsold is 0.2, at least 20% of equences must contain the same base in a position for it to be incorporated into the consensus sequence
  * Full support for ambiguous bases (both input and output)
  * Automatic detection of DNA, RNA and amino acids
  * Base frequencies of degenerate bases are shown in .xlsx summary file
* Automatically generates conservation plot based on consensus sequence (only positions with degenerate bases from consensus sequence are shown)
