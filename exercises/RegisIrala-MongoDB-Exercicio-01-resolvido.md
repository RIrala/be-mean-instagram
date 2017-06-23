# MongoDB - Aula 01 - Exercício
autor: Regis Irala

# Importando os restaurantes

mongoimport --db be-mean --collection restaurantes --host=127.0.0.1 --dr
op --file restaurantes.json
connected to: 127.0.0.1
2017-06-22T20:35:37.248-0300 dropping: be-mean.restaurantes
2017-06-22T20:35:38.607-0300 check 9 25359
2017-06-22T20:35:38.708-0300 imported 25359 objects

# Contando os restaurantes

db.restaurantes.find({}).count()
25359

