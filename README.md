<h1 align="center">Aplicación de recomendación de películas</h1>
<img source="<img width="500" height="348" alt="image" src="https://media3.giphy.com/media/CzrZNbaL8HwW7NTdV4/source.gif" />


## Contenido
- [Objetivos](#objetivos)

- [Rol_del_Cientifico_de_Datos](#rol-cientifico-de-datos)

- [Datos Utilizados](#datos-utilizados)

- [Metodología](#metodología)

## Objetivos

Desarrollar una herramienta basada en ciencia de datos que permita recomendar películas de forma eficiente y confiable, utilizando datos reales.

Objetivos específicos:

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
