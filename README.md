# ¿Por donde empezar?

Para empezar a programar lo único que precisás es una computadora, nada mas, no importa ni el Windows que tenés, lo podés hacer en cualquier computadora que funcione y luego ir siguiendo la tabla de contenidos de acá más abajo.


## 1. Instalando programas necesarios

### Un programa de terminal (donde tirar comandos al sistema)
Para programar necesitamos programas que nos ayuden, el más básico se llama **TERMINAL**, una terminal nos permite escribir comandos que nos facilitan y nos permiten la tarea de programar.

Si tu computadora tiene Windows vamos a usar **CMDER** como programa de terminal para escribir comandos.

Se puede bajar de acá:
[https://github.com/cmderdev/cmder/releases/download/v1.3.3/cmder.zip]


### Un editor de código (donde escribir nuestros programas)
Vamos a usar SublimeText, se puede bajar de acá:
[https://download.sublimetext.com/Sublime%20Text%20Build%203143%20x64%20Setup.exe]


### Un intérprete de código (para hacer andar los programas que escribimos)

El código que vamos a escribir en un principio va a ser en un lenguaje llamado **PHP**, por lo que precisamos tener instalado un programa (como sucede muchas veces, se llama igual que el lenguaje) **php** (asi con minúscula) que permite hacer andar los programas que vamos a escribir.

PHP se puede instalar de muchas maneras, la más fácil es instalando un paquete de programas llamado XAMPP que incluye muchos otros programas que vamos a usar después (es como cuando instalás el Office, vos querés solo el Word pero te clavan el Excel, el PowerPoint y otros que no vas a usar, esto es igual, XAMPP es como un Office pero para programar cosas para la web, trae PHP, Base de Datos, etc):

https://www.apachefriends.org/xampp-files/7.1.10/xampp-win32-7.1.10-0-VC14-installer.exe


## 2. Conceptos básicos para memorizar (sí, MEMORIZAR, no hay que olvidarselos ni en pedo)


### TERMINAL
Es una interfaz de usuario de nuestro sistema (Windows, ponele) permite llamar programas (es decir, escribir comandos)

Lista de programas accesibles desde la terminal (**CMDER**):
- [mkdir](#mkdir)
- [cd](#cd)
- [ls](#ls)
- [pwd](#pwd)
- [php](#php)


### WORKING DIRECTORY

Es la carpeta donde estamos parados, es como cuando abris el "Equipo" o "Documentos" o cualquier carpeta en Windows, si le das crear "Nueva Carpeta" o querés borrar algo, vas a ver que TODO se hace contra la carpeta que tenés abierta en el explorador.

Con la terminal es IGUAL, uno tiene que en lugar de ver, "moverse" (con el comando **cd**) hasta pararse en la carpeta sobre la que quiera hacer cosas o ejecutar programas.

- Si tiro un comando llamado "ls" y estoy parado en "Documentos" voy a ver una listita con los mismos archivos y carpetas que si abriera el explorador de Windows en la carpeta "Documentos".

- Si tiro un comando llamado "mkdir probando" y estoy parado en "Documentos" se va a crear una carpeta llamada "probando" dentro de la carpeta "Documentos".

- Si quisiera crear una carpeta "probando" en el escritorio, debería **CAMBIAR** el working directory, podés probarlo abriendo una terminal nueva y haciendo "cd Escritorio", todo los archivos o comandos que escribas en adelante se ejecutarán como si estuvieras trabajando sobre el Escritorio de tu pc.


## 3. Qué diferencia hay entre un programa y un comando
Rara vez uno llama un programa solo poniendo su nombre, en general le agregamos varias opciones, ese pedacito de texto que es el nombre del programa más sus opciones es lo que llamamos COMANDO:

Ejemplo 1
---
mkdir es un programa para crear una carpeta, pero para llamarlo SIEMPRE requiere que le digamos el nombre de la carpeta
```
mkdir mi_carpeta_nueva
```

Ejemplo 2
---
Casi todos los programas aceptan que se los llame con un "-h" despues de su nombre como opción para mostrar la ayuda:
```
mkdir -h
ls -h
```

Ejemplo 3
---
Ver la versión de PHP:
```
php -v
```

## 4. Aprendiendo a tirar comandos

Para tirar comandos lo primero que hay que hacer es abrir una terminal, cuando abrimos **CMDER** estamos abriendo una terminal.

Es importante mentalizarte esto: **UN COMANDO ES UN PROGRAMA**, y cuando usamos una terminal estamos llamando a programas ya instalados en nuestro sistema.

### Programas ya instalados que vas a usar (MUCHO)

#### mkdir
Crea una carpeta con el nombre que le pongamos.

Ejemplo:
```
mkdir ejemplo1
```

Va a crear una carpeta llamada ejemplo1 en el working directory, podes verificar que fue creada tirando el comando **ls**.

#### cd
Permite **CAMBIAR EL WORKING DIRECTORY**, es decir, abriste la terminal y querés moverte a una carpeta que recien creaste o que ya existe llamada "ejemplo1":
```
cd ejemplo1
```

#### ls
Si lo ponemos asi tal cual, muestra archivos y carpetas del **working directory**

#### pwd
Nos dice en que carpeta estamos parados (el **working directory** )

#### php
Permite ejecutar programas hechos con php (y que tengan el nombre terminando en .php)

Ejemplo:
```
php miprogramita.php
php subcarpeta/mi_otro_programita.php
```
