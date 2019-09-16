# Arquitetura

* As funções relacionadas ao gerenciamento das casas do
jogo da velha ficando no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma
string: "." para casa vazia; "X" para casa ocupada pelo 1o
jogador; "O" para casa ocupada pelo 2o jogador

* A função inicializar() retornara uma lista 3x3, onde cada
posição do jogo. A função retornará todas as casas
inicialmente vazias.