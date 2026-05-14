# Capítulo IV: Product Implementation & Validation

<h2 id="4-product-implementation-&-validation">4. Product Implementation & Validation</h2>

<h3 id="41-software-configuration-management">4.1. Software Configuration Management</h3>

Para el desarrollo de este proyecto, es de suma importancia definir las herramientas y configuraciones de software para controlar de los componentes manera concreta y eficiente como el código fuente, los documentos de diseño y los recursos digitales. De esta manera, aseguramos que cada integrante del equipo apliquen y comprendan las directrices para facilitar la cooperación.

<h3 id="411-software-development-enviroment-configuration">4.1.1. Software Development Environment Configuration</h3>

- **Project Management** 

    - Zoom: Herramienta de videollamadas empleada para el levantamiento de información y entrevistas con los usuarios para facilitar la documentación y validación de las caracteristicas del proyecto.
    - Trello: Sistema de gestión de proyectos basado en la metodología Kanban. Permite la organización del flujo de trabajo y asignación de tareas mediante tableros visuales.

- **Requirements Management**

    - Structurizr: Suite de herramientas especializada en el modelado de arquitectura C4 para la representación visual Domain-Driven Design.
    - PlantUML: Herramienta de modelado basada en código abierto que permite generar diagramas de UML para elaboración del diagrama de clases.

- **Product UX/UI Design**
  
    - Figma: Herramienta visual que facilita la creación de wireframes y mockups.

- **Software Development**

    - Android Studio: Entorno de desarrollo integrado oficial basado en IntelliJ IDEA para la creación de aplicaciones moviles en el sistema operativo Android. Proporciona herramientas avanzadas para la edición de código, depuración, pruebas y un sistema de construcción flexible
    - Visual Studio Code: Entorno de desarrollo integrado de Microsoft para multiples plataformas y lenguajes para realizar la Landing Page. 
    - Kotlin / Java: Lenguajes de programación principales utilizados para definir la lógica de negocio, el comportamiento de la aplicación y la integración con las APIs de Android.

    - HTML5: Lenguaje de marcado para estructurar el contenido de la Landing page.
    - CSS3: Lenguaje de estilos para definir la apariencia visual de la Landing page.
 
- **Software Deployment**
    
    - GitHub Pages: Servicio de hosting utilizado para el despliegue de la landing page del proyecto.

- **Software Testing**
    - Gherkin: Lenguaje para definir criterios de aceptación de User Stories en un formato entendible por todos los integrantes del equipo.
    - Espresso: Herramienta integrada en Android Studio diseñada para realizar pruebas de UI automatizadas, asegurando que las interacciones del usuario produzcan los resultados esperados.

- **Software Documentation**

    - Github: Plataforma de alojamiento para el control de versiones y la colaboración de miembros. Permite el seguimiento de cambios en el código fuente, la gestión de ramas y el almacenamiento seguro del progreso del proyecto.

<h3 id="412-source-code-management">4.1.2. Source Code Management</h3>

- **Main branch**

Esta rama representa el eje principal del proyecto y contiene el código fuente en su fase final. Es la rama más estable, donde solo se integra código que ha sido completamente testeado y aprobado para su despliegue final.

- **Develop branch** 

Esta rama representa de la integración de los cambios durante el desarrollo. Es el espacio donde se consolidan todas las nuevas funcionalidades y correcciones antes de ser enviadas a la rama principal.

- **Feature branchs**

Estas ramas temporales son creadas para el desarrollo de funcionalidades específicas, módulos o capítulos del aplicativo bajo la convención de nombres como ```feature/chapter1```. Esto permite que cada integrante trabaje de forma aislada y paralela, evitando conflictos en el código base hasta que la funcionalidad esté completada y lista para ser fusionada con la rama develop.

- **Conventional Commits**

Es una convención para estructurar los mensajes de confirmación (commits) en un formato estándar y semántico para comunicar claramente los cambios realizados en el código y facilitar la generación de registros de cambios automáticos, lo que facilita su seguimiento y comprensión por parte de los desarrolladores y otros miembros del equipo.

La estructura de un commit debe seguir las siguientes pautas:

```
git commit -m "<type>[optional scope]: <title>" -m "<description>"
```

Por otro lado, definimos las diferentes tipos de commits para que nos ayude a documentar los cambios de manera comprensible. A continuación, se describirán los más esenciales:

```
1. feat: Used to describe a new feature or functionality added to the code.
2. fix: Indicates a bug fix or solution to a problem.
3. docs: Employed for changes or improvements in code documentation.
4. style: Describes changes related to the code's formatting, such as whitespace, indentation, etc., that do not affect its functionality.
5. refactor: Used for modifications to the code that do not fix bugs or add new features, but rather improve its structure or readability.
6. test: Indicates the addition or modification of unit tests or functional tests.
7. chore: Used for changes in the build process or maintenance tasks that are not directly related to the code itself.
8. perf: Describes performance improvements in the code.
```

<h3 id="413-source-code-style-guide-&-conventions">4.1.3. Source Code Style Guide & Conventions</h3>

