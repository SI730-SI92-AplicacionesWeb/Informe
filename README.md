# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration


**User Experience Design (UX/UI)**

1. Figma: Una herramienta de diseño colaborativo basada en la nube, ideal para equipos que necesitan trabajar en la creación y edición de interfaces de usuario (UI) y experiencia de usuario (UX) en tiempo real.

2. Miro: Una plataforma de colaboración digital que ofrece una pizarra virtual con herramientas diversas para la creación visual, como diagramas, mapas mentales, wireframes, y sesiones de brainstorming.


**Software Development**

1. Visual Studio Code: Editor de código gratuito y de código abierto desarrollado por Microsoft, ampliamente utilizado por su interfaz limpia, opciones de personalización y funciones avanzadas como resaltado de sintaxis, autocompletado y depuración.

2. Intellij IDEA: IDE desarrollado por JetBrains, que ofrece soporte para una variedad de lenguajes y tecnologías, incluyendo Vue. Integra herramientas avanzadas como refactorización, finalización de código, depuración, y soporte para control de versiones.

3. Vue.js: Framework progresivo de JavaScript de código abierto mantenido por la comunidad, usado para desarrollar aplicaciones web dinámicas y escalables, como aplicaciones de una sola página (SPA).

   3.1. HTML5: Lenguaje de marcado para la estructura de páginas web. Se utilizará en el proyecto para organizar y presentar el contenido de la aplicación.

   3.2. CSS: Versión más reciente del lenguaje de hojas de estilo, que introduce funcionalidades como selectores avanzados, animaciones y transiciones, permitiendo diseños web más complejos y atractivos.

   3.3. JavaScript: Lenguaje de programación central para el desarrollo web, utilizado para crear aplicaciones interactivas y dinámicas.


### 5.1.2. Source Code Management

Para el control de versiones, el equipo utilizará GitHub como la plataforma de gestión. Se ha creado una organización denominada "Turisteando" para alojar todos los repositorios relacionados con el proyecto.

### 5.1.3. Source Code Style Guide & Conventions

Para mantener una codificación coherente en nuestro proyecto con Vue.js en IntelliJ IDEA, adoptaremos convenciones como camelCase y UpperCamelCase para variables, funciones y clases.

Se seguirán las prácticas de "conventional commits" tanto para la creación de ramas como para los commits, utilizando el modelo de GitFlow. Las ramas se nombrarán siguiendo el formato "type/title", como por ejemplo "feat/main-component" para nuevas funcionalidades.

El flujo de versiones centrará el desarrollo en la rama "main", que contendrá la versión de producción de la aplicación. Todas las características y correcciones se fusionarán en esta rama principal, asegurando un desarrollo ordenado y consistente del proyecto.

### 5.1.4. Software Deployment Configuration

**Landing Page Deployment**

Los pasos para el despliegue del Landing Page son:

1. Dirigirse a la sección "Settings" en GitHub.
2. Seleccionar "Build and deployment" en "Pages".
3. Optar por "Deploy from a branch".
4. Seleccionar la rama "main" para el despliegue.
5. Al completarse el despliegue, se generará un enlace para acceder a la Landing Page.

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1

En el marco de Scrum, un Sprint es un período de tiempo determinado y corto en el que el equipo se concentra en completar todas las actividades necesarias para alcanzar el "Product Goal" o meta del producto.

#### 5.2.1.1. Sprint Planning 1

| **Sprint #** | 1 |
|--------------|---|
| **Sprint Planning Background** |   |
| **Date** | 30/03/2024 |
| **Time** | 08:00 pm |
| **Location** | Reunión virtual a través del Google Meet |
| **Prepared by** | Alexander Justo |
| **Attendees (to planning meeting)** | Carlos Alejandro De La Cruz Villarreal, Rafael Agustin Pacheco Lavado, Alexander Paolo Justo Yauricasa, Erick Alessander Vasquez Goicochea|
| **Sprint n - 1 Review Summary** | En esta primera reunión de grupo realizada nos centramos en la asignación de tareas para la realización de la documentación a presentar para la primera entrega, así como también iniciar con la primera versión del Landing Page. Se repartió el trabajo y se designó responsabilidades a cada uno. |
| **Sprint n - 1 Retrospective Summary** | No existen resultados anteriores dado que es la primera reunión grupal. |
| **Sprint Goal & User Stories** |   |
| **Sprint n Goal** | Crear la landing page de nuestro sitio web, y la métrica de cumplimiento fue que la primera versión de dicha landing page esté lista antes de la fecha de presentación. |
| **Sprint n Velocity** | 9 |
| **Sum of Story Points** | 11 |


#### 5.2.1.2. Sprint Backlog 1

