# ESTRUTURA DE DIRETORIOS
 

Vamos começar listando os diretórios da pasta raiz "/"
- Ele é o principal diretório do sistema, pois nele ficam todos os outros. 

 ```
 ls /
 ```

 ```
 bin  bin.usr-is-merged  boot  cdrom  dev  etc  home  lib  lib32  lib64  lib.usr-is-merged  lost+found  media  mnt  opt  proc  root  run  sbin  sbin.usr-is-merged  snap  srv  swap.img  sys  tmp  usr  var
 ```

 /bin
 - armazena arquivos executáveis binários, que são os comandos
base para a execução do sistema, por exemplo o ls e o cd


/boot
- contém arquivos de inicialização do sistema, dentre os quais está o ge-
renciador de boot do sistema
- Ele é um aplicativo que carrega o sistema operacional
durante a inicialização


/dev 
- mantém o caminho dos dispositivos instalados no sistema.
- Todo o hardware reconhecido pelo sistema é representado por um arquivo nesse diretório, por exemplo, disco rígido e placa de vídeo.

/etc
- ficam os arquivos de configuração do sistema, scripts de inicialização,
configurações padrão para usuários e arquivos de configuração de programas que são
instalados

/lib
- contém as bibliotecas e módulos do kernel que são essenciais para o
funcionamento do sistema. As bibliotecas são funções compartilhadas que podem
ser usadas por vários programas.


/media
- e o diretorio responsavel por manter os pontos de montagem, ou seja, quando inserimos um pren drive é aqui que ele ficara disponivel 


/mnt
- é utilizado pra monstagem temporaria de sistema de arquivos, isto e um hd ou pen drive
- este diretorio pode ser usado da mesma forma que o /media


/opt
- é onde normalmente instalamos programas que não fazem parte oficialmente da distribuição. Por exemplo, o google chrome.


/sbin
- ficam os comandos utilizados para inicialização, reparação e restauração do sistema. 
- É um diretório de comandos essenciais, mas com a diferença de que apenas um usuário pode usar, o root


/srv 
- mantém dados de serviços disponíveis pelo sistema e pode ser acessado
de forma geral (por todos os usuários), por exemplo, web server


/tmp
- ficam armazenados arquivos temporários, informações que devem ser
mantidas até o fim de uma operação, como um download em andamento ou arquivos
de cache de vídeos do Youtube


/usr
- são mantidos programas que não são essenciais para o funcionamento do sistema. Programas instalados pelo usuário, como editores, programas gráficos,
gerenciadores de janelass são exemplos disso 


/var
- contém arquivos de dados variáveis, ou seja, arquivos que podem aumentar de tamanho, como arquivos de log, arquivos de bancos de dados e
mensagens de e-mail


/proc 
- contém arquivos temporários de processos em execução no sistema. 
-Em outras palavras, é um diretório virtual usado pelo kernel. 
- Nele são mantidos configurações atuais do sistema e dados estatísticos

/sys
- armazena quase o mesmo conteudo porem de forma mais organizada pra podermos administrar

