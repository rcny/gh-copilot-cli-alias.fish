# gh-copilot-cli-alias.fish

Installs the `gh copilot suggest` and `gh copilot explain` aliases as per [the official Configuring GitHub Copilot in the CLI documentation](https://docs.github.com/en/copilot/managing-copilot/configure-personal-settings/configuring-github-copilot-in-the-cli#setting-up-aliases), but for the Fish shell.

## Install via Fisher

```
fisher install rcny/gh-copilot-cli-alias.fish
```

## Manual install

Copy `conf.d/gh-copilot-cli-alias.fish` from this repository to your local `$__fish_config_dir/conf.d` directory.

## How to use

The aliases provided are `ghcs` and `ghce`, which behave in the same way as officially generated aliases for any supported shell.
