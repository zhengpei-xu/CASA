# CASA MRes Dissertation Template

## Structure
```
main.tex                  <- metadata + preamble, edit \newcommand block at top
frontmatter/              <- title page, abstract, declaration, acknowledgements, abbreviations
chapters/01-07            <- one file per chapter
appendices/               <- A: research log (required), B: supplementary
figures/                  <- all images (graphicspath is set)
references.bib            <- export from Zotero (Better BibTeX)
```

## Compile
latexmk / LaTeX Workshop handles this automatically. Manual order:
`pdflatex -> biber -> pdflatex -> pdflatex`

## Before submission checklist (from handbook)
- [ ] Word count updated in main.tex (10,000 target, 12,000 hard cap)
- [ ] Abstract under 300 words
- [ ] Statement of Ethics present in Methodology
- [ ] Research log appendix completed with supervision meeting dates
- [ ] Module code confirmed (CASA0004 / CASA0010 / CASA0012)
- [ ] All figures embedded, no interactive-only content
- [ ] Bibliography complete and consistent (everything cited appears, nothing superfluous)
- [ ] Deadline: 10am, 20 August, via Turnitin on Moodle
