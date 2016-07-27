# Pasae
Backend Java de proyecto para aprobar la materia PASAE.

Requerimientos
--------------
Es necesario para poder ejecutar la aplicación las siguientes herramientas:
* Java 8
* [Maven](https://maven.apache.org/)

Ejecutar
--------
Para ejecutar el proyecto se debe descaragar el repositorio:
```bash
git clone git@github.com:fedeotaran/pasae.git 
```
Ahora dentro del proyecto ejecutamos el comando para descargar las dependencias:
```bash
cd pasae && mvn package
```
Terminado esto podemos ejecuar el proyecto:
```bash
mvn spring-boot:run
```
Finalmente puedes entrar a http://localhost:8080/greeting
