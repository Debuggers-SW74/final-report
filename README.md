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
#### Sección: WS74
#### Profesor: Angel Augusto Velasquez Nuñez
#### Producto: FastPorte
#### Ciclo: 2024-02
<h4 align="center"> Agosto, 2024</h4>

___
# Registro de versiones del informe

| Versión | Fecha      | Autor            | Descripción de modificación                                                |
|---------|------------|------------------|----------------------------------------------------------------------------|
| 1.0     | 22/08/2024 | Sebastián Lévano | Creación del archivo base en Markdown para el desarrollo del Final Project |
| 1.1     | 26/08/2024 | Anthony Botello | Adición del capítulo 1 |

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

---

# Student Outcome

| Criterio Específico                                                                             | Acciones Realizadas | Conclusiones |
|-------------------------------------------------------------------------------------------------|---------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                |                     |              |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. |                     |              |

---
<div align="justify">

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
| Falta descripción | ![Josué Perfil](assets/capitulo1/integrantes/josue.png) |

| Integrante                                                                                                                                                                                                                                                                                                                                                                                                       | Botello Saldarriaga, Anthony Jean Pierre                    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| Tengo 23 años y soy estudiante de Ingeniería de Software con conocimientos y habilidades en distintos lenguajes de programación. Actualmente curso el noveno ciclo de la carrera y mi meta es ser un profesional destacado el cual rija sus decisiones por sus valores y el bien de la empresa donde labore. Me interesa el desarrollo de la tecnología y los avances que existen en la inteligencia artificial. | ![Anthony Perfil](assets/capitulo1/integrantes/anthony.jpg) |

| Integrante        | Chero Eme, Eduardo Andre                                    |
|-------------------|-------------------------------------------------------------|
| Falta descripción | ![Eduardo Perfil](assets/capitulo1/integrantes/eduardo.png) |

| Integrante                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Lévano Cavero, Eduardo Sebastián                                |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| Mi nombre es Sebastián, tengo 21 años y soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Elegí esta carrera porque me fascina crear y diseñar procesos que faciliten procesos complejos. Por ello, cuando tengo un poco de tiempo libre lo uso para relajarme y para aprender más de lo que me apasiona, la programación, se puede decir que es uno de mis hobbies. Además, de la programación también disfruto de jugar vóley, fútbol o algún videojuego con mis amigos. | ![Sebastián Perfil](assets/capitulo1/integrantes/sebastian.jpg) |

| Integrante        | Moreno Rosales, Claudio Jesús                               |
|-------------------|-------------------------------------------------------------|
| Falta descripción | ![Claudio Perfil](assets/capitulo1/integrantes/claudio.png) |

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

</div>

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping:
## 3.2. User Stories

| Epic ID | Título                                          | Descripción                                                                                                                                                                                                                                                 |
|---------|-------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP-01   | Desarrollo del Landing Page                     | Se centra en el desarrollo del sitio web que sirve de presentación para la empresa y el producto que ofrece. Se implementan diversas secciones que permiten al usuario conocer más acerca de FastPorte y como el producto puede satisfacer sus necesidades. |
| EP-02   | Desarrollo del Backend                          | Se enfoca en el desarrollo backend de la aplicación y las funcionalidades que debe poseer. Asimismo, como serán denominados los *endpoints* para su futura implementación en las aplicaciones web y móvil.                                                  |
| EP-03   | Conexión con el sensor                          | La integración del sensor instalado en el vehículo con el backend para almacenar la información que reporta y como se visualizará en el frontend.                                                                                                           |
| EP-04   | Autenticación y Registro                        | Abarca los aspectos iniciales del uso de la aplicación web y móvil. Los pasos de Registro e Inicio Sesión de los usuarios en la aplicación.                                                                                                                 |
| EP-05   | Servicios de viajes                             | Engloba las funcionalidades que brindan tanto la aplicación móvil como web respecto a los viajes programados para los transportistas de material peligroso.                                                                                                 |
| EP-06   | Notificaciones y Alertas                        | La gestión de las notificaciones y alertas recibidas por los servicios de transporte brindados o en caso de advertencia por la detección de un inconveniente por parte del sensor.                                                                          |
| EP-07   | Monitorización y Gestión del material peligroso | Las funcionalidades del sensor para captar y enviar la información detectada acerca de los materiales peligrosos.                                                                                                                                           |

