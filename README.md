# dlang-digger-for-vscode
[![license](https://badgen.net/github/license/tom-tan/dlang-digger-for-vscode)](https://github.com/tom-tan/dlang-digger-for-vscode/blob/main/LICENSE)

# What is this?
A template to debug [D](https://dlang.org/https://dlang.org/) compiler and standard library with [Digger](https://github.com/CyberShadow/Digger) with [Visual Studio Code](https://code.visualstudio.com/) with [remote container](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

## How to use

- Clone this repository to your local machine.
- Open the cloned repository with remote container extension of VSCode.
- Have fun!
  - `digger build` uses `/workspaces/digger` for the default working directory

## What is provided in this template?
- [Digger](https://github.com/CyberShadow/Digger) with [default setting](https://github.com/tom-tan/dlang-digger-for-vscode/blob/main/digger.ini)
- Other tools to build [dmd](https://github.com/dlang/dmd), [druntime](https://github.com/dlang/drutime) and [phobos](https://github.com/dlang/phobos)
- D extension for remote container and its default setting
  - [D Language utility extension pack](https://marketplace.visualstudio.com/items?itemName=webfreak.dlang-bundle)
  - See [`devcontainer.json`](https://github.com/tom-tan/dlang-digger-for-vscode/blob/main/.devcontainer/devcontainer.json) for details

## License
This repository is licensed under CC0 (a.k.a. Public Domain).

Please fix [LICENSE](LICENSE) file when you create a new repository from this template.
