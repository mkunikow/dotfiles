# My dotfiles

This directiory contains the dotfiles for my system

## Requiremnts

Ensure you have the following installed on your system

### Git
### Stow

### Installation

First, check out the dotfiles repo in your $HOME directory using git

```bash
$ git clone git@github.com/dreamsofautonomy/dotfiles.git
$ cd dotfiles
```

For Zsh install pllugin manager zinit
```bash
bash -c "$(curl --fail --show-error --silent --location https://raw.githubusercontent.com/zdharma-continuum/zinit/HEAD/scripts/install.sh)"
```

then use GNU stow to create symlinks

```
$ stow */
```
