# Dotfiles (GNU Stow)

## Setup

Install GNU Stow:

```bash
sudo apt install stow
```

Clone the repository:

```bash
git clone git@github.com:Ankit-Patra/dotfiles.git
cd dotfiles
```
Apply all configurations using GNU Stow:

```bash
stow */
```

This will create symlinks for all packages into your home directory.
