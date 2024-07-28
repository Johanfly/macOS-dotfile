## Personal dot file manage w/ chezmoi

**Install Homebrew**

```bash
xcode-select --install
```

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


**Brew file**

```bash
cd ~/
git clone https://github.com/Johanfly/macOS-dotfile.git
brew bundle install --file=~/Source/Brewfile
```

| Add | link |
|----|----|
| manager | [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) |
| plugin | [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) |
| Metasploit-framework Nightly | [Installing](https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html) |


**Chezmoi**

```bash
chezmoi init https://github.com/Johanfly/macOS-dotfile.git
chezmoi update -v
chezmoi apply -v
```


**Ruby**

```bash
gpg --keyserver keyserver.ubuntu.com --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

```bash
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```


