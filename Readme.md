# Este tutorial ensina você a usar o Git e como linkar um IDLE direto ao GitHub
## Passos:
1. instale o Git em seu computador - se estiver utilizando Linux poderá fazer isso através do comando - 'sudo install Git' - após a instalação verifique se deu tudo certo com o comando - git version no terminal
2. Configure o usuário e um email - comandos git config --global user.name "Nome Usuário" git --global user.email "email@provedor.com"
3. Crie uma pasta no seu computador que será o repósitorio de arquivos para seu projeto, por exemplo Git_Setup - abra a pasta e com o botão direito inicialize o IDLE que você está utilizando (nós estamos utilizando o VSCode)
4. Crie um arquivo Readme.md e escreva uma mensagem de sua preferência
5. Agora vamos começar - se estiver utilizando o Windowns abra sua pasta clique com o botão direito e clique em Git Bash Here, se estiver utilizando o Linux abra o terminal no VSCode - insira o comando - git init você deverá receber o seguinte output: 'initialized empty Git repository in 'caminho da pasta'
6. Utilize o comando git add 'nome do arquivo' para adicionar um arquivo na área de stage (local onde os arquivos ficam antes de serem enviados para o ambiente )
7. Para verificar se deu certo - git status (note se o arquivo consta em 'Changes to be committed')
8. Agora vamos incluir as mudanças feitas com o comando git commit -m "cria"
9. Para linkar suas alterações no GitHub crie um novo repositório e utilize os seguintes comandos git remote add origin "https://github.com/username/Projectname.git" (você precisará logar no GitHub para autorizar a ligação)
9. Criar uma nova branch - utilize o comando git checkout -b "nome_novabranch"
10. Utilizar os comandos normalmente: git add . (para adicionar os arquivos alterados) e git status para verificar a inclusão
11. git commit -m "alterações_2"
12. git push origin nome da branch
13. git checkout main - para voltar para a branch principal
14. git merge "nome da branch que você quer incluir" - para enviar as alteraçõs para a branch main
15. git push origin main