Con el fin de garantizar la mantenibilidad y legibilidad del código fuente, se ha adoptado un conjunto de convenciones internacionales.
- HTML:
    - Se utilizaran atributos en minúsculas y nombres de clase con kebab-case (section-title, main-container).
    - Estructura semántica clara: uso de etiquetas como ```<header>```, ```<nav>```, ```<main>```, ```<section>```, ```<footer>```. Además de utilizar una sangría con 2 espacios.
    - Atributos ordenados de manera lógica: id, class, type, name, placeholder, value, required, etc.
- CSS
    - Para clases personalizadas: usar kebab-case.
    - Se agruparán clases de utilidad por orden lógico (layout -> spacing -> color -> typography).

- Kotlin: Se adopta las directrices especificadas en la documentación de Google Kotlin Style Guide a nivel.

	- Immutability: Se prioriza el uso de val sobre var para fomentar la inmutabilidad y reducir errores en tiempo de ejecución.

	- PascalCase: Utilizado para nombres de clases, interfaces y objetos (por ejemplo LoginActivity, UserRepository...).

	- camelCase: Utilizado para funciones, propiedades y variables.

- Java (Android / Backend): Se aplica las directrices en la documentación de Google Java Style Guide. Se prioriza la legibilidad del código mediante el uso de nombres descriptivos que eviten la ambigüedad, eliminando abreviaturas innecesarias.

- Android XML Resources:

	- XML Layouts: Uso de snake_case con prefijos descriptivos (por ejemplo activity_login.xml, item_product_card.xml...).

	- IDs: Se utiliza camelCase precedido por la función del componente (por ejemplo btnSubmit, txtUserLabel...).

<h3 id="414-source-deployment-configuration">4.1.4. Software Deployment Configuration</h3>

En esta sección se describe la estrategia de despliegue automatizado para garantizar que los cambios en el código fuente se reflejen de manera consistente en el entorno de producción.

GitHub Pages:

- Para empezar, nos desplazaremos a la configuración de GitHub Pages en el repositorio de la landing page.

<img src="./img/deploy_evidence1.png">

- Luego, ingresaremos a la sección "Settings", y luego dentro entraremos a la sección "Pages"

<img src="./img/deploy_evidence2.png">

- Después, seleccionamos la rama en la que se encuentre alojado el proyecto.

<img src="./img/deploy_evidence3.png">

- Finalmente, esperamos la URL autogenerada por GitHub Pages y seleccionamos el botón de "Visitar sitio" para entrar al despliegue.

<img src="./img/deploy_evidence4.png">

<h2 id="42-landing-page-&-mobile-application-implementation">4.2. Landing Page & Mobile Application Implementation </h3>

<h3 id="421-sprint-1">4.2.1. Sprint 1</h3>

<h3 id="4211-sprint-planning-1">4.2.1.1. Sprint Planning 1</h3>

<table border="1" cellspacing="0" cellpadding="6">
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 1</strong></td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>08/05/2026</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>7:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Whatsapp</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Eduardo Cossar</td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td>
          Joan Elias Aguirre Eneque - u2023156497<br>
          Johan Giovani Huaman Cuba - u202417448<br>
          César Augusto Navarro Correa - u202310129<br>
          Eduardo Cossar - u202312109<br>
          Maria Fernanda Mostajo - u202312874<br>
        </td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Review Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Retrospective Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Goal</td>
        <td>
            <p>- Desarrollar la primera versión de una Landing page funcional y visualmente clara que comunique efectivamente para que cumpla los requisitos minimos del UI/UX</p>
            <p>- Realizar una pequeña estructuración y visualización grafica del Mobile Application</p>
            <p>- Establecer la organización de los repositorios del Front-end y Back-end</p>
        </td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Velocity</td>
        <td>8</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>30</td>
    </tr>
</table>

<h3 id="4212-sprint-backlog-1">4.2.1.2. Sprint Backlog 1</h3>

<table border="1" cellspacing="0" cellpadding="6">
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 1</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US-26</td>
        <td>Visualización de la sección inicial</td>
        <td>W-01</td>
        <td>Sección Home</td>
        <td>Como usuario, quiero ver una sección de inicio sobre un resumen del valor de la propuesta para comprender rápidamente el objetivo del sistema</td>
        <td>3 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-27</td>
        <td>Visualización del equipo de la startup</td>
        <td>W-02</td>
        <td>Sección About Us</td>
        <td>Como usuario, quiero conocer quiénes están detrás del proyecto para confiar en el profesionalidad del sistema</td>
        <td>4 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-28</td>
        <td>Visualización del funcionamiento del proyecto</td>
        <td>W-03</td>
        <td>Sección How it works?</td>
        <td>Como usuario, quiero entender cómo funciona la plataforma de manera sencilla para evaluar si se ajusta a mis necesidades</td>
        <td>5 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-29</td>
        <td>Visualización de los clientes satisfechos</td>
        <td>W-04</td>
        <td>Sección Our Clients</td>
        <td>Como usuario, quiero conocer a los demás usuarios utilizan la plataforma para tener confianza en la plataforma y saber que otras empresas ya la están usando</td>
        <td>6 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-30</td>
        <td>Enviar mensaje de contacto</td>
        <td>W-05</td>
        <td>Sección Contact</td>
        <td>Como usuario, quiero enviar un mensaje al equipo de desarrollo para solicitar más información del proyecto</td>
        <td>5 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-31</td>
        <td>Cambiar idioma</td>
        <td>W-06</td>
        <td>Switch de idioma</td>
        <td>Como usuario, quiero tener la capacidad de cambiar entre el inglés y español para entender la plataforma en mi idioma preferido</td>
        <td>3 horas</td>
        <td>Joan</td>
        <td>Done</td>
    </tr>
