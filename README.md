

## 3.1. Product design

En esta sección se presenta el diseño del producto digital IdeaForge, considerando su enfoque principal como aplicación móvil. IdeaForge es una plataforma orientada a que emprendedores, estudiantes y creativos puedan publicar ideas de proyectos y conectar con personas interesadas en colaborar según sus roles, habilidades e intereses.

El diseño del producto se plantea desde una perspectiva mobile-first, ya que la experiencia principal del usuario se desarrollará a través de una aplicación móvil. Por ello, las decisiones visuales y funcionales están orientadas a facilitar la exploración de ideas, la creación de proyectos, la postulación a iniciativas, la comunicación entre usuarios y la gestión del perfil personal.

La propuesta de diseño busca que los usuarios puedan comprender rápidamente el propósito de cada proyecto, identificar los roles requeridos y tomar decisiones de participación de forma simple. Además, se prioriza una interfaz moderna, atractiva y clara, adecuada para un público joven vinculado a entornos académicos, tecnológicos, creativos y emprendedores.

IdeaForge no se presenta como una aplicación de empleo ni de contratación de servicios, sino como un espacio digital para formar equipos alrededor de ideas en etapa temprana. Por esta razón, la experiencia visual y de interacción debe transmitir creatividad, colaboración, confianza y motivación para construir proyectos en conjunto.

---

## 3.1.1. Style Guidelines

El propósito de esta sección es establecer las pautas generales de estilo que guiarán el diseño visual y comunicacional de IdeaForge. Estas directrices permitirán mantener una identidad consistente dentro de la aplicación móvil, asegurando que las pantallas, componentes, textos, colores y elementos interactivos mantengan una misma línea gráfica.

Las Style Guidelines funcionarán como una guía común para el equipo de diseño y desarrollo, permitiendo que la aplicación mantenga coherencia visual durante la construcción de wireframes, mock-ups y futuras interfaces funcionales. Para ello, se consideran aspectos como branding, tipografía, colores, espaciado, tono de comunicación y aplicación en herramientas de diseño como Figma.

---

## 3.1.1.1. General Style Guidelines

### Branding

La identidad visual de IdeaForge se construye alrededor de los conceptos de creatividad, tecnología y colaboración. La marca busca representar un espacio donde las ideas pueden convertirse en proyectos reales mediante la conexión entre personas con habilidades, intereses y roles complementarios.

El logotipo de IdeaForge deberá transmitir una sensación moderna y tecnológica, evitando una apariencia demasiado corporativa o formal. La marca debe sentirse cercana para estudiantes, emprendedores y creativos, pero manteniendo una percepción profesional y confiable.

El isotipo puede estar relacionado con elementos visuales como conexiones, nodos, formas geométricas o una inicial estilizada, representando la unión entre ideas y personas. El uso del logotipo deberá mantenerse consistente en las principales pantallas de la aplicación móvil, especialmente en vistas como inicio de sesión, registro y bienvenida.

**Figura XX**

Logotipo de IdeaForge

[Insertar imagen del logotipo de IdeaForge]

A continuación, se detallan las decisiones relacionadas con el uso de la marca:

| Elemento | Decisión de diseño |
|---|---|
| Logo principal | Se utilizará en pantallas de ingreso, registro y presentación inicial de la aplicación. |
| Isotipo | Podrá utilizarse como ícono de aplicación, favicon o elemento visual reducido. |
| Estilo visual | Moderno, simple, tecnológico y colaborativo. |
| Personalidad de marca | Creativa, joven, confiable y orientada a la acción. |
| Aplicación en Figma | El logo deberá guardarse como componente reutilizable para asegurar consistencia en las pantallas móviles. |

### Typography

La tipografía es un elemento importante para garantizar una lectura clara dentro de la aplicación móvil. Debido a que IdeaForge se usará principalmente en pantallas pequeñas, se eligieron fuentes modernas, limpias y altamente legibles.

