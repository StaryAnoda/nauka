# GIT - Komendy #

`git reset --hard HEAD` \
`git reset --hard @` \
`HEAD = @` - To to samo. \
`git reset --hard @^^` - Dwa commity wcześniej. \
`git reset --hard @~2` - Dwa commity wcześniej. \
`^^^^^ = ~5` \
`git commit --amend` \
`git commit --amend --no-edit` \

`git checkout SHA -- file.txt` - Cofnij plik file.txt do rewizji SHA \
`git commit -m "TEST" -n` - Zrób commit z pominięciem pre commit hooka \
`git clone --depth=1 --branch NAME Repo-Link` - Klonuj repozytorium z jednym commitem. \
`git blame README.md` \
`git blame -L 1,5 README.md`