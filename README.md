# ISC Formula Student
2022-2023 Departamento de Telemetría

EL EQUIPO Está formado por más de 70 estudiantes, mayoritariamente de la Escuela de Ingeniería ICAI, contando también con miembros de ICADE. Nuestro objetivo es concebir, diseñar, fabricar y competir con un monoplaza eléctrico.


[2022](#section-1)
[2023](#section-2)
[IMAGES](#section-3)





## FS_data_rx
  Carpeta que contiene los scripts en python para:
  - recibir datos del coche a tiempo real, y guardarlos en una base de datos (InfluxDB).

## FS_influx_cloud
  Carpeta que contiene los scripts para:
  - sincronizar datos de Influx OSS (En local) a Influx Cloud.
  - permitir a los miembros del equipo facil acceso a los datos descargandolos como un .csv.




## Notas
- API Tokens and org variables have been removed for obvious reasons.
- Last update: 22/11/2023


# 2022
<a name="section-1"></a> 2022

Visualización a tiempo real utilizando Python, InfluxDB y Grafana.

El año anterior, para la elaboración de este programa, empleé con destreza el lenguaje Python, así como una Base de Datos basada en Influx y la plataforma Grafana. A través de Python, orquesto la recepción de datos provenientes de un Arduino con un módulo de radio NRF24L01, mismos que transformo en datos temporales y almaceno en la base de datos Influx. Posteriormente, Grafana extrae estos datos mediante consultas a InfluxDB para generar visualizaciones altamente personalizadas en tiempo real. En el presente año, estamos dedicando esfuerzos a la investigación y posible implementación de mejoras sustanciales en el proyecto.


# 2023
<a name="section-2"></a> 2023

Por añadir...


# 2022-2023
<a name="section-3"></a> Imagenes

Evento en el Jarama
![271650745-c974fee6-1a24-46b7-beee-b1f208b83c11](https://github.com/fadriqueat/ISC_FS/assets/74105814/6e8e3fcd-6bb5-4860-a9fb-a42f81c8a625)

Fases iniciales del dashboard en Grafana
![271650633-55d7d4c5-04e8-46f9-bdad-d5ed39385c7c](https://github.com/fadriqueat/ISC_FS/assets/74105814/6ee0268f-58a7-4340-b217-8717ff4f6926)
