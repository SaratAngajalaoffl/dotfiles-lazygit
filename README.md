# dotfiles-lazygit

Config for [lazygit](https://github.com/jesseduffield/lazygit).

Part of the [dotfiles-arch](https://github.com/SaratAngajalaoffl/dotfiles-arch) multi-repo dotfiles system.

## Layout

- `config/config.yml` → `~/.config/lazygit/config.yml` (see `.links`)
- Custom commands: `C` in the files panel runs `aic` (single-repo AI commit);
  `A` runs `aicp` (AI commits across every dirty submodule, then the parent).
  Both use `output: terminal` because they are interactive scripts.

## Setup

Not used standalone — applied by the parent repo's `install.sh`, which reads `.links` and symlinks `config.yml` into place.
