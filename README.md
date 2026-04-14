# CRUD de Productos con MVC

Proyecto Java Web para la Unidad 6: JSP con MVC.

## Descripcion

Aplicacion web desarrollada con Java, Servlets y JSP que implementa un CRUD de productos bajo el patron MVC. Permite listar, crear, editar y eliminar productos en una interfaz sencilla, aplicando el flujo POST-Redirect-GET para una navegacion mas segura y ordenada.

## Funcionalidades implementadas

- Listado de productos en tabla con datos precargados.
- Registro de nuevos productos mediante formulario.
- Edicion de productos existentes con formulario precargado.
- Eliminacion de productos con confirmacion del navegador.
- Mensajes de confirmacion despues de guardar, actualizar o eliminar.
- Navegacion con patron POST-Redirect-GET para evitar reenvio de formularios.
- Separacion por capas MVC: controlador, servicio, modelo y vistas JSP.

## Prerrequisitos

- JDK 11 o superior.
- Apache Tomcat 10.x.
- IDE compatible con Java Web.
- Git y cuenta en GitHub.

## Ejecución

1. Importar el proyecto como Maven Project.
2. Configurar Tomcat y desplegar la aplicación.
3. Abrir `http://localhost:8080/<contexto>/productos`.

## Capturas

### 1. Lista inicial

![Ejecucion](https://raw.githubusercontent.com/Danna-Cardenas/Cardenas_post1-u6/main/Capturas/Captura1.png)

### 2. Formulario nuevo producto

![Ejecucion](https://raw.githubusercontent.com/Danna-Cardenas/Cardenas_post1-u6/main/Capturas/Captura2.png)

### 3. Producto guardado

![Ejecucion](https://raw.githubusercontent.com/Danna-Cardenas/Cardenas_post1-u6/main/Capturas/Captura3.png)

### 4. Edicion de producto

![Ejecucion](https://raw.githubusercontent.com/Danna-Cardenas/Cardenas_post1-u6/main/Capturas/Captura4.png)

### 5. Flujo final y consola

![Ejecucion](https://raw.githubusercontent.com/Danna-Cardenas/Cardenas_post1-u6/main/Capturas/Captura5.png)
