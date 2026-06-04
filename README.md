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
* ¿Quién obtiene más "rendimiento" por cada tema lanzado?

### 2. Posicionamiento en rankings

* ¿Cuál es la posición media en ranking_lista para las mujeres frente a los hombres?
* ¿Qué porcentaje de artistas en el "Top 10" (según ranking_lista) son mujeres?
* ¿Qué porcentaje de artistas en el "Top 10" (según ranking_lista) son grupos mixtos con mujeres al frente?

### 3. Colaboraciones musicales

* ¿Quién colabora más? ¿Las mujeres suelen aparecer más en canciones con colaboraciones que en solitario?

### 4. Producción musical

* ¿Quién saca álbumes más largos (con más canciones)?
* ¿Cuál es el tiempo medio que pasa una mujer entre álbum y álbum frente a los hombres?

### 5. Representación por género musical

* ¿Existen estilos musicales con una presencia mínima o inexistente de artistas femeninas?

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

## 📂 Estructura de Archivos y Datos

En la raíz del proyecto encontrarás los siguientes archivos clave para la ejecución y el análisis:

| Archivo | Tipo | Descripción |
| :--- | :--- | :--- |
| `Extraccion_datos_apis.ipynb` | Jupyter Notebook | Cuaderno principal que contiene todo el código de extracción de APIs, limpieza, conexión y carga a la base de datos MySQL. |
| `listado_de_albumes.csv` | Dataset (CSV) | Información recopilada sobre los álbumes, fechas de lanzamiento y pistas. |
| `listado_de_artistas_fm.csv` | Dataset (CSV) | Datos detallados de Last.fm (oyentes, reproducciones, biografía y popularidad). |
| `listado_de_canciones.csv` | Dataset (CSV) | Métricas y características de las canciones individuales analizadas. |
| `requirements.txt` | Configuración | Archivo con las librerías necesarias para ejecutar el proyecto. |

---

## 👥 Equipo

Proyecto desarrollado por:

* Ana Daza Gallardo
* Alexandra Prieto Prieto
* María de los Ángeles Toro Cabezas

---

## 🚀 Cómo ejecutar el proyecto

### Clonar repositorio

```bash
git clone <https://github.com/Adalab/proyecto-da-promo-67-modulo2-team-1.git>
```

### Instalar dependencias
Asegúrate de tener Python instalado y ejecuta el siguiente comando en la terminal para instalar todas las librerías del archivo de requisitos:

```bash
pip install -r requirements.txt
```

### Crear archivo env
Crear un archivo .env en la raíz con tu clave siguiendo el siguiente formato:
PASS_SQL= "tu_contraseña_de_mysql"

### Abrir y ejecutar el cuaderno principal en Jupyter o VS Code

Archivo: Extraccion_datos_apis.ipynb
En caso de realizar un "Run All" a la pregunta del input contestar: N

### Reutilización del código

Para reutilizar el código con otro grupo de control es necesario cambiar dos variables:

id_artistas = al que se deben añadir los id de deezer del nuevo grupo de control
diccionario_genero = crear el diccionario con los nombres de los artistas y sus géneros. 


## 🌱 Aprendizajes

A través de este proyecto se consolidaron conocimientos sobre:

* Consumo de APIs REST.
* Limpieza y transformación de datos.
* Modelado de bases de datos relacionales.
* Consultas SQL complejas.
* Trabajo colaborativo mediante Git y GitHub.
* Desarrollo de proyectos de análisis de datos con perspectiva de género.

