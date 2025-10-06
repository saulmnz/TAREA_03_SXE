# PRÁCTICA DOCKER 🐳: 
![Docker](https://img.shields.io/docker/pulls/library/alpine?style=for-the-badge) ![Docker Image](https://img.shields.io/badge/image-alpine-lightgrey?style=for-the-badge) ![Docker Version](https://img.shields.io/badge/docker-v24.0-blue?style=for-the-badge)


## 1 - DESCARGAR IMAGEN ALPINE Y COMPROBAR QUE ESTÁ EN EL EQUIPO ⚡

- **Consultamos la página oficial de Docker para comprobar cómo es la instalación de la imagen Alpine. Con el comando `docker pull alpine` la imagen quedará
instalada y con `docker images` comprobaremos que esto sea verídico.**

<br>

![FOTO1](CAPTURAS/1.png)

---


## 2 - DESCARGAR CONTENEDOR SIN NOMBRE 🖥️

- **El contenedor está arrancado mientras el usuario esté dentro de él; al salir, el contenedor se detiene. En la captura se aprecia cómo
iniciamos una instancia en la terminal y ejecutamos el shell como proceso principal. Docker creará el contenedor iniciándolo sin problema; por lo tanto,
sí, está arrancado.**

<br>

![FOTO2](CAPTURAS/2.png)

---

## 3 - CREAR CONTENEDOR NOMBRE 'dam_alp1' Y ACCESO A ESTE 💾

- **Creamos el contenedor `dam_alp1`. Una vez creado, comprobamos que podemos acceder a él en cualquier momento.**

<br>

![FOTO3](CAPTURAS/3.png)

---

## 4 - COMPROBAR IP Y PING A GOOGLE.COM 📦

- **Para realizar este apartado, deberemos instalar las `iputils`, ya que no las incluye la imagen por defecto. Así podremos 
ejecutar los comandos IP necesarios. Una vez instalado el paquete, comprobamos la conexión con Google y mostramos la IP del contenedor.**

<br>

![FOTO4](CAPTURAS/4.png)

---
 
## 5 - CONTENEDOR NOMBRE 'dam_alp2' PING ENTRE CONTENEDORES 🖧

- **En este apartado, deberemos realizar los comandos usados anteriormente. Primero crearemos el contenedor 
con el nombre deseado, instalamos las `iputils` y utilizamos el comando `ping` hacia la IP que se muestra en el apartado anterior
(IP del contenedor `dam_alp1`), comprobando así la conectividad entre contenedores.**

<br>

![FOTO5](CAPTURAS/5.png)

---

## 6 - SALIR DEL TERMINAL ⛔

- **Al salir del contenedor, este se detiene pero no se elimina. Se puede comprobar el estado de los contenedores con el comando que se muestra en la imagen.**

<br>

![FOTO6](CAPTURAS/6.png)

---

## 7 - MEMORIA EN DISCO QUE SE OCUPÓ 📊

- **Para comprobar la memoria en disco, deberemos ejecutar el siguiente comando:**

<br>

![FOTO7](CAPTURAS/7.png)

---

## 8 - CUÁNTA RAM OCUPAN LOS CONTENEDORES, COMANDO 📊

- **El comando para saber cuánta RAM ocupa un contenedor es: `docker stats 'nombre_contenedor'`.**

<br>

![FOTO8](CAPTURAS/8.png)