La fuente principal recomendada es **Poppins**, ya que transmite modernidad, dinamismo y una estética tecnológica. Esta fuente se utilizará principalmente en títulos, encabezados, botones y elementos destacados.

Como fuente secundaria se recomienda **Inter**, debido a su alta legibilidad en interfaces digitales. Esta se utilizará para textos de apoyo, descripciones, etiquetas, formularios, chips, mensajes informativos y contenido dentro de las tarjetas de proyectos.

| Uso | Fuente | Tamaño recomendado | Peso |
|---|---|---:|---|
| Títulos principales | Poppins | 28px - 32px | Bold |
| Subtítulos | Poppins | 20px - 24px | SemiBold |
| Botones | Poppins | 14px - 16px | SemiBold |
| Cuerpo de texto | Inter | 14px - 16px | Regular |
| Descripciones | Inter | 12px - 14px | Regular |
| Etiquetas y chips | Inter | 11px - 13px | Medium |

**Aplicación en Figma**

En Figma se deberán crear Text Styles para títulos, subtítulos, cuerpo de texto, botones, etiquetas y mensajes de apoyo. Esto permitirá mantener uniformidad visual en todas las pantallas de la aplicación móvil.

### Colors

La paleta de colores de IdeaForge se plantea bajo una línea visual moderna, atractiva y tecnológica. Se opta por una interfaz de modo oscuro, ya que permite generar una apariencia más diferenciada, juvenil y alineada con una aplicación orientada a ideas, innovación y colaboración.

Los colores principales combinan tonos oscuros con acentos vibrantes en violeta, cian y magenta. Esta combinación permite que la aplicación tenga una identidad visual llamativa sin perder claridad ni legibilidad.

| Uso | Color | Código HEX | Aplicación |
|---|---|---:|---|
| Fondo principal | Azul noche | `#0F172A` | Fondo general de la aplicación móvil. |
| Superficies y cards | Azul gris oscuro | `#1E293B` | Tarjetas, contenedores, formularios y secciones internas. |
| Color primario | Violeta eléctrico | `#7C3AED` | Botones principales, navegación activa y elementos destacados. |
| Color secundario | Cian creativo | `#06B6D4` | Botones secundarios, enlaces y acciones complementarias. |
| Color de acento | Magenta | `#EC4899` | Chips, etiquetas y elementos visuales de énfasis. |
| Color de destacado | Amarillo creativo | `#FACC15` | Badges, recomendaciones o elementos importantes. |
| Texto principal | Blanco suave | `#F8FAFC` | Títulos, botones y textos principales. |
| Texto secundario | Gris claro | `#CBD5E1` | Descripciones, subtítulos y textos informativos. |
| Éxito | Verde | `#22C55E` | Confirmaciones, postulaciones aceptadas o acciones exitosas. |
| Error | Rojo coral | `#F43F5E` | Errores, alertas o validaciones negativas. |

**Figura XX**

Paleta de colores de IdeaForge

[Insertar imagen de la paleta de colores]

El color violeta eléctrico será el color principal de la marca, utilizado en botones importantes, pestañas activas y acciones clave como iniciar sesión, crear una idea o postular a un proyecto. El cian se utilizará como color secundario para enlaces, botones alternativos y elementos de interacción. El magenta funcionará como color de apoyo para diferenciar categorías, habilidades o etiquetas visuales. El amarillo se reservará para destacar proyectos recomendados, ideas importantes o información que requiera mayor visibilidad.

**Aplicación en Figma**

Los colores deberán guardarse como Color Styles dentro de Figma. De esta manera, el equipo podrá reutilizarlos en botones, cards, chips, formularios y componentes de navegación sin perder consistencia visual.

### Spacing

El espaciado en IdeaForge debe permitir que la aplicación se perciba limpia, ordenada y fácil de usar. Al tratarse de una experiencia móvil, se prioriza una estructura clara, con márgenes suficientes para evitar saturación visual y facilitar la interacción táctil.

