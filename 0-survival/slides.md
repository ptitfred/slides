!SLIDE
## Eviter les plus grosses boulettes

```bash
git config --global pull.rebase true
git config --global push.default nothing
```

!SLIDE
## Le cas échéant, les voir en couleurs

```bash
git config --global color.status true
git config --global color.diff true
git config --global color.ui true
```

!SLIDE
## Tout ne doit pas être versionné

```bash
touch .gitignore
```

Mais le mieux :

```bash
git config --global core.excludesfile /home/ptitfred/.gitignore
```

## Utilisez des templates

> https://github.com/github/gitignore

!SLIDE
## Git est dans l'esprit Unix

- N'oubliez pas les aliases!
- N'ayez pas peur de scripter

> use a proper shell

!SLIDE
## Git vous parle

- apprenez à lire
- au pire, changez la locale
