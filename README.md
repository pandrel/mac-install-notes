# mac-install-notes

* Install iterm2
* Install homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
* Install git
```
brew install git
```


* Install Ohmyzsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
* Install fonts required by powerline10k

Download these four ttf files:

- [MesloLGS NF Regular.ttf](
    https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf)
- [MesloLGS NF Bold.ttf](
    https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf)
- [MesloLGS NF Italic.ttf](
    https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf)
- [MesloLGS NF Bold Italic.ttf](
    https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf)

Double-click on each file and click "Install". This will make `MesloLGS NF` font available to all
applications on your system.

* Install powerline10k theme for zsh
```
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc

```
* Restart iterm2 and follow instructions to set prompt
* Change iterm2 font to Monaco and non-ascii font to MesloLGS NF Regular

Tools
* Install awscli ```brew install awscli``` 
* Install miniconda ```brew install miniconda```
* Enable conda for zsh ``` conda init zsh```, Restart the terminal
* Install terraform ```brew install terraform```
* Install vscode, intellij and datagrip

*
* 
