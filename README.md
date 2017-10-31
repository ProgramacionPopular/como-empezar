# ¿Por donde empezar?

Para empezar a programar lo único que precisás es una computadora, nada mas, no importa ni el Windows que tenés, lo podés hacer en cualquier computadora que funcione y luego ir siguiendo la tabla de contenidos de acá más abajo.

## 1. Instalando programas necesarios

Para programar necesitamos programas que nos ayuden, el más básico se llama **TERMINAL**, una terminal nos permite escribir comandos que nos facilitan y nos permiten la tarea de programar.

Si tu computadora tiene Windows vamos a usar **CMDER** como programa de terminal para escribir comandos.

Se puede bajar de acá:
[https://github.com/cmderdev/cmder/releases/download/v1.3.3/cmder.zip]


## 2. Aprendiendo a tirar comandos

Para tirar comandos lo primero que hay que hacer es abrir una terminal, cuando abrimos **CMDER** estamos abriendo una terminal.

Es importante mentalizarte esto: **UN COMANDO ES UN PROGRAMA**, y cuando usamos una terminal estamos llamando a programas ya instalados en nuestro sistema.

### Programas ya instalados que vas a usar (MUCHO)

Lista de programas accesibles desde la terminal (**CMDER**)
=================
[mkdir](#mkdir)
[cd](#cd)
[ls](#ls)
[pwd](#pwd)
[php](#php)

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
