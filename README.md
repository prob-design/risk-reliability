# Risk and Reliability

This book was developed for and used in the master's program of the faculty of Civil and Environmental Engineering at Delft University of Technology in the Netherlands. Although the concepts are relevant for a wider audience outside the faculty, the generic reference "for Engineers" in the title refers to the diverse areas of emphasis evolving within the field historically referred to as "civil engineering." For example, our MSc programs in Environmental Engineerinng and Applied Earth Sciences.

This book is released under a CC-BY 4.0 license, and can be cited as:

> Lanzafame, R. (2024) _Risk and Reliability for Engineers_, TU Delft Open. https://doi.org/10.59490/tb.89.

The official published version of this book is available via the [TU Delft OPEN Interactive Textbooks platform](https://textbooks.open.tudelft.nl/textbooks/catalog/category/interactive) at [interactivetextbooks.tudelft.nl/risk-reliability](https://interactivetextbooks.tudelft.nl/risk-reliability/intro.html). However, additional preliminary material may also be available at [prob-design.github.io/risk-reliability](https://prob-design.github.io/risk-reliability/main/intro.html).

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

This book is created using open source tools from [TeachBooks](https://teachbooks.io/): it is a Jupyter Book that is written using Markdown, Jupyter notebooks and Python files to generate some figures. Contents of this book are written in the GitHub repository in the GitHub repository [`prob-design/risk-reliability`](https://github.com/prob-design/risk-reliability). The published version of this book is generated from a special branch, `publish-tud-open-textbook`, in a [public GitLab repository of TU Delft](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/). In short: edits are made in the Git*Hub* repository; the Git*Lab* repository is intented only to mirror and publish the book. 

### Setup

This book is built locally using a standard Python 3.11 virtual environment, created in directory `./.venv` from `requirements.txt`. A number of custom packages are used to facilitate interactive code pages, and other aspects related to the book build.

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