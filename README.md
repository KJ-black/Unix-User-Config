# Unix-User-Config
User configuration for me

## ZSH
- `sudo apt-get update`
- `sudo apt-get upgrade`
- `sudo apt install vim curl git`

### ZSH
- `sudo apt install zsh`
- check `cat /etc/shells`
- change login shell `chsh -s $(which zsh)`

### oh-my-zsh
- `wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh`
- `sh install.sh`

### powerlevel10k
- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
- Edit ~/.zshrc `ZSH_THEME="powerlevel10k/powerlevel10k"`
- `source ~/.zshrc`
- `p10k configure`
    - "diamond?" n
    - "lock" y
    - "fit between the crosses" y
    - 2 ASCII
    - 2 24-hour
    - 2 two lines
    - 1 disconnected
    - 2 Sparse
    - 1 Concise
    - y Yes
    - 1 Verbose

### Plugins
- zsh-completions
    - `git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:-${ZSH:-~/.oh-my-zsh}/custom}/plugins/zsh-completions`
- zsh-autosuggestions
- zsh-syntax-highlighting
- Add to ~/.zshrc 
- `source ~/.zshrc`
