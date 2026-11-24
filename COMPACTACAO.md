
# Compactação e descompactação de arquivos

o '.tar' é excelente pra agrupar varios arquivos em apenas um. 


Basicamente existem três tipos de arquivos que são utilizados com o .tar:
tar.gz ou .tgz e .tar.bz2.

ele realiza uma copia sem compactacao dos arquivos passados como parametro, ou seje, ele junta todos os arquivos em um unico arquivo sem compactar.

• -c cria um novo arquivo .tar e adiciona os arquivos a serem compactados;
• -f indica que o destino é um arquivo em disco;
• -v exibe o nome de cada arquivo compactado;
• -x extrai os arquivos agrupados no arquivo .tar.


agrupando arquivos e compactando-os em uma pasta chamada backup
```
tar -cf meu_primeiro_backup.tar *.txt
```

Esse arquivo chamado backup.tar, que representa a união de todos os arquivos com extensão .txt