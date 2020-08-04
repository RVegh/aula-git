# Aula GIT E GITHUB

O git é uma linha do tempo no seu projeto,permitindo que navegue entre as diversas alterações durante o processo.

# Iniciar linha do tempo/ novo repositório - iniciar projeto com GIT

git init

# Adicionando arquivo no repositório

git add nome_do_arquivo.ext

git add . - Adiciona todas as alterações do projeto

# Comitando

git commit -m "added new file" (-m passa a mensagem do que foi adicionado)

git commit -am "comitando direto utilizando o parâmetro -a para adicionar automaticamente"


# Vendo logs de alteração

git log

# Mostrando o que foi alterado em cada commit

git show 'hash do commit' ou git show para ver o ultimo

# Criando ramificação - nova branch

git branch nome/nome - nova branch

git checkout branch/branch - Para entrar na branch desejada

# Recuperando alterações 

git checkout --nome do arquivo 

git checkout hash do commit --nome do arquivo a ser recuperado - - busca a ultima alteração 

# Excluindo arquivos

git checkout -D nome do arquivo

# Visão da branch atual e alterações
git status - ver a branch atual

# Unir as alterações(branchs) em produção (merge)

git merge nome/nome

# Excluindo branchs

git -D nome/nome

# Adicionando projeto ao repositório do github

git remote add origin https://github.com/RVegh/aula-git.git - Exemplo de link do repositório

git remote -v - Mostra os repositórios remotos

# Git push - Empurrando o repositório local para o repositório online

 git push -u origin master - Primeiro push para criar a master no repositório online

 git push - Demais pushs das alterações

# Atualizando alterações

git pull

# Clonando um repositório

git clone https://LINK