| **Sprint #**       | **Sprint 1**                                |                  |                                            |                                                                                                   |                        |                         |            |
|--------------------|---------------------------------------------|------------------|--------------------------------------------|---------------------------------------------------------------------------------------------------|------------------------|-------------------------|------------|
| **User Story ID**  | **Title**                                   | **Work-Item ID** | **Title**                                  | **Description**                                                                                   | **Estimation (Hours)** | **Assigned To**         | **Status** |
| US26               | Ver detalles generales del servicio         | T001             | Implementar el header, main y footer       | El desarrollador implementa los componentes señalados del landing page                             | 3 Horas                | Rafael Pacheco     | Done       |
|                    |                                             | T002             | Realizar una limpieza de código            | Corrección de errores y modificación de textos                                                     | 0.5 Horas              | Carlos DE La Cruz              | Done       |
| US27               | Ver misión y visión del proyecto            | T001             | Implementar la opción de misión y visión   | El desarrollador implementa la opción y lógica para la creación de los cuadros desplegables para misión y visión | 2 Horas                | Alexander Justo     | Done       |
| US28               | Revisar los servicios ofrecidos             | T001             | Implementar la opción de servicios         | Implementar los componentes y lógica para el botón atajo de servicio en el header                   | 1 Hora                 | Carlos De La Cruz     | Done       |
|                    |                                             | T002             | Implementar los servicios                  | Implementación de los componentes y vista de servicios en el main                                  | 1 Hora                 | Erick Vasquez    | Done       |
| US29               | Obtener contacto con los administradores    | T001             | Implementar la opción de contacto          | El desarrollador implementa la opción-atajo de contacto del landing page en el header               | 0.5 Horas              | Alexander Justo     | Done       |
|                    |                                             | T002             | Implementar sección de contacto            | El desarrollador implementa la sección de contacto del landing page                                 | 1 Hora                 | Erick Vasquez      | Done       |


#### 5.2.1.3. Development Evidence for Sprint Review


#### 5.2.1.4. Testing Suite Evidence for Sprint Review

En el proceso de desarrollo de la landing page, se aplicaron diversas estrategias de prueba para garantizar su correcto funcionamiento y adaptabilidad en diferentes entornos. A continuación se detallan las herramientas utilizadas y los enfoques adoptados

1. Uso de Live Server de Microsoft Visual Studio Code

Propósito:

Live Server se implementó para facilitar el desarrollo y la prueba de la landing page de manera local.
Descripción:

Esta herramienta permitió la visualización dinámica de la landing page en el navegador web, lo que agilizó el proceso de desarrollo al mostrar los cambios en tiempo real sin necesidad de recargar manualmente la página.

2. Aprovechamiento de las Propiedades del Navegador para Mejorar el Responsive

Propósito:

Se aprovecharon las características específicas del navegador para mejorar la compatibilidad con CSS Grid y el diseño responsivo.
Descripción:

Se exploraron las capacidades de inspección de elementos del navegador para ajustar y optimizar el diseño de la landing page, especialmente en lo que respecta al uso de CSS Grid. Además, se utilizaron las herramientas de depuración del navegador para identificar y corregir cualquier problema de diseño responsivo.
Estas estrategias de prueba garantizaron la funcionalidad, la estética y la adaptabilidad de la landing page en diversos dispositivos y navegadores, contribuyendo así a una experiencia de usuario excepcional.

#### 5.2.1.5. Execution Evidence for Sprint Review

Se ha implementado la primera versión del Landing Page, con partes
fundamentales como inicio, servicios y contacto:

https://si730-si92-aplicacionesweb.github.io/LandingPague.github.io/#

![img Landing](https://media.discordapp.net/attachments/1281807145603436607/1281913925969117275/image.png?ex=66dd72e0&is=66dc2160&hm=78f7d956b20e76b9048034af5ed5ff997311178f23e46b8d8f52995db6a28124&=&format=webp&quality=lossless&width=550&height=241)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Aún no se ha implementado el uso de Endpoints, y no se desplegó ningún web service en este sprint.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el despliegue de la landing page se utilizó github pages, a continuación se muestra el link de la landing page desplegada junto a los pasos realizados para publicarla.

Nos dirigimos a los settings del repositorio y seleccionamos el apartado de pages.

![Fo](https://media.discordapp.net/attachments/1281807145603436607/1281915702860845116/image.png?ex=66dd7488&is=66dc2308&hm=f71af5dc17847e16e9d1e641fb987938277d00ed9d5831b92a6c72741b17660a&=&format=webp&quality=lossless&width=1025&height=450)

Seleccionamos la rama main para ejecutar el deploy y damos a guardar

![Fotex](https://media.discordapp.net/attachments/1281807145603436607/1281915848210124892/image.png?ex=66dd74ab&is=66dc232b&hm=741911f1876ce64eb5afad2dbe347239b4f6e39c359da1ff605e3002d3e91e39&=&format=webp&quality=lossless&width=1025&height=447) 

Ingresamos el dominio de la landing page

![Foto](https://media.discordapp.net/attachments/1281807145603436607/1281915924903100498/image.png?ex=66dd74bd&is=66dc233d&hm=d9ca65b358daf1b94c240710d7c09c34b022417630e245efa7efcb2bf8082a20&=&format=webp&quality=lossless&width=550&height=242)


#### 5.2.1.8. Team Collaboration Insights during Sprint

Dado que el primer sprint se centra en la documentación y la creación del landing page, 4 de los 6 integrantes trabajaron en el desarrollo de ambas 

![Fto](https://media.discordapp.net/attachments/1281807145603436607/1281916965807718410/image.png?ex=66dd75b5&is=66dc2435&hm=c1a1b4c54c98fe22e9755c5169582581630fa374980c9c7960eeb8bc1e6d5e8e&=&format=webp&quality=lossless&width=1025&height=433) 

![Photo](https://media.discordapp.net/attachments/1281807145603436607/1281917128412364881/image.png?ex=66dd75dc&is=66dc245c&hm=7877deb741e1957a1b6e0704e357475f5bd913497a3e7808e13e70407f8d659e&=&format=webp&quality=lossless&width=1002&height=473)


