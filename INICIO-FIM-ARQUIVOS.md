# Exibindo o inicio e fim de arquivos

O head mostra o início dos dados em um arquivo. Por padrão ele exibe as 10
primeiras linhas do arquivo, mas utilizando a opção -n podemos limitar o número
de linhas:

```
head -n 5 nome_arquivo
```

Já o tail mostra o final dos dados do arquivo e possui a mesma opção para
limitar a quantidade de linhas, -n:
```
tail -n 5 name_arquivo
```