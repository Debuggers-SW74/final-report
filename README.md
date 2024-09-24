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

| Integrante        | Chero Eme, Eduardo Andre                                    |
|-------------------|-------------------------------------------------------------|
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
El problema afecta a una amplia gama de actores, desde los conductores que transportan materiales peligrosos hasta las empresas que se encargan de la logística y el transporte. También involucra a las comunidades cercanas a las rutas de transporte y a las autoridades responsables de la seguridad pública.

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

Para comprender mejor los desafíos que nuestro proyecto abarca, hemos definido Problem Statements. Estos enunciados nos permiten enmarcar de manera clara los problemas que nuestro producto busca resolver, facilitando así el enfoque en soluciones que verdaderamente impacten en la vida de nuestros usuarios. 

##### Problem Statement 1:
Nuestro contexto demanda una supervisión efectiva de las condiciones de seguridad durante el transporte de materiales peligrosos. A través de esta supervisión, las empresas de transporte podrán monitorear en tiempo real los niveles de gas, temperatura y presión, asegurando la integridad del transporte y el cumplimiento de las normativas. Hemos observado un factor crítico que afecta a las empresas de transporte, el cual se manifiesta en la dificultad para detectar y responder rápidamente a incidentes durante el transporte, poniendo en riesgo la seguridad de los materiales y la reputación de la empresa. ¿Cómo garantizar la supervisión efectiva en tiempo real durante el transporte de materiales peligrosos para evitar riesgos y asegurar el cumplimiento normativo?
 
##### Problem Statement 2:
Nuestro contexto demanda soluciones que aseguren la seguridad de los conductores durante el transporte de materiales peligrosos. A través de la tecnología IoT, los conductores podrán recibir alertas tempranas sobre cualquier condición peligrosa, como fugas de gas o variaciones en la presión. Hemos observado un factor crítico que afecta a los conductores, el cual se manifiesta en la falta de información en tiempo real sobre los riesgos durante el transporte, lo que incrementa el peligro para su seguridad y la de otros en la carretera. ¿Cómo proporcionar alertas tempranas y efectivas a los conductores para minimizar los riesgos y garantizar su seguridad durante el transporte de materiales peligrosos?

#### 1.2.2.2. Lean UX Assumptions

En esta sección, definimos las suposiciones clave que guiarán el desarrollo de FastPorte. Estas suposiciones se basan en una comprensión profunda de nuestros usuarios y del mercado, y nos permiten validar las decisiones de diseño y desarrollo a lo largo del proceso.

##### CARACTERÍSTICAS

- Registro de usuarios en dos perfiles: Empresa y Conductor, con identificación y verificación adecuadas.
- Visualización de los perfiles de los conductores, incluyendo información relevante para el transporte de materiales peligrosos, como certificaciones y datos del vehículo.
- Las empresas podrán crear y gestionar viajes, asignando conductores y supervisando el estado de los mismos en tiempo real.
- Los conductores recibirán notificaciones sobre los viajes asignados y alertas de seguridad durante el transporte.
- Monitoreo en tiempo real de las condiciones del material transportado (fugas de gas, temperatura, presión) con alertas automáticas a las empresas y conductores.
- Historial de viajes y reportes de incidentes para ambos perfiles.
- Integración con sistemas de pago seguros para la facturación de servicios.
- Soporte para visualizar rutas y ubicación en tiempo real utilizando tecnología GPS.

##### BUSINESS OUTCOMES

- Asegurar el cumplimiento de normativas de seguridad en el transporte de materiales peligrosos.
- Incrementar la confianza de las empresas en la seguridad del transporte de sus materiales.
- Mejorar la eficiencia operativa mediante la supervisión en tiempo real y la gestión centralizada de los viajes.
- Reducir el riesgo de incidentes y accidentes durante el transporte de materiales peligrosos.

##### BENEFICIOS DEL USUARIO

- Para las empresas: Mejorar la gestión de sus operaciones de transporte, asegurando la seguridad de sus materiales y cumpliendo con las normativas.
- Para los conductores: Aumentar la seguridad durante el transporte gracias a las alertas en tiempo real y la supervisión continua.
- Para ambos: Acceso a un sistema confiable que permite la monitorización de las condiciones de transporte y la gestión eficiente de los viajes.

##### BUSINESS ASSUMPTIONS

- Creemos que las empresas de transporte de materiales peligrosos buscan soluciones que les ofrezcan seguridad y eficiencia en la gestión de sus operaciones.
- Los conductores necesitan una herramienta que les ofrezca seguridad adicional y la capacidad de gestionar su trabajo de manera más eficiente.
- Nuestros usuarios esperan que la información proporcionada por los sensores sea precisa y que las alertas sean confiables.
- Estas necesidades pueden ser satisfechas mediante una plataforma que integre la tecnología IoT para monitorear en tiempo real las condiciones de transporte y alertar sobre posibles riesgos.
- Los usuarios iniciales son empresas que transportan materiales peligrosos y conductores que buscan mejorar la seguridad en su trabajo diario.
- El valor principal que nuestros usuarios buscan en FastPorte es la seguridad y la confianza en la supervisión continua de sus operaciones.
- Obtendremos clientes a través de campañas dirigidas a empresas de transporte y conductores mediante anuncios en internet y asociaciones estratégicas.
- Los ingresos se generarán a través de suscripciones a la plataforma, tarifas de servicio, y posibles acuerdos con aseguradoras que ofrezcan descuentos a empresas que utilicen FastPorte.
- Nuestra principal competencia son otras soluciones de monitoreo y gestión de flotas, pero nos destacaremos por nuestro enfoque especializado en materiales peligrosos.
- El mayor riesgo es que las alertas no se detecten a tiempo o que la información proporcionada sea incorrecta, lo que podría llevar a incidentes durante el transporte. - Resolveremos esto mediante pruebas rigurosas de los sensores y un sistema de validación continua.

##### USER ASSUMPTIONS

- **¿Quién es el usuario?**
Las empresas de transporte de materiales peligrosos y los conductores encargados de transportar dichos materiales.

- **¿Dónde encaja nuestro producto en su trabajo o vida?**
Para las empresas, encaja en la gestión y supervisión de sus operaciones diarias. Para los conductores, en la mejora de la seguridad durante su trabajo.

- **¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**
El producto podría enfrentar desafíos relacionados con la precisión de los sensores y la confiabilidad de las alertas. Estos se pueden resolver mediante pruebas continuas y actualizaciones basadas en el feedback de los usuarios.

- **¿Cuándo y cómo es usado nuestro producto?**
El producto será utilizado durante el transporte de materiales peligrosos para monitorear en tiempo real las condiciones de seguridad y gestionar los viajes.

- **¿Qué características son importantes?**
Monitoreo en tiempo real, alertas fiables, fácil gestión de viajes, y una interfaz intuitiva y segura.

- **¿Cómo debe verse nuestro producto y cómo debe comportarse?**
Debe tener una interfaz moderna, fácil de usar, con colores que transmitan confianza y seguridad. El comportamiento debe ser ágil, con notificaciones claras y precisas, y una respuesta rápida a cualquier incidencia.

#### 1.2.2.3. Lean UX Hypothesis Statements

En esta sección, formularemos hipótesis basadas en nuestras suposiciones de Lean UX. Estas hipótesis nos permitirán validar si las soluciones que implementamos en FastPorte están efectivamente resolviendo los problemas identificados y generando los resultados deseados tanto para los usuarios como para el negocio.

##### HIPÓTESIS 1:

**_Creemos que_** proporcionar una plataforma donde las empresas puedan monitorear en tiempo real las condiciones de seguridad durante el transporte de materiales peligrosos mejorará la eficiencia operativa y la seguridad del transporte.
**_Sabremos que_** hemos tenido éxito
**_Cuando_** las empresas reporten una reducción del 25% en incidentes relacionados con la seguridad y un incremento del 15% en la eficiencia de sus operaciones de transporte dentro de los primeros seis meses de uso de FastPorte.