| Elemento | Espaciado recomendado |
|---|---:|
| Margen lateral de pantalla | 16px |
| Padding interno de cards | 16px |
| Separación entre cards | 12px - 16px |
| Separación entre inputs | 12px |
| Separación entre secciones | 24px |
| Altura mínima de botones | 48px |
| Radio de borde en cards | 16px |
| Radio de borde en botones | 12px |
| Espacio mínimo entre íconos y texto | 8px |

El uso adecuado del espacio permitirá que las tarjetas de proyectos, formularios y secciones de navegación sean fáciles de leer y utilizar. Además, ayudará a que los usuarios puedan identificar rápidamente los elementos principales, como botones de acción, filtros y estados de postulación.

**Aplicación en Figma**

En Figma se utilizará Auto Layout para organizar cards, formularios, botones y barras de navegación. Esto permitirá mantener consistencia en márgenes, padding y separación entre componentes, facilitando además la adaptación de las pantallas a distintos tamaños de dispositivos móviles.

### Tono de Comunicación

El tono de comunicación de IdeaForge debe ser claro, cercano y motivador. La aplicación está dirigida a usuarios que desean convertir ideas en proyectos o sumarse a iniciativas colaborativas, por lo que el lenguaje debe incentivar la acción sin resultar demasiado formal o complicado.

La comunicación debe evitar términos asociados a empleo formal, contratación o venta de servicios. En su lugar, se priorizarán expresiones vinculadas a colaboración, creación, equipo, ideas, proyectos y participación.

| Dimensión | Decisión |
|---|---|
| Divertido / Serio | Equilibrado, con tono moderno y confiable. |
| Formal / Casual | Semi-casual, cercano al público joven. |
| Respetuoso / Irreverente | Respetuoso y claro. |
| Entusiasta / Sereno | Entusiasta moderado, orientado a motivar la colaboración. |

Ejemplos de microcopy para la aplicación:

| Situación | Texto sugerido |
|---|---|
| Pantalla de inicio | Find your next team |
| Subtítulo de login | Turn ideas into projects with the right people. |
| Botón principal | Log In |
| Crear cuenta | Create account |
| Crear idea | Create idea |
| Explorar proyectos | Explore ideas |
| Ver detalle | View |
| Postular | Apply |
| Guardar proyecto | Save idea |
| Sin resultados | No ideas found yet. Try another search. |
| Postulación enviada | Your application was sent successfully. |

En conclusión, el tono de comunicación de IdeaForge debe transmitir que la plataforma es un espacio donde cualquier persona con una idea o habilidad puede encontrar oportunidades para colaborar. El lenguaje debe ser directo, positivo y fácil de entender, fortaleciendo la percepción de comunidad y construcción conjunta.

---

## 3.1.2. Information Architecture

En esta sección se presentan las decisiones que guían la manera en que se organizará la información dentro de la aplicación móvil de IdeaForge. La arquitectura de información busca que los usuarios puedan adaptarse rápidamente a la plataforma, encontrar proyectos de interés, publicar ideas y gestionar sus postulaciones sin dificultad.

La estructura de la aplicación se basa en los objetivos principales de los usuarios: descubrir ideas, crear proyectos, postular a iniciativas, comunicarse con otros usuarios y administrar su perfil. Por ello, la información se organiza en secciones simples y accesibles desde una navegación inferior.

**Figura XX**

Estructura general de información de la aplicación móvil IdeaForge

[Insertar imagen o diagrama de arquitectura de información de la app móvil]

La aplicación se organizará en las siguientes secciones principales:

| Sección | Propósito |
|---|---|
| Home | Mostrar ideas recomendadas, proyectos recientes y accesos rápidos. |
| Search | Permitir la búsqueda y filtrado de proyectos por palabras clave, roles, habilidades o intereses. |
| Create | Facilitar la publicación de una nueva idea de proyecto. |
| Messages | Centralizar conversaciones entre creadores y postulantes. |
| Profile | Gestionar información personal, habilidades, intereses y actividad del usuario. |

