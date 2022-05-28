# vscode-enso

This is a vscode extension for [Enso](https://github.com/enso-org/enso) syntax highlighting, based off of [Kustosz's vim plugin](https://github.com/kustosz/vim-enso-syntax).



## Building

- Clone the repo
    `git clone https://github.com/mahsohn/vscode-enso`
    `cd vscod-enso`
- Install vsce
    `npm install -g vsce`
    `vsce package`

This should create a file enso-lang-x.x.x.vsix
## Installing

- Open vscode
- go to Extensions
- click `Install from VSIX...` in the menu
- select the generate vsix file
