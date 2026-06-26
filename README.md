# Computational Structural Characterization of Human C6orf47 protein

Computational structural characterization of the human uncharacterized protein C6orf47 using AlphaFold, intrinsic disorder prediction, pocket detection, evolutionary conservation analysis and exploratory molecular docking.

---

## Overview

Uncharacterized proteins remain a major challenge in modern molecular biology and structural bioinformatics. Although large-scale genome sequencing projects have identified thousands of protein-coding genes, many proteins still lack experimentally validated structural or functional annotation.

This project presents an exploratory computational structural characterization of the human uncharacterized protein **C6orf47** (UniProt accession: O95873). The study integrates sequence analysis, structural prediction, intrinsic disorder analysis, evolutionary conservation analysis, pocket detection, stereochemical validation and exploratory molecular docking to investigate the structural organization and possible interaction-prone regions of the protein.

The workflow emphasizes reproducibility-aware interpretation and scientific caution. All findings are computational predictions and should not be interpreted as experimental confirmation of biological function or ligand binding.

---

## Objectives

* Retrieve and analyze the sequence of human C6orf47
* Investigate conserved domains and structural organization
* Evaluate intrinsic disorder propensity
* Analyze AlphaFold structural confidence
* Identify predicted ligand-binding cavities
* Perform exploratory molecular docking with sterol-like ligands
* Assess stereochemical quality using PROCHECK
* Integrate multiple computational approaches for cautious structural interpretation

---

## Project Workflow

```text
UniProt Sequence Retrieval
            ↓
Conserved Domain Analysis
            ↓
AlphaFold Structure Analysis
            ↓
Intrinsic Disorder Prediction (IUPred2A)
            ↓
Evolutionary Conservation Analysis (ConSurf)
            ↓
Pocket Detection (P2Rank / PrankWeb)
            ↓
Exploratory Molecular Docking
            ↓
Structural Validation (PROCHECK)
            ↓
Integrated Structural Interpretation
```

---

## Tools and Databases Used

| Category                  | Tools / Resources    |
| ------------------------- | -------------------- |
| Sequence Database         | UniProt              |
| Conserved Domain Analysis | InterPro, NCBI CDD   |
| Structure Prediction      | AlphaFold            |
| Disorder Prediction       | IUPred2A             |
| Conservation Analysis     | ConSurf              |
| Pocket Detection          | P2Rank, PrankWeb     |
| Molecular Docking         | CB-Dock2, SeamDock   |
| Docking Engine            | AutoDock Vina        |
| Structure Visualization   | PyMOL                |
| Structural Validation     | PROCHECK, SAVES v6.1 |

---

## Key Findings

* AlphaFold structural analysis suggested a mixed architecture containing flexible terminal regions and a comparatively ordered hydrophobic core region.
* IUPred2A predicted substantial intrinsic disorder across large portions of the sequence.
* ConSurf analysis indicated relatively higher conservation within the ordered central region compared to terminal segments.
* Pocket prediction identified a hydrophobic cavity localized within the predicted ordered core.
* Exploratory docking with cholesterol and progesterone repeatedly localized both ligands within the same predicted cavity across multiple docking runs and platforms.
* Docking scores demonstrated variability between runs, highlighting the limitations of docking-based inference.
* PROCHECK validation produced globally weak stereochemical statistics, interpreted alongside disorder predictions and AlphaFold confidence trends rather than as evidence of complete structural collapse.

---

## Scientific Interpretation

The findings collectively support the possibility that C6orf47 contains a comparatively ordered hydrophobic region embedded within a broader disorder-rich protein architecture. The convergence of structural confidence patterns, disorder prediction, conservation analysis and pocket prediction strengthens this interpretation.

However, all docking observations remain exploratory computational predictions. The project does not establish physiological ligand binding, biological function or experimentally validated molecular interactions.

---

## Limitations

* All structural observations are prediction-based.
* AlphaFold models are not equivalent to experimentally solved structures.
* Intrinsically disordered proteins may produce poor stereochemical validation statistics.
* Docking scores are sensitive to scoring functions, cavity geometry and structural uncertainty.
* Docking results do not establish physiological binding or biological activity.
* No wet-lab experimental validation was performed for this project.

---

## Potential Future Directions

* Experimental validation through biochemical or biophysical approaches
* Protein expression and purification studies
* Molecular dynamics simulations
* Comparative analysis with homologous proteins
* Functional interaction studies
* Experimental ligand-binding assays

---

## References

1. Jumper J, Evans R, Pritzel A, et al. Highly accurate protein structure prediction with AlphaFold. Nature. 2021.

2. Erdős G, Dosztányi Z. Analyzing Protein Disorder with IUPred2A. Current Protocols in Bioinformatics. 2020.

3. Trott O, Olson AJ. AutoDock Vina: improving the speed and accuracy of docking. Journal of Computational Chemistry. 2010.

4. Laskowski RA, MacArthur MW, Moss DS, Thornton JM. PROCHECK: a program to check the stereochemical quality of protein structures. Acta Crystallographica D. 1993.

5. Liu Y, Grimm M, Dai WT, et al. CB-Dock2: improved protein–ligand blind docking. Nucleic Acids Research. 2022.

6. Polák M, et al. PrankWeb 4: a modular web server for protein–ligand binding site prediction and downstream analysis. Nucleic Acids Research. 2025.

---

## Acknowledgements

This project was completed as part of a postgraduate diploma mini-project focused on computational structural bioinformatics, reproducibility-aware analysis and scientific interpretation of uncharacterized proteins.

---

## Author

**LNS Sthavitha Rithu**

PG Diploma in Bioinformatics, Genomics and Data Science

Bversity School of Biosciences

---

