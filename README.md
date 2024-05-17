# Welcome to Julia!
This is a Julia tutorial.
<details>
<summary>Language</summary>

[English](https://github.com/hibiki-kato/Lecture_Julia)  
[日本語](https://github.com/hibiki-kato/Lecture_Julia_ja)
</details>

<a name="logo"/>
<div align="center">
<a href="https://julialang.org/" target="_blank">
<img src="src/assets/logo.svg" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>

# List of lessons

### If you want to run these codes in Google colaboratory, follow the introductions 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_Colab_Notebook_Template.ipynb)
| Lesson | summary | ja | en |
|:--------:|---|:----:|:----:|
| Lesson 1 | introduction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]() | |
| Lesson 2 | Variables and Data Types | | |
| Lesson 3 | Functions | | |
| Lesson 4 | Control Flow |  |  |
| Lesson 5 | Data Structure | |  |
| Lesson 6 | modules ||  |
| Lesson 7 | libraries ||  |


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
  <dd>Run this code to make your directory up to date.
      <li>Windows</li>
      <pre><code class="language-sh">> .\auto_pull\pull.ps1</code></pre>
      <li>macOS or Linux</li>
      <pre><code class="language-sh">$ zsh ./auto_pull/pull.sh</code></pre>
  </dd>
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
Then, press ```]``` and run the following command to install a package.
```sh
$ (@v1.10) pkg> add <packagename>
```
*e.g.* ```add PyPlot```

In this lesson, we use following packages
<dl>
  <li> PyPlot </li>
  <dd> Graph soft for visualising data.</dd>
  <li> IJulia </li>
  <dd> This enables us to use Julia in jupyter lab.</dd>
  <li> <a href="https://juliadynamics.github.io/DynamicalSystems.jl"> DynamicalSystems </a> </li>
  <dd> Powerful library for nonlinear dynamics and nonlinear timeseries analysis.
</dl>


