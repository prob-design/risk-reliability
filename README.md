# Risk and Reliability

This book is:
- initially created in a GH repo for the 2022-23 academic year. Mostly transcribed from old lecture notes by Caspar Jungbacker
- used in MUDE book as a weekly chapter for 2023-24 academic year
- being prepared for publication with TUD library Feb 2024
- a work in progress

This book will:
- serve as a general-purpose probabilistic design textbook for various modules in our MSc programs
- include EVA from MUDE
- include system, component reliability methods
- be useful :)

## Setup

Using Python venv, created in directory `.venv`.

Note that `requirements.txt` includes a suite of files defined in [this repo](https://gitlab.tudelft.nl/interactivetextbooks-citg/extensions/tud-citg-jb-stack), including the Jupyter stack as well as common numerical libraries (e.g., numpy, scipy).

```
PATH_TO_YOUR/python -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt
```