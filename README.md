# Assignment Title: QSAR Data Curation Using ChEMBL
## Course: AI and Drug Discovery (2026)
Selected Target: Mast/stem cell growth factor receptor KIT (c-KIT)
Organism: Homo sapiens
ChEMBL Target ID: CHEMBL1936
## Total Bioactivity Records (after curation): 4233 compounds
Active (IC50 ≤ 1000 nM): 3473
Intermediate (1000 nM < IC50 < 10000 nM): 353
Inactive (IC50 ≥ 10000 nM): 407
## Data Curation Summary
Bioactivity data were retrieved programmatically from the ChEMBL database using the chembl_webresource_client Python package and the provided AI/bioinformatics template. The workflow included target search and selection, retrieval of IC50 bioactivity records, initial data inspection and missing-value filtering, unit normalization from µM to nM, bioactivity classification, removal of invalid and duplicate entries, and export of the final curated dataset. The final dataset contains molecule ChEMBL IDs, canonical SMILES, normalized IC50 values (nM), and bioactivity classes (active, intermediate, and inactive), ready for QSAR modeling.
