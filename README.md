# git-commands

## GIT CONFIG
Serve para configurar variáveis e portanto comportamentos do git para  seu user de forma global ou local. 

Exemplo:

$ git config --list

user.email=e********@gmail.com
user.name=Edn************ *********8 **************
init.defaultbranch=main
core.editor=code --wait
alias.s=!git status -s
alias.c=!git add --all && git commit -m
alias.l=!git log --pretty=format:'%C(blue)%h %C(yellow)%d %C(red)%s - %C(white)%cn, %C(green)%cr'
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
remote.origin.url=git@github.com:Ed*******/estruturadedados-em-c.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main


git config --global --edit

Abre a tela do VI