| User Story ID | Título                                                                             | Descripción                                                                                                                                                                                                                      | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Epic ID |
|---------------|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| US-001        | Registro de compañía                                                               | **Como** compañía<br>**Quiero** registrarme en la aplicación<br>**Para** supervisar a los transportistas a mi cargo                                                                                                              | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía no está registrado<br>**Y** se encuentra en la vista inicial de la aplicación<br>**Cuando** hace click en el botón "Registrarse"<br>**Y** ingresa el código del sensor de su vehículo<br>**Y** elige registrarse como "Compañía"<br>**Y** completa los datos solicitados correctamente<br>**Y** hace click en el botón "Continuar"<br>**Entonces** el sistema registra el usuario como *Compañía*<br>**Y** el usuario puede iniciar sesión con las credenciales creadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP-04   |
| US-002        | Registro de transportista                                                          | **Como** transportista<br>**Quiero** registrarme en la aplicación<br>**Para** recibir información de los viajes que debo realizar                                                                                                | **Escenario Nº1:**<br><br>**Dado que** el transportista no está registrado<br>**Y** se encuentra en la vista inicial de la aplicación<br>**Cuando** hace click en el botón "Registrarse"<br>**Y** ingresa el código del sensor de su vehículo<br>**Y** elige registrarse como "Transportista"<br>**Y** completa los datos solicitados correctamente<br>**Y** hace click en el botón "Continuar"<br>**Entonces** el sistema registra el usuario como *Transportista*<br>**Y** el usuario puede iniciar sesión con las credenciales creadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-04   |
| US-003        | Inicio de sesión                                                                   | **Como** usuario de la aplicación<br>**Quiero** iniciar sesión en la aplicación<br>**Para** acceder a las funcionalidades de la aplicación                                                                                       | **Escenario Nº1:**<br><br>**Dado que** el usuario de la aplicación desea iniciar sesión<br>**Y** se encuentra en la vista inicial de la aplicación<br>**Cuando** hace click en el botón "Iniciar sesión"<br>**Y** ingresa sus credenciales<br>**Y** hace click en el botón "Continuar"<br>**Entonces** accede a las funcionalidades de la aplicación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP-04   |
| US-004        | Registrar un viaje                                                                 | **Como** compañía<br>**Quiero** registrar un viaje<br>**Para** notificar al transportista los servicios que debe realizar                                                                                                        | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía desea registrar un viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** hace click en el botón "Transportistas"<br>**Y** elige al transportista que realizará la entrega<br>**Y** completa la información del viaje<br>**Y** hace click en el botón "Enviar"<br>**Entonces** el sistema crea el viaje<br>**Y** notifica al transportista sobre el viaje que debe realizar                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-05   |
| US-005        | Viajes pendientes                                                                  | **Como** usuario de la aplicación<br>**Quiero** visualizar los viajes pendientes<br>**Para** gestionar los viajes que se deben realizar                                                                                          | **Escenario Nº1:**<br><br>**Dado que** el usuario de la aplicación desea visualizar los viajes pendientes<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** hace click en el botón "Viajes"<br>**Entonces** el sistema muestra los viajes pendientes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EP-05   |
| US-006        | Historial de Viajes                                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar el historial de viajes<br>**Para** llevar un registro de los viajes completados                                                                                       | **Escenario Nº1:**<br><br>**Dado que** el usuario de la aplicación desea visualizar el historial de viajes<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha hecho click en el botón "Viajes"<br>**Cuando** hace click en la subsección "Historial"<br>**Entonces** el sistema muestra los viajes realizados del historial                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | EP-05   |
| US-007        | Concluir viaje                                                                     | **Como** compañía<br>**Quiero** concluir los viajes que ya se han realizado<br>**Para** dar por terminado la tarea del transportista                                                                                             | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía desea  concluir un viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha hecho click en el botón "Viajes"<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** hace click en el botón "Hecho" del viaje correspondiente<br>**Entonces** el sistema concluye el viaje<br>**Y** notifica al transportista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | EP-05   |
| US-008        | Cancelar viaje                                                                     | **Como** compañía<br>**Quiero** cancelar un viaje<br>**Para** descartar un viaje creado erróneamente                                                                                                                             | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía desea cancelar un viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha hecho click en el botón "Viajes"<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** hace click en el botón "Cancelar" del viaje correspondiente<br>**Entonces** el sistema elimina el viaje<br>**Y** notifica al transportista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | EP-05   |
| US-009        | Buscar un transportista                                                            | **Como** compañía<br>**Quiero** buscar un transportista<br>**Para** asignarle un viaje                                                                                                                                           | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía desea buscar un transportista<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha dado click en el botón "Transportistas"<br>**Y** ha dado click en la barra de búsqueda<br>**Y** ha ingresado el nombre del transportista o el código del sensor de su vehículo<br>**Cuando** hace click en el ícono de Buscar o presiona la tecla "Enter"<br>**Entonces** el sistema busca y muestra al transportista correspondiente                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | EP-05   |
| US-010        | Visualizar la información del viaje                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar la información de un viaje<br>**Para** revisar algún dato en concreto                                                                                                 | **Escenario Nº1: Visualizar información de un viaje pendiente**<br><br>**Dado que** el usuario de la aplicación desea visualizar la información de un viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha dado click en el botón "Viajes"<br>**Y** ha identificado el viaje en la lista de viajes pendientes<br>**Cuando** hace click en el viaje correspondiente<br>**Entonces** se muestra la información del viaje<br><br>**Escenario Nº2: Visualizar información de un viaje realizado**<br><br>**Dado que** el usuario de la aplicación desea visualizar la información de un viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Y** ha dado click en el botón "Viajes"<br>**Y** ha dado click en la subsección "Historial"<br>**Cuando** hace click en el viaje correspondiente<br>**Entonces** se muestra información del viaje                                                                                                                                                                                                                                                                                             | EP-05   |
| US-011        | Notificar al transportista del nuevo viaje                                         | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si se me ha asignado un viaje                                                                                                                    | **Escenario Nº1: Notificación de un nuevo viaje en la sección Principal**<br><br>**Dado que** el transportista desea ser notificado de un nuevo viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** ingresa a la aplicación<br>**Entonces** le llega una notificación del nuevo viaje asignado<br><br>**Escenario Nº2: Notificación de un nuevo viaje en la sección Notificaciones**<br><br>**Dado que** el transportista desea ser notificado de un nuevo viaje<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** hace click en el ícono de Notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** se muestra la notificación de un nuevo viaje asignado                                                                                                                                                                                                                                                                                                                                                                                                                                               | EP-06   |
| US-012        | Notificar al transportista del viaje concluido                                     | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si mi supervisor conluyó el viaje                                                                                                                | **Escenario Nº1: Notificación de un viaje concluido en la sección Principal**<br><br>**Dado que** el transportista desea ser notificado de un viaje concluido<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** ingresa a la aplicación<br>**Entonces** le llega una notificación del viaje concluido<br><br>**Escenario Nº2: Notificación de un viaje concluido la sección Notificaciones**<br><br>**Dado que** el transportista desea ser notificado de un viaje concluido<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** hace click en el ícono de Notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** se muestra la notificación del viaje concluido                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP-06   |
| US-013        | Notificar al transportista del viaje cancelado                                     | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si un viaje ha sido cancelado                                                                                                                    | **Escenario Nº1: Notificación de un viaje cancelado en la sección Principal**<br><br>**Dado que** el transportista desea ser notificado de un viaje cancelado<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** ingresa a la aplicación<br>**Entonces** le llega una notificación del viaje cancelado<br><br>**Escenario Nº2: Notificación de un viaje cancelado en la sección Notificaciones**<br><br>**Dado que** el transportista desea ser notificado de un viaje cancelado<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** hace click en el ícono de Notificaciones<br>**Entonces** el sistema lista las notificaciones<br>**Y** se muestra la notificación del viaje cancelado                                                                                                                                                                                                                                                                                                                                                                                                                                           | EP-06   |
| US-014        | Visualizar el estado del viaje por el sensor                                       | **Como** usuario de la aplicación<br>**Quiero** visualizar el estado del viaje por el sensor<br>**Para** saber si ha sucedido algún accidente con el material peligroso transportado                                             | **Escenario Nº1:**<br><br>**Dado que** el usuario de la aplicación desea visualizar el estado del viaje por el sensor<br>**Y** ha iniciado sesión en la aplicación<br>**Cuando** ingresa a la aplicación<br>**Entonces** se muestra el estado del viaje por el sensor en la sección Principal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | EP-05   |
| US-015        | Enviar alerta de peligro al transportista                                          | **Como** compañía<br>**Quiero** enviar una alerta de peligro al transportista<br>**Para** alertarlo de algún inconveniente con el material peligroso transportado                                                                | **Escenario Nº1:**<br><br>**Dado que** el supervisor de la compañía desea enviar una alerta de peligro al transportista<br>**Y** ha iniciado sesión en la <br>aplicación<br>**Y** el sensor ha detectado algún inconveniente con el material peligroso transportado<br>**Cuando** el supervisor de la compañía hace click en el  botón "Alerta"<br>**Entonces** el sistema envía una alerta al transportista para advertirle de los inconvenientes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP-06   |
| US-016        | Editar perfil de Usuario                                                           | **Como** usuario de la aplicación<br>**Quiero** modificar mi información<br>**Para** corregir errores o mantenerla actualizada                                                                                                   | **Escenario Nº1:**<br><br>**Dado que** el usuario de la aplicación ha iniciado sesión<br>**Y** ha dado click en el ícono de Perfil<br>**Cuando** hace click en el botón "Editar"<br>**Y** modifica los campos disponibles<br>**Y** hace click en el botón "Guardar"<br>**Entonces** el sistema realiza los cambios <br>**Y** muestra los cambios en la vista "Perfil"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP-05   |
| US-017        | Añadir una compañía a través de un RESTful API                                     | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Compañía* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Compañía* a la aplicación           | **Escenario Nº1: Ingreso de correo único**<br><br>**Dado que** el endpoint `api/v1/company` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve  un recurso de usuario de tipo *Compañía* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Ingreso de correo existente**<br><br>**Dado que** el endpoint `api/v1/company` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico y contraseña<br>**Y** el correo electrónico ya existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                                                                                              | EP-02   |
| US-018        | Añadir un transportista a través de un RESTful API                                 | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Transportista* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Transportista* a la aplicación | **Escenario Nº1: Ingreso de correo único**<br><br>**Dado que** el endpoint `api/v1/driver` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico, número de celular y contraseña<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve un recurso de usuario de tipo *Transportista* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Ingreso de correo existente**<br><br>**Dado que** el endpoint `api/v1/driver` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para nombre, correo electrónico, número de celular y contraseña<br>**Y** el correo electrónico ya existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                                   | EP-02   |
| US-019        | Obtener a una compañía a través de un RESTful API                                  | **Como** desarrollador <br>**Quiero** obtener una compañía mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                                    | **Escenario Nº1: Ingreso de datos existentes**<br><br>**Dado que** el usuario endpoint `api/v1/company/:mail/:password` está disponible<br>**Cuando** una solicitud `GET` se realiza con los parámetros correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Compañía* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Ingreso de datos inexistentes**<br><br>**Dado que** el endpoint `api/v1/company/:mail/:password` está disponible<br>**Cuando** una solicitud `POST` se realiza con los parámetros correo electrónico y contraseña<br>**Y** el correo electrónico no existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *Uno o más valores son incorrectos*                                                                                                                                                                                                                                     | EP-02   |
| US-020        | Obtener a un transportista a través de un RESTful API                              | **Como** desarrollador <br>**Quiero** obtener un transportista mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                                | **Escenario Nº1: Ingreso de datos existentes**<br><br>**Dado que** el usuario endpoint `api/v1/driver/:mail/:password` está disponible<br>**Cuando** una solicitud `GET` se realiza con los parámetros correo electrónico y contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Transportista* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Ingreso de datos inexistentes**<br><br>**Dado que** el endpoint `api/v1/driver/:mail/:password` está disponible<br>**Cuando** una solicitud `POST` se realiza con los parámetros correo electrónico y contraseña<br>**Y** el correo electrónico no existe en el sistema<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *Uno o más valores son incorrectos*                                                                                                                                                                                                               | EP-02   |
| US-021        | Añadir un viaje a través de un RESTful API                                         | **Como** desarrollador <br>**Quiero** agregar un nuevo viaje al sistema mediante una solicitud `POST` al API<br>**Para** registrar nuevos viajes para los transportistas a cargo de la compañía                                  | **Escenario Nº1: Ingreso correcto de datos**<br><br>**Dado que** el endpoint `api/v1/trip` está disponible<br>**Cuando** una solicitud `POST` se realiza con los valores para ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado.<br>**Entonces** se recibe una Respuesta con estado `201`<br>**Y** se devuelve un recurso de usuario de tipo *Viaje* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP-02   |
| US-022        | Obtener los viajes pendientes a través de un RESTful API                           | **Como** desarrollador <br>**Quiero** listar los viajes pendientes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes pendientes a los usuarios                                                                 | **Escenario Nº1: Obtener los viajes pendientes de una compañía**<br><br>**Dado que** el endpoint `api/v1/trip/:companyId/pendingTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador de la compañía que ha iniciado sesión<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía<br><br>**Escenario Nº2: Obtener los viajes pendientes de un transportista**<br><br>**Dado que** el endpoint `api/v1/trip/:driverId/pendingTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del transportista que ha iniciado sesión.<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía      | EP-02   |
| US-023        | Obtener el historial de viajes a través de un RESTful API                          | **Como** desarrollador <br>**Quiero** listar el historial de viajes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes realizados del usuario                                                                   | **Escenario Nº1: Obtener los viajes realizados asignados por una compañía**<br><br>**Dado que** el endpoint `api/v1/trip/:companyId/doneTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador de la compañía que ha iniciado sesión<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía<br><br>**Escenario Nº2: Obtener los viajes realizados de un transportista**<br><br>**Dado que** el endpoint `api/v1/trip/:driverId/doneTrips` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del transportista que ha iniciado sesión.<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Viajes* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía | EP-02   |
| US-024        | Terminar un viaje a través de un RESTful API                                       | **Como** desarrollador <br>**Quiero** dar por terminado un viaje  mediante una solicitud `PATCH` al API<br>**Para** finalizar la tarea del transportista                                                                         | **Escenario Nº1: Finalizar un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId/done` está disponible<br>**Cuando** una solicitud `PATCH` se realiza con el parámetro del identificador del viaje que se va a modificar<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | EP-02   |
| US-025        | Cancelar un viaje a través de un RESTful API                                       | **Como** desarrollador <br>**Quiero** cancelar un viaje  mediante una solicitud `DELETE` al API<br>**Para** que el transportista no realice ese viaje                                                                            | **Escenario Nº1: Cancelar un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId` está disponible<br>**Cuando** una solicitud `DELETE` se realiza con el parámetro del identificador del viaje que se va a eliminar<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP-02   |
| US-026        | Buscar un transportista por su nombre a través de un API                           | **Como** desarrollador <br>**Quiero** listar los transportistas por su nombre mediante una solicitud `GET` al API<br>**Para** mostrar los transportistas al usuario                                                              | **Escenario Nº1: Nombre existente**<br><br>**Dado que** el endpoint `api/v1/driver/search?name=:name` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del transportista<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Transportista* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Nombre inexistente**<br><br>**Dado que** el endpoint `api/v1/driver/search?name=:name` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del transportista<br>**Y** no existe el nombre buscado<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *No se encontró el transportista con el nombre :nombre*                                                                                                                                                                                                                                                 | EP-02   |
| US-027        | Buscar un transportista por el código del sensor de su vehículo a través de un API | **Como** desarrollador <br>**Quiero** listar los transportistas por el código del sensor de su vehículo mediante una solicitud `GET` al API<br>**Para** mostrar los transportistas al usuario                                    | **Escenario Nº1: Código del sensor existente**<br><br>**Dado que** el endpoint `api/v1/driver/search?sensorCode=:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro código del sensor<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo lista de *Transportista* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Código del sensor inexistente**<br><br>**Dado que** el endpoint `api/v1/driver/search?sensorCode=:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro nombre del código del sensor<br>**Y** no existe el código del sensor buscado<br>**Entonces** se recibe una Respuesta con estado `404`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *No se encontró el transportista con el código de sensor :sensorCode*                                                                                                                                                                             | EP-02   |
| US-028        | Obtener un viaje a través de un RESTful API                                        | **Como** desarrollador <br>**Quiero** obtener un viaje  mediante una solicitud `GET` al API<br>**Para** mostrar la información al usuario                                                                                        | **Escenario Nº1: Obtener un viaje**<br><br>**Dado que** el endpoint `api/v1/trip/:tripId` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del identificador del viaje el cual se desea ver la información<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Viaje* en el cuerpo de la Respuesta con valores de ubicación inicial, ubicación final, hora de salida, fecha, descripción, transportista asignado, compañía.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | EP-02   |
| US-029        | Modificar la información de un transportista a través de un RESTful API            | **Como** desarrollador <br>**Quiero** modificar un transportista  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                               | **Escenario Nº1: Editar datos correctamente**<br><br>**Dado que** el endpoint `api/v1/driver/:driverId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico, número de celular o contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Transportista* en el cuerpo de la Respuesta con valores de nombre, correo electrónico, número de celular y contraseña<br><br>**Escenario Nº2: Correo ingresado existente**<br><br>**Dado que** el endpoint `api/v1/driver/:driverId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico, número de celular o contraseña<br>**Y** el nuevo correo electrónico ya ha sido registrado<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                           | EP-02   |
| US-030        | Modificar la información de una compañía a través de un RESTful API                | **Como** desarrollador <br>**Quiero** modificar una compañía  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                                   | **Escenario Nº1: Editar datos correctamente**<br><br>**Dado que** el endpoint `api/v1/company/:companyId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico o contraseña<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de usuario de tipo *Compañía* en el cuerpo de la Respuesta con valores de nombre, correo electrónico y contraseña<br><br>**Escenario Nº2: Correo ingresado existente**<br><br>**Dado que** el endpoint `api/v1/company/:companyId` está disponible<br>**Cuando** una solicitud `PUT` se realiza con los valores para nombre, correo electrónico o contraseña<br>**Y** el nuevo correo electrónico ya ha sido registrado<br>**Entonces** se recibe una Respuesta con estado `400`<br>**Y** se devuelve un mensaje en el cuerpo de la Respuesta: *El correo electrónico ya se encuentra registrado en otro usuario*                                                                                                                                                                                                     | EP-02   |
| US-031        | Captura de datos de Fuga de Gas                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de fuga de gas a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                   | **Escenario Nº1: Captura y envío de datos de Fuga de Gas**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Fuga de Gas<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la compañía puede revisar los datos para enviar una alerta al transportista<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Fuga de Gas<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                           | EP-07   |
| US-032        | Captura de datos de Temperatura                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de temperatura a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                   | **Escenario Nº1: Captura y envío de datos de Temperatura**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Temperatura<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la compañía puede revisar los datos para enviar una alerta al transportista<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Temperatura<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                           | EP-07   |
| US-033        | Captura de datos de Presión                                                        | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de presión a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                       | **Escenario Nº1: Captura y envío de datos de Presión**<br>     <br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Cuando** el sensor detecta la Presión<br>**Entonces** envía los datos en tiempo real al sistema de monitoreo<br>**Y** el supervisor de la compañía puede revisar los datos para enviar una alerta al transportista<br>     <br>**Escenario Nº2: Error en la captura de datos**<br><br>**Dado que** el sensor se encuentra instalado en el vehículo<br>**Y** tiene un problema técnico<br>**Cuando** el sensor intenta capturar los datos de Presión<br>**Entonces** el sistema muestra que ha ocurrido un error<br>**Y** el usuario de la aplicación puede notificarlo para su revisión                                                                                                                                                                                                                                                                                                                                                                                                                       | EP-07   |
| US-034        | Envío de datos de Fuga de Gas a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Fuga de Gas al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                               | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Fuga de Gas<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-07   |
| US-035        | Envío de datos de Temperatura a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Temperatura al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                               | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Temperatura<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-07   |
| US-036        | Envío de datos de Presión a través de un Edge Gateway                              | **Como** desarrollador<br>**Quiero** enviar la información de Presión al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                                   | **Escenario Nº1: Captura y envío de datos**<br><br>**Dado que** el sensor se encuentra encendido<br>**Cuando** el sensor detecta la Presión<br>**Entonces** el Edge Gateway obtiene la información<br>**Y** se almacena en el backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | EP-07   |
| US-037        | Enviar la información del sensor desde el Edge Gateway a través de un RESTful API  | **Como** desarrollador<br>**Quiero** enviar la información del sensor mediante una solicitud `POST` al API<br>**Para** almacenar la información en el backend                                                                    | **Escenario Nº1: Enviar datos del sensor**<br><br>**Dado que** el endpoint `api/v1/sensor/:sensorCode` está disponible<br>**Cuando** una solicitud `POST` se realiza con el parámetro del código del sensor para los valores fuga de gas, temperatura y presión.<br>**Entonces** se recibe una Respuesta con estado `204`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP-03   |
| US-038        | Recibir la información del sensor a través de un RESTful API                       | **Como** desarrollador<br>**Quiero** obtener la información del sensor mediante una solicitud `GET` al API<br>**Para** mostrar la información en la aplicación web o móvil                                                       | **Escenario Nº1: Recibir datos del sensor**<br><br>**Dado que** el endpoint `api/v1/sensor/:sensorCode` está disponible<br>**Cuando** una solicitud `GET` se realiza con el parámetro del código del sensor<br>**Entonces** se recibe una Respuesta con estado `200`<br>**Y** se devuelve un recurso de tipo *Sensor* en el cuerpo de la Respuesta con valores para fuga de gas, temperatura y presión.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | EP-03   |
| US-039        | Sección Principal                                                                  | **Como** visitante de la página de destino<br>**Quiero** saber que me ofrece el producto de inmediato<br>**Para** confirmar si es lo que estoy buscando                                                                          | **Escenario Nº1: Información general**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** se encuentre en la sección Principal<br>**Entonces** ve que es lo que ofrece la aplicación y como contactar con FastPorte<br><br>**Escenario Nº1: Información del Producto**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza que ofrece FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve más detalles del producto y cómo funciona                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | EP-01   |
| US-040        | Sección Características                                                            | **Como** visitante de la página de destino<br>**Quiero** saber cuáles son las características y beneficios<br>**Para** evaluar la contratación de este                                                                           | **Escenario Nº1: Características del Producto**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** se encuentre en la sección Características<br>**Entonces** verá información adicional sobre las características principales de FastPorte<br><br>**Escenario Nº1: Beneficios para cada segmento objetivo**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza las características de FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve cuáles son los beneficios que se ofrece para cada segmento objetivo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | EP-01   |
| US-041        | Sección Sobre Nosotros                                                             | **Como** visitante de la página de destino<br>**Quiero** saber quiénes están involucrados en FastPorte<br>**Para** conocer más sobre esta empresa                                                                                | **Escenario Nº1: Miembros de FastPorte**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** está en la sección Sobre Nosotros<br>**Entonces** ve quiénes son los responsables de hacer FastPorte posible<br><br>**Escenario Nº1: Testimonios de los usuarios**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Y** visualiza quienes son los miembros de FastPorte<br>**Cuando** deslice hacia abajo<br>**Entonces** ve testimonios sobre otros usuarios acerca de FastPorte                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | EP-01   |
| US-042        | Sección Descarga                                                                   | **Como** visitante de la página de destino<br>**Quiero** descargar la aplicación móvil<br>**Para** visualizar la interfaz de esta                                                                                                | **Escenario Nº1: Call to Action**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** esté en la sección Descarga<br>**Entonces** puede descargar la aplicación móvil dando click al botón "Descargar"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | EP-01   |
| US-043        | Sección Contáctanos                                                                | **Como** visitante de la página de destino<br>**Quiero** contactarme con FastPorte<br>**Para** obtener más información del producto                                                                                              | **Escenario Nº1: Call to Action**<br><br>**Dado que** el visitante de la página se encuentra en la página de destino<br>**Cuando** este en la sección Contáctanos<br>**Y** ingrese la información solicitada<br>**Entonces** hace click en el botón "Enviar mensaje" para contactar con FastPorte                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | EP-01   |
## 3.3. Impact Mapping
## 3.4. Product Backlog
Para la calificación de Story Points empleada en el Product Backlog se siguió la sucesión de Fibonacci. En este caso siendo 1 la mínima prioridad en el desarrollo y 8 siendo la máxima.

