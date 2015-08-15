dotfiles-manager
================

[![Build Status](https://travis-ci.org/ErikBjare/dotfiles-manager.svg)](https://travis-ci.org/ErikBjare/dotfiles-manager)

A nice script for managing your dotfiles.

> *Look again at that dot. That's here. That's home.*  
> \- Carl Sagan


## Usage
Just run `setup.sh` and everything will be symlinked to your home dir.  
If there are collisions with existing files they will be moved to `./backup/` by default. 
I plan to change this default in the future and introduce a flag which enables it. 
*(Always read through random scripts from the internets before executing)*


## Dependencies

 - git
 - bash


## Thanks to...
 - [Johan Bjäreholt](https://github.com/johan-bjareholt/) for his [dotfiles](https://github.com/johan-bjareholt/linux-configs) upon which this manager is based.
 - Everyone else from whom I stole!
