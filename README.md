# devemigrate
Ferramenta desenvolvida para facilitar a exportação/Importação de dados entre banco de dados através de conexão ODBC
# Introdução
o conceito da ferramenta é bem simples, você vai precisar ter os drivers ODBC das versões de banco as quais você vai conectar. A melhor e mais rápida forma de uso é utilizar templates SQL para que a exportação gere, ao final do processo, os arquivos SQL para serem executados direto no banco de origem.

Também é possível efetuar conexões banco a banco, porém o processo registro a registro mostrou-se demorado, pois o ponteiro vai inserindo registro a registro e efetuando o committ no banco destino. Desta forma, quando os dados são exportados direto para um arquivo SQL a execução deles é mais rápida.

Esta ferramenta foi desenvolvida em Delphi 7 e hoje é disponibilizada gratuitamente sem quaisquer compromisso.

Use por sua conta e risco.
