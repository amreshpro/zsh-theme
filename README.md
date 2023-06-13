<h1 align="center">oh-my-zsh</h1>

![Imgur](https://i.imgur.com/SM441j1.png)

Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

Sounds boring. Let's try again.

**Oh My Zsh will not make you a 10x developer...but you may feel like one.**



### Install oh-my-zsh via curl

```bash

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

### Install oh-my-zsh via wget

```bash
sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```
### Manual Installation 

```sh
git clone https://github.com/ohmyzsh/ohmyzsh.git ~/.oh-my-zsh
```

## Use My Custom Theme - ```amresh.zsh-theme```

### amresh

![amresh](https://i.imgur.com/aT6Od6S.png)


### Installation

```sh
git clone https://github.com/amreshpro/zsh-theme.git    randomTestFolder
```
#### Go to ```randomTestFolder```

```sh 
cd /yourpath/randomTestFolder
```

#### Copy ```amresh.zsh-theme``` file in  ```~/.oh-my-zsh/themes/```

```sh
sudo cp  amresh.zsh-theme   ~/.oh-my-zsh/themes/
```

## Enabling Plugins & Change Themes

### Open and edit the ```.zshrc``` config file

### Open using Vs Code

```sh
code  ~/.zshrc
```
### Open using vim
```sh
vim  ~/.zshrc
```


### Change default theme to amresh theme

```sh
ZSH_THEME="robbyrussell" --> ZSH_THEME="amresh"
```

### now
```sh
ZSH_THEME="amresh"
```

#### Save the file and reopen your terminal

### your terminal look like this.

> How This Theme look in Vs Code

![amresh](https://i.imgur.com/SM441j1.png)