Esta organización permite que el usuario tenga acceso directo a las funciones centrales de IdeaForge desde cualquier parte de la aplicación, reduciendo la fricción y favoreciendo una experiencia simple.

---

## 3.1.2.1. Organization Systems

Para organizar la información dentro de IdeaForge se aplicarán distintos sistemas de organización, de acuerdo con el tipo de contenido y la acción que el usuario necesite realizar.

### Organización jerárquica

La organización jerárquica se utilizará para priorizar la información más importante en cada pantalla. En la aplicación móvil, el usuario debe poder identificar rápidamente qué acción realizar y qué información necesita revisar primero.

Por ejemplo, en la pantalla de detalle de un proyecto, la información se presentará en el siguiente orden:

1. Nombre del proyecto.
2. Breve descripción.
3. Estado o etapa del proyecto.
4. Roles requeridos.
5. Cantidad de miembros.
6. Información del creador.
7. Botón de acción para postular o guardar.

Este orden permite que el usuario evalúe rápidamente si una idea es relevante para sus intereses o habilidades.

### Organización secuencial

La organización secuencial se utilizará en procesos que requieren pasos ordenados para completarse correctamente. Esto permitirá guiar al usuario de manera clara y evitar que se sienta perdido durante tareas importantes.

Se aplicará principalmente en los siguientes flujos:

| Flujo | Secuencia propuesta |
|---|---|
| Registro de usuario | Crear cuenta → Completar perfil → Seleccionar habilidades → Ingresar a Home |
| Inicio de sesión | Ingresar credenciales → Validar acceso → Mostrar pantalla principal |
| Creación de idea | Datos básicos → Descripción → Roles requeridos → Vista previa → Publicación |
| Postulación | Ver detalle → Presionar Apply → Confirmar postulación → Ver estado |

Este tipo de organización facilita que los usuarios completen acciones importantes sin omitir información relevante.

### Organización matricial

La organización matricial se utilizará en las pantallas de exploración y búsqueda, donde el usuario necesita combinar distintos criterios para encontrar proyectos adecuados.

Por ejemplo, un usuario podrá buscar proyectos mediante combinaciones como:

| Criterio | Ejemplo |
|---|---|
| Rol | Developer, Designer, Marketing |
| Habilidad | UX/UI, React, Flutter, Business |
| Interés | Education, Technology, Sustainability |
| Etapa | Idea, Prototype, Active |
| Estado | Open, In progress, Closed |

Este sistema permite que los usuarios encuentren proyectos más alineados con sus habilidades e intereses, mejorando la relevancia de los resultados mostrados.

### Esquemas de categorización

La aplicación también utilizará esquemas de categorización para ordenar mejor el contenido:

| Esquema | Aplicación en IdeaForge |
|---|---|
| Por tópicos | Categorías de proyectos como tecnología, educación, salud, sostenibilidad o negocios. |
| Según audiencia | Usuarios creadores de ideas y usuarios colaboradores. |
| Cronológico | Proyectos recientes, postulaciones enviadas y mensajes recientes. |
| Por estado | Ideas abiertas, proyectos en formación, proyectos activos o proyectos cerrados. |
| Por roles | Developer, Designer, Marketing, Business, Data Analyst, Content Creator. |

**Figura XX**

Sistema de organización de información en IdeaForge

[Insertar imagen o cuadro visual del sistema de organización]

---

## 3.1.2.2. Labelling Systems

El sistema de etiquetado de IdeaForge busca representar la información de manera simple, directa y fácil de entender para los usuarios. Las etiquetas deben utilizar pocas palabras y evitar términos técnicos innecesarios.

La aplicación utilizará principalmente etiquetas en inglés, debido a que los mock-ups y la interfaz principal se plantean con una línea visual moderna y orientada a un público familiarizado con productos digitales. Sin embargo, estas etiquetas podrán adaptarse posteriormente a español mediante internacionalización si el equipo lo considera necesario.