#####  HIPÓTESIS 2: 

**_Creemos que_** implementar alertas en tiempo real para los conductores mejorará su capacidad para prevenir accidentes durante el transporte de materiales peligrosos.
**_Sabremos que_** hemos tenido éxito
**_Cuando_** los conductores reporten una disminución del 30% en incidentes de riesgo y un aumento del 20% en su percepción de seguridad mientras utilizan FastPorte.

##### HIPÓTESIS 3: 

**_Creemos que_** ofrecer un historial detallado de viajes y reportes de incidentes ayudará a las empresas a tomar decisiones más informadas sobre la gestión de sus flotas.
**_Sabremos que_** hemos tenido éxito
**_Cuando_** observemos que el 70% de las empresas usuarias de FastPorte consultan regularmente los reportes de incidentes y utilizan la información para optimizar sus operaciones dentro de los primeros tres meses.

##### HIPÓTESIS 4: 

**_Creemos que_** la integración de un sistema de pago seguro para la facturación de servicios de transporte generará confianza en nuestros usuarios.
**_Sabremos que_** hemos tenido éxito
**_Cuando_** las empresas reporten un incremento del 20% en la puntualidad de los pagos y una reducción del 15% en disputas relacionadas con la facturación en el primer semestre de uso.

##### HIPÓTESIS 5: 

**_Creemos que_** proporcionar visualización en tiempo real de rutas y ubicación del transporte utilizando tecnología GPS aumentará la satisfacción de las empresas y conductores con la plataforma.
**_Sabremos que_** hemos tenido éxito
**_Cuando_** el 80% de nuestros usuarios reporten una mejora en la transparencia y control sobre sus operaciones de transporte, reflejada en encuestas de satisfacción realizadas después del primer trimestre de uso.

#### 1.2.2.4. Lean UX Canvas

<table>
    <tr>
        <th colspan="3" valign="top">LEAN UX CANVAS</th>
        <th colspan="1" valign="top">
            Fecha: 26/08/24
            <br>
            Iteración: 1
        </th>
    </tr>
    <tr>
        <td valign="top">
            <p><b>1. Business problem</b></p>
            <p></p>
            <p>Hemos
                identificado una necesidad en el mercado de transporte, donde
                las empresas y sus conductores requieren una solución que
                ofrezca seguridad y eficiencia en el transporte de materiales
                peligrosos. Estas entidades buscan una plataforma confiable que
                centralice y facilite la supervisión en tiempo real de sus
                operaciones para minimizar riesgos y cumplir con normativas
                estrictas.</p>
        </td>
        <td rowspan="2" valign="top">
            <p><b>5.Solutions</b></p>
            <p>
            <ul>
                <li> Plataforma de supervisión en tiempo real que integra
                    tecnología IoT para monitorear condiciones de seguridad
                    como fugas de gas, temperatura, y presión.</li>
                </p>
                <p>
                    <li>Proceso riguroso de registro y validación para
                        conductores y empresas, asegurando la confiabilidad de
                        los servicios ofrecidos.</li>
                </p>
                <p>
                    <li>Sistema de alertas automáticas que notifica a empresas y
                        conductores sobre posibles riesgos
                        durante el transporte.
                    </li>
            </ul>
            </p>
        </td>
        <td colspan="2" valign="top">
            <p><b>2.Business Outcomes</b></p>
            <p>
            <ul>
                <li> Asegurar el
                    cumplimiento de normativas de seguridad en el transporte
                    de
                    materiales peligrosos.</li>
                </p>
                <p>
                    <li>Incrementar la
                        confianza de las
                        empresas en la seguridad del transporte de sus
                        materiales.</li>
                </p>
                <p>
                    <li>Mejorar la eficiencia
                        operativa mediante la
                        supervisión en tiempo real y la gestión centralizada de
                        los
                        viajes.</li>
                </p>
                <p>
                    <li>Reducir el riesgo de incidentes
                        y accidentes
                        durante el transporte de materiales
                        peligrosos.</li>
            </ul>
            </p>
        </td>
    </tr>
    <tr>
        <td rowspan="2" valign="top">
            <p><b>3. User</b></p>
            <p></p>
            <p>
                Nuestro producto se dirige a dos tipos de usuarios
                principales:</p>
            <p>
            <ul>
                <li>
                    <b>Empresas de transporte de materiales peligrosos</b>
                    que
                    buscan mejorar la seguridad y el cumplimiento
                    normativo.
                </li>
                </p>
                <p>
                    <li><b>Conductores de transporte de materiales
                            peligrosos</b> que
                        necesitan herramientas para aumentar la seguridad
                        durante sus
                        operaciones diarias.</li>
            </ul>
            </p>
            <p></p>
        </td>
        <td colspan="2" rowspan="2" valign="top">
            <p><b>4. User outcomes & benefits</b></p>
            <p>
            <ul>
                <li>Para las <b>empresas</b>, FastPorte mejora la gestión de
                    sus operaciones,incrementa la seguridad y asegura el
                    cumplimiento
                    normativo.
                </li>
                </p>
                <p>
                    <li>Para los <b>conductores</b>, FastPorte ofrece
                        una mayor seguridad mediante alertas en tiempo real y
                        supervisión constante, reduciendo el riesgo de
                        accidentes.
                    </li>
                </p>
                <p>
                    <li> Para ambos, acceso a un sistema confiable
                        que permite la monitorización de las condiciones de
                        transporte y
                        la gestión eficiente de los viajes.
                    </li>
            </ul>
            </p>
        </td>
    </tr>
    <tr>
        <td rowspan="2" valign="top">
            <p><b>7. ¿Qué es lo más importante que
                    necesitamos aprender primero?</b></p>
            <p></p>
            <p>Validar la
                precisión y efectividad del sistema de alertas en tiempo real
                para que los usuarios confíen en ellas y tomen acciones
                preventivas.</p>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <p><b>6. Hypotheses</b></p>
            <p></p>
            <p>
            <ul>
                <li>
                    <b>Creemos que</b> proporcionar una plataforma donde las
                    empresas
                    puedan monitorear en tiempo real las condiciones de
                    seguridad
                    durante el transporte de materiales peligrosos mejorará
                    la
                    eficiencia operativa y la seguridad del transporte.
                    <br>
                    <b>Sabremos que</b> hemos tenido éxito
                    <br>
                    <b>Cuando</b> las empresas reporten una reducción del
                    25% en incidentes relacionados con la seguridad y un
                    incremento del 15% en la eficiencia de sus operaciones
                    de transporte dentro de los
                    primeros seis meses de uso de FastPorte.</p>
                    <p>
                </li>
                <li>
                    <b>Creemos que</b> implementar alertas en tiempo real
                    para los
                    conductores mejorará su capacidad para prevenir
                    accidentes
                    durante el transporte de materiales
                    peligrosos.</p>
                    <p><b>Sabremos que</b> hemos tenido
                        éxito</p>
                    <p>
                        <b>Cuando</b> los conductores reporten una disminución
                        del 30% en incidentes de riesgo y un aumento del 20% en
                        su percepción de seguridad mientras utilizan FastPorte.
                </li>
            </ul>
            </p>
            <p></p>
        </td>
        <td colspan="2" valign="top">
            <p><b>8.
                    ¿Cuál es la menor cantidad de trabajo que debemos hacer para
                    aprender la siguiente cosa más
                    importante?</b></p>
            <p>Desarrollar un prototipo funcional del
                sistema de alertas y realizar pruebas piloto con un grupo
                representativo de usuarios para evaluar su precisión y utilidad
                en situaciones reales.</p>
        </td>
    </tr>
</table>

## 1.3. Segmentos objetivo

En el desarrollo de FastPorte, hemos identificado dos segmentos de usuarios principales en el territorio peruano, cada uno con características y necesidades específicas que guían el diseño y funcionalidad de nuestra plataforma.

##### PRIMER SEGMENTO

