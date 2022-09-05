### 기본 프로그램

* Spectacle

  * https://www.spectacleapp.com/

* Keka

  * https://www.keka.io/ko/

### Homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### Download Iterm2

* https://iterm2.com/downloads/stable/latest

### Draculra Theme

* `git clone https://github.com/dracula/iterm.git`
* Activating theme
  1. *iTerm2 > Preferences > Profiles > Colors Tab*
  2. Open the *Color Presets...* drop-down in the bottom right corner
  3. Select *Import...* from the list
  4. Select the `Dracula.itermcolors` file
  5. Select the *Dracula* from *Color Presets...*

### Install pip

* `curl https://bootstrap.pypa.io/get-pip.py | python3`

### Oh My Zsh

* `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`


### Powerline

* `pip3 install powerline-status`
* `mkdir -p ~/bin/python3.8/bin`
* `ln -s ~/Library/Python/3.8/bin ~/bin/python3.8-bin`

### Tmux powerline

* `source "~/Library/Python/3.8/lib/python/site-packages/powerline/bindings/tmux/powerline.conf"`

### VIM

* Plug-in manager (vim-plug)

  `curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
      https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`

* `cp vimrc ~/.vimrc`
* `vi -> :PlugInstall`
