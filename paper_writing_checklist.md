# 📋 Scientific Writing Checklist

A structured checklist for preparing and polishing scientific works.
You can copy this list as an Issue to your repository of choice and mark the items online on GitHub to ensure you have satisfied all the requirements.

---

## ✒️ Style & formatting policy

**Symbols**
- [ ] Consistent across manuscript  
- [ ] Scalars → italic lowercase (e.g. $u$)  
- [ ] Vectors → bold italic lowercase (e.g. $\vec{u}$)  
- [ ] Matrices / second-order [tensor](https://en.wikipedia.org/wiki/Tensor) / [dyadics](https://en.wikipedia.org/wiki/Dyadics) → bold upright uppercase (e.g. $\mathbf{U}$) or bold if Greek (e.g. $\boldsymbol{\tau}$)  
- [ ] Unit vectors → always $\vec{e}$ (never hatted symbols)  
- [ ] Vector magnitudes → italic lowercase (like scalars, e.g. $u$)  
- [ ] Never introduce new symbols in brackets; brackets only for abbreviations (e.g. Virtual wind tunnel (VWT), the density $\rho$)  

**Abbreviations**
- [ ] Only capitalise names: airborne wind energy (AWE), Reynolds-averaged Navier–Stokes (RANS) ([AJE reference](https://www.aje.com/arc/editing-tip-capitalization-when-defining-abbreviations/))  
    

**Subscripts and indices**
- [ ] Variables/iterative indices → italic (e.g. $x_i$)  
- [ ] Descriptors/abbreviations → roman (e.g. $v_{\textrm{w}}$)  
- [ ] Use commas for multiple indices, never double subscripts (e.g. $v_{\textrm{w},i}$)  
- [ ] Indices never bold  

**Numbers and units**
- [ ] All numbers in math mode (e.g. $10^5$)  
- [ ] Units always with `\unit{}` inside math mode (e.g. $(\unit{m})$)  
- [ ] Minus signs always `$-$` (never hyphen)  
- [ ] Angles $\alpha$ to one decimal place (e.g. $10.1^\circ$)  
- [ ] Format as $m \, s^{-1}$ etc.  

**Equations**
- [ ] Use `equation` environment, one per block  
- [ ] Number only if referenced  
- [ ] No manual spacing like `\,`  
- [ ] Never place two equations consecutively without text between  
- [ ] End with a point or a comma, depending on sentence integration  

**Figures and tables**
- [ ] Units in figures in parentheses `(m)` or dash `(-)`  
- [ ] Captions must not start with “(A)” or “The”  
- [ ] Panels labelled (a), (b), etc., lowercase in parentheses  
- [ ] Figures referenced by label (“see~Fig.~\ref{fig:example}”), never by position  

**Terminology**
  - [ ] Always write “TU Delft V3 kite” or “V3 kite” (never just “V3”)  
  - [ ] Aerodynamic coefficients → lowercase ($C_{\mathrm{l}}, C_{\mathrm{d}}, C_{\mathrm{s}}$) for 2D; uppercase ($C_{\mathrm{L}}, C_{\mathrm{D}}, C_{\mathrm{S}}$) for 3D  
  - [ ] Reynolds number as $\mathrm{Re}$
  - [ ] Infinitesimal $d$ in italic ([reference](https://en.wikipedia.org/wiki/Derivative))

---

## 🧾 Reproducibility and FAIR data

- [ ] Provide DOIs for datasets, models, and code  
- [ ] Mention AI tool usage in Methods or Acknowledgements  
- [ ] Data in non-proprietary formats, metadata FAIR-aligned  
- [ ] Consistently reference datasets (Zenodo preferred over GitHub)  

---

## 📄 Manuscript preparation

**Sections and titles**  
- [ ] First letter capitalised, rest lowercase  
- [ ] Number up to three levels (e.g. 3, 3.1, 3.1.1)  
- [ ] Use “Sect.” in running text (unless at sentence start)  
- [ ] Refer to **Eq.** and **Fig.** (unless at sentence start)  
- [ ] Always capitalise “Table” when numbered, never abbreviate  

**Abstract**  
- [ ] 200–300 words  
- [ ] Include central research question, brief methods, main results, and conclusions  

**Textual style**  
- [ ] Use British English  
- [ ] Oxford comma always  
- [ ] Past tense for work done, results, observations  
- [ ] Present tense for general truths, established knowledge  
- [ ] Future tense for outlooks, perspectives  

**Bibliography**  
- [ ] Each entry must have DOI or working URL  
- [ ] “Submitted” or “in review” allowed if accessible to reviewers ([WES policy](https://www.wind-energy-science.net/submission.html#references))  
- [ ] BibTeX entries must compile with full initials (e.g. `J. A. W. Poland`)  
- [ ] Capitalise “van”, “de”, etc. if at start of entry  
- [ ] Ensure consistency with `macros.tex` vocabulary  

**Citations**  
- [ ] `\citep{}` for (Schmehl et al., 2023)  
- [ ] `\cite{}` for Schmehl et al. (2023)  

**Figures and tables**  
- [ ] Captions above tables  
- [ ] Black-and-white tables with meaningful captions; no colour fill  

**Introduction**  
- [ ] Clearly state research questions  
- [ ] Provide prior work and context  
- [ ] Define hypothesis and objectives  

**Results**  
- [ ] Present only data obtained  
- [ ] Move patterns and implications to Discussion  

**Conclusions**  
- [ ] Link directly to research questions  
- [ ] Provide concise executive summary  
- [ ] Avoid summary-only style  

---

## 📊 Figures, tables, and data

- [ ] Table captions above tables  
- [ ] Units correct (e.g. $\unit{m \, s^{-1}}$)  
- [ ] Numbered sections up to 3 levels  
- [ ] Use “Sect.” in text (unless at sentence start)  
- [ ] Use **Eq.** and **Fig.** for references  
- [ ] **Table** never abbreviated  
- [ ] Use `\unit{}` and `\times` (not `\SI` or `\num`)  
- [ ] Figures renamed `f01`, `f02`, …  
- [ ] Units in figures in parentheses `( )` or dash `(-)`  
- [ ] All figure captions correctly styled  
- [ ] Numerical formatting consistent (engineering vs scientific)  
- [ ] Example: keep $10^5$ scale for easier comparison  

---

## 🔬 Results & analysis

- [ ] Consistent reference to datasets (GitHub vs Zenodo)  
- [ ] Finalise code and data contribution section  
- [ ] Verify scripts and numbers reproducible  
- [ ] Include Reference Model status: TU Delft V3 kite  
- [ ] Mention asymmetry in 3D CFD (possible non-convergence)  

---

## 📦 Miscellaneous

- [ ] Ensure only one `.tex` file in Overleaf (track changes handles edits)  
- [ ] Add Overleaf files:  
  - [ ] `letter_to_editor.txt`  
  - [ ] `reviewers.txt`  

---
