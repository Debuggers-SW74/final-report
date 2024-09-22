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
| ------- | ---------- | ---------------- | -------------------------------------------------------------------------- |
| 1.0     | 22/08/2024 | Sebastián Lévano | Creación del archivo base en Markdown para el desarrollo del Final Project |

---
# Contenido 
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](/README.md#capítulo-i-introducción)
  - [1.1. Startup Profile](/README.md#11-startup-profile)
    - [1.1.1. Descripción de la Startup](/README.md#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](/README.md#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](/README.md#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](/README.md#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](/README.md#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](/README.md#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](/README.md#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](/README.md#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](/README.md#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](/README.md#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](/README.md#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](/README.md#21-competidores)
    - [2.1.1. Análisis competitivo](/README.md#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](/README.md#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](/README.md#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](/README.md#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](/README.md#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](/README.md#223-análisis-de-entrevistas)
  - [2.3. Needfinding](/README.md#23-needfinding)
    - [2.3.1. User Personas](/README.md#231-user-personas)
    - [2.3.2. User Task Matrix](/README.md#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](/README.md#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](/README.md#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](/README.md#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](/README.md#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](/README.md#31-to-be-scenario-mapping)
  - [3.2. User Stories](/README.md#32-user-stories)
  - [3.3. Impact Mapping](/README.md#33-impact-mapping)
  - [3.4. Product Backlog](/README.md#34-product-backlog)
- [Capítulo IV: Solution Software Design](/README.md#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](/README.md#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](/README.md#411-eventstorming)
      - [4.1.1.1 Candidate Context Discovery](/README.md#4111-candidate-context-discovery)
      - [4.1.1.2.  Domain Message Flows Modeling](/README.md#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](/README.md#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](/README.md#412-context-mapping)
    - [4.1.3. Software Architecture](/README.md#413-software-architecture)
    - [4.1.3.1. Software Architecture System Landscape Diagram](/README.md#4131-software-architecture-system-landscape-diagram)
    - [4.1.3.2. Software Architecture Context Level Diagrams](/README.md#4132-software-architecture-context-level-diagrams)
    - [4.1.3.3. Software Architecture Container Level Diagrams](/README.md#4133-software-architecture-container-level-diagrams)
    - [4.1.3.4. Software Architecture Deployment Diagrams](/README.md#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](/README.md#42-tactical-level-domain-driven-design)

---

# Student Outcome

| Criterio Específico                                                                             | Acciones Realizadas | Conclusiones |
| ----------------------------------------------------------------------------------------------- | ------------------- | ------------ |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta.                                |                     |              |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. |                     |              |

---
<div align="justify">

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
|Competidores |<a href ="https://postimg.cc/hz71FmXB"><img src="https://i.postimg.cc/RFgsHQ9N/fastporte.png" alt="Logo FastPorte" width="4000" height="100" /></a> |<a href ="https://postimg.cc/SnydXjv6"><img src="https://i.postimg.cc/W1ZHHkmH/geotab.jpg" alt="Logo Geotab" width="4000" height="100"></a> |<div style="background: black;"><a href ="https://postimg.cc/0zcf7xTL"><img src="https://i.postimg.cc/1zZjh3J5/samsara.png" alt="Logo Samsara" width="5000" height="100"></a></div> |<a href ="https://postimg.cc/jW14kcdc"><img src="https://i.postimg.cc/FRrCzCMM/tankscan.png" alt="Logo TankScan" width="5000" height="100"></a> |
|--|--|--|--|--|
|**Perfil**|||||
|Overview|Plataforma web, aplicación móvil y sensores IoT |Plataforma web, aplicación móvil y dispositivo sensores IoT |Plataforma web y dispositivo GO IoT |Plataforma web, aplicación móvil y dispositivo sensores IoT |
|Ventaja competitiva ¿Qué valor ofrece al cliente?|Proporciona seguridad avanzada en el transporte de gases combustibles mediante sensores que detectan fugas y alertan a los conductores en tiempo real, evitando explosiones y garantizando la seguridad.  |Amplia gama de datos para la seguridad y eficiencia de flotas mediante tecnología de monitoreo avanzada. |Conectividad integral de operaciones mediante una plataforma unificada que ofrece visibilidad y análisis en tiempo real.    |Monitoreo inalámbrico en tiempo real de niveles de tanques con alta precisión y alertas automatizadas.  |
| **Perfil de Marketing** | | | | |
|Mercado objetivo |Transportistas que manejan vehículos de carga peligrosa y empresas que trabajan con materiales peligrosos y necesitan asegurar el transporte seguro de sus productos. |Transporte, logística, servicios públicos, industria de gas, petróleo, minería, distribución de alimentos y reciclaje.    |Empresas con operaciones complejas que requieren gestión integrada de flotas, equipos, sitios y personas.    |Empresas con necesidad de monitoreo de tanques en campo, almacenamiento a granel y subterráneos.  
|Estrategias de marketing |Publicidad en redes sociales. <br><br> Colaboraciones con personas influyentes para promocionar el producto.|Publicidad mediante su página web.   |Publicidad mediante su página web.   |Publicidad mediante su página web.  |
|**Perfil del Producto** | | | | |
|Productos & Servicios |Sensores para supervisar condiciones de materiales peligrosos y aplicaciones móvil y web para la gestión de perfiles de empresas y conductores.    |Dispositivo Geotab GO, plataforma MyGeotab para monitoreo de flotas.       |Plataforma de Samsara, sensores, cámaras, integraciones con otros sistemas.    |Plataforma ATEK Intelligence y monitores de tanque inalámbricos.     |
|Precios & Costos |Dependiente de los requisitos de la empresa que lo solicite.   | Dependiente de los requisitos de la empresa que lo solicite.   | Dependiente de los requisitos de la empresa que lo solicite.   |Dependiente de los requisitos de la empresa que lo solicite.  |
|Canales de distribución (Web y/o Móvil) |Web/Móvil |Web/Móvil |Web |Web/Móvil |
|Tecnologías usadas |Plataforma Web (Angular y Spring Boot), App Móvil (Flutter) y Sensores IoT con análisis de datos en tiempo real. | Monitoreo en tiempo real, análisis de datos avanzados, conectividad IoT.   |IoT, AI, conectividad de sensores, análisis de datos en tiempo real.   | Monitoreo inalámbrico, sensores, conectividad celular o Ethernet.   |
|**Análisis SWOT** | | | | |
|Fortalezas |Seguridad en tiempo real para el transporte de materiales peligrosos y cumplimiento de regulaciones y estándares aplicables.   |Soluciones integradas de seguridad y eficiencia, experiencia en múltiples sectores.   |Amplia escalabilidad y flexibilidad, integración con múltiples sistemas.   |Precisión en la lectura de niveles, facilidad de instalación y escalabilidad.  |
|Debilidades |Necesidad de capacitación para conductores y empresas en el uso del sistema.   |Dependencia de la instalación física del dispositivo.    |Requiere inversión inicial significativa en tecnología.   |Dependencia en la conectividad para la transmisión de datos.  |
|Oportunidades |Integración con sistemas de gestión logística para mejorar la eficiencia operativa.   |Innovación en el monitoreo y análisis predictivo para nuevos sectores.   |Creciente demanda de soluciones integradas en operaciones complejas.  |Expansión en mercados con necesidades críticas de monitoreo remoto.  |
|Amenazas |Competencia con tecnologías emergentes de detección de gases y monitoreo de seguridad.  |Aparición de nuevas tecnologías de monitoreo con costos más bajos.  |Competencia de plataformas con enfoques más específicos o especializados.   |Competidores con tecnologías emergentes en monitoreo de líquidos.    |
<br>

<div style="text-align: center;"> <h4>Tabla: Matriz de análisis de competencia </h4> <img src="https://i.postimg.cc/CKPt3dsq/matriz-competencia.jpg" alt="Matriz de análisis de competencia" /> <p>Fuente: Elaboración propia.</p> </div>
 <br> <br>
 
<div style="text-align: center;"> <h4>Tabla: Matriz de perfil competitivo de los competidores directos </h4> <img src="https://i.postimg.cc/zv5TGGxz/matriz-perfil-competitivo.png" alt="Matriz de perfil competitivo de los competidores directos" /> <p>Fuente: Elaboración propia.</p> </div>
 <br> <br>
 

### 2.1.2. Estrategias y tácticas frente a competidores

1. **Diferenciación mediante Innovación Tecnológica:** Para destacar en el mercado de soluciones para el transporte de materiales peligrosos, es crucial ofrecer una propuesta de valor basada en tecnología avanzada. La estrategia de diferenciación se centra en implementar sensores IoT de última generación para monitorear condiciones críticas, como fugas de gas, temperatura y presión. Esta innovación no solo mejora la seguridad de los conductores y la integridad de la carga, sino que también optimiza la eficiencia operativa. 

2. **Enfoque en la Experiencia del Cliente:** La satisfacción del cliente es un factor clave para competir efectivamente. Implementar una estrategia de atención al cliente superior es esencial para retener clientes y atraer nuevos negocios. Esto incluye ofrecer una plataforma intuitiva para la gestión de sensores y alertas, soporte técnico receptivo y una interfaz de usuario optimizada para empresas y conductores. 

3. **Estrategias de Precio y Valor Agregado:** La competitividad en el mercado también puede lograrse mediante una estrategia de precios bien definida y valor agregado. Esto implica ofrecer precios competitivos para los sensores y servicios de monitoreo, así como paquetes flexibles que se adapten a las necesidades específicas de diferentes clientes, desde pequeñas empresas hasta grandes operadores. Además, proporcionar valor agregado, como informes detallados, análisis de datos y recomendaciones basadas en inteligencia artificial, puede diferenciar la oferta y justificar una inversión superior. 

<div style="text-align: center;"> <h4>Tabla: Matriz CAME. para el desarrollo de estrategias en base al análisis FODA. </h4> <img src="https://i.postimg.cc/1z527DwS/matriz-CAME.jpg" alt="Matriz CAME. para el desarrollo de estrategias en base al análisis FODA." /> <p>Fuente: Elaboración propia.</p> </div>
<br>

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

URL: https://youtu.be/Q5w1AZyZ7cU

Timing: 0:05

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

URL: https://youtu.be/5VN1W9JiBUE

Timing: 0:03

Duración: 25:11 minutos 

**Resúmen de la entrevista:**

Arquímedes es jefe de supervisores en Transcor SRL, una empresa dedicada al transporte terrestre de combustibles. Uno de los puntos clave en su enfoque es la preparación del conductor, ya que considera que sin un conductor bien capacitado y descansado, no importa cuán moderna o segura sea la unidad de transporte. El uso de tecnología avanzada como pulseras que monitorizan las horas de sueño y sensores en los camiones para detectar fatiga son fundamentales en su operación diaria.

Entre los principales riesgos que enfrenta están el tráfico y las condiciones geográficas adversas, especialmente en rutas de montaña. Para mitigarlos, su empresa realiza capacitaciones regulares sobre manejo defensivo y seguridad vial. Además, utilizan teléfonos satelitales para comunicarse en zonas sin señal y mantener un control constante del convoy.

Uno de los principales desafíos que identifica Arquímedes es la burocracia en la obtención de permisos para el transporte de materiales peligrosos, lo cual a veces retrasa las operaciones. Además, destaca la importancia de realizar simulacros en coordinación con las minas para estar preparados ante cualquier emergencia. Arquímedes propone reducir las distancias entre las unidades de apoyo vial para mejorar la respuesta en caso de incidentes.

Por otro lado, Arquímedes destaca habilidades como conocimiento técnico de los vehículos modernos, especialmente los sistemas avanzados de seguridad, y la capacidad de liderazgo y supervisión, ya que está a cargo de equipos de conductores. También haría hincapié en la importancia de la capacidad de tomar decisiones rápidas en situaciones difíciles. También, él probablemente ha trabajado con marcas de vehículos como Volvo, ya que menciona que sus conductores reciben capacitación específica de esta marca. Además, ha trabajado con empresas que requieren transporte de combustibles, posiblemente empresas del sector energético y minero.

Finalmente, Arquímedes mencionó utiliza sistemas como teléfonos satelitales y software de geocercas para el monitoreo constante de las unidades. También hace uso de sensores de fatiga y tecnologías integradas en los vehículos para detectar problemas y el entrevistado mencionó el uso de teléfonos satelitales, sensores de fatiga, cámaras de seguridad y sistemas de monitoreo GPS. Además, habló sobre kits antiderrame con tecnología avanzada y otros dispositivos relacionados con la seguridad de los conductores y los materiales peligrosos.

<br><br>

Entrevista 3: Segmento objetivo supervisores

Nombres y apellidos: Estuardo Chero

Edad:  46 años

Cargo actual: Supervisor Escolta de Materiales Peligrosos

[![interview1.png](https://i.postimg.cc/MGFJwqJ2/entrevista-empresa-3.png)](https://postimg.cc/Ff3BgtKD)

URL: https://youtu.be/Q5w1AZyZ7cU

Timing: 0:05

Duración: 8:04 minutos 

**Resúmen de la entrevista:**

Estuardo trabaja como supervisor escolta de materiales peligrosos, con un enfoque en el transporte seguro de concentrado de cobre. Antes de cada operación, se asegura de que tanto los vehículos como los conductores estén en condiciones óptimas. Realiza charlas de seguridad de 5 minutos con los conductores antes de cada jornada para asegurarse de que estén listos tanto física como mentalmente.

El principal riesgo que enfrenta es el de accidentes de tránsito, ya que muchas veces otros conductores no cumplen con las normativas de seguridad. El transporte del concentrado de cobre se realiza en tolvas, las cuales tienen ciertas medidas de seguridad, aunque no están completamente herméticas. Las dificultades en el monitoreo de la carga son mínimas, ya que las tolvas están cerradas, pero la preocupación principal es garantizar que no haya incidentes durante el trayecto.

En cuanto al cumplimiento de regulaciones, Estuardo destaca que su empresa cumple estrictamente con los estándares de seguridad y que la actitud de los conductores es clave para mantener ese nivel de cumplimiento. En caso de un incidente, siguen un plan de contingencia que incluye el uso de radios para reportar y coordinar con agentes viales que supervisan el convoy. Estuardo sugiere que, para mejorar la respuesta a emergencias, sería útil reducir la distancia entre las unidades de apoyo vial y mejorar los sistemas de monitoreo automáticos de los camiones.

Por otro lado, Estuardo destaca su habilidad para supervisar y gestionar convoyes, así como su conocimiento en cumplimiento de normativas de seguridad. También podría hablar de su capacidad para reaccionar ante emergencias y su atención al detalle en el control de los vehículos y la carga. Adicionalmente, él mencionó trabajar en Noat Logistics Perú, una empresa que realiza transporte para mineras. Es probable que haya trabajado con otras marcas y empresas en el sector de transporte de carga pesada y materiales peligrosos.

En adición, el entrevistado mencionó el uso de radios base para la comunicación constante con su equipo y con los agentes viales. También utiliza sistemas de monitoreo y software para la gestión de contingencias, como el plan de contingencias que debe seguir en caso de incidentes y los radios base, sistemas de monitoreo GPS, y las camionetas de soporte que monitorean el convoy. Se mencionó el uso de sensores en los vehículos para verificar fallas mecánicas, lo que sugiere que está familiarizado con la tecnología avanzada integrada en los camiones.

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

<br><br>

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

<br><br>

### 2.2.3. Análisis de entrevistas

- Las medidas de seguridad son una preocupación central para todos los entrevistados. Además, los riesgos relacionados con las condiciones externas son una preocupación común y el cumplimiento de normas es una obligación crítica en todas las empresas entrevistadas.

[![interview1.png](https://i.postimg.cc/x1Wp0CF2/gr-fico1-temas-clave.png)](https://postimg.cc/DSPP62Tj)

<br>

- Todos los entrevistados consideran los accidentes de tránsito como el principal riesgo. La pérdida de señal GPS en zonas remotas es un desafío significativo mencionado en 2 de las 3 entrevistas. Además, la mayoría de las empresas exige un mínimo de 7 horas de descanso para los conductores y la capacitación de los conductores se realiza dos veces al año como mínimo.

[![interview1.png](https://i.postimg.cc/JhZ6tL9B/gr-fico2-percepciones.png)](https://postimg.cc/McZbrhZW)

<br>

- Las empresas implementan múltiples tecnologías para garantizar la seguridad en el transporte. Todas las empresas utilizan teléfonos satelitales en zonas donde la cobertura de señal es deficiente. Además, los entrevistados perciben que el proceso burocrático es un desafío considerable. También, las empresas realizan simulacros de emergencia al menos 3 veces al año y se sugiere incrementar las unidades de respuesta para reducir tiempos de llegada en emergencias.

[![interview1.png](https://i.postimg.cc/t41mQPkk/gr-fico3-tecnolog-a-normas-simulacros.png)](https://postimg.cc/DSTc1St4)

<br>


## 2.3. Needfinding
### 2.3.1. User Personas

- **Segmento objetivo empresas: Arquetipo de las empresas**

[![interview1.png](https://i.postimg.cc/TwC09qF5/User-Persona-Empresas-new.png)](https://postimg.cc/9RwyXTWc)

<br>

- **Segmento objetivo conductores: Arquetipo del conductor**

[![interview1.png](https://i.postimg.cc/d3jmYn3n/User-Persona-Conductores-new.png)](https://postimg.cc/ct687RQ8)

### 2.3.2. User Task Matrix

- **Segmento objetivo empresas: Matriz de tareas**

[![interview1.png](https://i.postimg.cc/G3NQV1bD/User-Task-Matrix-Empresas.png)](https://postimg.cc/jCHPnmwq)

- **Segmento objetivo conductores: Matriz de tareas**

[![interview1.png](https://i.postimg.cc/FHVykTx4/User-Task-Matrix-Conductores.png)](https://postimg.cc/0zrMLd3W)

<br>

### 2.3.3. User Journey Mapping

- **Segmento objetivo empresas: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/fyPK4Www/Customer-Journey-Map-Empresas-new.png)](https://postimg.cc/YL1gYHGV)

<br>

- **Segmento objetivo conductores: Mapa del viaje del usuario**

[![interview1.png](https://i.postimg.cc/CMG4kM7D/Customer-Journey-Map-Conductores-new.png)](https://postimg.cc/8sCWVSqP)


### 2.3.4. Empathy Mapping

- **Segmento objetivo empresas: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/sXD9vGxj/Empathy-Map-Empresas-new.png)](https://postimg.cc/mcJFnD7J)

<br>

- **Segmento objetivo conductores: Mapa de empatía**

[![interview1.png](https://i.postimg.cc/pXPJZNcS/Empathy-Map-Conductores-new.png)](https://postimg.cc/4nFcf0gv)


### 2.3.5. As-is Scenario Mapping

- **Mapa As-Is: Segmento objetivo antes de conocer la solución de software:**

[![interview1.png](https://i.postimg.cc/0yCXLHWq/Mapa-As-Is-Empresas.png)](https://postimg.cc/3kdZG9QL)

<br><br>

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


