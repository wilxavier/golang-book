# Resumo da ópera
Este capítulo ensinou como instalar e configurar o Ambiente de Desenvolvimento Go e mostrou também algumas ferramentas para a construção de programas com Go.

## Linux
A maioria dos instaladores Linux e BSD são arquivos *gzipped* TAR e se expandem a um diretório chamado *go*. Copie esta pasta para */usr/local* e adicione */usr/local/go/bin* para o seu $PATH de modo que os comandos **go** sejam acessíveis.

#### Instalação
> $ tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz
> $ echo 'export PATH=$PATH:/usr/local/go/bin' >> $HOME/.bash_profile
> $ source $HOME/.bash_profile

Você precisará de permissôes de administrador para escrever em */usr/local*. Se o comando *tar* falhar execute-o novamente utilizando o comando: **sudo tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz**.
> $ go version

