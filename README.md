# Supplementary Materials: Mplus CLPM Analyses 

## Developmental Relations of Spanish and English Spelling in Emergent Bilinguals Between Grade 1 and Grade 3: Exploring Scoring Methods and Instructional Contexts

This repository contains Mplus output files for a series of cross-lagged panel model (CLPM) analyses used in a manuscript on spelling development in Spanish-English bilingual children (Grades 1–3).

## 🧠 Purpose
These models were developed as part of a study investigating:
- Cross-linguistic transfer between Spanish and English spelling
- Different scoring methods for spelling (correctness vs. text distance)
- Instructional program differences (English Immersion vs. Dual Immersion)

## 📁 Repository Structure
Files are organized by figure number and include three versions of each analysis.

### File Naming Convention
Base models:
- FigureX-[Description].out
(Primary analyses reported in the manuscript)

Sensitivity analyses:
- FigureX-[Description]-Drop-Changed.out - Robustness checks excluding changed observations
- FigureX-[Description]-School-SE.out - Models with school-clustered standard errors

Note: Output files (.out) include the full Mplus input syntax at the beginning of each file.

### Models Included
- **Figure 3: English-Spanish correctness scores CLPM**  
  Bidirectional relations between English and Spanish spelling correctness

- **Figure 4: English-Spanish text distance scores CLPM**  
  Bidirectional relations using text distance spelling scores

- **Figure 5: Final Multigroup correctness model**  
  Multi-group CLPM (English Immersion vs. Dual Immersion) with correctness scores
  
- **Figure 6: Final Multigroup text distance model**  
  Multi-group CLPM with text distance scores, pathways constrained/freed based on model comparison

## 📊 Variable Descriptions
- g1engsp, g3engsp: English spelling correctness scores at Grades 1 and 3
- g1spnsp, g3spnsp: Spanish spelling correctness scores at Grades 1 and 3
- g1engtd, g3engtd: English spelling text distance scores at Grades 1 and 3
- g1spntd, g3spntd: Spanish spelling text distance scores at Grades 1 and 3
- d_g1el: English learner (EL) status
- d_g1dual: Instructional group (0 = English Immersion, 1 = Dual Immersion)

## ⚙️ Model Information
- Estimation method:
		- MLR (robust maximum likelihood) for correctness scores, to account for nonnormality
		- ML (maximum likelihood) for text distance scores
- Missing data: Handled via Full Information Maximum Likelihood (FIML)
- Standardization: Variables are standardized (z) where noted in syntax
- Sensitivity analyses: Include models that drop changed observations and models accounting for school clustering

### 📖 Citation
[placeholder]
- DOI: [placeholder]

For questions, please contact: moonys@stanford.edu
