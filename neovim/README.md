# @neovim/proto-plugin

TOML plugin for installing Neovim with `proto`.

## Install

```sh
proto plugin add neovim "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/neovim/neovim.toml"
proto install neovim
```

## What it does

- Fetches releases from `https://github.com/neovim/neovim`.
- Installs `nvim` as the primary executable.
- Supports Linux, macOS, and Windows (x86_64).