A continuación, se presentan las principales etiquetas propuestas para la aplicación móvil:

| Etiqueta | Descripción |
|---|---|
| Home | Pantalla principal donde se muestran ideas recomendadas y proyectos recientes. |
| Search | Sección para buscar ideas, habilidades, roles o personas. |
| Create | Acción principal para publicar una nueva idea de proyecto. |
| Messages | Sección donde se visualizan conversaciones con otros usuarios. |
| Profile | Vista donde el usuario gestiona su información personal, habilidades e intereses. |
| Log In | Botón para iniciar sesión en la aplicación. |
| Create account | Botón para registrar una nueva cuenta. |
| Ideas for you | Sección que presenta ideas recomendadas para el usuario. |
| View | Acción para visualizar el detalle de una idea o proyecto. |
| Apply | Acción para postular a un proyecto. |
| Save | Acción para guardar un proyecto y revisarlo después. |
| Developer | Rol asociado a desarrollo de software. |
| Design | Rol asociado a diseño UX/UI o diseño visual. |
| Marketing | Rol asociado a comunicación, difusión o estrategia comercial. |
| Tech | Categoría relacionada con tecnología. |
| Recommended | Etiqueta para destacar ideas sugeridas por afinidad o relevancia. |

**Figura XX**

Etiquetas principales de la aplicación móvil IdeaForge

[Insertar imagen de etiquetas, chips o navegación de la aplicación]

También se establecen términos que deben evitarse dentro de la experiencia de usuario, debido a que no representan correctamente la propuesta de valor de IdeaForge:

| Término a evitar | Motivo |
|---|---|
| Cliente | Puede dar la idea de una relación comercial o transaccional. |
| Freelancer | Sugiere contratación de servicios independientes. |
| Proveedor | No representa la lógica colaborativa de la plataforma. |
| Empleo | Puede confundir IdeaForge con una bolsa laboral. |
| Contratar | No corresponde al objetivo de formar equipos alrededor de ideas. |
| Servicio | Puede asociarse a venta de servicios y no a colaboración. |

En su lugar, se priorizarán términos como idea, proyecto, colaboración, equipo, postulación, creador, colaborador, rol y habilidades.

---

## 3.1.2.3. SEO Tags and Meta Tags

Aunque el alcance principal de esta sección está orientado a la aplicación móvil, se consideran elementos generales de posicionamiento digital para mantener una identidad clara de IdeaForge en entornos web, buscadores y tiendas de aplicaciones. En este caso, los elementos SEO se plantean de manera referencial para la presencia digital general, mientras que los elementos ASO se orientan específicamente a la publicación futura de la aplicación móvil en una app store.

### SEO Tags referenciales

| Elemento | Valor propuesto |
|---|---|
| Title | IdeaForge | Build ideas together |
| Meta Description | IdeaForge is a mobile app that helps students, entrepreneurs and creatives publish project ideas and connect with people based on roles, skills and interests. |
| Meta Keywords | project ideas, collaboration, startup ideas, team building, students, entrepreneurs, mobile app, skills, roles |
| Author | IdeaForge Team |
| Robots | index, follow |

Ejemplo de implementación:

