# Git-Dicas

![alt tag](http://i.imgur.com/q9Saz4s.jpg)

## Criando um repositório por linha de comando e fazendo um commit

```html
echo "# $REPOSITORIO" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/$USER/$REPOSITORIO.git
git push -u origin master
```

## Importando um repositório já criado por linha de comando

```html
git remote add origin https://github.com/$USER/$REPOSITORIO.git
git branch -M master
git push -u origin master
```

## Ignorando o .DS_Store do Mac definitivamente

```html
$ git config --global core.excludesfile ~/.gitignore
$ echo .DS_Store >>
~/.gitignore
```

## Autenticação por Token

[Autenticação Git por token](https://www.alura.com.br/artigos/nova-exigencia-do-git-de-autenticacao-por-token-o-que-e-o-que-devo-fazer)

## Github Markdown Syntax

[Markdown Cheat Sheet](https://enterprise.github.com/downloads/en/markdown-cheatsheet.pdf)
