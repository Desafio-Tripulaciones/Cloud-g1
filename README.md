# CLOUD-G1

## DÍA 1.

El primer día del Desafío, hemos previsto crear una organización en Github, que contiene un repositorio principal con sus  submódulos para cada una de las verticales. Así podremos reunir el trabajo de todas las verticales en ese repositorio principal, donde trabajaran de forma independiente en sus propios repositorios (submódulos). Al mismo tiempo hemos definido los diferentes permisos a los integrantes de la organización, con respecto al repositorio principal y sus respectivos submódulos.

Por otro lado, elegida la platarfoma en la nube donde vamos a trabajar, en este caso Google Cloud, hemos creado un proyecto para el Desafío, y creado una alerta de presupuesto para controlar los gastos que vayan surgiendo.

## DÍA 2.

Durante el segundo día hemos recibido una aplicación sencilla de parte de Fullstack para poder ir haciendo pruebas y levantar dicha aplicación en GCP. Con ello podremos ver los requerimientos necesarios que Fullstack iré necesitando a medida que nos vayan aportando actualizaciones y mejoras en la aplicación web. Dockerizamos la aplicación recibida para crear una imagen de esta y preparar una cloudbuild que automatice la creación de una istancia en **Cloud Run** para levantar la aplicación mediante un trigger que hace que se construya el frontend de esta, siempre que se actualice la rama main del proyecto donde se encuentra el código de Fullstack y sus actualizaciones. 

Por otro lado hemos provisto al grupo de Data de una base de datos relacional SQL **PostgreSQL 15**, levantando una instancia para ello. Les facilitamos una IP pública, usuario y contraseña para que puedan conectarlo con **pgAdmin** que es la herramienta que ellos utilizarán para la creación y diseño del contenido de la Base de Datos.
