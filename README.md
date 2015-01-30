# Dotfile Windows (PowerShell)

* [ConEmu](https://code.google.com/p/conemu-maximus5/) 
* [Posh-GIT](https://github.com/dahlbyk/posh-git)


```
> git clone git@github.com:dukex/dotfiles-win.git ~/src/dotfiles-win
```


Edit your ~/.gitconfig

```
[user]
	email = YOURGITEMAIL
	name = YOURNAME

[include]
  path = ~/src/dotfiles-win/gitconfig

```

Open your profile file with ```notepad $PROFILE``` and append the follow line

```
. 'C:\Users\MYNAME\src\Alias.ps1'
``` 