El primer segmento está compuesto por las empresas de transporte de materiales peligrosos. Estas empresas, que varían en tamaño desde pequeñas a grandes, están ubicadas predominantemente en zonas industriales y áreas cercanas a puertos y fronteras. Muchas de ellas manejan un volumen significativo de operaciones que dependen de la seguridad y cumplimiento normativo en el transporte de materiales peligrosos. Para estas empresas, FastPorte ofrece una solución integral que permite monitorear y gestionar sus operaciones de manera más eficiente, reduciendo el riesgo de incidentes y garantizando el cumplimiento de la ley.

##### SEGUNDO SEGMENTO

El segundo segmento objetivo son los conductores de transporte de materiales peligrosos. Estos profesionales, con edades comprendidas entre 25 y 55 años, operan principalmente en rutas nacionales e internacionales, y han recibido formación técnica o certificaciones específicas para el manejo de materiales peligrosos. FastPorte está diseñado para proporcionar a estos conductores herramientas cruciales que aumenten su seguridad, como alertas en tiempo real y supervisión constante de las condiciones de transporte.

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
- ¿Actualmente a que rol desempeñas en la empresa?

**- Preguntas principales:**
- ¿Qué desafíos enfrentas actualmente en términos de seguridad durante el transporte de materiales peligrosos?
- ¿Puedes describir alguna situación en la que te hayas sentido preocupado por la seguridad debido a la carga que transportas?
- ¿Cómo afectan las condiciones del entorno en el que trabajas (por ejemplo, temperatura, presión) la seguridad durante el transporte?
- ¿Qué problemas encuentras al monitorear las condiciones del vehículo mientras estás en movimiento?
- ¿Cuáles son los problemas más comunes que enfrentas  o fallos en el sistema de transporte?
- ¿Cómo sueles darte cuenta de un problema con la carga o el vehículo durante el transporte?
- ¿Cuál es tu proceso actual para manejar un problema relacionado con la carga mientras estás en ruta?

**Segmento objetivo: Empresas**

**- Preguntas demográficas:**

- ¿Cuál es tu nombre?
- ¿Qué edad tienes?
-  ¿Actualmente a que rol desempeñas en la empresa?

**- Preguntas principales:** 
- ¿Qué medidas actuales tomas para asegurar la integridad de los materiales peligrosos durante el transporte?
- ¿Cuáles son los principales riesgos asociados con el transporte de materiales peligrosos que enfrentas en tu operación diaria?
- ¿Cómo supervisas y gestionas las condiciones de los vehículos que transportan materiales peligrosos?
- ¿Qué dificultades encuentras en el monitoreo de las condiciones del transporte y el estado de la carga?
- ¿Qué desafíos enfrentas para cumplir con las regulaciones y estándares de seguridad en el transporte de materiales peligrosos?
- ¿Cuál es el proceso actual para responder a incidentes de seguridad o problemas con la carga durante el transporte?
- ¿Qué tipo de soporte adicional consideras necesario para mejorar la respuesta a emergencias relacionadas con el transporte de materiales peligrosos?

### 2.2.2. Registro de entrevistas

Entrevista 1: Segmento objetivo empresa

