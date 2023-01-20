# Development Setup

- [Development Setup](#development-setup)
  - [Install](#install)
  - [VSCode settings](#vscode-settings)
  - [Git](#git)

Development setup for Jabez Wilson.

## Install

- Recommended VS Code extensions (mostly related to Python) of this repo
- [miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [git-scm](https://git-scm.com/download/win)

## VSCode settings

Ensure you do the following for setting up the Nord theme

```
"workbench.colorTheme": "Nord",
"workbench.colorCustomizations": {
    "notebook.cellEditorBackground": "#3b4252",
},
```


## Git

```
git config --global user.name "Jabez Wilson"
git config --global user.email "jabez.wilson0@gmail.com"
git config --global core.editor "code --wait"
```

Get OpenSSH keys using

```
ssh-keygen -t ed25519
```