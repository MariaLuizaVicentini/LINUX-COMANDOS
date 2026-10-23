# LOCALIZANDO ARQUIVOS

`find [caminho] [expressão] [ação]`

- caminho - define a partir de onde os arquivos serão procurados.
- expressão - define os critérios de busca.
- ação - define o que será feito com os arquivos encontrados.
  
find . -name "nome-arquivo"
- procura arquivos e diretórios pelo nome, a partir do diretório atual.

find . -user nome-usuario
- procura arquivos e diretórios pertencentes ao usuário informado.

find . -atime n
- procura arquivos acessados há aproximadamente n dias.
  
find . -mtime n
- procura arquivos modificados há aproximadamente n dias.
  
find . -type f
- lista apenas arquivos comuns.

find . -type d  
- lista apenas diretórios.
  
find . -name "*.txt"
- procura arquivos e diretórios com nomes terminados em .txt.

find . -size +10M
- procura arquivos maiores que 10 MB.

find . -empty
- procura arquivos e diretórios vazios.

find . -name "*.log" -delete
- procura arquivos com nomes terminados em .log e os remove.