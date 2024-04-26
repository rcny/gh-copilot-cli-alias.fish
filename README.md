# gh-copilot-cli-alias.fish

Installs the `gh copilot suggest` and `gh copilot explain` aliases as per the official GitHub Copilot in the CLI documentation, but for the Fish shell as it's not natively supported by the upstream.

## Install via fisher

```fish
fisher install rcny/gh-copilot-cli-alias.fish
```

## Manual install

Copy `conf.d/gh-copilot-cli-alias.fish` from this repository to your local `$__fish_config_dir/conf.d` directory.

## How to use

The aliases provided are `ghcs` and `ghce`, which behave in the same way as officially generated aliases for any supported shell.