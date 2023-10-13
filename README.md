# README - Proyecto de Diseño de Ingeniería

## Introducción al Framework MVC

Este proyecto utiliza el patrón de diseño MVC (Modelo-Vista-Controlador) para organizar la estructura de la aplicación. El patrón MVC separa la aplicación en tres componentes principales:

- **Modelo**: Representa los datos y la lógica de la aplicación. En nuestro caso, utilicé MongoDB con PyMongo para gestionar la base de datos, lo que se traduce en el componente "Modelo".

- **Vista**: La vista es la interfaz de usuario (UI) de la aplicación. Utilicé React para construir la interfaz de usuario del frontend, lo que equivale al componente "Vista".

- **Controlador**: El controlador maneja las solicitudes del usuario y actúa como intermediario entre el modelo y la vista. Flask en el backend se encarga de gestionar las rutas y controlar las solicitudes, desempeñando el papel del "Controlador".

## Diseño de Ingeniería

### Diagrama de Arquitectura del Framework

<img src="https://github.com/juanjaviermino/React-Flask-App/blob/b709ce2a225ed5eed7b3e93b12e14df9b0c6168d/Diagrama%20de%20arquitectura.jpg" width="1020" alt="Diagrama de arquitectura de Flask y React">

### Explicación del Diagrama

El diagrama de arquitectura representa la estructura general de nuestra aplicación basada en el Framework MVC. Aquí hay una breve explicación de los componentes clave:

- **Frontend (React)**: Esta parte de la aplicación maneja la interfaz de usuario y las interacciones del usuario. Utilizamos React para construir las vistas y componentes frontend.

- **Backend (Flask)**: Flask actúa como el controlador en nuestro patrón MVC. Gestiona las solicitudes HTTP, enruta las peticiones a las funciones adecuadas y se comunica con la base de datos.

- **Base de Datos (MongoDB)**: Utilicé MongoDB como base de datos para almacenar y recuperar datos. PyMongo se utiliza para interactuar con la base de datos desde la aplicación Flask.

- **Estilos (Bootswatch)**: Bootswatch proporciona un conjunto de estilos predefinidos que aplicamos a nuestra interfaz de usuario React para darle una apariencia atractiva y coherente.

Este diseño nos permite separar claramente las preocupaciones, lo que facilita el desarrollo y el mantenimiento de la aplicación. El frontend se encarga de la presentación, el backend gestiona la lógica de la aplicación y la base de datos almacena los datos de manera eficiente.
