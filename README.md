# Workshop 3

En este workshop integraremos algunas herramientas de Inteligencia Artificial a nuestro proyecto de películas. 

- Utilizaremos modelos de lenguaje (GPT desde la API de openAI) para crear elementos nuevos (películas) para nuestra base de datos.
- Utilizaremos la API de creación de imágenes para generar imágenes representativas de cada película de la base de datos.
- Crearemos un sistema de recomendación utilizando embeddings.

Las instrucciones de cada etapa del proyecto son las siguientes:

1. [Hacer Fork del proyecto base](1_Fork_and_clone.md) 
2. [Crear la API key en openAI](2_openAIapikey.md)
3. [Instalar las librerías necesarias](3_Instalaciones.md)
4. [Descripción de las películas](4_movie_descriptions.md)
5. [Ilustraciones de las películas](5_movie_pictures.md)
6. [Sistema de recomendación](6_recommendation_system.md)
7. [Alternativas open source](7_open_source.md)

### Entregable en clase 

Archivo pdf con:

1. GitHub del proyecto
2. Pantallazo de las películas con la imagen default
 ![image](https://github.com/user-attachments/assets/be4795cb-e67b-48a9-a4cc-025096c5bc1d)
![image](https://github.com/user-attachments/assets/d83c0f4b-b46d-4a79-b0a8-366d2fb0bb0f)
4. Pantallazo de las películas con la imagen generada con la API.
![image](https://github.com/user-attachments/assets/0fb3ce1a-3977-4603-9695-7d15dbcaface)
![image](https://github.com/user-attachments/assets/0c3832c3-639d-4d68-b752-a3c62a0d76c9)
6. Pantallazo del resultado de la ejecución del archivo check_embeddings_db.py
7. Pantallazo del resultado de la ejecución del archivo check_rec_sys_db.py

### Entregable para la semana del 23 de septiembre de 2024

Debe convertir el sistema de recomendación en una app del proyecto. Debe tener un nuevo item en la barra de navegaciónsimilar al de News. En esta app debe haber un campo para escribir el __prompt__ que generará la recomendación. Ejemplo: Película de la segunda guerra mundial. El sistema deberá mostrar la película recomendada, la imagen y la descripción. La vista debe ser similar a la búsqueda de película en la app Movies.

Archivo pdf con:

1. GitHub del proyecto
2. Pantallazo de la app funcionando con una búsqueda y el resultado
