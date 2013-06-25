tg
==

Trabalho de Graduação - CIn/UFPE

Para executar os comandos abaixo na distribuição Debian, instalei apenas o pacote texlive-full (cerca de 1GB após instalado)


Para transformar arquivos .tex em .pdf:

$ latex arquivo.tex

$ bibtex arquivo.aux

$ latex arquivo.tex

$ dvipdfm arquivo.dvi


*pode ser necessário executar o comando "latex" mais de uma vez. Então na dúvida, execute duas vezes.

Atenção: Arquivos texto utilizando encoding UTF8.
Caso esteja utilizando VIm, execute o comando ":set encoding=utf8" antes de visualizar/editar os arquivos texto.
