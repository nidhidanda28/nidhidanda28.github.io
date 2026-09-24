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
cd nidhidanda28.github.io

2. Set up the Python Environment
(on bash, from the top level of the repository in your terminal)
uv sync

3. Set up R Environemnt
(in R console, from the top level of the repository)
renv::restore()

4. Render the site 
(from the top level of your repository, in your terminal)
uv run quarto render

## Built site location
The built site is located the '/docs' folder. The index.html file is where the site is stored, and can be opened in a browser or through your terminal (from the top level of your repository) using:
uv run quarto preview

## About the data
Both the R and Python sites are from the Palmer Penguins dataset through the 'palmerpenguins' package that is available for both Python and R.  
Data: Palmer Penguins (https://allisonhorst.github.io/palmerpenguins/)