```html
<title>IdeaForge | Build ideas together</title>
<meta name="description" content="IdeaForge is a mobile app that helps students, entrepreneurs and creatives publish project ideas and connect with people based on roles, skills and interests.">
<meta name="keywords" content="project ideas, collaboration, startup ideas, team building, students, entrepreneurs, mobile app, skills, roles">
<meta name="author" content="IdeaForge Team">
<meta name="robots" content="index, follow">
````

### Open Graph Tags

Los Open Graph Tags permitirían que IdeaForge se visualice correctamente cuando sea compartido en redes sociales o plataformas digitales.

```html
<meta property="og:title" content="IdeaForge | Build ideas together">
<meta property="og:description" content="Publish ideas, discover projects and find people to build with.">
<meta property="og:image" content="URL_DE_IMAGEN_PREVIEW">
<meta property="og:url" content="URL_DE_IDEAFORGE">
<meta property="og:type" content="website">
```

### Twitter Cards

```html
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="IdeaForge | Build ideas together">
<meta name="twitter:description" content="Find your next team and turn ideas into projects.">
<meta name="twitter:image" content="URL_DE_IMAGEN_TWITTER">
```

### ASO Elements

Para la futura publicación de la aplicación móvil, se consideran los siguientes elementos de App Store Optimization:

| Elemento ASO    | Valor propuesto                                                                                                                                                                                                                                                                    |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| App Title       | IdeaForge                                                                                                                                                                                                                                                                          |
| App Subtitle    | Find your next team                                                                                                                                                                                                                                                                |
| App Keywords    | ideas, projects, startup, team, collaboration, students, skills, roles                                                                                                                                                                                                             |
| App Description | IdeaForge helps students, entrepreneurs and creatives publish project ideas, discover opportunities and connect with people based on roles, skills and interests. The app is designed to help users form teams around early-stage ideas and turn them into collaborative projects. |
| App Category    | Productivity / Social Networking                                                                                                                                                                                                                                                   |
| App Tagline     | Turn ideas into projects with the right people.                                                                                                                                                                                                                                    |

**Figura XX**

Vista referencial de elementos ASO para IdeaForge

[Insertar imagen referencial de App Store / Google Play con información de IdeaForge]

---

## 3.1.2.4. Searching Systems

El sistema de búsqueda de IdeaForge permitirá que los usuarios encuentren ideas, proyectos, roles o habilidades de manera rápida y precisa. Esta funcionalidad es importante porque la plataforma puede contener múltiples proyectos publicados, por lo que los usuarios necesitan mecanismos claros para filtrar y descubrir oportunidades relevantes.

La búsqueda estará integrada principalmente en la pantalla **Search**, pero también se incluirá una barra de búsqueda rápida en la pantalla **Home** para facilitar el acceso inmediato a proyectos o palabras clave.

**Figura XX**

Vista de búsqueda de la aplicación móvil IdeaForge

[Insertar imagen de la pantalla Search o barra de búsqueda]

La búsqueda permitirá filtrar contenido de acuerdo con los siguientes criterios:

| Criterio de búsqueda | Descripción                                                      | Ejemplo                               |
| -------------------- | ---------------------------------------------------------------- | ------------------------------------- |
| Palabra clave        | Permite buscar ideas por título, descripción o tema.             | AI, education, health, fintech        |
| Rol requerido        | Permite encontrar proyectos que buscan un perfil específico.     | Developer, Designer, Marketing        |
| Habilidad            | Permite buscar proyectos relacionados con habilidades concretas. | UX/UI, React, Flutter, Data Analysis  |
| Interés              | Permite filtrar ideas según áreas de afinidad.                   | Technology, Sustainability, Education |
| Etapa del proyecto   | Permite identificar el nivel de avance de la idea.               | Idea, Prototype, Active               |
| Estado del proyecto  | Permite saber si el proyecto aún recibe colaboradores.           | Open, In progress, Closed             |

Después de realizar una búsqueda, los resultados se presentarán mediante tarjetas de proyecto. Cada tarjeta deberá mostrar información suficiente para que el usuario pueda evaluar rápidamente si el proyecto es relevante.

Cada resultado de búsqueda incluirá:

| Elemento                 | Descripción                                  |
| ------------------------ | -------------------------------------------- |
| Nombre del proyecto      | Identifica la idea publicada.                |
| Descripción breve        | Resume el propósito del proyecto.            |
| Roles requeridos         | Muestra los perfiles que se necesitan.       |
| Habilidades relacionadas | Permite identificar afinidad con el usuario. |
| Número de miembros       | Indica la cantidad de integrantes actuales.  |
| Estado o etapa           | Muestra si está en idea, prototipo o activo. |
| Botón de acción          | Permite ver detalle o postular.              |

El objetivo del sistema de búsqueda es reducir la sensación de desorden y ayudar al usuario a encontrar proyectos compatibles con sus intereses, habilidades y disponibilidad.

---

## 3.1.2.5. Navigation Systems

El sistema de navegación de IdeaForge estará diseñado específicamente para una aplicación móvil. Por ello, se utilizará una barra de navegación inferior, ya que este patrón facilita el acceso rápido a las funciones principales desde cualquier pantalla.

La navegación inferior permitirá que el usuario se desplace entre las secciones principales de manera simple, manteniendo siempre visibles las acciones más importantes de la aplicación.

**Figura XX**

Sistema de navegación inferior de IdeaForge

[Insertar imagen de la barra de navegación inferior]

La barra de navegación estará compuesta por cinco opciones principales:

| Opción   | Función                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------- |
| Home     | Permite acceder a la pantalla principal con ideas recomendadas y proyectos recientes.                           |
| Search   | Permite buscar y filtrar proyectos según palabras clave, roles, habilidades o intereses.                        |
| Create   | Permite crear una nueva idea de proyecto. Esta acción estará destacada visualmente por ser una función central. |
| Messages | Permite revisar conversaciones con creadores, postulantes o colaboradores.                                      |
| Profile  | Permite gestionar la información del usuario, habilidades, intereses y actividad.                               |

La opción **Create** tendrá mayor énfasis visual, ubicándose en el centro de la barra de navegación. Esto responde a la importancia de la publicación de ideas dentro del producto, ya que IdeaForge depende de que los usuarios puedan compartir proyectos y formar equipos alrededor de ellos.

Además de la navegación inferior, se utilizarán otros elementos de navegación complementarios:

| Elemento               | Uso                                                         |
| ---------------------- | ----------------------------------------------------------- |
| Cards de proyectos     | Permiten navegar hacia el detalle de una idea.              |
| Chips de filtros       | Permiten cambiar rápidamente la categoría de exploración.   |
| Botones de acción      | Permiten ejecutar acciones como View, Apply, Save o Create. |
| Íconos de notificación | Permiten acceder a alertas o actualizaciones importantes.   |
| Back navigation        | Permite regresar a la pantalla anterior en flujos internos. |

En conjunto, el sistema de navegación busca ofrecer una experiencia fluida, intuitiva y adecuada para usuarios móviles, permitiendo que las funciones principales estén siempre disponibles con pocos toques.

---

## 3.1.3. Landing Page UI Design

Esta sección será completada posteriormente por el equipo encargado del diseño de la Landing Page. En el alcance actual del presente avance, el desarrollo se centra principalmente en la experiencia móvil de IdeaForge.

[Espacio reservado para completar el diseño UI de la Landing Page]

---

## 3.1.3.1. Landing Page Wireframe

Esta sección será completada posteriormente con los wireframes correspondientes a la Landing Page.

**Figura XX**

Landing Page Wireframe

[Insertar wireframe de Landing Page]

---

## 3.1.3.2. Landing Page Mock-up

Esta sección será completada posteriormente con el mock-up correspondiente a la Landing Page.

**Figura XX**

Landing Page Mock-up

[Insertar mock-up de Landing Page]

---

## 3.1.4. Mobile Applications UX/UI Design

En esta sección se presenta la propuesta de experiencia de usuario e interfaz visual para la aplicación móvil de IdeaForge. La solución móvil se diseña tomando en cuenta los objetivos principales del usuario: iniciar sesión, explorar ideas, buscar proyectos, crear una idea, postular a iniciativas, comunicarse con otros usuarios y administrar su perfil.

La propuesta UX/UI se enfoca en una experiencia simple, moderna y atractiva, basada en una interfaz de modo oscuro con acentos en violeta, cian y magenta. Esta línea visual busca diferenciar a IdeaForge de plataformas tradicionales, reforzando su identidad como una aplicación orientada a creatividad, tecnología y colaboración.

Los diseños móviles deberán evidenciar la aplicación de los principios de diseño definidos previamente, como jerarquía visual, consistencia, claridad, legibilidad, navegación simple y uso adecuado de espacios.

---

## 3.1.4.1. Mobile Applications Wireframes

En esta sección se presentarán los wireframes de la aplicación móvil de IdeaForge. Los wireframes permitirán visualizar la estructura inicial de las pantallas, la ubicación de los principales elementos de navegación y la organización del contenido antes de aplicar estilos visuales definitivos.

El objetivo de los wireframes es validar la distribución de información, la jerarquía de elementos y la secuencia de interacción en las principales pantallas de la aplicación. Estos diseños servirán como base para el desarrollo posterior de los mock-ups de alta fidelidad.

Las pantallas consideradas para los wireframes son las siguientes:

| Pantalla         | Propósito                                                                             |
| ---------------- | ------------------------------------------------------------------------------------- |
| Login            | Permitir que el usuario ingrese a su cuenta.                                          |
| Register         | Permitir que un nuevo usuario cree una cuenta.                                        |
| Complete Profile | Recopilar datos iniciales, habilidades e intereses.                                   |
| Home             | Mostrar ideas recomendadas y proyectos recientes.                                     |
| Search           | Permitir la búsqueda y filtrado de ideas o proyectos.                                 |
| Project Detail   | Mostrar información completa de una idea y permitir acciones como View, Apply o Save. |
| Create Idea      | Permitir publicar una nueva idea de proyecto.                                         |
| Applications     | Mostrar postulaciones enviadas y su estado.                                           |
| Messages         | Permitir la comunicación entre usuarios.                                              |
| Profile          | Mostrar y editar información del usuario.                                             |

**Figura XX**

Wireframe de pantalla Login

[Insertar wireframe de Login]

**Figura XX**

Wireframe de pantalla Register

[Insertar wireframe de Register]

**Figura XX**

Wireframe de pantalla Complete Profile

[Insertar wireframe de Complete Profile]

**Figura XX**

Wireframe de pantalla Home

[Insertar wireframe de Home]

**Figura XX**

Wireframe de pantalla Search

[Insertar wireframe de Search]

**Figura XX**

Wireframe de pantalla Project Detail

[Insertar wireframe de Project Detail]

**Figura XX**

Wireframe de pantalla Create Idea

[Insertar wireframe de Create Idea]

**Figura XX**

Wireframe de pantalla Applications

[Insertar wireframe de Applications]

**Figura XX**

Wireframe de pantalla Messages

[Insertar wireframe de Messages]

**Figura XX**

Wireframe de pantalla Profile

[Insertar wireframe de Profile]

Los wireframes deberán mantener una estructura limpia y clara, priorizando la ubicación de los elementos más importantes. En esta etapa no será necesario aplicar la paleta visual completa, ya que el objetivo principal es validar la estructura de navegación y la organización de contenido.

---

## 3.1.4.2. Mobile Applications Wireflow Diagrams

Esta sección será completada posteriormente con los Wireflow Diagrams de la aplicación móvil. En este avance no se desarrollan los wireflows, ya que primero se validarán las pantallas base mediante wireframes.

[Espacio reservado para wireflows de la aplicación móvil]

---

## 3.1.4.3. Mobile Applications Mock-ups

Esta sección será completada posteriormente con los mock-ups de alta fidelidad de la aplicación móvil. Los mock-ups aplicarán la paleta de colores, tipografías, componentes visuales, cards, chips, botones y sistema de navegación definidos en las Style Guidelines.

**Figura XX**

Mock-up de pantalla Login

[Insertar mock-up de Login]

**Figura XX**

Mock-up de pantalla Home

[Insertar mock-up de Home]

[Espacio reservado para mock-ups adicionales de la aplicación móvil]

```
```
