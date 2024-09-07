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

# Capitulo IV: Solution Software Desing

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming
![EventStorming](./assets/chapter4_img/step8.jpg)

#### 4.1.1.1 Candidate Context Discovery

Step 1:
![Step 1](/assets/chapter4_img/step1.jpg)
Step 2:
![Step 2](/assets/chapter4_img/step2.jpg)
Step 3:
![Step 3](/assets/chapter4_img/step3.jpg)
Step 4:
![Step 4](/assets/chapter4_img/step4.jpg)
Step 5:
![Step 5](/assets/chapter4_img/step5.jpg)
Step 6:
![Step 6](/assets/chapter4_img/step6.jpg)
Step 7:
![Step 7](/assets/chapter4_img/step7.jpg)
Step 8:
![Step 8](/assets/chapter4_img/step8.jpg)

#### 4.1.1.2 Domain Message Flows Modeling

Leyenda: <br>
![Leyenda](/assets/chapter4_img/leyenda.png)

Escenario: Inicio de sesión
![Escenario 1](/assets/chapter4_img/escenario1.png)

Escenario: Registro de usuario
![Escenario 2](/assets/chapter4_img/escenario2.png)

Escenario: Registro del sensor
![Escenario 3](/assets/chapter4_img/escenario3.png)

Escenario: Programación de viaje
![Escenario 4](/assets/chapter4_img/escenario4.png)

Escenario: Conductor visualiza sus viajes pendientes
![Escenario 5](/assets/chapter4_img/escenario5.png)

Escenario: Sensor detecta un problema
![Escenario 6](/assets/chapter4_img/escenario6.png)

#### 4.1.1.3 Bounded Context Canvases

Bounded context 'Usuario'  <br>
![Bounded Context Canvas Usuario](/assets/chapter4_img/canvas_users.jpg)

Bounded context 'Sensor'  <br>
![Bounded Context Canvas Usuario](/assets/chapter4_img/canvas_sensor.jpg)

Bounded context 'Viajes'  <br>
![Bounded Context Canvas Usuario](/assets/chapter4_img/canvas_viajes.jpg)

### 4.1.2. Context Mapping
![Context Mapping](/assets/chapter4_img/context_mapping.jpg)

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram
![C4 Diagrama de Contexto](/assets/chapter4_img/landscape.jpg)

#### 4.1.3.2. Software Architecture Context Level Diagrams
![C4 Diagrama de Contexto](/assets/chapter4_img/c4_context.png)

#### 4.1.3.2. Software Architecture Container Level Diagrams.
![C4 Diagrama de Componentes](/assets/chapter4_img/c4_component.jpg)

#### 4.1.3.3. Software Architecture Deployment Diagrams
![Software Architecture Deployment Diagrams](/assets/chapter4_img/ArchDeploy.png)

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.1. Bounded Context: Usuario
Este bounded context está relacionado con la gestión de cuentas de usuario, autenticación y la gestión de perfiles dentro de un sistema.<br>

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
![C4 Diagrama de Componentes](/assets/chapter4_img/bounded_context_user.jpeg)
#### 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.
![Diagrama_de_clases_usuario](/assets/chapter4_img/user_bounded_context-class_diagram.png)
###### 4.2.1.7.2. Bounded Context Database Design Diagram.
![Diagrama_de_base_de_Datos_usuario](/assets/chapter4_img/user_bounded_context-database_diagram.png)
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
![C4 Diagrama de Componentes](/assets/chapter4_img/bounded_context_sensor.jpeg)
#### 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.
##### 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.
![Diagrama de clases_sensor](/assets/chapter4_img/sensor_bounded_context-class_diagram.png)
##### 4.2.2.7.2. Bounded Context Database Design Diagram.
![Diagrama de base_de_datos_sensor](/assets/chapter4_img/sensor_bounded_context-database_diagram.png)
### 4.2.3. Bounded Context: Viajes
#### 4.2.3.1. Domain Layer.
#### 4.2.3.2. Interface Layer.
#### 4.2.3.3. Application Layer.
#### 4.2.3.4. Infrastructure Layer.
#### 4.2.3.6. Bounded Context Software Architecture Component Level Diagrams.
#### 4.2.3.7. Bounded Context Software Architecture Code Level Diagrams.
###### 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams.
###### 4.2.3.7.2. Bounded Context Database Design Diagram.
