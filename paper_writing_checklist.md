# 📋 Scientific Writing Checklist

A structured checklist for preparing and polishing scientific works.

---

## ✒️ Style & Formatting Policy

### 🔢 Notation Style

- [ ] **Symbols**
  - Consistent across manuscript
  - Scalars → italic lowercase (e.g. $u$).
  - Vectors → bold italic lowercase (e.g. $\vec{u}$).
  - Matrices / second-order tensors → bold upright uppercase (e.g. $\mathbf{U}$).
  - Unit vectors → always $\vec{e}$ (never hatted symbols).
  - Vector magnitudes → italic lowercase (like scalars, e.g. $u$).
  - Never introduce new symbols in brackets; brackets are reserved for abbreviations.  
    Example: Virtual wind tunnel (VWT), the density $\rho$.

- [ ] **Subscripts and Indices**
  - Variables/iterative indices → italic (e.g. $x_i$, $V_j$).
  - Descriptors/abbreviations → roman (e.g. $C_{\mathrm{w}}$, $T_{\mathrm{env}}$).
  - Never use double subscripts; use commas for multiple indices
    Example: $\vec{u}_{\textrm{a},k}$
  - Indices are never bold.

- [ ] **Numbers and Units**
  - All numbers in math mode (e.g. `$10^5$`).
  - Units always with `\unit{}` and inside math mode, e.g. $(\unit{m})$.
  - Minus signs always `$-$` (never a hyphen).
  - $\alpha$ values → one decimal place (e.g. $10.1^\circ$).
  - Formatted as $m \, s^{-1}$ etc.

- [ ] **Equations**
  - Use `equation` environment, one equation per block.
  - Reference equations only if cited later in text.
  - Do not use manual spacing like `\,`.
  - Never place two equations consecutively without explanatory text.
  - Must end with a point or a comma, depending on how they are integrated in the sentence.

- [ ] **Figures and Tables**
  - Units in figures must be in parentheses, e.g. `(m)` or dash `(-)`.
  - Captions must not start with “(A)” or “The”.
  - Panels labelled (a), (b), etc., lowercase in parentheses.
  - Figures referenced by label: “see~Fig.\ref{fig:example}”, never “see below”.

- [ ] **Terminology**
  - Always write “TU Delft V3 kite” or “V3 kite” (never just “V3”).
  - Aerodynamic coefficients: lowercase ($C_{\mathrm{l}}, C_{\mathrm{d}}, C_{\mathrm{s}}$) for 2D; uppercase ($C_{\mathrm{L}}, C_{\mathrm{D}}, C_{\mathrm{S}}$) for 3D.
  - Reynolds number as `$\mathrm{Re}$`

---

### 🧾 Reproducibility and FAIR Data

- [ ] Provide DOIs for datasets, models, and code.
- [ ] Mention AI tool usage in Methods or Acknowledgements.
- [ ] Data must be in non-proprietary formats, metadata aligned to FAIR principles.
- [ ] Consistently reference datasets (Zenodo preferred over GitHub for archival).

---

## 📐 Mathematical & Notation

