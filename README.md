<p align='left'>
    <img src='https://static.wixstatic.com/media/85087f_0d84cbeaeb824fca8f7ff18d7c9eaafd~mv2.png/v1/fill/w_160,h_30,al_c,q_85,usm_0.66_1.00_0.01/Logo_completo_Color_1PNG.webp' </img>
</p>

# Proyecto Final | [**Liliana GameStore**](https://lilianagamesstore.onrender.com)

<p align="center">
  <img src="https://www.vodacom.co.za/sites/vodacomcoza/files/styles/extra_large_landscape/public/2021-06/microsoft-store-banner.jpg?itok=viZ4SSQy" />
</p>

---

<div align="center">

## **:man_technologist: COLABORADORES DEL PROYECTO**

</div>

<table align="center">
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/GSBenevento"><img src="https://avatars.githubusercontent.com/u/129414715?v=4" width="100px;" alt="Gabriel Benevento"/><br /><sub><b>Gabriel Benevento</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Galbfran"><img src="https://avatars.githubusercontent.com/u/107511558?v=4" width="100px;" alt="Franco Galbiati"/><br /><sub><b>Franco Galbiati</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Insaurralde38"><img src="https://avatars.githubusercontent.com/u/127244677?v=4" width="100px;" alt="Diego Insaurralde"/><br /><sub><b>Diego Insaurralde</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/NicolasRojas09"><img src="https://avatars.githubusercontent.com/u/106163351?v=4" width="100px;" alt="Nicolás Rojas"/><br /><sub><b>Nicolás Rojas</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/DaveVrl"><img src="https://avatars.githubusercontent.com/u/110915236?v=4" width="100px;" alt="David Varela"/><br /><sub><b>David Varela</b></sub></a><br /></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/gabivillarec"><img src="https://avatars.githubusercontent.com/u/71297222?v=4" width="100px;" alt="Gabriel Villalobos"/><br /><sub><b>Gabriel Villalobos</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

<div align="center">
    
## **📌 TECNOLOGÍAS UTILIZADAS**

![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![HTML5](https://img.shields.io/badge/-HTML5-E46625?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-385BF4?style=flat-square&logo=css3)
[![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react&link=https://es.react.dev/)](https://es.react.dev/)
[![Redux](https://img.shields.io/badge/Redux-7241BE.svg?style=flat-square&logo=redux&logoColor=white&link=https://es.redux.js.org/)](https://es.redux.js.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7C01FD?style=flat-square&logo=bootstrap&logoColor=white&link=https://getbootstrap.com/)](https://getbootstrap.com/)
[![Vite](https://img.shields.io/badge/Vite-9E40FF?style=flat-square&logo=vite&logoColor=F7CA00&link=https://vitejs.dev/)](https://vitejs.dev/)

[![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=Node.js&link=https://nodejs.org/es)](https://nodejs.org/es)
[![Express.js](https://img.shields.io/badge/Express.js-404D59.svg?style=flat-square&logo=express&link=https://expressjs.com/es/)](https://expressjs.com/es/)
[![Sequelize](https://img.shields.io/badge/Sequelize-31396A?style=flat-square&logo=Sequelize&logoColor=68AEE8&link=https://sequelize.org/)](https://sequelize.org/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-404D59?style=flat-square&logo=postgresql&logoColor=61DAFB&link=https://www.postgresql.org/)](https://www.postgresql.org/)
![MercadoPago](https://img.shields.io/badge/-MercadoPago-419BE4?style=flat-square&logo=mercadopago&logoColor=0D0082)

</div>

---

<div align="center">

## **📋 DESCRIPCIÓN**

</div>

Liliana Games está diseñada para brindar una experiencia de compra fluida a los usuarios interesados en adquirir productos relacionados con la informática, como videojuegos, hardware de computadoras y accesorios. La aplicación tiene como objetivo crear una interfaz fácil de usar mientras ofrece una amplia gama de productos para satisfacer las diversas necesidades de entusiastas de la tecnología, profesionales y gamers. En ella podremos ver:

  - **Diseño adaptable**
  - **Catálogo de productos**
  - **Autenticación de usuarios**
  - **Carrito de compras**
  - **Pagos seguros**
  - **Seguimiento de pedidos**

Es necesario contar minimamente con la última versión estable de NodeJS y NPM. Asegúrate de contar con ella para poder instalar correctamente las dependecias necesarias para correr el proyecto. Actualmente las versiónes necesarias son:

-  **Node**: 12.18.3 o mayor
-  **NPM**: 6.14.16 o mayor

Para verificar que versión tienes instalada:

```bash
node -v
npm -v
```

<br />

---

<div align="center">

## **⚠️ IMPORTANTE!**

</div>

**1.** Sí deseas clonar el repositorio en tu computadora para ejecutarlo de manera local, primero es necesario instalar las depencencias de los archivos **`package.json`** tanto del Back-End, como del Front-End. Para ello es necesario que abras una terminal ubicado dentro de la carpeta **`api`** y otra terminal ubicado dentro de la carpeta **`client`**.

-  Cuando te encuentres en estas carpetas, debes ejecutar el comando

```bash
    npm install
```

**2.** En la carpeta **`api`** deberás crear un archivo llamado: **`.env`** que tenga la siguiente forma:

   ```env
       DB_USER=usuarioDePostgres
       DB_PASSWORD=passwordDePostgres
       DB_HOST=localhost
       MERCADO_PAGO=usuarioDePruebaMP
       ACCESS_TOKEN=tokenDePruebaMP
       USER_MAIL_NODEMAILER=usuarioDeNodemailer
       USER_PASS_NODEMAILER=passwordDeNodemailer
   ```

**3.** Reemplazar **`usuarioDePostgres`**, **`passwordDePostgres`**, **`usuarioDePruebaMP`**, **`tokenDePruebaMP`**, **`usuarioDeNodemailer`** y **`passwordDeNodemailer`** con tus propias credenciales para conectarte a postgres, MercadoPago y Nodemailer respectivamente. Este archivo no está incluido en este repositorio de github, ya que las credenciales son información sensible.

**4.** Adicionalmente será necesario que crees, **desde psql (shell o PGAdmin)**, una base de datos llamada **`lilianadb`**. Si no realizas este paso de manera manual no podrás visualizar el proyecto de manera local.

**5.** Para visualizar la aplicación desde el navegador, en la terminal previamente abierta ubicada dentro de la carpeta **`api`**, debes ejecutar el comando:


        npm start

y en la terminal previamente abierta ubicada dentro de la carpeta **`client`**, debes ejecutar el comando:


        npm run dev

Ingresando a <http://localhost:3000> desde el navegador, podrás ver el proyecto en tiempo real.

<br />

---

<br />

<div align="end">

Hecho con 💙💛💙 por [**DIEGO INSAURRALDE**](https://www.linkedin.com/in/djinsaurralde38/) 🐒

</div>
