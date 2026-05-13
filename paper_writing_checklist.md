# 📋 Checklist

A structured checklist for preparing and polishing scientific works. If you would like to use this checklist to tick off boxes, you can copy this into any markdown editor that supports this, e.g., Notion or Obsidian. Another option is to create an Issue in any repository (perhaps your project repo), where inside the Issue environment, GitHub allows you to tick off boxes in the browser.

---

- [ ] Write in British English  

## ✒️ Style & formatting policy

**Symbols**
- [ ] Consistent across manuscript (can use AI to point you towards inconsistencies)
- [ ] Scalars → italic lowercase (e.g. u: $u$)  
- [ ] Vectors → bold italic lowercase (e.g. \mathbf{u}: $\mathbf{u}$)  
- [ ] Matrices / second-order [tensor](https://en.wikipedia.org/wiki/Tensor) / [dyadics](https://en.wikipedia.org/wiki/Dyadics) → bold upright uppercase (e.g. \mathbf{U}: $\mathbf{U}$) 
    or bold if Greek (e.g. \boldsymbol{\tau}: $\boldsymbol{\tau}$)  
- [ ] Unit vectors → always \mathbf{e}: $\mathbf{e}$ (never hatted symbols)  although  $\mathbf{n}$ is also okay
- [ ] Vector magnitudes → italic lowercase, because they are scalars
- [ ] Never introduce new symbols in brackets; brackets only for abbreviations (e.g. Virtual wind tunnel (VWT), the density $\rho$)
- [ ] Non-dimensional numbers, e.g. Reynolds number R and Mach M, should be written in upright roman → \textrm{R}: $\textrm{R}$ & \textrm{M}: $\textrm{M}$
- [ ] Transpose operater → ^\top: $^\top$


**Abbreviations**
- [ ] Only capitalise names: airborne wind energy (AWE), Reynolds-averaged Navier–Stokes (RANS) ([AJE reference](https://www.aje.com/arc/editing-tip-capitalization-when-defining-abbreviations/))  
    
**Subscripts and indices**
- [ ] Variables/iterative indices → italic (e.g. x_i: $x_i$ and u_x: $u_x$)  
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
- [ ] Trigonometry functions always in upright roman font


**Terminology**
  - [ ] Always write “TU Delft V3 kite” or “V3 kite” (never just “V3”)  
  - [ ] Aerodynamic coefficients → lowercase ($C_{\mathrm{l}}, C_{\mathrm{d}}, C_{\mathrm{s}}$) for 2D; uppercase ($C_{\mathrm{L}}, C_{\mathrm{D}}, C_{\mathrm{S}}$) for 3D  
  - [ ] Reynolds number as \textrm{Re} → $\textrm{Re}$
  - [ ] Upright $d$, not italic


**Sections and titles**  
- [ ] First letter capitalised, rest lowercase  
- [ ] Number up to three levels (e.g. 3, 3.1, 3.1.1)  
- [ ] Use “Sect.” in running text (unless at sentence start
- [ ] No abbreviations in titles

**Citations**
- [ ] `\citep{}` for (Schmehl et al., 2023)  
- [ ] `\cite{}` for Schmehl et al. (2023)  

**Textual style**  
- [ ] Use British English  
- [ ] Oxford comma always  
- [ ] Past tense for work done, results, observations  
- [ ] Present tense for general truths, established knowledge  
- [ ] Future tense for outlooks, perspectives
- [ ] Try to limit the use of the word "enables". In native scientific English, “facilitates” (or sometimes “allows for”, “makes possible”, “permits”) is generally more idiomatic than “enables”, which can feel like a calque from German ermöglicht or Dutch maakt mogelijk.
- [ ] "Statements about equations should be in the present as these are timeless." When describing a timeless fact of some sort, you have to use the present. [Present tense: General truths and atemporal facts](https://www.nature.com/scitable/topicpage/effective-writing-13815989/)  

---

## 📊 Figures, tables, and data

- [ ] Table captions must be placed **above** the table.  
- [ ] Figure captions must be placed **below** the figure.  
- [ ] Captions must not start with “(A)” or “The”; they should start descriptively instead.
      Not: "The velocity standard deviations..", instead write: "Velocity standard deviations.."    
- [ ] Tables must be black-and-white with meaningful captions; no colour fill.  
- [ ] Panels in multi-part figures labelled (a), (b), etc., lowercase in parentheses.  
- [ ] Use **Sect.** in running text (unless at the beginning of a sentence).  
- [ ] Use **Eq.** and **Fig.** for equation/figure references (unless at sentence start).  
- [ ] Always capitalise “Table” when numbered, never abbreviate.  
- [ ] Figures must always be referenced by label (e.g. “see Fig. \ref{fig:example}”), never by position.
- [ ] No bold usage in tables
- [ ] For WES/Copernicus standards, a caption must: Define all symbols appearing in it.
- [ ] Be descriptive rather than narrative.
---

## 📄 Manuscript structure and content

**Referring to Faculty**
- [ ] Should be: "Faculty of Aerospace Engineering, Delft University of Technology, 2629 HS Delft, The Netherlands"

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

## 📚 Bibliography

- [ ] **Completeness of entries**
  - Every reference must include: `author`, `title`, `journal`/`booktitle`/`institution`, `year`.
  - Add `volume`, `number`, `pages` if available.
  - Always provide `doi` **and** `url` if possible.
  - Ensure `publisher` and `address` are included for books and reports.

- [ ] **Author names**
  - Use full last names, initials separated by spaces → `J. A. W. Poland`, not `J.A.W. Poland`.
  - Keep accents in names (e.g. *Raphaël*, *Viré*).
  - Capitalise *van*, *de*, etc. **only** when at the start of a reference list entry.
  - Multiple authors joined with “and” (BibTeX requirement).
  - No all-caps names (e.g. `PRANDTL1918` should be `Prandtl1918`).

- [ ] **Titles**
  - Sentence case for article, report, and book chapter titles (only proper nouns capitalised).
  - For journals and book series → keep official title capitalisation (e.g. *Journal of Physics: Conference Series*).
  - Conference series names in braces `{IFAC}` etc. to preserve capitalisation.

- [ ] **Journals, Books, Reports**
  - Journal names written in full (no abbreviations unless required by publisher).
  - Books → include `edition`, `publisher`, `address`, and `isbn` if available.
  - Technical reports → include `institution`, `number`, and `address`.
  - In-collection chapters → include `editor`, `booktitle`, `publisher`, and `pages`.

- [ ] **Special cases**
  - “Submitted”, “in review”, “in preparation” allowed if available to reviewers (WES policy).  
    Example: `Poland2025a` entry should include `[in preparation]` in the title.
  - Classic works without DOI must include a stable URL (e.g. `Prandtl1918` → `http://eudml.org/doc/59036`).
  - Historical reports without DOI → at least `institution` and year (e.g. `Batchelor1944`, `Gent1944`).

- [ ] **DOI and URL formatting**
  - DOI always in form: `doi = {10.1088/1742-6596/1618/3/032007}`, no prefix `https://doi.org/`.
  - If only URL is available, ensure it is a stable link (avoid institutional proxies).
  - Do not include both `doi` and `url` if the URL is just the DOI link.

- [ ] **Consistency checks**
  - Use consistent key naming → `SurnameYear` or `SurnameYear[a/b]` for duplicates.
  - Avoid capitalisation inconsistencies in citation keys (`Prandtl1918` not `PRANDTL1918`).
  - Ensure all references compile with BibTeX and match journal requirements.
  - Match symbol and terminology conventions in `macros.tex` (e.g. $C_{\mathrm{L}}$ not CL in titles).

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
- [ ] "If you help with writing the manuscript, then, and only then, should you be a co-author." Just being the author of a code that is used is not sufficient for being a co-author.
- [ ] nonlinear, not non-linear

---
