# cdict
Linux shell script to colorize `dict` program output and pipe to the `less` pager.

## Introduction

`dict` is a handy command-line dictionary program.
However, it does not natively support colored output and paged display (e.g., using `less` or `more`).
This tiny script colorizes the output from `dict` to make its output more readable, marking the 
queried word, its pronounciation, and list of explanations using different colors.
It also pipes the `dict` output to a pager to facilitate browsing of the dictionary entry.

## Usage

Same as `dict`.
Use `man dict` command to browse manual for `dict`.
