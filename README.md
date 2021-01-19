# bingo-kata

Bingo Kata 

Version PHP 7.2 (Dockerisado)
Composer
Pruebas PHPUNIT

## Instalación:

## Local:
Requisito php 7.2
Composer 

## Ejecutar:

**` composer install  `**

-- Corer el Projecto
Parametros de Entrada:
- `us` -> Modo de bingo Estunidence
- `1` -> Minimo rango de la tarjeta
- `75` -> Maximo rango de la tarjeta
- `5` -> Filas de la tarjeta
- `5` -> Columnas de la tarjeta
- `200` -> numeor de jugadores

## Ejecutar el siguiente comando para correr el projecto:
**` php main.php us 1 75 5 5 200 `**


En caso que se ejecute via Docker(Recomndable) se creo un archivo make que contine los siguientes comandos: I

- `make start-docker`
- `make composer-install`
- `make run-game-us`
- `make run-tests`