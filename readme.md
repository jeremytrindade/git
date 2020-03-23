# O que deve ser feito:
## Para configurar dados do utilizador

- git config --global user.name "nome de utilizador"
- git config --global user.email "email@email.com"

## Relativamente a ativar um projeto no computador
Para começar devemos escrever:
- git init
- - Serve para iniciar um projeto
- git add
- - Serve para adicionar um documento
- git add . ou git add *
- - Serve para adicionar todos os documentos
- git status
- - Serve para ver como estão os documentos
- git commit
- - Serve para fazer um commit com o editor previamente definido, por exemplo com o VSCode
- git commit -m "Neste podemos fazer um simples commit"
- git commit -am "neste commit da para adicionar tudo e fazer o commit ao mesmo tempo"

## Criar novo repositorio
- echo "# git" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/USERNAME/REPOSITORIO.git
- git push -u origin master

## Se já tiver repositorio local
- git remote add origin https://github.com/USERNAME/REPOSITORIO.git
- git push -u origin master

## Para clonar um repositorio
- git clone https://github.com/USERNAME/REPOSITORIO.git
- - Depois de fazer o que tem a fazer e quando fizer o commit para fazer update é so fazer o seguinte:
- git push

## Links uteis
- https://www.aulaead.com/courses/git-github
- - Pequeno curso de GIT e GITHUB

### Jérémy Trindade