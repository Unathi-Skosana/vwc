## USAGE:

    notes [all|category]

## EXAMPLES:

    notes all
      compiles all in $WIKI_PATH
    notes category
      1) $WIKI_PATH/academics
      2) $WIKI_PATH/coding
      3) $WIKI_PATH/diary
      4) $WIKI_PATH/cheats
      5) $WIKI_PATH/books
      #? 2

      compiles notes in 2)

## Dependencies
* pandoc
* LaTeX
* ghostscript


## Explanation
This script is mostly based on [Conner McDaniel](https://github.com/connermcd)'s notes script.
If the The directory structure looks like

    /home/lynx/Dropbox/wiki
    ├── academics
    │  ├── group-theory
    │  ├── index.md
    │  ├── quantum-mechanics
    │  ├── ...
    ├── assets
    │  ├── fonts
    │  ├── fonts.tex
    │  └── markdown.css
    ├── books
    │  ├── antifragile.md
    │  ├── fooled-by-randomness.md
    │  ├── index.md
    │  └── ...
    ├── ...
    └── index.md

Images and other assets stored in the ``asssets`` dir of each corresponding folder
