# Development Setup

- [Development Setup](#development-setup)
  - [Install](#install)
  - [VSCode settings](#vscode-settings)
    - [Nord](#nord)
    - [Conda Terminal](#conda-terminal)
  - [Git](#git)

Development setup for Jabez Wilson.

## Install

- Recommended VS Code extensions (mostly related to Python) of this repo
- [miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [git-scm](https://git-scm.com/download/win)

## VSCode settings

### Nord

```
"workbench.colorTheme": "Nord",
"workbench.colorCustomizations": {
    "notebook.cellEditorBackground": "#3b4252",
},
```

### Conda Terminal

```
  "python.terminal.activateEnvironment": true,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.profiles.windows": {
      "PowerShell": {
          "source": "PowerShell",
          "icon": "terminal-powershell",
          "python.terminal.executeInFileDir": true,
          "args": [
              "-NoLogo",
              "-ExecutionPolicy",
              "Bypass",
              "-NoExit",
              "-Command",
              "& 'C:\\Users\\JabezWilson\\miniconda3\\shell\\condabin\\conda-hook.ps1'",
              "; conda activate 'C:\\Users\\JabezWilson\\miniconda3'"
          ]
      },
  }
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