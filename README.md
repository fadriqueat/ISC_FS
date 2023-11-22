# ISC Formula Student
2022-2023 Departamento de Telemetría

EL EQUIPO Está formado por más de 70 estudiantes, mayoritariamente de la Escuela de Ingeniería ICAI, contando también con miembros de ICADE. Nuestro objetivo es concebir, diseñar, fabricar y competir con un monoplaza eléctrico.


[2022](#section-1)



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

Por añadir...
