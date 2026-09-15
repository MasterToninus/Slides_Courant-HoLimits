# Canonical L-infinity morphisms and homotopy fibers in higher Courant geometry

Beamer source for the 60-minute talk

> **Canonical L-infinity morphisms and homotopy fibers in higher Courant geometry: from twisted algebroids to higher Dirac structures**

presented at the **Geometry, Topology, and Physics (GPT) Seminar** on
September 16, 2026, at 17:00 GST (GMT+4).

## Mathematical content

The main part of the talk is based on joint work with Domenico Fiorenza:

- [D. Fiorenza and A. M. Miti, *L-infinity morphisms between twisted Courant r-Lie algebras and untwisted Courant (r+1)-Lie algebroids*, arXiv:2602.14702](https://arxiv.org/abs/2602.14702).

It covers:

- the homotopy-fiber model for higher Courant L-infinity algebras;
- the canonical morphism from a twisted Courant algebra of degree `r-1` to the untwisted Courant algebra of degree `r`;
- the homotopical interpretation of the morphism from multisymplectic observables to the corresponding higher Courant algebra.

The final section presents ongoing work with Aditya Basu and Domenico Fiorenza on extending this perspective from graphs of closed forms to general higher Dirac structures. Statements in this section are explicitly marked as ongoing work.

## Repository structure

- `main.tex`: main Beamer file;
- `HoLim-intro.tex`: motivation and roadmap;
- `HoLim-background.tex`: higher Courant algebras and homotopy fibers;
- `HoLim-NewMorphism.tex`: results of arXiv:2602.14702;
- `HoLim-DiracOutlook.tex`: ongoing work on higher Dirac structures;
- `HoLim-complementary-material.tex`: backup slides;
- `HoLim-aknowledgements.tex`: bibliography and acknowledgements;
- `Pictures/`: standalone TikZ figures;
- `bibfile.bib`: bibliography;
- `math.sty`, `custom-style.sty`, `beamerthemetoninus.sty`: macros and theme.

## Compilation

Compile the presentation with:

```bash
latexmk -pdf main.tex
```

or manually with:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

The source uses standard Beamer, TikZ, `tikz-cd`, `standalone`, `mathalfa`, and related LaTeX packages. On Debian or Ubuntu, the packages are available through a sufficiently complete TeX Live installation.

The default build is the live presentation. Set `\Handouttrue` near the beginning of `main.tex` to obtain the printable version with notes.

## Earlier version

The repository history preserves the version used for the 2025 talk *A canonical morphism between twisted and untwisted higher Courant L-infinity algebras*.

## License

GNU General Public License v3.0.

Copyright Antonio Michele Miti, 2025-2026.
