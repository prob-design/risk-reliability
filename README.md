# Risk and Reliability

% start copy: intro page
This book was developed and used for use in the master's program in the faculty of Civil and Environmental Engineering at Delft University of Technology in the Netherlands. Although the concepts are relevant for a wider audience outside the faculty, the generic reference "for Engineers" in the title refers to the diverse areas of emphasis evolving within the field historically referred to as "civil engineering." For example, our MSc programs in Environmental Engineerinng and Applied Earth Sciences.
% end copy

There are three versions of this book available online:
1. Published via the TU Delft Library **LINK**
2. An intermediate version shared with students
3. A draft version for review by teachers (password protected)

In addition, chapters of this book may be used in other courses and modules, either by direct linking, or including subsets of the book in another online textbooks (e.g., several chapters of this book are included in the [MUDE book](https://mude.citg.tudelft.nl/book/intro.html)).

View the Credits and License page in the book (**LINK XXX**) or [source code](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/-/blob/main/book/credits.md?ref_type=heads) for additional information.

## Development History

This book is under constant development, and was:
- in part based on material that was previously part of the lecture notes for CIE4130 Probabilistic Design (last taught in 2022)
- initially created in a GitHub repository for use during 2 weeks in the MUDE Module (CEGM1000) during the 2022-23 academic year. This was mostly transcribed material from the old lecture notes by Caspar Jungbacker
- used in MUDE book as a weekly chapter for 2023-24 academic year
- published via TU Delft Library in February, 2024

This book will eventually:
- serve as a general-purpose probabilistic design textbook for various modules in our MSc programs
- include EVA chapters from MUDE
- include system, component reliability methods

## Building and Editing the Book

% start copy: intro page
This book is created using open source tools: it is a Jupyter Book that is written using Markdown, Jupyter notebooks and Python files to generate some figures. The files are stored on a [public GitLab repository of TU Delft](https://gitlab.tudelft.nl/interactivetextbooks-citg/risk-and-reliability/). The published version of this book is compiled from a special branch (`xxxxxxxx`). View the repository README file or contact the author for additional information.
% end copy

### Setup

Using Python venv, created in directory `.venv`.

Note that `requirements.txt` includes a suite of files defined in [this repo](https://gitlab.tudelft.nl/interactivetextbooks-citg/extensions/tud-citg-jb-stack), including the Jupyter stack as well as common numerical libraries (e.g., numpy, scipy).

```
PATH_TO_YOUR/python -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt
```

### Figures

`./book/figures/` is from the original GitHub book where the figures were tentatively set up to facilitate creation during build. Left alone for now.

A new directory is created for figures to add prior to publishing in February, 2024: `./figures/`.

---

This book is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>

Two figures are not included in the license (see Credits page of textbook for explanation).