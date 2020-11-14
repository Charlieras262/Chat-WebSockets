# Bienvenidos a Chat WebSockets
Este aplicativo es muy útil para el intercambio de información entre personas.

# Instalación

## Modulo Auth-Service

Es necesario previo a la instalación se cuentes con los siguientes programas:
- JDK 10
- IntellijIDEA (Opcional)
- Apache Maven 3.3.5

1. Instalar dependencias y compilar
~~~
	$: mvn clean install
~~~
2. Ejecutar el Jar que genera en la carpeta del proyecto en target
~~~
	/ruta/del/proyecto/auth-service/target/*.jar
~~~


## Modulo Chat-Service
Es necesario previo a la instalación se cuentes con los siguientes programas:
- JDK 14
- IntellijIDEA (Opcional)
- Apache Maven 3.3.5

1. Instalar dependencias y compilar
~~~
	$: mvn clean install
~~~
2. Ejecutar el Jar que genera en la carpeta del proyecto en target
~~~
	/ruta/del/proyecto/chat-service/target/*.jar
~~~

## Modulo JWT-WebClient
Es necesario previo a la instalación se cuente con los siguientes programas:
- Node.js 10.13.0
- Visual Studio Code

1. Instalar dependencias
~~~
	$: npm install
~~~
2. Compilar 
~~~
	$: npm start
~~~
3. Dirigirse a `http://localhost:3000` en esta ruta se encuentra levantado el servidor de desarrollo del proyecto.

Imagen del Sistema

![enter image description here](https://raw.githubusercontent.com/Charlieras262/Chat-WebSockets/main/thumbnail.png)
