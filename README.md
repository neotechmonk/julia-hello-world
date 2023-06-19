# Julia hello world

1. Installing on Mac
1. Setting up VS Code
1. Hello World


## Installing on Mac
Followed the instructions from [juliafordatascience.com](https://www.juliafordatascience.com/first-steps-1-installing-julia/)

Dowload the .dmg from [julialang.org](https://julialang.org/downloads/?ref=juliafordatascience.com) for your x86 or Apple Silicon Architecture

Double click the .dmg and drag into the Applications directory

If you plan to use REPL, its a good idea to add julia to your path

```
sudo rm -f /usr/local/bin/julia

sudo ln -s /Applications/Julia-[YOUR VERSION].app/Contents/Resources/julia/bin/julia /usr/local/bin/julia
```

Test out julia REPL by typing `julia` into your terminal

run ```print("julia")```

## Setting up VS Code
Install the extention _Julia_ 
More in this extension [here](julia-vscode.org)

## Hello World
check out ```hello.jl```