# ndanda.github.io

# Nidhi's Repository (ndanda.github.io)
Welcome to my repository! 

This repository contains a website I built with Quarto. 
It contains two blog posts that analyse the Palmer Penguins dataset, one in R and one in Python. 
R: Relationship between bill depth and bill length. 
Python: Relationship between body mass and flipper length. 

## Installation Requirements
Quarto: https://quarto.org -> version 1.10.18
uv: https://docs.astral.sh/uv/ -> version 0.12.6
R: https://www.r-project.org/ -> version 4.6.1

renv bootstraps itself - no seperate installation required.

## Build Instructions
1. Clone the repository: 
(on bash)
git clone git@github.com:nidhidanda28/nidhidanda28.github.io.git
cd nidhidanda28.github.io.git

2. Set up the Python Environment
(on bash, from the top level of the repository in your terminal)
uv sync

3. Set up R Environemnt
(in R console, from the top level of the repository)
renv::restore()

4. Render the site 
(from the top level of your repostory, in your terminal)
uv run quarto render



## Where the built site lands

## Where the data comes from