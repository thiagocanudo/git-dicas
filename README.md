# git-dicas

=========

## Iniciando um novo repositório na linha de comando

```html
echo "# git-dicas" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/$USER/$REPOSITORIO.git
git push -u origin master
```

## Importando um repositório já criado

```html
git remote add origin https://github.com/thiagocanudo/git-dicas.git
git push -u origin master
```

## Excluindo o .DS_Store do Mac definitivamente do repositório

```html
$ git config --global core.excludesfile ~/.gitignore
$ echo .DS_Store >> ~/.gitignore
```

![https://git-scm.com/images/logos/2color-lightbg@2x.png)