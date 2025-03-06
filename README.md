# Guide

On a Linux machine, run `docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive xelatex resume.tex` in this directory.

If running on a Windows machine with WSL2 installed, navigate to this directory by running `cd /mnt/c/Users/zhiyu/{path_to_directory}` before running the above command.

Works on ARM64 devices too.