[![interview1.png](https://i.postimg.cc/9XT566xK/entrevista-empresa-1.png)](https://postimg.cc/Wt2HrHcw)

URL: https://youtu.be/Q5w1AZyZ7cU

Timing: 0:05

Duración: 8:04 minutos 

**Resúmen de la entrevista:**
Entrevistado: Jorge tiene 52 años y es Supervisor de Transportes en Convoy de materiales peligrosos (transporte de hidrocarburos a empresas mineras).

Características clave mencionadas por el entrevistado:
- **Medidas de seguridad:** Utilización de unidades adecuadas para el tipo de transporte, personal capacitado, documentación correcta, y un checklist exhaustivo de la unidad antes de cada transporte. El conductor debe descansar al menos 7 horas antes del turno, se realizan controles de alcoholemia y se prohíbe el uso de celulares durante el transporte.

- **Riesgos principales:** Carreteras en mal estado, condiciones climáticas adversas (neblina, lluvia, tormentas de arena), y el riesgo de robo en zonas peligrosas.

- **Supervisión:** Monitoreo constante con GPS, aunque existen problemas en áreas sin señal, como desiertos o montañas.

- **Cumplimiento de regulaciones:** Conocimiento y cumplimiento de procedimientos y políticas de seguridad tanto de la empresa de transporte como de las empresas mineras. Capacitación constante del personal, con charlas diarias sobre seguridad.

- **Respuesta a emergencias:** Planes de contingencia claros para derrames o emergencias personales, con necesidad de entrenamientos y simulacros regulares para mejorar la respuesta.

Entrevista 2: Segmento objetivo empresa

[![interview1.png](https://i.postimg.cc/9Fh5CLKM/entrevista-empresa-2.png)](https://postimg.cc/Z0VDLxTt)

URL: https://youtu.be/5VN1W9JiBUE

Timing: 0:03

Duración: 25:11 minutos 

**Resúmen de la entrevista:**
Entrevistado: Arquímedes Ordoño Gutiérrez tiene 55 años y es Jefe de Supervisores en Transcor SRL.

Características clave mencionadas por el entrevistado:

- **Medidas de seguridad:** Enfoque en la capacitación y descanso de los conductores. Uso de tecnologías avanzadas como pulseras para monitorear el sueño, cámaras de fatiga, y sistemas de alerta.

- **Riesgos principales:** Tráfico y la actitud de otros conductores en la carretera. Capacitación constante en seguridad vial y manejo defensivo, especialmente en zonas geográficas difíciles como la sierra.

- **Supervisión:** Uso de geocercas, control de velocidad, pruebas de alcoholemia, y teléfonos satelitales en zonas sin cobertura celular.

- **Cumplimiento de regulaciones:** Burocracia en la obtención de permisos de transporte, a pesar de tener una flota moderna y certificada. Se requiere mayor agilidad en los trámites para homologar unidades.

- **Respuesta a emergencias:** Simulacros regulares y un kit antiderrame avanzado para controlar fugas. Implementación de tecnología alemana para sellar fisuras en cisternas.

Entrevista 3: Segmento objetivo empresa

[![interview1.png](https://i.postimg.cc/MGFJwqJ2/entrevista-empresa-3.png)](https://postimg.cc/Ff3BgtKD)

URL: https://youtu.be/Q5w1AZyZ7cU

Timing: 0:05

Duración: 8:04 minutos 

**Resúmen de la entrevista:**
Entrevistado: Estuardo Chero tiene 46 años y es Supervisor Escolta de Materiales Peligrosos.

Características clave mencionadas por el entrevistado:
- **Medidas de seguridad:** Verificación del estado de las unidades y la condición de los conductores antes de iniciar el viaje. Cumplimiento estricto de las normas de seguridad.

- **Riesgos principales:** Accidentes de tránsito, especialmente debido a la falta de cumplimiento de estándares de seguridad por parte de otros conductores.

- **Supervisión:** Control continuo durante el trayecto, con charlas de seguridad previas y evaluación constante del estado del convoy.

- **Cumplimiento de regulaciones:** Cumplimiento total de los estándares de seguridad, basado en la convicción del personal. Los procedimientos están documentados en un plan de contingencia que incluye pasos detallados para emergencias.

- **Respuesta a emergencias:** Supervisión continua del convoy y rápida implementación del plan de contingencia en caso de accidentes. Uso de comunicaciones radiales y soporte de agentes viales en zonas peligrosas.

<br><br>

Entrevista 4: Segmento objetivo conductores

[![interview1.png](https://i.postimg.cc/5t8S9PQL/entrevista-conductor-2.png)](https://postimg.cc/bGNt39Tw)

URL: https://www.youtube.com/watch?v=KEh32dSaK2w

Timing: 0:01

Duración: 6:25 minutos 

**Resúmen de la entrevista:**
Entrevistado: José Gonzales tiene 27 años y es Conductor de Sisternas.

- **Seguridad:** La seguridad del transporte depende de asegurar que la carga esté bien sujeta y que el vehículo esté en óptimas condiciones. El transporte nocturno es particularmente peligroso debido a la visibilidad limitada y condiciones como la neblina.

- **Situación de riesgo:** Durante las noches con neblina y carreteras mojadas, José se siente preocupado por los riesgos adicionales, especialmente en zonas mal diseñadas.

- **Condiciones ambientales:** El calor extremo en verano puede aumentar la presión en los tanques y generar riesgos de explosión. En invierno, las lluvias intensas y la neblina representan riesgos al conducir en carreteras mojadas.

- **Monitoreo en movimiento:** Aunque su vehículo tiene sistemas de alerta, estos a veces fallan o se activan con retraso, lo que genera incertidumbre.

- **Problemas comunes:** Las fallas más frecuentes incluyen problemas con válvulas y frenos. Es esencial revisar estos componentes antes de cada viaje.

- **Proceso para manejar problemas:** Ante un problema en ruta, José se detiene en un lugar seguro y contacta a la base o al centro de emergencias para recibir instrucciones. Sugiere contar con técnicos especializados para acompañar los viajes y ayudar en casos graves.

Entrevista 5: Segmento objetivo conductores

[![interview1.png](https://i.postimg.cc/nzZYXvq5/entrevista-conductor-1.png)](https://postimg.cc/kV1tZR1F)

URL: https://www.youtube.com/watch?v=dP9vHbNym4c

Timing: 0:04

Duración: 10:26 minutos 

**Resúmen de la entrevista:**
Entrevistado: Juan Cueto Dominguez tiene 28 años y es Conductor de Materiales Peligrosos.

- **Seguridad:** El principal reto es garantizar que el vehículo y la carga cumplan con todas las normativas de seguridad. Esto implica un monitoreo constante de la estabilidad de la carga, el mantenimiento del vehículo, y el respeto a regulaciones locales. Las condiciones ambientales, como el calor y la fricción, también representan riesgos.

- **Situación de riesgo:** Durante el transporte de gases inflamables, Juan vió el aumento de la temperatura exterior que elevó la presión en los contenedores. Tuvo que estacionar en un lugar seguro y activar el plan de contingencia para evitar un accidente mayor.

- **Monitoreo en movimiento:** Es difícil verificar la carga mientras se conduce, y el ruido o la vibración del vehículo pueden ocultar señales de posibles problemas. Los sistemas de alerta no siempre detectan fallas como inestabilidad de la carga o fugas.

- **Problemas comunes:** Los fallos más frecuentes incluyen problemas con los sistemas de sujeción de la carga, desgaste de etiquetas de seguridad y sistemas de enfriamiento ineficientes.

- **Proceso para manejar problemas:** Ante cualquier indicio de riesgo, Juan se estaciona en una zona segura y notifica a los números de emergencia para activar el protocolo de seguridad. Luego, el sigue las instrucciones de los expertos y revisa las hojas de seguridad del material transportado.

### 2.2.3. Análisis de entrevistas

- Las medidas de seguridad son una preocupación central para todos los entrevistados. Además, los riesgos relacionados con las condiciones externas son una preocupación común y el cumplimiento de normas es una obligación crítica en todas las empresas entrevistadas.

[![interview1.png](https://i.postimg.cc/x1Wp0CF2/gr-fico1-temas-clave.png)](https://postimg.cc/DSPP62Tj)

- Todos los entrevistados consideran los accidentes de tránsito como el principal riesgo. La pérdida de señal GPS en zonas remotas es un desafío significativo mencionado en 2 de las 3 entrevistas. Además, la mayoría de las empresas exige un mínimo de 7 horas de descanso para los conductores y la capacitación de los conductores se realiza dos veces al año como mínimo.

[![interview1.png](https://i.postimg.cc/JhZ6tL9B/gr-fico2-percepciones.png)](https://postimg.cc/McZbrhZW)

- Las empresas implementan múltiples tecnologías para garantizar la seguridad en el transporte. Todas las empresas utilizan teléfonos satelitales en zonas donde la cobertura de señal es deficiente. Además, los entrevistados perciben que el proceso burocrático es un desafío considerable. También, las empresas realizan simulacros de emergencia al menos 3 veces al año y se sugiere incrementar las unidades de respuesta para reducir tiempos de llegada en emergencias.

[![interview1.png](https://i.postimg.cc/t41mQPkk/gr-fico3-tecnolog-a-normas-simulacros.png)](https://postimg.cc/DSTc1St4)

## 2.3. Needfinding
### 2.3.1. User Personas

- **Segmento objetivo empresas: Arquetipo de las empresas**

[![interview1.png](https://i.postimg.cc/TwC09qF5/User-Persona-Empresas-new.png)](https://postimg.cc/9RwyXTWc)

- **Segmento objetivo conductores: Arquetipo del conductor**

[![interview1.png](https://i.postimg.cc/d3jmYn3n/User-Persona-Conductores-new.png)](https://postimg.cc/ct687RQ8)

### 2.3.2. User Task Matrix

- **Segmento objetivo empresas: Matriz de tareas**

[![interview1.png](https://i.postimg.cc/G3NQV1bD/User-Task-Matrix-Empresas.png)](https://postimg.cc/jCHPnmwq)

- **Segmento objetivo conductores: Matriz de tareas**

[![interview1.png](https://i.postimg.cc/FHVykTx4/User-Task-Matrix-Conductores.png)](https://postimg.cc/0zrMLd3W)

### 2.3.3. User Journey Mapping

- **Segmento objetivo empresas: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/fyPK4Www/Customer-Journey-Map-Empresas-new.png)](https://postimg.cc/YL1gYHGV)

- **Segmento objetivo conductores: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/CMG4kM7D/Customer-Journey-Map-Conductores-new.png)](https://postimg.cc/8sCWVSqP)

### 2.3.4. Empathy Mapping

- **Segmento objetivo empresas: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/sXD9vGxj/Empathy-Map-Empresas-new.png)](https://postimg.cc/mcJFnD7J)

- **Segmento objetivo conductores: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/pXPJZNcS/Empathy-Map-Conductores-new.png)](https://postimg.cc/4nFcf0gv)

### 2.3.5. As-is Scenario Mapping

- **Mapa As-Is: Segmento objetivo antes de conocer la solución de software:**

[![interview1.png](https://i.postimg.cc/0yCXLHWq/Mapa-As-Is-Empresas.png)](https://postimg.cc/3kdZG9QL)

## 2.4. Ubiquitous Language

- **Hazardous Materials (Materiales Peligrosos):** Materiales que, debido a su naturaleza química, física o biológica, pueden causar daños a las personas, bienes o el medio ambiente durante el transporte o almacenamiento.

- **Gas Leak (Fuga de Gas):** Escape no controlado de gas de un contenedor, lo que puede representar un riesgo de explosión o intoxicación.

- **Real-Time Monitoring (Monitoreo en Tiempo Real):** Supervisión continua de las condiciones de seguridad durante el transporte, como la detección de fugas, cambios de temperatura o presión.

- **Sensor:** Dispositivo que detecta y mide condiciones específicas como temperatura, presión o fugas de gas, enviando información en tiempo real a los sistemas de monitoreo.

- **Company Profile (Perfil de Empresa):** Perfil dentro de la aplicación que permite a las empresas de transporte gestionar y monitorear los viajes de los conductores y las condiciones del material peligroso transportado.

- **Driver Profile (Perfil de Conductor):** Perfil en la aplicación utilizado por los conductores para visualizar los detalles de sus viajes, recibir alertas de seguridad y acceder a la información relacionada con la empresa y el transporte de materiales peligrosos.

- **Explosive Materials (Materiales Explosivos):** Tipos de materiales peligrosos que, al sufrir una alteración física o química (como una fuga), pueden detonar o incendiarse.

- **Transportation Incident (Incidente de Transporte):** Evento inesperado que ocurre durante el transporte, como accidentes, fugas o cambios en las condiciones ambientales, que puede afectar la seguridad del conductor o los materiales.

- **Safety Alerts (Alertas de Seguridad):** Notificaciones enviadas automáticamente por la aplicación cuando se detectan condiciones peligrosas, como fugas de gas o cambios extremos de temperatura.

- **Fleet Management (Gestión de Flotas):** Proceso de supervisión y coordinación de una flota de vehículos, con el objetivo de mejorar la seguridad, eficiencia y cumplimiento de normativas en el transporte de materiales peligrosos.

- **Compliance (Cumplimiento Normativo):** Adherencia a las leyes, regulaciones y estándares establecidos para garantizar la seguridad y legalidad en el transporte de materiales peligrosos.

- **Gas Combustible Natural (GNV):** Combustible basado en gas natural utilizado para vehículos, el cual puede representar un riesgo de explosión si no se maneja adecuadamente.

- **Safety Procedures (Procedimientos de Seguridad):** Conjunto de acciones o medidas establecidas para minimizar los riesgos durante el transporte de materiales peligrosos, incluyendo el uso adecuado de sensores y notificaciones en tiempo real.

- **Operational Efficiency (Eficiencia Operativa):** Medida de la efectividad con la que las empresas gestionan sus operaciones de transporte, optimizando recursos y minimizando riesgos mediante el uso de herramientas tecnológicas.

- **Transportation Request (Solicitud de Transporte):** Petición formal de una empresa para transportar materiales peligrosos, detallando las rutas, condiciones, y asignación de conductores y vehículos.

- **Pressure Sensor (Sensor de Presión):** Dispositivo que mide la presión dentro de un contenedor o tanque, alertando a los usuarios sobre cambios peligrosos que podrían comprometer la seguridad del transporte.

- **Temperature Sensor (Sensor de Temperatura):** Dispositivo que mide la temperatura de los materiales peligrosos transportados, enviando alertas si la temperatura se eleva o desciende a niveles peligrosos.

- **Incident Report (Reporte de Incidente):** Documento generado por la aplicación que detalla un incidente ocurrido durante el transporte de materiales peligrosos, incluyendo detalles como el tipo de incidente, la respuesta y las acciones tomadas.

- **Supervision (Supervisión):** Actividad de control y monitoreo continuo de los vehículos, conductores y condiciones del transporte para asegurar la integridad de los materiales peligrosos.
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

### 4.1.1. EventStorming
![EventStorming](./assets/chapter4_img/step8.jpg)

#### 4.1.1.1 Candidate Context Discovery

Step 1:
![Step 1](./assets/chapter4_img/step1.jpg)
Step 2:
![Step 2](./assets/chapter4_img/step2.jpg)
Step 3:
![Step 3](./assets/chapter4_img/step3.jpg)
Step 4:
![Step 4](./assets/chapter4_img/step4.jpg)
Step 5:
![Step 5](./assets/chapter4_img/step5.jpg)
Step 6:
![Step 6](./assets/chapter4_img/step6.jpg)
Step 7:
![Step 7](./assets/chapter4_img/step7.jpg)
Step 8:
![Step 8](./assets/chapter4_img/step8.jpg)

#### 4.1.1.2 Domain Message Flows Modeling

Leyenda: <br>
![Leyenda](./assets/chapter4_img/leyenda.png)

Escenario: Inicio de sesión
![Escenario 1](./assets/chapter4_img/escenario1.png)

Escenario: Registro de usuario
![Escenario 2](./assets/chapter4_img/escenario2.png)

Escenario: Registro del sensor
![Escenario 3](./assets/chapter4_img/escenario3.png)

Escenario: Programación de viaje
![Escenario 4](./assets/chapter4_img/escenario4.png)

Escenario: Conductor visualiza sus viajes pendientes
![Escenario 5](./assets/chapter4_img/escenario5.png)

Escenario: Sensor detecta un problema
![Escenario 6](./assets/chapter4_img/escenario6.png)

#### 4.1.1.3 Bounded Context Canvases

Bounded context 'Usuario'  <br>
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_users.jpg)

Bounded context 'Sensor'  <br>
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_sensor.jpg)

Bounded context 'Viajes'  <br>
![Bounded Context Canvas Usuario](./assets/chapter4_img/canvas_viajes.jpg)

### 4.1.2. Context Mapping
![Context Mapping](./assets/chapter4_img/context_mapping.jpg)

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram
![C4 Diagrama de Contexto](./assets/chapter4_img/landscape.jpg)

#### 4.1.3.2. Software Architecture Context Level Diagrams
![C4 Diagrama de Contexto](./assets/chapter4_img/c4_context.png)

#### 4.1.3.2. Software Architecture Container Level Diagrams.
![C4 Diagrama de Componentes](./assets/chapter4_img/c4_component.jpg)

#### 4.1.3.3. Software Architecture Deployment Diagrams
![Software Architecture Deployment Diagrams](./assets/chapter4_img/ArchDeploy.png)

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Usuario
Este bounded context está relacionado con la gestión de cuentas de usuario, autenticación y la gestión de perfiles dentro de un sistema.

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Usuario</td>
      <td class="tg-0pky" colspan="3">Representa a un usuario en el sistema, con credenciales y estado de autenticación</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">userID</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Composicón</td>
      <td class="tg-0lax">UserProfile</td>
      <td class="tg-0lax">authenticateUser()</td>
    </tr>
    <tr>
      <td class="tg-0lax">email</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Token</td>
      <td class="tg-0lax">validateToken()</td>
    </tr>
    <tr>
      <td class="tg-0lax">password</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">invalidateToken()</td>
    </tr>
    <tr>
      <td class="tg-0lax">isActive</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">UserProfile</td>
      <td class="tg-0pky" colspan="3">Contiene la información personal y preferencias del usuario</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">name</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax">Asociación</td>
      <td class="tg-0lax">Usuario</td>
      <td class="tg-0lax">updateUserProfile()</td>
    </tr>
    <tr>
      <td class="tg-0lax">address</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">retrieveUserProfile()</td>
    </tr>
    <tr>
      <td class="tg-0lax">phone</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">profileImg</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Token</td>
      <td class="tg-0pky" colspan="3">Token utilizado para validar sesiones activas del usuario</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">tokenId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Asociación</td>
      <td class="tg-0lax">Usuario</td>
      <td class="tg-0lax">generateToken()</td>
    </tr>
    <tr>
      <td class="tg-0lax">creationDate</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">validateToken()</td>
    </tr>
    <tr>
      <td class="tg-0lax">expirationDate</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">invalidateToken()</td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Notification</td>
      <td class="tg-0pky" colspan="3">Gestiona las notificaciones enviadas al usuario</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">notificationId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Asociación</td>
      <td class="tg-0lax">Usuario</td>
      <td class="tg-0lax">sendUserNotification()</td>
    </tr>
    <tr>
      <td class="tg-0lax">message</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">sendAccountActivityAlert()</td>
    </tr>
    <tr>
      <td class="tg-0lax">sentDate</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

#### 4.2.1.1. Domain Layer.

* **Usuario:** Define las propiedades y el comportamiento de un usuario en el sistema.
* **Perfil de Usuario:** Gestiona la información del perfil del usuario (nombre, dirección, teléfono, etc.).
* **Token de Autenticación:** Representa los tokens utilizados para manejar las sesiones de usuario.
* **Notificación:** Representa las notificaciones enviadas a los usuarios sobre actividades importantes o alertas.
#### 4.2.1.2. Interface Layer.
En esta capa presentamos los endpoints de la API que interactúan con las entidades del dominio:

* **Autenticación de Usuario:** Servicios como authenticateUser(), validateToken() y invalidateToken() para la validación y gestión de autenticación.
* **Gestión de Perfiles:** Servicios como updateUserProfile() y retrieveUserProfile() para la actualización y recuperación del perfil del usuario.
* **Notificaciones:** Servicios como sendUserNotification() para el envío de alertas al usuario.
#### 4.2.1.3. Application Layer.

* **Inicio de sesión:** Se gestiona la autenticación y validación de tokens.
* **Gestión de perfiles:** Actualización y consulta de información de perfiles de usuario.
* **Envío de notificaciones:** Envía notificaciones o alertas al usuario, tales como actividades sospechosas o cambios en la cuenta.
#### 4.2.1.4. Infrastructure Layer.

* **Persistencia de Usuario:** Manejo de la persistencia de los datos del usuario y su perfil en una base de datos.
* **Autenticación:** Comunicación con servicios de autenticación y generación de tokens.
* **Notificaciones:** Envío de notificaciones a través de servicios de mensajería (por ejemplo, email, SMS, notificaciones push).
#### 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams.
![C4 Diagrama de Componentes](./assets/chapter4_img/bounded_context_user.jpeg)
#### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.
![Diagrama_de_clases_usuario](./assets/chapter4_img/user_bounded_context-class_diagram.png)
###### 4.2.1.7.2. Bounded Context Database Design Diagram.
![Diagrama_de_base_de_Datos_usuario](./assets/chapter4_img/user_bounded_context-database_diagram.png)
### 4.2.2. Bounded Context: Sensor
Este bounded context es responsable de la gestión de los sensores y la captura de sus datos de telemetría, así como de la generación de alertas cuando se detectan valores fuera de los rangos establecidos.

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Sensor</td>
        <td class="tg-0pky" colspan="3">Captura datos de telemetría y genera alertas si los valores detectados están fuera de los parámetros establecidos</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">sensorId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Telemetry</td>
      <td class="tg-0lax">registrarSensor()</td>
    </tr>
    <tr>
      <td class="tg-0lax">nombre</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Alert</td>
      <td class="tg-0lax">actualizarEstado()</td>
    </tr>
    <tr>
      <td class="tg-0lax">tipo</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">ubicación</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">estado</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">fecha de registro</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Telemetry</td>
        <td class="tg-0pky" colspan="3">Contiene los datos capturados por los sensores en un momento dado, como temperatura, presión, o cualquier otra métrica</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">telemetryId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Composición</td>
      <td class="tg-0lax">Sensor</td>
      <td class="tg-0lax">actualizarDatos()</td>
    </tr>
    <tr>
      <td class="tg-0lax">sensorId</td>
      <td class="tg-0lax">Int (FK)</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">fecha captura</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">valor</td>
      <td class="tg-0lax">Float</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">unidad</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Alert</td>
        <td class="tg-0pky" colspan="3">Representa una notificación que se genera cuando un sensor detecta valores fuera de los parámetros normales, como una temperatura excesiva o una fuga de gas</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">alertaId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Composición</td>
      <td class="tg-0lax">Sensor</td>
      <td class="tg-0lax">generarAlerta()</td>
    </tr>
    <tr>
      <td class="tg-0lax">sensorId</td>
      <td class="tg-0lax">Int (FK)</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax">cerrarAlerta()</td>
    </tr>
    <tr>
      <td class="tg-0lax">tipo alerta</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">fecha generacion</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">estado</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

#### 4.2.2.1. Domain Layer.
Este Domain Layer contiene las entidades y lógica de negocio relacionadas con los sensores y la telemetría. Incluye las siguientes clases principales:

* **Sensor:** Representa un sensor que captura datos de telemetría.
* **Telemetry:** Registra los datos capturados por los sensores.
* **Alert:** Representa las alertas que se generan cuando se detectan condiciones anormales en los datos de los sensores.

Este dominio modela la lógica para registrar, actualizar y monitorear el estado de los sensores.
#### 4.2.2.2. Interface Layer.

Este Interface Layer define las interfaces de comunicación del sistema. Incluye APIs REST y eventos que permiten interactuar con el sistema. Los puntos de comunicación son:

* **API REST de Sensores:** Permite registrar, actualizar y consultar el estado de los sensores.
* **Mensajes/Eventos de Telemetría:** Comunicación para enviar y recibir datos de los sensores en tiempo real.
* **Notificaciones de Alertas:** Eventos que disparan alertas cuando se detectan condiciones fuera de rango.
#### 4.2.2.3. Application Layer.

En este caso, el Application Layer maneja:

* **Registro de Sensores:** Maneja la creación y registro de nuevos sensores en el sistema.
* **Recepción de Telemetría:** Procesa los datos recibidos por los sensores y genera alertas si es necesario.
* **Notificaciones de Alertas:** Coordina la emisión de notificaciones a los administradores en caso de alertas críticas.
#### 4.2.2.4. Infrastructure Layer.

Este apartado se encarga de la persistencia y comunicación externa. Aquí se incluyen:

* **Base de Datos de Sensores:** Donde se almacenan los registros de los sensores, la telemetría y las alertas.
* **Sistemas de Notificación:** Mecanismos para enviar notificaciones de alerta por diferentes medios (email, SMS).
* **Integración con sistemas de monitoreo:** Comunicación con plataformas externas que reciben los datos de los sensores.

#### 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams.
![C4 Diagrama de Componentes](./assets/chapter4_img/bounded_context_sensor.jpeg)
#### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.
![Diagrama de clases_sensor](./assets/chapter4_img/sensor_bounded_context-class_diagram.png)
##### 4.2.2.7.2. Bounded Context Database Design Diagram.
![Diagrama de base_de_datos_sensor](./assets/chapter4_img/sensor_bounded_context-database_diagram.png)
### 4.2.3. Bounded Context: Viajes

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Viaje</td>
        <td class="tg-0pky" colspan="3">Representa un viaje realizado por un usuario en el sistema</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">viajeId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Conductor</td>
      <td class="tg-0lax">iniciarViaje()</td>
    </tr>
    <tr>
      <td class="tg-0lax">origen</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">EstadoViaje</td>
      <td class="tg-0lax">finalizarViaje()</td>
    </tr>
    <tr>
      <td class="tg-0lax">destino</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">HistorialViaje</td>
      <td class="tg-0lax">actualizarEstado()</td>
    </tr>
    <tr>
      <td class="tg-0lax">fecha inicio</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">fecha fin</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">estado</td>
      <td class="tg-0lax">EstadoViaje</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">conductor</td>
      <td class="tg-0lax">Conductor</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">Conductor</td>
        <td class="tg-0pky" colspan="3">Representa a un conductor que puede ser asignado a uno o más viajes en el sistema</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">conductorId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Viaje</td>
      <td class="tg-0lax">asignarViaje()</td>
    </tr>
    <tr>
      <td class="tg-0lax">nombre</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">licencia</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">telefono</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">EstadoViaje</td>
        <td class="tg-0pky" colspan="3">Representa el estado de un viaje en un momento dado, incluyendo una descripción y un timestamp</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">estadoViajeId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Viaje</td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">nombre</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">descripcion</td>
      <td class="tg-0lax">String</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">timestamp</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

<table class="tg">
  <thead>
    <tr>
      <th class="tg-fymr" colspan="2">Nombre</th>
      <th class="tg-0pky" colspan="3">Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-fymr" colspan="2" style="text-align:center">HistorialViaje</td>
        <td class="tg-0pky" colspan="3">Representa el historial de cambios en el estado de un viaje, registrando cada cambio con su fecha y hora</td>
    </tr>
    <tr>
    <td class="tg-fymr" colspan="2">Atributos</td>
    <td class="tg-fymr" colspan="2">Relaciones</td>
    <td class="tg-fymr" rowspan="2">Metodos</td>
    </tr>
    <tr>
      <td class="tg-1wig">Nombre</td>
      <td class="tg-1wig">Tipo de dato</td>
      <td class="tg-1wig">Tipo</td>
      <td class="tg-1wig">Clases/Enums</td>
    </tr>
    <tr>
      <td class="tg-0lax">historialViajeId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">Viaje</td>
      <td class="tg-0lax">registrarCambio()</td>
    </tr>
    <tr>
      <td class="tg-0lax">viajeId</td>
      <td class="tg-0lax">Int</td>
      <td class="tg-0lax">Agregación</td>
      <td class="tg-0lax">EstadoViaje</td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">fechaCambio</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">timestamp</td>
      <td class="tg-0lax">Date</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">estadoAnterior</td>
      <td class="tg-0lax">EstadoViaje</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
    <tr>
      <td class="tg-0lax">estadoNuevo</td>
      <td class="tg-0lax">EstadoViaje</td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
      <td class="tg-0lax"></td>
    </tr>
  </tbody>
</table>

#### 4.2.3.1. Domain Layer.
Para este bounded context se definen las entidades principales, los agregados y las políticas que rigen el comportamiento de los viajes.

**Entidades principales:**

* **Viaje:** Representa un viaje de un conductor desde un origen hasta un destino
* **Conductor:** Persona responsable de realizar el viaje
* **EstadoViaje:** Representa los distintos estados que un viaje puede tener (e.g., "En curso", "Finalizado", "Cancelado")

**Agregados:**

El Viaje es el agregado raíz que contiene la lógica para gestionar su ciclo de vida completo, incluyendo su asociación con un Conductor y la actualización de su Estado.
#### 4.2.3.2. Interface Layer.

* **API REST:** Se expone a través de servicios web que permiten a la empresa registrar nuevos viajes, actualizar estados, y a los conductores consultar sus viajes asignados.
* **UI Móvil:** La aplicacione móvile permite la interacción con la funcionalidad del sistema, proporcionando interfaces amigables para visualizar los viajes, gestionarlos y realizar cambios de estado.
#### 4.2.3.3. Application Layer.

* **Servicio de Gestión de Viajes:** Orquesta la creación y actualización de viajes.
* **Servicio de Actualización de Estado:** Permite a los conductores actualizar el estado de un viaje.
* **Servicio de Consultas de Historial de Viajes:** Permite consultar el historial completo de los viajes de un conductor.
#### 4.2.3.4. Infrastructure Layer.

* **Base de datos relacional:** Almacena la información de los viajes, conductores y sus estados.
* **Servicios de monitoreo:** Notifica eventos críticos relacionados con el estado de los viajes.
#### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams.
![C4 Diagrama de Componentes](./assets/chapter4_img/bounded_context_travel.jpeg)
#### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams.
![Diagrama de clases_viajes](./assets/chapter4_img/travel_bounded_context-class_diagram.png)
###### 4.2.3.7.2. Bounded Context Database Design Diagram.
![Diagrama de base_de_datos_sensor](./assets/chapter4_img/travel_bounded_context-database_diagram.png)
# Capítulo V: Solution UI/UX Design
## 5.1. Style Guidelines
### 5.1.1. General Style Guidelines
### 5.1.2. Web, Mobile and IoT Style Guidelines
## 5.2. Information Architecture
### 5.2.1. Organization Systems
### 5.2.2. Labeling Systems
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems
### 5.2.5. Navigation Systems
## 5.3. Landing Page UI Design

En el siguiente apartado se abordará el diseño de la interfaz de usuario de la página de aterrizaje, la primera impresión visual y funcional que los usuarios tienen al interactuar con un sitio web. Este diseño tiene como objetivo captar la atención, guiar a los usuarios hacia una acción específica y ofrecer una experiencia intuitiva. Se enfoca en la disposición efectiva de los elementos visuales, como los llamados a la acción (CTAs), contenido relevante y diseño responsivo, asegurando que la página sea atractiva, fácil de navegar y optimizada para convertir visitantes en usuarios o clientes de FastPorte.

### 5.3.1. Landing Page Wireframe

Se han designado 5 secciones principales para la realización del Landing Page. En primer lugar, la sección Principal, la cual será la primera que verá el visitante de la página. En está sección se realiza una pregunta para llamar la atención de los visitantes sobre sus necesidades específicas. Asimismo, se agrega un botón como *Call to Action* para que puedan acceder a las soluciones que se han desarrollado. En segundo lugar, la sección Características donde se detalla los aspectos más importantes de la aplicación y lo que ofrece la Startup. Además, en esta sección se visualiza los beneficios generales para brindar mayor detalle sobre FastPorte y lo que ofrece para cada tipo de usuario. En tercer lugar, la sección Descarga donde se presenta el *Call to Action* principal mostrando la disponibilidad de FastPorte en dispositivos móviles también. En cuarto lugar, la sección Sobre nosotros donde los visitantes podrán conocer quienes son los creadores de FastPorte. Igualmente, podrá visualizar los testimonios de gente que ya ha usado FastPorte con anterioridad y como les ha servido. Finalmente, la sección Contáctanos la cual ofrece un formulario para poder contactarse con FastPorte con el fin de solicitar información o contratar los servicios.

![Landing Page Wireframe](assets/capitulo5/landing_page_wireframe.png)
De igual modo se diseño los Wireframes para la versión mobile con el objetivo de que este disponible una versión responsive de la página de aterrizaje.

![Landing Page Wireframe Mobile](assets/capitulo5/landing_page_wireframe_mobile.png)

### 5.3.2. Landing Page Mock-up

A continuación, se muestra la representación visual detallada de cómo se verá y funcionará la página de aterrizaje del sitio web de FastPorte. Este prototipo estático ofrece una vista previa del diseño final, permitiendo a los diseñadores y partes interesadas evaluar la disposición de los elementos, la jerarquía visual y la estética general antes de pasar a la fase de desarrollo. El _mock-up_ es clave para garantizar que la estructura, los colores, las tipografías y los componentes interactivos se alineen con los objetivos de la página, facilitando correcciones tempranas y decisiones basadas en una visión clara del producto final.

![Landing Page Mock-up](assets/capitulo5/landing_page_mockup.png)

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

En este apartado se presentan los wireflows correspondientes a las versiones móvil y web de la aplicación FastPorte. Estos diagramas detallan el recorrido que los usuarios realizan dentro de la plataforma, desde su interacción inicial hasta la finalización de las principales tareas. Mediante los wireflows, se busca proporcionar una visión clara de las transiciones entre las diferentes pantallas, lo que facilita una mejor comprensión de la experiencia de usuario tanto en la versión móvil como en la web. Para esta sección, se han considerado los user goals (UG) de los roles de Conductor y Supervisor, los cuales representan las principales funcionalidades y tareas que estos usuarios llevan a cabo en la aplicación. A continuación, se detalla cada uno de los user goals y su respectivo wireflow:

##### TaskFlow
-	**Conductor**
	- Registrarse en la aplicación
	- Iniciar sesión en la aplicación
	- Recuperar contraseña de la cuenta
	- Editar información básica del perfil
	- Visualizar información del viaje en curso
	- Revisar notificaciones sobre viajes
	- Visualizar los viajes por estado
	- Obtener contactos de soporte de la app
-	**Supervisor**
	- Registrarse en la aplicación
	- Iniciar sesión en la aplicación
	- Recuperar contraseña de la cuenta
	- Visualizar estado del viaje en curso
	- Editar información del perfil
	- Asignar un viaje a un conductor
	- Visualizar los viajes por estado
	- Visualizar notificaciones
	- Obtener contacto del soporte

##### Conductor

Para el wireflow del Conductor, se ha decidido utilizar la versión móvil, ya que esta será la principal herramienta que emplearán. A continuación, se describen los user goals correspondientes y sus respectivos wireflows:

###### UG01: Registrarse en la aplicación

El conductor accede a la aplicación y selecciona la opción de registrarse. Luego de ello, se le pedirá ingresar un código que corresponde al sensor que se le ha asignado. Una vez validado esto, tendrá que elegir su tipo de perfil, en este caso conductor, para posteriormente completar su información personal y de contacto. Asímismo, deberá aceptar los términos y condiciones de la aplicación. Por último, confirma la creación de la cuenta.

![Wireflow_Conductor_1](./assets/capitulo5/wireflow/mobile%20app/Conductor_1.png)

###### UG02: Iniciar sesión en la aplicación

Para iniciar sesión en la aplicación, deberá ingresar su correo electrónico y contraseña.  Una vez validadas sus credenciales, se le redirigirá a la pantalla principal de la aplicación donde podrá acceder al menú de opciones.

![Wireflow_Conductor_2.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_2.png)

###### UG03: Recuperar contraseña de la cuenta

En caso de olvidar su contraseña, el conductor podrá recuperarla ingresando su correo electrónico. Posteriormente, se le mostrará una vista para ingresar un nuevo password y confirmarlo. Una vez realizado este proceso, se le notificará que la contraseña ha sido actualizada con éxito. 

![Wireflow_Conductor_3.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_3.png)

###### UG04: Editar información básica del perfil

El conductor podrá editar su información personal y de contacto en cualquier momento. Para ello, deberá acceder a la sección de perfil y seleccionar la opción de editar. Posteriormente, podrá modificar los campos que desee y guardar los cambios realizados.

![Wireflow_Conductor_4.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_4.png)

###### UG05: Visualizar información del viaje en curso

Al iniciar sesión, el conductor podrá ver dos posibles vistas: en caso no esté en un viaje en curso, se le mostrarán sus viajes recientes en la pantalla de home. En caso de estar en un viaje, podrá visualizar la información del mismo, como el origen y destino. Pero principalmente podrá ver la información del sensor que lleva consigo, como la temperatura y la presión, si hay fuga de gas y el nivel de humedad.

![Wireflow_Conductor_5.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_5.png)

###### UG06: Revisar notificaciones sobre viajes

El conductor podrá revisar las notificaciones sobre es estado de sus viajes: si le asignan uno o si cancelan uno que tenía programado. Para ello, deberá acceder a la sección de notificaciones en la aplicación. Allí podrá ver los mensajes recibidos y también las alertas generadas por los sensores.

![Wireflow_Conductor_6.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_6.png)

###### UG07: Visualizar los viajes por estado

El conductor podrá visualizar los viajes que ha realizado y los que tiene programados. Para ello, deberá acceder a la sección de viajes en la aplicación. Allí podrá ver los detalles de cada viaje, como el origen, destino, fecha y hora.

![Wireflow_Conductor_7.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_7.png)

###### UG08: Obtener contactos de soporte de la app

En caso de necesitar ayuda o soporte técnico, el conductor podrá acceder a la sección de soporte en la aplicación. Allí encontrará el número de teléfono y correo electrónico de soporte técnico para comunicarse en caso de emergencia o dudas, así como también, redes sociales de contacto como WhatsApp.

![Wireflow_Conductor_8.png](./assets/capitulo5/wireflow/mobile%20app/Conductor_8.png)

Enlace a Lucidchart: [Wireflows - Conductor](https://lucid.app/lucidchart/bee2da3c-eaf6-41b4-aa3c-b9cbfc69825e/edit?invitationId=inv_cb01a0c3-90db-4460-b553-8d064ac80e6b)

##### Supervisor

###### UG09: Registrarse en la aplicación

El supervisor accede a la aplicación y selecciona la opción de registrarse. Luego de ello, se le pedirá ingresar un código que corresponde al sensor que se le ha asignado. Una vez validado esto, tendrá que elegir su tipo de perfil, en este caso supervisor, para posteriormente completar su información personal y de contacto. Asímismo, deberá aceptar los términos y condiciones de la aplicación. Por último, confirma la creación de la cuenta como supervisor.

![Wireflow_Supervisor_9.png](./assets/capitulo5/wireflow/web%20app/Supervisor_9.png)

###### UG10: Iniciar sesión en la aplicación

Para iniciar sesión en la aplicación, deberá ingresar su correo electrónico y contraseña.  Una vez validadas sus credenciales, se le redirigirá a la pantalla principal de la aplicación donde podrá acceder al menú de opciones que tiene disponibles en su rol de supervisor.

![Wireflow_Supervisor_10.png](./assets/capitulo5/wireflow/web%20app/Supervisor_10.png)

###### UG11: Recuperar contraseña de la cuenta

En caso de olvidar su contraseña, el supervisor podrá recuperarla ingresando su correo electrónico. Posteriormente, se le mostrará una vista para ingresar un nuevo password y confirmarlo. Una vez realizado este proceso, le aparecerá un mensaje que diga que la contraseña ha sido actualizada con éxito y, por ende, podrá volver a iniciar sesión con sus nuevas credenciales.

![Wireflow_Supervisor_11.png](./assets/capitulo5/wireflow/web%20app/Supervisor_11.png)

###### UG12: Visualizar estado del viaje en curso

El supervisor podrá visualizar el estado del viaje en curso, así como también la información del conductor asignado y los detalles del viaje. Para ello, al iniciar sesión en la aplicación y si hay un viaje en curso, podrá visualizar el estado del mismo en la pantalla principal y se mostrará información del sensor que lleva consigo el conductor. En caso no haya algún problema, la aplicación mostrará un mensaje de que todo está en orden. Caso contrario, se mostrará una alerta con la información del problema detectado.

![Wireflow_Supervisor_12.png](./assets/capitulo5/wireflow/web%20app/Supervisor_12.png)

###### UG13: Editar información del perfil

El supervisor podrá editar su información personal y de contacto en cualquier momento. Para ello, deberá acceder a la sección de perfil y seleccionar la opción de editar. Posteriormente, podrá modificar los campos que desee y guardar los cambios realizados.

![Wireflow_Supervisor_13.png](./assets/capitulo5/wireflow/web%20app/Supervisor_13.png)

###### UG14: Asignar un viaje a un conductor

El supervisor podrá asignar un viaje a un conductor en la aplicación. Para ello, deberá acceder a la sección de conductores, buscar algún conductor que tenga a su carga, seleccionarlo y posteriormente rellenar un formulario con la información relevante para que pueda realizar su viaje. Finalmente, cuando todo ha sido completado de manera correcta, se mostrará un mensaje que diga que el conductor ha sido notificado de su nuevo viaje.

![Wireflow_Supervisor_14.png](./assets/capitulo5/wireflow/web%20app/Supervisor_14.png)

###### UG15: Visualizar los viajes por estado

El supervisor podrá visualizar los viajes que tienen estado pendiente y los que ya se han realizado. Para acceder a este apartado, deberá seleccionar la sección de viajes en la aplicación. Allí podrá ver los detalles de cada viaje, como el origen, destino, fecha y hora.

![Wireflow_Supervisor_15.png](./assets/capitulo5/wireflow/web%20app/Supervisor_15.png)

###### UG16: Visualizar notificaciones

El supervisor podrá visualizar las notificaciones que recibe en la aplicación. Para ello, deberá acceder a la sección de notificaciones. Allí será notificado acerca del estado de los viajes y también las alertas generadas por los sensores.

![Wireflow_Supervisor_16.png](./assets/capitulo5/wireflow/web%20app/Supervisor_16.png)

###### UG17: Obtener contacto del soporte

En caso de necesitar ayuda o soporte técnico, el supervisor podrá acceder a la sección de soporte en la aplicación. Allí encontrará el número de teléfono y correo electrónico de soporte técnico para comunicarse en caso de emergencia o dudas.

![Wireflow_Supervisor_17.png](./assets/capitulo5/wireflow/web%20app/Supervisor_17.png)

Enlace a Figma: [Wireflows - Supervisor](https://lucid.app/lucidchart/bee2da3c-eaf6-41b4-aa3c-b9cbfc69825e/edit?viewport_loc=-28132%2C3528%2C6656%2C3260%2CxHlbvWFvACDV&invitationId=inv_cb01a0c3-90db-4460-b553-8d064ac80e6b)

### 5.4.3. Applications Mock-ups

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
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration
## 6.2. Landing Page, Services & Applications Implementation
### 6.2.1. Sprint 1
#### 6.2.1.1. Sprint Planning 1
#### 6.2.1.2. Sprint Backlog 1
#### 6.2.1.3. Development Evidence for Sprint Review
#### 6.2.1.4. Testing Suite Evidence for Sprint Review
#### 6.2.1.5. Execution Evidence for Sprint Review
#### 6.2.1.6. Services Documentation Evidence for Sprint Review
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
