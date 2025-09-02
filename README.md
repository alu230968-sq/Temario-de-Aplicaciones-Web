# Temario-de-Aplicaciones-Web
Accede a GitHub y crea un repositorio llamado Temario de Aplicaciones Web con el archivo README en donde investigarás con imágenes los temas propuestos.


# <ins> Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
_1.-Introducción al desarrollo web_  
# Historia y evolución del desarrollo web  
_La historia del desarrollo web inicia en 1989, cuando Tim Berners-Lee propuso el concepto de la World Wide Web en el CERN. El primer sitio web fue publicado en 1991. Desde entonces, el desarrollo web ha experimentado una evolución continua_  

<img width="226" height="168" alt="image" src="https://github.com/user-attachments/assets/39eb71ad-f97a-47d8-a649-bbd6e3f98a47" />  

# Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
__1. Aplicaciones web estáticas:__  
Son páginas cuyo contenido no cambia, a menos que el desarrollador modifique manualmente el código fuente. Se componen principalmente de HTML y CSS, y muestran la misma información a todos los usuarios. Ejemplo: páginas de presentación o portafolios personales.

__2. Aplicaciones web dinámicas:__  
El contenido de estas aplicaciones se genera de forma dinámica a partir de bases de datos o la interacción del usuario. Utilizan lenguajes como PHP, Python, Ruby y frameworks como Node.js para procesar información en el servidor. Ejemplo: foros, tiendas en línea, blogs, redes sociales.

__3. SPA (Single Page Application):__  
Una SPA carga una sola página web y actualiza dinámicamente el contenido conforme el usuario navega, sin recargar la página completa. Utilizan JavaScript y frameworks modernos como React, Angular o Vue.js para ofrecer una experiencia fluida y rápida, similar a una aplicación nativa. Ejemplo: Gmail, Trello.

__4. PWA (Progressive Web Application):__  
Las PWA son aplicaciones web que ofrecen funcionalidades similares a las aplicaciones móviles nativas: pueden funcionar sin conexión, enviar notificaciones push y ser instaladas en dispositivos. Utilizan tecnologías como Service Workers y manifiestos web para mejorar la experiencia del usuario. Ejemplo: Twitter Lite, Starbucks.  

<img width="189" height="161" alt="image" src="https://github.com/user-attachments/assets/269c59d8-d976-4583-92c0-2927024b5767" />  

# <ins>  2. Arquitectura de aplicaciones web_  
# Cliente-Servidor  
La arquitectura cliente-servidor es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee. El cliente interactúa con el usuario, mientras que el servidor gestiona y centraliza los recursos y el procesamiento de datos.  
# Arquitectura de tres capas (presentación, lógica, datos)  
La arquitectura de tres capas es un patrón de diseño de software que organiza una aplicación en tres niveles lógicos e interconectados: la capa de presentación (la interfaz de usuario), la capa de lógica de aplicación (o de negocio), y la capa de acceso a datos. Este enfoque busca la separación de responsabilidades para mejorar la escalabilidad, el mantenimiento y la flexibilidad de la aplicación. 
Las tres capas principales:  
__1. Capa de Presentación (Interfaz de Usuario):__  
Es la capa que interactúa directamente con el usuario, mostrando la información y recolectando las entradas. 
Generalmente se implementa en tecnologías web como HTML, CSS o JavaScript, y utiliza interfaces gráficas de usuario (GUI).  
__2. Capa de Lógica de Aplicación (o de Negocio):__  
Es el "cerebro" de la aplicación, donde se procesan las reglas de negocio, se gestionan las operaciones y se toman decisiones. 
Esta capa se comunica con la capa de presentación y la capa de datos, actuando como intermediaria.  
__3. Capa de Acceso a Datos:__  
Se encarga del almacenamiento, la gestión y la recuperación de la información de una base de datos. 
Esta capa garantiza la consistencia, seguridad e integridad de los datos.  
# REST y API-first design  
REST es un estilo arquitectónico para servicios web que utiliza HTTP para interactuar con recursos, y el diseño API-first es una filosofía de desarrollo donde las API se diseñan y se documentan exhaustivamente antes de escribir el código para los servicios subyacentes.  

<img width="320" height="156" alt="image" src="https://github.com/user-attachments/assets/c7171efc-958d-4de6-aed5-74bc2eb1b3d3" />  

# <ins> 3. -Lenguajes y tecnologías fundamentales  
__HTML, CSS, JavaScript, PHP, MySQL__   
# HTML (estructura de una página web):

HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Ejemplo HTML</title>
  </head>
  <body>
    <h1>Hola, mundo!</h1>
    <p>Este es un ejemplo de HTML.</p>
  </body>
</html>
CSS (estilos para una página web):

# CSS
body {
  background-color: #f0f0f0;
  color: #333;
  font-family: Arial, sans-serif;
}

h1 {
  color: #0066cc;
}
# JavaScript (interactividad en la web):

JavaScript
document.getElementById("boton").onclick = function() {
  alert("¡Hiciste clic en el botón!");
};
HTML necesario para el ejemplo de JS:

# HTML
<button id="boton">Haz clic aquí</button>
PHP (generación dinámica de contenido en el servidor):

# PHP
<?php
echo "<h1>¡Hola desde PHP!</h1>";
?>
# MySQL (consulta básica en una base de datos):

# SQL
SELECT nombre, correo FROM usuarios WHERE activo = 1;
# <ins> 4.-Control de versiones  

# Git y GitHub  
Flujo de trabajo con ramas (branching, merge, pull requests)  


# <ins> Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup
API
2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend
4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 


# <ins> Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