</table>

</table>

<h3 id="4213-development-evident-for-sprint-review">4.2.1.3. Development Evidence for Sprint Review</h3>

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Rama</th>
      <th>ID de Commit</th>
      <th>Mensaje de Commit</th>
      <th>Descripción del Commit</th>
      <th>Fecha de Commit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>49bd82a</td>
      <td>style(css)</td>
      <td>design navigation bar and scroll progress</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>a5e1651</td>
      <td>style(css)</td>
      <td>implement base design system and variables</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>0f581e9</td>
      <td>feat(html)</td>
      <td>define core structure and semantic sections</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>8a55346</td>
      <td>feat(assets)</td>
      <td>add team member portraits</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>937b194</td>
      <td>feat(assets)</td>
      <td>add platform interface mockup</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>4eb8acb</td>
      <td>feat(assets)</td>
      <td>add futuristic background for hero section</td>
      <td>12/05/26</td>
    </tr>
    <tr>
      <td>IdeaForge-App/landing-page</td>
      <td>main</td>
      <td>5fe7581</td>
      <td>feat(assets)</td>
      <td>add brand identity logo</td>
      <td>12/05/26</td>
    </tr>
  </tbody>
</table>

<h3 id="4214-testing-suite-evidence-for-sprint-review">4.2.1.4. Testing Suite Evidence for Sprint Review</h3>

Durante el Sprint 1, el esfuerzo del equipo se concentró exclusivamente en el desarrollo del Landing Page de IdeaForge. Debido a esta priorización del frontend, la creación de la tabla Testing Suite para Web Services no fue ejecutada. El diseño de la arquitectura de pruebas, así como la implementación de endpoints y su respectiva validación, se encuentran programados dentro del cronograma de los Sprints subsiguientes.

<h3 id="4215-execution-evidence-for-sprint-review">4.2.1.5. Execution Evidence for Sprint Review</h3>

<strong>Landing Page</strong>

<ul>
    <li><img src="./img/landing_page_evidence1.png"></li>
	<li><img src="./img/landing_page_evidence2.png"></li>
	<li><img src="./img/landing_page_evidence3.png"></li>
	<li><img src="./img/landing_page_evidence4.png"></li>
	<li><img src="./img/landing_page_evidence5.png"></li>
	<li><img src="./img/landing_page_evidence6.png"></li>
</ul>

<h3 id="4216-services-documentation-evidence-for-sprint-review">4.2.1.6. Services Documentation Evidence for Sprint Review</h3>

Durante el Sprint 1, el equipo se enfocó en el desarrollo del Landing Page de IdeaForge, por lo cual no se implementaron ni documentaron endpoints relacionados a Web Services. Los trabajos de desarrollo backend, integración de API y documentación con OpenAPI están planificados para Sprints posteriores.

<h3 id="4217-software-deployment-evidence-for-sprint-review">4.2.1.7. Software Deployment Evidence for Sprint Review</h3>

<ul>
    <li>
        <strong>URL de la Landing Page:</strong>
        <a href="https://ideaforge-app.github.io/landing-page/" target="_blank">https://ideaforge-app.github.io/landing-page/</a>
    </li>
    <li>
        <strong>Repositorio:</strong>
        <a href="https://github.com/IdeaForge-App/landing-page" target="_blank">https://github.com/IdeaForge-App/landing-page</a>
    </li>
</ul>

<h3 id="4218-team-collaboration-insights-during-sprint">4.2.1.8. Team Collaboration Insights during Sprint</h3>

<p><strong>Resumen:</strong><br>
El equipo se realizado las tareas de manera colaborativa mediante el uso de herrameintas GitHub y WhatsApp durante el Sprint para brindar información. Las actividades principales se centraron principalmente en el desarrollo y despliegue de la Landing Page.</p>

<h5>Evidencia de Colaboración:</h5>
<ul>
  <li>Captura de pantalla de commits en GitHub mostrando contribuciones del equipo.</li>
  <li>Conversaciones de WhatsApp sobre coordinación de secciones y ajustes de diseño.</li>
</ul>

<h5>Principales Herramientas de Comunicación:</h5>
<ul>
  <li>GitHub (control de versiones y manejo de issues)</li>
  <li>WhatsApp (comunicación diaria y aclaraciones rápidas)</li>
  <li>Figma (desarrollo del diseño de la interfaz de usuario de la Lannding Page)</li>
</ul>
