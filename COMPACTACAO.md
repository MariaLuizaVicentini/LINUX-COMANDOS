
# Compactação e descompactação de arquivos

o '.tar' é excelente pra agrupar varios arquivos em apenas um. 


Basicamente existem três tipos de arquivos que são utilizados com o .tar:
tar.gz ou .tgz e .tar.bz2.

ele realiza uma copia sem compactacao dos arquivos passados como parametro, ou seje, ele junta todos os arquivos em um unico arquivo sem compactar.

• -c cria um novo arquivo .tar e adiciona os arquivos a serem compactados;
• -f indica que o destino é um arquivo em disco;
• -v exibe o nome de cada arquivo compactado;
• -x extrai os arquivos agrupados no arquivo .tar.
• -z extrai os arquivos agrupados no arquivo .tar.


agrupando arquivos e compactando-os em uma pasta chamada backup
```
tar -cf meu_primeiro_backup.tar *.txt
```

Esse arquivo chamado backup.tar, que representa a união de todos os arquivos com extensão .txt

pra descompactar um arquivo:
```
tar xvf nome_arquivo.tar
```

----

# O tipo .tar.gz

O .tar.gz consiste em dois processos diferentes e interligados, sendo que pri-
meiro ele cria um arquivo .tar e, em seguida, compacta utilizando o formato .gz.
Neste caso, além de gerar um único arquivo com o .tar, ele será compactado, re-
duzindo assim o seu tamanho.


inda dentro da pasta backup, vamos testar a criação do nosso arquivo dessa
vez compactado com .tar.gz:

```
tar zcvf backup.tar.gz *.txt
```


pra verificar o tamnho dos arquivos
```
du -h nome_arquivo.txt
```


Para descom-
pactar arquivos .tar.gz usa-se as opções zxvf:
```
tar zxvf meu_arquivo.tar.gz
```


