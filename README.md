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

Diagrama del modelado de la base de datos para el bounded context de Transport management:

![diagrama de base de datos transport management](./assets/chapter4_img/transport_management_database_diagram.png)

### 4.2.4. Bounded Context: Alerts system

Este Bounded Context se encarga de la gestión y envío de alertas y notificaciones en tiempo real a conductores y supervisores cuando se detectan problemas críticos a través de los sensores de monitoreo. El sistema prioriza las alertas según su criticidad y asegura que los usuarios clave reciban la información necesaria para tomar acción.

#### 4.2.4.1. Domain Layer.

En esta capa se encuentran las entidades y objetos de valor que representan los conceptos fundamentales relacionados con la gestión de alertas y notificaciones.

* **Alerta:** Entidad principal que encapsula los detalles de una situación crítica detectada por el sistema de sensores. Una alerta tiene atributos como el tipo de alerta, el sensor que la disparó, la prioridad, y el tiempo en el que fue generada.
* **Notificación:** Objeto de valor que contiene la información enviada a los usuarios (conductores y supervisores) respecto a una alerta generada. Incluye el destinatario, el canal de comunicación y el estado de la notificación (enviada, recibida, pendiente).
* **Incidente:** Objeto de valor que registra un problema crítico detectado por los sensores. Los incidentes pueden incluir fallos en el sistema, situaciones peligrosas o interrupciones en el servicio.
* **Usuario:** Entidad que representa a los conductores y supervisores que reciben las alertas. Cada usuario tiene atributos como su rol (conductor o supervisor), preferencias de notificación, y disponibilidad.
* **Sensor:** Dispositivo que recoge datos del entorno. Cada sensor tiene atributos como su identificador, tipo, y los umbrales críticos que, al ser excedidos, generan una alerta.

#### 4.2.4.2. Interface Layer.

Esta capa gestiona las interacciones entre el sistema de alertas y las interfaces externas, permitiendo la notificación en tiempo real de los incidentes a conductores y supervisores.

* **Interfaz de Notificaciones:** Proporciona la capacidad de visualizar y gestionar las notificaciones enviadas a los usuarios. Los conductores y supervisores reciben alertas en sus dispositivos móviles o aplicaciones internas.
* **Interfaz de Consulta de Historial de Alertas:** Permite a los supervisores acceder a un registro detallado de alertas generadas y su estado (enviada, recibida, o fallida).
* **Interfaz de Configuración de Sensores y Alertas:** Permite a los administradores del sistema configurar los sensores y definir los umbrales que disparan alertas.

#### 4.2.4.3. Application Layer.

La capa de aplicación coordina la lógica que gestiona el flujo de alertas y notificaciones en el sistema.

* **Generación de Alertas:** Módulo que orquesta la creación de alertas cuando los datos de los sensores exceden los umbrales críticos definidos.
* **Envío de Notificaciones:** Responsable de enviar las notificaciones de alertas a los conductores y supervisores. Este módulo asegura que las notificaciones se entreguen a tiempo y monitorea el estado de las mismas.
* **Gestión de Incidentes:** Se encarga de registrar y gestionar incidentes críticos detectados, permitiendo a los supervisores tomar acciones correctivas en tiempo real.
* **Prioridad de Alertas:** Lógica que organiza y prioriza las alertas cuando varios eventos críticos ocurren simultáneamente, para garantizar una respuesta eficiente.

#### 4.2.4.4. Infrastructure Layer.

La capa de infraestructura se encarga de la operación técnica del sistema, asegurando la persistencia de los datos y la conectividad entre componentes.

* **Repositorio de Alertas:** Almacena los datos de las alertas generadas, incluyendo la fecha, tipo de alerta, sensor asociado, y el estado de la notificación.
* **Servicio de Notificaciones:** Componente encargado de enviar las notificaciones a través de diversos canales (SMS, email, aplicaciones internas) y gestionar el estado de entrega.
* **Servicio de Monitoreo de Sensores:** Recibe datos en tiempo real de los sensores, los analiza y genera alertas cuando los valores críticos son excedidos.
* **Integración con el Contexto de Monitoreo de Seguridad:** Permite la conexión con el sistema de monitoreo de seguridad para compartir datos sobre incidentes y generar alertas en caso de condiciones peligrosas.

#### 4.2.4.6. Bounded Context Software Architecture Component Level Diagrams.

Diagrama de componentes para el bounded context de Alerts System:

![diagrama de componentes alerts system](assets/chapter4_img/alertSystemComponentDiagram.jpeg)

#### 4.2.4.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.4.7.1. Bounded Context Domain Layer Class Diagrams.

Diagrama de clases para el bounded context de Alerts System:

![diagrama de clases de alertas](assets/chapter4_img/alerts_system_class_diagram.png)

###### 4.2.4.7.2. Bounded Context Database Design Diagram.

Diagrama del modelado de la base de datos para el bounded context de Alerts System:

![diagrama de base de datos alertas](assets/chapter4_img/alerts_system_database_diagram.png)

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
### 5.3.1. Landing Page Wireframe
### 5.3.2. Landing Page Mock-up
## 5.4. Applications UX/UI Design
### 5.4.1. Applications Wireframes
### 5.4.2. Applications Wireflow Diagrams
### 5.4.4. Applications Mock-ups
### 5.4.4. Applications User Flow Diagrams
## 5.5. Applications Prototyping
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
