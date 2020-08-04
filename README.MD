# Aula GIT E GITHUB

O git é uma linha do tempo no seu projeto,permitindo que navegue entre as diversas alterações durante o processo.

# Iniciar linha do tempo/ novo repositório - iniciar projeto com GIT

git init

# Adicionando arquivo no repositório

git add nome_do_arquivo.ext

git add . - adiciona todas as alterações do projeto

# Comitando

git commit -m "added new file" (-m passa a mensagem do que foi adicionado)

# Vendo logs de alteração

git log

# Mostrando o que foi alterado em cada commit

git show 'hash do commit' ou git show para ver o ultimo

# Criando ramificação - nova branch

git branch nome/nome

git checkout branch/branch - para entrar na branch desejada

git status - ver a branch atual

# Unir as alterações(branchs) em produção (merge)

git merge nome/nome

# Excluindo branchs

git -D nome/nome

# Adicionando projeto ao repositório do github

git remote add origin https://github.com/RVegh/aula-git.git - exemplo de link do repositório

git remote -v - mostra os repositórios remotos

# Git push - Empurrando o repositório local para o repositório online

 git push -u origin master - Primeiro push para criar a master no repositório online



