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

    - Kotlin / Java: Lenguajes de programación principales utilizados para definir la lógica de negocio, el comportamiento de la aplicación y la integración con las APIs de Android.

- **Software Testing**

    -  Espresso: Herramienta integrada en Android Studio diseñada para realizar pruebas de UI automatizadas, asegurando que las interacciones del usuario produzcan los resultados esperados.

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

