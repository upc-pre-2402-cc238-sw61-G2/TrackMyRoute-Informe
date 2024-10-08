<p align="center" id="caratula">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC"><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles - SW61</strong><br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br>INFORME DE TRABAJO FINAL
</p>
<p align="center">
    <strong>Startup: TrackMyRoute</strong><br>
    <strong>Producto: TrackMyRoute</strong>
</p>

<div>
    <h3 align="center">Relación de Integrantes:</h3>
</div>

<div align="center">
     <table>
        <tr>
            <th style="text-align:center;">Integrante</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Anampa Lavado, Luis Angel</td>
            <td>u202218664</td>
        </tr>
        <tr>
            <td>Casimiro Fernandez, Carlos Oswaldo</td>
            <td>u202115412</td>
        </tr>
        <tr>
            <td>Huamán Cataño, Miguel Ángel</td>
            <td>u202120615</td>
        </tr>
        <tr>
            <td>Landeo Simeón, Favio Sebastián</td>
            <td>u202119588</td>
        </tr>
        <tr>
            <td>Orrego Noriega, Jorge David</td>
            <td>u201921734</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Agosto 2024</strong>
</p>

<div class="page"/>

# Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| **Versión** | **Fecha** | **Autor** | **Descripción de Modificación** |
| ----------- | --------- | --------- | ------------------------------- |
| v1.0        | 23/08/2024 | Todos los integrantes | Definimos la parte de la introducción de nuestro proyecto, la obtención y análisis de requisitos junto a las especificaciones de estos. |
| v2.0        | 15/09/2024 | Todos los integrantes | Actualizamos el informe y agregamos el prototipado de los dispositivos móviles según la retroalimentación del profesor. |

<div class="page"/>

# Tabla de contenidos

