# Fbcmd4j

Facebook CLI client. For educational purposes only.

Evidencia para la materia de Computacion en Java

## Instalación

Para la correcta realizacion de este repositorio se instalaron los siguientes componentes:

+ JDK 8 en la version mas reciente (en este caso fue la 172 para windows x64)

+ GitHub para escritorio o Git en linea de comando

+ Un IDE con el cual podamos manejar el repositorio de GitHub (en este caso usaremos eclipse)

+ Una vez que nos aseguramos de tener los requisitos antes mencionados procederemos a realizar la clonacion del repositorio, importarlo a eclipse y finalmente crear, exportar y ejecturar el archivo .jar

+ **Clonar el repositorio**  
```
git clone https://github.com/hjcasasv/fbcmd4j.git
```
+ **Importar a Eclipse**  
1. Dar clic en `File -> Import -> Existing Projects into Workspace`.
2. Se deberá seleccionar la carpeta donde está el proyecto ya clonado.

+ **Exportar .jar**  
1. Dirigirse a la barra de herramientas de Eclipse.
2. Dar click en `File -> Export -> Runnable JAR File -> Next`.
3. Seleccionar la clase que tiene el método main de nuestro programa como `Launch configuration`.
4. Dar click en `Browse` para seleccionar la carpeta de destino.
5. Seleccionar (*Extract required libraries into generated JAR*).
6. Dar click en `Finish`.

+ **Ejecutar .jar**  
1. Abrir la carpeta previamente seleccionada y copiar el archivo JAR a la carpeta `C:\Program Files\Java\jdk1.8.0_144\bin`.
2. Abrir la terminal (*utilizar privilegios de administrador en Windows*).
3. Navegar a la carpeta `fbcmd4j/bin` donde se encuentra el archivo `fbcmd4j.jar`.
4. Ejecutar el comando `java -jar fbcmd4j.jar`.

## Uso

**Configurar tokens**   
1. Seleccionar la opción 0 `Configurar tokens`.
2. Escribir identificador de aplicación.
3. Escribir clave secreta de aplicación.

**Obtener el NewsFeed**   
1. Seleccionar la opción 1 `NewsFeed`.
2. Escribir 'Si' en caso de querer guardar los posts en un archivo.
	* Escribir el número de posts a guardar.

**Obtener el Wall**   
1. Seleccionar la opción 2 `Muro`.
2. Escribir 'Si' en caso de querer guardar los posts en un archivo.
	* Escribir el número de posts a guardar.

**Publicar un Estado**   
1. Seleccionar la opción 3 `Publicar Estado`.
2. Escribir el estado deseado.

**Publicar un Link**   
1. Seleccionar la opción 4 `Publicar Link`.
2. Escribir el link deseado.

**Salir del programa**
1. Seleccionar la opcion 5 `Salir`.

## Créditos

Hector Casas (hjcasasv) -- Creador de este repositorio y alumno de la materia Computacion en Java

Jose Manuel (jm66) -- Creador del repositorio original de donde se obtuvo la informacion

## Licencia

Este repositorio fue creado bajo la licencia de MIT License. Para mayor informacion acerca de la licencia ir al archivo LICENSE.
