# Sol Lee's dotfiles

author: [Cheng-Jen Lee](http://about.me/Sollee)

# Installation

## On Ubuntu

* Clone this repo to your home directory

```
git clone https://github.com/u10313335/dotfiles.git ~
```

* Remove the default `vim-tiny`

```
sudo apt-get remove vim-tiny
```

* Install `zsh`, `git`, `tmux`, and `neovim`

```
sudo apt-get install zsh git-core tmux neovim
```

* Install the required dependencies

```
sudo apt-get install python-dev python-pip python3-dev python3-pip curl vim exuberant-ctags git ack-grep
sudo pip install neovim pep8 flake8 pyflakes pylint isort
sudo pip3 install neovim pep8 flake8 pyflakes pylint isort
```

* Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) via `wget`

```
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

* Run the following script

```
~/dotfiles/makesymlinks.sh
```

## On macOS

* Clone this repo to your home directory

```
git clone https://github.com/u10313335/dotfiles.git ~
```

* Install `git` by trying to run git from the Terminal

* Install `zsh` and `tmux` via [homebrew](http://brew.sh/)

```
brew install zsh tmux
```

* Install oh-my-zsh via `curl`

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

* Run the following script

```
~/dotfiles/makesymlinks.sh
```
