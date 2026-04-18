# Alzheimer's-related proteins: a sequence analysis

A Python-based sequence analysis of three intrinsically disordered proteins 
implicated in Alzheimer's and Parkinson's disease: amyloid-beta (APP), tau, 
and alpha-synuclein.

## What this project does

- Fetches protein data programmatically from the UniProt REST API
- Compares sequence length and amino acid composition across all three proteins
- Calculates physicochemical properties (molecular weight, isoelectric point)
- Analyses disorder-promoting vs order-promoting residue content
- Performs cross-species conservation analysis of alpha-synuclein across 6 mammals

## Tools used

Python, Jupyter, pandas, matplotlib, seaborn, UniProt REST API

## Key findings

- All three proteins are highly enriched in disorder-promoting residues (49–66%),
  consistent with their classification as intrinsically disordered proteins (IDPs)
- Alpha-synuclein is remarkably conserved across mammals (94–100% identity to human),
  suggesting strong evolutionary constraint despite its disordered nature
- Tau shows the highest disorder content at 66%, consistent with its highly flexible structure
