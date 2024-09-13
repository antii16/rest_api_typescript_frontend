# Administrador de productos (FRONTEND)
Aplicación para registrar productos pudiendo editar o eliminarlo a través de una REST API's. También permite cambiar la disponibilidad.

En este proyecto se introducen las REST API's y el stack PERN (PostgreSQL + Express + React + Node.js), entre otros conceptos. Para organizar mejor el proyecto se ha dividido el <a href="https://github.com/antii16/rest-api-node-ts-server" target="_blank">backend</a> y el frontend en dos repositorios diferentes. 

<b> Proyecto: <a href="https://rest-api-typescript-frontend-cyan.vercel.app/" target="_blank">Administrador de Productos</a></b>



### Idea del proyecto 
Noveno proyecto realizado durante el curso de <a href="https://www.udemy.com/course/react-de-principiante-a-experto-creando-mas-de-10-aplicaciones/?couponCode=KEEPLEARNING">React y TypeScript</a>.

<a href="https://github.com/antii16/bebidas-react"> Ver proyecto anterior </a> 

### Tecnologías aplicadas en el Frontend

<ul>
  <li>React</li>
  <li>TypeScript</li>
  <li>Tailwind</li>
  <li>Data Router</li>
  <li>Valibot</li>
</ul>


## DATA API's
Desde la versión 6.4 de react router agregaron un nuevo router que te permite utilizar lo que se conoce como Data API's.
Estas API's permiten obtener datos de una API de forma muy eficiente.
También permiten manejar entrada de datos desde un formulario. 

### Actions en REACT ROUTER
Utiliza actions para procesar la entrada de datos en un formulario. Para ello deberás importar un componente llamado `<Form>`, crear una función y en tu router indicar qué función debe ejecutarse en el action. 

## Valibot
En este caso se ha utilizado valibot para validar.


## Loaders en REACT ROUTER
Utiliza Loaders para obtener datos de una API, similar a useEffect y colocar la respuesta en un state. 

Para ello deberás crear una función y en tu router
decirle que función debe ejecutarse en el loader. 

### ¿Cuando utilizar useLoaderData y useActionData?

useLoaderData. Cuando quieras obtener el resultado de un loader
useActionData. Cuando quieras obtener el resultado de un action (formularios)

## useFetcher
Útil para no redireccionar.


