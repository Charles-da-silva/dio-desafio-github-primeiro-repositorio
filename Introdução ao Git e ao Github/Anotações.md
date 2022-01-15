# Principais comandos do Git:

## git init
Para começar um projeto que ainda não seja um repositório (ou repo), o Git Init costuma ser o primeiro comando que você vai usar, pois vai precisar de um subdiretório .git na raiz do seu projeto.
Esse comando cria um repositório vazio ou transforma uma pasta que você já tem, e que não está com controle de versão, em um repositório.
## git clone
comando para baixar o código-fonte existente de um repositório remoto (como o Github, por exemplo).

exemplo:  git clone "https://url-do-repositório-no-GitHub"
## git status
Exibe o status dos arquivos dentro do repositório local. Pode informar que tudo está atualizado com o repositório remoto ou que existem arquivos Untracked (arquivos que não existiam no repositório local desde o último snapshot (Commit)).
## git add . 
Adiciona os arquivos Untracked à área de Stage, para depois serem "commitados". O sinal de ponto (.) ou asterisco (*) depois do add fará a adição de todos os arquivos Untracked. Também pode ser usado o comando **git add -A**
## git commit -m "comentário"
Este comando serve para preparar os arquivos para serem enviado para a núvem (repositório remoto). Dentro das aspas deve-se adicionar um comentário resumido de qual alteração está sendo realizada no commit.
## git push origin main
Comando utilizado para enviar os arquivos commitados para a núvem.
## git pull
Comando usado para baixar o repositório remoto para sua máquina local. Depois do "git pull" deve-se adicionar o endereço do repositório remoto (HTTP/SSH/GitHub CLI).
## git branch
Com branches (ou ramificações), vários desenvolvedores podem trabalhar paralelamente no mesmo projeto. Assim, cada um pode codar a sua parte sem se atrapalharem.

Por isso, esse é um dos comandos Git mais importantes. Pode-se usar o comando git branch para criar, listar e excluir branches.

- **git branch "nome-da-branch"**  -->  Este comando criará uma branch local. 

- **git push -u "remote" "nome-da-branch"**  -->  Para upar a nova branch para o repositório remoto.

- **git branch ou git branch --list**  -->  Para ver as ramificações

- **git branch -d "nome-da-branch"**  -->  Deletando uma branch

## git checkout
Este é um dos comandos Git mais usados. Para trabalhar em uma branch, primeiro você precisa mudar para ela. Não ir para a branch que você acabou de criar e na qual quer trabalhar é um erro bastante comum no começo.

Então, usamos o git checkout principalmente para mudar de um branch para outro. Também podemos usá-lo para verificar arquivos e commits:

exemplo: **git checkout "nome-da-ramificação"**

Há ainda um comando de atalho que te permite criar e ir para um branch de uma vez só:  **git checkout -b "nome-da-branch"**
