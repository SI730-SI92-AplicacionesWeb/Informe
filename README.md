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
| **Prepared by** | Max Anthony Paitan Pumacahua |
| **Attendees (to planning meeting)** | Alexander Alberto Cantoral Sedamano, Max Anthony Paitan Pumacahua, Carlos Alejandro de la Cruz Villareal, Diego Rolin Acuña Tomas, Miguel Angel Gomez Hurtado |
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
| US26               | Ver detalles generales del servicio         | T001             | Implementar el header, main y footer       | El desarrollador implementa los componentes señalados del landing page                             | 3 Horas                | Alexander Cantoral      | Done       |
|                    |                                             | T002             | Realizar una limpieza de código            | Corrección de errores y modificación de textos                                                     | 0.5 Horas              | Max Paitan               | Done       |
| US27               | Ver misión y visión del proyecto            | T001             | Implementar la opción de misión y visión   | El desarrollador implementa la opción y lógica para la creación de los cuadros desplegables para misión y visión | 2 Horas                | Alexander Cantoral      | Done       |
| US28               | Revisar los servicios ofrecidos             | T001             | Implementar la opción de servicios         | Implementar los componentes y lógica para el botón atajo de servicio en el header                   | 1 Hora                 | Alexander Cantoral      | Done       |
|                    |                                             | T002             | Implementar los servicios                  | Implementación de los componentes y vista de servicios en el main                                  | 1 Hora                 | Alexander Cantoral      | Done       |
| US29               | Obtener contacto con los administradores    | T001             | Implementar la opción de contacto          | El desarrollador implementa la opción-atajo de contacto del landing page en el header               | 0.5 Horas              | Alexander Cantoral      | Done       |
|                    |                                             | T002             | Implementar sección de contacto            | El desarrollador implementa la sección de contacto del landing page                                 | 1 Hora                 | Alexander Cantoral      | Done       |


#### 5.2.1.3. Development Evidence for Sprint Review


#### 5.2.1.4. Testing Suite Evidence for Sprint Review


#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
### 5.3.1. Diseño de entrevistas
### 5.3.2. Registro de entrevistas
### 5.3.3. Evaluación según heurísticas

## 5.4. Video about the product
