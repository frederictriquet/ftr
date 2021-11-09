.gitconfig
```
[filter "lfs"]
	smudge = git-lfs smudge -- %f
	process = git-lfs filter-process
	required = true
	clean = git-lfs clean -- %f
[pull]
	rebase = true

[includeIf "gitdir:~/Dev/"]
path = ~/Dev/.gitconfig.pro

[includeIf "gitdir:~/DevPerso/"]
path = ~/DevPerso/.gitconfig.perso
```

.gitconfig.perso
```
[user]
email = xxxx
name = my name

[github]
user = "my personnal account"

[core]
sshCommand = "ssh -i ~/.ssh/somesshkey"
```

.gitconfig.pro
```
[user]
email = yyyy
name = my name

[github]
user = "my pro account"

[core]
sshCommand = "ssh -i ~/.ssh/othersshkey"
```

