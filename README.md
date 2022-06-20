# Trabalho em desenvolvimento

## Como votou suma vizinhança
_Reloaded_

Notebooks para geração de mapa (shapefiles) com os locais de votação das eleições e os respectivos resultados.

Baseado no trabalho da equipe do Estadão - Como votou sua vizinhança https://github.com/estadao/como-votou-sua-vizinhanca

O processo de georreferenciamento pega os locais de votação, passa pela API do Google Maps para gerar o lat-long e então aplica o metodo de voronoi para gerar os polígonos.


![image](https://github.com/vinicius-macario/como-votou-reloaded/blob/f86b5382b7e203acd1ebcafa2f2c2973e8250d0d/georreferenciamento.png)

