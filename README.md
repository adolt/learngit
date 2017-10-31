# learngit
learn git

## 配置别名

### 常用配置
```
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
git config --global alias.unstage 'reset HEAD'
git config --global alias.last 'log -1'
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```

### 配置文件
每个仓库的Git配置文件都放在 **.git/config** 文件中

`--global` 全局配置在 **~/.gitconfig** 目录下
