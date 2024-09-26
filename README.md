<p align="center">
  <img src="assets/upc_logo.png" alt="Logo" width="200"/>
</p>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas</h3>
<h4 align="center"> Ingeniería de Sistemas y Computación | Ingeniería de Software  </h4>
<h4 align="center"> Desarrollo de Soluciones IOT </h4>
<h4 align="center"> Informe de Trabajo Final </h4>

### Startup: Debuggers
#### Team Members
- Arrunátegui Aguilar, Josué David 
- Botello Saldarriaga, Anthony Jean Pierre
- Chero Eme, Eduardo Andre
- Lévano Cavero, Eduardo Sebastián
- Moreno Rosales, Claudio Jesús
#### Sección: SW74
#### Profesor: Angel Augusto Velasquez Nuñez
#### Producto: FastPorte
#### Ciclo: 2024-02
<h4 align="center"> Agosto, 2024</h4>

___
# Registro de Versiones del Informe

| Versión | Fecha      | Autor                             | Descripción de modificación                                                |
| ------- | ---------- | --------------------------------- | -------------------------------------------------------------------------- |
| 1.0     | 22/08/2024 | Sebastián Lévano                  | Creación del archivo base en Markdown para el desarrollo del Final Project |
| 1.1     | 01/08/2024 | Sebastián Lévano                  | Desarrollo del Capítulo 3                                                  |
| 1.2     | 26/08/2024 | Anthony Botello                   | Desarrollo del Capítulo 1                                                  |
| 1.3     | 01/09/2024 | Claudio Moreno                    | Desarrollo del Capítulo 2                                                  |
| 1.4     | 05/09/2024 | Eduardo Chero & Josue Arrunátegui | Desarrollo del Capítulo 4                                                  |
| 1.5     | 16/09/2024 | Sebastián Lévano                  | Actualización de índice, títulos y subtítulos para el Trabajo Parcial      |
| 1.6     | 19/09/2024 | Sebastián Lévano                  | Correcciones del Capítulo I y Outcomes                                     |

---

# Project Report Collaboration Insights

