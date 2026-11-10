# Supplementary Material

Supplementary Material for the article *A Systematic Review of Adaptive Artificial Intelligence Middleware for Quantum-Ready Smart Environments* (Darlan Noetzold, Jorge Luis Victória Barbosa, Juan Francisco de Paz Santana and Valderi Reis Quietinho Leithardt), submitted to ACM Computing Surveys.

## Contents

| File | Description |
|------|-------------|
| `supplement.pdf` | Compiled Supplementary Material (Tables S1–S3). |
| `supplement.tex` | LaTeX source of the Supplementary Material (acmart class, `manuscript` option). |
| `appendix_scope.tex` | Table S1 — study-level scope-compliance reassessment of the 74 included studies against the operational definitions of Section 3.2 of the main article. |
| `appendix_qa.tex` | Table S2 — study-level quality-appraisal scores under the nine-criterion rubric of Section 3.4 of the main article. |
| `taxonomy_index.tex` | Table S3 — study identifiers attached to each category of the four taxonomy figures (Figures 3–6 of the main article). |
| `sample-base.bib` | Bibliography shared with the main article. |
| `acmart.cls`, `ACM-Reference-Format.bst` | ACM class and bibliography style required for compilation. |

Study identifiers (A01–A74) follow Appendix A of the main article.

## Compilation

```
pdflatex supplement
bibtex supplement
pdflatex supplement
pdflatex supplement
```

## Citation

Noetzold, D., Barbosa, J. L. V., de Paz Santana, J. F., Leithardt, V. R. Q. Supplementary Material for "A Systematic Review of Adaptive Artificial Intelligence Middleware for Quantum-Ready Smart Environments". https://github.com/DarlanNoetzold/adaptive-ai-middleware-slr-supplement
