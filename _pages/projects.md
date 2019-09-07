---
layout: page
title: Mis Proyectos
permalink: /projects/
images: [projects.jpg]
---
# <span style="color:#1ABC9C">[Yelpcamp](https://donnattocamps.herokuapp.com)</span>
>Agosto - 2019

[![]({{site.baseurl}}/img/yelpcamp.jpg)](https://donnattocamps.herokuapp.com)

Este proyecto fue desarrollado cuando llevé el curso online **[The Web Developer Bootcamp](https://www.udemy.com/share/100YK4BkMed1hbQXg=/)**.

Es una aplicación web que permite a los visitantes (previo registro) la creación de posts acerca de campamentos, indicando nombre, costo por noche, url de imagen de campamento, descripción y ubicación.

- Cada creación de campamento hace uso del API de Google Maps para convertir la ubicación de texto a latitud y longitud.
- Cada post de campamento permite la creación de comentarios previo registro.
- Los usuarios tienen la posibilidad de editar o eliminar sus propios comentarios y posts.
- Hace uso de RESTful routing, así como autenticación mediante Passport.js
- Aplicación desplegada en Heroku.
- Base de datos no relacional alojada en mongoDB Atlas.

## Stack Utilizado

MongoDB, Express, Bootstrap, NodeJS

#### **[Repositorio del proyecto](https://github.com/donnatto/yelpcamp)**

***

# <span style="color:#1ABC9C">[Hamachi Sushi Bar](https://hamachisushi.herokuapp.com)</span>
>Julio - 2019

[![]({{site.baseurl}}/img/hamachi.jpg)](https://hamachisushi.herokuapp.com)

Este proyecto fue desarrollado junto a **[@miguelramosc2201](https://github.com/miguelramosc2201)** cuando llevamos el curso de Desarrollo de Aplicaciones Empresariales I en ISIL.

Es una aplicación web enfocada al área de restaurantes, en este caso un sushi bar.
Cuenta con un Sistema de Gestión el cuál solo puede ser accedido por personas previa autenticación.

- Permite al cliente la obtención de una reserva de atención.
- Permite al cliente contactarse mediante un mensaje indicando nombre, correo electrónico, asunto, el cuál será alojado en la base de datos.
- Permite al personal de la empresa ingreso al Sistema de Gestión haciendo uso de su codigo de trabajador.
- Permite, una vez dentro del Sistema de Gestión, la aprobación o rechazo de las reservas de los clientes.
- Permite, una vez dentro del Sistema de Gestión, la visualización de los mensajes enviados por clientes en la aplicación web.
- Aplicación web desplegada en Heroku.
- Base de datos MSSQL alojada en Microsoft Azure.

## Stack Utilizado

MS SQL, JSP, Bootstrap, Java

#### **[Repositorio del proyecto](https://github.com/donnatto/hamachi-sushi)**

