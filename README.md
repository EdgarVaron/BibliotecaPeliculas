# *Importante:* Descargar Gson para poder ejecutar el programa
  
https://mvnrepository.com/artifact/com.google.code.gson/gson

Dentro de la carpeta ```principal``` ejecutar la clase `PrincipalConBusqueda`

## Los conceptos aplicados en este programa fueron:

1. Lo que es una API y su funcionamiento básico
  - Cómo funciona la API de OMDb para buscar películas
    - Realizar una consulta en la API de OMDb usando Postman
      - Cómo integrarse con la API de OMDb en Java, utilizando las clases

2. Lo que son las bibliotecas de Java
  - Cómo instalar la biblioteca Gson en el proyecto, descargando y configurando su archivo jar
    - A usar la biblioteca Gson para convertir json en un objeto Java
      - Cómo crear un Record en Java, que es una estructura similar a una clase, pero utilizada solo para representar datos
        - A flexibilizar la conversión de un json en un objeto Java, siguiendo la documentación de la biblioteca Gson

3. Lo que son las excepciones en Java y cómo tratarlas con el bloque try/catch
  - Cómo detectar diferentes tipos de excepciones que pueden ocurrir en el código
    - Cómo crear una clase exception personalizada
      - A realizar una validación y lanzar una excepción en caso de error
     
4. Escribir datos en un archivo utilizando clases del paquete java.io;
  - Serializar un objeto Título a formato JSON, utilizando la biblioteca Gson vista anteriormente;
    - Generar el archivo en formato JSON, con un formato más elegante, utilizando el método setPrettyPrinting.
