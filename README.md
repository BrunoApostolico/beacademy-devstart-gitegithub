
# Curso Git e GitHub - BeAcademy - DevStart

Esse é o módulo do curso que trata sobre o versionamento dos projetos utilizando Git e GitHub.


## Autor

- [@BrunoApostolico](https://www.github.com/brunoapostolico)


## Funcionalidades - Comandos do Git
### Comandos da Aula da Plataforma

- git /*Lista diversos comandos possíveis*/
- git --version /*Informa a versão do GIT instalada*/
- git config --global user.name "nomeDeUsuario" /*Usuario do GIT para identificar quem fez as alterações*/
- git config --global user.email "emailDoUsuario" /*Email do usuário do GIT*/
- git status /*visualiza o status do diretório*/
- git init /*Inicializa o repositório vazio*/
- git add <nome_do_arquivo> /*adiciona arquivo ao commit*/
- git add . /*adiciona todos arquivos que foram editados e colocar no commit*/
- git rm --cached <arquivo> /*Desfaz a ação*/
- git commit -m "mensagem" /*Realiza o commit*/
- git log /*Mostra o log das operações, historicos dos commits*/
- git branch /*Lista as branchs disponíveis no repositório local*/
- git branch nome_da_branch /*Criação de branch*/
- git checkout nome_da_branch /*Permite navegar entre as branchs*/
- git checkout -b nome_da_branch /*Cria uma branch e já faz o checkou para a branch criada*/
- git branch -d nome_da_branch /*Remove uma branch auxiliar*/
- git merge nome_da_branch /*Unificação das alterações entre branchs*/
- git clone /*Faz uma cópia de um repositório do GitHub para o Git*/
- git remote -v /*Lista urls de origem de repositório remoto*/
- git push /*Envia as alterações do commit para o repositório remoto*/

### Comandos da Live de 09/05/22

- em construção
- git stash (salva alterações sem commit)
- git stash pop (restaura alterações salvas)
- git stash list (list stashes)
- git stash pop stash@{1} (aplica stash especifico)
