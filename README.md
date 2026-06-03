# 🎵 ¿Suena igual para todos?

## Análisis de la presencia y popularidad femenina en las plataformas de streaming musical

### 📌 Descripción del proyecto

La industria musical ha experimentado una profunda transformación gracias a las plataformas de streaming. Sin embargo, surge una pregunta relevante:

**¿Las artistas femeninas tienen la misma representación y éxito que los artistas masculinos en la música digital?**

Este proyecto analiza la presencia, visibilidad y popularidad de artistas masculinos y femeninos a través de datos obtenidos mediante las APIs de Deezer y Last.fm.

A partir de una muestra de 30 artistas y más de 1.500 canciones, se construyó una base de datos relacional que permitió explorar posibles diferencias en audiencia, reproducciones, rankings, colaboraciones y representación por géneros musicales.

---

## 🎯 Objetivo

Investigar si existen diferencias significativas entre artistas femeninos y masculinos en las principales métricas de éxito dentro del ecosistema musical digital.

---

## 🔍 Preguntas de investigación

El análisis se desarrolló alrededor de las siguientes preguntas:

### 1. Audiencia y popularidad

* ¿Cuál es la media de oyentes de las artistas femeninas frente a los artistas masculinos?
* ¿Cuál es la media de reproducciones según el género del artista?

### 2. Eficiencia por canción

* Si dividimos el número total de reproducciones entre el número de canciones disponibles, ¿qué grupo obtiene un mayor rendimiento por tema publicado?

### 3. Posicionamiento en rankings

* ¿Cuál es la posición media en los rankings musicales para mujeres y hombres?
* ¿Qué porcentaje de artistas presentes en el Top 10 pertenece a cada grupo?

### 4. Colaboraciones musicales

* ¿Quién realiza más colaboraciones?
* ¿Las artistas femeninas aparecen con mayor frecuencia en canciones colaborativas que en proyectos en solitario?

### 5. Producción musical

* ¿Qué grupo publica álbumes con mayor número de canciones?
* ¿Existe alguna diferencia en la frecuencia de lanzamiento de nuevos trabajos discográficos?

### 6. Representación por género musical

* ¿Existen estilos musicales con una presencia mínima o inexistente de artistas femeninas?
* ¿Qué géneros muestran una representación más equilibrada?

---

## 📂 Fuentes de datos

### Deezer API

Información recopilada:

* Artistas
* Canciones
* Álbumes
* Fechas de lanzamiento
* Géneros musicales

### Last.fm API

Información complementaria:

* Biografías
* Número de oyentes
* Número de reproducciones
* Ranking de popularidad
* Artistas similares

---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* Requests
* MySQL
* SQL
* Git
* GitHub
* Deezer API
* Last.fm API

---

## 🗄️ Arquitectura del proyecto

El flujo de trabajo siguió las siguientes fases:

1. Selección de artistas.
2. Extracción de datos mediante APIs.
3. Limpieza y transformación de datos.
4. Diseño de una base de datos relacional.
5. Inserción de información en MySQL.
6. Desarrollo de consultas SQL.
7. Análisis exploratorio y comparación por género.
8. Elaboración de conclusiones y visualizaciones.

---

## 📊 Principales métricas analizadas

* Oyentes medios por artista.
* Reproducciones totales.
* Reproducciones por canción.
* Posición media en rankings.
* Presencia en Top 10.
* Número de colaboraciones.
* Canciones por álbum.
* Tiempo medio entre lanzamientos.
* Distribución de artistas por género musical.

---

## 💡 Impacto del análisis

Este estudio permite explorar posibles desigualdades en la representación musical dentro de las plataformas digitales y comprender mejor cómo se distribuye la visibilidad de artistas según su género.

Los resultados pueden aportar información valiosa para plataformas de streaming interesadas en promover una mayor diversidad y representación dentro de sus recomendaciones y estrategias de promoción.

---

## 👥 Equipo

Proyecto desarrollado por:

* [Nombre integrante]
* [Nombre integrante]
* [Nombre integrante]
* [Nombre integrante]

---

## 🚀 Cómo ejecutar el proyecto

### Clonar repositorio

```bash
git clone <url-repositorio>
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Ejecutar extracción de datos

```bash
python src/extraccion_datos.py
```

### Cargar información en la base de datos

```bash
python src/carga_bbdd.py
```

### Ejecutar consultas de análisis

```bash
python src/analisis.py
```

---

## 🌱 Aprendizajes

A través de este proyecto se consolidaron conocimientos sobre:

* Consumo de APIs REST.
* Limpieza y transformación de datos.
* Modelado de bases de datos relacionales.
* Consultas SQL complejas.
* Trabajo colaborativo mediante Git y GitHub.
* Desarrollo de proyectos de análisis de datos con perspectiva de género.

