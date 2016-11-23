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

* Install `zsh`, `git`, `tmux`, and `vim-full`

```
sudo apt-get install zsh git-core tmux vim
```

* Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) via `wget`

```
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

* Run the following script

```
run makesymlinks.sh
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
run makesymlinks.sh
```