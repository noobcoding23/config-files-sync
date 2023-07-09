# config-files-sync
Configuration files backup

### 1. Install zsh

#### a. For ubuntu
```
sudo apt install zsh
```

#### b. For Fedora
```
sudo dnf install zsh
```

### 3. Change the shell
```
chsh
```
and
```
/bin/zsh
```
#### ***For root use `sudo`

### 4. Install oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 5. Install zsh-autosuggestions

```
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions)
```

### 6. Install zsh-syntax-highlighting

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-hightlighting/zsh-synstax-hightlighting.zsh
```

### 7. Add this repository in your home directory in `.dotfiles` folder

```
git clone https://github.com/noobcoding23/config-files-sync.git ~/.dotfiles
```