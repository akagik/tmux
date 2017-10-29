# Install
このレポジトリを ~/.config/tmux にクローンする.
```bash
cd ~/.config
git clone https://github.com/akagik/tmux.git tmux
```
~/.tmux.conf を以下のように編集する.

```bash
source-file ~/.config/tmux/tmux.conf
```

# Requires
Mac では reattach-to-user-namespace を入れる
```bash
brew install reattach-to-user-namespace
```