- [Carátula](#caratula)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Requirements Specification](23-requirements-specification)
    - [2.4.1. To-Be Scenario Mapping](#241-to-be-scenario-mapping)
    - [2.4.2. User Stories](#242-user-stories)
    - [2.4.3. Impact Mapping](#243-impact-mapping)
    - [2.4.4. Product Backlog](#244-product-backlog)
- [Capítulo III: Arquitectura](#capítulo-iii-arquitectura)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Information Architecture](#313-information-architecture)
        - [3.1.3.1. Landing Page Wireframes](#3131-landing-page-wireframes)
        - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-ux-ui-design)
        - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
        - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
        - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
        - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
        - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
  - [3.2. Arquitecture Overview](#32-arquitecture-overview)
    - [3.2.1. Domain-Driven Software Architecture](#321-domain-driven-software-architecture)
      - [3.2.1.1. Software Architecture Context Level Diagram](#3211-software-architecture-context-level-diagram)
      - [3.2.1.2. Software Architecture Container Level Diagram](#3212-software-architecture-container-level-diagram)
      - [3.2.1.3. Software Architecture Components Diagram](#3213-software-architecture-components-diagram)
    - [3.2.2. Software Object-Oriented Design](#322-software-object-oriented-design)
      - [3.2.2.1. Class Diagrams](#3221-class-diagrams)
      - [3.2.2.2. Class Dictionary](#3222-class-dictionary)
      - [3.2.2.3. Database Design](#3223-database-design)
      - [3.2.2.4. Database Diagram](#3224-database-diagram)
- [Conclusiones](#conclusiones)
- [Anexos](#anexos)


<div class="page"/>

# Student Outcome

<b> ABET – EAC - Student Outcome 7 </b> <br>
<b> La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas. </b>

| Criterio específico  | Acciones realizadas | Conclusiones |
|----------------------|-------------------- | ------------ |
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software. |                                                                             **Anampa Lavado, Luis Angel** <br> <br> **TB1:** Durante el desarrollo del proyecto, he actualizado mis conocimientos sobre nuevas tecnologías y metodologías de desarrollo de software, integrando estos conocimientos para mejorar la calidad de nuestra propuesta y garantizar que se alinee con las mejores prácticas actuales. <br> **TB2:** (TB2) <br> <br> <br> **Carlos Oswaldo Casimiro Fernández** <br> <br> **TB1:** Demostré mi capacidad para aprender e integrar nuevos conceptos en la creación de nuestra propuesta inicial para "TrackMyRoute". <br> **TB2:** (TB2) <br> <br> <br> **Miguel Ángel Huamán Cataño** <br> <br> **TB1:** Mejore mi comprensión sobre las necesidades de los usuarios en el ámbito del transporte público en Lima. Investigué sobre ello y consolide lo aprendido con el fin de encontrar mejoras en distintos aspectos de nuestro proyecto. <br> **TB2:** (TB2) <br> <br> <br> **Favio Sebastián Landeo Simeón** <br> <br> **TB1:** Aprendí que los conocimientos generales acerca de la población y sus problemas son importantes si los adaptamos para realizar una solución. <br> **TB2:** (TB2) <br> <br> <br> **Jorge David Orrego Noriega** <br> <br> **TB1:** Actualicé mis conceptos previos acerca de la situación del transporte público en Lima Metropolitana para el análisis del problema. <br> **TB2:** (TB2) <br>  <br> | **TB1:** Concluimos que en la realización de este proyecto hemos investigado y recordado conceptos relacionados a la problemática que planteamos para poder tener un mejor resultado. <br> <br> **TB2:** (TB2) |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software. |                                                                              **Anampa Lavado, Luis Angel** <br> <br> **TB1:** Reconozco la importancia del aprendizaje continuo en mi desarrollo profesional y en la ejecución de proyectos de software. Identifiqué la necesidad de actualizar constantemente mis habilidades técnicas y de gestión, lo que ha permitido un avance más eficiente en el proyecto y una mejor adaptación a los cambios del entorno tecnológico. <br> **TB2:** (TB2) <br> <br> **Carlos Oswaldo Casimiro Fernández** <br> <br> **TB1:** Reconocí la importancia del aprendizaje continuo en mi desarrollo profesional y en la ejecución de proyectos de soluciones de software, identificando oportunidades para actualizar mis conocimientos y habilidades técnicas de manera constante. <br> **TB2:** (TB2) <br> <br> **Miguel Ángel Huamán Cataño** <br> <br> **TB1:** Aprendí lo importante que es el aprendizaje continuo, ya que gracias a ello puedo adquirir más conocimientos y mejorar de diferentes maneras nuestro aplicativo y ser un mejor  profesional. <br> **TB2:** (TB2) <br> <br> **Favio Sebastián Landeo Simeón** <br> <br> **TB1:** Aprendí a tener en cuenta una problemática seria y que tenga solución tecnológica para poder aplicar mis conocimientos. <br> **TB2:** (TB2) <br> <br> **Jorge David Orrego Noriega** <br> <br> **TB1:** Aprendí sobre nuevas ideas para mejorar la experiencia de viajar en el transporte público limeño. <br> **TB2:** (TB2) <br> <br> | **TB1:** Concluimos que el aprendizaje que nos brinda el profesor durante las clases y los recursos que nos dan ayudan a mejorar tanto a nuestro proyecto como de forma personal para ser mejores especialistas en tecnología. <br> <br> **TB2:** (TB2)  |


# Objetivos SMART

| **Nombre**                 | **Objetivo SMART**  | **Fecha de Inicio** |                                                                                                                                            
|----------------------------|---------------------|--------------------|
| **Luis Angel Anampa Lavado** | Mi objetivo es desarrollar e implementar una aplicación móvil llamada "TrackMyRoute". Esta aplicación facilitará a los residentes de Lima encontrar las mejores rutas de transporte público, planificar sus viajes y obtener información en tiempo real sobre las rutas y medios de transporte. La aplicación también colaborará con las empresas de transporte para mejorar sus servicios. Mi segundo objetivo es completar el desarrollo e implementación de la aplicación, con todas las funcionalidades operativas. |28/08/2024 |
| **Carlos Oswaldo Casimiro Fernández** | Coordinaré con mis compañeros para aplicar los conocimientos adquiridos en clase y otros recursos disponibles, completando todas las tareas pendientes de nuestro proyecto final según una lista asignada, asegurando una entrega cooperativa y exitosa del trabajo. | 28/08/2024 |
| **Miguel Ángel Huamán Cataño** | Contribuir activamente al desarrollo de la aplicación "TrackMyRoute" coordinando con mi equipo, participando en las reuniones para revisar el progreso y asegurar que todos los aspectos del proyecto estén avanzando según el plan.| 28/08/2024|
| **Favio Sebastián Landeo Simeón** | Tratar de aplicar los conocimientos que nos brinde el profesor y los demás recursos que estén a mi alcance para lograr completar satisfactoriamente el trabajo final de forma cooperativa. | 28/08/2024 |
| **Jorge David Orrego Noriega** | Cuando falten cinco días para la entrega del trabajo, iré coordinando con mis compañeros para ver qué falta por hacer por medio de una lista de pendientes, en la cual se asignará a un integrante del equipo por cada tarea no finalizada. | 26/08/2024 |


<div class="page"/>

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

"TrackMyRoute" es una startup innovadora que busca revolucionar la movilidad urbana en Lima a través de la tecnología. Nuestra plataforma está diseñada para facilitar el uso del transporte público, ofreciendo una solución integral que no solo ayuda a los usuarios a planificar sus trayectos de manera eficiente, sino que también mejora la experiencia de viaje al proporcionar información en tiempo real sobre rutas, tiempos de espera, y disponibilidad de vehículos. Al conectar a los usuarios con las mejores opciones de transporte en tiempo real, estamos transformando la manera en que las personas se desplazan por la ciudad. Además, nuestra colaboración con empresas de transporte público les permite optimizar sus operaciones y mejorar la calidad de sus servicios, creando así un ecosistema de movilidad más inteligente y conectado.

### Visión
Ser la plataforma líder en movilidad urbana en América Latina, mejorando la calidad de vida de millones de personas al ofrecer soluciones innovadoras y sostenibles para el transporte público.

### Misión
Facilitar el acceso a un transporte público más eficiente y confiable, brindando a los usuarios de Lima una herramienta poderosa para planificar sus viajes y optimizar sus desplazamientos diarios, mientras apoyamos a las empresas de transporte en la mejora continua de sus servicios.

<div class="page"/>

### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" width="70%" style="text-align:center; border-collapse: collapse;">
  <!-- Luis Angel Anampa Lavado -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/Anampa_Angel.jpg" alt="Luis Angel Anampa Lavado" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Luis Angel Anampa Lavado
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Mi nombre es Angel Anampa y tengo 19 años. Actualmente estoy cursando la carrera de Ingeniería de Software en la UPC. Elegí dicha carrera porque soy una persona que le interesa mucho los temas que tienen que ver con tecnología, me gustan los videojuegos. Me considero una persona atenta, responsable, optimista que sabe solucionar los problemas. Como integrante del equipo me comprometo a apoyar al grupo en este trabajo.
    </td>
  </tr>
  <!-- Carlos Oswaldo Casimiro Fernández -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/CarlosCasimiro.png" alt="Carlos Oswaldo Casimiro Fernandez" style="margin-bottom: 5px;" width="200"/>
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Carlos Oswaldo Casimiro Fernández
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Tengo 20 años y soy estudiante de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas. Me considero una persona proactiva, educada y sociable con los que me rodean. Además, cuento con habilidades peculiares como la animación en 3D, edición de videos cinematográficos y conocimiento en lenguajes como C++, Python.
    </td>
  </tr>
  <!-- Miguel Ángel Huamán Cataño -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/MiguelHuaman.png" alt="Miguel Angel Huaman Cataño" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Miguel Ángel Huamán Cataño
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Mi nombre es Miguel Ángel Huamán Cataño, tengo 20 años y soy estudiante de Ingeniería de Software. Soy una persona que disfruta trabajar con empeño para alcanzar mis objetivos, nunca me rindo a pesar de los momentos difíciles, y haré todo lo posible para seguir mejorando en este largo camino de ser un buen profesional.
    </td>
  </tr>
  <!-- Favio Sebastián Landeo Simeón -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/FavioLandeo.png" alt="Favio Sebastian Landeo Simeon" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Favio Sebastián Landeo Simeón
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Tengo 20 años y actualmente estoy cursando el séptimo ciclo de la carrera de Ingeniería de Software. Estoy disponible para ayudar siempre a mis compañeros y además tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo. En mis tiempos libres me gusta escuchar música, jugar videojuegos y editar videos.
    </td>
  </tr>
  <!-- Jorge David Orrego Noriega -->
  <tr align="center">
    <td rowspan="3" width="30%">
      <img src="assets/JorgeOrrego.png" alt="Jorge David Orrego Noriega" style="margin-bottom: 5px;" width="200"/> 
    </td>
    <td align="left" style="padding: 10px;">
      <b>Nombre y Apellido:</b><br>
      Jorge David Orrego Noriega
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Carrera:</b><br>
      Ingeniería de Software
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 10px;">
      <b>Acerca de:</b><br>
      Estudio actualmente la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas y la razón por la cual me encuentro estudiando esta carrera es porque siempre he tenido un interés particular por la tecnología, con un mayor énfasis en el software.
    </td>
  </tr>
</table>

<div class="page"/>

## 1.2. Solution Profile

En esta sección iniciaremos por un análisis de los antecedentes y problemática sobre la movilización en transporte público para identificar las raíces del problema e identificar algunas necesidades que se deban cubrir para llegar a una solución de la problemática. Asimismo, luego pasaremos por el proceso UX para poder analizar más a detalle la problemática y poder plantear una hipótesis acerca de la problemática.


### 1.2.1. Antecedentes y problemática

La movilización en transportes públicos en Lima, se ha visto influenciada por una serie de antecedentes y problemáticas a lo largo de su historia. En un contexto de rápido crecimiento poblacional y urbano, la demanda de servicios de transporte público ha ido en constante aumento. Sin embargo, varios factores han contribuido a desafiar la eficiencia y la calidad de la movilización en la ciudad. Históricamente, Lima contaba con sistemas de transporte público, como los tranvías, en el siglo XIX. Sin embargo, la falta de inversión y una planificación inadecuada llevaron al declive y eventual desaparición de estos sistemas en la segunda mitad del siglo XX. Entre las problemáticas más apremiantes se destaca la congestión del tráfico, que afecta de manera significativa a los limeños. El aumento de vehículos particulares y la infraestructura inadecuada han resultado en largos tiempos de viaje y congestión constante en las calles de la ciudad. Asimismo, el transporte público en Lima ha enfrentado dificultades, desde deficiencias en infraestructura y falta de mantenimiento hasta servicios ineficientes. Los usuarios a menudo se ven obligados a utilizar autobuses y combis en condiciones precarias, lo que afecta negativamente su experiencia de viaje. La seguridad en el transporte público también ha sido motivo de preocupación, con incidentes de robos y acoso a los pasajeros. Esto ha generado inquietudes sobre la seguridad de los usuarios en el sistema. Además, las tarifas de transporte público pueden resultar onerosas para personas de bajos ingresos, y la falta de accesibilidad adecuada para personas con discapacidad ha sido una preocupación persistente. A pesar de estos desafíos, el gobierno y las autoridades locales han implementado medidas para mejorar el transporte público en Lima, incluyendo la introducción de sistemas de transporte masivo como el Metropolitano y el Tren Eléctrico, así como esfuerzos para combatir la informalidad y elevar la calidad del servicio. Sin embargo, los retos siguen siendo considerables en una ciudad en constante crecimiento y transformación.

¿Qué?: La movilización en transportes públicos en Lima se refiere al desplazamiento de personas dentro de la ciudad utilizando medios de transporte público, como autobuses, combis, el Metropolitano (un sistema de buses de tránsito rápido) y el Tren Eléctrico. Esto incluye viajes diarios para trabajar, estudiar y realizar actividades cotidianas.

¿Quién?: Los usuarios del transporte público en Lima, que incluyen a residentes locales y visitantes de la ciudad, son los principales actores de esta movilización. Además, las autoridades gubernamentales y las empresas de transporte público desempeñan un papel importante en la gestión y regulación de estos servicios.

¿Por qué?: Las personas utilizan el transporte público en Lima por varias razones, incluyendo la congestión del tráfico, la falta de estacionamiento, la necesidad de una opción de movilidad asequible y la preocupación por el medio ambiente. Además, muchas personas no tienen acceso a un automóvil personal y dependen del transporte público para sus desplazamientos diarios.

¿Dónde?: Esta movilización se lleva a cabo en toda la ciudad de Lima, que incluye el centro histórico, los distritos periféricos y las áreas metropolitanas circundantes. Los usuarios se desplazan tanto dentro de la ciudad como hacia y desde los suburbios.

¿Cuándo?: La movilización en transportes públicos en Lima ocurre todos los días, durante todas las horas del día, ya que es esencial para las actividades diarias de la población. Los horarios varían según la ruta y el tipo de transporte.

¿Cómo?: Los usuarios pueden acceder al transporte público en Lima a través de una red de paraderos y estaciones que sirven a diferentes rutas y servicios. Los sistemas de transporte masivo, como el Metropolitano y el Tren Eléctrico, ofrecen tarjetas de acceso y estaciones específicas para abordar. Los autobuses y combis tienen paraderos designados en las calles

¿Cuánto?: El costo de utilizar el transporte público en Lima varía según el tipo de servicio y la distancia recorrida. Los precios de los boletos pueden oscilar desde unos pocos centavos hasta varios soles peruanos, dependiendo de la ruta y el sistema de transporte. Los usuarios a menudo pueden optar por tarifas con descuento si utilizan tarjetas de prepago o si son estudiantes o adultos mayores.

Conclusiones de las 5W y 2H: En conclusión, la movilización en transportes públicos en Lima, Perú, es una parte fundamental de la vida cotidiana de sus residentes y visitantes. Este sistema de transporte es utilizado por una amplia variedad de personas que dependen de él para desplazarse por la ciudad debido a la congestión del tráfico, la falta de estacionamiento y la necesidad de opciones de movilidad asequibles. A pesar de las numerosas problemáticas, como la congestión, la seguridad y la falta de inversión en infraestructura, el transporte público sigue siendo esencial para mantener la movilidad en una ciudad en constante crecimiento y transformación. Los esfuerzos de las autoridades locales y gubernamentales, como la implementación de sistemas de transporte masivo y la regulación del sector, son pasos importantes hacia la mejora de la movilización en Lima.

<div class="page"/>

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

El propósito de TrackMyRoute es ayudar a las personas a planificar y realizar viajes en transporte público de manera fácil y eficiente. Además, de reducir los costos de transporte y la congestión de tráfico. Esto contribuye a mejorar la calidad del aire para reducir el impacto ambiental de los desplazamientos diarios.


#### 1.2.2.2. Lean UX Assumptions

User Assumptions

I. ¿Quién es el usuario? TrackMyRoute está dirigido a cualquier persona que utilice el transporte público en la ciudad de Lima. Esto puede incluir a estudiantes, trabajadores, viajeros y cualquier otra persona que necesite planificar un viaje en transporte público. Además es útil para turistas y visitantes que no están familiarizados con el sistema de transporte público local y que necesitan ayuda para planificar sus viajes.

II. ¿Dónde encaja nuestro producto en su trabajo o vida?

Nuestro servicio encaja para los residentes de Lima, que dependen en gran medida del transporte público para sus desplazamientos diarios, "TrackMyRoute" puede ser una herramienta esencial. Les permite encontrar la mejor ruta de transporte público para llegar a su destino de manera eficiente, ahorrando tiempo y minimizando la incertidumbre en sus viajes. Esto se traduce en una mayor comodidad y productividad en su vida cotidiana.

III. ¿Qué problemas tiene nuestro producto? ¿Evitar?

La precisión de la información en tiempo real es fundamental para la efectividad de la aplicación. Los datos incorrectos pueden llevar a los usuarios por rutas equivocadas y generar frustración. Además, al recopilar datos de ubicación en tiempo real, es crucial garantizar la privacidad y seguridad de los usuarios. Es por ello que debemos evitar problemas de seguridad, como la exposición de datos sensibles o la posibilidad de rastreo no autorizado.

IV. ¿Cuándo y cómo es nuestro producto? ¿Usado?

Nuestro servicio podrá ser utilizado a través de dispositivos móviles, como teléfonos inteligentes o tabletas. Los usuarios pueden descargar la aplicación desde tiendas de aplicaciones móviles, como la App Store o Google Play, e instalarla en sus dispositivos. Luego, ingresan su ubicación actual y destino, y la aplicación proporciona información sobre las rutas disponibles, tiempos de viaje estimados y actualizaciones en tiempo real sobre la ubicación de los vehículos de transporte público. Esto permite a los usuarios tomar decisiones informadas sobre la mejor manera de llegar a su destino utilizando el transporte público en Lima.

V. ¿Qué características son importantes?

“TrackMyRoute" es una aplicación esencial para los usuarios de transporte público en Lima, ofreciendo una amplia gama de características cruciales, como la búsqueda de rutas, información en tiempo real sobre el transporte, notificaciones y alertas, mapas interactivos, detalles de tarifas y opciones de pago, comentarios de usuarios, historial de viajes, accesibilidad y medidas de seguridad, todo ello respaldado por una colaboración efectiva con las empresas de transporte. Esta aplicación mejora la experiencia de viaje al ayudar a los usuarios a planificar y seguir sus rutas de manera eficiente, brindando un servicio completo y personalizado que facilita la movilidad en la ciudad de Lima.

VI. ¿Cómo debe verse nuestro producto y cómo comportarse?

Nuestra plataforma tiene que interactuar con los usuarios mediante un diseño llamativo e intuitivo con la finalidad de que nuestros usuarios confíen en nosotros y tengan facilidad de lograr sus objetivos al usar la plataforma y tengan una experiencia de usuario satisfactoria.

Business Assumptions

1. Demanda de Usuarios: Suponemos que existe una demanda significativa de una aplicación de planificación de rutas de transporte público en Lima, ya que muchas personas utilizan el transporte público en la ciudad y buscan formas de optimizar sus viajes.
2. Colaboración con Empresas de Transporte: Suponemos que las empresas de transporte público en Lima estarán dispuestas a colaborar y proporcionar datos actualizados sobre sus rutas y vehículos para integrarlos en nuestra aplicación.

3. Disponibilidad de Datos en Tiempo Real: Suponemos que podemos acceder a datos en tiempo real de los sistemas de transporte público, lo que nos permitirá proporcionar información precisa sobre la ubicación y el estado de los vehículos.

4. Aceptación de Tecnología: Suponemos que la población de Lima está dispuesta a adoptar y utilizar aplicaciones móviles para planificar sus viajes en transporte público, y que cuentan con los dispositivos y la conectividad necesarios.

5. Monetización: Suponemos que podemos generar ingresos a través de modelos de monetización como la publicidad en la aplicación, la venta de boletos de transporte o la suscripción premium para características adicionales.

6. Seguridad de Datos: Suponemos que podemos garantizar la seguridad y privacidad de los datos personales de los usuarios, lo que fomentará la confianza en nuestra aplicación.

7. Competencia: Suponemos que habrá competidores en el mercado de aplicaciones de transporte público en Lima, y debemos encontrar formas de diferenciarnos y ofrecer un valor único a los usuarios.

8. Retención de Usuarios: Suponemos que podemos mantener una base de usuarios activa y comprometida a largo plazo mediante actualizaciones regulares de la aplicación, características adicionales y un excelente servicio al cliente.

9. Regulaciones y Cumplimiento Normativo: Suponemos que podemos cumplir con todas las regulaciones y requisitos legales relacionados con la operación de una aplicación de transporte público en Lima.

10. Marketing efectivo: Suponemos que podemos llevar a cabo estrategias de marketing efectivas para aumentar la conciencia y la adopción de la aplicación entre los residentes y visitantes de Lima.

<div class="page"/>

#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que existe una demanda insatisfecha de una aplicación de planificación de rutas de transporte público en Lima.
Realizaremos encuestas y análisis de mercado para evaluar el interés y la disposición de los usuarios para utilizar la aplicación.
Suponemos que las empresas de transporte público estarán dispuestas a colaborar y proporcionar datos esenciales para nuestra aplicación.
Iniciaremos conversaciones con empresas de transporte para determinar su interés y disposición para colaborar.
Creemos que la población de Lima está dispuesta a utilizar aplicaciones móviles para planificar sus viajes en transporte público.
Realizaremos encuestas de aceptación de tecnología y evaluaremos la adopción inicial de la aplicación.
Suponemos que habrá competidores en el mercado de aplicaciones de transporte público y que podemos diferenciarnos.
Realizaremos un análisis de la competencia y evaluaremos nuestra propuesta de valor única.
Suponemos que podemos generar ingresos a través de modelos de monetización como la publicidad en la aplicación y la venta de boletos.
Implementaremos estos modelos y evaluaremos la generación de ingresos y la aceptación de los usuarios.

<div class="page"/>

#### 1.2.2.4. Lean UX Canvas

<img src="assets/LeanUXCanvas.png">

<div class="page"/>

## 1.3. Segmentos Objetivo

### Segmento objetivo 1: Pasajeros en busca de un autobús

- Personas que viajan al trabajo o la escuela en transporte público. <br>
- Turistas que exploran Lima y prefieren utilizar el transporte público. <br>
- Personas que no tienen acceso a un vehículo personal y dependen del transporte público para sus desplazamientos diarios.

### Segmento objetivo 2: Empresas de transporte que operan en Lima.

- Los gerentes de operaciones y logística de estas empresas. <br>
- Empresas formalizadas y con papeles en regla.


<div class="page"/>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

<br>
Luego de realizar una investigación en el mercado, hemos encontrado tres proyectos que consideramos como potenciales competidores para TrackMyRoute. Estos son:
<br><br>

- **Moovit:**
  <br>

  Moovit es una aplicación de movilidad urbana que proporciona a los usuarios información sobre rutas y horarios de transporte público en tiempo real. Permite a los usuarios planificar sus viajes utilizando una variedad de opciones de transporte público, incluidos autobuses, trenes, metro y tranvías. Moovit también ofrece alertas sobre interrupciones en el servicio y actualizaciones en tiempo real para ayudar a los usuarios a navegar por la ciudad de manera eficiente.
  <br>

<div align="center">
  <img src="https://moovit.com/wp-content/uploads/2020/03/opengraph-homepage-1.png">
</div>

<br><br>

- **Citymapper:**
  <br>

  Citymapper es una aplicación de planificación de viajes que ofrece rutas y horarios para una amplia gama de opciones de transporte en ciudades de todo el mundo. Además de proporcionar información sobre transporte público, Citymapper incluye opciones de transporte alternativo como bicicletas compartidas, scooters eléctricos y servicios de viaje compartido. La aplicación también ofrece detalles sobre tarifas, tiempo de viaje y opciones de rutas más rápidas o escénicas.
  <br>

<div align="center">
  <img src="https://logovectorseek.com/wp-content/uploads/2020/11/citymapper-logo-vector.png">
</div>

<br><br>

- **Trafi:**
  <br>

  Trafi es una aplicación de movilidad urbana que ofrece información detallada sobre rutas y horarios de transporte público, así como opciones para otros modos de transporte, como bicicletas compartidas y servicios de viaje compartido. La aplicación utiliza datos en tiempo real para proporcionar a los usuarios actualizaciones sobre el estado del servicio, retrasos y cambios en las rutas. Trafi está disponible en varias ciudades de todo el mundo y se centra en ofrecer soluciones de movilidad integrales para sus usuarios.
  <br>

<div align="center">
  <img src="https://logowik.com/content/uploads/images/trafi-20215422.logowik.com.webp">
</div>

<br><br>

<div class="page"/>

### 2.1.1. Análisis competitivo

<table>
<tbody><tr><th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th></tr><tr><td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td><td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td></tr><tr><td colspan="5">Este análisis se concretó teniendo como finalidad el poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de ellos.</td></tr><tr><td colspan="3">Nuestro Producto / Competidores</td><td colspan="1" valign="top" style="font-weight: bold;">TrackMyRoute<br></td><td colspan="1" valign="top" style="font-weight: bold;">Moovit<br><img src="https://moovit.com/wp-content/uploads/2020/03/opengraph-homepage-1.png" alt="Mootvit" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Citymapper<br><img src="https://logovectorseek.com/wp-content/uploads/2020/11/citymapper-logo-vector.png" alt="Citymapper" width="60px"></td><td colspan="1" valign="top" style="font-weight: bold;">Trafi<br><img src="https://logowik.com/content/uploads/images/trafi-20215422.logowik.com.webp" alt="Trafi" width="60px"></td></tr><tr><td colspan="1" rowspan="2">Perfil</td><td colspan="2">Overview</td><td colspan="1" valign="top">TrackMyRoute se destaca por su enfoque específico en mejorar la movilidad urbana en Lima, Perú. Ofrece una combinación de planificación de rutas, información en tiempo real sobre el estado del transporte público y la posibilidad de realizar pagos de pasajes dentro de la aplicación. Su colaboración con empresas de transporte público locales y la opción de una versión premium con funciones adicionales lo convierten en una opción atractiva para los residentes de Lima que buscan optimizar sus desplazamientos por la ciudad.</td><td colspan="1" valign="top">Moovit es una aplicación ampliamente reconocida a nivel mundial por su capacidad para proporcionar información detallada sobre rutas y horarios de transporte público en tiempo real. Con una amplia disponibilidad internacional, Moovit se destaca por su capacidad para ofrecer actualizaciones en tiempo real sobre el estado del servicio, alertas de servicio y una comunidad activa de usuarios que contribuyen con información valiosa sobre el transporte público en sus ciudades.</td><td colspan="1" valign="top">Citymapper es conocida por su enfoque integral en la planificación de viajes, ofreciendo opciones para una variedad de modos de transporte, incluidos el transporte público, bicicletas compartidas, scooters eléctricos y servicios de viaje compartido. Su diseño intuitivo y la capacidad de ofrecer opciones de rutas más rápidas o escénicas lo convierten en una opción popular entre los usuarios que buscan soluciones de movilidad flexibles y personalizadas en ciudades de todo el mundo.</td><td colspan="1" valign="top">Trafi ofrece una solución completa para la planificación de viajes en ciudades de todo el mundo, con información detallada sobre rutas y horarios de transporte público, así como opciones para otros modos de transporte como bicicletas compartidas y servicios de viaje compartido. Su enfoque en ofrecer soluciones de movilidad integrales y actualizaciones en tiempo real sobre el estado del servicio lo convierten en una herramienta valiosa para los usuarios que buscan optimizar sus desplazamientos urbanos.</td></tr><tr><td colspan="2">Ventaja competitiva</td><td colspan="1" valign="top">TrackMyRoute se destaca por su enfoque localizado en Lima, Perú, lo que permite una adaptación precisa a las necesidades del sistema de transporte público local. Además, su integración con las empresas de transporte público ofrece una experiencia más confiable y personalizada para los usuarios, brindando acceso a datos actualizados y recursos exclusivos.</td><td colspan="1" valign="top">Moovit sobresale por su amplia disponibilidad internacional, convirtiéndose en una opción confiable para usuarios que viajan entre diferentes ciudades y países. Además, sus actualizaciones en tiempo real sobre el estado del servicio y la participación activa de la comunidad de usuarios garantizan información precisa y confiable para optimizar los viajes en transporte público.</td><td colspan="1" valign="top">Citymapper ofrece una ventaja competitiva a través de su variedad de modos de transporte, que incluyen opciones como transporte público, bicicletas compartidas y servicios de viaje compartido. Su diseño intuitivo y las opciones de rutas personalizadas hacen que la planificación de viajes sea flexible y adaptada a las preferencias individuales de los usuarios.</td><td colspan="1" valign="top">Trafi destaca por ofrecer soluciones integrales de movilidad, proporcionando información detallada sobre una amplia variedad de modos de transporte. Sus actualizaciones en tiempo real sobre el estado del servicio permiten a los usuarios tomar decisiones informadas sobre sus desplazamientos, adaptándose a cualquier cambio en el transporte público de manera eficiente.</td></tr><tr><td colspan="1" rowspan="2">Perfil de Marketing</td><td colspan="2">Mercado objetivo</td><td colspan="1" valign="top">El mercado objetivo principal para TrackMyRoute son los residentes de Lima, Perú, que dependen del transporte público para sus desplazamientos diarios. Esto incluye a estudiantes, trabajadores y cualquier persona que utilice el transporte público en la ciudad. Además, la aplicación también puede ser útil para turistas y visitantes que desean explorar Lima utilizando el transporte público.</td><td colspan="1" valign="top">Moovit tiene un mercado objetivo amplio y diverso que abarca usuarios de transporte público en ciudades de todo el mundo. Esto incluye a personas de todas las edades y grupos demográficos que utilizan el transporte público como parte de su rutina diaria, así como viajeros y turistas que buscan orientación sobre el transporte público en nuevas ubicaciones.</td><td colspan="1" valign="top">Citymapper se dirige a usuarios urbanos en ciudades de todo el mundo que buscan una solución integral para planificar sus viajes utilizando una variedad de modos de transporte. Esto incluye a personas jóvenes y activas que prefieren opciones de movilidad flexibles y personalizadas, así como a profesionales y trabajadores que necesitan optimizar sus desplazamientos diarios.</td><td colspan="1" valign="top">Trafi está dirigido a usuarios urbanos en ciudades de todo el mundo que buscan una solución completa para planificar y optimizar sus viajes utilizando diferentes modos de transporte. Su mercado objetivo incluye a personas de todas las edades y grupos demográficos que dependen del transporte público y están interesadas en recibir información actualizada y precisa sobre sus opciones de movilidad.</td></tr><tr><td colspan="2">Estrategias de marketing</td><td colspan="1" valign="top">Publicidad dirigida en redes sociales, enfocada en residentes de Lima y colaboración con empresas de transporte público para promoción mutua.</td><td colspan="1" valign="top">Publicidad en plataformas online y apps de viajes. Tambien programas de referidos para usuarios existentes.</td><td colspan="1" valign="top">Creación de contenido educativo en video. Colaboraciones con influencers locales.</td><td colspan="1" valign="top">Optimización SEO para mejorar visibilidad en búsquedas. Participación en eventos de movilidad urbana.</td></tr><tr><td colspan="1" rowspan="3">Perfil de Producto</td><td colspan="2">Productos &amp; Servicios</td><td colspan="1" valign="top">TrackMyRoute ofrece una aplicación móvil para la planificación de rutas de transporte público en Lima, con una versión premium que incluye características como pagos integrados y actualizaciones en tiempo real. Además, se colabora con empresas de transporte público para mejorar la calidad de los servicios y la experiencia del usuario.</td><td colspan="1" valign="top">Moovit proporciona una aplicación móvil para la planificación de rutas y horarios de transporte público a nivel global. Ofrece actualizaciones en tiempo real sobre el estado del servicio y alertas de servicio, junto con una comunidad activa de usuarios que contribuyen con información sobre el transporte público.</td><td colspan="1" valign="top">Citymapper ofrece una aplicación móvil para la planificación de viajes integrales en ciudades de todo el mundo. La aplicación proporciona rutas para una variedad de modos de transporte y opciones de rutas personalizadas, con un diseño intuitivo para mejorar la experiencia del usuario.</td><td colspan="1" valign="top">Trafi es una aplicación móvil que permite la planificación de viajes en ciudades globales. Ofrece información detallada sobre rutas y horarios de transporte público, así como opciones para otros modos de transporte. Además, proporciona actualizaciones en tiempo real sobre el estado del servicio y soluciones integrales de movilidad para usuarios urbanos.</td></tr><tr><td colspan="2">Precios &amp; Costos</td><td colspan="1" valign="top">Ofrece una versión gratuita con opciones básicas y una versión premium con características adicionales que los usuarios pueden adquirir mediante una tarifa mensual o anual. Los ingresos provienen de la venta de la versión premium y los costos asociados incluyen desarrollo inicial, mantenimiento de servidores, actualizaciones de software y posibles costos de soporte técnico.</td><td colspan="1" valign="top">La aplicación es gratuita para los usuarios, generando ingresos principalmente a través de acuerdos de publicidad y posiblemente asociaciones con empresas de transporte público. Los costos incluyen el desarrollo continuo de la aplicación, mantenimiento de servidores y posibles costos de soporte técnico y marketing.</td><td colspan="1" valign="top">Es gratuita para los usuarios y probablemente genere ingresos a través de acuerdos de publicidad y posibles asociaciones con empresas de transporte. Los costos están asociados con el desarrollo y mantenimiento continuo de la aplicación, así como los gastos de servidores y posibles costos de marketing.</td><td colspan="1" valign="top">Igualmente gratuita para los usuarios, Trafi podría generar ingresos a través de acuerdos de publicidad y posiblemente asociaciones con empresas de transporte. Los costos incluyen el desarrollo y mantenimiento de la aplicación, así como los gastos de servidores y posibles costos de marketing y soporte técnico.</td></tr><tr><td colspan="2">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">La aplicación puede distribuirse a través de su propio sitio web, donde los usuarios pueden acceder a información sobre la aplicación y descargarla desde enlaces directos a las tiendas de aplicaciones.</td><td colspan="1" valign="top">Moovit ofrece información sobre la aplicación y enlaces de descarga en su sitio web oficial, permitiendo a los usuarios acceder y descargar la aplicación desde sus navegadores web.</td><td colspan="1" valign="top">Citymapper proporciona información sobre la aplicación y enlaces de descarga en su sitio web oficial, permitiendo a los usuarios acceder y descargar la aplicación desde sus navegadores web.</td><td colspan="1" valign="top">Trafi ofrece información sobre la aplicación y enlaces de descarga en su sitio web oficial, permitiendo a los usuarios acceder y descargar la aplicación desde sus navegadores web.</td><tr></tr><td colspan="1" rowspan="5">Análisis SWOT</td></td></tr><tr><td colspan="2">Fortalezas</td><td colspan="1" valign="top">Enfoque localizado en Lima, integración con empresas de transporte público, versión premium con funciones adicionales.</td><td colspan="1" valign="top">Amplia disponibilidad internacional, actualizaciones en tiempo real, comunidad activa de usuarios.</td><td colspan="1" valign="top">Variedad de modos de transporte, diseño intuitivo, opciones de rutas personalizadas.</td><td colspan="1" valign="top">Soluciones integrales de movilidad, actualizaciones en tiempo real, enfoque en la experiencia del usuario.</td></tr><tr><td colspan="2">Debilidades</td><td colspan="1" valign="top">Dependencia del desarrollo del sistema de transporte público en Lima, competencia con aplicaciones establecidas.</td><td colspan="1" valign="top">Dependencia de la calidad de los datos de transporte público, competencia con otras aplicaciones similares.</td><td colspan="1" valign="top">Dependencia de la calidad de los datos de transporte, competencia con aplicaciones establecidas como Moovit.</td><td colspan="1" valign="top">Dependencia de la calidad de los datos de transporte público, competencia con aplicaciones más establecidas como Moovit y Citymapper.</td></tr><tr><td colspan="2">Oportunidades</td><td colspan="1" valign="top">Crecimiento del mercado de aplicaciones de movilidad urbana en Lima, colaboración con más empresas de transporte público, expansión a otras ciudades.</td><td colspan="1" valign="top">Expansión a nuevos mercados, desarrollo de nuevas características y funcionalidades, colaboraciones con más empresas de transporte.</td><td colspan="1" valign="top">Expansión a nuevas ciudades, desarrollo de nuevas características innovadoras, colaboraciones con empresas de transporte y urbanismo.</td><td colspan="1" valign="top">Expansión a nuevos mercados globales, desarrollo de nuevas funciones para mejorar la experiencia del usuario, colaboraciones con empresas de transporte y gobierno.</td></tr><tr><td colspan="2">Amenazas</td><td colspan="1" valign="top">Cambios en la infraestructura de transporte, entrada de competidores locales o globales.</td><td colspan="1" valign="top">Entrada de nuevos competidores, cambios en las políticas de datos de transporte público.</td><td colspan="1" valign="top">Cambios en la infraestructura de transporte, entrada de nuevos competidores con características similares.</td><td colspan="1" valign="top"> Cambios en las políticas de transporte, entrada de nuevos competidores con enfoques similares.</td></tr></tbody></table>

<div class="page"/>

### 2.1.2. Estrategias y tácticas frente a competidores

1. **Diferenciación de Producto:**

Estrategia: TrackMyRoute se enfocará en resaltar las características únicas de la aplicación, como la integración con empresas de transporte público locales y la oferta de una versión premium con funciones exclusivas.
  <br>  <br>
Tácticas: Para llevar a cabo esta estrategia, se implementarán campañas de marketing que destaquen estas características distintivas, utilizando mensajes claros y persuasivos para comunicar el valor añadido de la aplicación en comparación con los competidores.

2. **Desarrollo Continuo:**

Estrategia: La startup se comprometerá a mantenerse actualizada con las últimas tendencias y tecnologías en el mercado de movilidad urbana.
  <br>  <br>
Tácticas: Para lograr esto, se planificarán actualizaciones frecuentes de la aplicación para mejorar la experiencia del usuario, se agregarán nuevas características basadas en comentarios de usuarios y análisis de competidores, y se buscarán colaboraciones con empresas de transporte público para integrar nuevas funcionalidades.

3. **Colaboraciones Estratégicas:**

Estrategia: Se buscarán asociaciones con empresas de transporte público y otras organizaciones relacionadas con la movilidad urbana.
  <br>  <br>
Tácticas: Para implementar esta estrategia, la startup identificará oportunidades para colaborar con empresas de transporte público en la mejora de la infraestructura de datos, ofrecerá promociones y descuentos exclusivos para los usuarios de la aplicación en colaboración con estas empresas, y participará activamente en eventos y conferencias de la industria para establecer conexiones con otras organizaciones del sector.

4. **Enfoque en la Experiencia del Usuario:**

Estrategia: La prioridad será la satisfacción del usuario y la facilidad de uso de la aplicación.
  <br>  <br>
Tácticas: Para llevar a cabo esta estrategia, se realizarán pruebas de usuario para identificar áreas de mejora en la experiencia del usuario, se ofrecerá soporte técnico receptivo y eficiente, y se proporcionarán recursos educativos y tutoriales para ayudar a los usuarios a aprovechar al máximo la aplicación.

5. **Análisis Competitivo Continuo:**

Estrategia: La startup se comprometerá a monitorear de cerca las acciones y estrategias de los competidores.
  <br>  <br>
Tácticas: Para ejecutar esta estrategia, se realizarán análisis periódicos de la competencia para identificar nuevas oportunidades y amenazas, se seguirán de cerca las actualizaciones y lanzamientos de productos de los competidores, y se ajustará la estrategia de la startup en función de los cambios en el mercado competitivo.

<div class="page"/>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
Nuestro objetivo es obtener información sobre las necesidades y los problemas de los usuarios de
transporte público en Lima. Esta información se utilizará para mejorar el servicio de nuestra empresa.
Nuestros participantes serán usuarios de transporte público en Lima. Se seleccionarán participantes
con diferentes perfiles, como edad, género, lugar de residencia, y frecuencia de uso del transporte
público.
Las preguntas serán abiertas y no directivas para que los participantes puedan expresar sus opiniones
libremente. A continuación, se presentan algunos ejemplos de preguntas:

**Segmento 1: Usuarios Diarios de Transporte Público en Lima:**

- ¿Con qué frecuencia utilizas el transporte público en Lima?
- ¿Cuál es tu principal motivo para utilizar el transporte público en lugar de otros medios de transporte?
- ¿Cuáles son los horarios en los que más utilizas el transporte público y por qué?
- ¿Has experimentado problemas de puntualidad con el transporte público? Si es así, ¿puedes describir una situación en la que esto haya sido un problema para ti?
- ¿Has tenido alguna experiencia negativa o insegura mientras usabas el transporte público en Lima? Si es así, ¿puedes contarnos más al respecto?
- ¿Qué tan satisfecho estás con la accesibilidad del transporte público en términos de paradas, estaciones y rutas disponibles?
- ¿Cómo te enteras de las actualizaciones o cambios en el servicio de transporte público en Lima?
- ¿Has utilizado aplicaciones o sitios web relacionados con el transporte público en Lima? Si es así, ¿cuál ha sido tu experiencia con ellos?
- ¿Qué características de nuestra aplicación encuentras más útiles en tu rutina de viaje diario?
- ¿Hay alguna característica específica que sientas que falta en la aplicación y que te gustaría ver implementada?
- ¿Cómo crees que podríamos mejorar la experiencia general de los usuarios en nuestra aplicación de transporte público? 

**Segmento 2: Empresas de transporte en Lima:**

- ¿Cuál es el nombre de su empresa de transporte público?
- ¿Cuál es su rol dentro de la empresa?
- ¿Podría describir brevemente las principales operaciones y servicios de transporte que ofrece su empresa en Lima?
- ¿Qué desafíos enfrenta actualmente su empresa en términos de operaciones de transporte y atención al cliente?
- ¿Está su empresa utilizando alguna aplicación o plataforma tecnológica para gestionar sus servicios de transporte?
- ¿Qué características o funcionalidades consideraría más útiles en una aplicación destinada a empresas de transporte público como la suya?
- ¿Cómo cree que una aplicación de este tipo podría mejorar la eficiencia y la calidad de los servicios de transporte que ofrece su empresa?
- ¿Qué aspectos consideraría más importantes al evaluar y seleccionar una aplicación para su empresa?
- ¿Cuál sería su principal preocupación o requisito al considerar la adopción de una nueva aplicación o plataforma tecnológica para su empresa de transporte público?
- ¿Tiene alguna experiencia previa en la implementación o uso de aplicaciones similares en su empresa o en la industria del transporte público en general?

### 2.2.2. Registro de entrevistas

#### **Entrevista 01**

- Nombre y apellidos: Melina Dayana Rojas Sosa

- Edad: 19 años

- Ubicación: Lima

- Duración: 3:52

Evidencia de la reunión:

<div align="center">
  <img src="assets/Entrevista01.png">
</div>

- Inicio: 00:04

- Fin: 3:50

**Enlace de entrevista:** [Click aqui para ver el video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218664_upc_edu_pe/EfbeZ9aRnCVLs6ENJGMY35sB3pyCcLOu_7eoZd384gBMDA?e=1vWH3v&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Resumen de la entrevista:**

Mi compañera Dayana Rojas es actualmente una estudiante universitaria que usa diariamente el transporte publico ya que es mas economico y es lo mas rapido que puede escoger, nos comento sobre su mala experiencia que le ocurrio de camino a casa despues de la universidad, es algo para tomar en consideraciòn por ese motivo estaria dispuesta a usar una aplicaciòn que le de esa seguridad que como usuaria necesite. 

#### **Entrevista 02**

- Nombre y apellidos: Fabio Horna

- Edad: 24 años

- Ubicación: Lima

- Duración: 2:57

Evidencia de la reunión:

<div align="center">
  <img src="assets/Entrevista02.jpg">
</div>

- Inicio: 00:04

- Fin: 02:57

**Enlace de entrevista:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202018894_upc_edu_pe/EddQn8WabOhChWfh2viP_c8BR0u5fm4qwyeLOcOZLOEE1g?e=uzQA3P&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Resumen de la entrevista:**

Nuestro entrevistado fue Fabio Horna, un joven de 24 años que trabaja en una empresa de transporte público, discutió varios aspectos de su rol como auditor y las operaciones de la empresa en Lima. Explicó los servicios de transporte que ofrece la empresa, identificando los desafíos actuales en operaciones y atención al cliente, como la eficiencia y la satisfacción del usuario. Además, mencionó que su empresa desea incorporar tecnología para mejorar la gestión de los servicios, y destacó las funcionalidades importantes que debería tener una aplicación para optimizar estos procesos. Fabio valoró características como la usabilidad y la integración de datos al seleccionar tecnología y expresó preocupaciones sobre la implementación efectiva de nuevas plataformas. También compartió experiencias previas con tecnologías similares en el sector del transporte público.

#### **Entrevista 03**

- Nombre y apellidos: Alejandra Orrego

- Edad: 24 años

- Ubicación: Lima

- Duración: 5:08 minutos

Evidencia de la reunión:

<div align="center">
  <img src="assets/Entrevista04.png">
</div>

**Enlace de entrevista:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u201921734_upc_edu_pe/EXHEG_PwxKBMo-Saj7qtUhMBvdCQxVidwivN3u5SeOohaQ?e=hi2ysX 

**Resumen de la entrevista:**

El análisis de la entrevista revela que los usuarios de transporte público en Lima valoran la puntualidad, la disponibilidad de información actualizada y la seguridad durante los viajes. Utilizan principalmente dispositivos móviles para acceder a aplicaciones y canales digitales, como Google Maps y Moovit, para planificar sus viajes. Esperan características como la visualización en tiempo real de los autobuses y notificaciones sobre cambios en el servicio, junto con una interfaz intuitiva y opciones de personalización. Su disposición a pagar por una versión premium depende de si ofrece mejoras significativas en la experiencia de viaje. En resumen, los usuarios buscan una aplicación confiable, precisa y fácil de usar que satisfaga sus necesidades de planificación de viajes en transporte público y mejore su experiencia general.

<div class="page"/>

### 2.2.3. Análisis de entrevistas

**Análisis de las Entrevistas: Usuarios Regulares del Transporte Público en Lima**

El análisis de la entrevista revela que los usuarios de transporte público en Lima valoran la puntualidad, la disponibilidad de información actualizada y la seguridad durante los viajes. Utilizan principalmente dispositivos móviles para acceder a aplicaciones y canales digitales, como Google Maps y Moovit, para planificar sus viajes. Esperan características como la visualización en tiempo real de los autobuses y notificaciones sobre cambios en el servicio, junto con una interfaz intuitiva y opciones de personalización. Su disposición a pagar por una versión premium depende de si ofrece mejoras significativas en la experiencia de viaje. En resumen, los usuarios buscan una aplicación confiable, precisa y fácil de usar que satisfaga sus necesidades de planificación de viajes en transporte público y mejore su experiencia general.

**Análisis de las Entrevistas: Empresas de Transporte Público en Lima**

Las empresas de transporte público en Lima expresaron la necesidad de una aplicación que les permita optimizar la gestión de sus flotas, coordinar horarios y mejorar la eficiencia operativa. Esperan una aplicación fácil de usar que proporcione información precisa y actualizada sobre las rutas de transporte público, los horarios y las ubicaciones de las paradas. Además, valorarían características adicionales como la capacidad de gestionar flotas de manera eficiente, la generación de informes de rendimiento y la integración con sistemas de pago electrónico. La fiabilidad y la consistencia en el funcionamiento de la aplicación son aspectos clave para estas empresas, quienes necesitan contar con una herramienta confiable para gestionar sus operaciones diarias. Están abiertas a colaborar estrechamente con los desarrolladores de la aplicación para adaptarla a sus necesidades específicas y garantizar una implementación exitosa en sus operaciones

## 2.3. Needfinding
### 2.3.1. User Personas

Los User Personas son necesarios para la formación de este proyecto, ya que brindan una perspectiva completa de los usuarios clave. Estos perfiles detallados permiten a la startup diseñar una plataforma y experiencia enfocada y personalizada, abordando de manera efectiva los desafíos específicos de cada segmento objetivo:

<div class="page"/>

**User Persona del segmento: Usuarios Diarios de Transporte Público en Lima**

<div align="center">
  <img src="https://i.imgur.com/ebiHXz2.png">
</div>

<div class="page"/>

**User Persona del segmento: Empresas de transporte en Lima**

<div align="center">
  <img src="https://i.imgur.com/Tz0fqBD.png">
</div>
<br>

<div class="page"/>

### 2.3.2. User Task Matrix

En esta seccion, se describen las tareas típicas que realizan los dos segmentos objetivos. Se evalúa la frecuencia y la severidad de cada tarea de los user persona, lo que ayuda a priorizar y entender cuáles son las áreas clave en las que el producto podría influir.

**Segmento Objetivo:** Usuarios Diarios de Transporte Público en Lima

|                               Tarea                               |  Frecuencia  | Severidad |
| :---------------------------------------------------------------: | :----------: | :-------: |
|          Planificar viajes diarios        | Casi siempre |   Alta    |
|               Obtener información sobre transporte público            | Casi siempre |   Alta     |
|         Minimizar tiempo de viaje        |  Casi siempre    |   Alta    |
|              Evitar retrasos en el transporte público             |   Casi siempre  |   Alta    |
|  Acceder a noticias locales  | A veces |   Media   |
|    Buscar eventos locales   |   A veces    |   Media   |
|          Acceder a descuentos locales         |   A veces    |   Media   |
| Utilizar transporte público en horarios no laborales  |   Rara vez    |   Baja    |
| Interactuar con la aplicación |   Casi siempre    |   Alta   |

**Segmento Objetivo:** Empresas de transporte en Lima

| Tareas                                                               | Frecuencia   | Severidad |
| -------------------------------------------------------------------- | ------------ | --------- |
| Registrar la empresa en la aplicación            | Una vez | Alta      |
| Configurar y personalizar la aplicación | Rara vez | Alta     |
| Programar rutas y horarios de los vehículos                | Casi Siempre  | Alta      |
| Supervisar el estado y la ubicación de los vehículos        | Casi siempre     | Alta      |
| Comunicarse con los conductores en tiempo real           | Casi siempre     | Alta      |
| Generar informes de rendimiento y eficiencia  | Rara vez | Alta    |
| Integrar la aplicación con sistemas de pago     | Rara vez     | Alta    |
| Proporcionar retroalimentación sobre la aplicación     | Rara vez      | Media    |
| Monitorear la satisfacción del cliente y gestionar quejas | Casi siempre     | Media   |

<div class="page"/>

### 2.3.3. User Journey Mapping

**User Journey Mapping del segmento: Usuarios Diarios de Transporte Público en Lima**

<div align="center">
  <img src="assets/UserJourneyUsuario.png">
</div>

<div class="page"/>

**User Journey Mapping del segmento: Empresas de transporte en Lima**

<div align="center">
  <img src="assets/UserJourneyEmpresa.png">
</div>

<div class="page"/>

### 2.3.4. Empathy Mapping

<div align="center">
  <img src="assets/EmpathyMap.jpg">
</div>

<div class="page"/>

### 2.3.5. As-is Scenario Mapping

As-is Map del Usuario
<div align="center">
  <img src="assets/AsIsMapUsuario.jpg">
</div>

<br>

As-is Map de la Empresa
<div align="center">
  <img src="assets/AsIsMapEmpresa.jpg">
</div>

<div class="page"/>

## 2.4. Requirements Specifications
### 2.4.1. To-Be Scenario Mapping

Con la herramiento del To-be scenario mapping exploramos las mejoras y las nuevas funcionalidades que se incorporarán en la aplicación “TrackMyRoute”. Estas mejoras están diseñadas para optimizar la experiencia de los usuarios al movilizarse por la ciudad de Lima en transporte público y proporcionar a la empresa de transporte una visión en tiempo real de sus clientes. A través de este proceso, visualizamos cómo la aplicación evolucionará para brindar un servicio más eficiente y útil a los dos grupos de usuarios.

<div align="center">
  <img src="assets/ToBeMap.jpg">
</div>
<br>

<div class="page"/>

### 2.4.2. User Stories

En la sección de User Stories, detallaremos las diversas necesidades y requerimientos de nuestros
usuarios y la empresa de transporte. Cada historia de usuario representará un escenario o una función
específica que se espera que la aplicación proporcione, con el objetivo de cumplir connuestro
propósito principal: ayudar a las personas a navegar por la ciudad de Lima utilizando el transporte
público de manera eficiente y brindar a la empresa de transporte información en tiempo real sobre sus
clientes. A través de estas historias de usuario, podremos comprender mejor cómo la aplicación
satisfará las necesidades de ambas partes y proporcionará una solución integral para la movilidad
urbana.

| **Epic / Story ID** | **Título**                                      | **Descripción**                                                                                                                                                                                                    | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)** |
|---------------------|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| HU01                | Registrar al usuario                            | Como cliente quiero registrarme con todos mis datos pertinentes (nombre, correo, edad, etc.) en la aplicación para poder hacer uso de sus funcionalidades.                                                         | Escenario: El cliente se registra en la aplicación. Dado que el cliente se encuentra en la pantalla de inicio de sesión,Y el cliente quiere registrarse para usar la aplicación,Cuando el cliente rellena un formulario de creación de una cuenta nueva con todos sus datos personales pertinentes,Entonces el sistema guardará todos sus datos y le permitirá acceder a las funcionalidades de la aplicación.                                                                       | HU02                          |
| HU02                | Inicio de sesión en la aplicación               | Como cliente quiero iniciar sesión en la aplicación con mis credenciales (correo y contraseña) para poder entrar a la aplicación con mi cuenta existente                                                           | Escenario: El cliente quiere iniciar sesión en la aplicación Dado que el cliente se encuentra en la pantalla de inicio de sesión,Y el usuario ya tiene una cuenta existente,Cuando el cliente rellena los campos de la pantalla de inicio de sesión con sus credenciales (correo y contraseña) correctamente,Entonces el cliente podrá acceder a las funcionalidades de la aplicación con su cuenta existente.                                                                       | HU01                          |
| HU03                | Eliminar cuenta o usuario                       | Como cliente quiero tener la posibilidad de borrar mi cuenta para que mis datos ya no permanezcan en la base de datos de la aplicación.                                                                            | Escenario: El cliente quiere eliminar una cuenta o usuario Dado que el cliente se encuentra en la pantalla de ajustes de la cuenta,Y el cliente tiene la intención de borrar su cuenta,Cuando el cliente selecciona la opción de borrar su cuenta en la aplicación,Entonces la aplicación eliminará su cuenta y los datos personales del cliente de la base de datos.                                                                                                                | HU01,HU02                     |
| HU04                | Registro de rutas y buses                       | Como desarrollador quiero registrar a las rutas de transporte urbano y a los buses que transitan por estas para así tener un registro de todas las que se encuentren en Lima.                                      | Escenario: el desarrollador quiere registrar las rutas de los buses. Dado que el desarrollador se encuentra en la pantalla de ingreso de datos en la base de datos,Y el desarrollador tiene a la mano los datos de las rutas y los buses,Cuando el desarrollador quiera insertar los datos pertinentes,Entonces la aplicación guardará en la base de datos todos los datos relacionados con las rutas y los buses                                                                    | HU05, HU06                    |
| HU05                | Registro de conductores                         | Como desarrollador quiero registrar a los conductores de los buses para así tener un registro de todos los conductores que transitan por las rutas por motivos de seguridad al usuario.                            | Escenario: El desarrollador quiere registrar a los conductores de los buses. Dado que el desarrollador se encuentra en la pantalla de ingreso de datos en la base de datos,Y el desarrollador tiene a la mano los datos de las rutas y los buses,Cuando el desarrollador quiera insertar los datos pertinentes,Entonces la aplicación guardará en la base de datos todos los datos relacionados con las rutas y los buses.                                                           | HU04, HU06                    |
| HU06                | Registro de las empresas operadoras de rutas    | Como desarrollador quiero registrar a las empresas que operan en cada una de las rutas de transporte urbano en buses para así tener un registro de todas estas empresas en la base de datos de la aplicación       | Escenario: El desarrollador quiere registrar a las empresas operadoras de rutas. Dado que el desarrollador se encuentra en la pantalla de ingreso de datos en la base de datos,Y el desarrollador tiene a la mano los datos de las empresas operadoras de las rutas de transporte de buses,Cuando el desarrollador quiera insertar los datos pertinentes, Entonces la aplicación guardará en la base de datos todos los datos relacionados con las empresas operadoras de las rutas. | HU04, HU05                    |
| HU07                | Implementación de servicios externos            | Como desarrollador quiero implementar servicios externos de otras empresas como Google Maps para así poder darle la funcionalidad deseada a la aplicación sin tener que desarrollar todo desde cero                | Escenario: El desarrollador quiere implementar servicios externos a la app.Dado que el desarrollador se encuentra en la pantalla de implementación de servicios externos,Y el desarrollador ha juntado el código y los requisitos necesarios para llamar al servicio externo,Cuando el desarrollador quiera crear una funcionalidad que llame a un servicio externo de otra empresa,Entonces la aplicación hará uso de este servicio cuando lo requiera.                             | HU06                          |
| HU08                | Visualización del menú de opciones              | Como cliente quiero ver el menú de opciones de la aplicación para así tener una idea de las funcionalidades que están presentes en esta.                                                                           | Escenario: El cliente quiere ver las funciones de la aplicación.Dado que el cliente se encuentra en la pantalla de inicio de la aplicación,Y el cliente quiere ver qué puede ser la aplicación,Cuando el cliente selecciona el botón que abre el menú de opciones,Entonces la aplicación deberá mostrarle al usuario el menú de opciones con todas las funcionalidades presentes.                                                                                                    | HU10                          |
| HU09                | Configuración de búsqueda de ruta personalizada | Como cliente quiero modificar ciertas opciones relacionadas a la búsqueda de rutas (tiempo de viaje, distancia al paradero, mostrar la ruta más rápida, etc.) para optimizar esta búsqueda según mis preferencias. | Escenario: El cliente quiere realizar una búsqueda personalizada.Dado que el cliente se encuentra en la pantalla de búsqueda de rutas,Y el cliente quiere especificar las condiciones de búsqueda según su parecer,Cuando el cliente modifique los criterios de búsqueda,Entonces la aplicación le mostrará las rutas disponibles según los filtros de búsqueda establecidos por el usuario.                                                                                         | HU10                          |
| HU10 | Visualización del mapa                        | Como cliente quiero ver un mapa interactivo con las rutas presentes para tener una idea más clara del posible camino por el que quiera viajar.                                                                                                      | Escenario: El cliente quiere ver el mapa. Dado que el cliente se encuentra en la pantalla principal, Y el cliente desea visualizar el mapa  con las rutas disponibles, Cuando el cliente seleccione la opción  de buscar rutas e ingrese todos los filtros que desee, Entonces la aplicación deberá mostrar  un mapa interactivo de la zona con las posibles rutas.                                                                                                                                                   | HU12       |
| HU11 | Visualización de costos del pasaje            | Como cliente quiero ver el costo del pasaje aproximado al elegir una ruta en la aplicación para saber con anticipación cuánto dinero debo tener para costear el viaje                                                                               | Escenario: El cliente quiere ver los costos de pasaje. Dado que el cliente se encuentra en la pantalla principal, Y el cliente desea ver cuánto le costaría realizar un viaje por cierta ruta, Cuando el cliente haya seleccionado  la opción de buscar rutas y haya  realizado la búsqueda de las rutas  disponibles, Entonces la aplicación deberá mostrar el costo aproximado de cada viaje por ruta.                                                                                                              | HU12       |
| HU12 | Visualización del número de buses a abordar   | Como cliente quiero ver cuántos buses se tiene que abordar para llegar al destino para determinar qué ruta sería la mejor conforme a la situación en la que me encuentre.                                                                           | Escenario: El cliente quiere ver cuántos buses puede abordar Dado que el cliente se encuentra en la pantalla principal, Y el cliente desea saber cuántos buses debe abordar para llegar a cierto lugar, Cuando el cliente haya seleccionado la opción de buscar rutas y haya realizado la búsqueda de las rutas disponibles, Entonces la aplicación deberá mostrar la cantidad de buses que se deberá abordar para llegar al destino.                                                                                 | HU14       |
| HU13 | Planificación de viajes                       | Como cliente quiero planificar mis viajes en función a mi ubicación actual y al destino (se muestran los horarios de salida y de llegada de los buses, su ubicación, etc.) para organizar mejor mis tiempos.                                        | Escenario: El cliente quiere planificar un viaje Dado que el cliente se encuentra en la pantalla principal, Y el cliente desea planificar un viaje, Cuando el cliente haya seleccionado la opción de buscar rutas y haya realizado la búsqueda de las rutas disponibles, Entonces la aplicación deberá permitirle al cliente el planificar su viaje dependiendo de los tiempos estimados del viaje hipotético.                                                                                                        | HU15       |
| HU14 | Información en tiempo real                    | Como cliente quiero observar la información pertinente a mi viaje en tiempo real (ubicación actual de los autobuses, su hora estimada de llegada y cualquier retraso o cambio en la ruta) para tomar mejores decisiones en el acto.                 | Escenario: El cliente quiere ver información de los buses en tiempo real Dado que el cliente ya eligió la ruta en la que desea viajar, Y el cliente desea ver información pertinente a su viaje en tiempo real, Cuando el cliente seleccione la opción para ver la información en tiempo real, Entonces la aplicación le tendrá que mostrar al cliente toda la información relacionada a su viaje actualizada y en tiempo real.                                                                                       | HU17       |
| HU15 | Compra de boletos                             | Como cliente quiero comprar boletos para el transporte público directamente desde la aplicación para agilizar y facilitar el proceso de pago por los boletos o pasajes.                                                                             | Escenario: El cliente quiere comprar un boleto anticipadamente Dado que el cliente ya eligió la ruta en la que desea viajar, Y los buses en los cuales el cliente va a viajar tienen el pago de pasajes por la aplicación disponible, Cuando el cliente le de a la opción para pagar por la aplicación, Entonces la aplicación le permitirá al cliente pagar por el boleto o pasaje desde esta.                                                                                                                       | HU13       |
| HU16 | Notificaciones personalizadas                 | Como cliente quiero recibir notificaciones personalizadas acerca de eventos pertinentes a mi viaje en bus (retrasos, horarios, etc.) para estar al tanto de las situaciones que pueden afectar mi futuro viaje                                      | Escenario: El cliente quiere recibir notificaciones acerca de eventos de buses Dado que el cliente está al tanto de las notificaciones de su celular, Cuando ocurra un evento de importancia para el viaje del cliente, Entonces la aplicación emitirá una notificación, la cual el cliente puede ver o ignorar si es que lo considera necesario.                                                                                                                                                                     | HU14       |
| HU17 | Mapas interactivos                            | Como cliente quiero visualizar mapas interactivos en los que pueda ver la ubicación de las paradas de autobús, la ruta y la ubicación de los autobuses en tiempo real, para así poder tomar mejores decisiones en el momento sobre qué ruta elegir. | Escenario: El cliente quiere visualizar mapas interactivos Dado que el cliente se encuentra en la pantalla principal, Y el cliente desea visualizar el mapa con las rutas disponibles, Cuando el cliente seleccione la opción de buscar rutas e ingrese todos los filtros que desee, Entonces la aplicación deberá mostrar un mapa interactivo de la zona donde se puede ver la ubicación de las paradas de autobús, la ruta y la ubicación de los autobuses en tiempo real.                                          | HU10, HU14 |
| HU18 | Integración con otros servicios de transporte | Como desarrollador quiero integrar la aplicación con otros servicios de transporte público, como trenes o tranvías, para permitir a los usuarios planificar viajes intermodales.                                                                    | Escenario: El desarrollador quiere implementar otros servicios de transporte Dado que el desarrollador se encuentra en la pantalla de implementación de servicios externos, Y el desarrollador ha juntado el código y los requisitos necesarios para incluir a otro servicio de transporte público, Cuando el desarrollador quiera crear una funcionalidad que se integre con otro servicio, Entonces la aplicación hará uso de esta función para permitirles a los clientes la planificación de viajes intermodales. | HU04       |
| HU19 | Accesibilidad                                 | Como desarrollador quiero hacer la aplicación más accesible para personas con discapacidades, ofreciendo opciones de accesibilidad como la navegación por voz y el alto contraste, para ampliar la cantidad de posibles usuarios.                   | Escenario: El desarrollador quiere hacer la aplicación más accesible para el usuario Dado que el desarrollador se encuentra en la pantalla de implementación de servicios de accesibilidad, Y el desarrollador ha juntado el código y los requisitos necesarios para hacer uso de herramientas de accesibilidad, Cuando el desarrollador quiera crear una funcionalidad que mejore la accesibilidad de la aplicación, Entonces la aplicación integrará esta funcionalidad.                                            | HU20       |
| HU20 | Retroalimentación de los usuarios             | Como cliente quiero dar una retroalimentación sobre mi experiencia de viaje o al utilizar la aplicación para dar a conocer mi agrado o mi malestar con respecto al funcionamiento de esta.                                                          | Escenario: El cliente quiere dar una retroalimentación sobre la app. Dado que el cliente está en la pantalla principal de la aplicación, Y el cliente desee dar una retroalimentación sobre su experiencia, Cuando el cliente seleccione la opción para dar una retroalimentación, Entonces la aplicación le deberá dar la posibilidad al cliente de dar una retroalimentación tanto sobre su viaje en el bus, la ruta o la funcionalidad de la aplicación en general.                                                | HU19       |
| HU21 | Integración de api de transporte público         | como desarrollador, quiero integrar una api de transporte público para acceder a datos actualizados sobre rutas, horarios y paradas de transporte público en tiempo real.                               | dado que se ha establecido la conexión con la api de transporte público, cuando realizo una solicitud de búsqueda de rutas con una ubicación de origen y destino, entonces la aplicación devuelve datos precisos y actualizados sobre las rutas disponibles, horarios de salida y llegada, y paradas intermedias.                             | HU12, HU14 |
| HU22 | Implementación de sistema de autenticación oauth | como desarrollador, quiero implementar un sistema de autenticación oauth para permitir que los usuarios inicien sesión utilizando sus cuentas de redes sociales.                                        | dado que un usuario intenta iniciar sesión en la aplicación utilizando oauth, cuando selecciona la opción de inicio de sesión con una plataforma de redes sociales, entonces la aplicación redirige al usuario al sitio web de la plataforma de redes sociales para autorizar el acceso.                                                      | HU01, HU02 |
| HU23 | Desarrollo de algoritmo de ruta óptima           | como desarrollador, quiero diseñar un algoritmo eficiente para calcular la ruta óptima entre dos puntos dados, teniendo en cuenta factores como la distancia, el tiempo y las preferencias del usuario. | dado que un usuario solicita una búsqueda de ruta entre dos ubicaciones, cuando el algoritmo calcula la ruta óptima basada en las preferencias del usuario y los datos de transporte disponibles, entonces la aplicación devuelve la ruta más rápida y eficiente, considerando factores como la duración del viaje y el número de trasbordos. | HU13       |
| HU24 | Sección principal de landing page                | como visitante de la landing page, quiero ser recibido por una sección principal llamativa para captar mi atención y despertar mi interés en explorar más sobre la aplicación de seguimiento de rutas.  | dado que ingreso a la landing page, cuando miro la sección principal, entonces encuentro un diseño visualmente atractivo con un mensaje claro y conciso que destaque las características únicas de la aplicación.                                                                                                                             |            |
| HU25 | Información de beneficios                        | como visitante de la landing page, quiero encontrar una sección dedicada a los beneficios de la aplicación de seguimiento de rutas para comprender cómo puede mejorar mi experiencia de viaje.          | dado que estoy interesado en la aplicación, cuando navego por la sección de beneficios, entonces encuentro información clara y convincente sobre cómo la aplicación puede ayudarme a planificar mejor mis viajes, ahorrar tiempo y optimizar mis desplazamientos diarios.                                                                     |            |
| HU26 | Conocer los aliados que respaldan la app         | como visitante de la landing page, quiero ver una lista de aliados que respaldan la aplicación de seguimiento de rutas para sentir confianza en su calidad y fiabilidad.                                | dado que estoy interesado en la aplicación, cuando reviso la sección de aliados, entonces encuentro logotipos o testimonios de empresas, organizaciones o autoridades que respaldan y confían en la aplicación.                                                                                                                               |            |
| HU27 | Reseñas de usuarios satisfechos                  | como visitante de la landing page, quiero encontrar reseñas y testimonios de usuarios satisfechos para obtener una idea de su experiencia y satisfacción con la aplicación.                             | dado que estoy interesado en la aplicación, cuando busco la sección de reseñas, entonces encuentro testimonios reales de usuarios que describen cómo la aplicación ha mejorado su experiencia de viaje y les ha ayudado en sus desplazamientos diarios.                                                                                       |            |
| HU28 | Conocer los planes de suscripción                | como visitante de la landing page, quiero encontrar información sobre los planes de suscripción disponibles para entender las opciones de pago y beneficios asociados con cada plan.                    | dado que estoy interesado en utilizar la aplicación de forma regular, cuando navego por la sección de planes de suscripción, entonces encuentro una descripción clara de los diferentes planes disponibles, sus precios y las características incluidas en cada uno.                                                                          |            |
| HU29 | Obtener respuestas a preguntas frecuentes        | como visitante de la landing page, quiero acceder a una sección de preguntas frecuentes para encontrar respuestas a mis dudas más comunes sobre la aplicación de seguimiento de rutas.                  | dado que tengo preguntas sobre la aplicación, cuando accedo a la sección de preguntas frecuentes, entonces encuentro una lista completa de preguntas comunes y sus respuestas claras y concisas, lo que me ayuda a entender mejor cómo funciona la aplicación y cómo puedo utilizarla eficazmente.                                            |            |
|HU30 | Promociones | Como cliente, quiero ver las promociones disponibles en la aplicación para que pueda aprovechar descuentos al utilizar el servicio de transporte público. | Dado que el cliente abre la aplicación, Cuando accede a la sección de promociones, Entonces se muestran claramente todas las promociones vigentes, incluyendo sus términos y condiciones. |
|HU31 | Soporte y Ayuda | Como cliente, quiero tener acceso a opciones de soporte y ayuda dentro de la aplicación para que pueda resolver cualquier problema o duda que pueda surgir durante su uso. | Dado que el cliente necesita ayuda o soporte, Cuando accede a la sección de soporte y ayuda, Entonces encuentra información detallada sobre cómo contactar al servicio de atención al cliente, así como preguntas frecuentes y tutoriales útiles. | 
|HU32 | Configuración | Como cliente, quiero tener la capacidad de personalizar la configuración de mi cuenta en la aplicación para que pueda adaptarla a mis preferencias y necesidades individuales. | Dado que el cliente desea personalizar su experiencia en la aplicación, Cuando accede a la sección de configuración de la cuenta, Entonces puede ajustar preferencias como notificaciones, idioma, método de pago, etc|
|HU33 | Historial de Viajes | Como cliente, quiero poder acceder a un historial detallado de mis viajes anteriores en la aplicación para que pueda realizar un seguimiento de mis desplazamientos y gastos. | Dado que el cliente desea revisar sus viajes pasados, Cuando accede a la sección de historial de viajes, Entonces se muestra una lista cronológica de todos los viajes realizados, incluyendo detalles como fecha, hora, ruta, costo, y método de pago utilizado.|
|HU34 | Recuperación de Contraseña | Como cliente, quiero tener la opción de recuperar mi contraseña en caso de olvido o pérdida para que pueda volver a acceder a mi cuenta sin problemas. | Dado que el cliente ha olvidado su contraseña, Cuando selecciona la opción de recuperación de contraseña e ingresa su dirección de correo electrónico o número de teléfono asociado a la cuenta, Entonces recibe un enlace o código de verificación que le permite restablecer su contraseña y acceder nuevamente a su cuenta.|

<div class="page"/>

### 2.4.3. Impact Mapping

En la sección de Impact Mapping, exploraremos las repercusiones más amplias y los objetivos
estratégicos que buscamos lograr con la implementación de esta aplicación. En lugar de centrarnos en
detalles técnicos o funcionalidades específicas, el Impact Mapping nos ayudará a comprender cómo
nuestro proyecto contribuirá a alcanzar metas más grandes y cómo afectará positivamente a los
diferentes grupos de interés. A través de este mapeo de impacto, identificaremos las conexiones entre
las características de la aplicación y los resultados deseados, lo que nos permitirá tomar decisiones
informadas sobre qué aspectos priorizar y cómo medir el éxito a largo plazo.

<div align="center">
  <img src="assets/ImpactMap.png">
</div>

<div class="page"/>

### 2.4.4. Product Backlog

|#Orden|User Story ID|Título|Descripción|Story Points|
|:----|:----|:----|:----|:----|
|1|HU07|Implementación de servicios externos|Como desarrollador quiero implementar servicios externos de otras empresas como Google Maps para así poder darle la funcionalidad deseada a la aplicación sin tener que desarrollar todo desde cero|5|
|2|HU09|Configuración de búsqueda de ruta personalizada|Como cliente quiero modificar ciertas opciones relacionadas a la búsqueda de rutas (tiempo de viaje, distancia al paradero, mostrar la ruta más rápida, etc.) para optimizar esta búsqueda según mis preferencias.|5|
|3|HU10|Visualización del mapa|Como cliente quiero ver un mapa interactivo con las rutas presentes para tener una idea más clara del posible camino por el que quiera viajar.|5|
|4|HU11|Visualización de costos del pasaje|Como cliente quiero ver el costo del pasaje aproximado al elegir una ruta en la aplicación para saber con anticipación cuánto dinero debo tener para costear el viaje|5|
|5|HU12|Visualización del número de buses a abordar|Como cliente quiero ver cuántos buses se tiene que abordar para llegar al destino para determinar qué ruta sería la mejor conforme a la situación en la que me encuentre.|5|
|6|HU13|Planificación de viajes|Como cliente quiero planificar mis viajes en función a mi ubicación actual y al destino (se muestran los horarios de salida y de llegada de los buses, su ubicación, etc.) para organizar mejor mis tiempos.|5|
|7|HU14|Información en tiempo real|Como cliente quiero observar la información pertinente a mi viaje en tiempo real (ubicación actual de los autobuses, su hora estimada de llegada y cualquier retraso o cambio en la ruta) para tomar mejores decisiones en el acto.|5|
|8|HU15|Compra de boletos|Como cliente quiero comprar boletos para el transporte público directamente desde la aplicación para agilizar y facilitar el proceso de pago por los boletos o pasajes.|5|
|9|HU17|Mapas interactivos|Como cliente quiero visualizar mapas interactivos en los que pueda ver la ubicación de las paradas de autobús, la ruta y la ubicación de los autobuses en tiempo real, para así poder tomar mejores decisiones en el momento sobre qué ruta elegir.|5|
|10|HU18|Integración con otros servicios de transporte|Como desarrollador quiero integrar la aplicación con otros servicios de transporte público, como trenes o tranvías, para permitir a los usuarios planificar viajes intermodales.|5|
|11|HU21|integración de api de transporte público|como desarrollador, quiero integrar una api de transporte público para acceder a datos actualizados sobre rutas, horarios y paradas de transporte público en tiempo real.|5|
|12|HU23|desarrollo de algoritmo de ruta óptima|como desarrollador, quiero diseñar un algoritmo eficiente para calcular la ruta óptima entre dos puntos dados, teniendo en cuenta factores como la distancia, el tiempo y las preferencias del usuario.|5|
|13|HU04|Registro de rutas y buses|Como desarrollador quiero registrar a las rutas de transporte urbano y a los buses que transitan por estas para así tener un registro de todas las que se encuentren en Lima.|3|
|14|HU05|Registro de conductores|Como desarrollador quiero registrar a los conductores de los buses para así tener un registro de todos los conductores que transitan por las rutas por motivos de seguridad al usuario.|3|
|15|HU06|Registro de las empresas operadoras de rutas|Como desarrollador quiero registrar a las empresas que operan en cada una de las rutas de transporte urbano en buses para así tener un registro de todas estas empresas en la base de datos de la aplicación|3|
|16|HU08|Visualización del menú de opciones|Como cliente quiero ver el menú de opciones de la aplicación para así tener una idea de las funcionalidades que están presentes en esta.|3|
|17|HU19|Accesibilidad|Como desarrollador quiero hacer la aplicación más accesible para personas con discapacidades, ofreciendo opciones de accesibilidad como la navegación por voz y el alto contraste, para ampliar la cantidad de posibles usuarios.|3|
|18|HU20|Retroalimentación de los usuarios|Como cliente quiero dar una retroalimentación sobre mi experiencia de viaje o al utilizar la aplicación para dar a conocer mi agrado o mi malestar con respecto al funcionamiento de esta.|3|
|19|HU22|implementación de sistema de autenticación oauth|como desarrollador, quiero implementar un sistema de autenticación oauth para permitir que los usuarios inicien sesión utilizando sus cuentas de redes sociales.|3|
|20|HU24|sección principal de landing page|como visitante de la landing page, quiero ser recibido por una sección principal llamativa para captar mi atención y despertar mi interés en explorar más sobre la aplicación de seguimiento de rutas.|3|
|21|HU25|información de beneficios|como visitante de la landing page, quiero encontrar una sección dedicada a los beneficios de la aplicación de seguimiento de rutas para comprender cómo puede mejorar mi experiencia de viaje.|3|
|22|HU26|conocer los aliados que respaldan la app|como visitante de la landing page, quiero ver una lista de aliados que respaldan la aplicación de seguimiento de rutas para sentir confianza en su calidad y fiabilidad.|3|
|23|HU27|reseñas de usuarios satisfechos|como visitante de la landing page, quiero encontrar reseñas y testimonios de usuarios satisfechos para obtener una idea de su experiencia y satisfacción con la aplicación.|3|
|24|HU28|conocer los planes de suscripción|como visitante de la landing page, quiero encontrar información sobre los planes de suscripción disponibles para entender las opciones de pago y beneficios asociados con cada plan.|3|
|25|HU29|obtener respuestas a preguntas frecuentes|como visitante de la landing page, quiero acceder a una sección de preguntas frecuentes para encontrar respuestas a mis dudas más comunes sobre la aplicación de seguimiento de rutas.|3|
|26|HU01|Registrar al usuario|Como cliente quiero registrarme con todos mis datos pertinentes (nombre, correo, edad, etc.) en la aplicación para poder hacer uso de sus funcionalidades.|2|
|27|HU02|Inicio de sesión en la aplicación|Como cliente quiero iniciar sesión en la aplicación con mis credenciales (correo y contraseña) para poder entrar a la aplicación con mi cuenta existente|2|
|28|HU03|Eliminar cuenta o usuario|Como cliente quiero tener la posibilidad de borrar mi cuenta para que mis datos ya no permanezcan en la base de datos de la aplicación.|2|
|29|HU16|Notificaciones personalizadas|Como cliente quiero recibir notificaciones personalizadas acerca de eventos pertinentes a mi viaje en bus (retrasos, horarios, etc.) para estar al tanto de las situaciones que pueden afectar mi futuro viaje|2|
|30| HU30 |Promociones |Como cliente, quiero ver las promociones disponibles en la aplicación para que pueda aprovechar descuentos al utilizar el servicio de transporte público.  | 2 |
|31|HU31 |Soporte y Ayuda |Como cliente, quiero tener acceso a opciones de soporte y ayuda dentro de la aplicación para que pueda resolver cualquier problema o duda que pueda surgir durante su uso. | 2|
|32|HU32 | Configuración | Como cliente, quiero tener la capacidad de personalizar la configuración de mi cuenta en la aplicación para que pueda adaptarla a mis preferencias y necesidades individuales.| 3|
|33|HU33 | Historial de Viajes| Como cliente, quiero poder acceder a un historial detallado de mis viajes anteriores en la aplicación para que pueda realizar un seguimiento de mis desplazamientos y gastos.| 5|
|34| HU34| Recuperación de Contraseña| Como cliente, quiero tener la opción de recuperar mi contraseña en caso de olvido o pérdida para que pueda volver a acceder a mi cuenta sin problemas| 3|


<div class="page"/>


# Capítulo III: Arquitectura
## 3.1. Product design
### 3.1.1. Style Guidelines

Las guías de estilo son los criterios y sugerencias creados para uniformar la apariencia, el estilo y la facilidad de uso tanto de la Landing Page como de la Aplicación Web.

#### 3.1.1.1. General Style Guidelines

La paleta de colores que estamos usando en nuestra Landing Page y Web Application son los siguientes:

<div align="center">
  <img src="assets/GeneralStyleGuidelines.png">
</div>

El tono predominante y fundamental de nuestra solución es el azul y sus diversas variaciones, seleccionado con el propósito de generar en nuestros usuarios sensaciones de confianza, seguridad y calma. Nuestra meta es mantener la simplicidad y el minimalismo para lograr que nuestros usuarios se sientan comodos con la aplicación.

Se ha seleccionado MuseoModerno para el logotipo, los títulos y los subtítulos de la Landing Page y la Aplicación Web, ya que su diseño evoca pistas y carreteras, lo cual se considera adecuado para nuestro producto. Para los textos, el contenido informativo y los botones de la Landing Page, se utilizará Montserrat.

<div align="center">
  <img src="assets/GeneralStyleGuidelines2.png">
</div>

Optamos por establecer un espaciado entre letras de 1,15 para los textos y el contenido de la página, y de 2 píxeles para los títulos y subtítulos, con el objetivo de garantizar una visualización óptima para nuestros usuarios.

En cuanto al tono de nuestra comunicación, será formal, cortés y tranquilo, ya que la mayoría de nuestro público objetivo son adultos.

### 3.1.2. Information Architecture

En este apartado, presentaremos el procedimiento de ordenar, configurar y categorizar el contenido de la Landing Page y la Aplicación Web de Track My Route de manera que resulte comprensible y accesible para nuestros usuarios. Ponemos énfasis en diseñar la estructura y la navegación de sistemas de información, asi como páginas web y sistemas de gestión de contenido, con el fin de potenciar la usabilidad y la experiencia del usuario.

#### 3.1.2.1. Organization Systems

- **Forma jerárquica**
        La aplicación web de TrackMyRoute se organizará de forma jerárquica, comenzando con un panel de control principal que ofrece acceso rápido a las funciones esenciales. Esto incluirá la búsqueda de rutas por ubicación y horarios en tiempo real, así como la opción de pago de pasajes. En un segundo nivel, los usuarios podrán acceder a su historial de viajes y pagos, además de encontrar promociones disponibles para ellos. En un nivel más profundo de jerarquía, tendrán la posibilidad de configurar notificaciones personalizadas y gestionar su perfil de usuario. Además, habrá una sección de ayuda que proporcionará recursos adicionales y soporte. Esta estructura jerárquica está diseñada para garantizar una navegación intuitiva y una experiencia fluida para los usuarios al buscar y gestionar información relacionada con el transporte público.
  
- **Organización secuencial (step-by-step to accomplish)**
        En la aplicación web de TrackMyRoute, se ha implementado la organización secuencial en situaciones donde los usuarios necesitan completar una serie de pasos en un orden específico para alcanzar un objetivo determinado. Por ejemplo, durante el proceso de registro de un nuevo usuario, se les guiará a través de una secuencia de pasos que incluirá la creación de una cuenta, la configuración de preferencias y la aceptación de los términos y condiciones. Esto también se observa al buscar rutas y autobuses, así como al pagar el pasaje a través de la aplicación. Esta metodología de organización secuencial ayuda a simplificar y estructurar procesos complejos, lo que facilita la navegación y la comprensión para los usuarios.
  
- **Organización matricial**
        En TrackMyRoute, se emplea la organización matricial en situaciones donde hay una diversidad de categorías o dimensiones que se entrelazan y se relacionan entre sí. Esto es evidente al buscar autobuses, donde se muestra un mapa junto con la información de los autobuses y se ofrecen filtros para refinar la búsqueda. Asimismo, se utiliza en la disposición visual de las promociones dirigidas a los usuarios.

#### 3.1.2.2. Labelling Systems

| Etiqueta            | Descripción                                                                                                                                    |
|:-------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|
| Buscar Rutas        | En esta sección se le mostrará al usuario avisos por parte de la aplicación                                                                    |
| Notificaciones      | En esta sección el usuario podrá ingresar su origen y destino y visualizar sus rutas y buses, así como un mapa con información en tiempo real. |
| Pagar Pasaje        | En esta sección el usuario podrá pagar sus pasajes de su ruta de manera anticipada para ser más eficiente a la hora de abordar el bus.         |
| Promociones         | En esta sección el usuario podrá acceder a distintas promociones que brindamos a nuestros usuarios premium                                     |
| Historial de Viajes | En esta sección el usuario podrá visualizar sus viajes anteriores y pasajes pagados.                                                           |
| Soporte y Ayuda     | En esta sección el usuario accede a ayuda por parte de nuestro equipo de soporte.                                                              |
| Configuración       | En esta sección el usuario puede configurar sus preferencias y su perfil.                                                                      |

#### 3.1.2.3. SEO Tags and Meta Tags

Los tags de SEO y Meta tags son cruciales ya que desempeñan una función vital en la optimización para motores de búsqueda (SEO), contribuyendo a mejorar la visibilidad y el ranking de una página web en los resultados de búsqueda. Por ende, para optimizar la búsqueda y el posicionamiento de TrackMyRoute, hemos implementado lo siguiente:

| Landing Page | Web Application |
|---------------|-----------------|
|**Title:** TrackMyRoute<br>**Description:** Optimiza tu viaje y libérate del estrés<br>**Keywords:** Autobús, Metro, Tren, Paradas, Ubicación, Tráfico, Planificador, Seguridad, Comodidad, Precisión, Horario, Buses en Lima, Rutas.<br>**Authors:** TrackMyRoute| **Title:**  TrackMyRoute <br> **Description:** Optimiza tu viaje y libérate del estrés <br> **Keywords:** Autobús, Metro, Tren, Paradas, Ubicación, Tráfico, Planificador, Seguridad, Comodidad, Precisión, Horario, Buses en Lima, Rutas, Buses, Seguimiento, Mapas, Transporte, Navegación, Tiempo, Notificaciones, Promociones, Pasajes, Historial. <br> **Authors:** TrackMyRoute|

#### 3.1.2.4. Searching Systems

 El sistema de búsqueda de nuestra aplicación se fundamenta en la ubicación de los autobuses y sus rutas, así como en los puntos de recogida de pasajeros. Esta funcionalidad estará conectada a una base de datos que contiene información sobre los autobuses, sus rutas y los costos de los pasajes. Por lo tanto, esta herramienta de búsqueda estará disponible en las secciones de "Buscar Rutas", "Pagar Pasajes" y "Historial de Viajes".

#### 3.1.2.5. Navigation Systems

Los métodos de navegación utilizados en TrackMyRoute son los siguientes:

1. Barra de navegación en la Landing Page: Los usuarios pueden desplazarse por nuestra Landing Page para familiarizarse con nuestra aplicación y comprender nuestra propuesta de valor.
2. Barra de navegación en la Aplicación Web: Los usuarios tienen la posibilidad de explorar los distintos apartados y funciones de nuestra propuesta utilizando la barra de navegación.
3. Tarjetas de promociones: Los usuarios pueden ver fácilmente las promociones que les ofrecemos a través de las tarjetas de promociones.

### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe

<div align="center">
  <img src="assets/LPWireframe.png">
</div>

#### 3.1.3.2. Landing Page Mock-up

<div align="center">
  <img src="assets/LPMockup.png">
</div>

### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes
#### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### 3.1.4.3. Mobile Applications Mock-ups
#### 3.1.4.4. Mobile Applications User Flow Diagrams
#### 3.1.4.5. Mobile Applications Prototyping

## 3.2. Architecture Overview
### 3.2.1. Domain-Driven Software Architecture

Para el modelo de negocio que utilizaremos para desarrollar nuestro software complejo que se centra en la problemática que abordamos. para ello utilizaremos la técnica de modelado C4 Model.

#### 3.2.1.1. Software Architecture Context Level Diagram

<div align="center">
  <img src="assets/ContextDiagram.png">
</div>

#### 3.2.1.2. Software Architecture Container Level Diagram

<div align="center">
  <img src="assets/ContainerDiagram.png">
</div>

#### 3.2.1.3. Software Architecture Components Diagram

<div align="center">
  <img src="assets/ComponentsDiagram1.png">
</div>

<div align="center">
  <img src="assets/ComponentsDiagram2.png">
</div>

<div align="center">
  <img src="assets/ComponentsDiagram3.png">
</div>

<div align="center">
  <img src="assets/ComponentsDiagram4.png">
</div>

### 3.2.2. Software Object-Oriented Design
#### 3.2.2.1. Class Diagrams

Para nuestro sistema, hemos implementado un diagrama de clases. Este diagrama visualiza la estructura estática del software, mostrando las clases, sus atributos y las relaciones entre ellas. Es una herramienta esencial que nos ayuda a comprender cómo se organizan y comunican las diferentes partes de nuestro sistema de software.

Diagramas de clases por módulo:
- User Interface:

<div align="center">
  <img src="assets/ClassUser.png">
</div>

- Subscription:

<div align="center">
  <img src="assets/ClassSubscription.png">
</div>

- FAQ:

<div align="center">
  <img src="assets/ClassFAQ.png">
</div>

- Track Route:

<div align="center">
  <img src="assets/ClassTrackRoute.png">
</div>

#### 3.2.2.2. Class Dictionary

Explicación del funcionamiento de cada función por módulo. 

Módulos:
- User Interface: Para explicar nuestro sistema de usuario este tendra que registrarse para luego iniciar sesion en su cuenta, donde este recibirá un correo para confirmar su creación, todo esto en una clase llamada UserInterface que recibirá toda la información.

<div align="center">
  <img src="assets/ClassDictionaryUser.png">
</div>

- Subscription: Este módulo de clases es referido a la elección que tenga el usuario sobre la subscripción que desea poseer.

<div align="center">
  <img src="assets/ClassDictionarySubscription.png">
</div>

- FAQ: Está dirigido a una parte más de dudas que tenga el usuario sobre el uso o funcionamiento de la aplicación.

<div align="center">
  <img src="assets/ClassDictionaryFAQ.png">
</div>

- Track Route: Este es el módulo que explica el funcionamiento principal de la aplicación, nos mostrará la ruta de los buses y çómo de acuerdo a las preferencias del usuario puede variar, además de una funcionalidad para pagar el servicio del bus que este desee tomar.

<div align="center">
  <img src="assets/ClassDictionaryTrackRoute.png">
</div>

#### 3.2.2.3. Database Design

Para el desarrollo del diseño de la base de datos hemos utilizado Vertabelo como herramienta, que nos ayudó mucho a trabajar colaborativamente.

<div align="center">
  <img src="assets/DatabaseDesign.png">
</div>

#### 3.2.2.4. Database Diagram

Para explicar el sistema de nuestra aplicación comencemos por las entidades como buses, company y customers cada una de ellas se refiere a los usuarios tanto de buses como el cliente que se transporta (éste de acuerdo a la subscripción que posea tiene distintos beneficios).

Tenemos una entidad que explica la data que va tener cada uno de los buses en nuestro sistema.

<div align="center">
  <img src="assets/DatabaseDiagram1.png">
</div>

Tenemos una entidad llamada TrackMyRouteBuses, ésta se refiere a la data que va recibir sobre las rutas que van a tomar los distintos servicios de buses.

<div align="center">
  <img src="assets/DatabaseDiagram2.png">
</div>

A su vez, éstas pueden ser personalizadas por el usuario

<div align="center">
  <img src="assets/DatabaseDiagram3.png">
</div>

Para que éste verifique si es válido la ruta que ha sido escogida y el status es un dato que se mandará a la entidad "Status_TrackRouteBuses".

<div align="center">
  <img src="assets/DatabaseDiagram4.png">
</div>

También tenemos una entidad la cual se encarga de ver la subscripción actual del usuario y qué beneficios este va poseer.

<div align="center">
  <img src="assets/DatabaseDiagram5.png">
</div>

<div class="page"/>

# Conclusiones
 
 Para esta entrega concluimos que es muy importante tener en cuenta la opinion de nuestros futuros usuarios, así como la ventaja competitiva que podemos brindar sobre nuestros competidores. Tambien concluimos que es necesaria una previa investigación y diseño de producto para tener claro los puntos principales de la aplicación.


# Referencias bibliográficas 

Batalla, C. (2021, 27 enero). ¿Cuándo empezó el caos vehicular en Lima? Así era el tránsito de la ciudad en los años 20. El Comercio Perú. https://elcomercio.pe/archivo-elcomercio/transporte-como-era-el-transito-de-lima-en-los-anos-20-nnsp-aptz-noticia/ 

Chacón, C. (2021, 26 julio). Bitácora Urbana - EL TRANSPORTE EN LIMA: Algunos apuntes de su proceso histórico. por: Carlos Chacón. Sociedad de Urbanistas del Perú. https://www.urbanistasperu.org/2021/07/26/el-transporte-en-lima-algunos-apuntes-de-su-proceso-historico/ 


# Anexos

**Enlaces a los videos de las entrevistas:** 
* Entrevista 1: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218664_upc_edu_pe/EfbeZ9aRnCVLs6ENJGMY35sB3pyCcLOu_7eoZd384gBMDA?e=1vWH3v&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 
* Entrevista 2: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202018894_upc_edu_pe/EddQn8WabOhChWfh2viP_c8BR0u5fm4qwyeLOcOZLOEE1g?e=uzQA3P&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 
* Entrevista 3: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201921734_upc_edu_pe/EXHEG_PwxKBMo-Saj7qtUhMBvdCQxVidwivN3u5SeOohaQ?e=hi2ysX 
