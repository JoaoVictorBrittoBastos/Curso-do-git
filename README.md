# Curso-do-git
Git Bash
# Os comandos:
- $ git --version 
- $ git config --global user.name "João Victor"
- $ git config --global user.email "jbastos2000@gmail.com"
- $ clear
- $ cd Gitcourse/
- $ git init
- $ dir -a
- $ git init
- $ cd --
- $ cd Desktop/
- $ cd gitcourse/
- $ dir -a
- $ git init
- $ dir
- $ git status
- $ git add readme.txt
- $ git status
- $ git add --all
- $ git status
- $ git add -A
- $ git add .
- $ git commit -m "Adição do arquivo readme"
- $ git status
Adicionei mais um documento cópia, dei git status ele deu untracked files, e precisei de dar add --all.
modifiquei de novo o arquivo e usei o comando git diff para mostrar a diferença de antes.
- $ git add
- git diff --cached, que mostra as diferenças
- e git saved que mostra
git log que mostra todas as alterações e gera um "cha" q associa um commit a um cha
git checkout no commit do log / muda de branch ou procura arvores da branch
alterei o value e usei git status e depois git diff e mostrou o que foi alterado, depois usei git checkout gitcoursee.txt e então ele voltou ao que era antes
git reset desfaz tudo
git exit fecha o git bash

git clean -f apaga os arq que foram adicionados
Usei o git clone para clonar um repositório dentro do github.
cd .. Volta para o caminho anterior
- $ git reset --hard é como se fosse um ctrlz que volta tudo oque vc mudou antes de ser salvo
- $ git branch lista as branchs existentes naquele repositório; $ git branch nomeBranch, cria uma branch chamada "nomeBranch
- $ git push envia, git pull puxa, ambos de uma branch pra 
-  upstream é algo que mapeia a branch do repositório no servidor
-  git branch -d, para remover branch locais.
-  git push --delete origin "branch" deleta comando no servidor
-  git branch -m renomeia as branchs
-  se quiser renomear uma branch chamada TASK-3-Update para TASK-3 por exemplo você tem que chamar: $ git branch -m TASK-3-Update TASK-3
