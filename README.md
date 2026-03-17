# My dotfiles

## Deploy

### Quick Setup

Run the deployment script to install all tools and configure symlinks:

```shell
bin/upgrade-all
```

The script is idempotent - you can run it multiple times safely. It will:

* Install/update Homebrew packages
* Set up zsh configuration sourcing
* Create configuration symlinks (tmux, claude)
* Skip already installed packages

### Manual Homebrew Installation

If you need to install Homebrew manually:

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


## Reference

- [David Chen](https://github.com/theniceboy/.config)
