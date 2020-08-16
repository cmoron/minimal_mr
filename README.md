minimal_mr
===

A minimalistic tool to launch git commands on multiple repositories.

Install
---
It's a bash script. Just put it in your $PATH (eg: $HOME/.local/bin for local install or /usr/local/bin for system wide install).

Usage
---
mr PATH <command>
Eg: mr $HOME/dev/ status 
Launches `git status` on every git repository under $HOME/dev directory.
