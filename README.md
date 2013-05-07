## Basics

Este proyecto utiliza Moovweb para crear una version movil del sitio www.unicentrobogota.com.

## Compilación 

Este proyecto utiliza el SDK de Moovweb, el cual debe estar instalado. Para esto simplemente vaya a - [the download page on the Moovweb site](http://console.moovweb.com/download) descargue e instale.

Los siguientes con enlaces útiles [the page about the scripts folder](http://console.moovweb.com/learn/reference/configuration/pages) para comenzar a programar en Tritium y  [documents on the stylesheets folder](http://console.moovweb.com/learn/reference/configuration/stylesheet) con información acerca de como se estructuran los stylesheets.

## Ejecución

Desde linea de comando ejecúte:

    sudo moov server --auto-hosts

Luego, tan solo vaya a [mlocal.unicentrobogota.com](http://mlocal.unicentrobogota.com)!

## Despliegue

Moovweb utiliza un sistema de desplliegue basado en git-based para desplegar en la consola de Moovweb o simplemente para guardar sus cambios ejecute

    git add --all
    git commit -m 'Nuevo codigo'
    git push origin master

## Más información

Documentación de Moovweb [console.moovweb.com](http://console.moovweb.com).

Cualquier bug puede ser reporatado a help@moovweb.com o en particular de este proyecto via Git.
