# Comandos essenciais

## ssh-keygen -t ed25519 -C alvarojnetto@gmail.com
Gera o par de chaves pública e privada ssh. Precisa cadastrar uma senha. ed25519 é o nome da criptografia.
Antes é preciso ir ao GitHub clicar no ícone da foto, abrir settings, clicar em SSH ans GPG keys, New SSH key, preencher o nome da máquina, a chave copiada no comando abaixo e Add SSH Key.

## cat id_ed25519.pub
Para visualizar o conteúdo da chave pública e copiá-la.
Antes precisa entrar no diretório .ssh
Após copiar a chave pública precisa ir ao GitHub e colar a chave pública ao adicionar a chave SSH.

## eval $(ssh-agent -s)
Inicializar o SSH-Agent que vai lidar com as chaves.

## ssh-add id_ed25519
Entrega a chave para o SSH-Agent. Agora a chave SSH está pronta para ser utilizada.

## Gerar um token de acesso pessoal.
Precisa ir ao GitHub em settings, Developer Settings, Personal access tokens, Generate new token, Colocar uma nota, uma data de expiração, marcar repo, Generate token.
Copiar o HTTPS do repositírio.

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

## git clone <url ou http do repositório a ser clonado>
Clona o repositório endereçado pela url ou http. Dá para aplicar um git remote -v para saber os repositórios remotos para onde o repositório que foi clonado está apontado.

## rm -rf <diretório>
Remove (apaga) todo o diretório com suas subpastas.




