# challenge_01
Desafío 01 EDVai vinculado a la copa mundial de fútbol Femenino 2019 


En esta oportunidad utilizaremos datos provenientes de https://github.com/cienciadedatos/datos-de-miercoles.

Nuestro objetivo es conocer por fecha de mundial que país hizo más goles y almacenarlo en un dataframe.

|Año de la Copa Mundial       |País               |Cantidad de Goles |
|:--------------|:-------------------|:-----------|
|  |  |  |


# Datos sobre Copas Mundiales de Fútbol Femenino

## Obtener los datos

Puedes utilizar el siguiente código para importar los datos a Google Colaboratory:

```
import pandas as pd 
resultados_cmff = pd.read_csv("https://raw.githubusercontent.com/nico-edvai/challenge_01/main/resultados_cmff.csv")
```

## Diccionario de datos

#### `resultados_cmff`

|Variable       |Clase               |Descripción |
|:--------------|:-------------------|:-----------|
| anio | numérica | Año de la Copa Mundial |
| equipo | caracter | Equipo  |
| codigo_pais | caracter | Código ISO de 3 letras del país |
| ronda | caracter | Ronda/Fase dentro del torneo |
| resultado | caracter | Resultado final del encuentro `victoria`, `derrota`, `empate` |
| goles | numérica | Total de goles del equipo |
| id_partido_anio | numérica | Número del partido dentro del torneo de ese año |
| numero_equipo | numérica | Número del equipo en ese partido (`1` o `2`) |

## Fuente de los datos

https://github.com/cienciadedatos
