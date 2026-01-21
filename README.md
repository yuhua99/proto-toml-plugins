# proto-toml-plugins

Small collection of TOML plugins for `proto`.

## Plugins

- `neovim`: installs the `nvim` CLI from the official Neovim releases.

## Usage

Add the plugin by URL, then install the tool:

```sh
proto plugin add neovim "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/neovim/neovim.toml"
proto install neovim
```

## Layout

- `neovim/neovim.toml` contains the Neovim plugin definition.
