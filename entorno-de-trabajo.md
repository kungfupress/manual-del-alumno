# Preparación del entorno de trabajo

## Requisitos

Necesitas algunos requisitos antes de empezar a hacer este ejercicio:
* Instalación local de WordPress para desarrollar y probar tu plugin.
* Instalar **Git** en local, tener una cuenta en GitHub y unas nociones básicas de Git.
* Entorno de desarrollo o editor de código en tu equipo. Te recomiendo **Visual Code Studio** por ser de código abierto, gratuito y ligero. Además ¡está de moda!

Para realizar los tutoriales y poder ir comprobando lo que vas haciendo te hará falta colocar la carpeta del plugin (o del tema cuando toque) dentro de la carpeta **plugins** o **themes** de una instalación local de WordPress.

### WordPress local
La instalación de WordPress local la puedes instalar con cualquiera de estas soluciones, las pongo por orden de facilidad de instalación y uso:
* Utilizando [Local by Flywheel](https://localbyflywheel.com/) o [DesktopServer](https://serverpress.com/).
* Cualquier aplicación tipo WAMP (windows), MAMP(mac),  LAMP(linux) o XAMPP (para los tres).
    * [Wamp Server](http://www.wampserver.com/en/).
    * [MAMP](https://www.mamp.info/en/)
    * [Instalar LAMP en Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/como-instalar-en-ubuntu-18-04-la-pila-lamp-linux-apache-mysql-y-php-es).
    * [XAMPP - ApacheFriends](https://www.apachefriends.org/es/index.html).
* Utilizando Docker con un hub de WordPress
    * https://neliosoftware.com/es/blog/como-usar-docker-para-desarrollar-en-wordpress/
    * https://platzi.com/blog/wordpress-en-docker/
    * https://hub.docker.com/_/wordpress

### Git
Si  necesitas repasar tus conocimientos de Git te recomiendo el vídeo [Aprende Git en 30 minutos](https://www.youtube.com/watch?v=QGKTdL7GG24) (de momento bastaría con que controles hasta el minuto 15).
Si prefieres leer o quieres profundizar un poco más te recomiendo el libro [Aprende Git y de paso GitHub](https://github.com/JJ/aprende-git). 

Si utilizas Windows puedes descargar [Git para Windows](https://gitforwindows.org/), si usas Mac puedes instalar Git con [Homebrew](https://brew.sh/index_es )y si eres linuxero con tu gestor de paquetes favoritos aunque en la versiones actuales suele venir de serie. Si necesitas más información sobre la instalación te recomiendo el artículo ["Como instalar git en Windows, Mac y Linux"](https://filisantillan.com/como-instalar-git/)

### GitHub
Posiblemente ya tengas una cuenta en GitHub y puedes usar esa. Si no la tienes es un buen momento para [crear una](https://github.com/join?source=kungfupress). 

Si te vas a dedicar al desarrollo de código esta será una de las redes sociales donde más deberías trabajar tu perfil, así que elige un buen nombre de usuario que refleje tu marca personal. Procura que no lleve números a no ser que el número forme parte de la marca.

Más adelante te explicaré como trabajar con GitHub para crear, modificar y compartir tu código, de momento basta con que tengas o te crees una cuenta.

### Primera vez con Git
Si es la primera vez que vas a usar git desde este equipo debes configurar un par de cosas más. Para ello puedes utilizar el terminal de Linux o Mac o la aplicación Git Bash en Windows, si has seguido los pasos que te di para instalar Git ya lo debes tener todo listo:
* Usuario y correo para los registros(logs) de los commits. Para ello teclea estas dos órdenes:
```
git config --global user.name “Pepe Pérez"
git config --global user.email “pepeperez@dominio.com" 
```

## Entorno de desarrollo
Si no estás habituado a ningún IDE (entorno de desarrollo), te recomiendo que empieces con [Visual Studio Code](https://code.visualstudio.com/). 

Una vez instalado puedes descargar algún plugin de este editor para WordPress, el más interesante es **WordPress VS Code Extension Pack**. Si da algún fallo durante la instalación o te pide instalar más cosas y no sabes seguir,  déjalo deshabilitado de momento, pero sigue con el ejercicio que es lo importante. Espero escribir un artículo sobre este tema en cuanto pueda.

¿Has encontrado algún error? :see_no_evil: ¿Tienes una propuesta para mejorar esta guía? :happy: Si es así te agradezco infinito que [me dejes un issue](https://github.com/kungfuclass/como-hacer-los-ejercicios-en-kungfuclass/issues/new) :hammer_and_wrench: para mejorarlo y así poder ayudar al resto de aprendices.