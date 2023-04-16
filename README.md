# git alias
Repositorio con todos los alias que he ido creando, para que si cambio de ordenador pueda volver a crearlos y volver a usarlos

## tree
git config --global alias.tree "log --graph --oneline --decorate"

## code
git config --global alias.code "!code"

## alias
git config --global alias.alias "config --get-regexp ^alias\."

## rank
git config --global alias.rank "shortlog -sn --no-merges"

## branches
git config --global alias.branches "branch \
--format='%(color:yellow)%(refname:short)%(color:reset) - \
%(contents:subject) %(color:green)(%(committerdate:relative)) \
[%(authorname)]' --sort=-committerdate"
