---
layout: projects
title: Mis Proyectos
permalink: /projects/
images: [projects.jpg]
---
# <a href="https://donnattocamps.herokuapp.com" target="_blank">Yelpcamp</a>
>Agosto - 2019

<a href="https://donnattocamps.herokuapp.com" target="_blank"><img src="{{site.baseurl}}/img/project-yelpcamp.jpg" /></a>

Este proyecto fue desarrollado mientras llevaba el curso online <a href="https://www.udemy.com/share/100YK4BkMed1hbQXg=/" target="_blank">**The Web Developer Bootcamp**</a>

El proyecto consiste en una aplicación web que permite a los visitantes (previo registro) la creación de posts con información acerca de campamentos, indicando el nombre, costo por noche, url de imagen de campamento, descripción y ubicación.

- La creción de campamentos hace uso del API de Google Maps para convertir la ubicación de formato de texto a latitud y longitud.
- Cada post cuenta con una sección comentarios, la cual está disponible para el uso de todos los visitantes, previamente registrados.
- Los usuarios tienen la posibilidad de editar o eliminar sus propios comentarios y posts.
- Hace uso de RESTful routing, así como autenticación mediante el uso de la librería Passport.js
- La aplicación está desplegada en Heroku.
- El backend fue construido utilizando el framework Express, el cual se ejecuta en un entorno NodeJS.
- La aplicación hace uso de una base de datos no relacional MongoDB, la cual se encuentra alojada en mongoDB Atlas.

### Stack Utilizado

MongoDB, Express, Bootstrap, NodeJS

#### <a href="https://github.com/donnatto/yelpcamp" target="_blank">Repositorio del Proyecto en Github</a>

***

# <a href="https://hamachisushi.herokuapp.com" target="_blank">Hamachi Sushi Bar</a>
>Julio - 2019

<a href="https://hamachisushi.herokuapp.com" target="_blank"><img src="{{site.baseurl}}/img/project-hamachi.jpg" /></a>

Este proyecto fue desarrollado junto a <a href="https://github.com/miguelramosc2201" target="_blank">@miguelramosc2201</a> con fines de uso académico, cuando llevamos el curso de Desarrollo de Aplicaciones Empresariales I en ISIL.

El proyecto consiste en una aplicación web enfocada al área de restaurantes, en este caso un sushi bar.
Cuenta con un Sistema de Gestión el cuál solo puede ser accedido por sus trabajadores con el ingreso de sus credenciales.

- Permite al cliente la creación de reservas de atención.
- Permite al cliente contactarse mediante un mensaje indicando su nombre, correo electrónico y asunto, el cuál se envía a una base de datos relacional MS SQL.
- Permite al personal de la empresa ingreso al Sistema de Gestión haciendo uso de sus credenciales.
- Permite, una vez dentro del Sistema de Gestión, la aprobación o rechazo de las reservas de atención.
- Permite, una vez dentro del Sistema de Gestión, la visualización de los mensajes enviados por clientes dentro de la aplicación web.
- La aplicación web está desplegada en Heroku, en un entorno de ejecución Java.
- Hace uso de una base de datos relacional MS SQL alojada en Microsoft Azure.

### Stack Utilizado

MS SQL, JSP, Bootstrap, Java

#### <a href="https://github.com/donnatto/hamachi-sushi" target="_blank">Repositorio del proyecto en Github</a>
