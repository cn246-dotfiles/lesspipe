## Less Dotfiles

This repo sets up dotfiles for `lesskey` and `lesspipe`

----

### Installing
- Create a hidden dotfiles directory:
```bash
mkdir -p "${HOME}/.dotfiles"
```

- Change directories:
```bash
cd "${HOME}/.dotfiles"
```

- Clone this repo
```bash
git clone git@github.com:cn246-dotfiles/less.git
```

- Stow the dotfiles:
```bash
stow --verbose --no-folding less
```

----

### Links
- https://manpages.debian.org/stable/less/lesskey.1.en.html
- https://github.com/wofr06/lesspipe
- https://www.gnu.org/software/stow/manual/stow.html
