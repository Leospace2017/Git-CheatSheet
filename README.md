# Git Cheat Sheet

- git add . ``( . steht für Alles vorspeichern um commiten zu können oder einen Dateiname zunennen, um nur es zu speichern)``

- git commit -m "Nachricht" ``(Am Lokale Repo speichern um zu pushen) ``

- git push -u`` (auf remote Branch oder Main zu pushen -u heißt --set-upstream) `` 

- git checkout -b ``(-b heißt Branch checkout heit umschalten, hier heißt umschalten und neuen Branch erstellen(nach -b Branchname eingeben))``

- git pull ``(ist die Verschmelzung von git fetch und merge(fetch heißt vom remote das Inhalt kopieren und merge heißt zusammenfügen))``

- git branch -a ``(branch anzeigen oder erstellen -a wird das remote branch auch angezeigt)``

- git clone ``(hier wird links vom SSH oder HTTPS auf das Lokale kopiert)``

- git status / git show ``(git den detaillierte Status an)``

- git log ``(zeigt alle lokale gespeicherte commits an)``

- git revert ``(nimmt die Committverlaufswerte ein um wiederherzustellen) ``

- git diff ``vergleicht die Änderungen zum gestageten(comitteten) Inhalten ``

- git reset ``(nimmt die Vormerkungen zurück ohne es zu ändern)``

- git restore ``(ändert die dateien zum gespeicherten Punkten zurück)``

- git stash  ``(speichern stagen)``

- git config --global user.name/user.email ``(Konfiguriere user und Email für allen Lokalen Repos )``

- git switch ``(hier funktioniert wie git checkout kann zwischen die Branchen gewechselt werden)``

- git rm -r --cached ``(beim gitignore was falsches gemacht und die datein nochmals löschen)``

- touch .gitignore ``(erstellt dateien wo nicht hochgeladen sollen)``




## Install Git
[Git Installationsanleitung](https://github.com/git-guides/install-git)
## SSH Key einstellen
[Git SSHkey Anleitung](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)