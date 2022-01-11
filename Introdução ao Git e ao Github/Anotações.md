# Comandos principais do Git:
## git status
Exibe o status dos arquivos dentro do repositório local. Pode informar que tudo está atualizado com o repositório remoto ou que existem arquivos Untracked (arquivos que não existiam no repositório local desde o último snapshot (Commit)).
## git add . 
Adiciona os arquivos Untracked à área de Stage, para depois serem "commitados". O sinal de ponto (.) ou asterisco (*) depois do add fará a adição de todos os arquivos Untracked.
## git commit -m "comentário"
Este comando serve para preparar os arquivos para serem enviado para a núvem (repositório remoto). Dentro das aspas deve-se adicionar um comentário resumido de qual alteração está sendo realizada no commit.
## git push origin main
Comando utilizado para enviar os arquivos commitados para a núvem.
## git pull
Comando usado para baixar o repositório remoto para sua máquina local. Depois do "git pull" deve-se adicionar o endereço do repositório remoto (HTTP/SSH/GitHub CLI).