# 42 mastery

The 42 Abu Dhabi Data Science and Machine Learning branch. Each project lives in
its own repository and is linked here as a Git submodule.

## Projects

| Project | What it is | Status | Guide |
|---|---|---|---|
| [ft_linear_regression](https://github.com/myousaf64/ft_linear_regression) | Linear regression by gradient descent, pure standard library | Done | Done |
| [dslr](https://github.com/myousaf64/dslr) | One-vs-all logistic regression from scratch, ~98.7% accuracy | Done | Done |
| [multilayer-perceptron](https://github.com/myousaf64/multilayer-perceptron) | Feedforward network with hand-written backpropagation, ~99% accuracy | Done | TODO |
| [total-perspective-vortex](https://github.com/myousaf64/total-perspective-vortex) | EEG brain-computer interface, Common Spatial Patterns from scratch | Done | TODO |
| [Learn2Slither](https://github.com/myousaf64/Learn2Slither) | Q-learning Snake agent, reaches length ~29 | Done | TODO |
| [matrix](https://github.com/myousaf64/matrix) | Linear algebra from scratch, all 14 exercises | Done | Done |
| [computorv1](https://github.com/myousaf64/computorv1) | Polynomial equation solver, degree 2 and below (private) | Done | - |
| [computorv2](https://github.com/myousaf64/computorv2) | Interactive calculator: rationals, complex, matrices, functions | Core done | - |
| [py4DataScience-0-Starting](https://github.com/myousaf64/py4DataScience-0-Starting) | Python piscine, module 00 | Done | - |
| [42_Collaborative_resume](https://github.com/myousaf64/42_Collaborative_resume) | Collaborative resume and interview preparation (private) | Done | - |
| [Leaffliction](https://github.com/myousaf64/Leaffliction) | Leaf disease image classification | Not started | - |
| [piscineDataSci](https://github.com/myousaf64/piscineDataSci) | Data Science piscine work | Not started | - |

Every project is written without machine learning libraries unless the assignment
allows one. Each repository carries a `PROGRESS.md` development log alongside its
README.

## Guides

A guide is a single self-contained `GUIDE.html` at the root of the project it
covers. It explains the subject from first principles, walks through the code in
that repository, and prepares the oral defense: hidden-answer evaluation
questions, the traps that fail the review, and a live in-browser playground that
runs the real algorithm. Open it straight from the file system, no build step and
no network.

The three projects marked `TODO` above are next.

## Clone

```sh
git clone --recurse-submodules https://github.com/myousaf64/42-mastery.git
```

If you already cloned the repository:

```sh
git submodule update --init --recursive
```

To move every project to the latest commit on its `main` branch:

```sh
git submodule update --remote --merge
```

Two entries, `computorv1` and `42_Collaborative_resume`, are private repositories
and use SSH URLs. Without access, their submodules stay empty. The other ten clone
over HTTPS and need no credentials.
