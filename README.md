# Math

> Self-directed study of the mathematics and programming I need for a graduate computational neuroscience PhD. Background: MBBS (medicine). Everything here is my own work: handwritten notes, problem-set attempts, and Python implementations.

## Goal

Build a rigorous quantitative foundation (calculus, linear algebra, differential equations, probability and statistics), and apply it in independent computational neuroscience projects.

## How I study each topic

1. Watch lectures and read the notes; make **handwritten notes**.
2. Attempt the **problem sets and exams** myself before looking at solutions.
3. Re-implement key ideas in **Python** (Jupyter notebooks) and connect them to neuroscience where possible.
4. Write a short **reflection**: what was hard, what I got wrong, what clicked.


## Featured projects

Separate repositories for independent work:

- _Coming soon:_ Leaky integrate-and-fire neuron from scratch
- _Coming soon:_ Tuning-curve fitting with least squares

## Repository layout

```
.
├── README.md
├── environment.yml
├── 18.02-multivariable-calculus/
│   └── 02-partial-derivatives/
│       └── A-functions-of-two-variables/
│           ├── notes/          # scanned handwritten notes (PDF)
│           ├── problem-sets/   # my own attempts (PDF)
│           ├── notebooks/      # Python implementations
│           └── reflection.md
└── ...
```

## Setup

```bash
conda env create -f environment.yml
conda activate math-neuro
jupyter lab
```

## Credits and licensing

Course materials (lectures, problem sets, official solutions) belong to MIT OpenCourseWare and are licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). They are **not** reproduced here; I link to them. The notes, attempts, and code in this repository are my own.

Code: MIT License. Notes: CC BY 4.0.
