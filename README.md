# My Dotfiles

This directory contains the dotfiles required for the setup of my system

## Requirements

Ensure you have the following installed in your system

### Git

```
sudo apt install git-all
```

### Stow

```
sudo apt install stow
```

## Installation

First, checkout the dotfiles repo in your $HOME directory using git

```
git clone git@github.com:Theprashil/dotfiles.git
```

```
cd dotfiles
```

Then use GNU Stow to create symlinks

```
stow .
```


