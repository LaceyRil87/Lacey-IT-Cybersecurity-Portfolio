# Bashrc PS1 and Shell Variables Lab (RHEL)

## Overview
This project documents a Red Hat Enterprise Linux lab focused on editing ~/.bashrc, customizing the Bash prompt using PS1, and practicing shell variables versus environment variables.

The goal was to
- Set a custom prompt using PS1
- Reload the shell configuration using source ~/.bashrc or by reconnecting with SSH
- Create and use a local shell variable in commands
- Export an environment variable

## Lab Objectives
- Edit ~/.bashrc using Vim
- Add a PS1 prompt string with a required trailing space
- Confirm prompt changes after reloading .bashrc
- Create a local variable and use it with ls and rm
- Export the EDITOR environment variable

## Key Concepts
```md
### Environment variable
An environment variable is exported so programs started from the shell can use it.

Example
```bash
export EDITOR=vim
echo $EDITOR

### Shell variable
A shell variable exists only in the current shell session.

Example
```bash
file=tmp.zdkei083
echo $file
