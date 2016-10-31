# Sistemas y Tecnologías Web. Creación de Paquete en NodeJS.


## Introducción

El objetivo de esta práctica es crear un package **NodeJS** y publicarlo en npm. El paquete se construye a partir de el código que haya desarrollado en la práctica anterior.

##Tutorial para su instalación

Instalar el paquete

```shell
npm install -g gitbook-start-alex-moi-nitesh
npm install --save gitbook-start-alex-moi-nitesh
```

Creación de directorio

```shell
gitbook-start-alex-moi-nitesh -d [nombre directorio]
```

##Tutorial para su ejecución

Para ejecutar, ponemos el siguiente comando:

```shell
gitbook-start-alex-moi-nitesh [opciones]
```
[opciones] 
*    -a: Especificar el autor del gitbook
*    -n: Especificar el nombre del gitbook
*    -d: Especificar el nombre del directorio(Obligatorio)
*    -u: Especificar la url del repositorio git
*    -h: Help (ayuda)

Después de ejecutar el comando se genera una estructura de directorios para poder desarrollar un gitbook y publicarlo en github. 

La estructura que genera es similar a la siguiente:
![enter image description here](https://i.gyazo.com/f8eaf0e19ccf15b6ac25a19f3b02d009.png)

Una vez instalado y ejecutado, desde el directorio generado (Book en la imagen anterior) hacemos:

```shell
npm install
```

Una vez completado los "ficheros.md" de nuestro book, para construirlo y publicarlo hacemos:

```shell
gulp build
gulp deploy
```

Donde gulp build nos generará un directorio gh-pages con el contenido del gitbook, es decir, los ficheros html creados a partir de los markdowns. Por otro lado, con gulp deploy, publicamos el contenido de dicho directorio en la rama gh-pages del repositorio git.

Un ejemplo de la versión final del gitbook sería: [Ejemplo](https://alu0100782851.github.io/prueba/)


## Enlaces importantes
*  [Página en NPM](https://www.npmjs.com/package/gitbook-start-alex-moi-nitesh)
*  [Repositorio GitHub](https://github.com/ULL-ESIT-SYTW-1617/creacion-de-paquetes-y-modulos-en-nodejs-alex-moi)
*  [Descripción de la práctica](https://casianorodriguezleon.gitbooks.io/ull-esit-1617/content/practicas/practicanm.html)
*  [Campus Virtual](https://campusvirtual.ull.es/1617/course/view.php?id=1175)

## Autores

* Alexander Cole Mora   | [Página Personal](http://alu0100767421.github.io/)
* Moisés Yanes Carballo | [Página Personal](http://alu0100782851.github.io/)
* Nitesh Gul Ramnani    | [Página Personal](http://alu0100814651.github.io/blog/)

![Universidad de La Laguna](https://github.com/ULL-ESIT-SYTW-1617/tareas-iniciales-alex-moi/blob/master/images/logotipo-principal.png?raw=true)