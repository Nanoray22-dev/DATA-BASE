# Carreras

## Listados de entidades

### Carreras **(ED)**

- carrera_id **(PK)**
- carrera_nombre 
- tipo_de_carrera **(FK)**
- fechas 
- tiempo
- mejor_tiempo
- altitud 
- lugar 
- pais **(FK)**
- foto 

### tipo_carrera **(EC)**

- tipo_carrera **(PK)**
- descripcion
- distancias

### paises **(EC)**

- pais_id **(PK)**
- nombre

## Relaciones

1. Una **carrera** _pertenece_ a un **tipo de carrera** (_1 a 1_)
1. Una **carrera** se_corre_ en un **pais** (_1 a 1_)
