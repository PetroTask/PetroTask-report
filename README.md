# Informe del Trabajo Final

<div>
  <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC" width="150px" /></p>
  <p align="center"><b>Informe de Trabajo Final</b></p>
  <p align="center">Facultad de Ingeniería</p>
  <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
  <p align="center">Ingeniería de Software</p>
  <p align="center">Desarrollo de Aplicaciones Open Source - 1ASI0729</p>
  <p align="center">NRC: 7349</p>
  <p align="center">Efraín Ricardo Bautista Ubillús</p>
  <p align="center">Startup: PetroTask</p>
  <p align="center">Producto: TaskOil</p>
</div>

---

## Team members:

| **Nombre**                       | **Código** |
| ---------------------------------|------------|
| Baldeón Vivar, Santiago Armando  | U202319881 |
| Oskar Rodrigo Sosa Soto          | U202212214 |
| Rodrigo Fabrizio Aguilar Untiveros  | U202318309 |
| Santiago Valentino Solis Chang   | U20231B475 |
| Johan Giovani Huamán Cuba        | u202417448 |


<div>
  <p align="center"><b>Ciclo 2025 - 20</b></p>
</div>

---
# Contenido

1. __[Capítulo I: Introducción](#1-capítulo-i-introducción)__  
&nbsp;&nbsp;&nbsp;&nbsp;1.1. [Startup Profile](#11-startup-profile)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.1. [Descripción del startup](#111-descripción-del-startup)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2. [Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)  
&nbsp;&nbsp;&nbsp;&nbsp;1.2. [Solution Profile](#12-solution-profile)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.1. [Antecedentes y Problemática](#121-antecedentes-y-problemática)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2. [Lean UX Process](#122-lean-ux-process)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.1. [Lean UX Problem Statement](#1221-lean-ux-problem-statement)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)  
&nbsp;&nbsp;&nbsp;&nbsp;1.3. [Segmentos objetivos](#13-segmentos-objetivos)

2. __[Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)__  
&nbsp;&nbsp;&nbsp;&nbsp;2.1. [Competidores](#21-competidores)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.1. [Análisis competitivo](#211-análisis-competitivo)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
&nbsp;&nbsp;&nbsp;&nbsp;2.2. [Entrevistas](#22-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;2.3. [Needfinding](#23-needfinding)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.1. [User Personas](#231-user-personas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.2. [User Task Matrix](#232-user-task-matrix)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.3. [User Journey Mapping](#233-user-journey-mapping)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.4. [Empathy Mapping](#234-empathy-mapping)  
&nbsp;&nbsp;&nbsp;&nbsp;2.4. [Big Picture Event Storming](#24-big-picture-event-storming)  
&nbsp;&nbsp;&nbsp;&nbsp;2.5. [Ubiquitous Language](#25-ubiquitous-language)  

3. __[Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)__  
&nbsp;&nbsp;&nbsp;&nbsp;3.1. [User Stories](#31-user-stories)  
&nbsp;&nbsp;&nbsp;&nbsp;3.2. [Impact Mapping](#32-impact-mapping)  
&nbsp;&nbsp;&nbsp;&nbsp;3.3. [Product Backlog](#33-product-backlog)  

4. __[Capítulo IV: Product Design](#4-capítulo-iv-product-design)__  
&nbsp;&nbsp;&nbsp;&nbsp;4.1. [Style Guidelines](#41-style-guidelines)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.1. [General Style Guidelines](#411-general-style-guidelines)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.1.2. [Web Style Guidelines](#412-web-style-guidelines)  
&nbsp;&nbsp;&nbsp;&nbsp;4.2. [Information Architecture](#42-information-architecture)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.1. [Organization Systems](#421-organization-systems)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.2. [Labeling Systems](#422-labeling-systems)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.4. [Searching Systems](#424-searching-systems)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.2.5. [Navigation Systems](#425-navigation-systems)  
&nbsp;&nbsp;&nbsp;&nbsp;4.3. [Landing Page UI Design](#43-landing-page-ui-design)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)  
&nbsp;&nbsp;&nbsp;&nbsp;4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)  
&nbsp;&nbsp;&nbsp;&nbsp;4.5. [Web Applications Prototyping](#45-web-applications-prototyping)  
&nbsp;&nbsp;&nbsp;&nbsp;4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.1. [Design-Level Event Storming](#461-design-level-event-storming)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.2. [Software Architecture Context Diagram](#462-software-architecture-context-diagram)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.3. [Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.4. [Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)  
&nbsp;&nbsp;&nbsp;&nbsp;4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.1. [Class Diagrams](#471-class-diagrams)  
&nbsp;&nbsp;&nbsp;&nbsp;4.8. [Database Design](#48-database-design)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.8.1. [Database Diagrams](#481-database-diagrams)  

5. __[Capítulo V: Product Implementation, Validation & Deployment](#5-capítulo-v-product-implementation-validation--deployment)__  
&nbsp;&nbsp;&nbsp;&nbsp;5.1. [Software Configuration Management](#51-software-configuration-management)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.2. [Source Code Management](#512-source-code-management)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)  
&nbsp;&nbsp;&nbsp;&nbsp;5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1. [Sprint 1](#521-sprint-1)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2. [Sprint 2](#522-sprint-2)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.1. [Sprint Planning 2](#5221-sprint-planning-2)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.2. [Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.3. [Sprint Backlog 2](#5223-sprint-backlog-2)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.4. [Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.5. [Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.6. [Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.7. [Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.2.8. [Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3. [Sprint 3](#523-sprint-3)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.1. [Sprint Planning 3](#5231-sprint-planning-3)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.2. [Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.3. [Sprint Backlog 3](#5233-sprint-backlog-3)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.4. [Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.5. [Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.6. [Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.7. [Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.2.3.8. [Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)  
&nbsp;&nbsp;&nbsp;&nbsp;5.3. [Validation Interviews](#53-validation-interviews)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.1. [Diseño de Entrevistas](#531-diseño-de-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.2. [Registro de Entrevistas](#532-registro-de-entrevistas)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.3. [Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  
&nbsp;&nbsp;&nbsp;&nbsp;5.4. [Video About-the-Product](#54-video-about-the-product)  

6. __[Conclusiones](#6-conclusiones)__  
&nbsp;&nbsp;&nbsp;&nbsp;6.1. [Conclusiones y recomendaciones](#61-conclusiones-y-recomendaciones)  
&nbsp;&nbsp;&nbsp;&nbsp;6.2. [Video About-the-Team](#62-video-about-the-team)  

7. __[Bibliografía](#7-bibliografía)__  

8. __[Anexos](#8-anexos)__

# 1. Capítulo I: Introducción  

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup  

PetroTask tiene como objetivo transformar digitalmente la planificación, ejecución y supervisión de operaciones de campo en la industria petrolera, abarcando actividades como extracción, transporte, almacenamiento y mantenimiento en zonas operativas remotas. A través de su plataforma principal, PetroTask permite a las empresas petroleras organizar de forma centralizada las tareas críticas, asignar personal y equipos de manera eficiente, y supervisar la ejecución operativa en tiempo real, incluso ante condiciones cambiantes del entorno.

La solución busca resolver la falta de trazabilidad, coordinación y control en entornos donde las operaciones petroleras deben adaptarse constantemente a factores como el clima, el estado del equipo o la disponibilidad del personal. Para ello, PetroTask integra funcionalidades de reprogramación dinámica de tareas, registro de evidencias fotográficas, emisión de alertas automáticas y almacenamiento seguro de datos para análisis posterior.

Una de las principales fortalezas del sistema es su capacidad para adaptarse a la realidad de las operaciones petroleras: contempla la ejecución en entornos con conectividad limitada, la sincronización de datos cuando la red está disponible, y dashboards especializados que reflejan el avance, desempeño y cumplimiento de tareas en tiempo real. Esta solución aporta un valor diferencial tanto para los supervisores que planifican como para el personal que ejecuta tareas en terreno.

Misión: Optimizar la planificación, ejecución y trazabilidad de actividades de campo en la industria petrolera mediante una plataforma inteligente, segura y adaptable a entornos operativos remotos.
Visión: PetroTask aspira a convertirse en el aliado tecnológico preferido por empresas petroleras en Latinoamérica, facilitando operaciones más eficientes, seguras y trazables a través de la innovación digital aplicada al sector energético.


### 1.1.2. Perfiles de los integrantes del equipo



## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### 1.2.1.1. What

__¿Cuál es el problema?__

El problema puede ser mencionado como la falta de un recurso tecnológico capaz de organizar, planificar y supervisar las operaciones críticas en campo dentro de empresas petroleras. Actualmente, la ausencia de un sistema centralizado que permita coordinar y monitorear las tareas provoca **descoordinación**, **errores operativos**, **pérdidas de tiempo**, **aumento de costos** y **riesgos de seguridad** tanto para el personal como para el entorno. Esto genera impactos negativos en la eficiencia, la productividad y la capacidad de respuesta ante incidentes.

#### 1.2.1.2. Who

__¿Quiénes están involucrados en el problema?__

Este problema involucra principalmente a **supervisores y planificadores de campo**, encargados de distribuir tareas y asignar recursos de manera eficiente; a **operarios y técnicos**, responsables de ejecutar las actividades y reportar incidencias en el terreno; y a **personal administrativo y gerencial**, que requiere información confiable y actualizada para la toma de decisiones estratégicas y operativas. La falta de integración y visibilidad entre estos actores genera cuellos de botella que afectan directamente la continuidad de las operaciones petroleras.

#### 1.2.1.3. Where

__¿Dónde surge el problema?__

El problema surge en **plataformas de perforación, campos de extracción, estaciones de bombeo y plantas de procesamiento**, donde la ejecución de tareas requiere un alto nivel de coordinación y control. También se presenta en las **oficinas de control y centros administrativos**, donde la falta de visibilidad en tiempo real sobre el estado de las operaciones limita la capacidad de reacción ante imprevistos, como fallas de equipo, cambios climáticos o emergencias operativas.

#### 1.2.1.4. When

__¿Cuándo se presenta el problema?__

El problema inicia desde la **planificación inicial de las operaciones** y se intensifica durante la ejecución en campo, cuando los supervisores no cuentan con información actualizada para tomar decisiones rápidas. Persiste hasta la etapa de **verificación y cierre de tareas**, especialmente en situaciones donde se presentan **cambios inesperados o emergencias** que requieren reprogramar actividades, reasignar recursos o emitir alertas inmediatas.

#### 1.2.1.5. Why

__¿Por qué surge el problema?__

La causa principal radica en la **desorganización y fragmentación de la comunicación** entre los diferentes equipos de trabajo, sumada a la **ausencia de herramientas digitales especializadas** para la industria petrolera que permitan un control integral, trazable y en tiempo real de todas las operaciones. La dependencia de procesos manuales o herramientas genéricas provoca que la información se pierda, se registre de manera incompleta o no esté disponible en el momento necesario.

#### 1.2.1.6. How

__¿Cómo se utilizará el producto?__

**PetroTask** se utilizará como una **plataforma web y móvil** diseñada para que supervisores, técnicos y operarios puedan:
- **Planificar y coordinar tareas** críticas en campo.
- **Registrar evidencias** mediante fotografías y reportes de avance.
- **Recibir alertas automáticas** de seguridad y fallas de equipos.
- **Reprogramar actividades** en tiempo real ante imprevistos.
- **Acceder a un historial digital** con trazabilidad completa de cada operación.

La plataforma funcionará en entornos con conectividad limitada, permitiendo la carga y sincronización de datos una vez restablecida la conexión.

#### 1.2.1.7. How much

__¿Cuál es la magnitud del problema?__

Según datos de la **Sociedad Nacional de Minería, Petróleo y Energía (2024)**, un **35% de las paradas no programadas** en operaciones petroleras se deben a **fallos de coordinación y supervisión**. Estas interrupciones generan **pérdidas económicas millonarias**, impactan negativamente en la productividad y aumentan los **riesgos de seguridad** para el personal y el medio ambiente. Este panorama evidencia la necesidad urgente de contar con **herramientas digitales adaptadas al sector petrolero** que optimicen la comunicación, la trazabilidad y la eficiencia de las operaciones.


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statement

El propósito de PetroTask es crear un sistema de gestión de operaciones de campo diseñado específicamente para la industria petrolera, capaz de planificar, coordinar y supervisar tareas críticas de manera eficiente, segura y trazable, desde la etapa de extracción hasta el almacenamiento y transporte.
Nuestra solución busca ofrecer una interfaz clara e intuitiva que permita a supervisores, técnicos y operarios interactuar en un mismo entorno digital, de manera que la información registrada por un rol sea útil y procesable para los demás. El sistema estará optimizado para entornos con conectividad limitada, permitiendo el trabajo offline y la sincronización automática de datos cuando la conexión se restablezca, lo que resulta clave en zonas remotas como plataformas petroleras, campos de extracción y plantas de procesamiento.
PetroTask integrará herramientas de alertas automáticas ante riesgos de seguridad o fallas en los equipos, así como funciones para reprogramar actividades en tiempo real frente a imprevistos como cambios climáticos, indisponibilidad de recursos o incidentes en campo. Además, contará con un módulo de registro de evidencias fotográficas y seguimiento de cumplimiento para mantener un historial digital auditado de cada operación.
Hemos identificado que las empresas petroleras enfrentan pérdidas significativas de tiempo, recursos y oportunidades debido a la descoordinación interna y la falta de trazabilidad en la ejecución de tareas. Esto no solo impacta en la productividad, sino que también eleva el riesgo de incidentes operativos y disminuye la capacidad de respuesta ante emergencias.
De esta forma, es evidente que se necesita una herramienta tecnológica especializada en la gestión de operaciones petroleras, que unifique la comunicación entre áreas, mejore el control de actividades y optimice la toma de decisiones en tiempo real.
¿Cómo podemos implementar una plataforma digital que centralice la planificación, ejecución y monitoreo de tareas petroleras, incluso en entornos sin conexión, para mejorar la coordinación, reducir los riesgos y aumentar la eficiencia operativa?


#### 1.2.2.2. Lean UX Assumptions

__Business Assumptions:__

- __Creemos que nuestros usuarios necesitan__ una solución digital que centralice la planificación, ejecución y seguimiento de operaciones petroleras, eliminando procesos manuales y reduciendo los errores humanos.
- __Estas necesidades pueden satisfacerse__ mediante una plataforma web y móvil que permita registrar tareas, asignar recursos, recibir alertas automáticas y reprogramar actividades en tiempo real, incluso sin conexión a internet.
- __Nuestros clientes iniciales serán__ empresas operadoras de petróleo, contratistas de servicios petroleros y empresas de mantenimiento industrial que trabajan en campos de extracción, transporte y procesamiento.
- __El valor más importante que un cliente espera de nuestros servicios es__ la reducción de tiempos muertos, el aumento de la seguridad operativa y la trazabilidad completa de cada tarea.
- __Vamos a obtener la mayoría de nuestros clientes mediante__ alianzas con proveedores del sector, demostraciones piloto en campos petroleros, ferias industriales y campañas de marketing digital especializadas en B2B energético.
- __Vamos a obtener ingresos mediante__ suscripciones mensuales o anuales bajo el modelo SaaS escalable, con planes ajustados según el número de usuarios, ubicaciones y módulos contratados.
- __Nuestra competencia en el mercado será__ software de gestión genérico, herramientas no adaptadas a la industria petrolera o sistemas costosos con poca flexibilidad para entornos remotos.
- __Vamos a tener ventaja frente a nuestra competencia debido a__ la adaptación al contexto petrolero, la compatibilidad con IoT y sensores industriales, y la facilidad de uso en condiciones adversas.
- __El mayor riesgo del servicio es__ que el personal de campo no registre las actividades de forma consistente o que la empresa no adopte el sistema como parte de su flujo de trabajo.
- __Lo resolveremos ofreciendo__ una interfaz intuitiva, capacitación enfocada en procesos reales del sector y un soporte técnico disponible 24/7, además de realizar pilotos con iteración constante para asegurar la adopción.


__User Assumptions:__

__¿Quién es el usuario?__

Los usuarios principales son **supervisores, planificadores, técnicos y operarios** que participan en operaciones petroleras, así como **personal administrativo y gerencial** encargado de la toma de decisiones. Estos usuarios intervienen en distintas etapas del ciclo operativo, desde la planificación de tareas hasta su verificación y cierre, necesitando herramientas que les permitan coordinarse y actuar con rapidez.

__¿Qué problemas busca resolver el producto?__

La **falta de control y trazabilidad** de las tareas críticas, la **descoordinación entre equipos**, la **dificultad para reprogramar actividades** ante imprevistos y la **ausencia de reportes confiables** para la gestión operativa y la toma de decisiones estratégicas.

__¿Qué funcionalidades son importantes?__

**PetroTask** permitirá:
- Planificar tareas y asignar recursos humanos y materiales.
- Recibir alertas automáticas por incidencias o riesgos detectados.
- Reprogramar actividades en tiempo real ante cambios o emergencias.
- Registrar evidencias fotográficas para documentar el avance de las tareas.
- Generar reportes analíticos que faciliten la toma de decisiones.

__¿Dónde encaja nuestro producto en su trabajo o vida?__

En el **flujo operativo diario de las operaciones petroleras**: desde la preparación de trabajos, el control y supervisión en campo, el registro de avances, hasta la verificación y cierre de actividades.

__¿Cuándo y cómo es nuestro producto usado?__

Durante cada punto crítico de la operación, por múltiples usuarios de manera simultánea, accediendo desde **celulares, tablets o dashboards de oficina**, garantizando la actualización en tiempo real.

__¿Cómo debe verse nuestro producto y cómo debe comportarse?__

Debe tener una **interfaz intuitiva, modular y responsiva**, con **indicadores visuales claros**, alertas priorizadas según la criticidad del evento, carga automática de datos desde sensores y herramientas de validación **rápidas y confiables**.

#### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 01

**Creemos** que los supervisores y planificadores adoptarán el sistema si pueden asignar y reprogramar tareas en tiempo real, incluso en entornos sin conexión.  
**Sabremos** que hemos tenido éxito  
**cuando** al menos el 80% de las asignaciones y reprogramaciones durante la fase piloto se realicen a través de la plataforma PetroTask.  

Hypothesis Statement 02

**Creemos** que permitir que los operarios de campo registren incidencias y evidencias fotográficas directamente desde sus dispositivos móviles mejorará la calidad de los reportes.  
**Sabremos** que hemos tenido éxito  
**cuando** el 70% de los reportes contengan evidencias visuales válidas dentro de los primeros tres meses de uso.  

Hypothesis Statement 03

**Creemos** que implementar alertas automáticas de seguridad reducirá la cantidad de incidentes operativos y permitirá actuar con mayor rapidez ante riesgos.  
**Sabremos** que hemos tenido éxito  
**cuando** se observe una reducción del 30% en incidentes reportados y una disminución del 40% en el tiempo de respuesta frente a emergencias durante los primeros seis meses.  

Hypothesis Statement 04

**Creemos** que un dashboard de trazabilidad en tiempo real, con indicadores clave de avance y rendimiento, mejorará la coordinación entre áreas.  
**Sabremos** que hemos tenido éxito  
**cuando** al menos el 75% de los supervisores utilicen el dashboard de forma semanal para tomar decisiones operativas.  

Hypothesis Statement 05

**Creemos** que permitir la planificación visual de recursos (personal, equipos y materiales) optimizará la asignación y reducirá el tiempo improductivo.  
**Sabremos** que hemos tenido éxito  
**cuando** se logre una reducción del 20% en tiempos muertos y un 15% de incremento en la eficiencia operativa en el periodo de prueba.  

Hypothesis Statement 06

**Creemos** que integrar funcionalidades offline con sincronización automática aumentará el uso continuo del sistema en zonas remotas.  
**Sabremos** que hemos tenido éxito  
**cuando** más del 60% de las operaciones registradas offline se sincronicen exitosamente y sean utilizadas en la toma de decisiones sin pérdida de información.  

Hypothesis Statement 07

**Creemos** que un historial digital de operaciones, con registro de responsables, tiempos y evidencias, facilitará auditorías y verificaciones internas.  
**Sabremos** que hemos tenido éxito  
**cuando** el 70% de las auditorías internas utilicen exclusivamente los datos generados por PetroTask como fuente principal.  

Hypothesis Statement 08

**Creemos** que incluir reportes analíticos personalizables permitirá a la gerencia identificar tendencias y áreas de mejora de forma más efectiva.  
**Sabremos** que hemos tenido éxito  
**cuando** al menos el 75% de los reportes solicitados por gerencia se generen directamente desde la plataforma PetroTask sin necesidad de herramientas externas.  

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas es una herramienta que nos ha permitido identificar y analizar a nuestros potenciales usuarios junto con sus principales necesidades. Se emplea dentro del enfoque de diseño centrado en el usuario y la metodología Lean, con el objetivo de crear productos de manera ágil, efectiva y orientada al valor real que reciben los usuarios. Además, facilita el trabajo conjunto de equipos multidisciplinarios, ya que proporciona un marco estructurado que fomenta la colaboración y la alineación de ideas durante todo el proceso de desarrollo.

<div>
  <p align="center"><img src="assets/md-images/canvas-open-new.png" alt="Canvas" width="700px" /></p>
</div>

Enlace para acceder al [Canvas](https://www.canva.com/design/DAGjpb8uvJA/kFkhcvG5a6BCtdU2xvq5gw/edit?utm_content=DAGjpb8uvJA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## 1.3. Segmentos Objetivos

#### Segmento objetivo #1: Supervisores y Planificadores de Campo (Sector Petrolero)

__Descripción General__

Mandos intermedios encargados de planificar, asignar y supervisar operaciones petroleras en terreno. Este segmento incluye a jefaturas y coordinadores que gestionan el uso de personal, equipos y recursos para cumplir con los objetivos operativos, garantizando seguridad y eficiencia en cada tarea.

__Perfil Demográfico__

- Edad: 30 a 55 años  
- Experiencia: técnica-operativa en el sector petrolero, con alta responsabilidad en la coordinación de equipos  
- Ubicación: regiones con actividad petrolera (como Loreto, Piura, Tumbes, Ucayali)  
- Nivel digital: medio; familiarizados con hojas de cálculo, radio-comunicación, GPS y sistemas de gestión básicos

__Datos del Sector__

De acuerdo con reportes del sector energético en Latinoamérica, las operaciones petroleras requieren una coordinación precisa entre áreas para evitar retrasos y riesgos de seguridad. Las condiciones adversas del entorno, la infraestructura limitada y la necesidad de cumplir estándares internacionales de seguridad impulsan la adopción de soluciones tecnológicas adaptadas a entornos remotos.

__Necesidad__

Automatizar la planificación, trazabilidad y reprogramación de tareas críticas, permitiendo a los supervisores responder con agilidad ante imprevistos y generar reportes confiables para la toma de decisiones.

---

#### Segmento objetivo #2: Operarios de Campo / Técnicos Petroleros

__Descripción General__

Trabajadores encargados de ejecutar actividades operativas en plataformas, campos y plantas petroleras. Son responsables de llevar a cabo tareas de extracción, mantenimiento, transporte y control, así como de registrar avances, incidencias y condiciones del entorno de trabajo.

__Perfil Demográfico__

- Edad: 20 a 50 años  
- Formación: técnica o empírica relacionada con operaciones de campo en el sector petrolero  
- Herramientas: teléfonos móviles, radios, tablets (ocasionalmente)  
- Nivel digital: bajo a medio; priorizan sistemas simples, rápidos y fáciles de usar

__Datos del Sector__

El personal de campo en la industria petrolera enfrenta condiciones ambientales exigentes y, en muchas ocasiones, limitaciones de conectividad. La adopción de herramientas móviles que funcionen sin conexión y permitan registrar información en tiempo real es clave para garantizar la trazabilidad y la seguridad de las operaciones.

__Necesidad__

Contar con una herramienta que facilite la consulta de tareas, el registro de datos reales (como hora de ejecución, cambios de recursos o incidencias) y la recepción de alertas rápidas, incluso en entornos sin conectividad.

# 2. Capítulo II: Requirements Elicitation & Analysis  

## 2.1. Competidores  

### 2.1.1. Análisis competitivo  
### 2.1.2. Estrategias y tácticas frente a competidores  

## 2.2. Entrevistas  

### 2.2.1. Diseño de entrevistas  
### 2.2.2. Registro de entrevistas  
### 2.2.3. Análisis de entrevistas  

## 2.3. Needfinding  

### 2.3.1. User Personas  
### 2.3.2. User Task Matrix  
### 2.3.3. User Journey Mapping  
### 2.3.4. Empathy Mapping  

## 2.4. Big Picture Event Storming  
## 2.5. Ubiquitous Language  


# 3. Capítulo III: Requirements Specification  

## 3.1. User Stories  
## 3.2. Impact Mapping  
## 3.3. Product Backlog  


# 4. Capítulo IV: Product Design  

## 4.1. Style Guidelines  

### 4.1.1. General Style Guidelines  
### 4.1.2. Web Style Guidelines  

## 4.2. Information Architecture  

### 4.2.1. Organization Systems  
### 4.2.2. Labeling Systems  
### 4.2.3. SEO Tags and Meta Tags  
### 4.2.4. Searching Systems  
### 4.2.5. Navigation Systems  

## 4.3. Landing Page UI Design  

### 4.3.1. Landing Page Wireframe  
### 4.3.2. Landing Page Mock-up  

## 4.4. Web Applications UX/UI Design  

### 4.4.1. Web Applications Wireframes  
### 4.4.2. Web Applications Wireflow Diagrams  
### 4.4.3. Web Applications Mock-ups  
### 4.4.4. Web Applications User Flow Diagrams  

## 4.5. Web Applications Prototyping  

## 4.6. Domain-Driven Software Architecture  

### 4.6.1. Design-Level Event Storming  
### 4.6.2. Software Architecture Context Diagram  
### 4.6.3. Software Architecture Container Diagrams  
### 4.6.4. Software Architecture Components Diagrams  

## 4.7. Software Object-Oriented Design  

### 4.7.1. Class Diagrams  

## 4.8. Database Design  

### 4.8.1. Database Diagrams  


# 5. Capítulo V: Product Implementation, Validation & Deployment  

## 5.1. Software Configuration Management  

### 5.1.1. Software Development Environment Configuration  
### 5.1.2. Source Code Management  
### 5.1.3. Source Code Style Guide & Conventions  
### 5.1.4. Software Deployment Configuration  

## 5.2. Landing Page, Services & Applications Implementation  

### 5.2.X. Sprint n  

#### 5.2.X.1. Sprint Planning n  
#### 5.2.X.2. Aspect Leaders and Collaborators  
#### 5.2.X.3. Sprint Backlog n  
#### 5.2.X.4. Development Evidence for Sprint Review  
#### 5.2.X.5. Execution Evidence for Sprint Review  
#### 5.2.X.6. Services Documentation Evidence for Sprint Review  
#### 5.2.X.7. Software Deployment Evidence for Sprint Review  
#### 5.2.X.8. Team Collaboration Insights during Sprint  

## 5.3. Validation Interviews  

### 5.3.1. Diseño de Entrevistas  
### 5.3.2. Registro de Entrevistas  
### 5.3.3. Evaluaciones según heurísticas  

## 5.4. Video About-the-Product  


# Conclusiones  

## Conclusiones y recomendaciones  
## Video About-the-Team  

# Bibliografía  
# Anexos  
