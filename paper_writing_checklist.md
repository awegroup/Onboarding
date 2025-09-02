# 📋 Checklist

A structured checklist for preparing and polishing scientific works.
You can copy this list as an Issue to your repository of choice and mark the items online on GitHub to ensure you have satisfied all the requirements.

---

## ✒️ Style & formatting policy

**Symbols**
- [ ] Consistent across manuscript  
- [ ] Scalars → italic lowercase (e.g. u: $u$)  
- [ ] Vectors → bold italic lowercase (e.g. \vec{u}: $\vec{u}$)  
- [ ] Matrices / second-order [tensor](https://en.wikipedia.org/wiki/Tensor) / [dyadics](https://en.wikipedia.org/wiki/Dyadics) → bold upright uppercase (e.g. \mathbf{U}: $\mathbf{U}$) 
    or bold if Greek (e.g. \boldsymbol{\tau}: $\boldsymbol{\tau}$)  
- [ ] Unit vectors → always \vec{e}: $\vec{e}$ (never hatted symbols)  
- [ ] Vector magnitudes → italic lowercase (like scalars, e.g. u: $u$)  
- [ ] Never introduce new symbols in brackets; brackets only for abbreviations (e.g. Virtual wind tunnel (VWT), the density \rho)  

**Abbreviations**
- [ ] Only capitalise names: airborne wind energy (AWE), Reynolds-averaged Navier–Stokes (RANS) ([AJE reference](https://www.aje.com/arc/editing-tip-capitalization-when-defining-abbreviations/))  
    
**Subscripts and indices**
- [ ] Variables/iterative indices → italic (e.g. x_i: $x_i$)  
- [ ] Descriptors/abbreviations → roman (e.g. v_\textrm{w}: $v_{\textrm{w}}$)  
- [ ] Use commas for multiple indices, never double subscripts (e.g. v_{\textrm{w},i}: $v_{\textrm{w},i}$)  
- [ ] Indices never bold

**Numbers and units**
- [ ] All numbers in math mode →  $10^5$  
- [ ] Units always with `\unit{}` inside math mode, and between round brackets →  (\unit{m}):  $(\unit{m})$  
- [ ] Minus signs always `$-$` (never hyphen)   
- [ ] Format as $\unit{m \, s^{-1}}$ 

**Equations**
- [ ] Use `equation` environment, one per block  
- [ ] Number only if referenced  
- [ ] No manual spacing like `\,`  
- [ ] Never place two equations consecutively without text between  
- [ ] End with a point or a comma, depending on sentence integration  

**Terminology**
  - [ ] Always write “TU Delft V3 kite” or “V3 kite” (never just “V3”)  
  - [ ] Aerodynamic coefficients → lowercase ($C_{\mathrm{l}}, C_{\mathrm{d}}, C_{\mathrm{s}}$) for 2D; uppercase ($C_{\mathrm{L}}, C_{\mathrm{D}}, C_{\mathrm{S}}$) for 3D  
  - [ ] Reynolds number as $\mathrm{Re}$
  - [ ] Infinitesimal $d$ in italic ([reference](https://en.wikipedia.org/wiki/Derivative))

**Sections and titles**  
- [ ] First letter capitalised, rest lowercase  
- [ ] Number up to three levels (e.g. 3, 3.1, 3.1.1)  
- [ ] Use “Sect.” in running text (unless at sentence start

**Citations** → see [Bibliography](##Bibliography) 
- [ ] `\citep{}` for (Schmehl et al., 2023)  
- [ ] `\cite{}` for Schmehl et al. (2023)  

**Textual style**  
- [ ] Use British English  
- [ ] Oxford comma always  
- [ ] Past tense for work done, results, observations  
- [ ] Present tense for general truths, established knowledge  
- [ ] Future tense for outlooks, perspectives  

---

## 📊 Figures, tables, and data

- [ ] Table captions must be placed **above** the table.  
- [ ] Figure captions must be placed **below** the figure.  
- [ ] Captions must not start with “(A)” or “The”.  
- [ ] Tables must be black-and-white with meaningful captions; no colour fill.  
- [ ] Panels in multi-part figures labelled (a), (b), etc., lowercase in parentheses.  
- [ ] Use **Sect.** in running text (unless at the beginning of a sentence).  
- [ ] Use **Eq.** and **Fig.** for equation/figure references (unless at sentence start).  
- [ ] Always capitalise “Table” when numbered, never abbreviate.  
- [ ] Figures must always be referenced by label (e.g. “see Fig. \ref{fig:example}”), never by position.  

---

## 📄 Manuscript structure and content

**Abstract**  
- [ ] 200–300 words  
- [ ] Include central research question, brief methods, main results, and conclusions  

**Introduction**  
- [ ] Clearly state research questions  
- [ ] Provide prior work and context  
- [ ] Define hypothesis and objectives

**Method**  
- [ ] Thoroughly discuss the method, without revealing any results
- [ ] Make sure the description is sufficient to be reproducible
- [ ] Focus on the essence, and leave the details in the Appendix

**Results**  
- [ ] Present only data obtained  
- [ ] Move patterns and implications to Discussion

**Conclusions**  
- [ ] Link directly to research questions  
- [ ] Provide concise executive summary  
- [ ] Avoid summary-only style  

---

## 📚 Bibliograph  
- [ ] Each entry must have DOI or working URL  
- [ ] “Submitted” or “in review” allowed if accessible to reviewers ([WES policy](https://www.wind-energy-science.net/submission.html#references))  
- [ ] BibTeX entries must compile with full initials (e.g. `J. A. W. Poland`)  
- [ ] Capitalise “van”, “de”, etc. if at start of entry  
- [ ] Ensure consistency with `macros.tex` vocabulary  

---

## 🧾 Reproducibility and FAIR data

- [ ] Provide DOIs for datasets, models, and code  
- [ ] Mention AI tool usage in Methods or Acknowledgements  
- [ ] Data in non-proprietary formats, metadata FAIR-aligned  
- [ ] Consistently reference datasets (Zenodo preferred over GitHub)  

---

## 📦 Miscellaneous

- [ ] Ensure only one `.tex` file in Overleaf (track changes handles edits)  
- [ ] Add Overleaf files:  
  - [ ] `letter_to_editor.txt`  
  - [ ] `reviewers.txt`  

---