- [ ] [Tensor definitions](https://en.wikipedia.org/wiki/Tensor)  
  - A **scalar** (0th order) → single number  
  - A **vector** (1st order) → quantity with direction  
  - A **dyadic** (2nd order) → matrix transforming vectors to vectors  
  - [Dyadics](https://en.wikipedia.org/wiki/Dyadics) are natural in mechanics (stress, strain, momentum flux):  
    - *Which direction the quantity flows*  
    - *Through which surface orientation*  
- [ ] Typeset infinitesimal *d* correctly ([reference](https://en.wikipedia.org/wiki/Derivative))  


---

## ✍️ Writing & Formatting

- [ ] Author name → `J. A. W. Poland` (spaces required in BibTeX)  
- [ ] Abbreviation capitalization rules ([AJE reference](https://www.aje.com/arc/editing-tip-capitalization-when-defining-abbreviations/))  
- [ ] Use `\cite{}` vs. `\citep{}` correctly  
  - `\cite{}` → inline  
  - `\citep{}` → full reference in parentheses  
- [ ] Do **not** glue references to previous word with `~` (except numbered references)  
- [ ] Noca method:  
  - Use "Noca's method" or "the Noca method" (not "NOCA method")  
  - Example: [CFD Land](https://cfdland.com/introduction-to-dpm-breakup-models/)  

- [ ] Abstract between 200–300 words  
- [ ] Ensure correct tense ([Nature guide](https://www.nature.com/scitable/topicpage/effective-writing-13815989/)):  
  - Past → work done, observations  
  - Present → general truths  
  - Future → perspectives  

---

## 📄 Manuscript preparation checklist

- [ ] **Sections and titles**
  - Section titles → only first letter capitalised, rest lowercase.
  - Sections numbered up to three levels (e.g. 3, 3.1, 3.1.1).
  - Use “Sect.” in running text (unless at sentence start).
  - Refer to equations and figures as **Eq.** and **Fig.** (unless at sentence start).
  - Always capitalise “Table” when numbered; never abbreviate.

- [ ] **Abstract**
  - 200–300 words.
  - Must state central research question, brief methods, main results, and conclusions.

- [ ] **Textual style**
  - Use **British English**.
  - Oxford comma always.
  - Past tense for work done, results, observations.
  - Present tense for general truths, established knowledge.
  - Future tense for outlooks and perspectives.

- [ ] **Bibliography**
  - Each entry must have a DOI or working URL.
  - Works “submitted” or “in review” allowed if accessible to reviewers ([WES reference policy](https://www.wind-energy-science.net/submission.html#references)).
  - BibTeX entries must compile with full initials (e.g. `J. A. W. Poland`).
  - Capitalise “van”, “de”, etc. if at start of entry.
  - Ensure consistency with `macros.tex` vocabulary.

- [ ] **Citations**
  - `\citep{}` → for (Schmehl et al., 2023).
  - `\cite{}` → for Schmehl et al. (2023).

- [ ] **Figures and tables**
  - Captions above tables.
  - Black-and-white tables with meaningful captions; no colour fill.

- [ ] **Introduction**
  - Clearly state the **research questions**.
  - Provide prior work and context.
  - Define hypothesis and objectives.

- [ ] **Results**
  - Present only **data obtained**.
  - Patterns and implications deferred to **Discussion**.

- [ ] **Conclusions**
  - Link directly to research questions.
  - Provide concise **executive summary**.
  - Avoid summary-only style.

---

## 📊 Figures, Tables, and Data

- [ ] [WES requirements](https://www.wind-energy-science.net/submission.html#figurestables):  
  - [ ] Table captions above tables  
  - [ ] Units correct (e.g. \( \mathrm{m \, s^{-1}} \))  
  - [ ] Numbered sections (up to 3 levels)  
  - [ ] "Sect." abbreviation in text (unless at sentence start)  
  - [ ] Use **Eq.** and **Fig.**  
  - [ ] **Table** never abbreviated  
  - [ ] Use `\unit{}` and `\times` (not `\SI` or `\num`)  
  - [ ] Figures renamed `f01`, `f02`, ...  

- [ ] Units in figures: use parentheses `( )` or dash `(-)`  
- [ ] Ensure all figure captions are correctly styled  
- [ ] Numerical formatting:  
  - Engineering vs. scientific notation  
  - Use consistent convention  
  - Example: easier comparisons if kept at $10^5$ scale  

---


---

## 🔬 Results & Analysis

- [ ] Consistent reference to datasets (GitHub vs Zenodo?)  
- [ ] Finalize code & data contribution section  
- [ ] Verify all scripts and numbers reproducible  
- [ ] Include Reference Model status: TU Delft V3 kite  
- [ ] Mention asymmetry in 3D CFD (possible non-convergence)  

---

## 📦 Miscellaneous

- [ ] Ensure only **one `.tex` file** in Overleaf (track changes handles edits)  
- [ ] Add Overleaf files:  
  - `letter_to_editor.txt`  
  - `reviewers.txt`
    
---
