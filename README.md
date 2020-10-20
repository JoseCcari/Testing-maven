# Testing-maven

Primero deberemos asegurarnos tener java-jdk instalado y procedemos a instalar maven con el siguiente comando:

![Tuto-1](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial00.png?raw=true)
![Tuto-2](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial01.png?raw=true)

Una vez instalado maven y confirmando la instalacion, crearemos una nueva carpeta en la cual crearemos nuestro proyecto pero utilizando Maven para ello escribimos el siguiente comando:

![Tuto-3](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial02.png?raw=true)

Al correr el comando comenzaran a descargarse paquetes necesarios del repositorio de maven y nos pedira una serie de configuraciones para poder crear el proyecto:

![Tuto-4](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial04.png?raw=true)

Rellenamos las configuraciones ya sea por defecto o con los valores deseados y nos devolvera un mensaje de que el proyecto se ha construido correctamente:

![Tuto-5](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial05.png?raw=true)

Podemos comprobando visualizando el arbol de archivos de nuestro proyecto:

![Tuto-6](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial06.png?raw=true)

Editamos App and AppTest en estas carpetas podremos nuestro proyecto y las pruebas que deseemos realizar; tambien podemos editar el archivo pom que nos sirve para describir el proyecto de software a construir, sus dependencias de otros módulos y componentes externos, y el orden de construcción de los elementos, una vez realizado esto compilamos nuestro proyecto:

![Tuto-7](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial07.png?raw=true)

Esto nos generara un nueva carpeta llamada target que sera donde se generaran los archivos de nuestro proyecto:

![Tuto-8](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial08.png?raw=true)

Por ultimo escribimos mvn package, lo cual generara el ejecutable de nuestro proyecto:

![Tuto-9](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial09.png?raw=true)

Una vez se halla realizado la construccion y las pruebas esten correctas, podemos ver nuestro ejecutable en la carpeta target:

![Tuto-10](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial10.png?raw=tru10)

Nos ubicamos en dicha carpeta y corremos nuestro archivo para ver que todo se halla realizado correctamente:

![Tuto-11](https://github.com/Pimed23/Testing-maven/blob/main/img/Tutorial11.png?raw=true)








