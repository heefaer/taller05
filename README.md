<h1 align="center">Aplicación de recomendación de películas</h1>
<img source="<img width="500" height="348" alt="image" src="https://media3.giphy.com/media/CzrZNbaL8HwW7NTdV4/source.gif" />

## Descripcion
Esta aplicacion es un sistema de recomendación de películas basado en el análisis de datos provenientes de IMDb. Utiliza criterios como género y calificación promedio para filtrar, ordenar y seleccionar las películas más relevantes dentro de un conjunto de datos. 

Las recomendaciones se basan en el contenido, donde se priorizan criterios como el rating y la popularidad. A partir de este proceso, se generan sugerencias que permiten identificar patrones y tendencias en la industria cinematográfica, facilitando  asi la exploración de contenido de alta calidad para el usuario.


## Contenido
- [Objetivos](#objetivos)

- [Rol del Cientifico de Datos](#rol-cientifico-de-datos)

- [Datos Utilizados](#datos-utilizados)

- [Metodología](#metodología)

## Objetivos

Brindar al usuario una variada recomendacion de películas, que faciliten la elección de qué ver, basadas en el género de su preferencia y en las calificaciones que han hecho otras personas, permitiéndole asi, descubrir películas bien valoradas de manera rápida y sencilla.

1. Analizar datos provenientes de IMDb
2. Filtrar películas por género
3. Clasificar según su puntuación
4. Recomendar contenido relevante
5. Mejorar la experiencia del usuario

## Datos utilizados

Fuente:  <a href="https://www.kaggle.com/code/necrorohan/imdb-full-official-dataset-analysis">  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQDDAP6csPW4r0ZeDthUzBcIOCSmPRFU79G2w&s" width= "50px" height = "50px"> </a>

Los datos utilizados para el proyecto provienen del dataset publicado en Kaggle del IMDb.

En el dataset se realizó un análisis completo de los datos del IMDb. Este contiene:

- Título de la película
- Géneros asociados
- Puntaje promedio IMDb
- Número de reseñas
- Año de lanzamiento
- Reparto

Esta información permite una recomendación acertiva según la popularidad de cada película.

---

## Metodología
> [!NOTE]
> El proceso no se ve afectado por el comportamiento anterior del usuario (no existe un historial que registre las películas vistas, no es una plataforma personalizada).

1. Se filtra por el género seleccionado por el usuario.
2. Se organiza la recomendación de mayor a menor, con base en los puntajes promedios. 
3. Seleccionadas las mejores películas, se muestran al usuario.

---

## Conclusión

La aplicación genera atracción en usuarios que en medio de un mundo personalizado, buscan conocer el comportamiento y gustos del mundo en general. 
