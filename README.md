
# Curso Git e GitHub - BeAcademy - DevStart

Esse é o módulo do curso que trata sobre o versionamento dos projetos utilizando Git e GitHub.


## Autor

- [@BrunoApostolico](https://www.github.com/brunoapostolico)


## Funcionalidades - Comandos do Git

### Comandos da Aula da Plataforma

- git (Lista diversos comandos possíveis)
- git --version (Informa a versão do GIT instalada)
- git config --global user.name "nomeDeUsuario" (Usuario do GIT para identificar quem fez as alterações)
- git config --global user.email "emailDoUsuario" (Email do usuário do GIT)
- git status (visualiza o status do diretório)
- git init (Inicializa o repositório vazio)
- git add <nome_do_arquivo> (adiciona arquivo ao commit)
- git add . (adiciona todos arquivos que foram editados e colocar no commit)
- git rm --cached <nome_do_arquivo> (Desfaz a ação/Remove o arquivo)
- git commit -m "mensagem" (Realiza o commit)
- git log (Mostra o log das operações, historicos dos commits)
- git branch (Lista as branchs disponíveis no repositório local)
- git branch nome_da_branch (Criação de branch)
- git checkout nome_da_branch (Permite navegar entre as branchs)
- git checkout -b nome_da_branch (Cria uma branch e já faz o checkou para a branch criada)
- git branch -d nome_da_branch (Remove uma branch auxiliar)
- git merge nome_da_branch (Unificação das alterações entre branchs)
- git clone (Faz uma cópia de um repositório do GitHub para o Git)
- git remote -v (Lista urls de origem de repositório remoto)
- git push (Envia as alterações do commit para o repositório remoto)

### Comandos da Live de 09/05/22

- git stash (salva alterações sem commit)
- git stash pop (restaura alterações salvas)
- git stash pop stash@{1} (aplica stash especifico)
- git stash list (list stashes)
- git revert <hash do commit> (inverte as mudanças de um commit e gera um novo commit com o conteúdo invertido) 

### Outros Comandos do GIT

- git remote add origin git@github.com: seuusuario/seurepositorio.git
- ls -al .git (Vai listar todos os arquivos git do diretório)
- git log -n 5 (traz os 5 ultimos commits)
- git log --since=2020-10-01 (todos os commits de 2020)
- git log --until=2020-10-01 (traz os anteriores a essa data)
- git log --author=<nome_usuario> (traz todos as alterações e commits do usuario)
- git log --grep="init" (ele procura por init, é uma ferramenta de pesquisa)
- git diff (mostra oq foi apagado ou adicionado)
- git diff staged (mostra oq foi apagado ou adicionado)
- git commit -m "remove nomedoarquivo.txt" (Usar esse comando depois de apagar um arquivo )
- git mv file1.txt sub/file1.txt (vai mover o arquivo para a pasta sub)
- git commit --amend (ele abre o ultimo arquivo)
- git checkout códigoHash--Nomedoarquivo (esse código serve para vc encontrar algum commit que vc queira)
- git clean -n (vai mostrar todos os arquivos q vão ser removidos para sempre)
- git clean -f (vai confirmar a remoção)
- git show códigohash (mostra as diferenças de uma atualização para outra)
- cat nomedoarquivo.txt (serve para buscar algum arquivo e vê oq tem dentro)

