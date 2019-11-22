## Descarga el repositorio de trabajo
A continuación debes seguir el enlace del correo electrónico que has debido recibir para hacer el ejercicio. 

Cuando accedas al enlace, el sistema de **GitHub Classroom** va a crear dentro de **KungFuClass** un repositorio personalizado con tu alias de GitHub que es sobre el que tienes que trabajar para ir haciendo el ejercicio.

En ese repositorio ya tienes una plantilla inicial con cuatro ficheros:
* Fichero **.gitignore** preparado para WordPress, aunque casi no va hacer falta porque la raíz de este repositorio va a ser la propia carpeta del plugin.
* Fichero **LICENSE** con la licencia GPL que ampara a esta plugin para que sea software libre.
* Fichero **README.md** con unas sencillas instrucciones de lo que tienes que hacer para completar el ejercicio. Aunque tienes mayor detalle en el artículo del blog de KungFuPress.
* Fichero **kfc-form-autoevaluacion-tu-alias.php** que es el propio plugin y donde vas a trabajar prácticamente todo el tiempo. 

Cómo ves contiene un esqueleto muy básico para empezar a desarrollar el plugin.

Una vez echas las presentaciones, vas a copiar el repositorio a tu entorno de desarrollo y entonces ¡por fin! podrás empezar a escribir código en él. 🙌

Si todo esto te parece engorroso esta primera vez pronto te resultará algo natural, y no solamente tiene utilidad para hacer ejercicio de clase, sino que, he escogido precisamente este sistema, porque es el que utilizan actualmente todos los desarrolladores, trabajen en WordPress, JavaScript, PHP, Java o lo que sea. De hecho esto es lo que deberías encontrar en cualquier entorno de trabajo serio, y si no, puedes aportarlo tú.

## Descarga del repositorio en local
Para copiar la URL del repositorio, ve a la página inicial del mismo, busca el botón verde **Clone or download** y copia la URL al portapapeles 📋

Ahora abres una terminal en tu equipo si estás en Mac o Linux, o desde una terminal especial para Git en Windows (también te hablé de ello en el correo) buscas el directorio donde tienes instalado tu WordPress local. 

Ve a la carpeta **wp-content/plugins**, ahí tecleas: ```git clone``` y pegas la URL del portapapeles. Pulsa ```enter``` para ejecutar el comando. 

Accede al directorio **kfc-form-autoevaluacion-tu-alias.php** que se acaba de crear.

Si tu shell está preparada para trabajar con repositorios de git es posible que el prompt cambie ligeramente de aspecto cuando estés dentro de un repositorio. Como ves dentro de este directorio están todos los archivos que estaban en GitHub.

## Accede al código desde el entorno de desarrollo
Ahora puedes empezar a trabajar desde Visual Studio Code, abres el programa y dentro abres la carpeta del plugin.

Para ver que todo está funcionando correctamente puedes modificar en la cabecera del plugin el campo **Author** con tu nombre.
Abres en tu navegador tu sitio WordPress local y accedes al panel de administración y en el menú de plugins verás el plugin **kfc-form-autoevaluacion-tu-alias** desactivado pero ahora debe aparecer tu nombre en él.

## Volviendo al terminal y a git
Por último, una vez que has comprobado que todo está preparado para empezar a trabajar debes actualizar el repositorio y subirlo a GitHub:
* Haz un ```git status``` para ver que hay un fichero que se ha modificado.
* Si llevaras un rato trabajando y no recordaras bien lo que has hecho puedes teclear ```git diff`` para que te muestre las líneas que han cambiado dentro del archivo. Sales de git diff pulsando la letra ```q```.
* Teclea ```git add .``` para agregar los cambios al **stage** de git.
* Agrega los cambios al repositorio local con ```git commit -m"Modifica el valor de author en la cabecera del plugin"```
* Con esto los cambios ya están recogidos en tu repositorio local, pero ahora debes hacer un ```git push``` para subir los cambios al repositorio remoto de GitHub, el que está en KungFuClass.
* Entra a la web de GitHub para ver que efectivamente los cambios se han subido.
* Sigue creando el plugin, haciendo commit, push a github y vuelta a empezar hasta terminar el tutorial. 

## Resumiendo
Esta sería la dinámica normal de trabajo: 
* Descargar el contenido del repositorio dentro de la carpeta **plugins** de una instalación local de WordPress.
* Ir haciendo los pasos del tutorial
* En cada uno de los apartados que voy marcando puedes hacer un commit y un push para que el trabajo quede recogido por etapas, de este modo podré ir viendo cada commit que hayas realizado para ver como has ido progresando, si te has equivocado en algún punto o si has introducido alguna mejora respecto del original.

El flujo sería igual en un entorno real de trabajo donde necesitaras implementar alguna mejora o nueva característica en el código e ir guardando los pasos a medida que las cosas vayan funcionando, reflejando los cambios que vas realizando mediante [buenos mensajes de commit](https://github.com/RomuloOliveira/commit-messages-guide/blob/master/README_es-AR.md)

¿Has encontrado algún error? :see_no_evil: ¿Tienes una propuesta para mejorar esta guía? :happy: Si es así te agradezco infinito que [me dejes un issue](https://github.com/kungfuclass/como-hacer-los-ejercicios-en-kungfuclass/issues/new) :hammer_and_wrench: para mejorarlo y así poder ayudar al resto de aprendices.