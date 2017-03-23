# git-alias-lg
Alias for git log

Paste this line to [alias] section in file C:\\Users\\%userprofile%\\.gitconfig
```
lg = ! git log --pretty=format:\"%C(bold blue)%h%C(reset) - %C(bold cyan)%ad%C(reset) %C(bold green)%ar%C(reset)%C(bold yellow)%d%C(reset)%n          %C(white)%s%C(reset)%n          %C(dim white)- %an <%ae>%C(reset)\"
```
