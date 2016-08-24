#Archwiki

[Git](https://wiki.archlinux.org/index.php/git)


##bruger
`emilbk`

`emilboel@gmail.com`

saet op med

`git config --gloabl user.name *bruger*`

`git config --global user.email *email*`

## Staging
###init
```
cd /mappe/
git init
```

###tilfoej fil
`git add *fil*`

###tilfoej alle filer
`git add .`

###ignorer fil
tilfoej .gitignore fil

[man](http://git-scm.com/docs/gitignore)

###fjern fil
`git rm (--cached) fil1`

--cached gemmer lokal fil

###commit
`git commit -m "besked"`

-m tilfoejer besked

###sammenlign
mellem to commits

`git diff HEAD HEAD~3`

mellem staging og working tree

`git diff`

overblik

`git status`

historie (-N er antal seneste commits)

`git log -p (-N)`


nb - `HEAD` er den nyeste commit. `Head` plus `~` referer til tidligere, med numerisk vaerdi.
