# My dev tools

(source: https://www.youtube.com/watch?v=g5ECuNDkq4A)

## Update ubuntu

```shell
sudo apt update -y && sudo apt upgrade -y
```

## Install common utils

```shell
sudo apt install -y software-properties-common awk curl fc-cache mkdir mktemp unlink zip unzip wget
```

## Update ubuntu again

```shell
sudo apt updqate -y && sudo apt upgrade -y
```

## Install font JetBrains Mono

```shell
curl -fsSL https://raw.githubusercontent.com/JetBrains/JetBrainsMono/master/install_manual.sh | bash
```

## Install python latest

```shell
add-apt-repository -y ppa:deadsnakes/ppa
sudo apt update -y
sudo apt install -y python3 python3-dev python3-pip build-essential libssl-dev libffi-dev
sudo apt --only-upgrade install -y python3 python3-dev python3-pip build-essential libssl-dev libffi-dev
```

## Install nodejs

```shell
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash - &&\
sudo apt install -y nodejs npm
```

## install git

```shell
sudo apt install -y git
```

## install zsh

```shell
sudo apt install -y zsh fonts-powerline
```

## install oh-my-zsh

```shell
curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh | bash -s -- --unattended
```

## install alacritty

```shell
sudo add-apt-repository ppa:aslatter/ppa -y
sudo apt install -y alacritty
```

## install tmux

```shell
sudo apt install -y tmux
```

## install poetry

```shell
curl -sSL https://install.python-poetry.org | python3 -
```

## install fzf

```shell
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## install zoxide

```shell
curl -sS https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | bash
```

## install broot

```shell
wget -O ~/.local/bin/broot https://dystroy.org/broot/download/x86_64-linux/broot
chmod +x ~/.local/bin/broot
```

## install rtx

```shell
curl https://rtx.pub/install.sh | bash
```

