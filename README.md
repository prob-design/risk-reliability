# Risk and Reliability

This book was developed for and used in the master's program of the faculty of Civil and Environmental Engineering at Delft University of Technology in the Netherlands. Although the concepts are relevant for a wider audience outside the faculty, the generic reference "for Engineers" in the title refers to the diverse areas of emphasis evolving within the field historically referred to as "civil engineering." For example, our MSc programs in Environmental Engineerinng and Applied Earth Sciences.

There are three versions of this book available online:
1. A version bublished via the [Open Interactive Textbooks platform](https://textbooks.open.tudelft.nl/textbooks/catalog/category/interactive) of the TU Delft Library, built from the branch `publish-tud-open-textbook`: [interactivetextbooks.tudelft.nl/risk-reliability](https://interactivetextbooks.tudelft.nl/risk-reliability/intro.html)
2. An intermediate version shared with students, built from the branch `publish`: [interactivetextbooks.citg.tudelft.nl/risk-reliability](https://interactivetextbooks.citg.tudelft.nl/risk-reliability/intro.html)
3. A draft version for review by teachers (password protected), built from the branch `main`: [interactivetextbooks.citg.tudelft.nl/risk-reliability-draft](https://interactivetextbooks.citg.tudelft.nl/risk-reliability-draft/intro.html)

In addition, chapters of this book may be used in other courses and modules, either by direct linking, or including subsets of the book in another online textbooks (e.g., several chapters of this book are included in the [MUDE book](https://mude.citg.tudelft.nl/book/intro.html)).

This book is released under a CC-BY 4.0 license, and can be cited as:

> Lanzafame, R. (2024) _Risk and Reliability for Engineers_, TU Delft Open. https://doi.org/10.59490/tb.89.

As new material is added to the book, it will appear online first in sites 2 and 3, listed above. A final editing and copyright check takes place between the sharing of materials with students (site 2) and via the TU Delft Open website (site 1). For additional information visit the [Credits and License page](https://interactivetextbooks.tudelft.nl/risk-reliability/credits.html) in the book (or view the [source code](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/-/blob/main/book/credits.md?ref_type=heads)).

## Development History

This book is under constant development, and was:
- in part based on material that was previously part of the lecture notes for CIE4130 Probabilistic Design (last taught in 2022)
- initially created in a GitHub repository for use during 2 weeks in the MUDE Module (CEGM1000) during the 2022-23 academic year. This was mostly material from the old lecture notes, transcribed by Caspar Jungbacker
- used in MUDE book as a weekly chapter for 2023-24 academic year
- published via TU Delft Open in February, 2024 ([https://doi.org/10.59490/tb.89](https://doi.org/10.59490/tb.89))

The long-term goals for this book are:
- to serve as a general-purpose probabilistic design textbook for various modules in our MSc programs
- include Continuous Distribution and Extreme Value Analysis chapters from the MUDE book
- include expanded chapters on system, component reliability methods
- include more examples and exercises, especially using the interactive pages
- include an introduction to multivariate distributions that presents key theory, but is limited to illustrations of only 2 variables, based on dependence structures that use up to three variables

## Building and Editing the Book

This book is created using open source tools: it is a Jupyter Book that is written using Markdown, Jupyter notebooks and Python files to generate some figures. The files are stored on a [public GitLab repository of TU Delft](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/). The published versions of this book are compiled from special branches (see above).

### Setup

This book is built locally using a standard Python 3.11 virtual environment, created in directory `./.venv` from `requirements.txt`. A number of custom packages are used to facilitate interactive code pages, and other aspects related to the book build (see [TeachBooks website](https://interactivetextbooks.citg.tudelft.nl/) for more information). For example, a standard suite of packages is defined in [this repo](https://gitlab.tudelft.nl/interactivetextbooks-citg/extensions/tud-citg-jb-stack), including the Jupyter stack as well as common numerical libraries (e.g., numpy, scipy).

To activate and create the environment:

```
PATH_TO_YOUR/python -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt
```

### Figures

`./book/figures/` is from the original GitHub book where the figures subdirectory wase tentatively set up to facilitate figure creation during build. Some figures from previous versions of the book were generated from code in `./book/code/`. These files were left in place and a new subdirectory was created for generaring copyright-free figures to add prior to publishing in February, 2024: `./figures/`.

---

This book is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>

Two figures are excluded from the CC-BY license. For additional information visit the [Credits and License page](https://interactivetextbooks.tudelft.nl/risk-reliability/credits.html) in the book (or view the [source code](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/-/blob/main/book/credits.md?ref_type=heads))