# Rifamycins — Lecture Package

Postgraduate ID lecture (~1 hour) on the rifamycin class: rifampin, rifabutin, rifapentine, and rifaximin.

Built from *Mandell, Douglas, and Bennett's Principles and Practice of Infectious Diseases*, Chapter 26 "Rifamycins" (Sterling & Portal-Celhay), via the `lecture-builder` skill.

## Contents

- `rifamycins-slides.qmd` — RevealJS deck (53 content slides + 8 section dividers; speaker notes throughout)
- `rifamycins-webpage.qmd` — HTML lecture-notes page (full chapter content, tables, callouts)
- `rifamycins-references.bib` — 71 BibTeX entries; landmark trials verified against PubMed
- `rifamycins-images/` — institutional logo (`DMM_newlogo.png`)
- `custom.scss`, `diagnostic-microbiology-and-infectious-disease.csl`, `_extensions/fontawesome/` — rendering dependencies

## Audience & emphasis

Postgraduate ID specialists — deeper pharmacology, resistance, and clinical decision-making (especially *when to add rifampin, and when not to*).

## To render

```
quarto render rifamycins-slides.qmd
quarto render rifamycins-webpage.qmd
```

Quarto was not available in the build sandbox, so a first render in RStudio/Quarto locally is recommended to confirm layout.

## Notes / to verify

- Chapter references 263–268 (investigational agents) were not captured cleanly in the source OCR. Entries `@TNP2092` and `@TNP2198` are marked `INCOMPLETE` in the `.bib` — verify volume/pages/DOI before publishing.
- Two `<!-- IMAGE NEEDED -->` placeholders in the slides/webpage (ansamycin scaffold; RNAP-binding schematic). Source figures are copyrighted; redraw rather than reproduce.
