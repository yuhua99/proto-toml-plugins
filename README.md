# proto-toml-plugins

Small collection of TOML plugins for `proto`.

## Plugins

- `bottom`: installs the `btm` CLI from the official bottom releases.
- `neovim`: installs the `nvim` CLI from the official Neovim releases.
- `ty`: installs the `ty` CLI from the Astral releases.

## Usage

Add the plugin by URL, then install the tool:

Use `--to global` if you want to install the plugin globally, for example:

```sh
proto plugin add --to global neovim "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/neovim/neovim.toml"
proto install -c global neovim "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/neovim/neovim.toml"
```

```sh
proto plugin add bottom "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/bottom/bottom.toml"
proto install bottom
```

```sh
proto plugin add neovim "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/neovim/neovim.toml"
proto install neovim
```

```sh
proto plugin add ty "https://raw.githubusercontent.com/yuhua99/proto-toml-plugins/refs/heads/main/ty/ty.toml"
proto install ty
```

