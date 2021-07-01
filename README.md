# TP 2 InfoVis

Trabalho desenvolvido na disciplina Visualização da Informação do Programa de Pós-Graduação em Ciência da Computação (PPGCC) da Universidade Federal do Pará (UFPA) em 2021.1.

O trabalho desenvolvido visa criar uma ferramenta de visualização da informação utilizando o D3.js. As visualizações geradas precisam responder ao menos 3 perguntas que envolvam entre 3 e 4 atributos da base de dados utilizada. Uma das visualizações deve ser obrigatoriamente com base em mapas.

## Base de dados

A base de dados trabalhada contém informações sobre a queda de meteoritos na terra, e está disponível em <https://www.kaggle.com/nasa/meteorite-landings>.

## Pré-processamento

O arquivo [meteorite-landings.ipynb](meteorite-landings.ipynb) contém pré-processamentos realizados nos dados da [base de dados original](meteorite-landings.csv), como remoções de valores nulos, atributo massa igual a 0 e coordenadas (0, 0). A arquivo [meteorite-landings-v2.csv](meteorite-landings-v2.csv) contém os dados utilizados no desenvolvimento do trabalho.

## Mapa

O arquivo [JSON](world_countries.json) contém as informações geométricas do mapa utilizado nas visualizações.

## Perguntas

1. Dentre os intervalos de tempo com grade número de episódios de meteoritos, quais as regiões mais afetadas e qual a massa média dos meteoritos nesta região?
2. Qual a massa média da classe predominante de meteoritos e em qual região eles costumam mais ocorrer? 
3. Qual a classe predominante dos meteoritos do tipo Fell, qual o período de sua maior ocorrência e em quais locais eles são mais comumente encontrados? 

## Vídeo

Um melhor detalhamento do que foi desenvolvido e das visualizações geradas com o D3.js encontra-se disponível em: <https://youtu.be/ov9QcZWFRaQ>.