| # Orden | User Story ID | Título                                                                             | Descripción                                                                                                                                                                                                                      | Story Points (1/2/3/5/8) |
|---------|---------------|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| 1       | US-039        | Sección Principal                                                                  | **Como** visitante de la página de destino<br>**Quiero** saber que me ofrece el producto de inmediato<br>**Para** confirmar si es lo que estoy buscando                                                                          | 3                        |
| 2       | US-040        | Sección Características                                                            | **Como** visitante de la página de destino<br>**Quiero** saber cuáles son las características y beneficios<br>**Para** evaluar la contratación de este                                                                           | 3                        |
| 3       | US-041        | Sección Sobre Nosotros                                                             | **Como** visitante de la página de destino<br>**Quiero** saber quiénes están involucrados en FastPorte<br>**Para** conocer más sobre esta empresa                                                                                | 3                        |
| 4       | US-042        | Sección Descarga                                                                   | **Como** visitante de la página de destino<br>**Quiero** descargar la aplicación móvil<br>**Para** visualizar la interfaz de esta                                                                                                | 3                        |
| 5       | US-043        | Sección Contáctanos                                                                | **Como** visitante de la página de destino<br>**Quiero** contactarme con FastPorte<br>**Para** obtener más información del producto                                                                                              | 3                        |
| 6       | US-001        | Registro de compañía                                                               | **Como** compañía<br>**Quiero** registrarme en la aplicación<br>**Para** supervisar a los transportistas a mi cargo                                                                                                              | 5                        |
| 7       | US-002        | Registro de transportista                                                          | **Como** transportista<br>**Quiero** registrarme en la aplicación<br>**Para** recibir información de los viajes que debo realizar                                                                                                | 5                        |
| 8       | US-003        | Inicio de sesión                                                                   | **Como** usuario de la aplicación<br>**Quiero** iniciar sesión en la aplicación<br>**Para** acceder a las funcionalidades de la aplicación                                                                                       | 5                        |
| 9       | US-004        | Registrar un viaje                                                                 | **Como** compañía<br>**Quiero** registrar un viaje<br>**Para** notificar al transportista los servicios que debe realizar                                                                                                        | 8                        |
| 10      | US-005        | Viajes pendientes                                                                  | **Como** usuario de la aplicación<br>**Quiero** visualizar los viajes pendientes<br>**Para** gestionar los viajes que se deben realizar                                                                                          | 5                        |
| 11      | US-006        | Historial de Viajes                                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar el historial de viajes<br>**Para** llevar un registro de los viajes completados                                                                                       | 5                        |
| 12      | US-007        | Concluir viaje                                                                     | **Como** compañía<br>**Quiero** concluir los viajes que ya se han realizado<br>**Para** dar por terminado la tarea del transportista                                                                                             | 8                        |
| 13      | US-008        | Cancelar viaje                                                                     | **Como** compañía<br>**Quiero** cancelar un viaje<br>**Para** descartar un viaje creado erróneamente                                                                                                                             | 5                        |
| 14      | US-009        | Buscar un transportista                                                            | **Como** compañía<br>**Quiero** buscar un transportista<br>**Para** asignarle un viaje                                                                                                                                           | 3                        |
| 15      | US-010        | Visualizar la información del viaje                                                | **Como** usuario de la aplicación<br>**Quiero** visualizar la información de un viaje<br>**Para** revisar algún dato en concreto                                                                                                 | 5                        |
| 16      | US-011        | Notificar al transportista del nuevo viaje                                         | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si se me ha asignado un viaje                                                                                                                    | 5                        |
| 17      | US-012        | Notificar al transportista del viaje concluido                                     | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si mi supervisor conluyó el viaje                                                                                                                | 5                        |
| 18      | US-013        | Notificar al transportista del viaje cancelado                                     | **Como** transportista<br>**Quiero** recibir una notificación<br>**Para** saber si un viaje ha sido cancelado                                                                                                                    | 5                        |
| 19      | US-014        | Visualizar el estado del viaje por el sensor                                       | **Como** usuario de la aplicación<br>**Quiero** visualizar el estado del viaje por el sensor<br>**Para** saber si ha sucedido algún accidente con el material peligroso transportado                                             | 8                        |
| 20      | US-015        | Enviar alerta de peligro al transportista                                          | **Como** compañía<br>**Quiero** enviar una alerta de peligro al transportista<br>**Para** alertarlo de algún inconveniente con el material peligroso transportado                                                                | 8                        |
| 21      | US-016        | Editar perfil de Usuario                                                           | **Como** usuario de la aplicación<br>**Quiero** modificar mi información<br>**Para** corregir errores o mantenerla actualizada                                                                                                   | 2                        |
| 22      | US-017        | Añadir una compañía a través de un RESTful API                                     | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Compañía* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Compañía* a la aplicación           | 5                        |
| 23      | US-018        | Añadir un transportista a través de un RESTful API                                 | **Como** desarrollador <br>**Quiero** agregar un nuevo usuario de tipo *Transportista* al sistema mediante una solicitud `POST` al API<br>**Para** permitir el acceso de nuevos usuarios de tipo *Transportista* a la aplicación | 5                        |
| 24      | US-019        | Obtener a una compañía a través de un RESTful API                                  | **Como** desarrollador <br>**Quiero** obtener una compañía mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                                    | 5                        |
| 25      | US-020        | Obtener a un transportista a través de un RESTful API                              | **Como** desarrollador <br>**Quiero** obtener un transportista mediante una solicitud `GET` al API<br>**Para** permitir iniciar sesión al usuario                                                                                | 5                        |
| 26      | US-021        | Añadir un viaje a través de un RESTful API                                         | **Como** desarrollador <br>**Quiero** agregar un nuevo viaje al sistema mediante una solicitud `POST` al API<br>**Para** registrar nuevos viajes para los transportistas a cargo de la compañía                                  | 5                        |
| 27      | US-022        | Obtener los viajes pendientes a través de un RESTful API                           | **Como** desarrollador <br>**Quiero** listar los viajes pendientes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes pendientes a los usuarios                                                                 | 5                        |
| 28      | US-023        | Obtener el historial de viajes a través de un RESTful API                          | **Como** desarrollador <br>**Quiero** listar el historial de viajes  mediante una solicitud `GET` al API<br>**Para** mostrar los viajes realizados del usuario                                                                   | 5                        |
| 29      | US-024        | Terminar un viaje a través de un RESTful API                                       | **Como** desarrollador <br>**Quiero** dar por terminado un viaje  mediante una solicitud `PATCH` al API<br>**Para** finalizar la tarea del transportista                                                                         | 8                        |
| 30      | US-025        | Cancelar viaje a través de un RESTful API                                          | **Como** desarrollador <br>**Quiero** cancelar un viaje  mediante una solicitud `DELETE` al API<br>**Para** que el transportista no realice ese viaje                                                                            | 5                        |
| 31      | US-026        | Buscar un transportista por su nombre a través de un API                           | **Como** desarrollador <br>**Quiero** listar los transportistas por su nombre mediante una solicitud `GET` al API<br>**Para** mostrar los transportistas al usuario                                                              | 5                        |
| 32      | US-027        | Buscar un transportista por el código del sensor de su vehículo a través de un API | **Como** desarrollador <br>**Quiero** listar los transportistas por el código del sensor de su vehículo mediante una solicitud `GET` al API<br>**Para** mostrar los transportistas al usuario                                    | 5                        |
| 33      | US-028        | Obtener un viaje a través de un RESTful API                                        | **Como** desarrollador <br>**Quiero** obtener un viaje  mediante una solicitud `GET` al API<br>**Para** mostrar la información al usuario                                                                                        | 5                        |
| 34      | US-029        | Modificar la información de un transportista a través de un RESTful API            | **Como** desarrollador <br>**Quiero** modificar un transportista  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                               | 3                        |
| 35      | US-030        | Modificar la información de una compañía a través de un RESTful API                | **Como** desarrollador <br>**Quiero** modificar una compañía  mediante una solicitud `PUT` al API<br>**Para** editar la información solicitada                                                                                   | 5                        |
| 36      | US-031        | Captura de datos de Fuga de Gas                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de fuga de gas a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                   | 8                        |
| 37      | US-032        | Captura de datos de Temperatura                                                    | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de temperatura a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                   | 8                        |
| 38      | US-033        | Captura de datos de Presión                                                        | **Como** usuario de la aplicación<br>**Quiero** que el sensor capture y envíe los datos de presión a la aplicación web o móvil<br>**Para** monitorear el estado de los materiales peligrosos transportados                       | 8                        |
| 39      | US-034        | Envío de datos de Fuga de Gas a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Fuga de Gas al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                               | 8                        |
| 40      | US-035        | Envío de datos de Temperatura a través de un Edge Gateway                          | **Como** desarrollador<br>**Quiero** enviar la información de Temperatura al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                               | 8                        |
| 41      | US-036        | Envío de datos de Presión a través de un Edge Gateway                              | **Como** desarrollador<br>**Quiero** enviar la información de Presión al Edge Gateway<br>**Para** que la información pueda estar en el backend                                                                                   | 8                        |
| 42      | US-037        | Enviar la información del sensor desde el Edge Gateway a través de un RESTful API  | **Como** desarrollador<br>**Quiero** enviar la información del sensor mediante una solicitud `POST` al API<br>**Para** almacenar la información en el backend                                                                    | 8                        |
| 43      | US-038        | Recibir la información del sensor a través de un RESTful API                       | **Como** desarrollador<br>**Quiero** obtener la información del sensor mediante una solicitud `GET` al API<br>**Para** mostrar la información en la aplicación web o móvil                                                       | 8                        |
