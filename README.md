# Dotfiles - managed by chezmoi

## Installation

The standard installation script installs at `./bin/`, so either navigate to your home directory to have it as a local only binary, or to the system root `/` to have it a folder in `$PATH`.

If you're on a machine which already has your git info in the global config:

`sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME`

Otherwise:

`sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply aviemet`
