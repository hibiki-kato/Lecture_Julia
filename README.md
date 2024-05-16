# Welcome to Julia!
This is a Julia tutorial.
<a name="logo"/>
<div align="center">
<a href="https://julialang.org/" target="_blank">
<img src="data/assets/logo.svg" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>

# List of lessons

### If you want to run these codes in Google colaboratory, follow the introductions 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_Colab_Notebook_Template.ipynb)
| Lesson | summary | ja | en |
|:--------:|---|:----:|:----:|
| Lesson 1 | introduction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() ||
| Lesson 2 | control flow |  |  |
| Lesson 3 | data structure | |  |
| Lesson 4 | modules ||  |
| Lesson 5 | libraries ||  |


# Directory tree

```
.
├── auto_pull
├── data
│   └── assets
└── src
    ├── en
    └── ja
```

<dl>
  <dt>auto_pull</dt>
  <dd>Run this code to make your directory up to date.</dd>
  <dt>data</dt>
  <dd>Store data files.</dd>
  <dt>src</dt>
  <dd>Source code directory.</dd>
</dl>


# How to install Julia?
Please check the [official website.](https://julialang.org/downloads/)

Please use [Juliaup](https://github.com/JuliaLang/juliaup), a Julia installer and version multiplexer.

```sh
# Windows
> winget install julia -s msstore

# macOS or Linux
$ curl curl -fsSL https://install.julialang.org | sh

# homebrew
$ brew install juliaup
```

Then, run
```sh
juliaup add <version>
```
to install a specific version of Julia. *e.g.* ```juliaup add 1.10```


# How to install packages?
Open the terminal, and run ```julia```. Interactive command line **REPL** is launched.

```sh
$ julia
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.10.3 (2024-04-30)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia>
```
Then, press ```]```. Then
```sh
$ (@v1.10) pkg> add <packagename>
```
- PyPlot 
- DynamicalSystems
- IJulia


