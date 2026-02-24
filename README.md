## Встановлення Zsh та Oh My Zsh
```
Встановлення Zsh
sudo apt update && sudo apt install zsh -y

Зміна шелла на Zsh, після зміни треба ребутнути систему
chsh -s $(which zsh)

Встановлення Oh My Zsh
sh -c "$(curl -fsSL [https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh](https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh))"


```
## Встановлення плагінів
```
sudo apt install fzf -y

git clone [https://github.com/zsh-users/zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone [https://github.com/unixorn/fzf-zsh-plugin.git](https://github.com/unixorn/fzf-zsh-plugin.git) ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/fzf-zsh-plugin
```

## Активація конфігурації

```
cp .zshrc ~/.zshrc

source /usr/share/doc/fzf/examples/key-bindings.zsh
source ~/.zshrc

```

