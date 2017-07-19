# Install
このレポジトリを ~/.config/tmux にクローンする.
```bash
cd ~/.config
git clone https://github.com/akagik/tmux.git tmux
```
.zshrc に以下の文を追記する.
```bash
alias tmux='tmux -f ~/.config/tmux/tmux.conf'
```
