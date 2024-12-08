# Introduction to Julia for Python Scientists

This is the material used in the workshop "Introduction to Julia for Python Scientists" at Barcelona Supercomputing Center (BSC-CNS) on the 10th of December of 2024.

## Setup

### Clone this repository

```bash
git clone https://github.com/bsc-quantic/intro-to-julia-for-python-scientists
```

### Install Juliaup

Juliaup is a Julia version manager and the recommended way of installing Julia.
You should follow the instructions in [Julia's Manual > Installation](https://docs.julialang.org/en/v1/manual/installation/), but I'm putting them here too for speed.

#### Windows

You can directly install it from the Windows store [here](https://www.microsoft.com/store/apps/9NJNWW8PVKMN), or can you can also install in by running the following command in a terminal:

```powershell
winget install julia -s msstore
```

#### macOS

If you use Homebrew, then run

```bash
brew install juliaup
```

If not, you ~~should install Homebrew~~ can follow the Linux instructions.

#### Linux

> [!WARNING]
> If you use Ubuntu/Debian, **don't install julia using `apt` / `apt-get`**.
> They don't ship Juliaup but a really old version of Julia.

Run the following command in a terminal:

```bash
curl -fsSL https://install.julialang.org | sh
```

### Install Visual Studio Code (VSCode)

VSCode is the recommended text editor for programming in Julia.
You can code in other text editors / IDEs but the VSCode is the one with the best support and the one that we will be using in this workshop.

#### Install the Julia extension for VSCode

Go to [https://marketplace.visualstudio.com/items?itemName=julialang.language-julia](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia) and click install, or search for the same extension in the "Extensions" panel.

## Where to go from here

### Community

- [Official website](https://julialang.org)
- [Slack](https://julialang.org/slack/)
- [Discourse](https://discourse.julialang.org/)
- [YouTube](https://www.youtube.com/user/JuliaLanguage)

### Courses

- [Official Manual's "Getting Started" section](https://docs.julialang.org/en/v1/manual/getting-started/)
- [MIT's Introduction to Computational Thinking (Fall 2024)](https://computationalthinking.mit.edu/Fall24/) 
  - Very recommended!
  - Has Image Processing, Data Science and Climate Science tracks
- [Julia Academy](https://juliaacademy.com/courses)
- [Exercism](https://exercism.org/tracks/julia)
- [From zero to Julia!](https://techytok.com/from-zero-to-julia/)

### Other resources

- [Resources from JuliaParallel](https://juliaparallel.org/resources/)
