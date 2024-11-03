# Resumo da ópera
Este ato ensinou como instalar e configurar o Ambiente de Desenvolvimento Go e mostrou também algumas ferramentas para a construção de programas com Go.

As últimas versões das Ferramentas de Desenvolvimento **Go** para os mais variados sistemas operacionais podem ser baixadas em https://go.dev/dl/. Escolha e baixe o pacote para sua plataforma específica. Os instaladores *.pkg* para Mac e o *.msi* para Windows instalam o *Go* no caminho correto de execução, removendo qualquer instalação antiga e colocando os arquivos binários *Go* no caminho padrão de arquivos executáveis.
## Linux
A maioria dos instaladores Linux e BSD são arquivos *gzipped* TAR e se expandem a um diretório chamado *go*. Copie esta pasta para */usr/local* e adicione */usr/local/go/bin* para o seu $PATH de modo que os comandos **go** sejam acessíveis.

#### Instalação
> $ tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz\
> $ echo 'export PATH=$PATH:/usr/local/go/bin' >> $HOME/.bash_profile\
> $ source $HOME/.bash_profile

Você precisará de permissões de administrador para escrever em */usr/local*. Se o comando *tar* falhar execute-o novamente utilizando o comando:
> $ sudo tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz

Você precisará de permissões de administrador para escrever em */usr/local*. Se o comando *tar* falhar execute-o novamente utilizando o comando: 
> sudo tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz

E para ver foi instalado corretamente utilize:
> $ go version

