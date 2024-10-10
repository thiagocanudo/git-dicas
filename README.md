# git-dicas

=========

![alt tag](http://i.imgur.com/q9Saz4s.jpg)

## Criando um README iniciando o repositório e fazendo um Commit 

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
git init
git remote add origin https://github.com/$USER/$REPOSITORIO.git
git pull -u origin master
```

## Ignorando o .DS_Store do Mac definitivamente

```html
$ git config --global core.excludesfile ~/.gitignore
$ echo .DS_Store >> ~/.gitignore
```