- Link del repositorio Github: [Github](https://github.com/orgs/Debuggers-SW74) / [https://github.com/Debuggers-SW74/final-report](https://github.com/Debuggers-SW74/final-report)

![Repositorio final-report GitHub](./assets/collaboration_insights/final-report_repository.png)

**Desarrollo de las actividades del informe:**

- TB1: Se desarrollaron los capítulos I, II, III y IV, donde cada miembro se encargo en el avance de uno de estos capítulos en el repositorio de GitHub, empleando Gitflow. A continuación, la evidencia de los commits realizados:

![TB1 Collaboration Insights](./assets/collaboration_insights/tb1_collaboration.png)

Durante la realización de la entrega TB1 se abordaron los cuatro primeros capítulos. Se brindo la introducción del proyecto, explicando a detalle la Startup y cuál será la problemática que se abordará apoyándose del Lean UX Process en el capítulo I. Asimismo, cuál es la solución propuesta y cómo está resulta adecuada. La validación de la propuesta de solución se realizó mediante el análisis de los requisitos en el capítulo II. Durante este capítulo se llevaron a cabo artefactos importantes como el análisis competitivo y las entrevistas a los segmentos objetivos contemplados para corroborar las suposiciones e hipótesis planteadas en el capítulo anterior. Posteriormente, por medio del capítulo III se definió las características de la aplicación su priorización el desarrollo ejecutando el Product Backlog y sus Historias de Usuario relacionadas. Finalmente en el capítulo IV se diseñaron los diagramas de arquitecturas necesarios para la aplicación basados en el desarrollo previo de los Bounded Context.

- TP: Se desarrollaron los capítulos V y VI, en el cual para el capítulo VI se llevo a cabo la ejecución de los aspectos necesarios para cumplir con el Sprint 1. Este Sprint involucra el desarrollo de la página de aterrizaje, *Landing Page* y la primera versión del *Web Application*.
![TP Collaboration Insights](./assets/collaboration_insights/tp_collaboration.png)

La presenta entrega cubrió el cumplimiento de los capítulos V y VI del informe. A lo largo del quinto capítulo se definieron las guías de estilo que se aplicarán en la realización de las soluciones de software propuestas por la Startup. Asimismo,  se diseño la estructura y organización del contenido de la aplicación web FastPorte para facilitar su acceso y comprensión por parte de los usuarios. También se diseño el Landing Page, el contenido que presentará y el aspecto que tendrá por medio de los wireframes y mock-ups. De igual manera para la aplicación web, aunque detallando el flujo que seguirá cada una de sus funcionalidades y características. Por otro lado, se empezó con el desarrollo de software siguiendo los elementos contemplados para el primer Sprint, designado para completar el Landing Page y presentar una primera versión de la aplicación web.

---
# Contenido 
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2.  Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ux-ui)
  - [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guiledines)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems](#521-organization-systems)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    - [5.3.2. Labeling Page Mock-up](#532-landing-page-mock-up)
  - [5.4. Application UX/UI Design](#54-application-ux-ui-design)
    - [5.4.1. Applications Wireframes](#541-applications-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
    - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
  - [5.5. Applications Prototyping](#55-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation-deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide-conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
  - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services-applications-implementation)
    - [6.2.1. Sprint 1](#621-sprint-1)
      - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
      - [6.2.1.2. Sprint Backlog 1](#6212-sprint-backlog-1)
      - [6.2.1.3. Development Evidence for Sprint Review](#6213-development-evidence-for-sprint-review)
      - [6.2.1.4. Testing Suite Evidence for Sprint Review](#6214-testing-suite-evidence-for-sprint-review)
      - [6.2.1.5. Execution Evidence for Sprint Review](#6215-execution-evidence-for-sprint-review)
      - [6.2.1.6. Services Documentation Evidence for Sprint Review](#6216-services-documentation-evidence-for-sprint-review)
      - [6.2.1.7. Software Deployment Evidence for Sprint Review](#6217-software-deployment-evidence-for-sprint-review)
      - [6.2.1.8. Team Collaboration Insights during Sprint](#6218-team-collaboration-insights-during-sprint)

---

# Student Outcome

| Criterio Específico                                                                             | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Conclusiones                                                                                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                | *Eduardo Sebastián Lévano Cavero*<br>**TB1:**<br>A través de la realización de los To Be Scenario Mapping y User Stories, lideré la definición de escenarios futuros y necesidades del usuario, respectivamente, lo que permitió al equipo visualizar y priorizar funcionalidades clave. Mediante el Impact Mapping, pudimos establecer en conjunto relaciones claras entre los objetivos estratégicos y las características del producto, garantizando un enfoque alineado con las metas organizacionales. Finalmente, en el Product Backlog, se gestionaron las tareas de manera colaborativa, facilitando una planificación y ejecución eficientes que reflejan las prioridades acordadas en equipo. <br><br>*Anthony Botello Saldarriaga* <br>**TB1:**<br>En el presente proyecto, colaboré activamente en el liderazgo conjunto del equipo. Contribuí en la definición del startup y solution profile, y participé en la creación de los Lean UX Problem Statements y su análisis. Además, apoyé en la elaboración del Lean UX Canvas, tomando decisiones clave en conjunto con el equipo para asegurar un desarrollo efectivo y alineado con los objetivos del proyecto.<br><br>*Eduardo André Chero Emé*<br>**TB1:**<br>El desarrollo del event Storming nos ayudó para tener una visualizacion más definida de nuestros bounded context para una mejor implementación en el código. Clasificar los escenarios mediante el modelado de Message flows y generar los Bounded Context Canvas nos brindan un mejor entendimiento de las variables, conexiones y propisitos de los bounded context que impementamos. Por ultimo el desarrollo del diseño de la arquitectura de software en C4 para una mejor ejemplificacion de como va a realizarce nuestras conexiones de los respectivos servicios.<br><br>*Claudio Jesús Moreno Rosales*<br>**TB1:**<br>Para realizar y encontrar los requisitos de los segmentos objetivos se tuvo que realizar cada parte con los miembros del equipo para establecer cuales son los requisitos encontrados, como se debería ver los User Persona, User Journey Map, entre otros para entender y empatizar a profundidad con los usuarios.<br><br>*Josue David Arrunategui Aguilar*<br>**TB1:**<br>En el desarrollo del proyecto, asumí un papel clave en el diseño y la implementación de los bounded contexts de Usuario, Viaje y Sensor. Mi enfoque incluyó la definición precisa de cada contexto para garantizar una integración efectiva en el sistema. | *TB1*<br>La presente entrega sirvió para validar que la solución propuesta es adecuada para los segmentos objetivo abordados, esto en base al trabajo colaborativo realizado durante las entrevistas y el análisis de estas. Asimismo, por el desarrollo de los apartados involucrados desde la Introducción hasta la estructuración de la arquitectura durante el empleo de C4. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | *Eduardo Sebastián Lévano Cavero*<br>**TB1:**<br>Por medio de los To Be Scenario Mapping y las User Stories, identificamos y documentamos las necesidades y expectativas de los usuarios, asegurando que todas las voces fueran escuchadas y consideradas. Mediante el Impact Mapping, en grupo alineamos las metas estratégicas con las funcionalidades del producto, permitiendo una planificación clara y enfocada. En el Product Backlog, priorizamos y planificamos las tareas de forma conjunta, lo que facilitó el cumplimiento de los objetivos establecidos dentro de un marco de trabajo inclusivo y bien organizado.<br><br>*Anthony Botello Saldarriaga* <br>**TB1:**<br>En el desarrollo, fomenté un entorno colaborativo e inclusivo asegurando que todas las ideas fueran escuchadas y valoradas. Participé en la definición de metas claras para el proyecto, colaborando en la planificación de tareas específicas como el desarrollo de los diferentes puntos del informe. Además, me aseguré de que los plazos y objetivos se cumplieran de manera eficiente, distribuyendo responsabilidades entre los miembros del equipo.<br><br>*Eduardo André Chero Emé*<br>**TB1:**<br>A través de EventStorming, se identificaron los contextos potenciales y se modelaron los flujos de mensajes del dominio; esto permitió utilizar los Bounded Context Canvases para encontrar contextos delimitados. Posteriormente, se trabajó en el mapeo de contextos y el diseño de la arquitectura de software, creando diagramas a nivel de sistema, contexto, contenedor y despliegue, lo que proporcionó una visión clara de las conexiones y dependencias entre los servicios.<br><br>*Claudio Jesús Moreno Rosales*<br>**TB1:**<br> En la elaboración de las técnicas de Design Thinking como los User Persona, User Journey Map, entre otros, se pudo apreciar que los miembros del equipo colaboraron realizando sus entrevistas, analisando cuantiativamente las entrevistas y al final sacando los resultados finales para empatizar con nuestros segmentos objetivo.<br><br>*Josue David Arrunategui Aguilar*<br>**TB1:**<br>En el desarrollo del proyecto, asumí un papel clave en el diseño y la implementación de los bounded contexts de Usuario, Viaje y Sensor. Mi enfoque incluyó la definición precisa de cada contexto para garantizar una integración efectiva en el sistema.                                                                                                  | *TB1*<br>Se lograron los objetivos diseñados en grupo al completar la base del proyecto tanto a nivel de diseño como de arquitectura. Asimismo, al planear los elementos a desarrollar durante los siguientes Sprints.                                                                                                                                                           |

---
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Somos un grupo de estudiantes de la Universidad Peruana de Ciencias Aplicadas que, motivados por la creciente necesidad de seguridad en el transporte de materiales peligrosos, identificamos una oportunidad de negocio única. Durante nuestras investigaciones, notamos que el transporte de gases combustibles y otros productos peligrosos presenta riesgos significativos, tanto para los conductores como para el público en general. Estos riesgos, muchas veces subestimados o mal gestionados, pueden tener consecuencias catastróficas si no se abordan con soluciones tecnológicas adecuadas.

En respuesta a esta problemática, decidimos fundar TechCompany, una startup enfocada en ofrecer soluciones de vanguardia que integran la tecnología IoT para la supervisión en tiempo real de las condiciones de seguridad en el transporte de materiales peligrosos. Nuestro producto, FastPorte, no solo se centra en la implementación de sensores avanzados que monitorean parámetros críticos como fugas de gas, temperatura y presión, sino también en proporcionar una plataforma integral que facilita la gestión de estos datos para prevenir accidentes.

En TechCompany, entendemos que la seguridad no es solo una necesidad, sino una responsabilidad compartida entre todas las partes involucradas en la cadena de transporte. Por ello, nos hemos comprometido a desarrollar productos y servicios que no solo cumplan con las normativas internacionales más estrictas, sino que también superen las expectativas de nuestros clientes, brindándoles herramientas que aseguren la integridad de sus operaciones y protejan vidas.

**Misión:** 
Proporcionar soluciones tecnológicas innovadoras que garanticen la seguridad y eficiencia en el transporte de materiales peligrosos, contribuyendo así a la protección de vidas humanas y al cumplimiento de normativas internacionales de seguridad.

**Visión:**
Ser reconocidos como líderes en el mercado de soluciones IoT aplicadas al transporte de materiales peligrosos, impulsando un futuro más seguro y confiable para la industria del transporte a nivel nacional e internacional.

**Valores:**
- Seguridad
- Innovación
- Responsabilidad
- Compromiso con el cliente
- Sostenibilidad

### 1.1.2. Perfiles de integrantes del equipo

| Integrante        | Arrunátegui Aguilar, Josué David                        |
|-------------------|---------------------------------------------------------|
| **Código:** U202111033 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Me gusta dibujar, tocar guitarra y jugar videojuegos. Tengo conocimiento en el desarrollo frontend con lenguajes como angular y vue.js, así como desarrollo móvil con flutter. Planeo especializarme en desarrollo web o como Analista de Datos. | ![Josué Perfil](assets/capitulo1/integrantes/josue.jpg) |

| Integrante                                                                                                                                                                                                                                                                                                                                                                                                       | Botello Saldarriaga, Anthony Jean Pierre                    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Código:** U20201B846 <br>  **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Tengo 23 años y soy estudiante de Ingeniería de Software con conocimientos y habilidades en distintos lenguajes de programación. Actualmente curso el noveno ciclo de la carrera y mi meta es ser un profesional destacado el cual rija sus decisiones por sus valores y el bien de la empresa donde labore. Me interesa el desarrollo de la tecnología y los avances que existen en la inteligencia artificial. | ![Anthony Perfil](assets/capitulo1/integrantes/anthony.jpg) |

| Integrante                                                                                                                                                                                                                                          | Chero Eme, Eduardo Andre                                    |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Código:** U20201F282 <br> **Carrera:** Ingeniería de software <br> **Acerca de mí:** Me gustan los videojuegos y las series, quiero especializarme en ciberseguridad para tener una ganancia estable mientras creo videojuegos aparte por pasión. | ![Eduardo Perfil](assets/capitulo1/integrantes/eduardo.jpg) |

| Integrante                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Lévano Cavero, Eduardo Sebastián                                |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| **Código:** U20201C172 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Mi nombre es Sebastián, tengo 21 años y soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Elegí esta carrera porque me fascina crear y diseñar procesos que faciliten procesos complejos. Por ello, cuando tengo un poco de tiempo libre lo uso para relajarme y para aprender más de lo que me apasiona, la programación, se puede decir que es uno de mis hobbies. Además, de la programación también disfruto de jugar vóley, fútbol o algún videojuego con mis amigos. | ![Sebastián Perfil](assets/capitulo1/integrantes/sebastian.jpg) |

| Integrante        | Moreno Rosales, Claudio Jesús                               |
|-------------------|-------------------------------------------------------------|
| **Código:** U20191E800 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** La tecnología en general me gusta mucho, por ello, sigo constantemente explorando nuevas herramientas y tendencias del mundo tech. Estoy siempre dispuesto a aprender y enfrentar desafíos. Un campo que me interesa mucho es el de la Seguridad Informática, para lograr que el desarrollo de software sea de la más alta calidad posible y mantener seguros a los clientes. | ![Claudio Perfil](assets/capitulo1/integrantes/claudio.jpg) |

## 1.2. Solution Profile

En esta sección, exploraremos en detalle la solución que nuestra startup, TechCompany, propone para abordar los desafíos identificados en el transporte de materiales peligrosos. 

### 1.2.1 Antecedentes y problemática

#### Antecedentes

El transporte de materiales peligrosos, como gases combustibles y productos químicos, ha sido históricamente una actividad de alto riesgo. A lo largo de los años, numerosos incidentes han demostrado las graves consecuencias que pueden surgir cuando no se implementan medidas de seguridad adecuadas. Desde explosiones devastadoras hasta fugas tóxicas que ponen en peligro la vida de conductores y comunidades enteras, la necesidad de soluciones efectivas en este campo es evidente.

Para mitigar este problema, soluciones similares a nuestra propuesta han surgido en el mercado como: 
- **Geotab:** Es una plataforma de gestión de flotas que ofrece soluciones avanzadas de telemetría para vehículos de transporte, incluyendo aquellos que manejan materiales peligrosos. La solución permite el monitoreo en tiempo real de diversos parámetros del vehículo, tales como la ubicación, la velocidad, y las condiciones de los activos transportados. 
- **TankScan:** Se especializa en la monitorización inalámbrica de tanques que contienen líquidos y gases peligrosos. Utilizando tecnología avanzada, permite a las empresas verificar remotamente los niveles de fluidos y planificar rutas de manera más eficiente, mejorando la seguridad y reduciendo costos operativos.
- **Samsara:** Plataforma integral de gestión de flotas que ofrece telemetría en tiempo real, rastreo GPS, monitoreo de condiciones ambientales como temperatura y presión, y herramientas de seguridad avanzada. Su tecnología ayuda a las empresas a mejorar la eficiencia operativa, cumplir con normativas de seguridad y reducir riesgos en el transporte de materiales peligrosos.

#### Problemática

Para abordar la problemática del transporte de materiales peligrosos, es fundamental comprender el contexto en el que se desarrolla y los actores involucrados. A continuación, presentamos un análisis de la problemática utilizando el marco de las 5 'W's y 2 'H's:

**Who? (¿Quién?)**
El problema afecta a una amplia gama de actores, desde los conductores que transportan materiales peligrosos hasta los supervisores de empresas que se encargan de la logística y el transporte. También involucra a las comunidades cercanas a las rutas de transporte y a las autoridades responsables de la seguridad pública.

**What? (¿Qué?)**
La principal problemática radica en la falta de monitoreo en tiempo real y la ausencia de sistemas que puedan detectar y alertar sobre condiciones peligrosas, como fugas de gas o cambios bruscos en la temperatura o presión, antes de que se conviertan en incidentes graves.

**Where? (¿Dónde?)**
Este problema es global, pero en el contexto de TechCompany, nos centramos en el transporte de materiales peligrosos dentro del Perú, un país con una geografía compleja que presenta desafíos adicionales para el transporte seguro.

**When? (¿Cuándo?)**
La problemática es constante, pero se vuelve especialmente crítica durante el transporte de largas distancias, en zonas remotas o en áreas urbanas densamente pobladas donde el riesgo de accidentes y sus consecuencias es mayor.

**Why? (¿Por qué?)**
Las causas de este problema son múltiples. La falta de tecnología avanzada en los vehículos de transporte, la escasa inversión en sistemas de seguridad, y la subestimación de los riesgos asociados son factores que han contribuido a que los incidentes continúen ocurriendo.

**How? (¿Cómo?)**
La solución a este problema pasa por la implementación de tecnologías de monitoreo en tiempo real que puedan alertar de inmediato a los conductores y operadores sobre cualquier condición peligrosa. FastPorte se posiciona para llenar este vacío mediante el uso de sensores IoT que supervisan constantemente las condiciones de seguridad y envían alertas en tiempo real.

**How much? (¿Cuánto?)**
El impacto potencial de no abordar esta problemática es significativo, tanto en términos de vidas humanas como de pérdidas económicas para las empresas y el costo social de los accidentes. La inversión en una solución como FastPorte es, por tanto, no solo justificada, sino esencial para mitigar estos riesgos.

### 1.2.2 Lean UX Process.

En esta sección, exploraremos cómo el Lean UX Process se aplica en el desarrollo de nuestro producto, FastPorte. Este enfoque nos permite centrarnos en la creación de valor para nuestros usuarios. Mediante la implementación de Lean UX, alineamos nuestra visión de negocio con las necesidades de nuestros clientes, asegurando que el producto no solo resuelva problemas relevantes, sino que también se adapte a un entorno que cambia.

#### 1.2.2.1. Lean UX Problem Statements.

Para comprender mejor los desafíos que nuestro proyecto abarca, hemos definido un Problem Statement. Este enunciado nos permite enmarcar de manera clara el problema que nuestro producto busca resolver, facilitando así el enfoque en soluciones que verdaderamente impacten en la vida de nuestros usuarios. 
##### Problem Statement:
El transporte de materiales peligrosos demanda una supervisión constante y efectiva de las condiciones de seguridad, tanto para los supervisores de transporte que deben monitorear el estado del transporte en tiempo real, como para los conductores que necesitan recibir alertas inmediatas sobre riesgos potenciales. Actualmente, hemos observado que existe una dificultad crítica en la detección y respuesta rápida ante incidentes durante el transporte, lo que pone en riesgo tanto la seguridad de los materiales como la integridad física de los conductores y otros actores en la vía. Esto también impacta en el cumplimiento normativo y en la reputación de las empresas involucradas.

¿Cómo podríamos mejorar la detección y respuesta temprana ante riesgos durante el transporte de materiales peligrosos para reducir incidentes y asegurar el cumplimiento normativo, medido por una reducción en incidentes de transporte y una mejora en los tiempos de respuesta ante alertas?

#### 1.2.2.2. Lean UX Assumptions

En esta sección, definimos las suposiciones clave que guiarán el desarrollo de FastPorte. Estas suposiciones se basan en una comprensión profunda de nuestros usuarios y del mercado, y nos permiten validar las decisiones de diseño y desarrollo a lo largo del proceso. 

##### FEATURES

Las características que hemos considerado son las siguientes:

- Registro de usuarios en dos perfiles: Supervisor y Conductor, con identificación y verificación adecuadas.
- Visualización de los perfiles de los conductores, incluyendo información relevante para el transporte de materiales peligrosos, como certificaciones y datos del vehículo.
- Los supervisores podrán crear y gestionar viajes, asignando conductores y supervisando el estado de los mismos en tiempo real.
- Los conductores recibirán notificaciones sobre los viajes asignados y alertas de seguridad durante el transporte.
- Monitoreo en tiempo real de las condiciones del material transportado (fugas de gas, temperatura, presión) con alertas automáticas a los supervisores y conductores.
- Historial de viajes y reportes de incidentes accesibles para ambos perfiles.
- Integración con sistemas de pago seguros para la facturación de servicios.
- Soporte para visualizar rutas y ubicación en tiempo real utilizando tecnología GPS.

##### BUSINESS OUTCOMES

Las suposiciones sobre business outcomes son:

- Asegurar el cumplimiento de las normativas de seguridad en el transporte de materiales peligrosos al adoptar un sistema de monitoreo en tiempo real que reduce las violaciones de seguridad y permite una respuesta rápida ante incidentes.
- Los supervisores de transporte de materiales peligrosos aumentarán su uso del sistema gracias a la mayor confianza en la seguridad proporcionada por las alertas en tiempo real y la capacidad de prevenir incidentes antes de que ocurran.
- Los supervisores optimizarán la gestión de sus operaciones al reducir el tiempo invertido en tareas de supervisión manual y mejorar la coordinación entre los conductores y los supervisores a través de la gestión centralizada de los viajes y condiciones de transporte.
- Los usuarios reducirán significativamente el número de incidentes y accidentes durante el transporte de materiales peligrosos al responder de manera más eficiente a las alertas en tiempo real, disminuyendo el riesgo operativo y las pérdidas asociadas.

##### USER OUTCOMES AND BENEFITS

Para esta sección hemos considerado lo siguiente:

- Para los supervisores: 
	- Mejorar la gestión de sus operaciones de transporte, asegurando la seguridad de sus materiales y cumpliendo con las normativas.
	- Sentir confianza y seguridad en sus procesos, con la tranquilidad de que pueden mitigar incidentes antes de que se conviertan en problemas mayores, lo que además protege la reputación de la empresa.
	- Los supervisores percibirán la reducción de los incidentes durante el transporte, cumpliendo de forma más eficiente con las normativas y mejorando los tiempos de respuesta ante riesgos.
- Para los conductores: 
	- Aumentar la seguridad durante el transporte gracias a las alertas en tiempo real y la supervisión continua.
	- Los conductores sentirán que están mejor protegidos y que su seguridad está siendo priorizada, lo que disminuye la ansiedad durante los trayectos peligrosos.
	- Los conductores reaccionarán más rápido ante alertas de riesgo, reduciendo incidentes y aumentando la confianza en el sistema.
- Para ambos: 
	- Acceso a un sistema confiable que permite la monitorización de las condiciones de transporte y la gestión eficiente de los viajes.
	- Tanto supervisores como conductores sentirán que cuentan con una herramienta sólida y confiable, lo que genera una sensación de control y reduce el estrés ante posibles emergencias.
	- Ambos grupos utilizarán el sistema de manera más frecuente y eficiente, integrándolo en sus operaciones diarias y aumentando la confianza en su capacidad para prevenir incidentes.

##### BUSINESS ASSUMPTIONS

Con respecto a los business assumptions:

- Creemos que los supervisores de transporte de materiales peligrosos buscan soluciones que les ofrezcan seguridad y eficiencia en la gestión de sus operaciones.
- Los conductores necesitan una herramienta que les ofrezca seguridad adicional y la capacidad de gestionar su trabajo de manera más eficiente.
- Nuestros usuarios esperan que la información proporcionada por los sensores sea precisa y que las alertas sean confiables.
- Estas necesidades pueden ser satisfechas mediante una plataforma que integre la tecnología IoT para monitorear en tiempo real las condiciones de transporte y alertar sobre posibles riesgos.
- Los usuarios iniciales son supervisores de transporte de materiales peligrosos y conductores que buscan mejorar la seguridad en su trabajo diario.
- El valor principal que nuestros usuarios buscan en FastPorte es la seguridad y la confianza en la supervisión continua de sus operaciones.
- Obtendremos clientes a través de campañas dirigidas a supervisores y conductores mediante anuncios en internet y asociaciones estratégicas.
- Los ingresos se generarán a través de suscripciones a la plataforma, tarifas de servicio, y posibles acuerdos con aseguradoras que ofrezcan descuentos a empresas cuyos supervisores utilicen FastPorte.
- Nuestra principal competencia son otras soluciones de monitoreo y gestión de flotas, pero nos destacaremos por nuestro enfoque especializado en materiales peligrosos.
- El mayor riesgo es que las alertas no se detecten a tiempo o que la información proporcionada sea incorrecta, lo que podría llevar a incidentes durante el transporte. - Resolveremos esto mediante pruebas rigurosas de los sensores y un sistema de validación continua.

##### USER ASSUMPTIONS

Con respecto a los user assumptions:

- Los usuarios clave son los supervisores de transporte de materiales peligrosos y los conductores encargados de realizar dichos transportes.
- Los supervisores necesitan monitorear en tiempo real las condiciones de seguridad durante los trayectos para garantizar el cumplimiento normativo y evitar riesgos que puedan afectar su reputación y la seguridad del material transportado.
- Los conductores requieren una solución que les provea alertas inmediatas y confiables sobre condiciones peligrosas, lo que les permitirá actuar rápidamente para minimizar riesgos a su integridad física y a la seguridad en la carretera.
- La interfaz del producto debe ser sencilla e intuitiva para que tanto supervisores como conductores puedan interactuar con facilidad y enfocarse en sus tareas sin distracciones técnicas.
- Los conductores priorizarán la precisión de las alertas y la rapidez en la notificación de riesgos, ya que esto afecta directamente su seguridad personal durante los trayectos.
- Los supervisores de transporte están motivadas por el deseo de reducir costos operativos relacionados con incidentes, optimizar el cumplimiento de las regulaciones y mejorar la reputación de su servicio al demostrar proactividad en la gestión de riesgos.
- Los conductores están motivados por mejorar su seguridad personal y minimizar las interrupciones durante los trayectos, permitiéndoles cumplir con sus tareas de manera eficiente y sin incidentes.
- Las empresas de transporte pueden no estar dispuestas a invertir en hardware costoso o en sistemas complejos que requieran una implementación prolongada, por lo que valorarán una solución que sea rápida de implementar y de fácil integración con su infraestructura existente.
- Supervisores y conductores podrían resistirse al cambio si el sistema requiere modificar demasiado sus procesos actuales. Se asume que cuanto más fácil de usar y eficiente sea la solución, mayor será la adopción.

#### 1.2.2.3. Lean UX Hypothesis Statements

En esta sección, formularemos hipótesis basadas en nuestras suposiciones de Lean UX. Estas hipótesis nos permitirán validar si las soluciones que implementamos en FastPorte están efectivamente resolviendo los problemas identificados y generando los resultados deseados tanto para los usuarios como para el negocio.

##### HIPÓTESIS 1:
**Creemos que lograremos** una reducción en los incidentes y accidentes **si** los conductores de transporte de materiales peligrosos **pueden** mejorar su capacidad de respuesta a situaciones peligrosas en tiempo real **con** un sistema de alertas automatizadas basado en sensores de presión, temperatura y fugas.

##### HIPÓTESIS 2:
**Creemos que lograremos** una mejora en la eficiencia operativa **si** los supervisores de transporte **pueden** planificar y gestionar sus viajes de manera eficiente, asignando conductores y supervisando el estado de los mismos en tiempo real **con** un sistema de gestión centralizada de viajes.

##### HIPÓTESIS 3:
**Creemos que lograremos** una mejora en la trazabilidad y seguridad del transporte **si** los supervisores y conductores **pueden** consultar el historial de viajes y reportes de incidentes pasados **con** un sistema que documente estos eventos de manera clara y accesible.

##### HIPÓTESIS 4:
**Creemos que lograremos** una mejora en la seguridad del transporte **si** los conductores **pueden** recibir notificaciones sobre los viajes asignados y alertas de seguridad en tiempo real durante el transporte **con** un sistema de notificaciones y alertas confiable.

##### HIPÓTESIS 5:
**Creemos que lograremos** una adopción efectiva del sistema **si** los supervisores y conductores **pueden** registrarse y verificar su identidad de manera segura en dos perfiles (Supervisor y Conductor) con un **sistema** de registro e identificación adecuado.

##### HIPÓTESIS 6:
**Creemos que lograremos** el cumplimiento de las normativas de seguridad **si** los supervisores de transporte **pueden** visualizar los perfiles de los conductores, incluyendo certificaciones y datos del vehículo relevantes para el transporte de materiales peligrosos, **con** un sistema de gestión de perfiles.

#### 1.2.2.4. Lean UX Canvas

A lo largo de este capítulo, hemos desarrollado cada uno de los elementos fundamentales que componen el Lean UX Canvas. A continuación, presentamos el canvas que refleja nuestras suposiciones, problemáticas y soluciones clave para abordar las necesidades del mercado en el transporte de materiales peligrosos.

<table><tr><th colspan="2" valign="top"><b>LEAN UX CANVAS</b></th><th valign="top"><p>Fecha: 20/09/24</p><p>Iteración: 1</p></th></tr>
<tr><td valign="top"><p><b>1. Business problem</b></p><p></p><p>El transporte de materiales peligrosos demanda una supervisión constante y efectiva de las condiciones de seguridad, tanto para los encargados de supervisar que deben monitorear el estado del transporte en tiempo real, como para los conductores que necesitan recibir alertas inmediatas sobre riesgos potenciales. Actualmente, hemos observado que existe una dificultad crítica en la detección y respuesta rápida ante incidentes durante el transporte, lo que pone en riesgo tanto la seguridad de los materiales como la integridad física de los conductores y otros actores en la vía. Esto también impacta en el cumplimiento normativo y en la reputación de las empresas involucradas.</p><p></p><p>¿Cómo podríamos mejorar la detección y respuesta temprana ante riesgos durante el transporte de materiales peligrosos para reducir incidentes y asegurar el cumplimiento normativo, medido por una reducción en incidentes de transporte y una mejora en los tiempos de respuesta ante alertas?</p></td><td rowspan="2" valign="top"><p><b>5.Solutions</b></p><p>- Registro de usuarios en dos perfiles: Supervisor y Conductor, con identificación y verificación adecuadas para garantizar la seguridad en el acceso.</p><p>- Visualización de perfiles de los conductores, con certificaciones y datos relevantes para asegurar el cumplimiento normativo.</p><p>- Creación y gestión de viajes en tiempo real, asignando conductores y supervisando el estado de estos para mejorar la eficiencia operativa.</p><p>- Notificaciones y alertas de seguridad en tiempo real para los conductores, permitiendo una respuesta rápida ante riesgos durante el transporte.</p><p>- Monitoreo en tiempo real de las condiciones del material transportado (fugas de gas, temperatura, presión) con alertas automáticas a empresas y conductores.</p><p>- Historial de viajes y reportes de incidentes accesibles para ambos perfiles, mejorando la trazabilidad y aprendizaje a partir de incidentes.</p><p>- Integración con sistemas de pago seguros para facilitar la facturación de servicios.</p></td><td valign="top"><p><b>2.Business Outcomes</b></p><p>- Asegurar el cumplimiento de normativas de seguridad en el transporte de materiales peligrosos.</p><p>- Incrementar la confianza de las empresas en la seguridad del transporte de sus materiales.</p><p>- Mejorar la eficiencia operativa mediante la supervisión en tiempo real y la gestión centralizada de los viajes.</p><p>- Reducir el riesgo de incidentes y accidentes durante el transporte de materiales peligrosos.</p></td></tr>
<tr><td valign="top"><p><b>3. User</b></p><p></p><p>Nuestro producto se dirige a dos tipos de usuarios principales:</p><p>- <b>Supervisores de transporte de materiales peligrosos</b> que buscan mejorar la seguridad y el cumplimiento normativo.</p><p>- <b>Conductores de transporte de materiales peligrosos</b> que necesitan herramientas para aumentar la seguridad durante sus operaciones diarias.</p><p></p></td><td valign="top"><p><b>4. User outcomes & benefits</b></p><p>- Para los <b>supervisores</b>, FastPorte mejora la gestión de sus operaciones, incrementa la seguridad y asegura el cumplimiento normativo.</p><p>- Para los <b>conductores</b>, FastPorte ofrece una mayor seguridad mediante alertas en tiempo real y supervisión constante, reduciendo el riesgo de accidentes.</p><p>Para ambos, acceso a un sistema confiable que permite la monitorización de las condiciones de transporte y la gestión eficiente de los viajes.</p></td></tr>
<tr><td valign="top"><p><b>6. Hypotheses</b></p><p></p><p>- <b>Creemos que lograremos</b> una reducción en los incidentes y accidentes <b>si</b> los conductores de transporte de materiales peligrosos <b>pueden</b> mejorar su capacidad de respuesta a situaciones peligrosas en tiempo real <b>con</b> un sistema de alertas automatizadas basado en sensores de presión, temperatura y fugas.</p><p>- <b>Creemos que lograremos</b> una mejora en la eficiencia operativa <b>si</b> las empresas de transporte <b>pueden</b> planificar y gestionar sus viajes de manera eficiente, asignando conductores y supervisando el estado de los mismos en tiempo real <b>con</b> un sistema de gestión centralizada de viajes.</p><p>- <b>Creemos que lograremos</b> una mejora en la trazabilidad y seguridad del transporte <b>si</b> las <b>con</b> empresas y conductores <b>pueden</b> consultar el historial de viajes y reportes de incidentes pasados <b>con</b> un sistema que documente estos eventos de manera clara y accesible.</p></td><td valign="top"><p><b>7. ¿Qué es lo más importante que necesitamos aprender primero?</b></p><p></p><p>Validar la precisión y efectividad del sistema de alertas en tiempo real para que los usuarios confíen en ellas y tomen acciones preventivas.</p></td><td valign="top"><p><b>8. ¿Cuál es la menor cantidad de trabajo que debemos hacer para aprender la siguiente cosa más importante?</b></p><p></p><p>Desarrollar un prototipo funcional del sistema de alertas y realizar pruebas piloto con un grupo representativo de usuarios para evaluar su precisión y utilidad en situaciones reales.</p></td></tr>
</table>
## 1.3. Segmentos objetivo

En el desarrollo de FastPorte, hemos identificado dos segmentos de usuarios principales en el territorio peruano, cada uno con características y necesidades específicas que guían el diseño y funcionalidad de nuestra plataforma.

##### PRIMER SEGMENTO
El primer segmento está compuesto por los supervisores de transporte de materiales peligrosos. Estos supervisores, que operan en empresas de diferentes tamaños, suelen estar ubicados predominantemente en zonas industriales y áreas cercanas a puertos y fronteras. Muchos de ellos manejan varias operaciones que dependen de la seguridad y el cumplimiento normativo en el transporte de materiales peligrosos. Para estos supervisores, FastPorte ofrece una solución integral que les permite monitorear y gestionar las operaciones de transporte de manera más eficiente y que reduce el riesgo de incidente.

##### SEGUNDO SEGMENTO
El segundo segmento objetivo está compuesto por los conductores de transporte de materiales peligrosos. Estos profesionales, con edades comprendidas entre 25 y 55 años, operan principalmente en rutas nacionales y cuentan con formación técnica o certificaciones específicas para el manejo seguro de materiales peligrosos. Para estos conductores, FastPorte ofrece herramientas esenciales que mejoran su seguridad y eficiencia, como alertas en tiempo real sobre riesgos durante el transporte, así como la supervisión continua de las condiciones del material transportado. Estas funcionalidades permiten a los conductores reaccionar rápidamente ante situaciones peligrosas, reduciendo el riesgo de incidentes y garantizando un mayor control durante sus trayectos.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo

|Competidores directos  | Resumen |
|--|--|
| <a href ="#"><img src="https://i.postimg.cc/W1ZHHkmH/geotab.jpg" alt="Logo Geotab" width="300" height="150" /><br> https://www.geotab.com/es/ <br> </a> |GEOTAB es una empresa líder mundial en soluciones de gestión de flotas que ofrece una plataforma integral para digitalizar procesos, reducir costos y aumentar la sostenibilidad en la operación de vehículos. Su sistema incluye el dispositivo Geotab GO, que se instala fácilmente en los vehículos para recopilar datos sobre ubicación, velocidad, comportamiento del conductor y estado del vehículo. La plataforma proporciona herramientas para mejorar la seguridad de la flota, como informes detallados, alertas personalizadas y asesoramiento al conductor en tiempo real.   |
| <a href ="#"><img src="https://i.postimg.cc/1zZjh3J5/samsara.png" alt="Logo Samsara" width="300" height="100"/><br> https://www.samsara.com/mx/ </a> |Samsara es una plataforma integral de gestión de operaciones que conecta flotas, equipos, sitios y personal en una sola interfaz. Ofrece visibilidad en tiempo real, información basada en datos y flujos de trabajo optimizados para mejorar la eficiencia operativa. La plataforma ha ayudado a diversas empresas a reducir accidentes, mejorar la gestión de mantenimiento y tomar decisiones más rápidas, según testimonios de clientes. Además, Samsara ofrece un amplio ecosistema de integraciones listas para usar, permitiendo a las empresas ampliar sus soluciones y aprovechar al máximo sus sistemas existentes.   |
| <a href ="#"><img src="https://i.postimg.cc/FRrCzCMM/tankscan.png" alt="Logo TankScan" width="300" height="100" /><br>https://tankscan.com </a> |TankScan ofrece una solución de monitoreo inalámbrico de tanques que permite a las empresas verificar en tiempo real los niveles de líquido en múltiples tanques y ubicaciones desde una computadora o teléfono inteligente. Esta tecnología mejora la eficiencia de la flota, optimiza la gestión de inventario y aumenta la seguridad al eliminar la necesidad de lecturas manuales. El sistema utiliza hardware de vanguardia y la Plataforma de Inteligencia ATEK (AIP) basada en la nube, proporcionando alertas automáticas, un panel de control personalizable, mapeo de activos para optimizar rutas y capacidades de generación de informes.  |
<br><br>

|Competitive Analysis Landscape|
|--|

|¿Por qué llevar a cabo este análisis? |El objetivo del siguiente análisis competitivo es identificar las fortalezas y debilidades de FastPorte que es el producto final de TechCompany en relación con los posibles competidores para desarrollar estrategias efectivas para tener ventaja competitiva en el mercado.|
|--|--|
---
| Competidores                                      | <a href ="https://postimg.cc/hz71FmXB"><img src="https://i.postimg.cc/RFgsHQ9N/fastporte.png" alt="Logo FastPorte" width="4000" height="100" /></a>                                                      | <a href ="https://postimg.cc/SnydXjv6"><img src="https://i.postimg.cc/W1ZHHkmH/geotab.jpg" alt="Logo Geotab" width="4000" height="100"></a> | <div style="background: black;"><a href ="https://postimg.cc/0zcf7xTL"><img src="https://i.postimg.cc/1zZjh3J5/samsara.png" alt="Logo Samsara" width="5000" height="100"></a></div> | <a href ="https://postimg.cc/jW14kcdc"><img src="https://i.postimg.cc/FRrCzCMM/tankscan.png" alt="Logo TankScan" width="5000" height="100"></a> |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Perfil**                                        |                                                                                                                                                                                                          |                                                                                                                                             |                                                                                                                                                                                     |                                                                                                                                                 |
| Overview                                          | Plataforma web, aplicación móvil y sensores IoT                                                                                                                                                          | Plataforma web, aplicación móvil y dispositivo sensores IoT                                                                                 | Plataforma web y dispositivo GO IoT                                                                                                                                                 | Plataforma web, aplicación móvil y dispositivo sensores IoT                                                                                     |
| Ventaja competitiva ¿Qué valor ofrece al cliente? | Proporciona seguridad avanzada en el transporte de gases combustibles mediante sensores que detectan fugas y alertan a los conductores en tiempo real, evitando explosiones y garantizando la seguridad. | Amplia gama de datos para la seguridad y eficiencia de flotas mediante tecnología de monitoreo avanzada.                                    | Conectividad integral de operaciones mediante una plataforma unificada que ofrece visibilidad y análisis en tiempo real.                                                            | Monitoreo inalámbrico en tiempo real de niveles de tanques con alta precisión y alertas automatizadas.                                          |
| **Perfil de Marketing**                           |                                                                                                                                                                                                          |                                                                                                                                             |                                                                                                                                                                                     |                                                                                                                                                 |
| Mercado objetivo                                  | Transportistas que manejan vehículos de carga peligrosa y empresas que trabajan con materiales peligrosos y necesitan asegurar el transporte seguro de sus productos.                                    | Transporte, logística, servicios públicos, industria de gas, petróleo, minería, distribución de alimentos y reciclaje.                      | Empresas con operaciones complejas que requieren gestión integrada de flotas, equipos, sitios y personas.                                                                           | Empresas con necesidad de monitoreo de tanques en campo, almacenamiento a granel y subterráneos.                                                |
| Estrategias de marketing                          | Publicidad en redes sociales. <br><br> Colaboraciones con personas influyentes para promocionar el producto.                                                                                             | Publicidad mediante su página web.                                                                                                          | Publicidad mediante su página web.                                                                                                                                                  | Publicidad mediante su página web.                                                                                                              |
| **Perfil del Producto**                           |                                                                                                                                                                                                          |                                                                                                                                             |                                                                                                                                                                                     |                                                                                                                                                 |
| Productos & Servicios                             | Sensores para supervisar condiciones de materiales peligrosos y aplicaciones móvil y web para la gestión de perfiles de empresas y conductores.                                                          | Dispositivo Geotab GO, plataforma MyGeotab para monitoreo de flotas.                                                                        | Plataforma de Samsara, sensores, cámaras, integraciones con otros sistemas.                                                                                                         | Plataforma ATEK Intelligence y monitores de tanque inalámbricos.                                                                                |
| Precios & Costos                                  | Dependiente de los requisitos de la empresa que lo solicite.                                                                                                                                             | Dependiente de los requisitos de la empresa que lo solicite.                                                                                | Dependiente de los requisitos de la empresa que lo solicite.                                                                                                                        | Dependiente de los requisitos de la empresa que lo solicite.                                                                                    |
| Canales de distribución (Web y/o Móvil)           | Web/Móvil                                                                                                                                                                                                | Web/Móvil                                                                                                                                   | Web                                                                                                                                                                                 | Web/Móvil                                                                                                                                       |
| Tecnologías usadas                                | Plataforma Web (Angular y Spring Boot), App Móvil (Flutter) y Sensores IoT con análisis de datos en tiempo real.                                                                                         | Monitoreo en tiempo real, análisis de datos avanzados, conectividad IoT.                                                                    | IoT, AI, conectividad de sensores, análisis de datos en tiempo real.                                                                                                                | Monitoreo inalámbrico, sensores, conectividad celular o Ethernet.                                                                               |
| **Análisis SWOT**                                 |                                                                                                                                                                                                          |                                                                                                                                             |                                                                                                                                                                                     |                                                                                                                                                 |
| Fortalezas                                        | Seguridad en tiempo real para el transporte de materiales peligrosos y cumplimiento de regulaciones y estándares aplicables.                                                                             | Soluciones integradas de seguridad y eficiencia, experiencia en múltiples sectores.                                                         | Amplia escalabilidad y flexibilidad, integración con múltiples sistemas.                                                                                                            | Precisión en la lectura de niveles, facilidad de instalación y escalabilidad.                                                                   |
| Debilidades                                       | Necesidad de capacitación para conductores y empresas en el uso del sistema.                                                                                                                             | Dependencia de la instalación física del dispositivo.                                                                                       | Requiere inversión inicial significativa en tecnología.                                                                                                                             | Dependencia en la conectividad para la transmisión de datos.                                                                                    |
| Oportunidades                                     | Integración con sistemas de gestión logística para mejorar la eficiencia operativa.                                                                                                                      | Innovación en el monitoreo y análisis predictivo para nuevos sectores.                                                                      | Creciente demanda de soluciones integradas en operaciones complejas.                                                                                                                | Expansión en mercados con necesidades críticas de monitoreo remoto.                                                                             |
| Amenazas                                          | Competencia con tecnologías emergentes de detección de gases y monitoreo de seguridad.                                                                                                                   | Aparición de nuevas tecnologías de monitoreo con costos más bajos.                                                                          | Competencia de plataformas con enfoques más específicos o especializados.                                                                                                           | Competidores con tecnologías emergentes en monitoreo de líquidos.                                                                               |
<br>

<div style="text-align: center;"> <h4>Tabla: Matriz de análisis de competencia </h4> <img src="https://i.postimg.cc/CKPt3dsq/matriz-competencia.jpg" alt="Matriz de análisis de competencia" /> <p>Fuente: Elaboración propia.</p> </div>

<div style="text-align: center;"> <h4>Tabla: Matriz de perfil competitivo de los competidores directos </h4> <img src="https://i.postimg.cc/zv5TGGxz/matriz-perfil-competitivo.png" alt="Matriz de perfil competitivo de los competidores directos" /> <p>Fuente: Elaboración propia.</p> </div>

### 2.1.2. Estrategias y tácticas frente a competidores

1. **Diferenciación mediante Innovación Tecnológica:** Para destacar en el mercado de soluciones para el transporte de materiales peligrosos, es crucial ofrecer una propuesta de valor basada en tecnología avanzada. La estrategia de diferenciación se centra en implementar sensores IoT de última generación para monitorear condiciones críticas, como fugas de gas, temperatura y presión. Esta innovación no solo mejora la seguridad de los conductores y la integridad de la carga, sino que también optimiza la eficiencia operativa. 

2. **Enfoque en la Experiencia del Cliente:** La satisfacción del cliente es un factor clave para competir efectivamente. Implementar una estrategia de atención al cliente superior es esencial para retener clientes y atraer nuevos negocios. Esto incluye ofrecer una plataforma intuitiva para la gestión de sensores y alertas, soporte técnico receptivo y una interfaz de usuario optimizada para empresas y conductores. 

3. **Estrategias de Precio y Valor Agregado:** La competitividad en el mercado también puede lograrse mediante una estrategia de precios bien definida y valor agregado. Esto implica ofrecer precios competitivos para los sensores y servicios de monitoreo, así como paquetes flexibles que se adapten a las necesidades específicas de diferentes clientes, desde pequeñas empresas hasta grandes operadores. Además, proporcionar valor agregado, como informes detallados, análisis de datos y recomendaciones basadas en inteligencia artificial, puede diferenciar la oferta y justificar una inversión superior. 

<div style="text-align: center;"> <h4>Tabla: Matriz CAME. para el desarrollo de estrategias en base al análisis FODA. </h4> <img src="https://i.postimg.cc/1z527DwS/matriz-CAME.jpg" alt="Matriz CAME. para el desarrollo de estrategias en base al análisis FODA." /> <p>Fuente: Elaboración propia.</p> </div>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
**Segmento objetivo: Conductores**

**- Preguntas demográficas:**
- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
- ¿Dónde vives actualmente?
- ¿Qué rol desempeñas en la empresa en la que trabajas?

**- Preguntas principales:**
- ¿Cómo llegaste a trabajar en esa empresa?
- ¿Me podrías comentar a qué se dedica y cuál es su forma de trabajo de la empresa?
- ¿Qué desafíos enfrentas actualmente en términos de seguridad durante el transporte de materiales peligrosos?
- ¿Puedes describir alguna situación en la que te hayas sentido preocupado por la seguridad debido a la carga que transportas?
- ¿Cómo afectan las condiciones del entorno en el que trabajas (por ejemplo, temperatura, presión) la seguridad durante el transporte?
- ¿Qué problemas encuentras al monitorear las condiciones del vehículo mientras estás en movimiento?
- ¿Cuáles son los problemas más comunes que enfrentas  o fallos en el sistema de transporte?
- ¿Cómo sueles darte cuenta de un problema con la carga o el vehículo durante el transporte?
- ¿Cuál es tu proceso actual para manejar un problema relacionado con la carga mientras estás en ruta?
- ¿Cuáles crees que han sido tus principales habilidades para desempeñar el cargo de conductor?
- ¿Cuáles crees que han sido las marcas u otros empresas con las que han trabajado?
- ¿Qué medios digitales sules usar con frecuencias?
- En tu trabajo ¿cuáles son los dispositivos tecnológicos que suelen usar con frecuencia?


<br>

**Segmento objetivo: Supervisores**

**- Preguntas demográficas:**

- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
- ¿Dónde vives actualmente?
- ¿Qué rol desempeñas en la empresa en la que trabajas?

**- Preguntas principales:** 
- ¿Cómo llegaste a trabajar en esa empresa?
- ¿Me podrías comentar un poco a qué se dedica y cuál es su forma de trabajo de la empresa?
- ¿Qué medidas actuales tomas para asegurar la integridad de los materiales peligrosos durante el transporte?
- ¿Cuáles son los principales riesgos asociados con el transporte de materiales peligrosos que enfrentas en tu operación diaria?
- ¿Cómo supervisas y gestionas las condiciones de los vehículos que transportan materiales peligrosos?
- ¿Qué dificultades encuentras en el monitoreo de las condiciones del transporte y el estado de la carga?
- ¿Qué desafíos enfrentas para cumplir con las regulaciones y estándares de seguridad en el transporte de materiales peligrosos?
- ¿Cuál es el proceso actual para responder a incidentes de seguridad o problemas con la carga durante el transporte?
- ¿Qué tipo de soporte adicional consideras necesario para mejorar la respuesta a emergencias relacionadas con el transporte de materiales peligrosos?
- ¿Cuáles crees que han sido tus principales habilidades para desempeñar el cargo de supervisor?
- ¿Cuáles crees que han sido las marcas u otras empresas con las que han trabajado?
- ¿Qué medios digitales sules usar con frecuencias?
- En tu trabajo ¿cuáles son los dispositivos tecnológicos que suelen usar con frecuencia?


### 2.2.2. Registro de entrevistas

Entrevista 1: Segmento objetivo supervisores

Nombres y apellidos: Jorge Chero

Edad:  52 años

Cargo actual: Supervisor de Transportes en Convoy de materiales peligrosos

[![interview1.png](https://i.postimg.cc/9XT566xK/entrevista-empresa-1.png)](https://postimg.cc/Wt2HrHcw)

URL: https://upcedupe-my.sharepoint.com/personal/u20201c172_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201c172_upc_edu_pe%2FDocuments%2Fupc-pre-202402-si572-sw74-Debuggers-needfinding-interviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6ed7c1cd-8118-4016-baf7-6b5e58e1d318

Timing: 0:08

Duración: 8:04 minutos 

**Resúmen de la entrevista:**

Jorge es supervisor de transportes en una empresa que se dedica al traslado de materiales peligrosos, principalmente hidrocarburos, a compañías mineras. Él menciona la importancia de contar con unidades adecuadas para el transporte y personal capacitado. Se asegura de que todo el personal tenga la documentación en regla y que los conductores descansen al menos 7 horas continuas antes de iniciar su turno. Las principales dificultades que enfrenta están relacionadas con las malas condiciones de las carreteras, el clima y otros conductores que no siguen las mismas normas de seguridad.

Jorge implementa un estricto control de las condiciones de los vehículos mediante checklists y la instalación de cámaras de seguridad que monitorizan tanto la carretera como el estado de los conductores. Una de las mayores dificultades en el monitoreo es la falta de señal GPS en zonas montañosas o desérticas, lo que complica el seguimiento en tiempo real. Considera que los mayores desafíos son cumplir con las regulaciones de las empresas y las capacitaciones constantes, esenciales para mantener al personal actualizado sobre los protocolos de seguridad.

En caso de emergencias, Jorge sigue un plan de contingencia bien definido, asegurándose de que todo el personal esté preparado para responder a derrames o incidentes. Propone mejorar la respuesta a emergencias mediante simulacros constantes y la implementación de tecnologías que ayuden a detectar problemas en las primeras etapas del transporte.

Por otro lado, Jorge posee las habilidades como manejo defensivo, conocimiento profundo de rutas y condiciones climáticas, y capacidad de mantener la calma en situaciones de alto riesgo, ya que son esenciales para el transporte seguro de materiales peligrosos. También destacaría la importancia de la experiencia en la supervisión de convoyes y gestión de equipos de trabajo. Adicionalmente, Jorge podría haber trabajado con empresas mineras y compañías de transporte de hidrocarburos, y que podrían ser marcas reconocidas dentro del sector minero y de energía.

También, en cuanto a los medios digitales es probable que Jorge utilice sistemas de monitoreo GPS, así como cámaras de seguridad instaladas en los vehículos. También menciona el uso de aplicaciones para seguimiento de alcoholemia y el software de monitoreo que emplea su empresa para verificar las rutas. Además, Jorge mencionó el uso de cámaras de seguridad para monitorear los convoyes, así como dispositivos de monitoreo GPS. También es probable que utilice teléfonos móviles (aunque él especificó que los conductores no pueden usarlos mientras manejan), y kits de emergencia que incluyen tecnología para controlar derrames.

<br><br>

Entrevista 2: Segmento objetivo Supervisores

Nombres y apellidos: Arquímedes Ordoño Gutiérrez

Edad:  55 años

Cargo actual: Jefe de Supervisores en Transcor SRL

[![interview1.png](https://i.postimg.cc/9Fh5CLKM/entrevista-empresa-2.png)](https://postimg.cc/Z0VDLxTt)

URL: https://upcedupe-my.sharepoint.com/personal/u20201c172_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201c172_upc_edu_pe%2FDocuments%2Fupc-pre-202402-si572-sw74-Debuggers-needfinding-interviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6ed7c1cd-8118-4016-baf7-6b5e58e1d318

Timing: 8:11

Duración: 25:11 minutos 

**Resúmen de la entrevista:**

Arquímedes es jefe de supervisores en Transcor SRL, una empresa dedicada al transporte terrestre de combustibles. Uno de los puntos clave en su enfoque es la preparación del conductor, ya que considera que sin un conductor bien capacitado y descansado, no importa cuán moderna o segura sea la unidad de transporte. El uso de tecnología avanzada como pulseras que monitorizan las horas de sueño y sensores en los camiones para detectar fatiga son fundamentales en su operación diaria.

Entre los principales riesgos que enfrenta están el tráfico y las condiciones geográficas adversas, especialmente en rutas de montaña. Para mitigarlos, su empresa realiza capacitaciones regulares sobre manejo defensivo y seguridad vial. Además, utilizan teléfonos satelitales para comunicarse en zonas sin señal y mantener un control constante del convoy.

Uno de los principales desafíos que identifica Arquímedes es la burocracia en la obtención de permisos para el transporte de materiales peligrosos, lo cual a veces retrasa las operaciones. Además, destaca la importancia de realizar simulacros en coordinación con las minas para estar preparados ante cualquier emergencia. Arquímedes propone reducir las distancias entre las unidades de apoyo vial para mejorar la respuesta en caso de incidentes.

Por otro lado, Arquímedes destaca habilidades como conocimiento técnico de los vehículos modernos, especialmente los sistemas avanzados de seguridad, y la capacidad de liderazgo y supervisión, ya que está a cargo de equipos de conductores. También haría hincapié en la importancia de la capacidad de tomar decisiones rápidas en situaciones difíciles. Además, él probablemente ha trabajado con marcas de vehículos como Volvo, ya que menciona que sus conductores reciben capacitación específica de esta marca. Además, ha trabajado con empresas que requieren transporte de combustibles, posiblemente empresas del sector energético y minero.

Finalmente, Arquímedes mencionó utiliza sistemas como teléfonos satelitales y software de geocercas para el monitoreo constante de las unidades. También hace uso de sensores de fatiga y tecnologías integradas en los vehículos para detectar problemas y el entrevistado mencionó el uso de teléfonos satelitales, sensores de fatiga, cámaras de seguridad y sistemas de monitoreo GPS. Además, habló sobre kits antiderrame con tecnología avanzada y otros dispositivos relacionados con la seguridad de los conductores y los materiales peligrosos.

<br><br>

Entrevista 3: Segmento objetivo supervisores

Nombres y apellidos: Estuardo Chero

Edad:  46 años

Cargo actual: Supervisor Escolta de Materiales Peligrosos

[![interview1.png](https://i.postimg.cc/MGFJwqJ2/entrevista-empresa-3.png)](https://postimg.cc/Ff3BgtKD)

URL: https://upcedupe-my.sharepoint.com/personal/u20201c172_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201c172_upc_edu_pe%2FDocuments%2Fupc-pre-202402-si572-sw74-Debuggers-needfinding-interviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6ed7c1cd-8118-4016-baf7-6b5e58e1d318

Timing: 33:21

Duración: 16:04 minutos 

**Resúmen de la entrevista:**

Estuardo trabaja como supervisor escolta de materiales peligrosos, con un enfoque en el transporte seguro de concentrado de cobre. Antes de cada operación, se asegura de que tanto los vehículos como los conductores estén en condiciones óptimas. Realiza charlas de seguridad de 5 minutos con los conductores antes de cada jornada para asegurarse de que estén listos tanto física como mentalmente.

El principal riesgo que enfrenta es el de accidentes de tránsito, ya que muchas veces otros conductores no cumplen con las normativas de seguridad. El transporte del concentrado de cobre se realiza en tolvas, las cuales tienen ciertas medidas de seguridad, aunque no están completamente herméticas. Las dificultades en el monitoreo de la carga son mínimas, ya que las tolvas están cerradas, pero la preocupación principal es garantizar que no haya incidentes durante el trayecto.

En cuanto al cumplimiento de regulaciones, Estuardo destaca que su empresa cumple estrictamente con los estándares de seguridad y que la actitud de los conductores es clave para mantener ese nivel de cumplimiento. En caso de un incidente, siguen un plan de contingencia que incluye el uso de radios para reportar y coordinar con agentes viales que supervisan el convoy. Estuardo sugiere que, para mejorar la respuesta a emergencias, sería útil reducir la distancia entre las unidades de apoyo vial y mejorar los sistemas de monitoreo automáticos de los camiones.

Por otro lado, Estuardo destaca su habilidad para supervisar y gestionar convoyes, así como su conocimiento en cumplimiento de normativas de seguridad. También podría hablar de su capacidad para reaccionar ante emergencias y su atención al detalle en el control de los vehículos y la carga. Adicionalmente, él mencionó trabajar en Noat Logistics Perú, una empresa que realiza transporte para mineras. Es probable que haya trabajado con otras marcas y empresas en el sector de transporte de carga pesada y materiales peligrosos.

En adición, el entrevistado mencionó el uso de radios base para la comunicación constante con su equipo y con los agentes viales. También utiliza sistemas de monitoreo y software para la gestión de contingencias, como el plan de contingencias que debe seguir en caso de incidentes y los radios base, sistemas de monitoreo GPS, y las camionetas de soporte que monitorean el convoy. Se mencionó el uso de sensores en los vehículos para verificar fallas mecánicas, lo que sugiere que está familiarizado con la tecnología avanzada integrada en los camiones.

<br><br>

Entrevista 4: Segmento objetivo conductores

Nombres y apellidos: José Gonzales 

Edad:  27 años

Cargo actual: Conductor de Cisternas

[![interview1.png](https://i.postimg.cc/5t8S9PQL/entrevista-conductor-2.png)](https://postimg.cc/bGNt39Tw)

URL: https://upcedupe-my.sharepoint.com/personal/u20201c172_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201c172_upc_edu_pe%2FDocuments%2Fupc-pre-202402-si572-sw74-Debuggers-needfinding-interviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6ed7c1cd-8118-4016-baf7-6b5e58e1d318

Timing: 1:00:47

Duración: 6:25 minutos 

**Resúmen de la entrevista:**

José Daniel trabaja como conductor de cisternas para una empresa que transporta materiales peligrosos. En su trabajo, se enfrenta a desafíos relacionados con la seguridad, especialmente en asegurar que la carga esté bien sujeta y que el vehículo esté en óptimas condiciones. Las carreteras en mal estado y la neblina densa en las noches son fuentes de gran preocupación, ya que aumentan el riesgo de accidentes. Menciona que las condiciones climáticas extremas, como el calor intenso en verano o las lluvias en invierno, también representan un riesgo significativo, ya que pueden afectar la presión interna de los tanques o las condiciones del asfalto.

José cuenta con sistemas de alerta en su vehículo, pero reconoce que no siempre funcionan de manera eficiente, lo que puede retrasar la detección de problemas. Los fallos más comunes que enfrenta incluyen problemas con las válvulas, los frenos, o la estabilidad de la carga. En caso de detectar un problema, su proceso consiste en detenerse en un lugar seguro, revisar el vehículo, y en casos graves, contactar con su base para recibir asistencia técnica.

Por otro lado, José destacaría por su atención al detalle en la seguridad del vehículo y la carga, así como su capacidad para mantener la calma bajo condiciones climáticas adversas. Además, tiene experiencia en la detección temprana de fallos en el vehículo y la carga. También, él mencionó el transporte de gases y materiales peligrosos, lo que sugiere que ha trabajado para empresas de transporte de hidrocarburos o químicos, aunque no mencionó marcas específicas.

En adición, es probable que José use sistemas de monitoreo de alertas en el vehículo, así como sistemas de comunicación con su base para gestionar emergencias. Y él Mencionó sistemas de alerta en el vehículo, así como herramientas de diagnóstico para revisar el estado de las válvulas y frenos.

<br><br>

Entrevista 5: Segmento objetivo 

Nombres y apellidos: Juan Cueto Dominguez

Edad: 28 años

Cargo actual: Conductor de camiones de transporte de Materiales Peligrosos

[![interview1.png](https://i.postimg.cc/nzZYXvq5/entrevista-conductor-1.png)](https://postimg.cc/kV1tZR1F)

URL: https://upcedupe-my.sharepoint.com/personal/u20201c172_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201c172_upc_edu_pe%2FDocuments%2Fupc-pre-202402-si572-sw74-Debuggers-needfinding-interviews%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6ed7c1cd-8118-4016-baf7-6b5e58e1d318

Timing: 50:23

Duración: 10:26 minutos 

**Resúmen de la entrevista:**

Juan trabaja como conductor especializado en el transporte de materiales peligrosos y enfrenta desafíos constantes relacionados con la seguridad. Uno de sus principales retos es asegurarse de que tanto la carga como el vehículo cumplan con las normativas de seguridad, especialmente cuando se trata de sustancias inflamables o explosivas. Destaca que sigue estrictamente las regulaciones internacionales y locales, y que las condiciones ambientales, como el calor o el viento, pueden alterar la estabilidad de los materiales peligrosos.

Una experiencia que lo marcó fue transportar gases inflamables bajo temperaturas extremas, lo que lo llevó a tomar medidas inmediatas para garantizar su seguridad y la del entorno. En cuanto al monitoreo del vehículo, Juan confía en sistemas de alerta y monitoreo visual, aunque reconoce que el ruido de la carretera y las vibraciones del vehículo pueden afectar la capacidad para detectar problemas a tiempo. Los fallos más comunes que enfrenta incluyen problemas con los sistemas de sujeción de la carga, los frenos, y los sistemas de enfriamiento. Cuando se presenta un problema, sigue un estricto protocolo de seguridad, deteniéndose en áreas seguras y notificando a los equipos de emergencia.

Por otro lado, Juan destaca su conocimiento profundo de las normativas internacionales de seguridad, como el CFR 49 de Estados Unidos, así como su capacidad para tomar decisiones rápidas en situaciones de riesgo. También, es probable que Juan haya trabajado para empresas de transporte de gases inflamables y explosivos que requieren un alto nivel de cumplimiento normativo.

<br><br>

### 2.2.3. Análisis de entrevistas

- Las medidas de seguridad son una preocupación central para todos los entrevistados. Además, los riesgos relacionados con las condiciones externas son una preocupación común y el cumplimiento de normas es una obligación crítica en todas las empresas entrevistadas.

[![interview1.png](https://i.postimg.cc/x1Wp0CF2/gr-fico1-temas-clave.png)](https://postimg.cc/DSPP62Tj)

- Todos los entrevistados consideran los accidentes de tránsito como el principal riesgo. La pérdida de señal GPS en zonas remotas es un desafío significativo mencionado en 2 de las 3 entrevistas. Además, la mayoría de las empresas exige un mínimo de 7 horas de descanso para los conductores y la capacitación de los conductores se realiza dos veces al año como mínimo.

[![interview1.png](https://i.postimg.cc/JhZ6tL9B/gr-fico2-percepciones.png)](https://postimg.cc/McZbrhZW)

- Las empresas implementan múltiples tecnologías para garantizar la seguridad en el transporte. Todas las empresas utilizan teléfonos satelitales en zonas donde la cobertura de señal es deficiente. Además, los entrevistados perciben que el proceso burocrático es un desafío considerable. También, las empresas realizan simulacros de emergencia al menos 3 veces al año y se sugiere incrementar las unidades de respuesta para reducir tiempos de llegada en emergencias.

[![interview1.png](https://i.postimg.cc/t41mQPkk/gr-fico3-tecnolog-a-normas-simulacros.png)](https://postimg.cc/DSTc1St4)

<br><br>

## 2.3. Needfinding

En la fase de NeedFinding, el equipo se ha centrado en analizar la información recolectada a través de entrevistas diseñadas previamente, realizadas con Supervisores de Transportes de Materiales Peligrosos y Conductores de Camiones que transportan materiales como gases inflamables, tóxicos y explosivos. Estas entrevistas, realizadas en plataformas digitales como Google Meet, han permitido una interacción directa con los segmentos objetivos, ofreciendo una valiosa oportunidad para profundizar en sus necesidades, desafíos y expectativas.

Los artefactos resultantes de este análisis incluyen herramientas clave como el User Task Matrix, User Journey Maps, Empathy Mapping y As-Is Scenario Mapping, todos enfocados en identificar patrones, comportamientos y necesidades ocultas dentro de los roles específicos de cada grupo objetivo. Este proceso nos ha permitido estructurar información crítica para guiar el diseño y solución del problema identificado.

### 2.3.1. User Personas

En la sección de User Personas, presentamos fichas detalladas que representan los perfiles de los segmentos objetivos: Supervisores de Transportes de Materiales Peligrosos y Conductores de Camiones. Estas fichas son el resultado del análisis de las entrevistas, donde se ha extraído información clave para crear arquetipos que reflejen sus características, motivaciones, frustraciones y necesidades.

Cada ficha de User Persona incluye datos esenciales que fueron recopilados durante el proceso de entrevistas, integrando las mejores prácticas en cuanto a especificación de arquetipos. Estas fichas nos permitirán profundizar en la comprensión del usuario final y orientar las próximas fases del proyecto.

- **Segmento objetivo supervisores: Arquetipo del supervisor**

El User Persona de Supervisores de Transportes de Materiales Peligrosos se enfoca en los roles, responsabilidades y desafíos que enfrentan estos profesionales a la hora de gestionar el transporte de materiales como gases inflamables, tóxicos y explosivos. A través de las entrevistas realizadas, hemos identificado las características principales de estos supervisores, quienes suelen lidiar con altos niveles de responsabilidad, asegurando que las normativas de seguridad sean cumplidas estrictamente y que la cadena de transporte opere sin contratiempos.

[![interview1.png](https://i.postimg.cc/P5CKLmkj/User-Persona-Supervisor-Update.png)](https://postimg.cc/3kH2V0RS)

- **Segmento objetivo conductores: Arquetipo del conductor**

El User Persona de Conductores de Camiones de Materiales Peligrosos nos permite entender a aquellos que están directamente a cargo del transporte de materiales altamente peligrosos en la carretera. A través de las entrevistas realizadas, hemos descubierto que estos conductores deben cumplir con estrictas normativas y enfrentan situaciones de alta presión, como condiciones climáticas adversas y riesgos constantes durante el trayecto. La creación de este perfil es esencial para diseñar soluciones que se alineen con sus necesidades diarias y sus experiencias en ruta.

[![interview1.png](https://i.postimg.cc/k58csq4Y/User-Persona-Conductores-Update.png)](https://postimg.cc/HJYXsGbb)

<br><br>

### 2.3.2. User Task Matrix

En esta sección se presenta el User Task Matrix, que presenta las tareas esenciales que los User Persona, Juan Navarro para el segmento de supervisores y Miguel Herrera para el segmento de conductores, deben realizar para alcanzar sus objetivos. La matriz incluye columnas para cada User Persona, con sub-columnas que reflejan la frecuencia y la importancia de cada tarea. Las filas enumeran las tareas identificadas, y posteriormente se ofrecerá un análisis de las tareas más relevantes, destacando diferencias y similitudes entre ambos segmentos.

[![interview1.png](https://i.postimg.cc/KYxSZQR0/User-Task-Matrix-Update.png)](https://postimg.cc/nXRw24Km)

La mayoría de tareas tiene una frecuencia e importancia alta, ya que al tratarse y trabajar con materiales peligrosos de alto riesgo cada tarea es crítica, de estas tareas depende la seguridad y la vida de los conductores y la reputación de la empresa que supervisa este tipo de trabajos.

**Tareas más frecuentes e importantes:** Tanto para Juan Navarro como Miguel Herrera se ve la importancia de inspeccionar las condiciones del vehículo, supervisar el aseguramiento de la carga y gestionar el cumplimiento de normativas. Estas actividades son esenciales para ambos, ya que contribuyen directamente a la seguridad del transporte de materiales peligrosos.

**Principales diferencias:** Los supervisores como Juan Navarro están más enfocados en monitorear el estado del conductor y realizar informes de seguridad, que son cruciales en su rol de supervisión. Para los conductores como Miguel Herrera, estas tareas son menos frecuentes o de menor importancia, ya que su enfoque principal está en el monitoreo de los sistemas de alerta y reaccionar ante incidentes.

**Coincidencias:** Ambos coinciden en la importancia de mantener la comunicación con la base y tomar decisiones en situaciones de emergencia. Estas actividades, aunque realizadas con diferente frecuencia, son críticas para la seguridad del transporte y la gestión de incidentes en ruta.

### 2.3.3. User Journey Mapping

En esta sección, se presentan los User Journey Maps para cada User Persona, Juan Navarro y Miguel Herrera. Estos mapas va a presentar el recorrido actual de los usuarios, reflejando sus interacciones y experiencias sin la intervención de una solución tecnológica. A través de diagramas elaborados en la herramienta indicada de UXPressia, se destacan las etapas clave del journey de cada segmento, permitiendo una comprensión más profunda de sus necesidades y desafíos en la situación actual.

- **Segmento objetivo supervisores: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/fyPK4Www/Customer-Journey-Map-Empresas-new.png)](https://postimg.cc/YL1gYHGV)

- **Segmento objetivo conductores: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/CMG4kM7D/Customer-Journey-Map-Conductores-new.png)](https://postimg.cc/8sCWVSqP)

### 2.3.4. Empathy Mapping

En esta sección, se detalla el proceso de creación de los Empathy Maps para cada User Persona. Estos mapas ayudan a entender las emociones y pensamientos de los usuarios, abordando preguntas fundamentales sobre lo que piensan, sienten y experimentan en su contexto. Con capturas de los Empathy Maps elaborados, se busca responder a interrogantes sobre las necesidades, preocupaciones y motivaciones de Juan Navarro (segmento supervisor) y Miguel Herrera (segmento conductor), identificando así sus Pains y Gains para guiar el desarrollo de soluciones efectivas.

- **Segmento objetivo supervisores: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/sXD9vGxj/Empathy-Map-Empresas-new.png)](https://postimg.cc/mcJFnD7J)

- **Segmento objetivo conductores: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/pXPJZNcS/Empathy-Map-Conductores-new.png)](https://postimg.cc/4nFcf0gv)

### 2.3.5. As-is Scenario Mapping

Esta sección introduce el As-Is Scenario Mapping, que resume el proceso realizado por el equipo para cada User Persona. A través de un diagrama que incluye las fases de acción, pensamiento y sentimiento, se analizan las experiencias actuales de los usuarios. El proceso implica la identificación de áreas positivas y negativas, así como la señalización de blank areas que requieren más investigación, lo que proporciona una visión clara de cómo mejorar las experiencias de Juan Navarro (segmento supervisor) y Miguel Herrera (segmento conductor) en su entorno actual.

- **Mapa As-Is: Segmento objetivo antes de conocer la solución de software:**

[![interview1.png](https://i.postimg.cc/0yCXLHWq/Mapa-As-Is-Empresas.png)](https://postimg.cc/3kdZG9QL)

## 2.4. Ubiquitous Language

En esta sección se presenta el glosario de términos y conceptos relevantes al business domain, conocido como Ubiquitous Language. Este glosario es esencial para mantener una comunicación clara y precisa entre todos los miembros del equipo y los stakeholders. Incluye definiciones de términos específicos del área de especialidad, evitando ambigüedades y garantizando que todos compartan un entendimiento común del lenguaje utilizado en el contexto del problema y la solución. Las definiciones se presentan en español, mientras que los términos están en inglés, facilitando así una referencia accesible para todos.

- **Itinerary (Itinerario):**  Ruta planificada para el transporte de materiales peligrosos, incluyendo puntos de carga y descarga.
- **Manifest (Manifiesto):**  Documento que detalla la carga transportada, asegurando que todos los materiales peligrosos estén correctamente identificados y documentados.
- **Safety Conditions (Condiciones de seguridad):** Conjunto de normas y regulaciones que deben cumplirse para garantizar un transporte seguro de materiales peligrosos.
- **Quality Indicators (Indicadores de calidad):**  Métricas que evalúan la efectividad y seguridad de un medio de transporte, como el estado del vehículo, el cumplimiento de normativas y la capacitación del personal.

- **Hazardous Materials (Materiales Peligrosos):** Materiales que, debido a su naturaleza química, física o biológica, pueden causar daños a las personas, bienes o el medio ambiente durante el transporte o almacenamiento.

- **Gas Leak (Fuga de Gas):** Escape no controlado de gas de un contenedor, lo que puede representar un riesgo de explosión o intoxicación.

- **Transportation Incident (Incidente de Transporte):** Evento inesperado que ocurre durante el transporte, como accidentes, fugas o cambios en las condiciones ambientales, que puede afectar la seguridad del conductor o los materiales.

- **Safety Procedures (Procedimientos de Seguridad):** Conjunto de acciones o medidas establecidas para minimizar los riesgos durante el transporte de materiales peligrosos, incluyendo el uso adecuado de sensores y notificaciones en tiempo real.

- **Transportation Request (Solicitud de Transporte):** Petición formal de una empresa para transportar materiales peligrosos, detallando las rutas, condiciones, y asignación de conductores y vehículos.

- **Incident Report (Reporte de Incidente):** Documento generado que detalla un incidente ocurrido durante el transporte de materiales peligrosos, incluyendo detalles como el tipo de incidente, la respuesta y las acciones tomadas.

- **Real-time Monitoring (Monitoreo en tiempo real):** Supervisión continua de las condiciones del transporte, incluyendo la ubicación y el estado de la carga.
- **Driver Training (Capacitación del conductor):** Formación específica que garantiza que los conductores estén preparados para manejar materiales peligrosos y responder a situaciones de emergencia.
- **Contingency Plan (Plan de contingencia):** Estrategia definida para abordar emergencias durante el transporte, incluyendo procedimientos en caso de derrames o accidentes.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping:

A continuación, se mostrará los To-Be Scenario Mapping realizados para los segmentos objetivos considerados, Conductor y Supervisor. En los diagramas es ofrece una representación detallada del estado futuro que se desea para cada proceso que realizan segmentos. Además, se evidencian las mejoras al emplear la aplicación **FastPorte** en comparación con el estado actual presentado en los As-Is Scenario Mapping.

**To-Be Scenario Mapping - Usuario Conductor:**
![To Be Scenario Mapping del usuario Conductor](assets/capitulo3/to-be-scenario-mapping/driver.jpg)
**To-Be Scenario Mapping - Usuario Supervisor:**
![To Be Scenario Mapping del usuario Empresa](assets/capitulo3/to-be-scenario-mapping/company.jpg)
Enlace para mejor visualización en Miro: [To Be Scenario Mapping FastPorte](https://miro.com/app/board/uXjVKlAIMgY=/?share_link_id=669866924097)
## 3.2. User Stories

Se han descrito las funcionalidades y características de la propuesta de solución desde la perspectiva de los usuarios finales considerados, Conductor y Supervisor. Previamente a la elaboración de las Historias de Usuario se han designado las categorías en las que formarán parte, siendo estas las siguientes Épicas:

| Epic ID | Título                                                           | Descripción                                                                                                                                                                                                                                                 |
| ------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EP-01   | Creación de una página de aterrizaje para captar nuevos usuarios | Se centra en el desarrollo del sitio web que sirve de presentación para la empresa y el producto que ofrece. Se implementan diversas secciones que permiten al usuario conocer más acerca de FastPorte y como el producto puede satisfacer sus necesidades. |
| EP-02   | Sistema para el manejo de información y funcionalidad            | Se enfoca en el desarrollo backend de la aplicación y las funcionalidades que debe poseer. Asimismo, como serán denominados los *endpoints* para su futura implementación en las aplicaciones web y móvil.                                                  |
| EP-03   | Conexión con el sensor integrado                                 | La integración del sensor instalado en el vehículo con el backend para almacenar la información que reporta y como se visualizará en el frontend.                                                                                                           |
| EP-04   | Autenticación y Registro de usuarios                             | Abarca los aspectos iniciales del uso de la aplicación web y móvil. Los pasos de Registro e Inicio Sesión de los usuarios en la aplicación.                                                                                                                 |
| EP-05   | Servicios de viajes y gestión de itinerario                      | Engloba las funcionalidades que brindan tanto la aplicación móvil como web respecto a los viajes programados para los conductores de material peligroso.                                                                                                    |
| EP-06   | Sistema de notificaciones y alertas                              | La gestión de las notificaciones y alertas recibidas por los servicios de transporte brindados o en caso de advertencia por la detección de un inconveniente por parte del sensor.                                                                          |
| EP-07   | Monitorización y Gestión del material peligroso                  | Las funcionalidades del sensor para captar y enviar la información detectada acerca de los materiales peligrosos.                                                                                                                                           |

A continuación, las Historias de Usuario relacionadas para definir los requisitos del sistema incluyendo los criterios de aceptación:

| User Story ID | Título                                                                            | Descripción                                                                                                                                                                                                              | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Epic ID |
| ------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| US-001        | Registro de supervisor de la empresa                                              | **Como** supervisor de la empresa<br>**Quiero** registrarme en la aplicación<br>**Para** supervisar a los conductores a mi cargo                                                                                         | **Escenario Nº1: Código correcto**<br><br>**Dado que** el supervisor de la empresa no está registrado<br>**Y** está en la vista inicial de la aplicación<br>**Cuando** ingresa el código del sensor de un vehículo<br>**Y** selecciona la opción de registrarse como "Supervisor"<br>**Y** completa los datos requeridos correctamente<br>**Entonces** el sistema registra el usuario como *Supervisor*<br>**Y** permite al usuario iniciar sesión con las credenciales creadas<br><br>**Escenario Nº2: Código usado anteriormente**<br><br>**Dado que** el supervisor de la empresa no está registrado<br>**Y** está en la vista inicial de la aplicación<br>**Y** se ha usado el código del sensor anteriormente para registrar un *Supervisor*<br>**Cuando** ingresa el código del sensor de un vehículo<br>**Y** selecciona la opción de registrarse como "Supervisor"<br>**Y** completa los datos requeridos correctamente<br>**Entonces** el sistema le indica que ya se ha registrado un *Supervisor* para el código ingresado                                                                                               | EP-04   |
| US-002        | Registro de conductor                                                             | **Como** conductor<br>**Quiero** registrarme en la aplicación<br>**Para** recibir información de los viajes que debo realizar                                                                                            | **Escenario Nº1: Código correcto**<br><br>**Dado que** el conductor no está registrado<br>**Y** se encuentra en la vista inicial de la aplicación<br>**Cuando** ingresa el código del sensor de su vehículo<br>**Y** selecciona la opción de registrarse como "Conductor"<br>**Y** completa los datos requeridos correctamente<br>**Entonces** el sistema registra el usuario como *Conductor*<br>**Y** permite al usuario iniciar sesión con las credenciales creadas<br><br>**Escenario Nº2: Código usado anteriormente**<br><br>**Dado que** el conductor no está registrado<br>**Y** está en la vista inicial de la aplicación<br>**Y** se ha usado el código del sensor anteriormente para registrar un *Conductor*<br>**Cuando** ingresa el código del sensor de un vehículo<br>**Y** selecciona la opción de registrarse como "Conductor"<br>**Y** completa los datos requeridos correctamente<br>**Entonces** el sistema le indica que ya se ha registrado un *Conductor* para el código ingresado                                                                                                                          | EP-04   |
| US-003        | Inicio de sesión                                                                  | **Como** usuario de la aplicación<br>**Quiero** iniciar sesión en la aplicación<br>**Para** acceder a las funcionalidades de la aplicación                                                                               | **Escenario Nº1: Credenciales correctas**<br><br>**Dado que** el usuario de la aplicación desea iniciar sesión<br>**Y** está en la vista inicial de la aplicación<br>**Cuando** ingresa sus credenciales<br>**Entonces** el sistema permite al usuario acceder a las funcionalidades de la aplicación<br><br>**Escenario Nº2: Credenciales inccorrectas**<br><br>**Dado que** el usuario de la aplicación desea iniciar sesión<br>**Y** está en la vista inicial de la aplicación<br>**Cuando** ingresa sus credenciales<br>**Y** se ha equivocado en su correo o contraseña<br>**Entonces** el sistema le indica que una de sus credenciales es incorrecta                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP-04   |
| US-004        | Registrar un viaje                                                                | **Como** supervisor de la empresa<br>**Quiero** registrar un viaje<br>**Para** notificar al conductor los servicios que debe realizar                                                                                    | **Escenario Nº1: Viaje creado**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea registrar un viaje en el itinerario<br>**Cuando** selecciona al conductor que realizará la entrega<br>**Y** completa la información del viaje correctamente<br>**Entonces** el sistema crea el viaje<br>**Y** notifica al conductor sobre el viaje que debe realizar<br><br>**Escenario Nº2: Conflicto de horario**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea registrar un viaje en el itinerario<br>**Cuando** selecciona al conductor que realizará la entrega<br>**Y** completa la información del viaje correctamente<br>**Y** el horario elegido ya ha sido reservado para otro viaje<br>**Entonces** el sistema indica que se debe de elegir otro horario para el servicio de transporte                                                                                                                                                                                                                                          | EP-05   |
| US-005        | Viajes pendientes                                                                 | **Como** usuario de la aplicación<br>**Quiero** visualizar los viajes pendientes<br>**Para** gestionar los viajes que se deben realizar                                                                                  | **Escenario Nº1: Viajes pendientes existentes**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación <br>**Y** desea visualizar los viajes pendientes<br>**Cuando** selecciona la opción para ver el itinerario<br>**Entonces** el sistema muestra los viajes pendientes<br><br>**Escenario Nº2: Sin viajes pendientes**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación <br>**Y** desea visualizar los viajes pendientes<br>**Cuando** selecciona la opción para ver el itinerario<br>**Y** no posee ningún viaje agendado<br>**Entonces** el sistema muestra un mensaje indicando que no hay viajes pendientes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | EP-05   |
| US-006        | Historial de Viajes                                                               | **Como** usuario de la aplicación<br>**Quiero** visualizar el historial de viajes<br>**Para** llevar un registro de los viajes completados                                                                               | **Escenario Nº1: Viajes completados existentes**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación<br>**Y** desea visualizar el historial de viajes<br>**Cuando** selecciona la opción para ver el historial de viajes<br>**Entonces** el sistema muestra los viajes completados en el historial<br><br>**Escenario Nº2: Sin viajes completados**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación <br>**Y** desea visualizar los viajes pendientes<br>**Cuando** selecciona la opción para ver el historial de viajes<br>**Y** no posee ningún viaje completado<br>**Entonces** el sistema muestra un mensaje indicando que no hay viajes en el historial                                                                                                                                                                                                                                                                                                                                                                                                                                       | EP-05   |
| US-007        | Concluir viaje                                                                    | **Como** supervisor de la empresa<br>**Quiero** concluir los viajes que ya se han realizado<br>**Para** dar por terminado la tarea del conductor                                                                         | **Escenario Nº1: Viaje finalizado**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea concluir un viaje<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** marca el viaje como concluido<br>**Entonces** el sistema registra el viaje como completado<br>**Y** notifica al conductor sobre la finalización del viaje<br><br>**Escenario Nº2: Irregularidades detectadas**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea concluir un viaje<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** marca el viaje como concluido<br>**Y** el sensor todavía está detectando irregularidades<br>**Entonces** el sistema muestra un mensaje indicando que el viaje no puede ser finalizado                                                                                                                                                                                                                                                                                | EP-05   |
| US-008        | Cancelar viaje                                                                    | **Como** supervisor de la empresa<br>**Quiero** cancelar un viaje<br>**Para** descartar un viaje creado erróneamente                                                                                                     | **Escenario Nº1: Viaje cancelado**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea cancelar un viaje<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** cancela el viaje<br>**Entonces** el sistema elimina el registro del viaje<br>**Y** notifica al conductor sobre el viaje cancelado<br><br>**Escenario Nº2: Viaje en curso**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea cancelar un viaje<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** cancela el viaje<br>**Y** el viaje ya se encuentra en curso<br>**Entonces** el sistema muestra un mensaje indicando que el viaje ya se encuentra en curso<br>**Y** muestra la opción para contactar con el conductor<br>**Y** con el área de soporte                                                                                                                                                                                                                                                      | EP-05   |
| US-009        | Buscar un conductor                                                               | **Como** supervisor de la empresa<br>**Quiero** buscar un conductor<br>**Para** asignarle un viaje                                                                                                                       | **Escenario Nº1: Búsqueda de conductor existente**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea buscar un conductor<br>**Cuando** ingresa el nombre del conductor o el código del sensor de su vehículo<br>**Y** confirma la búsqueda<br>**Entonces** el sistema busca y muestra al conductor correspondiente<br><br>**Escenario Nº2: Búsqueda de conductor inexistente**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea buscar un conductor<br>**Cuando** ingresa el nombre del conductor o el código del sensor de su vehículo<br>**Y** ingresa un carácter incorrectamente<br>**Y** confirma la búsqueda<br>**Entonces** el sistema muestra un mensaje indicando que no se ha encontrado ningún conductor que coincida con los datos ingresados                                                                                                                                                                                                                                                                        | EP-05   |
| US-010        | Visualizar la información del viaje                                               | **Como** usuario de la aplicación<br>**Quiero** visualizar la información de un viaje<br>**Para** revisar algún dato en concreto                                                                                         | **Escenario Nº1: Visualizar información de un viaje pendiente**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación<br>**Y** desea visualizar la información de un viaje<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** selecciona el viaje correspondiente<br>**Entonces** el sistema muestra la información del viaje<br><br>**Escenario Nº2: Visualizar información de un viaje realizado**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación<br>**Y** desea visualizar la información de un viaje<br>**Cuando** selecciona la opción de ver el historial de viajes<br>**Y** elige el viaje correspondiente en la lista de viajes completados<br>**Entonces** el sistema muestra la información del viaje realizado                                                                                                                                                                                                                                                                                                                                            | EP-05   |
| US-011        | Notificar al conductor del nuevo viaje                                            | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si se me ha asignado un viaje                                                                                                                | **Escenario Nº1: Notificación de un nuevo viaje en la sección Principal**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir una notificación de un nuevo viaje<br>**Cuando** ingresa a la aplicación<br>**Entonces** el sistema muestra una notificación del nuevo viaje asignado<br><br>**Escenario Nº2: Notificación de un nuevo viaje en la sección Notificaciones**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir una notificación de un nuevo viaje<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** muestra la notificación del nuevo viaje asignado<br><br>**Escenario Nº3: Sin notificaciones de viajes**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir una notificación de un nuevo viaje<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema muestra un mensaje indicando que no posee notificaciones                                                                  | EP-06   |
| US-012        | Notificar al conductor del viaje concluido                                        | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si mi supervisor concluyó el viaje                                                                                                           | **Escenario Nº1: Notificación de un viaje concluido en la sección Principal**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje concluido<br>**Cuando** ingresa a la aplicación<br>**Entonces** el sistema muestra una notificación del viaje concluido<br><br>**Escenario Nº2: Notificación de un viaje concluido en la sección Notificaciones**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje concluido<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** muestra la notificación del viaje concluido<br><br>**Escenario Nº3: Sin notificaciones de viajes**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje concluido<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema muestra un mensaje indicando que no posee notificaciones                                                           | EP-06   |
| US-013        | Notificar al conductor del viaje cancelado                                        | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si un viaje ha sido cancelado                                                                                                                | **Escenario Nº1: Notificación de un viaje cancelado en la sección Principal**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje cancelado<br>**Cuando** ingresa a la aplicación<br>**Entonces** el sistema muestra una notificación del viaje cancelado<br><br>**Escenario Nº2: Notificación de un viaje cancelado en la sección Notificaciones**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje cancelado<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** muestra la notificación del viaje cancelado<br><br>**Escenario Nº3: Sin notificaciones de viajes**<br><br>**Dado que** el conductor ha iniciado sesión en la aplicación<br>**Y** desea recibir la notificación de un viaje cancelado<br>**Cuando** selecciona la opción de ver las notificaciones<br>**Entonces** el sistema muestra un mensaje indicando que no posee notificaciones                                                           | EP-06   |
| US-014        | Visualizar el estado del viaje por el sensor                                      | **Como** usuario de la aplicación<br>**Quiero** visualizar el estado del viaje por el sensor<br>**Para** saber si ha sucedido algún accidente con el material peligroso transportado                                     | **Escenario Nº1: Información del sensor recibida**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación<br>**Y** desea visualizar el estado del viaje por el sensor<br>**Cuando** ingresa a la aplicación<br>**Entonces** el sistema muestra el estado del viaje monitoreado por el sensor en la sección correspondiente Principal<br><br>**Escenario Nº2: Error con el sensor**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación<br>**Y** desea visualizar el estado del viaje por el sensor<br>**Cuando** ingresa a la aplicación<br>**Entonces** el sistema muestra un mensaje de error indicando que no puede recibir información del sensor<br>**Y** muestra una opción para comunicarse con el área de soporte                                                                                                                                                                                                                                                                                                                                                                                | EP-05   |
| US-015        | Enviar alerta de peligro al conductor                                             | **Como** supervisor de la empresa<br>**Quiero** enviar una alerta de peligro al conductor<br>**Para** alertarlo de algún inconveniente con el material peligroso transportado                                            | **Escenario Nº1: Alerta enviada**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea enviar una alerta de peligro al conductor<br>**Y** el sensor ha detectado algún inconveniente con el material peligroso transportado<br>**Cuando** el supervisor confirma el envío de una alerta de peligro<br>**Entonces** el sistema envía una alerta al conductor para advertirle de los inconvenientes<br><br>**Escenario Nº2: Error con el sistema**<br><br>**Dado que** el supervisor de la empresa ha iniciado sesión en la aplicación<br>**Y** desea enviar una alerta de peligro al conductor<br>**Y** el sensor ha detectado algún inconveniente con el material peligroso transportado<br>**Cuando** el supervisor confirma el envío de una alerta de peligro<br>**Y** hay problemas con la red o el sistema<br>**Entonces** el sistema muestra un mensaje indicando que ocurrió un error<br>**Y** muestra una opción para comunicarse con el área de soporte                                                                                                                       | EP-06   |
| US-016        | Editar perfil de Usuario                                                          | **Como** usuario de la aplicación<br>**Quiero** modificar mi información<br>**Para** corregir errores o mantenerla actualizada                                                                                           | **Escenario Nº1: Edición de perfil**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación <br>**Y** desea modificar su información de perfil<br>**Cuando** actualiza los campos disponibles con la nueva información<br>**Y** confirma los cambios<br>**Entonces** el sistema guarda los cambios<br>**Y** muestra la información actualizada en la vista de perfil<br><br>**Escenario Nº2: Carácteres inválidos**<br><br>**Dado que** el usuario ha iniciado sesión en la aplicación <br>**Y** desea modificar su información de perfil<br>**Cuando** actualiza los campos disponibles con la nueva información<br>**Y** confirma los cambios<br>**Y** ha ingresado carácteres inválidos en algún campo<br>**Entonces** el sistema muestra un mensaje indicando que el formato ingresado es inválido                                                                                                                                                                                                                                                                                                                  | EP-05   |
| US-017        | Añadir un supervisor de la empresa a través de un RESTful API                     | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Empresa* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Supervisor* a la aplicación  | **Escenario Nº1: Ingreso de correo único**<br><br>**Dado que** el endpoint `api/v1/supervisor` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve  un recurso de usuario de tipo *Supervisor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Ingreso de correo existente**<br><br>**Dado que** el endpoint `api/v1/supervisor` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico y contraseña<br>**Y** el correo electrónico ya existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                                                                       | EP-02   |
| US-018        | Añadir un conductor a través de un RESTful API                                    | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Conductor* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Conductor* a la aplicación | **Escenario Nº1: Ingreso de correo único**<br><br>**Dado que** el endpoint `api/v1/driver` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico, número de celular y contraseña<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve un recurso de usuario de tipo *Conductor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Ingreso de correo existente**<br><br>**Dado que** el endpoint `api/v1/driver` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico, número de celular y contraseña<br>**Y** el correo electrónico ya existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                        | EP-02   |
| US-019        | Obtener a un supervisor de la empresa a través de un RESTful API                  | **Como** desarrollador <br>**Quiero** obtener un supervisor mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                           | **Escenario Nº1: Ingreso de datos existentes**<br><br>**Dado que** el usuario endpoint `api/v1/supervisor/:mail/:password` está disponible<br>**Cuando** una solicitud `GET` se realiza con los parámetros correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Supervisor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Ingreso de datos inexistentes**<br><br>**Dado que** el endpoint `api/v1/supervisor/:mail/:password` está disponible<br>**Cuando** una solicitud `POST` se realiza con los parámetros correo electrónico y contraseña<br>**Y** el correo electrónico no existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *Uno o más valores son incorrectos*                                                                                                                                                                                                              | EP-02   |
| US-020        | Obtener a un conductor a través de un RESTful API                                 | **Como** desarrollador <br>**Quiero** obtener un conductor mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                            | **Escenario Nº1: Ingreso de datos existentes**<br><br>**Dado que** el usuario endpoint `api/v1/driver/:mail/:password` está disponible<br>**Cuando** una solicitud `GET` se realiza con los parámetros correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Conductor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Ingreso de datos inexistentes**<br><br>**Dado que** el endpoint `api/v1/driver/:mail/:password` está disponible<br>**Cuando** una solicitud `POST` se realiza con los parámetros correo electrónico y contraseña<br>**Y** el correo electrónico no existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *Uno o más valores son incorrectos*                                                                                                                                                                                                    | EP-02   |
| US-021        | Añadir un viaje a través de un RESTful API                                        | **Como** desarrollador <br>**Quiero** agregar un nuevo viaje al sistema mediante una solicitud `POST` al API<br>**Para** registrar nuevos viajes para los conductores a cargo de la empresa                              | **Escenario Nº1: Ingreso correcto de datos**<br><br>**Dado que** el endpoint `api/v1/trip` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado.<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve un recurso de usuario de tipo *Viaje* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EP-02   |
| US-022        | Obtener los viajes pendientes a través de un RESTful API                          | **Como** desarrollador <br>**Quiero** listar los viajes pendientes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes pendientes a los usuarios                                                         | **Escenario Nº1: Obtener los viajes pendientes de un supervisor**<br><br>**Dado que** el endpoint `api/v1/trip/:supervisorId/pendingTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador de la empresa que ha iniciado sesión<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa<br><br>**Escenario Nº2: Obtener los viajes pendientes de un conductor**<br><br>**Dado que** el endpoint `api/v1/trip/:driverId/pendingTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del conductor que ha iniciado sesión.<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa      | EP-02   |
| US-023        | Obtener el historial de viajes a través de un RESTful API                         | **Como** desarrollador <br>**Quiero** listar el historial de viajes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes realizados del usuario                                                           | **Escenario Nº1: Obtener los viajes realizados asignados por un supervisor**<br><br>**Dado que** el endpoint `api/v1/trip/:supervisorId/doneTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador de la empresa que ha iniciado sesión<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa<br><br>**Escenario Nº2: Obtener los viajes realizados de un conductor**<br><br>**Dado que** el endpoint `api/v1/trip/:driverId/doneTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del conductor que ha iniciado sesión.<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa | EP-02   |
| US-024        | Terminar un viaje a través de un RESTful API                                      | **Como** desarrollador <br>**Quiero** dar por terminado un viaje  mediante una solicitud `PATCH` al API<br>**Para** finalizar la tarea del conductor                                                                     | **Escenario Nº1: Finalizar un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId/done` está disponible<br>**Cuando** una solicitud `PATCH` se realiza con el parámetro del identificador del viaje que se va a modificar<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP-02   |
| US-025        | Cancelar un viaje a través de un RESTful API                                      | **Como** desarrollador <br>**Quiero** cancelar un viaje  mediante una solicitud `DELETE` al API<br>**Para** que el conductor no realice ese viaje                                                                        | **Escenario Nº1: Cancelar un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId` está disponible<br>**Cuando** una solicitud `DELETE` se realiza con el parámetro del identificador del viaje que se va a eliminar<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP-02   |
| US-026        | Buscar un conductor por su nombre a través de un API                              | **Como** desarrollador <br>**Quiero** listar los conductores por su nombre mediante una solicitud `GET` al API<br>**Para** mostrar los conductores al usuario                                                            | **Escenario Nº1: Nombre existente**<br><br>**Dado que** el endpoint `api/v1/driver/search?name=:name` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del conductor<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Conductor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Nombre inexistente**<br><br>**Dado que** el endpoint `api/v1/driver/search?name=:name` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del conductor<br>**Y** no existe el nombre buscado<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *No se encontró el conductor con el nombre :nombre*                                                                                                                                                                                                                                                  | EP-02   |
| US-027        | Buscar un conductor por el código del sensor de su vehículo a través de un API    | **Como** desarrollador <br>**Quiero** listar los conductores por el código del sensor de su vehículo mediante una solicitud `GET` al API<br>**Para** mostrar los conductores al usuario                                  | **Escenario Nº1: Código del sensor existente**<br><br>**Dado que** el endpoint `api/v1/driver/search?sensorCode=:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro código del sensor<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Conductor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Código del sensor inexistente**<br><br>**Dado que** el endpoint `api/v1/driver/search?sensorCode=:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del código del sensor<br>**Y** no existe el código del sensor buscado<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *No se encontró el conductor con el código de sensor :sensorCode*                                                                                                                                                                      | EP-02   |
| US-028        | Obtener un viaje a través de un RESTful API                                       | **Como** desarrollador <br>**Quiero** obtener un viaje  mediante una solicitud `GET` al API<br>**Para** mostrar la información al usuario                                                                                | **Escenario Nº1: Obtener un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del viaje el cual se desea ver la información<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Viaje* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, conductor asignado, empresa.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP-02   |
| US-029        | Modificar la información de un conductor a través de un RESTful API               | **Como** desarrollador <br>**Quiero** modificar un conductor  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                           | **Escenario Nº1: Editar datos correctamente**<br><br>**Dado que** el endpoint `api/v1/driver/:driverId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico, número de celular o contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Conductor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Correo ingresado existente**<br><br>**Dado que** el endpoint `api/v1/driver/:driverId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico, número de celular o contraseña<br>**Y** el nuevo correo electrónico ya ha sido registrado<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                | EP-02   |
| US-030        | Modificar la información de un supervisor a través de un RESTful API              | **Como** desarrollador <br>**Quiero** modificar un supervisor  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                          | **Escenario Nº1: Editar datos correctamente**<br><br>**Dado que** el endpoint `api/v1/supervisor/:supervisorId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico o contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Supervisor* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Correo ingresado existente**<br><br>**Dado que** el endpoint `api/v1/supervisor/:supervisorId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico o contraseña<br>**Y** el nuevo correo electrónico ya ha sido registrado<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                                        | EP-02   |
| US-031        | Captura de datos de Fuga de Gas                                                   | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de fuga de gas a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados           | **Escenario Nº1: Captura y envío de datos de Fuga de Gas**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Fuga de Gas<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la empresa puede revisar los datos para enviar una alerta al conductor<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Fuga de Gas<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                 | EP-07   |
| US-032        | Captura de datos de Temperatura                                                   | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de temperatura a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados           | **Escenario Nº1: Captura y envío de datos de Temperatura**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Temperatura<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la empresa puede revisar los datos para enviar una alerta al conductor<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Temperatura<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                 | EP-07   |
| US-033        | Captura de datos de Presión                                                       | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de presión a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados               | **Escenario Nº1: Captura y envío de datos de Presión**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Presión<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la empresa puede revisar los datos para enviar una alerta al conductor<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Presión<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                             | EP-07   |
| US-034        | Envío de datos de Fuga de Gas a través de un Edge Gateway                         | **Como** desarrollador<br>**Quiero** enviar la información de Fuga de Gas al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                       | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Fuga de Gas<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | EP-07   |
| US-035        | Envío de datos de Temperatura a través de un Edge Gateway                         | **Como** desarrollador<br>**Quiero** enviar la información de Temperatura al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                       | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Temperatura<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | EP-07   |
| US-036        | Envío de datos de Presión a través de un Edge Gateway                             | **Como** desarrollador<br>**Quiero** enviar la información de Presión al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                           | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Presión<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP-07   |
| US-037        | Enviar la información del sensor desde el Edge Gateway a través de un RESTful API | **Como** desarrollador<br>**Quiero** enviar la información del sensor mediante una solicitud `POST` al API<br>**Para** almacenar la información en el backend                                                            | **Escenario Nº1: Enviar datos del sensor**<br><br>**Dado que** el endpoint `api/v1/sensor/:sensorCode` está disponible<br>**Cuando** una solicitud `POST` se realiza con el parámetro del código del sensor para los valores fuga de gas, temperatura y presión.<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | EP-03   |
| US-038        | Recibir la información del sensor a través de un RESTful API                      | **Como** desarrollador<br>**Quiero** obtener la información del sensor mediante una solicitud `GET` al API<br>**Para** mostrar la información en la aplicación web o móvil                                               | **Escenario Nº1: Recibir datos del sensor**<br><br>**Dado que** el endpoint `api/v1/sensor/:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del código del sensor<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de tipo *Sensor* en el cuerpo de la Respuesta con valores para fuga de gas, temperatura y presión.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | EP-03   |
| US-039        | Sección Principal                                                                 | **Como** visitante de la página de destino<br>**Quiero** saber que me ofrece el producto de inmediato<br>**Para** confirmar si es lo que estoy buscando                                                                  | **Escenario Nº1: Información general**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** se encuentre en la sección Principal<br>**Entonces** ve que es lo que ofrece la aplicación y como contactar con FastPorte<br><br>**Escenario Nº1: Información del Producto**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza que ofrece FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve más detalles del producto y cómo funciona                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EP-01   |
| US-040        | Sección Características                                                           | **Como** visitante de la página de destino<br>**Quiero** saber cuáles son las características y beneficios<br>**Para** evaluar la contratación de este                                                                   | **Escenario Nº1: Características del Producto**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** se encuentre en la sección Características<br>**Entonces** verá información adicional sobre las características principales de FastPorte<br><br>**Escenario Nº1: Beneficios para cada segmento objetivo**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza las características de FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve cuáles son los beneficios que se ofrece para cada segmento objetivo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-01   |
| US-041        | Sección Sobre Nosotros                                                            | **Como** visitante de la página de destino<br>**Quiero** saber quiénes están involucrados en FastPorte<br>**Para** conocer más sobre esta empresa                                                                        | **Escenario Nº1: Miembros de FastPorte**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** está en la sección Sobre Nosotros<br>**Entonces** ve quiénes son los responsables de hacer FastPorte posible<br><br>**Escenario Nº1: Testimonios de los usuarios**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza quienes son los miembros de FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve testimonios sobre otros usuarios acerca de FastPorte                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | EP-01   |
| US-042        | Sección Descarga                                                                  | **Como** visitante de la página de destino<br>**Quiero** descargar la aplicación móvil<br>**Para** visualizar la interfaz de esta                                                                                        | **Escenario Nº1: Call to Action**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** esté en la sección Descarga<br>**Entonces** puede descargar la aplicación móvil dando click al botón "Descargar"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP-01   |
| US-043        | Sección Contáctanos                                                               | **Como** visitante de la página de destino<br>**Quiero** contactarme con FastPorte<br>**Para** obtener más información del producto                                                                                      | **Escenario Nº1: Contáctanos**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** este en la sección Contáctanos<br>**Y** ingrese la información solicitada<br>**Entonces** hace click en el botón "Enviar mensaje" para contactar con FastPorte                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EP-01   |
## 3.3. Impact Mapping

Se realizó el Impact Mapping para los dos User Persona desarrollados, el cuál es una técnica que permite asociar las Historias de Usuario desarrolladas a un objetivo de negocio establecido. Además, de identificar los resultados esperados y los actores involucrados.

![Impact Mapping](assets/capitulo3/impact-mapping.png)

Enlace para una mejor visualización en Figma: [Impact Mapping - Figma](https://www.figma.com/design/kRuNT3xHNIfd0SQ6vAFi9K/Artifacts-FastPorte?node-id=0-1)
## 3.4. Product Backlog

Para la calificación de Story Points empleada en el Product Backlog se siguió la sucesión de Fibonacci. En este caso siendo 1 la mínima prioridad en el desarrollo y 8 siendo la máxima. Además, se considero en el orden la realización de los Sprints.

| User Story ID | Título | Descripción                                                                        | Story Points (1/2/3/5/8)                                                                                                                                                                                                 |     |
| ------------- | ------ | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- |
| 1             | US-039 | Sección Principal                                                                  | **Como** visitante de la página de destino<br>**Quiero** saber que me ofrece el producto de inmediato<br>**Para** confirmar si es lo que estoy buscando                                                                  | 3   |
| 2             | US-040 | Sección Características                                                            | **Como** visitante de la página de destino<br>**Quiero** saber cuáles son las características y beneficios<br>**Para** evaluar la contratación de este                                                                   | 3   |
| 3             | US-041 | Sección Sobre Nosotros                                                             | **Como** visitante de la página de destino<br>**Quiero** saber quiénes están involucrados en FastPorte<br>**Para** conocer más sobre esta empresa                                                                        | 3   |
| 4             | US-042 | Sección Descarga                                                                   | **Como** visitante de la página de destino<br>**Quiero** descargar la aplicación móvil<br>**Para** visualizar la interfaz de esta                                                                                        | 3   |
| 5             | US-043 | Sección Contáctanos                                                                | **Como** visitante de la página de destino<br>**Quiero** contactarme con FastPorte<br>**Para** obtener más información del producto                                                                                      | 3   |
| 6             | US-001 | Registro de supervisor de la empresa                                               | **Como** supervisor de la empresa<br>**Quiero** registrarme en la aplicación<br>**Para** supervisar a los conductores a mi cargo                                                                                         | 5   |
| 7             | US-004 | Registrar un viaje                                                                 | **Como** supervisor de la empresa<br>**Quiero** registrar un viaje<br>**Para** notificar al conductor los servicios que debe realizar                                                                                    | 8   |
| 8             | US-015 | Enviar alerta de peligro al conductor                                              | **Como** supervisor de la empresa<br>**Quiero** enviar una alerta de peligro al conductor<br>**Para** alertarlo de algún inconveniente con el material peligroso transportado                                            | 8   |
| 9             | US-014 | Visualizar el estado del viaje por el sensor                                       | **Como** usuario de la aplicación<br>**Quiero** visualizar el estado del viaje por el sensor<br>**Para** saber si ha sucedido algún accidente con el material peligroso transportado                                     | 8   |
| 10            | US-007 | Concluir viaje                                                                     | **Como** supervisor de la empresa<br>**Quiero** concluir los viajes que ya se han realizado<br>**Para** dar por terminado la tarea del conductor                                                                         | 8   |
| 11            | US-009 | Buscar un conductor                                                                | **Como** supervisor de la empresa<br>**Quiero** buscar un conductor<br>**Para** asignarle un viaje                                                                                                                       | 5   |
| 12            | US-010 | Visualizar la información del viaje                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar la información de un viaje<br>**Para** revisar algún dato en concreto                                                                                         | 5   |
| 13            | US-011 | Notificar al conductor del nuevo viaje                                             | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si se me ha asignado un viaje                                                                                                                | 5   |
| 14            | US-002 | Registro de conductor                                                              | **Como** conductor<br>**Quiero** registrarme en la aplicación<br>**Para** recibir información de los viajes que debo realizar                                                                                            | 5   |
| 15            | US-003 | Inicio de sesión                                                                   | **Como** usuario de la aplicación<br>**Quiero** iniciar sesión en la aplicación<br>**Para** acceder a las funcionalidades de la aplicación                                                                               | 5   |
| 16            | US-005 | Viajes pendientes                                                                  | **Como** usuario de la aplicación<br>**Quiero** visualizar los viajes pendientes<br>**Para** gestionar los viajes que se deben realizar                                                                                  | 5   |
| 17            | US-006 | Historial de Viajes                                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar el historial de viajes<br>**Para** llevar un registro de los viajes completados                                                                               | 5   |
| 18            | US-008 | Cancelar viaje                                                                     | **Como** supervisor de la empresa<br>**Quiero** cancelar un viaje<br>**Para** descartar un viaje creado erróneamente                                                                                                     | 5   |
| 19            | US-012 | Notificar al conductor del viaje concluido                                         | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si mi supervisor conluyó el viaje                                                                                                            | 5   |
| 20            | US-013 | Notificar al conductor del viaje cancelado                                         | **Como** conductor<br>**Quiero** recibir una notificación<br>**Para** saber si un viaje ha sido cancelado                                                                                                                | 5   |
| 21            | US-016 | Editar perfil de Usuario                                                           | **Como** usuario de la aplicación<br>**Quiero** modificar mi información<br>**Para** corregir errores o mantenerla actualizada                                                                                           | 2   |
| 22            | US-017 | Añadir un supervisor de la empresa a través de un RESTful API                      | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Empresa* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Empresa* a la aplicación     | 5   |
| 23            | US-018 | Añadir un conductor a través de un RESTful API                                     | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Conductor* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Conductor* a la aplicación | 5   |
| 24            | US-019 | Obtener a un supervisor de la empresa a través de un RESTful API                   | **Como** desarrollador <br>**Quiero** obtener una empresa mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                             | 5   |
| 25            | US-020 | Obtener a un conductor a través de un RESTful API                                  | **Como** desarrollador <br>**Quiero** obtener un conductor mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                            | 5   |
| 26            | US-021 | Añadir un viaje a través de un RESTful API                                         | **Como** desarrollador <br>**Quiero** agregar un nuevo viaje al sistema mediante una solicitud `POST` al API<br>**Para** registrar nuevos viajes para los conductores a cargo de la empresa                              | 5   |
| 27            | US-022 | Obtener los viajes pendientes a través de un RESTful API                           | **Como** desarrollador <br>**Quiero** listar los viajes pendientes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes pendientes a los usuarios                                                         | 5   |
| 28            | US-023 | Obtener el historial de viajes a través de un RESTful API                          | **Como** desarrollador <br>**Quiero** listar el historial de viajes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes realizados del usuario                                                           | 5   |
| 29            | US-024 | Terminar un viaje a través de un RESTful API                                       | **Como** desarrollador <br>**Quiero** dar por terminado un viaje  mediante una solicitud `PATCH` al API<br>**Para** finalizar la tarea del conductor                                                                     | 8   |
| 30            | US-025 | Cancelar viaje a través de un RESTful API                                          | **Como** desarrollador <br>**Quiero** cancelar un viaje  mediante una solicitud `DELETE` al API<br>**Para** que el conductor no realice ese viaje                                                                        | 5   |
| 31            | US-026 | Buscar un conductor por su nombre a través de un API                               | **Como** desarrollador <br>**Quiero** listar los conductores por su nombre mediante una solicitud `GET` al API<br>**Para** mostrar los conductores al usuario                                                            | 5   |
| 32            | US-027 | Buscar un conductor por el código del sensor de su vehículo a través de un API     | **Como** desarrollador <br>**Quiero** listar los conductores por el código del sensor de su vehículo mediante una solicitud `GET` al API<br>**Para** mostrar los conductores al usuario                                  | 5   |
| 33            | US-028 | Obtener un viaje a través de un RESTful API                                        | **Como** desarrollador <br>**Quiero** obtener un viaje  mediante una solicitud `GET` al API<br>**Para** mostrar la información al usuario                                                                                | 5   |
| 34            | US-029 | Modificar la información de un conductor a través de un RESTful API                | **Como** desarrollador <br>**Quiero** modificar un conductor  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                           | 3   |
| 35            | US-030 | Modificar la información de un supervisor de la empresa a través de un RESTful API | **Como** desarrollador <br>**Quiero** modificar una empresa  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                            | 5   |
| 36            | US-031 | Captura de datos de Fuga de Gas                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de fuga de gas a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados           | 8   |
| 37            | US-032 | Captura de datos de Temperatura                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de temperatura a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados           | 8   |
| 38            | US-033 | Captura de datos de Presión                                                        | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de presión a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados               | 8   |
| 39            | US-034 | Envío de datos de Fuga de Gas a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Fuga de Gas al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                       | 8   |
| 40            | US-035 | Envío de datos de Temperatura a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Temperatura al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                       | 8   |
| 41            | US-036 | Envío de datos de Presión a través de un Edge Gateway                              | **Como** desarrollador<br>**Quiero** enviar la información de Presión al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                           | 8   |
| 42            | US-037 | Enviar la información del sensor desde el Edge Gateway a través de un RESTful API  | **Como** desarrollador<br>**Quiero** enviar la información del sensor mediante una solicitud `POST` al API<br>**Para** almacenar la información en el backend                                                            | 8   |
| 43            | US-038 | Recibir la información del sensor a través de un RESTful API                       | **Como** desarrollador<br>**Quiero** obtener la información del sensor mediante una solicitud `GET` al API<br>**Para** mostrar la información en la aplicación web o móvil                                               | 8   |
# Capitulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming <br>
Para el desarroolo del EventStorming, nos reunimos para organizar una lluvia de ideas con los temas, datos y funcionalidades necesarias para el desarrollo de la aplicación, resultando en el siguiente gráfico:<br>
![EventStorming](./assets/chapter4_img/step8.jpg)

#### 4.1.1.1 Candidate Context Discovery <br>
A continuación mostraremos el paso a paso para la organizacion del EventStorming: <br>
<br>Step 1: <br>
Generar las ideas más importantes del negocio en base a los requerimientos
![Step 1](./assets/chapter4_img/step1.jpg)
<br>Step 2: <br>
Relacionar las ideas entre si para tener secuencias
![Step 2](./assets/chapter4_img/step2.jpg)
<br>Step 3: <br>
Identificar las ideas que pueden ocacionar deciciones múltiples o pueden ser puntos críticos, usando preguntas clave
![Step 3](./assets/chapter4_img/step3.jpg)
<br>Step 4: <br>
Organizar las relaciones en función secuencial
![Step 4](./assets/chapter4_img/step4.jpg)
<br> Step 5: <br>
Clasificar el tipo de usuario que va a usar cada sección
![Step 5](./assets/chapter4_img/step5.jpg)
<br>Step 6: <br>
Añadir detalles de visualizacion de interfaz
![Step 6](./assets/chapter4_img/step6.jpg)
<br> Step 7: <br>
Detectar si es posible usar una aplicación externa
![Step 7](./assets/chapter4_img/step7.jpg)
<br> Step 8: <br> 
Por ultimo se eliminan dellates que fueron descartados y muestra el resultado final
![Step 8](./assets/chapter4_img/step8.jpg)

#### 4.1.1.2 Domain Message Flows Modeling <br>
En esta seccion mostraremos el proceso seguido para visualizar cómo deben colaborar los bounded contexts para resolver los casos que se presentan en el negocio para los usuarios del sistema. <br>

Leyenda: <br>

![Leyenda](./assets/chapter4_img/leyenda.png)

Escenario: Inicio de sesión <br>
Cuando un usario, ya sea supervisro o conductor, desee registrarse se enviará una solicitud al bounded context 'Profile management' con los datos requeridos, este hará una validacion con la base de datos y si es exitosa, retornará al usuario el inicio de su sesión
![Escenario 1](./assets/chapter4_img/escenario1.png)

Escenario: Registro de usuario <br>
Si el usuario va a registrarse, ingresa los datos solicitados, estos pasaran al bounded context y se alamcenán en su base de datos.
![Escenario 2](./assets/chapter4_img/escenario2.png)

Escenario: Registro del sensor <br>
Cuando el usuario registre un sensor, el bounded context 'Profile management' se comunicara con 'Security monitoring' para registrar los datos
![Escenario 3](./assets/chapter4_img/escenario3.png)

Escenario: Programación de viaje <br>
Si el usuario supervisor debe registrar un nuevo viaje, 'Transport management' recibe los datos necesarios y se comunica con ' Profile management' para generarle la notificación
![Escenario 4](./assets/chapter4_img/escenario4.png)

Escenario: Conductor visualiza sus viajes pendientes <br>
Cuando el usuario desea revisar los viajes programados que tiene, por medio de 'Profile management' y 'Transport management' ingresan a la base de datos respectiva para obtener la lista que retorne con los viajes. 
![Escenario 5](./assets/chapter4_img/escenario5.png)

Escenario: Sensor detecta un problema <br>
En caso de que el sensor detecte un problema por medio de 'Security monitoring', envia una alerta desde 'Alerts system' para que lo reciba el usuario.
![Escenario 6](./assets/chapter4_img/escenario6.png)

#### 4.1.1.3 Bounded Context Canvases

Bounded context 'Profle management'  <br>
Autenticación y autorización de usuarios (conductores y supervisores) y manejo de roles dentro del sistema
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_profile.jpg)

Bounded context 'Security monitoring'  <br>
Capturar y procesar los datos de sensores instalados en las cisternas para garantizar la seguridad durante el transporte de materiales peligrosos. Notificar en tiempo real cuando se excedan los límites críticos de seguridad.
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_security.jpg)

Bounded context 'Transport management'  <br>
Planificar y gestionar el transporte de materiales peligrosos, asignando vehículos y conductores para cada ruta, garantizando el cumplimiento de regulaciones.
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_transport.jpg)

Bounded context 'Alerts system'  <br>
Gestionar el envío de alertas y notificaciones a los conductores y supervisores en tiempo real cuando se detectan problemas en los sensores.
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_alerts.jpg)

### 4.1.2. Context Mapping <br>
Transport management ↔️ Security monitoring

Relación: Customer-Supplier

Patrón:
Transport management actúa como un 'Cliente' de Security monitoring. Necesita información en tiempo real sobre el estado de los sensores de seguridad instalados en los vehículos.
Security monitoring actúa como un 'Proveedor' de datos de gases, temperatura y presión a Transport management.

Security monitoring ↔️ Alerts system

Relación: Customer-Supplier

Patrón:
Security monitoring es el 'Cliente' que requiere la funcionalidad de notificaciones en tiempo real cuando un sensor detecta un valor crítico.
Alerts system es el 'Proveedor', que envía mensajes a los usuarios relevantes (conductores, supervisores) cuando se genera una alerta.

Transport management ↔️ Profle management

Relación: Customer-Supplier

Patrón:
Transport management es el 'Cliente' que requiere la autenticación y autorización de los usuarios (conductores y supervisores) antes de planificar rutas y asignar tareas.
Profle management es el 'Proveedor' que gestiona los permisos y autenticaciones para permitir el acceso a los usuarios en el sistema de transporte.

Alerts system ↔️ Profle management

Relación: Anticorruption Layer 

Patrón:
Alerts system se protege contra posibles complejidades o cambios en el sistema de Profle management al establecer una capa anticorrupción. De esta manera, los cambios en el esquema de usuarios o permisos no afectan la lógica de notificaciones.

![Context Mapping](./assets/chapter4_img/context_mapping.jpg)

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram <br>

Este diagrama describe la arquitectura a nivel de sistema de FastPorte, un servicio que conecta conductores y empresas para la gestión eficiente de la logística y transporte. Los actores involucrados son: <br>

Conductor: Se comunica con el sistema para obtener asignaciones de transporte y actualizar el estado de las entregas.<br>
Supervisor: Utiliza el sistema para gestionar los viajes de los conductores. El sistema gestiona el intercambio de información entre conductores y supervisores para optimizar las operaciones logísticas. <br>

![C4 Diagrama de Contexto](./assets/chapter4_img/landscape.jpg)

#### 4.1.3.2. Software Architecture Context Level Diagrams <br>

El diagrama de nivel de contexto de FastPorte muestra las interacciones clave entre el sistema y sus usuarios principales:<br>

Conductor: Recibe notificaciones, alertas del sensor y actualizaciones de rutas.<br>
Supervisar: Utiliza el sistema para gestionar los viajes de los conductores. El sistema gestiona el intercambio de información entre conductores y supervisores para optimizar las operaciones logísticas.<br>

![C4 Diagrama de Contexto](./assets/chapter4_img/c4_context.png)

#### 4.1.3.2. Software Architecture Container Level Diagrams. <br>

Este diagrama detalla la arquitectura de los contenedores de FastPorte, mostrando los componentes principales del sistema:<br>

Landing Page: La interfaz web pública para que los usuarios obtengan información sobre el servicio.<br>
Web Application: Aplicación utilizada por los supervisores para gestionar envíos.<br>
Mobile App: Aplicación móvil destinada a los conductores para recibir las alertas o notificaciones de viaje<br>
Backend: Servicio REST que gestiona y procesa la información de los datos. <br>
Database: Base de datos donde se almacena la información relacionada con los envíos, conductores, y empresas.<br>
Edge API: Conexion con el sistema IoT para el envio de alertas.<br>

![C4 Diagrama de Componentes](./assets/chapter4_img/c4_component.png)

#### 4.1.3.3. Software Architecture Deployment Diagrams <br>

Para el despliegue de nuestra landing page, app web nos apoyaremos de Firebase, servicio gratuito y de facil uso de hosting para paginas web, y para nuestro servidor backend y base de datos nos apoyaremos de la nube de Azure<br>

![Software Architecture Deployment Diagrams](./assets/chapter4_img/ArchDeploy.png)

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Profle management

Este Bounded Context "Profile Management" se encarga exclusivamente de 
la gestión de la información de los usuarios dentro del sistema, sin 
involucrar los aspectos relacionados con la autenticación o autorización. 
Su objetivo es permitir a los usuarios visualizar y actualizar su 
información personal, gestionar sus preferencias, y administrar los 
roles asignados.

#### 4.2.1.1. Domain Layer.

En esta capa se encuentran las entidades y objetos de valor que forman parte del dominio del perfil de usuario. Esta capa representa la lógica central de negocio que se ocupa de gestionar los perfiles de los usuarios.

* **Usuario:** Es la entidad principal que contiene la información del perfil del usuario, como su nombre, dirección de correo, número de teléfono, y otras propiedades que lo definen.
* **Rol:** Esta entidad representa los distintos roles que pueden ser asignados a los usuarios, como conductores o supervisores, con diferentes permisos asociados para interactuar con el sistema.
* **Notificación de Usuario:** Es un objeto de valor que maneja las preferencias del usuario relacionadas con el envío de notificaciones (por ejemplo, preferencia de recibir alertas por correo electrónico).
* **Historial de Perfil:** Un objeto de valor que rastrea las modificaciones realizadas en el perfil del usuario, permitiendo auditoría o consultas de cambios.

#### 4.2.1.2. Interface Layer.

Esta capa proporciona la interfaz para que el sistema interactúe con otros sistemas o interfaces de usuario. Permite que los usuarios actualicen y accedan a la información de su perfil.

* **Gestión de Perfiles:** Interfaz que ofrece la capacidad de ver y actualizar los datos del perfil del usuario. Desde esta capa, el usuario puede modificar su información personal y preferencias.
* **Notificaciones de Usuario:** Interface que controla cómo los usuarios gestionan la configuración de notificaciones dentro de su perfil (por ejemplo, activar o desactivar notificaciones push).

#### 4.2.1.3. Application Layer.

La capa de aplicación coordina las operaciones del sistema que involucran la gestión de perfiles, sin involucrarse directamente en la lógica de negocio ni en la infraestructura.

* **Actualización de Perfil:** Orquesta las operaciones necesarias para que el perfil de un usuario sea actualizado, comunicándose con las entidades de la capa de dominio.
* **Consulta de Perfil:** Se encarga de proporcionar los datos de perfil cuando se realiza una solicitud de consulta desde la interfaz.
* **Gestión de Roles:** Encargada de coordinar las actualizaciones y consultas de los roles de los usuarios.

#### 4.2.1.4. Infrastructure Layer.

Esta capa se ocupa de implementar los detalles técnicos relacionados con la persistencia de los datos, y las interacciones con otras herramientas externas.

* **Repositorios de Usuarios y Roles:** Componentes encargados de almacenar, recuperar y actualizar la información del usuario y los roles en la base de datos.
* **Servicio de Notificaciones:** Enlace a servicios externos para gestionar el envío de notificaciones a los usuarios, basándose en sus preferencias.

#### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams.

Diagrama de componentes para el bounded context de Profile Management:

![C4 Diagrama de Componentes](./assets/chapter4_img/profileManagementComponentDiagram.png)

#### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.

Diagrama de clases para el bounded context de Profile Management:

![Diagrama_de_clases_perfil](./assets/chapter4_img/profile_management_class_diagram.png)

###### 4.2.1.7.2. Bounded Context Database Design Diagram.

Diagrama del modelado de la base de datos para el bounded context de Profile Management:

![Diagrama_de_base_de_Datos_perfil](./assets/chapter4_img/profle_management_database_diagram.png)

### 4.2.2. Bounded Context: Security Monitoring
Este Bounded Context se encarga de la monitorización de la seguridad relacionada con el transporte de materiales peligrosos. Captura y procesa los datos de sensores instalados en las cisternas para garantizar la seguridad durante el transporte. Además, envía notificaciones en tiempo real cuando los sensores detectan que se exceden los límites críticos de seguridad.

#### 4.2.2.1. Domain Layer.

En esta capa se encuentran las entidades y objetos de valor que representan los conceptos fundamentales de la monitorización de seguridad.

* **Sensor:** Entidad principal que representa los sensores instalados en las cisternas. Cada sensor tiene atributos como identificador, ubicación y valores de medida como temperatura o presión.
* **Estado del Sensor:** Un objeto de valor que refleja el estado actual de un sensor (por ejemplo, normal, crítico, fuera de servicio) en función de los datos registrados por los sensores.
* **Alerta de Seguridad:** Un objeto de valor que encapsula la información relacionada con una alerta generada cuando los valores del sensor superan ciertos umbrales críticos.
* **Historial del Sensor:** Objeto de valor que registra los cambios de estado y los datos históricos del sensor, permitiendo auditoría y análisis.

#### 4.2.2.2. Interface Layer.

Esta capa gestiona las interacciones entre el sistema y las interfaces externas (ya sean interfaces de usuario o sistemas de terceros) para monitorizar la seguridad de las cisternas y obtener información en tiempo real.

* **Consulta de Estado del Sensor:** Interfaz que permite a los operadores o sistemas externos consultar el estado actual de los sensores instalados en las cisternas.
* **Gestión de Sensores:** Proporciona la capacidad de registrar nuevos sensores en el sistema o actualizar los datos de los sensores existentes.

#### 4.2.2.3. Application Layer.

La capa de aplicación coordina las operaciones de monitoreo y alertas, manejando la lógica de la aplicación que no está directamente relacionada con la infraestructura o la lógica central del dominio.

* **Registro de Sensores:** Coordina el proceso de registrar nuevos sensores en el sistema y asociarlos a las cisternas correspondientes.
* **Actualización de Datos del Sensor:** Orquesta la actualización periódica de los datos de los sensores (por ejemplo, temperatura, presión).
* **Generación de Alertas:** Se encarga de generar alertas en tiempo real cuando los sensores detectan condiciones peligrosas que superan los umbrales establecidos.

#### 4.2.2.4. Infrastructure Layer.

La capa de infraestructura se encarga de los detalles técnicos y de soporte, como el almacenamiento de los datos de sensores y la conexión con otros sistemas externos.

* **Repositorio de Sensores:** Componente encargado de almacenar los datos de los sensores, incluyendo la información histórica y las alertas generadas.
* **Servicio de Alertas:** Responsable de enviar notificaciones a los operadores o sistemas externos cuando se detecta una condición de alerta. Puede estar vinculado a servicios de mensajería o correo electrónico.
* **Servicio de Comunicación con Sensores:** Interfaz técnica que permite recibir y procesar los datos enviados por los sensores en tiempo real.

#### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams.

Diagrama de componentes para el bounded context de Security Monitoring:

![C4 Diagrama de Componentes](./assets/chapter4_img/securityMonitoringComponentDiagram.jpeg)

#### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.

Diagrama de clases para el bounded context de Security Monitoring:

![Diagrama de clases_security](./assets/chapter4_img/security_monitoring_class_diagram.png)

##### 4.2.2.7.2. Bounded Context Database Design Diagram.

Diagrama del modelado de la base de datos para el bounded context de Security Monitoring:

![Diagrama de base_de_datos_security](./assets/chapter4_img/security_monitoring_database_diagram.png)

### 4.2.3. Bounded Context: Transport management

El bounded context Transport Management se encarga de planificar y gestionar el transporte de materiales peligrosos, asegurando el cumplimiento de regulaciones. Este contexto incluye la asignación de vehículos y conductores, y monitorea los viajes en tiempo real para garantizar que se realicen de manera segura.

#### 4.2.3.1. Domain Layer.

El domain layer en el contexto de Transport Management maneja la lógica central del negocio relacionada con la planificación y gestión del transporte de materiales peligrosos. Aquí se definen las entidades principales y los servicios relacionados con las operaciones de transporte. En este bounded context, la lógica central incluye:

* **Viaje:** Representa el transporte de materiales peligrosos desde un origen a un destino, que incluye datos como el origen, destino, conductor asignado, vehículo, estado actual, y materiales transportados.
* **Conductor:** Es el encargado de operar el vehículo y realizar el transporte de los materiales peligrosos.
* **Vehículo:** Describe el vehículo asignado para cada viaje, con detalles sobre su capacidad y características especiales para transportar materiales peligrosos.
* **Estado del Viaje:** Representa las diferentes etapas del viaje, desde su inicio hasta su finalización, incluyendo alertas y situaciones anómalas.
* **Historial de Viajes:** Mantiene un registro de todos los viajes realizados, con sus estados y eventos importantes.

#### 4.2.3.2. Interface Layer.

La interface layer proporciona los puntos de acceso para los usuarios y sistemas externos que interactúan con el contexto de Transport Management. En este caso, incluye:

* **Registrar Viaje:** Una interfaz para que los usuarios ingresen un nuevo viaje en el sistema, asignando conductor, vehículo, y materiales a transportar.
* **Actualizar Estado de Viaje:** Permite actualizar la información del viaje en curso, como la ubicación actual, problemas detectados, o si se ha completado.
* **Consultar Historial de Viajes:** Interfaz para obtener un resumen o detalle completo de viajes anteriores, con información sobre eventos, incidentes, o irregularidades.

#### 4.2.3.3. Application Layer.

La application layer orquesta el comportamiento entre la capa de dominio y las interfaces externas. Aquí se encapsulan las reglas del negocio y se coordinan los procesos dentro del contexto de transporte. Las responsabilidades incluyen:

* **Asignación de Transporte:** Un servicio de la aplicación que asigna automáticamente conductores y vehículos disponibles según las necesidades del transporte.
* **Monitoreo de Viajes:** Coordinación con el contexto de Security Monitoring para obtener actualizaciones en tiempo real sobre el estado del viaje, asegurando el cumplimiento de regulaciones de seguridad.
* **Gestión de Incidentes:** Gestión de incidentes críticos en tiempo real, generando alertas cuando se detectan situaciones peligrosas durante el transporte.

#### 4.2.3.4. Infrastructure Layer.

La infrastructure layer gestiona la interacción con recursos externos como bases de datos, sistemas de monitoreo, y APIs de otros contextos. En el contexto de Transport Management, esta capa maneja:

* **Base de Datos de Viajes:** Una base de datos que almacena todos los detalles de los viajes, estados y eventos importantes asociados a cada uno.
* **Integración con Sensores:** Interacciones con sensores de monitoreo (a través del contexto Security Monitoring) para obtener información en tiempo real sobre el estado del vehículo y materiales.
* **Comunicación con otros Contextos:** Integración con otros sistemas relevantes, como el contexto de Profile Management para obtener detalles de los conductores, o Security Monitoring para actualizaciones de seguridad.

#### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams.

Diagrama de componentes para el bounded context de Transport management:

![C4 Diagrama de Componentes](./assets/chapter4_img/transportManagementComponentDiagram.jpeg)

#### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams.

Diagrama de clases para el bounded context de Transport management:

![diagrama de clases transport management](./assets/chapter4_img/transport_management_class_diagram.png)

###### 4.2.3.7.2. Bounded Context Database Design Diagram.
![Diagrama de base_de_datos_sensor](./assets/chapter4_img/travel_bounded_context-database_diagram.png)
# Capítulo V: Solution UI/UX Design
## 5.1. Style Guidelines

En esta sección, nuestro equipo gestionará de manera coherente los elementos visuales y de diseño utilizados en el proyecto. Aquí se incluyen recursos como assets, tipografías, y otros componentes esenciales que permiten mantener una presentación visual consistente y alineada en todos los aspectos del proyecto. Las guías se dividen en tres áreas clave: Guías Generales de Estilo, Guías de Estilo Web y Guías de Estilo para Móviles, asegurando un enfoque unificado independientemente de la plataforma o medio.

### 5.1.1. General Style Guidelines

Esta sección detalla las decisiones clave y las referencias visuales en torno a conceptos básicos como Branding, Tipografía, Colores y Espaciado, así como las dimensiones relacionadas con el tono de comunicación y el estilo de lenguaje utilizado formal y respetuoso. Además, se incluye el fundamento de los principios y elementos de diseño considerados en cada decisión, garantizando una alineación clara y estratégica en todas las instancias visuales del proyecto.

**Tipografía:**

Para este proyecto, se ha decidido utilizar la tipografía Inter debido a su diseño moderno, legibilidad y versatilidad en una amplia variedad de dispositivos y tamaños de pantalla. Inter está diseñada específicamente para ofrecer legibilidad en interfaces, lo que la convierte en una opción ideal para plataformas web y móviles.

[![image.png](https://i.postimg.cc/Dy6r4RnW/1-Inter-Font-Family.png)](https://postimg.cc/8jFJqKFD)

<br>

[![image.png](https://i.postimg.cc/W14MGS15/2-Inter-Font-Family.png)](https://postimg.cc/crVgZRY3)

**Tipografía Fluida:**

La tipografía fluida es una técnica moderna que permite que el tamaño de las fuentes se ajuste automáticamente según el tamaño de la pantalla. En lugar de establecer un tamaño de fuente fijo para cada tipo de dispositivo, por ejemplo de 16px para móviles y 24px para escritorio, se puede establecer una fórmula que permita que el tamaño de la fuente "fluya" entre un valor mínimo y un valor máximo dependiendo del ancho de la pantalla.

[![image.png](https://i.postimg.cc/7ZQSm7Cw/2-Modern-fluid-typography.png)](https://postimg.cc/PCYLqCzR)


**Parámetros de Tipografía Fluida:**

- Root Font Size (Tamaño de Fuente Base): Establece el tamaño de la fuente raíz (generalmente 16px) y es el valor de referencia para los tamaños relativos.

- Min Size (Tamaño Mínimo): El tamaño más pequeño que la tipografía debe tener en cualquier dispositivo o pantalla.

- Max Size (Tamaño Máximo): El tamaño más grande que la tipografía debe alcanzar en pantallas grandes.

- Fluid Size: Controla cómo la tipografía crece o decrece en función del ancho de la pantalla.

- Relative Size: Este es un ajuste que respeta las configuraciones del usuario en el navegador, utilizando valores relativos como rem en lugar de valores absolutos como px. 

[![image.png](https://i.postimg.cc/Gp8GN2YY/2-Modern-fluid-typography2.png)](https://postimg.cc/5HJXQfsN)

<br><br>

**Colores:**

La elección de una paleta de colores predominantemente azul para nuestra solución de software de gestión de flotas y transporte de materiales peligrosos se basa en consideraciones psicológicas y funcionales específicas para nuestro público objetivo.

[![image.png](https://i.postimg.cc/vB59YN0Z/3-colors.png)](https://postimg.cc/0M2rZcgT)

- **Confianza y seguridad:** El azul transmite una sensación de confiabilidad y seguridad.

- **Calma y concentración:** Los tonos azules claros promueven la calma y ayudan a mantener la concentración.

- **Profesionalismo:** El azul oscuro aporta un toque de profesionalismo y seriedad, reflejando la naturaleza crítica del negocio.

- **Contraste y legibilidad:** La combinación de azules con fondos oscuros y texto claro (--text-100:#FFFFFF) asegura una excelente legibilidad en diversas condiciones de iluminación.

- **Asociación con la tecnología:** El azul se asocia comúnmente con la tecnología y la innovación, reforzando la percepción de una solución de software avanzada.

[![image.png](https://i.postimg.cc/L5RPn3WB/3-colors2.png)](https://postimg.cc/0MWj4DPb)

[![image.png](https://i.postimg.cc/90p7Tq53/3-colors3.png)](https://postimg.cc/jnD2Y2Sv)

<br>

**Espaciado:**

[![image.png](https://i.postimg.cc/m2LM4VCT/4-spacing.png)](https://postimg.cc/jC1CQHM1)

Se utilizará un sistema de espaciado coherente en toda la aplicación para crear una experiencia visual uniforme y predecible.También, se empleará diferentes tamaños de espaciado para establecer una clara jerarquía entre elementos, facilitando la comprensión rápida de la información. El sistema de espaciado es flexible y se adapta a diferentes tamaños de pantalla, garantizando una experiencia consistente en diversos dispositivos.

Por otro lado, nos aseguraremos de tener un espaciado adecuado entre líneas y párrafos para mejorar la legibilidad, especialmente importante en condiciones de baja visibilidad o durante la conducción. Además, se utilizará el espaciado para agrupar elementos relacionados y separar distintas secciones de información, mejorando la organización visual. Se incorporará espacios en blanco estratégicos para reducir la sobrecarga visual y ayudar a los usuarios a enfocarse en la información crítica.

**Branding:**

[![image.png](https://i.postimg.cc/JzgBbLgh/5-fastporte-Logo.png)](https://postimg.cc/dh21YzJM)

Nuestro logo presenta la silueta estilizada de un camión dirigiéndose hacia la derecha. Esta imagen fue elegida por varias razones.El camión es una representación directa de la industria del transporte, lo que comunica instantáneamente el campo en el que operamos. La dirección del camión hacia la derecha simboliza avance, progreso y movimiento hacia adelante, alineándose con nuestra visión de impulsar la industria hacia el futuro. Además, La silueta simplificada del camión permite un reconocimiento rápido y fácil, incluso a pequeña escala o en diferentes aplicaciones. La claridad y precisión del diseño transmiten un sentido de profesionalismo y confiabilidad.

### 5.1.2. Web, Mobile and IoT Style Guidelines

Nuestra aplicación web para el transporte de materiales peligrosos incorporará un diseño responsive para garantizar su funcionalidad en una amplia gama de dispositivos. Esta característica es esencial en nuestro sector, donde los usuarios necesitan acceder a información crítica desde diversos dispositivos y en diferentes contextos operativos.

[![image.png](https://i.postimg.cc/QxhgtjGG/6-responsive.jpg)](https://postimg.cc/pyc5cbLq)

El enfoque responsive permite que la interfaz se adapte automáticamente a diferentes tamaños de pantalla, desde smartphones hasta computadoras de escritorio. Utilizamos un sistema de rejilla flexible y breakpoints estratégicos para reorganizar el contenido, asegurando que elementos como menús, tablas de datos y gráficos se ajusten para mantener la legibilidad y usabilidad en cualquier dispositivo.

También, se usará principios de diseño para aplicaciones móviles hecho por Google.

[![image.png](https://i.postimg.cc/MTYgR8wF/6-b-squeda.png)](https://postimg.cc/8JjyQ9jR)

Fuente: Google (s.f). Principios de diseño de las aplicaciones para dispositivos móviles. https://www.thinkwithgoogle.com/_qs/documents/1011/Google_Guia_UX.pdf#:~:text=Cap%C3%ADtulo%201:%20Navegaci%C3%B3n%20y%20exploraci%C3%B3n%20de%20la%20aplicaci%C3%B3n. 

Por ejemplo, un buen diseño es que las acciones principales como búsqueda deban estar en un posición privilegiada, donde se destaque esa característica y sea claramente visiable por el usuario.

[![image.png](https://i.postimg.cc/qqMSxZMM/6-registro.png)](https://postimg.cc/cg2FshnV)

Fuente: Google (s.f). Principios de diseño de las aplicaciones para dispositivos móviles. https://www.thinkwithgoogle.com/_qs/documents/1011/Google_Guia_UX.pdf#:~:text=Cap%C3%ADtulo%201:%20Navegaci%C3%B3n%20y%20exploraci%C3%B3n%20de%20la%20aplicaci%C3%B3n. 

También, se puede obtar por un diseño donde primero se le muestre la Landing Page y se le solicite al usuario registrarse solo si es escencial que lo haga o si el servicio lo ha convencido, ya que directamente enviar al usuario a registrarse sería un error de diseño.

[![image.png](https://i.postimg.cc/xjHsNQfj/6-vocabulario.png)](https://postimg.cc/V5f92302)

Fuente: Google (s.f). Principios de diseño de las aplicaciones para dispositivos móviles. https://www.thinkwithgoogle.com/_qs/documents/1011/Google_Guia_UX.pdf#:~:text=Cap%C3%ADtulo%201:%20Navegaci%C3%B3n%20y%20exploraci%C3%B3n%20de%20la%20aplicaci%C3%B3n. 

Adicionalmente, se tendrá en cuenta el diseño mediante un mismo vocabulario que usan los usuarios de la solución de software. En este apartado se sugiere evitar el uso de frase o términos desconocidos que sunpondría mayor carga congnitiva para los usuarios. La comunicación debe ser clara para que cada funcionalidad que use nuestro público objetivo pueda se use sin conplicaciones.

## 5.2. Information Architecture

### 5.2.1. Organization Systems

En nuestra aplicación de gestión de transporte de materiales peligrosos "FastPorte", hemos implementado diversos sistemas de organización para asegurar que la información sea accesible y fácil de entender para nuestros usuarios. Estos son los principales enfoques utilizados:

[![image.png](https://i.postimg.cc/nzNMjzbn/Organization-System-Web-App.png)](https://postimg.cc/TLqTBT3s)

[![image.png](https://i.postimg.cc/59FXcwLy/Organization-System-Mobile-App.png)](https://postimg.cc/G9dLGTMn)

- **Organización Jerárquica (Visual Hierarchy):** Para la Landing Page vamos a utilizar una jerarquía visual clara, con el Call To Action principal en la sección hero, seguido por características, beneficios e información de contacto. Además, para la Web App y Mobile App la información del viaje en curso se presenta de manera prominente, seguida por otras funcionalidades en orden de importancia.

- **Organización Secuencial:** Para el proceso de registro y login tanto en la web como en la app móvil, estos procesos siguen una secuencia de pasos lógica. También, la asignación de viajes (Web App), el supervisor sigue un proceso paso a paso para asignar viajes a los conductores.

- **Categorización por Tópicos:** La Web App y Mobile App tendrán funcionalidades que se agrupan por temas como "Perfil", "Viajes", "Notificaciones" y "Soporte".


- **Categorización por Audiencia:** Vamos a diferenciar claramente entre la Web App (para supervisores) y la Mobile App (para conductores), con funcionalidades específicas para cada grupo.

**Organización Cronológica:** Se aplica en la visualización de viajes y notificaciones, mostrando los más recientes o próximos primero.


### 5.2.2. Labeling Systems

Implementar Sistemas de Etiquetado efectivos es crucial para mejorar la experiencia del usuario. Esta sección detalla cómo representar los datos a través de etiquetas concisas e intuitivas, asegurando que los usuarios puedan navegar por la aplicación sin confusiones.

**Consideraciones para el Sistemas de Etiquetado**

- **Simplicidad:** Las etiquetas deben ser directas y fácilmente comprensibles para el público objetivo (supervisores y conductores). Evitar el uso de jergas y optar por una terminología común que sea fácil de entender por los usuarios.

- **Consistencia:** Utilizar un etiquetado consistente en todas las plataformas (web y móvil) para crear una experiencia de usuario fluida. Esto ayudará a los usuarios a familiarizarse con la interfaz, reduciendo la carga cognitiva.

- **Claridad:** Cada etiqueta debe indicar claramente su función o la información a la que llevará. Se debe evitar términos ambiguos que puedan confundir a los usuarios.

<br>

**Etiquetas para la Landing Page**

- Llamada a la Acción: "Comienza Ahora" o "Descubre Más"

- Características: Seguridad, Contacto Fácil, Precio Justo

- Beneficios:

  - GPS en Tiempo Real

  - Fácil de Usar

  - Planificación en Calendario

  - Soporte 24/7

  - Alertas y Notificaciones

  - Función de Búsqueda

<br>

**Aplicación Web (Funciones del Supervisor)**
- Acciones del Usuario:

  - Registrarse

  - Iniciar Sesión

  - Recuperar Contraseña

  - Ver Estado del Viaje Actual

  - Editar Perfil

  - Asignar Viaje

  - Ver Viajes por Estado

  - Notificaciones

  - Contactar Soporte

<br>

**Aplicación Móvil (Funciones del Conductor)**

- Acciones del Usuario:

  - Registrarse

  - Iniciar Sesión

  - Recuperar Contraseña

  - Editar Perfil

  - Información del Viaje Actual

  - Notificaciones de Viaje

  - Ver Viajes por Estado

  - Contactar Soporte


### 5.2.3. SEO Tags and Meta Tags

Para optimizar la presencia en línea de la solución de software FastPorte, es esencial implementar correctamente los SEO Tags y Meta Tags en las principales páginas de tu experiencia digital, tanto en la Landing Page como en la Aplicación Web. A continuación, se presentan las etiquetas recomendadas junto con sus valores asignados.

**Landing Page**

Title:
  - &lt;title&gt;FastPorte: Transporte Seguro de Materiales Peligrosos&lt;/title&gt;

Meta Description:
  - &lt;meta name="description" content="¿Necesitas transportar materiales peligrosos de forma segura? FastPorte ofrece soluciones rápidas y confiables para el transporte."&gt;

Meta Keywords:
  - &lt;meta name="keywords" content="transporte seguro, materiales peligrosos, GPS, soporte 24/7"&gt;

Meta Author:
  - &lt;meta name="author" content="FastPorte Team"&gt;

<br>

**Aplicación Web**

Title:
  - &lt;title&gt;FastPorte: Plataforma de Gestión para Supervisores de Transporte&lt;/title&gt;

Meta Description:
  - &lt;meta name="description" content="Gestione el transporte de materiales peligrosos con FastPorte. Registre viajes, asigne conductores y reciba notificaciones en tiempo real."&gt;

Meta Keywords:
  - &lt;meta name="keywords" content="gestión de transporte, supervisión, asignación de viajes, notificaciones"&gt;

Meta Author:
  - &lt;meta name="author" content="FastPorte Team"&gt;

<br>

**Aplicaciones Móviles (ASO)**

Para las aplicaciones móviles que se publican en tiendas de aplicaciones, es importante considerar los elementos de Optimización para Tiendas de Aplicaciones (ASO):

App Title:
  - "FastPorte: Transporte Seguro"

App Keywords:
  - "transporte, materiales peligrosos, GPS, gestión"

App Subtitle:
  - "Soluciones rápidas y seguras para el transporte"

App Description:
  - "FastPorte es la aplicación ideal para supervisores y conductores de vehículos que transportan materiales peligrosos. Ofrece seguimiento GPS en tiempo real, gestión de viajes y soporte 24/7. Descarga ahora y mejora la seguridad en el transporte."

### 5.2.4. Searching Systems

En esta sección, se detallará los medios de ayuda que se brindarán a los usuarios para facilitar la búsqueda de datos dentro de la aplicación de FastPorte. La implementación de un sistema de búsqueda es esencial para evitar que los usuarios se sientan abrumados por el volumen de información disponible. A continuación, se especifican las opciones de búsqueda, los filtros disponibles y cómo se presentarán los datos después de realizar una búsqueda.

**Opciones de Búsqueda**

  **1. Búsqueda por Palabras Clave:**

  Los usuarios podrán ingresar palabras clave relacionadas con la información que buscan. Esta opción será útil para encontrar viajes, conductores o notificaciones específicas.
    
  Ejemplo: Un supervisor puede buscar "viaje urgente" para localizar rápidamente información sobre un viaje clasificado como urgente.

  **2. Búsqueda Avanzada:**

  Se ofrecerá una opción de búsqueda avanzada que permite a los usuarios combinar múltiples criterios para afinar sus resultados.

  Criterios disponibles:
    - Fecha del viaje
    - Estado del viaje (en curso, completado, cancelado)
    - Nombre del conductor
    - Tipo de material transportado

<br>

**Filtros Disponibles:** Para mejorar la experiencia de búsqueda, se implementarán filtros que permitirán a los usuarios restringir los resultados según sus necesidades específicas. Los filtros incluirán:

**Por Fecha:** Permite seleccionar un rango de fechas para visualizar viajes realizados en un período específico.

**Por Estado:** Opción para filtrar viajes según su estado actual (por ejemplo: "En curso", "Completado", "Cancelado").

**Por Conductor:** Filtro que permite seleccionar un conductor específico para ver solo sus viajes asignados.

**Por Tipo de Material:** Opción para filtrar según el tipo de material transportado (por ejemplo: "explosivos", "gases").

<br>

**Resultados:** Una vez que el usuario realiza una búsqueda, los resultados se presentarán en un formato claro y organizado:

**Lista de Resultados:** Cada resultado incluirá información relevante como:

  - ID del viaje
  - Nombre del conductor
  - Estado del viaje
  - Fecha y hora programada
  - Tipo de material transportado

**Opciones de Acción:** Cada entrada en la lista tendrá botones o enlaces para acciones rápidas, como "Ver Detalles", "Editar Viaje" o "Contactar Conductor".

**Paginación y Carga Dinámica:** Para evitar la sobrecarga visual, se implementará paginación o carga dinámica para mostrar un número limitado de resultados a la vez, permitiendo al usuario navegar fácilmente entre ellos.

### 5.2.5. Navigation Systems

En esta sección, se describen las acciones y técnicas que guiarán a los usuarios a través de la Landing Page y las aplicaciones tanto Web como Móvil, permitiéndoles cumplir sus objetivos e interactuar de manera satisfactoria con el producto. Un sistema de navegación efectivo es importante para garantizar que los usuarios puedan encontrar lo que necesitan sin frustraciones.

**Navegación en la Landing Page**

1. **Menú Principal**:
    
  - **Ubicación**: El menú principal estará ubicado en la parte superior de la página y será visible en todo momento.

  - **Elementos del Menú**:

    - Inicio
    - Características
    - Beneficios
    - Descarga
    - Contacto

  - **Interacción**: Los usuarios podrán hacer clic en cualquiera de estos elementos para ser redirigidos a secciones específicas de la página o a otras páginas relevantes.

2. **Llamada a la Acción (CTA)**:

  - Se incluirán botones prominentes como "Comienza Ahora" o "Descarga la App", que dirigirán a los usuarios a las páginas de registro o descarga.

  - Estos botones estarán ubicados estratégicamente para captar la atención del usuario y facilitar su interacción.

3. **Footer**:

  - El pie de página incluirá enlaces a redes sociales, información de contacto y políticas de privacidad, asegurando que los usuarios tengan acceso a información adicional sin perderse en la navegación.

<br>

**Navegación en la Aplicación Web**

1. **Barra de Navegación Lateral**:

  - **Ubicación**: Una barra lateral estará presente en todas las páginas de la aplicación web.

  - **Elementos de Navegación**:

    - Viajes Actuales
    - Historial de Viajes
    - Asignar Viaje
    - Perfil
    - Soporte

  - Esta barra permitirá a los supervisores acceder rápidamente a las diferentes secciones y funcionalidades de la aplicación.

2. **Breadcrumbs**:

  - Se implementarán Breadcrumbsen la parte superior de las páginas secundarias para mostrar al usuario su ubicación dentro del sistema y facilitar el regreso a secciones anteriores.

3. **Botones de Acción Rápida**:

  - En cada sección relevante, se incluirán botones destacados para acciones comunes, como "Agregar Nuevo Viaje" o "Ver Notificaciones", permitiendo un acceso rápido y eficiente.

<br>

**Navegación en la Aplicación Móvil**

1. **Menú Hamburguesa**:

  - La aplicación móvil utilizará un menú hamburguesa (icono con tres líneas) ubicado en la parte superior izquierda para acceder a las principales secciones.

  - Este menú incluirá opciones similares a las de la aplicación web, adaptadas al formato móvil.

2. **Interfaz Táctil Intuitiva**:

  - Los elementos interactivos estarán diseñados para ser fácilmente accesibles mediante toques, con botones grandes y espaciados adecuadamente para evitar errores al seleccionar opciones.

3. **Navegación por Tarjetas**:

  - Los resultados de los viajes y notificaciones se presentarán en formato de tarjetas, permitiendo a los usuarios deslizarse entre ellas fácilmente y acceder rápidamente a detalles adicionales.


## 5.3. Landing Page UI Design

En el siguiente apartado se abordará el diseño de la interfaz de usuario de la página de aterrizaje, la primera impresión visual y funcional que los usuarios tienen al interactuar con un sitio web. Este diseño tiene como objetivo captar la atención, guiar a los usuarios hacia una acción específica y ofrecer una experiencia intuitiva. Se enfoca en la disposición efectiva de los elementos visuales, como los llamados a la acción (CTAs), contenido relevante y diseño responsivo, asegurando que la página sea atractiva, fácil de navegar y optimizada para convertir visitantes en usuarios o clientes de FastPorte.

### 5.3.1. Landing Page Wireframe

Se han designado 5 secciones principales para la realización del Landing Page. En primer lugar, la sección Principal, la cual será la primera que verá el visitante de la página. En está sección se realiza una pregunta para llamar la atención de los visitantes sobre sus necesidades específicas. Asimismo, se agrega un botón como *Call to Action* para que puedan acceder a las soluciones que se han desarrollado. En segundo lugar, la sección Características donde se detalla los aspectos más importantes de la aplicación y lo que ofrece la Startup. Además, en esta sección se visualiza los beneficios generales para brindar mayor detalle sobre FastPorte y lo que ofrece para cada tipo de usuario. En tercer lugar, la sección Descarga donde se presenta el *Call to Action* principal mostrando la disponibilidad de FastPorte en dispositivos móviles también. En cuarto lugar, la sección Sobre nosotros donde los visitantes podrán conocer quienes son los creadores de FastPorte. Igualmente, podrá visualizar los testimonios de gente que ya ha usado FastPorte con anterioridad y como les ha servido. Finalmente, la sección Contáctanos la cual ofrece un formulario para poder contactarse con FastPorte con el fin de solicitar información o contratar los servicios.

![Landing Page Wireframe](assets/capitulo5/landing_page_wireframe.png)

De igual modo se diseño los Wireframes para la versión mobile con el objetivo de que este disponible una versión responsive de la página de aterrizaje.

![Landing Page Wireframe Mobile](assets/capitulo5/landing_page_wireframe_mobile.png)

Enlace a Figma: [Landing Page Wireframes](https://www.figma.com/design/eLXz5gA2bvN7AgWFRqQbAv/Landing-Page?node-id=6-379)

### 5.3.2. Landing Page Mock-up

A continuación, se muestra la representación visual detallada de cómo se verá y funcionará la página de aterrizaje del sitio web de FastPorte. Este prototipo estático ofrece una vista previa del diseño final, permitiendo a los diseñadores y partes interesadas evaluar la disposición de los elementos, la jerarquía visual y la estética general antes de pasar a la fase de desarrollo. El _mock-up_ es clave para garantizar que la estructura, los colores, las tipografías y los componentes interactivos se alineen con los objetivos de la página, facilitando correcciones tempranas y decisiones basadas en una visión clara del producto final.

![Landing Page Mock-up](assets/capitulo5/landing_page_mockup.png)

Enlace a Figma: [Landing Page Mock-up](https://www.figma.com/design/eLXz5gA2bvN7AgWFRqQbAv/Landing-Page?node-id=0-1)

## 5.4. Applications UX/UI 

En el siguiente apartado se centrará en la creación de interfaces y experiencias de usuario optimizadas para la aplicación FastPorte, con el fin de garantizar que sean intuitivas, atractivas y fáciles de usar. El diseño de UX (Experiencia de Usuario) se enfoca en cómo los usuarios interactúan con la aplicación, priorizando su satisfacción mediante una navegación eficiente y la resolución de problemas de manera lógica. Por otro lado, el diseño de UI (Interfaz de Usuario) se ocupa de la parte visual, asegurando que los elementos gráficos sean atractivos y estén bien organizados. Juntos, estos enfoques crean aplicaciones que no solo cumplen con los objetivos funcionales, sino que también ofrecen una experiencia agradable y coherente para el usuario. 

### 5.4.1. Applications Wireframes

En este apartado se presentan los wireframes de la aplicación FastPorte, los cuales representan el esquema visual básico de la interfaz tanto en su versión móvil como web. Estos diagramas permiten visualizar la estructura y disposición de los elementos clave en cada pantalla, proporcionando una base sólida para el diseño final de la aplicación.

##### Mobile application

Se ha considerado el diseño de la aplicación móvil para que sea intuitiva y fácil de usar, con una interfaz sencilla y clara que permita a los conductores y supervisores acceder rápidamente a la información relevante y realizar las tareas necesarias de manera eficiente. Los wireframes de la aplicación móvil incluyen las siguientes pantallas:

![Wireframes mobile](./assets/capitulo5/wireflow/mobile%20app/Wireframes.png)

Enlace a Figma: [Wireframes - Mobile application](https://www.figma.com/design/OsXsqDb70Sp5wVdhIor56G/FastPorte-IOT?node-id=4187-1551)

##### Web application

La versión web de la aplicación FastPorte ha sido diseñada para proporcionar una experiencia de usuario similar a la de la aplicación móvil, pero adaptada a las necesidades y preferencias de los usuarios que prefieren acceder a la plataforma desde un navegador de escritorio. Los wireframes de la aplicación web incluyen las siguientes pantallas:

![Wireflow web](./assets/capitulo5/wireflow/web%20app/Wireframes.png)

Enlace a Figma: [Wireframes - Web application](https://www.figma.com/design/OsXsqDb70Sp5wVdhIor56G/FastPorte-IOT?node-id=0-1)

A continuación, se mostrarán los wireframes realizados para cada tipo de dispositivo:


**Sing In: Inicio de sesión en la aplicación FastPorte**

- Versión web: 

![Web App Sign In](assets/capitulo5/WebFastPorteWireframes/SignIn.png)

- Versión móvil:

![Mobile Sign In](assets/capitulo5/MobileFastPorteWireframes/SignIn.png)

**Sign Up: Registro en la aplicación FastPorte**

- Versión web: 

1. Ingreso del código de sensor

![Web App Sign Up - Sensor Code](assets/capitulo5/WebFastPorteWireframes/Signup-SensorCode.png)

2. Elección del tipo de usuario

![Web App Sign Up - User Type](assets/capitulo5/WebFastPorteWireframes/Signup-UserType.png)

3. Registro de usuario

![Web App Sign Up - Register](assets/capitulo5/WebFastPorteWireframes/Signup-Register.png)

4. Ingreso de datos básicos

![Web App Sign Up - Basic Data](assets/capitulo5/WebFastPorteWireframes/Signup-FillInformation.png)

- Versión móvil:

1. Ingreso del código de sensor

![Mobile Sign Up - Sensor Code](assets/capitulo5/MobileFastPorteWireframes/Signup-SensorCode.png)

2. Elección del tipo de usuario

![Mobile Sign Up - User Type](assets/capitulo5/MobileFastPorteWireframes/Signup-UserType.png)

3. Registro de usuario

![Mobile Sign Up - Register](assets/capitulo5/MobileFastPorteWireframes/Signup-Register.png)

4. Ingreso de datos básicos

![Mobile Sign Up - Basic Data](assets/capitulo5/MobileFastPorteWireframes/Signup-FillInformation.png)

**Forgot Password: Recuperar contraseña de la cuenta**

- Versión web: 

1. Ingreso del correo electrónico

![Web App Forgot Password - Send Email](assets/capitulo5/WebFastPorteWireframes/ForgotPassword-SendEmail.png)

2. Ingreso de nueva contraseña

![Web App Forgot Password - New Password](assets/capitulo5/WebFastPorteWireframes/ForgotPassword-NewPassword.png)

- Versión móvil:

1. Ingreso del correo electrónico

![Mobile Forgot Password - Send Email](assets/capitulo5/WebFastPorteWireframes/ForgotPassword-SendEmail.png)

2. Ingreso de nueva contraseña

![Mobile Forgot Password - New Password](assets/capitulo5/WebFastPorteWireframes/ForgotPassword-NewPassword.png)

**Home: Página de inicio de la aplicación FastPorte**

- Versión web (Conductor):

1. Página de inicio sin viajes

![Web App Home - No Trips](assets/capitulo5/WebFastPorteWireframes/Home-NoTrips-Conductor.png)

2. Página de inicio con viaje pendiente

![Web App Home - Trips](assets/capitulo5/WebFastPorteWireframes/Home-TripOk-Conductor.png)

- Versión web (Supervisor):

1. Página de inicio sin viajes

![Web App Home - No Trips](assets/capitulo5/WebFastPorteWireframes/Home-NoTrips-Supervisor.png)

2. Página de inicio con viaje pendiente

![Web App Home - Trips](assets/capitulo5/WebFastPorteWireframes/Home-TripOk-Supervisor.png)

- Versión móvil (Conductor):

1. Página de inicio sin viajes

![Web App Home - No Trips](assets/capitulo5/MobileFastPorteWireframes/Home-NoTrips-Conductor.png)

2. Página de inicio con viaje pendiente

![Web App Home - Trips](assets/capitulo5/MobileFastPorteWireframes/Home-TripOk-Conductor.png)

- Versión móvil (Supervisor):

1. Página de inicio sin viajes

![Mobile Home - No Trips](assets/capitulo5/MobileFastPorteWireframes/Home-NoTrips-Supervisor.png)

2. Página de inicio con viaje pendiente

![Mobile Home - Trips](assets/capitulo5/MobileFastPorteWireframes/Home-TripOk-Supervisor.png)

**Notifications: Página de notificaciones de la aplicación FastPorte**

- Versión web (Conductor):

1. Notificación de viaje asignado

![Web App Notifications - Trip Assigned](assets/capitulo5/WebFastPorteWireframes/Notifications-TripAssigned-Conductor.png)

2. Notificación de viaje cancelado

![Web App Notifications - Trip Cancelled](assets/capitulo5/WebFastPorteWireframes/Notifications-TripCancelled-Conductor.png)

- Versión web (Supervisor):

1. Notificación de viaje finalizado

![Web App Notifications - Trip Finished](assets/capitulo5/WebFastPorteWireframes/Notifications-TripFinished-Supervisor.png)

2. Notificación de viaje creado

![Web App Notifications - Trip Created](assets/capitulo5/WebFastPorteWireframes/Notifications-TripCreated-Supervisor.png)

- Versión móvil (Conductor):

1. Notificación de viaje asignado

![Mobile Notifications - Trip Assigned](assets/capitulo5/MobileFastPorteWireframes/Notifications-TripAssigned-Conductor.png)

2. Notificación de viaje cancelado

![Mobile Notifications - Trip Cancelled](assets/capitulo5/MobileFastPorteWireframes/Notifications-TripCancelled-Conductor.png)

- Versión móvil (Supervisor):

1. Notificación de viaje finalizado

![Mobile Notifications - Trip Finished](assets/capitulo5/MobileFastPorteWireframes/Notifications-TripFinished-Supervisor.png)

2. Notificación de viaje creado

![Mobile Notifications - Trip Created](assets/capitulo5/MobileFastPorteWireframes/Notifications-TripCreated-Supervisor.png)

**Trips: Página sobre los servicios de transporte de la aplicación FastPorte**

- Versión web (Conductor):

1. Página de viajes pendientes

![Web App Trips - Pending Trips](assets/capitulo5/WebFastPorteWireframes/Trips-PendingTrips-Conductor.png)

2. Página de viajes finalizados (historial)

![Web App Trips - Finished Trips](assets/capitulo5/WebFastPorteWireframes/Trips-FinishedTrips-Conductor.png)

- Versión web (Supervisor):

1. Página de viajes pendientes

![Web App Trips - Pending Trips](assets/capitulo5/WebFastPorteWireframes/Trips-PendingTrips-Supervisor.png)

2. Página de viajes finalizados (historial)

![Web App Trips - Finished Trips](assets/capitulo5/WebFastPorteWireframes/Trips-FinishedTrips-Supervisor.png)

- Versión móvil (Conductor):

1. Página de viajes pendientes

![Mobile Trips - Pending Trips](assets/capitulo5/MobileFastPorteWireframes/Trips-PendingTrips-Conductor.png)

2. Página de viajes finalizados (historial)

![Mobile Trips - Finished Trips](assets/capitulo5/MobileFastPorteWireframes/Trips-FinishedTrips-Conductor.png)

- Versión móvil (Supervisor):

1. Página de viajes pendientes

![Mobile Trips - Pending Trips](assets/capitulo5/MobileFastPorteWireframes/Trips-PendingTrips-Supervisor.png)

2. Página de viajes finalizados (historial)

![Mobile Trips - Finished Trips](assets/capitulo5/MobileFastPorteWireframes/Trips-FinishedTrips-Supervisor.png)

**Edit Profile: Editar información básica del perfil**

- Versión web (Conductor):

1. Menú de opciones

![Web App Edit Profile - Menu](assets/capitulo5/WebFastPorteWireframes/EditProfile-Menu-Conductor.png)

2. Editar información básica

![Web App Edit Profile - Basic Information](assets/capitulo5/WebFastPorteWireframes/EditProfile-BasicInformation-Conductor.png)

- Versión web (Supervisor):

1. Menú de opciones

![Web App Edit Profile - Menu](assets/capitulo5/WebFastPorteWireframes/EditProfile-Menu-Supervisor.png)

2. Editar información básica

![Web App Edit Profile - Basic Information](assets/capitulo5/WebFastPorteWireframes/EditProfile-BasicInformation-Supervisor.png)

- Versión móvil (Conductor):

1. Menú de opciones

![Mobile Edit Profile - Menu](assets/capitulo5/MobileFastPorteWireframes/EditProfile-Menu-Conductor.png)

2. Editar información básica

![Mobile Edit Profile - Basic Information](assets/capitulo5/MobileFastPorteWireframes/EditProfile-BasicInformation-Conductor.png)

- Versión móvil (Supervisor):

1. Menú de opciones

![Mobile Edit Profile - Menu](assets/capitulo5/MobileFastPorteWireframes/EditProfile-Menu-Supervisor.png)

2. Editar información básica

![Mobile Edit Profile - Basic Information](assets/capitulo5/MobileFastPorteWireframes/EditProfile-BasicInformation-Supervisor.png)

**Support: Página de soporte de la aplicación FastPorte**

- Versión web (Conductor):

![Web App Support - Conductor](assets/capitulo5/WebFastPorteWireframes/Support-Conductor.png)

- Versión web (Supervisor):

![Web App Support - Supervisor](assets/capitulo5/WebFastPorteWireframes/Support-Supervisor.png)

- Versión móvil (Conductor):

![Mobile Support - Conductor](assets/capitulo5/MobileFastPorteWireframes/Support-Conductor.png)

- Versión móvil (Supervisor):

![Mobile Support - Supervisor](assets/capitulo5/MobileFastPorteWireframes/Support-Supervisor.png)

**Drivers: Página para la búsqueda de conductores y gestión del itinerario de viajes**

_Esta sección se solo se encuentra disponible para los usuarios de tipo Supervisor._

- Versión web:

1. Búsqueda de conductores

![Web App Drivers - Search Driver](assets/capitulo5/WebFastPorteWireframes/Drivers-SearchDriver.png)

2. Gestión del itinerario de viajes

![Web App Drivers - Trip Management](assets/capitulo5/WebFastPorteWireframes/Drivers-TripManagement.png)

- Versión móvil:

1. Búsqueda de conductores

![Mobile Drivers - Search Driver](assets/capitulo5/MobileFastPorteWireframes/Drivers-SearchDriver.png)

2. Gestión del itinerario de viajes

![Mobile Drivers - Trip Management](assets/capitulo5/MobileFastPorteWireframes/Drivers-TripManagement.png)

### 5.4.2. Applications Wireflow Diagrams
### 5.4.4. Applications Mock-ups
### 5.4.4. Applications User Flow Diagrams

En esta sección se presentan los user flows de la aplicación FastPorte, los cuales muestran de manera detallada los diferentes caminos que los usuarios pueden tomar al interactuar con la plataforma. Estos diagramas representan las decisiones y acciones clave que los usuarios, en sus distintos roles, realizan para completar tareas específicas dentro de la aplicación. Los user flows son fundamentales para entender cómo se desarrollan las interacciones y para identificar posibles mejoras en la experiencia de usuario. A continuación, se detallan los user flows correspondientes a los roles de Conductor y Supervisor:

##### Conductor

Para el user flow del Conductor, se ha decidido utilizar la versión móvil, ya que esta será la principal herramienta que emplearán. A continuación, se describen los user goals correspondientes y sus respectivos user flows:

###### UG01: Registrarse en la aplicación

El conductor accede a la aplicación y selecciona la opción de registrarse. Luego de ello, se le pedirá ingresar un código que corresponde al sensor que se le ha asignado. Si es un código válido, se le redireccionará a la siguiente pantalla, caso cantrario, se le pedirá que ingrese uno correcto. Posteriormente, deberá elegir su tipo de perfil, en este caso conductor. Luego completará la información de su nueva cuenta con campos como email y contraseña, los cuáles serán validados para que pueda pasar a la siguiente pantalla. Por último, deberá ingresar información personal como nombre y número de teléfono y aceptar los términos y condiciones de la aplicación. Una vez rellenados los campos procederá a darle en el botón de Sign up y si ha completado de manera correcta los campos, se le mostrará un mensaje de que la cuenta se ha creado con éxito, caso contrario, se le pedirá que ingrese campos válidos.

![Userflow_Conductor_1](./assets/capitulo5/userflow/mobile%20app/Conductor_1.png)

###### UG02: Iniciar sesión en la aplicación

El conductor accede a la aplicación, se le muestra el formulario de iniciar sesión donde deberá ingresar su correo electrónico y contraseña. Si los datos son correctos, se le redirigirá a la pantalla principal de la aplicación, caso contrario, se le mostrará un mensaje de error. Una vez en la pantalla principal, podrá acceder a las diferentes secciones de la aplicación.

![Userflow_Conductor_2](./assets/capitulo5/userflow/mobile%20app/Conductor_2.png)

###### UG03: Recuperar contraseña de la cuenta

En caso de olvidar su contraseña, el conductor podrá recuperarla ingresando su correo electrónico. Si es un correo válido, se le redirigirá a la pantalla de recuperación de contraseña donde deberá ingresar un nuevo password y confirmarlo. Si los datos son correctos, se le mostrará un mensaje de que la contraseña ha sido actualizada con éxito, caso contrario, se le pedirá que ingrese datos válidos.

![Userflow_Conductor_3](./assets/capitulo5/userflow/mobile%20app/Conductor_3.png)

###### UG04: Editar información básica del perfil

El conductor podrá editar su información personal y de contacto en cualquier momento. Para ello, deberá desplegar el pequeño menú en l parte superior derecha de la app móvil, seleccionar la opción de perfil y posteriormente la opción de editar. Luego podrá modificar los campos que desee y guardar los cambios realizados. Si los datos son correctos, se le mostrará un mensaje de que la información ha sido actualizada con éxito, caso contrario, se le pedirá que ingrese datos válidos.

![Userflow_Conductor_4](./assets/capitulo5/userflow/mobile%20app/Conductor_4.png)

###### UG05: Visualizar información del viaje en curso

Al iniciar sesión, el conductor podrá ver dos posibles vistas: en caso no esté en un viaje en curso, se le mostrarán sus viajes recientes en la pantalla de home. En caso de estar en un viaje, podrá visualizar la información del mismo, como el origen y destino. Pero principalmente podrá ver la información del sensor que lleva consigo, como la temperatura y la presión, si hay fuga de gas y el nivel de humedad.

![Userflow_Conductor_5](./assets/capitulo5/userflow/mobile%20app/Conductor_5.png)

###### UG06: Revisar notificaciones sobre viajes

Al estar en la pantalla principal y abrir el menú de opciones, el conductor podrá acceder a la sección de notificaciones. Si tiene notificaciones podrá ver mensajes sobre si le han asignado algún viaje o si han cancelado alguno que tenía programado. En caso de no tener notificaciones, se le mostrará un mensaje de que no tiene notificaciones recientes.

![Userflow_Conductor_6](./assets/capitulo5/userflow/mobile%20app/Conductor_6.png)

###### UG07: Visualizar los viajes por estado

Desde el menú de opciones, el conductor podrá visualizar el apartado de viajes. Si tiene viajes pendientes, le aparecerá un listado con los detalles de cada uno, como el origen, destino, fecha y hora. En caso de no tener viajes pendientes, se le mostrará un mensaje de que no tiene viajes pendientes. Luego, para acceder al historial de viajes, tendrá que tocar en History y se le mostrará un listado con los viajes que ha realizado en caso de tenerlos, caso contrario, se le mostrará un mensaje de que no tiene historial de viajes.

![Userflow_Conductor_7](./assets/capitulo5/userflow/mobile%20app/Conductor_7.png)

###### UG08: Obtener contactos de soporte de la app

Si el conductor requiere asistencia o soporte técnico, podrá acceder a la sección de soporte dentro de la aplicación, donde se le proporcionará el número de teléfono y el correo electrónico del equipo de soporte técnico para resolver cualquier duda.

![Userflow_Conductor_8](./assets/capitulo5/userflow/mobile%20app/Conductor_8.png)

Enlace a Lucidchart: [Userflows - Conductor](https://lucid.app/lucidchart/bee2da3c-eaf6-41b4-aa3c-b9cbfc69825e/edit?viewport_loc=-10846%2C5056%2C19159%2C9384%2CpCrbmlS9wx4U&invitationId=inv_cb01a0c3-90db-4460-b553-8d064ac80e6b)

#### Supervisor

Para el userflow del Supervisor, se ha decidido utilizar la versión web, ya que esta será la principal herramienta que emplearán. A continuación, se describen los user goals correspondientes y sus respectivos user flows:

##### UG09:  Registrarse en la aplicación  

El supervisor ingresa a la aplicación y selecciona la opción de registro. A continuación, se le solicitará ingresar un código que corresponde al sensor asignado a uno de los conductores bajo su supervisión. Si el código es válido, se le llevará a la siguiente pantalla; de lo contrario, deberá ingresar un código correcto. Después, seleccionará su tipo de perfil, en este caso, supervisor, y completará su información personal y de contacto. Además, tendrá que aceptar los términos y condiciones de la aplicación. Finalmente, confirmará la creación de su cuenta como supervisor. Si todos los datos ingresados son correctos, aparecerá un mensaje indicando que la cuenta ha sido creada exitosamente; de lo contrario, se le solicitará corregir los datos ingresados.

![Userflow_Supervisor_9](./assets/capitulo5/userflow/web%20app/Supervisor_9.png)

##### UG10:  Iniciar sesión en la aplicación  

El supervisor accede a la aplicación y se le muestra el formulario de inicio de sesión, donde deberá ingresar su correo electrónico y contraseña. Si los datos son correctos, se le redirigirá a la pantalla principal de la aplicación; de lo contrario, se le mostrará un mensaje de error. Una vez en la pantalla principal, podrá acceder a las diferentes secciones de la aplicación disponibles para su rol de supervisor.

![Userflow_Supervisor_10](./assets/capitulo5/userflow/web%20app/Supervisor_10.png)

##### UG11:  Recuperar contraseña de la cuenta  


Si el supervisor olvida su contraseña, podrá restablecerla ingresando su correo electrónico. Si el correo es válido, será dirigido a la pantalla de recuperación de contraseña, donde deberá ingresar y confirmar una nueva contraseña. Si los datos ingresados son correctos, recibirá un mensaje confirmando que la contraseña ha sido actualizada exitosamente; de lo contrario, se le pedirá que corrija la información proporcionada.

![Userflow_Supervisor_11](./assets/capitulo5/userflow/web%20app/Supervisor_11.png)

##### UG12:  Visualizar estado del viaje en curso  

El supervisor accede a la aplicación e inicia sesión ingresando sus credenciales. Una vez autenticado, el sistema verifica si hay un viaje en curso; si lo hay, se revisa si existe alguna incidencia con el sensor asignado al conductor. En caso de haber una incidencia, se muestra una alerta en la pantalla de reporte del viaje, de lo contrario, el reporte del viaje se presenta sin alertas. Si no hay ningún viaje en curso, el supervisor es redirigido a la pantalla principal, donde puede ver a sus conductores y los viajes recientes.

![Userflow_Supervisor_12](./assets/capitulo5/userflow/web%20app/Supervisor_12.png)

##### UG13:  Editar información del perfil  

El supervisor accede a la pantalla principal de la aplicación, donde puede visualizar sus conductores asignados y los viajes recientes. Desde el menú de su perfil, selecciona la opción para editar su información. Al hacerlo, es redirigido a la pantalla de edición de perfil, donde puede modificar su nombre, correo electrónico, contraseña y número de teléfono. Tras realizar los cambios, el sistema valida los campos ingresados; si son correctos, se actualiza la información del perfil con éxito, de lo contrario, se le solicita ingresar datos válidos antes de proceder.

![Userflow_Supervisor_13](./assets/capitulo5/userflow/web%20app/Supervisor_13.png)

##### UG14:  Asignar un viaje a un conductor  

Desde la pantalla de inicio, el supervisor accede manualmente a la opción de "Drivers" para buscar conductores disponibles. Si ya tiene conductores asignados, procede a seleccionar uno para programar un viaje. En la pantalla de programación, el supervisor completa los detalles del viaje. Si el formulario se completa correctamente, se envía una notificación al conductor con los detalles del viaje y se muestra un mensaje de confirmación. Si hay errores en el formulario, el sistema solicita corregir los campos antes de enviar la notificación.

![Userflow_Supervisor_14](./assets/capitulo5/userflow/web%20app/Supervisor_14.png)

##### UG15:  Visualizar los viajes por estado  

El supervisor accede a la opción de "Trips" desde la pantalla de inicio para visualizar los viajes según su estado. Si existen viajes pendientes, se mostrarán en la sección "Pending Trips" con opciones para finalizar o cancelar. Si no hay viajes pendientes, se mostrará un mensaje indicando que no hay viajes en curso. En la sección "History", el supervisor podrá revisar los viajes completados, y si no ha supervisado ninguno, verá un mensaje indicando que el historial está vacío.

![Userflow_Supervisor_15](./assets/capitulo5/userflow/web%20app/Supervisor_15.png)

##### UG16:  Visualizar notificaciones

El supervisor accede a la pantalla principal de la aplicación y el sistema verifica si tiene notificaciones. Si hay notificaciones pendientes, el supervisor puede hacer clic en el ícono de notificaciones y revisarlas. Si no existen notificaciones, se le mostrará un mensaje diciendo que no tiene notificaciones recientes.

![Userflow_Supervisor_16](./assets/capitulo5/userflow/web%20app/Supervisor_16.png)

##### UG17:  Obtener contacto del soporte

El supervisor accede a la pantalla principal de la aplicación y selecciona la opción "Support" desde el menú superior. Al hacerlo, es redirigido a una pantalla donde se le muestra la información de contacto del equipo de soporte, que incluye un correo electrónico, número de teléfono y enlaces a las redes sociales. Además, se le ofrece la opción de enviar un mensaje directo a través de un botón en la misma pantalla.

![Userflow_Supervisor_17](./assets/capitulo5/userflow/web%20app/Supervisor_17.png)

Enlace a Figma: [Userflows - Supervisor](https://lucid.app/lucidchart/bee2da3c-eaf6-41b4-aa3c-b9cbfc69825e/edit?viewport_loc=-6599%2C16162%2C13775%2C6747%2CTCrb9ORHf_s2&invitationId=inv_cb01a0c3-90db-4460-b553-8d064ac80e6b)

## 5.5. Applications Prototyping

En esta sección se presentan los prototipos de la interfaz de usuario (UI) para navegadores web en desktop y dispositivos móviles, diseñados con simulaciones de interacción y navegación que reflejan los flujos de usuario propuestos en los diagramas de user flow. Las decisiones de interacción se han tomado en base a criterios de usabilidad y eficiencia, con el objetivo de optimizar la experiencia del usuario en la plataforma. Asimismo, se ha considerado la arquitectura de información para garantizar un sistema de navegación intuitivo, donde las interacciones sean claras y correspondan con las necesidades de cada rol. El sistema de navegación ha sido estructurado para facilitar la transición entre pantallas y accesos a funciones clave.

##### Mobile Application

![Mobile Application - Prototype](assets/capitulo5/prototype/Prototype_Mobile.png)

Enlace a Microsoft Stream (minuto 4:00): [Prototipo Móvil - FastPorte](https://upcedupe-my.sharepoint.com/personal/u20201b846_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201b846%5Fupc%5Fedu%5Fpe%2FDocuments%2Fupc%2Dpre%2D202402%2Dsi572%2DSW74%2DTechCompany%2Dprototype%20navigation%2Dsprint%2D1%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E79e8551e%2Dd211%2D4f7d%2Db08a%2D88829cdebbc7)

##### Web Application

![Web Application - Prototype](assets/capitulo5/prototype/Prototype_Web.png)

Enlace a Microsoft Stream (minuto 0:00): [Prototipo Web - FastPorte](https://upcedupe-my.sharepoint.com/personal/u20201b846_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201b846%5Fupc%5Fedu%5Fpe%2FDocuments%2Fupc%2Dpre%2D202402%2Dsi572%2DSW74%2DTechCompany%2Dprototype%20navigation%2Dsprint%2D1%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E79e8551e%2Dd211%2D4f7d%2Db08a%2D88829cdebbc7)

---

# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### **Project Management**
Se emplearon herramientas de software que permiten la comunicación en tiempo real y la edición rápida y compartida, lo que facilitó el trabajo eficiente. Algunas de las herramientas utilizadas fueron los servicios de Google (Drive, Documents, Meet) y Microsoft Outlook. Para el registro de versiones y la creación de repositorios se utilizó GitHub, una plataforma que permite registrar de manera ordenada cada uno de los commits realizados y Git  una herramienta que permite el control de versiones.

![github](assets/chapter6_img/github.jpg)

### **Product UX/UI Design**
Se utilizó Miro y UXPressia para el desarrollo de los segmentos objetivos y sus mapeos, así como para los As-Is y To-Be Scenario Maps. Para los mockups, wireframes, wireflows y el prototipo de la aplicación web se empleó Figma.

### **Software Development**
Para el desarrollo del software se utilizó Visual Studio Code, HTML, CSS, Bootstrap y Javascript. Visual Studio Code es un software que admite muchos lenguajes de programación, incluyendo HTML y CSS, y fue utilizado principalmente para el Landing Page. HTML se utilizó para el desarrollo de la estructura de las páginas web, CSS para el diseño y presentación, Bootstrap para crear interfaces más limpias y responsive, y Javascript para implementar la interactividad dinámica y animaciones en el Landing Page.<br>

![vscode](assets/chapter6_img/visual%20studio.png)

También se está desarrollando la aplicación móvil emppleando el framework Flutter, la cual es multiplataforma. Sin embargo, no se utiliza Flutter solo por su responsiveness, sino que se eligió por el uso de distintos componentes que permite darle una estética más personalizado. El lenguaje en uso para el desarrollo de la aplicación móvil es Dart.

![flutter](assets/chapter6_img/android%20studio.png)

Asimismo, se utilizo Angular para el desarrollo de la aplicación web, un framework progresivo de TypeScript que permite crear interfaces de usuario interactivas y dinámicas.

![angular](assets/chapter6_img/Angular.png)

Para el desarrollo del backend se utilizó JAVA, un lenguaje de programación extremadamente versátil. Se puede usar para programar software y aplicaciones para muchos sistemas operativos y dispositivos diferentes, incluidos dispositivos IoT, teléfonos móviles y equipos.

![java](assets/chapter6_img/Java-logo.png)


### **Software Testing**
Para los test de aceptación se utilizó el lenguaje Gherkin y se subió al repositorio mencionado anteriormente.

### **Software Deployment**
Para desplegar la Landing Page, al ser una página de contenido estático que no necesita muchas actualizaciones, se utilizó GitHub Pages, que es gratuito y permite actualizar el contenido cuando sea necesario.

### **Software Documentation**
La documentación del software se realizó mediante comentarios en los archivos HTML, ya que al utilizar HTML para el desarrollo del Landing Page, un lenguaje de marcado, no era necesario crear diagramas de clases u otros tipos de documentación.

### 6.1.2. Source Code Management

Para mantener el orden y evitar conflictos o superposiciones de información, los proyectos se trabajaron en una
organización de GitHub y dentro de esta se encuentran los diferentes repositorios para cada proyecto cuyos enlaces de los repositorios son los
siguientes:
1. Repositorio para el landing page: https://github.com/Debuggers-SW74/landing-page
2. Repositorio de la aplicación web: https://github.com/Debuggers-SW74/web-application
3. Repositorio del testing: https://github.com/Debuggers-SW74/testing-suite

Se utilizará GitFlow para la administración de versiones del proyecto, en concreto se hará uso de las ramas main, develop and feature.
+ Para cada commit que se realice, ya sea para el landing page o los archivos .feature, se utilizará el formato de mensaje "Conventional Commits" para ayudar a reconocer mejor lo que se hizo en los commits y de esta forma conocer mejor el estado del proyecto.
+ Cada repositorio de código tendrá sus respectivas ramas tal como lo describe Vincent Driessen, donde estará presente la rama Main (que almacenará las versiones estables y finales), Develop (donde se irán integrando los cambios implementados por cada feature y estará en constante actualización).
+ Además, para la creación de ramas feature se utilizará el formato, feature/< user story / technical story> y para los commits Se utilizara el siguiente formato para realizar los commits: < type>[optional scope]< optional sticker>: < description>
  [optional body]
  [optional footer(s)]

### 6.1.3. Source Code Style Guide & Conventions

A continuación, se mostrarán las pautas, convenciones, estilo y principios que se utilizarán para cada uno de los lenguajes de se emplearán en la creacion y desarrollo de nuestra aplicación. La práctica de este conjunto de reglas es de suma importancia, ya que estas tienen el propósito de conservar la calidad estructural del software, dar una mayor legibilidad al código fuente y facilitar el mantenimiento del código.

**HTML:**
+ Declarar siempre el tipo de documento con <! DOCTYPE html>.
+ Utilizar nombres de etiquetas y atributos en minúscula.
+ Cerrar todas las etiquetas.
+ Siempre utilizar comillas para los valores de los atributos.
+ Especificar los atributos alt, width y height para las imágenes.
+ No omitir la etiqueta < title> ni los metadatos (< meta>).
```
<!DOCTYPE html>
<html>
<head>
  <title>Example Page</title>
  <meta charset="UTF-8">
  <meta name="description" content="This is an example page">
</head>
<body>
  <img src="example.jpg" alt="Example Image" width="200" height="150">
</body>
</html>

```

**CSS:**
+ Usar nombres cortos y descriptivos para variables, funciones, etc.
+ Evitar el uso de variables globales (var).
+ Comentar líneas de código complejas para facilitar la comprensión.
+ Utilizar notaciones simples y comprensibles.

```
// Declaración de variables
let nombreUsuario: string = "Juan";

// Definición de función
function saludar(): string {
  return "Hola, " + nombreUsuario + "!";
}

// Uso de función
console.log(saludar());

```

**Dart:**
+ Usar nombres de clases, métodos y variables en minúsculas.
+ Utilizar nombres de clases en singular y en mayúscula.
+ Utilizar nombres de métodos y variables en minúscula.
+ Utilizar nombres de métodos en camelCase.
+ Utilizar nombres de variables en minúscula y separados por guiones bajos.
```
// Declaración de variable utilizando camelCase
String nombreUsuario = 'Juan';

// Definición de función utilizando camelCase
void saludar() {
  print('Hola, $nombreUsuario!');
}
```
**Angular:**
+ Usar nombres de componentes en singular y en mayúscula.
+ Utilizar nombres de métodos y variables en minúscula.
+ Seguir las convenciones de Angular para la estructura del proyecto, como el uso de componentes y la organización del código.
+ Utilizar la sintaxis de Angular de manera consistente en los archivos de componentes. Por ejemplo tener cada componente en una carpeta en donde este el .ts, .html y .css de cada componente.

```
//component.ts (typescript):
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
})
export class AppComponent {
  mensaje: string = 'Hola Mundo!';

  cambiarMensaje(): void {
    this.mensaje = '¡Hola Angular!';
  }
}

//component.html:

<div>
  <p>{{ mensaje }}</p>
  <button (click)="cambiarMensaje()">Cambiar Mensaje</button>
</div>

```
**JAVA:**

+ Usar nombres de variables y métodos en camelCase (por ejemplo, nombreVariable, miMetodo)
+ Utilizar nombres descriptivos y significativos para las variables y métodos.
+ Seguir las convenciones de Java para la estructura del proyecto, como el uso de paquetes y la organización del código. Por ejemplo, dividir la lógica de la aplicación en clases y mantener una estructura de carpetas lógica para los archivos de las clases.
+ Utilizar dependencias de Maven y gestionar las dependencias de manera adecuada. Por ejemplo, especificar las dependencias en un archivo *pom.xml* y utilizar estas herramientas para instalar y gestionar paquetes.

```
proyecto-java/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── ejemplo/
│   │   │           ├── Main.java
│   │   │           ├── controllers/
│   │   │           │   └── UsuarioController.java
│   │   │           ├── models/
│   │   │           │   └── UsuarioModel.java
│   │   │           └── routes/
│   │   │               └── UsuarioRoutes.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── ejemplo/
│                   └── UsuarioControllerTest.java
│
├── pom.xml
└── README.md
```

+ Seguir las convenciones de nomenclatura de Java para nombres de variables, clases, métodos y paquetes. Por ejemplo, utilizar camelCase para nombres de variables y métodos, UpperCamelCase para nombres de clases, y utilizar nombres descriptivos que reflejen el propósito de la entidad.
+ Utilizar comentarios Javadoc para documentar clases y métodos públicos. Esto es fundamental para proporcionar una descripción clara de la funcionalidad de las clases y métodos, así como para generar documentación automáticamente.
+ Organizar el código en paquetes lógicos y utilizar la convención de nombres de paquetes de dominio invertido para evitar conflictos de nombres. Por ejemplo, el nombre de paquete com.ejemplo.proyecto indica que el proyecto pertenece al dominio ejemplo.com.


```
package com.ejemplo.proyecto.modelo;

/**
 * Clase que representa un usuario en el sistema.
 */
public class Usuario {
    private String nombre;
    private int edad;
    
    /**
     * Constructor de la clase Usuario.
     * @param nombre El nombre del usuario.
     * @param edad La edad del usuario.
     */
    public Usuario(String nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    /**
     * Método para obtener el nombre del usuario.
     * @return El nombre del usuario.
     */
    public String getNombre() {
        return nombre;
    }
    
    /**
     * Método para establecer el nombre del usuario.
     * @param nombre El nuevo nombre del usuario.
     */
    public void setNombre(String nombre) {
        this.nombre = nombre;
    }
    
    /**
     * Método para obtener la edad del usuario.
     * @return La edad del usuario.
     */
    public int getEdad() {
        return edad;
    }
    
    /**
     * Método para establecer la edad del usuario.
     * @param edad La nueva edad del usuario.
     */
    public void setEdad(int edad) {
        this.edad = edad;
    }
    
    /**
     * Método para imprimir los datos del usuario.
     */
    public void imprimirDatos() {
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
    }
}
```
**Spring:**<br>
Se siguieron las convenciones y guías de estilo de código de la documentación oficial de Spring Boot y se destaca lo siguiente:
+ Uso de Anotaciones: Utilizar anotaciones como @Controller, @Service, @Repository y @Component para marcar clases y componentes
  específicos de Spring.
+ Convención de Paquetes: Organizar los archivos y clases en carpetas que representen la estructura lógica de la aplicación, como controladores,
  servicios, repositorios, etc.
+ Convención de Nombres en Bases de Datos: Utilizar la convención de nombres en bases de datos como snake_case para nombres de tablas y
  columnas. Spring Boot se encargará de mapear estos nombres a objetos Java.
+ Uso de Spring Data JPA: Emplear Spring Data JPA para simplificar la interacción con la capa de persistencia y bases de datos.
+ Uso de Inyección de Dependencias: Aplicar la inyección de dependencias utilizando el constructor de las clases.
+ Uso de @RestController: Usar la anotación @RestController para marcar controladores que devuelven datos en formato JSON.
+ Seguridad con Spring Security: Implementar la seguridad en la aplicación utilizando Spring Security para autenticación y autorización.

### 6.1.4. Software Deployment Configuration

En este punto, se dara a conocer el proceso de despliegue de las aplicaciones, así como la configuración de los servidores y la infraestructura necesaria para su correcto funcionamiento.

**Landing Page:**
Para desplegar la Landing Page, se utilizó GitHub Pages, una plataforma gratuita que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. El proceso de despliegue fue el siguiente:
1. Crear un repositorio en GitHub con el código de la Landing Page.
2. Acceder a la configuración del repositorio y habilitar GitHub Pages.

![github pages1](assets/chapter6_img/githubpagesLanding1.jpeg)
![github pages1](assets/chapter6_img/githubpagesLanding2.jpeg)

3. Seleccionar la rama y la carpeta de origen del sitio web.
4. Guardar la configuración y obtener la URL del sitio web desplegado.
5. Finalmente, acceder a la URL del sitio web para verificar que se haya desplegado correctamente.

![landing page desplegada](assets/chapter6_img/landingpagedeployed.png)

+ Enlace de la Landing Page desplegada: https://debuggers-sw74.github.io/landing-page/

## 6.2. Landing Page, Services & Applications Implementation
### 6.2.1. Sprint 1
#### 6.2.1.1. Sprint Planning 1

| Sprint #                          | 1                                      |
|-----------------------------------|----------------------------------------|
| Sprint Planning Background                                                 |
| Date                              | 2024-09-19                             |
| Time                              | 07:30 PM                               |
| Location                          | Reunion virtual durante la clase       |
| Prepared By                       | Lévano Cavero, Eduardo Sebastián       |
| Attendees                         | Josué Arrunátegui / Anthony Botello / Eduardo Chero / Sebastián Lévano / Claudio Moreno                            |
| Sprint n – 1 Review Summary       | Este es el primer Sprint, por lo que no hay un resumen anterior, sin embargo se aplicaron las correcciones notadas por el profesor.                                                             |
| Sprint n – 1 Retrospective Summary| Gracias a las observaciones del profesor, nos dimos cuenta de las deficiencias que teniamos, por lo que mejoramos los detalles para el proceso de desarrollo siguiendo las pautas Domain-Driven Design.                                                        |
| Sprint Goal & User Stories                                                 |
| Sprint n Goal                     | Nos centramos en el desarrollo del      sitio web que sirve como presentación. Creemos que ofrece una visión de FastPorte y de cómo el producto puede satisfacer las necesidades de la empresa. Esto se confirmará cuando nos contacten para solicitar nuestros servicios.                                                                   |
| Sprint n Velocity                 | 30                                     |
| Sum of Story Points               | 30                                     |

#### 6.2.1.2. Sprint Backlog 1

Para este Sprint nos enfocamos en el desarrollo de la Landing page y una face inicial de la app web. <br>
[Enlace del tablero en Trello](https://trello.com/b/cydCcpde)

| Sprint # | Sprint 1 | | | | | |                                            |
|----------|----------|-|-|-|-|-|--------------------------------------------|
| User Story | | Work-Item / Task |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-do / InProcess / ToReview / Done)                                 |
| 1  | Registro de supervisor de la empresa | 1 | Regstro supervisor | Se desarrollara una opcion para registrarse como supervisor para sus labores | 3 |  Sebastián Lévano | Done |
| 2  | Registro de conductor | 2 | Regstro conductor | Se desarrollara la opcion para q el conductor se pueda registrar | 3 | Sebastián Lévano | Done |
| 3  | Inicio de sesión | 3 | Inicio sesion | Creación de la vista de inicio de sesión | 3 |  Sebastián Lévano | Done |
| 39 | Sección Principal | 4 | Home | Una vista principal para la landing page | 1 | Anthony Botello | Done |
| 40 | Sección Características | 5 | Features | Caracteristas de nuestro software | 1 | Claudio Moreno | Done |
| 41 | Sección Sobre Nosotros | 6 | About us | Seccion donde presentamos a los integrantes | 1 | Josué Arrunátegui | Done |
| 42 | Sección Descarga | 7 | Download | Seccion para descargar la app movil | 1 | Josué Arrunátegui | Done |
| 43 | Sección Contáctanos | 8 | Contact us | Seccion donde puede encontrar la informacion de contacto | 1 | Eduardo Chero | Done |

#### 6.2.1.3. Development Evidence for Sprint Review

Se completó la implementacion de la Landing-page, el desarrollo del header, caracteristicas, acerca de el equipo y el form para contacto y avance de la aplicación web en temas de registro e inicio de seción, apoyados de una fake API.

Tablero de commits del repositorio de la Landing-page:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body| Commited on (Date)                                                                       |                                       
|---------- |----------|-|-|-|-|
| Debuggers-SW74/landing-page | feature/home-section | fdea0458258f6c9f6a3c4faac2a20f0d44d62486 | feat: product section |   | 21/09/2024 |
|  | feature/future-section | 9bc86f40e0e8dd49d598e6162da9bb62b3059d10 | feat: benefits were added |  | 21/09/2024 |
|  | feature/contact-section | 15f2c2a1c1482e36083afb85877f4765763ff4b7 | feat: contact section and footer layout, feat: Add styles contact section, footer layout |   | 22/09/2024 |
|  | feature/details-section | 665ecc903f2cb39335a2b95992b8d6cce8c1a671  | refactor: merge |   | 23/09/2024 |
|  | feature/team-section | e6be5ae2c9c977c4efe95df440e5ff614a6b70fb | cta & team section |   | 23/09/2024 |

Tablero de commits del repositorio de la App web:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body| Commited on (Date)                                                                       |                                       
|---------- |----------|-|-|-|-|
| Debuggers-SW74 / web-application |  |   |   |   | |
|  |  |   |   |   | |
|  |  |   |   |   | |
|  |  |   |   |   | |
|  |  |   |   |   | |

#### 6.2.1.4. Testing Suite Evidence for Sprint Review

Para este Sprint se desarrollaron los test BDD para archivos .featrue usando el lenguaje Gherkin para cada User Story del srint

- us001.feature
  ```
  @registroSupervisor @Trello=https://trello.com/c/RxIS3ojW
  Feature: Registro de Supervisores
    Como supervisor de la empresa
    Quiero registrarme en la aplicación
    Para supervisar a los conductores a mi cargo


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Registro del supervisor con diferentes códigos de sensor
      Given que el supervisor de la empresa no está registrado
      And está en la vista inicial de la aplicación
      When ingresa el código del sensor <codigo_sensor> de un vehículo
      And selecciona la opción de registrarse como "Supervisor"
      And completa los datos requeridos correctamente
      Then el sistema registra al usuario como Supervisor
      And permite al usuario iniciar sesión con las credenciales creadas

      Examples:
        | codigo_sensor |
        | HRS491        |
        | TXM126        |


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Registro fallido con código de sensor ya usado
      Given que el supervisor de la empresa no está registrado
      And está en la vista inicial de la aplicación
      And el código del sensor <codigo_sensor> ya ha sido usado para registrar un Supervisor
      When ingresa el código del sensor <codigo_sensor> de un vehículo
      And selecciona la opción de registrarse como "Supervisor"
      And completa los datos requeridos correctamente
      Then el sistema le indica que ya se ha registrado un Supervisor para el código <codigo_sensor>

      Examples:
        | codigo_sensor |
        | HRS491        |
        | TXM126        |
  ```

- us002.feature
  ```
  @registroConductor @Trello=https://trello.com/c/u2YdrjjZ
  Feature: Registro de Conductores
    Como conductor
    Quiero registrarme en la aplicación
    Para recibir información de los viajes que debo realizar


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Registro del conductor con código de sensor correcto
      Given que el conductor no está registrado
      And se encuentra en la vista inicial de la aplicación
      When ingresa el código del sensor <codigo_sensor> de su vehículo
      And selecciona la opción de registrarse como "Conductor"
      And completa los datos requeridos correctamente
      Then el sistema registra al usuario como Conductor
      And permite al usuario iniciar sesión con las credenciales creadas

      Examples:
        | codigo_sensor |
        | CAR680        |
        | LLE382        |


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Registro fallido con código de sensor ya usado
      Given que el conductor no está registrado
      And está en la vista inicial de la aplicación
      And se ha usado el código del sensor <codigo_sensor> anteriormente para registrar un Conductor
      When ingresa el código del sensor <codigo_sensor> de un vehículo
      And selecciona la opción de registrarse como "Conductor"
      And completa los datos requeridos correctamente
      Then el sistema le indica que ya se ha registrado un Conductor para el código <codigo_sensor>

      Examples:
        | codigo_sensor |
        | CAR680        |
        | LLE382        |
  ```
- us003.feature
  ```
  @inicioSesionUsuario @Trello=https://trello.com/c/mN0aRbpr
  Feature: Inicio de sesión de usuarios en la aplicación
    Como usuario de la aplicación
    Quiero iniciar sesión en la aplicación
    Para acceder a las funcionalidades de la aplicación


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Inicio de sesión con credenciales correctas
      Given que el usuario de la aplicación desea iniciar sesión
      And está en la vista inicial de la aplicación
      When ingresa sus credenciales <correo> y <contraseña>
      Then el sistema permite al usuario acceder a las funcionalidades de la aplicación

      Examples:
        | correo                     | contraseña    |
        | jorge.supervisor@gmail.com | password1     |
        | mario.driver@gmail.com     | password2     |


  #-------------------------------------------------------------------------------------------
    Scenario Outline: Inicio de sesión fallido con credenciales incorrectas
      Given que el usuario de la aplicación desea iniciar sesión
      And está en la vista inicial de la aplicación
      When ingresa sus credenciales <correo> y <contraseña>
      And se ha equivocado en su correo o contraseña
      Then el sistema le indica que una de sus credenciales es incorrecta

      Examples:
        | correo                     | contraseña     |
        | joge.superviso@mail.com    | password1      |
        | mario.driver@gmail.com     | pasword2       |
  ```
- us040.feature
  ```
  @paginaDestino @Trello=https://trello.com/c/FrBzt0kY
  Feature: Información sobre características y beneficios en la página de destino
    Como visitante de la página de destino
    Quiero saber cuáles son las características y beneficios
    Para evaluar la contratación de este servicio


  #-------------------------------------------------------------------------------------------
    Scenario: Características del Producto
      Given que el visitante de la página se encuentra en la página de destino
      When se encuentre en la sección Características
      Then verá información adicional sobre las características principales de FastPorte


  #-------------------------------------------------------------------------------------------
    Scenario: Beneficios para cada segmento objetivo
      Given que el visitante de la página se encuentra en la página de destino
      And visualiza las características de FastPorte
      When deslice hacia abajo
      Then ve cuáles son los beneficios que se ofrecen para cada segmento objetivo
  ```
- us042.feature
  ```
  @descargarApp @Trello=https://trello.com/c/hO6H3kzT
  Feature: Descargar la aplicación móvil desde la página de destino
    Como visitante de la página de destino
    Quiero descargar la aplicación móvil
    Para visualizar la interfaz de esta


  #-------------------------------------------------------------------------------------------
    Scenario: Call to Action - Descargar la aplicación
      Given que el visitante de la página se encuentra en la página de destino
      When esté en la sección Descarga
      Then puede descargar la aplicación móvil dando click al botón "Descargar"
  ```
- us043.feature
  ```
  @contactarServicio @Trello=https://trello.com/c/FrBzt0kY
  Feature: Contacto desde la página de destino
    Como visitante de la página de destino
    Quiero contactarme con FastPorte
    Para obtener más información del producto


  #-------------------------------------------------------------------------------------------
  Scenario: Envío exitoso del formulario de contacto
    Given el visitante está en la página de destino de FastPorte
    And se desplaza hasta la sección "Contáctanos"
    When ingresa la siguiente información en el formulario:
      | Campo       | Valor                                        |
      | Nombre      | Juan Pérez                                   |
      | Email       | jorge.supervisor@gmail.com                   |
      | Tema        | Consulta sobre el servicio FastPorte         |
      | Mensaje     | Quisiera más información sobre sus servicios |
    And hace clic en el botón "Enviar mensaje"
    Then debería ver un mensaje de confirmación que diga "Mensaje enviado con éxito"
    And debería recibir un email de confirmación en jorge.supervisor@gmail.com


  #-------------------------------------------------------------------------------------------
  Scenario: Intento de envío de formulario con campos incompletos
    Given el visitante está en la página de destino de FastPorte
    And se desplaza hasta la sección "Contáctanos"
    When intenta enviar el formulario sin completar todos los campos requeridos
    Then debería ver mensajes de error indicando los campos faltantes
    And el formulario no debería enviarse


  #-------------------------------------------------------------------------------------------
  Scenario Outline: Validación de formato de email
    Given el visitante está en la página de destino de FastPorte
    And se desplaza hasta la sección "Contáctanos"
    When ingresa "<email>" en el campo de email
    And completa el resto de los campos correctamente
    And hace clic en el botón "Enviar mensaje"
    Then debería ver "<mensaje>"

    Examples:
      | email                       | mensaje                             |
      | jorge.supervisor@gmail.com  | Mensaje enviado con éxito           |
      | jorge.supervisor@gmail      | Por favor, ingrese un email válido  |
      | jorge.supervisor.com        | Por favor, ingrese un email válido  |
      | @gmail.com                  | Por favor, ingrese un email válido  |
  ```


| Repository | Branch | Commit Id | Commit Message | Commit Message Body| Commited on (Date)                                                                       |                                       
|---------- |----------|-|-|-|-|
| Debuggers-SW74 / testing-suite | main | 85e308b73fe9abd849cf2c8a4d11f600efe18344 | feat: Acceptance tests for user stories 1, 2,3, 40, 42 and 43 added |   | 22/09/2024 |

#### 6.2.1.5. Execution Evidence for Sprint Review



#### 6.2.1.6. Services Documentation Evidence for Sprint Review

Para este Sprint se implementó una Api Fake para el inicio de sesión y registro de usuarios, asi como una pre-visualización de los datos al generar un viaje.

| URL                              | Peiciones soportadas | 
|----------------------------------|----------------------|
| http://localhost:3000/users      | GET, POST            |
| http://localhost:3000/users/{id} | GET, PATCH           |
| http://localhost:3000/trips      | GET, POST            |

Estos endopoints sirven para desarrollar un entorno de pruebas de manera local por medio del paquete de npm llamado JSON Server.

Demostración de petición GET endpoint http://localhost:3000/users 
![get_users](/assets/chapter6_img/get_users.jpg)

Demostración de petición POST endpoint http://localhost:3000/users 
![post_users](/assets/chapter6_img/post_users.jpg)

Demostración de petición GET endpoint http://localhost:3000/trips 
![get_trips](/assets/chapter6_img/get_trips.jpg)

También se desplegó la API fake en un hosting gratuito para usarse al momento del despliegue de la version incial de la app web.

| URL                              | Peiciones soportadas | 
|----------------------------------|----------------------|
| https://my-json-server.typicode.com/Debuggers-SW74/dbiot/users      | GET, POST            |
| https://my-json-server.typicode.com/Debuggers-SW74/dbiot/users/{id} | GET, PATCH      |
| https://my-json-server.typicode.com/Debuggers-SW74/dbiot/trips      | GET, POST            |

Demostración de petición GET endpoint https://my-json-server.typicode.com/Debuggers-SW74/dbiot/users 
![get_users](/assets/chapter6_img/host_get_users.png)

Demostración de petición POST endpoint https://my-json-server.typicode.com/Debuggers-SW74/dbiot/users 
![post_users](/assets/chapter6_img/host_post_users.jpg)

Demostración de petición GET endpoint https://my-json-server.typicode.com/Debuggers-SW74/dbiot/trips 
![get_trips](/assets/chapter6_img/host_get_trips.png)

#### 6.2.1.7. Software Deployment Evidence for Sprint Review
#### 6.2.1.8. Team Collaboration Insights during Sprint

---
# Conclusiones

- El desarrollo del Lean UX Process ayudó a comprender mejor y aplicar efectivamente las herramientas en nuestra propuesta enfocada al servicio de transportistas hacia clientes. De la misma forma, contribuyó a definir de manera más clara nuestro público objetivo o llámese segmento hacia el cual va enfocada nuestra aplicación.
- Después de culminar la primera parte de nuestro proyecto e identificar los principales problemas que tienen nuestros segmentos, concluimos que sería de mucha ayuda el desarrollo de FastPorte con el fin de mejorar la experiencia y seguridad de los transportistas durante el transporte de material peligroso.
- El desarrollo de entrevistas nos ayudó a esclarecer la visión del proyecto, en cuanto a la perspectiva del usuario y por lo tanto fue importante para mejorar los aspectos de las funcionalidades de la aplicación.

---
# Bibliografía

---
# Anexos
## Anexo A
Enlace al video de exposición TB1:
[https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c172_upc_edu_pe/EaZHtsPladZLlSwgQU-S2gwBGxTUoaFbMr6ZAOYLOMK3lg?e=OcEN0D&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c172_upc_edu_pe/EaZHtsPladZLlSwgQU-S2gwBUV-dOtrbJ9E5PX3dYOZXAA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=wiIAWs)
## Anexo B
Enlace al video de entrevistas de Needfinding: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c172_upc_edu_pe/Ef5R7TRsWwNIs8GeLyIg4NEB7bnBukyP6rBCoV3SOG7QRw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=6H8zRb](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c172_upc_edu_pe/Ef5R7TRsWwNIs8GeLyIg4NEB7bnBukyP6rBCoV3SOG7QRw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=6H8zRb)
