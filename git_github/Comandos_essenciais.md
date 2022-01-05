# Comandos essenciais

## git init
Criar um repositório Git vazio no diretório de trabalho.

## ls -a
Lista arquivos ocultos.

## git config --list
Mostra a lista de todas as configurações.

## git config --global user.name "Alvaro de Jesus Netto"
Configura o nome do autor.

## git config --global --unset user.name
Apaga a configuração do nome do autor.

## git config --global user.email "alvarojnetto@gmail.com"
Configura o e-mail do autor.

## git config --global --unset user.email
Apaga a configuração do e-mail do autor.

## git status
Mostra o status da árvore de trabalho.

## git add * ou git add . ou  git add <lista de arquivos ou diretórios>
Adiciona tudo ou itens específicos.

## git commit -m "Texto descritivo do commit"
Grava as mudanças no repositório local.  
A flag _-m_ significa que será inserida uma mensagem.

## echo > README.md
Cria o arquivo README.md.

## git remote add origin <link do repositório>
Criar novo repositório no GitHub, colocar nome, descrição, público, README.md e licença e copiar o caminho do repositório e colar o link. origin é somente um alias, um apelido.

## git remote -v
Mostra a lista de repositórios remotos cadastrados.

## git push -u origin main
Empurra o código do repositório local para o repositório remoto. main é a branch que vai receber o código.

## git pull origin main
Pucha o repositório do branch main para o servidor local.



