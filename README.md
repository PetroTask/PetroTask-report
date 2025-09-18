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



## Epics

| Epic/User Story ID | Título | Descripción | Criterios de aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| EP01 | Contacto | Como visitante de la landing page, quiero comunicarme con el equipo de desarrollo de la aplicación TrackLab para enviar mis comentarios y realizar consultas sobre su producto. | No corresponde | No corresponde |
| EP02 | Desarrollo de la landing page | Como visitante del sitio, quiero navegar una landing page clara, informativa y visualmente atractiva que me brinde acceso a las funcionalidades clave, preguntas frecuentes y formas de contacto, para entender mejor el valor de SwiftPort. | No corresponde | No corresponde |
| EP03 | Conectar la landing page con la aplicación | Como visitante de la landing page, quiero navegar hacia diferentes secciones de la aplicación a través de componentes interactivos, para acceder a las funciones y beneficios que ofrece TrackLab. | No corresponde | No corresponde |
| EP04 | Registro y Creación de Tareas | Como supervisor logístico, quiero crear y registrar tareas asignadas a los responsables del proceso para organizar la ejecución diaria de las operaciones. | No corresponde | No corresponde |
| EP05 | Seguimiento de Actividades | Como supervisor logístico, quiero hacer seguimiento del avance de cada tarea para identificar bloqueos, demoras y condiciones externas que puedan afectar su cumplimiento. | No corresponde | No corresponde |
| EP06 | Alertas y Notificaciones | Como trabajador de la empresa, quiero recibir notificaciones sobre asignaciones, cambios o bloqueos de tareas para mantenerme informado y actuar a tiempo. | No corresponde | No corresponde |
| EP07 | Validación y Control de Actividades | Como supervisor logístico, quiero validar el cumplimiento de las tareas ejecutadas o suspendidas para asegurar su correcta ejecución y documentar causas de no cumplimiento. | No corresponde | No corresponde |
| EP08 | Visualización y Tableros de Control | Como Supervisor logístico, quiero visualizar el estado general de tareas y procesos en dashboards para tomar decisiones basadas en datos actualizados. | No corresponde | No corresponde |
| EP09 | Integración con Sistemas Externos | Como operario, quiero integrar datos relevantes del clima, tránsito u otros sistemas para anticipar retrasos o problemas logísticos. | No corresponde | No corresponde |
| EP10 | Gestión de Usuarios y Roles | Como Supervisor logístico, quiero gestionar los usuarios y sus permisos según sus roles para garantizar un acceso seguro y adecuado a las funcionalidades del sistema. | No corresponde | No corresponde |
| EP11 | Planeamiento Diario de Operaciones | Como Supervisor logístico, quiero generar el plan diario de actividades considerando restricciones y recursos disponibles para optimizar el cumplimiento de las tareas. | No corresponde | No corresponde |

## User Stories (US)

| Epic/User Story ID | Título | Descripción | Criterios de aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| US01 | Contactar al startup | Como visitante de la landing page, quiero contar con un medio para escribirle al equipo de desarrolladores, para compartir mis comentarios y sugerencias sobre la aplicación. | **Escenario 1: Acceder al formulario para enviar sugerencias**<br>DADO que el visitante ha accedido al landing page<br>CUANDO el visitante selecciona la opción “Enviar sugerencia”<br>ENTONCES el sistema debe desplegar un formulario breve para completar<br><br>**Escenario 2: Enviar una sugerencia al equipo de desarrollo**<br>DADO que el visitante está dentro del formulario de sugerencias<br>CUANDO el visitante redacta su mensaje<br>Y el visitante presiona el botón “Enviar”<br>ENTONCES el sistema debe remitir el contenido del mensaje al correo del equipo de desarrolladores | EP01 |
| US02 | Obtener información sobre el uso de la aplicación | Como visitante de la landing page, quiero contar con un espacio donde pueda conocer las funcionalidades y beneficios de la aplicación, para utilizarlos fácilmente cuando los necesite. | **Escenario 1: Acceder a la sección de información sobre la aplicación**<br>DADO que el visitante ha accedido al landing page<br>CUANDO el visitante selecciona el ícono con el signo de interrogación<br>ENTONCES el sistema debe redirigirlo a una pantalla donde se detallan las funcionalidades y beneficios de la aplicación<br><br>**Escenario 2: Acceder a la sección de preguntas frecuentes**<br>DADO que el visitante ha ingresado al landing page<br>CUANDO el visitante selecciona la opción “Preguntas Frecuentes”<br>ENTONCES el sistema debe mostrar una lista de preguntas y respuestas | EP02 |
| US03 | Acceder a la aplicación desde el landing page | Como visitante de la landing page, quiero ingresar a la aplicación desde la landing page para acceder fácilmente a las funcionalidades de la aplicación. | **Escenario 1: Ingreso exitoso**<br>DADO que el visitante ha ingresado al landing page<br>CUANDO el visitante selecciona la opción “Iniciar sesión”<br>Y el visitante ingrese correctamente su usuario y contraseña<br>ENTONCES el sistema redirigirá al usuario a su cuenta dentro de la aplicación<br><br>**Escenario 2: Error en el ingreso**<br>DADO que el usuario ha ingresado al landing page<br>CUANDO el visitante seleccione la opción “Iniciar sesión”<br>Y el visitante ingrese su usuario o su contraseña incorrectamente<br>ENTONCES el sistema mostrará el mensaje “Datos ingresados incorrectamente, favor de reintentar” | EP03 |
| US04 | Crear una nueva tarea | Como supervisor logístico, quiero crear tareas logísticas para planificar los procesos de envío. | **Escenario 1: Crear una tarea con datos completos**<br>DADO que el supervisor logístico tiene acceso al módulo de planificación de tareas<br>Y que el supervisor cuenta con los campos necesarios para el registro<br>CUANDO ingresa la descripción, la fecha, la fase y asigna un responsable<br>Y presiona el botón “Guardar”<br>ENTONCES el sistema debe crear la nueva tarea<br>Y mostrarla en la lista de planificación diaria<br><br>**Escenario 2: Intentar crear tarea sin completar campos obligatorios**<br>DADO que el supervisor intenta registrar una tarea<br>CUANDO deja vacía la descripción o la fecha<br>Y trata de guardarla<br>ENTONCES el sistema debe mostrar un mensaje de error<br>Y resaltar los campos faltantes<br><br>**Escenario 3: Crear varias tareas consecutivas**<br>DADO que el supervisor se encuentra en el módulo de tareas<br>CUANDO crea una tarea<br>Y selecciona la opción “crear otra”<br>ENTONCES el sistema guarda la tarea actual<br>Y muestra un nuevo formulario en blanco<br><br>**Escenario 4: Crear tarea programada a futuro**<br>DADO que el supervisor desea planificar tareas futuras<br>CUANDO selecciona una fecha posterior a la actual<br>ENTONCES el sistema debe guardarla<br>Y marcarla como “programada”<br><br>**Escenario 5: Cancelar la creación de una tarea**<br>DADO que el supervisor ha iniciado el registro de una nueva tarea<br>CUANDO presiona el botón “Cancelar”<br>ENTONCES el sistema debe descartar los datos ingresados<br>Y regresar a la lista principal sin guardar información | EP04 |
| US05 | Asignar tarea a un responsable | Como supervisor logístico, quiero asignar responsables a tareas para distribuir el trabajo adecuadamente. | **Escenario 1: Asignar responsable disponible a una tarea**<br>DADO que hay una tarea pendiente sin responsable<br>CUANDO el supervisor selecciona un operario disponible<br>ENTONCES el sistema debe asignarlo<br>Y actualizar su estado a “Asignada”<br><br>**Escenario 2: Intentar asignar tarea a operario no disponible**<br>DADO que el supervisor selecciona un operario que ya tiene una tarea en el mismo horario<br>CUANDO intenta asignarle otra<br>ENTONCES el sistema debe mostrar una advertencia de conflicto de horario<br>Y evitar la asignación<br><br>**Escenario 3: Reasignar tarea a otro responsable**<br>DADO que hay una tarea con un responsable asignado<br>CUANDO el supervisor selecciona otro operario para reemplazarlo<br>ENTONCES el sistema actualiza la asignación<br>Y notifica al nuevo responsable<br><br>**Escenario 4: Ver lista filtrada de operarios por turno y zona**<br>DADO que se asigna una tarea para el turno mañana y zona norte<br>CUANDO el supervisor aplica los filtros<br>ENTONCES el sistema muestra solo los operarios que cumplen los criterios<br><br>**Escenario 5: Cancelar asignación antes de guardar**<br>DADO que se ha iniciado la asignación<br>CUANDO el supervisor presiona “Cancelar” antes de confirmar<br>ENTONCES el sistema debe descartar la acción<br>Y dejar la tarea sin cambios | EP04 |
| US06 | Establecer prioridad y riesgo externo | Como supervisor logístico, quiero agregar comentarios a una tarea para que esta contenga especificaciones en cuanto a su desarrollo. | **Escenario 1: Ingresar comentario a una tarea**<br>DADO que el supervisor se encuentra creando una nueva tarea<br>CUANDO ingresa texto en el recuadro de comentarios<br>ENTONCES el sistema registra el comentario en la tarea<br><br>**Escenario 2: Visualizar comentarios de tarea**<br>DADO que el supervisor está visualizando la lista de tareas<br>CUANDO el supervisor se acerque a una tarea<br>ENTONCES el supervisor verá los comentarios registrados | EP04 |
| US07 | Cambiar estado de tarea | Como operario, quiero actualizar el estado de una tarea para reflejar si está en proceso, finalizada o bloqueada. | **Escenario 1: Cambiar estado de tarea a “En Proceso”**<br>DADO que el operario se encuentra ejecutando una tarea<br>CUANDO cambia el estado a “En Proceso”<br>ENTONCES el sistema registra el nuevo estado<br>Y lo muestra en el panel del supervisor<br><br>**Escenario 2: Marcar tarea como “Finalizada”**<br>DADO que el operario ha completado una tarea<br>CUANDO selecciona la opción “Finalizada”<br>ENTONCES el sistema actualiza el estado<br>Y registra la hora de finalización<br><br>**Escenario 3: Bloquear tarea por causa externa**<br>DADO que el operario no puede continuar por una protesta<br>CUANDO marca la tarea como “Bloqueada” y selecciona el motivo<br>ENTONCES el sistema registra el estado como bloqueado<br>Y genera una alerta al supervisor<br><br>**Escenario 4: Evitar cambio de estado sin motivo**<br>DADO que el operario intenta marcar como “Bloqueada”<br>CUANDO no selecciona una causa<br>ENTONCES el sistema impide el cambio<br>Y solicita seleccionar un motivo<br><br>**Escenario 5: Corregir estado marcado por error**<br>DADO que el operario ha marcado erróneamente el estado<br>CUANDO intenta corregirlo dentro de 5 minutos<br>ENTONCES el sistema permite la edición<br>Y guarda el historial del cambio | EP05 |
| US08 | Ver tareas asignadas | Como operario, quiero ver todas las tareas que tengo pendientes con sus fechas y estado para poder gestionarlas adecuadamente. | **Escenario 1: Ver listado de tareas pendientes**<br>DADO que el operario accede al sistema<br>CUANDO ingresa al módulo “Mis Tareas”<br>ENTONCES el sistema muestra la lista de tareas asignadas<br>Y cada una incluye fecha y estado<br><br>**Escenario 2: Actualización en tiempo real de nuevas tareas**<br>DADO que el operario mantiene abierta su lista de tareas<br>CUANDO el supervisor le asigna una nueva tarea<br>ENTONCES el sistema actualiza la lista automáticamente<br>Y muestra la nueva asignación sin recargar la página | EP05 |
| US09 | Ingresar comentario a tarea | Como operario, quiero ingresar comentarios a las tareas que creo para que los demás puedan saber más de las mismas al verlas. | **Escenario 1: Ingresar comentario a una tarea**<br>DADO que el operario se encuentra creando una nueva tarea<br>CUANDO ingresa texto en el recuadro de comentarios<br>ENTONCES el sistema registra el comentario en la tarea<br><br>**Escenario 2: Visualizar comentarios de tarea**<br>DADO que el operario está visualizando la lista de tareas<br>CUANDO el operario se acerque a una tarea<br>ENTONCES el operario verá los comentarios registrados | EP05 |
| US10 | Agrupar tareas por fase | Como supervisor logístico, quiero ver las tareas agrupadas por fase para facilitar la ejecución. | **Escenario 1: Ver tareas agrupadas por fase en el panel principal**<br>DADO que el supervisor accede al panel de tareas<br>Y hay tareas con fases asignadas<br>CUANDO selecciona la opción “Agrupado por fase”<br>ENTONCES el sistema organiza las tareas según su fase<br><br>**Escenario 2: Expandir y contraer fases para visualizar tareas**<br>DADO que el supervisor está en la vista agrupada por fase<br>CUANDO presiona expandir sobre “Tareas de Entrega”<br>ENTONCES el sistema muestra las tareas de esa fase<br>Y permite contraerlas de nuevo<br><br>**Escenario 3: Visualizar tareas sin aplicar filtro**<br>DADO que el supervisor está en la vista agrupada por fase<br>CUANDO el supervisor no ha ingresado algún filtro<br>ENTONCES el sistema mostrará tareas de todas las fases | EP05 |
| US11 | Alerta por tarea bloqueada | Como supervisor logístico, quiero recibir una alerta cuando una tarea sea bloqueada para estar al tanto de la situación | **Escenario 1: Recibir alerta por bloqueo**<br>DADO que el supervisor gestiona tareas del sistema<br>Y un operario marca una tarea como bloqueada<br>CUANDO se actualiza el estado<br>ENTONCES el sistema genera una alerta inmediata<br>Y la envía a la bandeja de notificaciones del supervisor<br><br>**Escenario 2: No generar alerta si la tarea fue pausada voluntariamente**<br>DADO que una tarea fue reprogramada internamente<br>CUANDO se cambia su estado<br>ENTONCES el sistema no genera ninguna alerta<br><br>**Escenario 3: Recibir la alerta en la app web**<br>DADO que el supervisor tiene sesión iniciada en la web<br>CUANDO se bloquea una tarea por causas externas<br>ENTONCES el sistema envía una notificación<br>Y permite acceder al detalle del bloqueo | EP06 |
| US12 | Notificación de nueva tarea asignada | Como operario, quiero recibir notificación inmediata cuando se me asigne una nueva tarea. | **Escenario 1: Recibir notificación al ser asignado a una tarea**<br>DADO que el operario tiene sesión iniciada en el sistema<br>CUANDO un supervisor le asigna una nueva tarea<br>ENTONCES el sistema genera una notificación<br>Y la muestra de forma inmediata<br><br>**Escenario 2: Ver notificación con detalle de urgencia y fecha límite**<br>DADO que el operario recibe una nueva tarea prioritaria<br>CUANDO se genera la notificación<br>ENTONCES esta incluye la fecha límite y nivel de urgencia | EP06 |
| US13 | Cambiar estado de tarea | Como supervisor, quiero cambiar el estado de las tareas y registrar un comentario en cuanto al motivo del cambio para que exista un seguimiento. | **Escenario 1: Cambiar el estado de una tarea**<br>DADO que el supervisor observa una tarea con su estado<br>CUANDO selecciona la opción "Cambiar estado"<br>Y selecciona un nuevo estado<br>ENTONCES el sistema registra el nuevo estado<br><br>**Escenario 2: Ingresa un comentario**<br>DADO que el supervisor ha selecciona la opción "Guardar estado"<br>CUANDO el supervisor ingrese texto en la sección "Comentarios"<br>ENTONCES el sistema guardará el comentario<br>Y se registrarán ambos cambios | EP07 |
| US14 | Añadir observaciones a una tarea | Como operario, quiero dejar comentarios sobre problemas o incidencias al realizar una tarea. | **Escenario 1: Agregar observación durante la ejecución**<br>DADO que el operario está realizando una tarea<br>CUANDO detecta un inconveniente<br>Y accede al campo de observaciones<br>ENTONCES puede redactar y guardar un comentario asociado a la tarea<br><br>**Escenario 2: Registrar múltiples observaciones**<br>DADO que ya hay una observación previa<br>CUANDO el operario agrega una nueva entrada<br>ENTONCES el sistema guarda ambas en orden cronológico<br><br>**Escenario 3: Impedir observación vacía**<br>DADO que el operario intenta guardar sin contenido<br>CUANDO presiona “Guardar”<br>ENTONCES el sistema muestra un mensaje de error<br>Y bloquea el guardado hasta que se ingrese texto | EP07 |
| US15 | Reportar incidencias | Como operario, quiero reportar una incidencia durante la ejecución de una tarea para que sea atendida. | **Escenario 1: Reportar una incidencia con causa y descripción**<br>DADO que el operario está ejecutando una tarea y ocurre un inconveniente<br>CUANDO accede a la opción “Reportar incidencia”<br>Y selecciona la causa junto con una descripción<br>ENTONCES el sistema registra la incidencia<br>Y notifica al supervisor correspondiente<br><br>**Escenario 2: Evitar envío de incidencia sin causa seleccionada**<br>DADO que el operario intenta reportar una incidencia<br>CUANDO no marca la causa<br>ENTONCES el sistema bloquea el envío<br>Y muestra un mensaje indicando que el campo es obligatorio<br><br>**Escenario 3: Registrar la hora exacta de la incidencia**<br>DADO que el operario confirma el envío del reporte<br>CUANDO se guarda la incidencia<br>ENTONCES el sistema registra la fecha y hora automáticamente<br><br>**Escenario 4: Adjuntar evidencia al reporte**<br>DADO que el operario adjunta una foto relevante<br>CUANDO la sube desde su dispositivo<br>ENTONCES el sistema guarda la imagen con el reporte<br>Y la hace visible para el supervisor | EP08 |
| US16 | Programar entrega con condiciones | Como supervisor logístico, quiero registrar si una entrega posee ciertos requisitos para que estos se tengan en cuenta en su ejecución. | **Escenario 1: Supervisor crea nuevo incidente asociado a una entrega**<br>DADO que el supervisor está gestionando una entrega<br>CUANDO decide registrar un nuevo incidente<br>ENTONCES el sistema permite ingresar un nuevo incidente vinculado a esa entrega<br>Y lo asocia como una condición externa a considerar en su ejecución<br><br>**Escenario 2: Supervisor ingresa la severidad del incidente**<br>DADO que el supervisor está registrando un incidente<br>CUANDO selecciona el nivel de severidad (leve, moderado, crítico)<br>ENTONCES el sistema guarda el nivel de severidad<br>Y lo utiliza para priorizar o alertar durante la planificación y ejecución<br><br>**Escenario 3: Supervisor ingresa título y tipo de restricción del incidente**<br>DADO que el supervisor está completando los datos del incidente<br>CUANDO ingresa un título descriptivo y selecciona el tipo de restricción (acceso, clima, tránsito)<br>ENTONCES el sistema registra dicha información<br>Y la muestra como advertencia visible durante el seguimiento de la entrega | EP05 |
| US17 | Operario crea un incident report | Como operario, quiero crear reportes de incidentes con comentarios para que mis compañeros estén al tanto de su camino. | **Escenario 1: Operario visualiza entregas con incidentes registrados**<br>DADO que el operario accede a su panel de entregas asignadas<br>CUANDO una entrega tiene incidentes registrados<br>ENTONCES el sistema muestra un ícono de advertencia<br>Y permite consultar los detalles del incidente<br><br>**Escenario 2: Operario revisa severidad y tipo de restricción**<br>DADO que el operario está consultando los detalles de un incidente<br>CUANDO accede a la información del incidente<br>ENTONCES el sistema muestra la severidad y el tipo de restricción asociado<br>Y destaca si se requiere alguna acción preventiva<br><br>**Escenario 3: Operario reporta imposibilidad de cumplir con la entrega**<br>DADO que el operario detecta que una restricción impide realizar la entrega<br>CUANDO selecciona la opción “No se pudo entregar” e indica el motivo<br>ENTONCES el sistema registra la incidencia reportada<br>Y notifica al supervisor para tomar acciones correctivas | EP05 |
| US18 | Filtrado de tareas | Como supervisor logístico, quiero filtrar las tareas existentes en cuanto a su estado. | **Escenario 1: Ingreso a pantalla de filtros**<br>DADO que el supervisor desea gestionar tareas<br>CUANDO accede a la sección de tareas en el sistema<br>ENTONCES se muestra la interfaz con opciones de filtrado por estado<br><br>**Escenario 2: Aplicar filtro por estado específico**<br>DADO que el supervisor está en la pantalla de filtros<br>CUANDO selecciona un estado como “En ejecución”, “Pausada” o “Completada”<br>ENTONCES el sistema muestra únicamente las tareas que coinciden con ese estado<br><br>**Escenario 3: Visualizar todas las tareas sin aplicar filtro**<br>DADO que el supervisor no selecciona ningún filtro de estado<br>CUANDO accede al listado de tareas<br>ENTONCES el sistema muestra todas las tareas con su estado correspondiente |  |
| US19 | Bloquear programación de herramientas simultáneamente | Como supervisor logístico, quiero que una herramienta o equipo no pueda tener dos reservas simultáneas para evitar casos de overlap, retrasos y conflicto | **Escenario 1: Ingreso de programación de herramienta o equipo**<br>DADO que el supervisor desea programar una herramienta o equipo<br>CUANDO ingresa el tipo de recurso, su identificador, la hora de inicio y fin<br>ENTONCES el sistema registra la programación en la base de datos<br>Y la asocia correctamente al recurso indicado<br><br>**Escenario 2: Detección de programación duplicada**<br>DADO que ya existe una programación para una herramienta o equipo en un rango horario<br>CUANDO el supervisor intenta registrar una programación idéntica<br>ENTONCES el sistema lanza un mensaje de error indicando que ya existe una programación en ese horario<br>Y bloquea el registro de la programación duplicada<br><br>**Escenario 3: Rechazo de reserva con solapamiento (overlap)**<br>DADO que hay una reserva activa o futura en un rango horario específico para una herramienta o equipo<br>CUANDO el supervisor intenta ingresar una nueva reserva que se superpone parcialmente o totalmente<br>ENTONCES el sistema lanza un mensaje de error indicando conflicto de horarios<br>Y bloquea el registro de la nueva reserva<br><br>**Escenario 4: Registro exitoso de reserva sin conflicto**<br>DADO que no existe ninguna programación previa en el rango horario indicado<br>CUANDO el supervisor ingresa una nueva reserva<br>ENTONCES el sistema guarda la reserva exitosamente<br>Y confirma al usuario que no existe ningún solapamiento | EP09 |
| US20 | Evitar reprogramación con conflictos de horario | Como operario, quiero reprogramar una reserva de herramienta o equipo solo si no se cruza con otra existente, para evitar conflictos de uso simultáneo | **Escenario 1: Reprogramación de reserva**<br>DADO que el operario necesita modificar el horario de una reserva existente<br>CUANDO actualiza la hora de inicio y fin para una herramienta o equipo<br>ENTONCES el sistema verifica si hay conflictos con otras reservas activas<br>Y actualiza la programación si no hay solapamientos<br><br>**Escenario 2: Detección de conflicto por cruce de horarios**<br>DADO que existe otra reserva activa para la misma herramienta o equipo<br>CUANDO el operario intenta reprogramar una reserva con un horario que se solapa total o parcialmente<br>ENTONCES el sistema lanza un mensaje de error indicando conflicto de horarios<br>Y no permite completar la reprogramación<br><br>**Escenario 3: Reprogramación exitosa sin conflicto**<br>DADO que la herramienta o equipo está libre en el nuevo horario propuesto<br>CUANDO el operario actualiza la reserva con el nuevo horario<br>ENTONCES el sistema registra la reprogramación exitosamente<br>Y confirma que no existen reservas en conflicto<br><br>**Escenario 4: Validación previa antes de guardar**<br>DADO que el operario ha ingresado un nuevo rango horario<br>CUANDO el sistema detecta que no hay cruce con otras reservas<br>ENTONCES el sistema guarda y registra la reserva | EP09 |
| US21 | Supervisor evita reprogramación con conflictos de horario | Como supervisor logístico, quiero reprogramar una reserva de herramienta o equipo solo si no se cruza con otra existente, para evitar conflictos de uso simultáneo | **Escenario 1: Reprogramación de reserva**<br>DADO que el supervisor necesita modificar el horario de una reserva existente<br>CUANDO actualiza la hora de inicio y fin para una herramienta o equipo<br>ENTONCES el sistema verifica si hay conflictos con otras reservas activas<br>Y actualiza la programación si no hay solapamientos<br><br>**Escenario 2: Detección de conflicto por cruce de horarios**<br>DADO que existe otra reserva activa para la misma herramienta o equipo<br>CUANDO el supervisor intenta reprogramar una reserva con un horario que se solapa total o parcialmente<br>ENTONCES el sistema lanza un mensaje de error indicando conflicto de horarios<br>Y no permite completar la reprogramación<br><br>**Escenario 3: Reprogramación exitosa sin conflicto**<br>DADO que la herramienta o equipo está libre en el nuevo horario propuesto<br>CUANDO el supervisor actualiza la reserva con el nuevo horario<br>ENTONCES el sistema registra la reprogramación exitosamente<br>Y confirma que no existen reservas en conflicto<br><br>**Escenario 4: Validación previa antes de guardar**<br>DADO que el supervisor ha ingresado un nuevo rango horario<br>CUANDO el sistema detecta que no hay cruce con otras reservas<br>ENTONCES el sistema guarda y registra la reserva | EP09 |
| US22 | Crear nuevos usuarios | Como supervisor logístico, quiero registrar nuevos usuarios en el sistema para permitirles acceder y participar en los procesos logísticos. | **Escenario 1: Registrar un nuevo usuario operativo**<br>DADO que el supervisor desea dar acceso a un nuevo operario<br>CUANDO accede al módulo de administración de usuarios<br>Y completa los datos personales, rol y zona asignada<br>ENTONCES el sistema registra al nuevo usuario<br>Y envía sus credenciales de acceso<br><br>**Escenario 2: Evitar creación de usuarios con datos incompletos**<br>DADO que el supervisor intenta registrar un usuario<br>CUANDO no completa campos como nombre, documento o rol<br>ENTONCES el sistema impide el registro<br>Y muestra un mensaje indicando los campos requeridos<br><br>**Escenario 3: Consultar historial de usuarios creados**<br>DADO que el supervisor ha registrado múltiples usuarios<br>CUANDO accede al historial de creación<br>ENTONCES el sistema muestra una lista con fecha, nombre, rol y zona<br>Y permite exportar dicha información | EP10 |
| US23 | Asignar roles y permisos | Como supervisor logístico, quiero asignar roles (ej. operario, supervisor, gerente) para definir qué acciones puede realizar cada usuario. | **Escenario 1: Asignar rol de operario a nuevo usuario**<br>DADO que el supervisor registra un nuevo usuario<br>CUANDO selecciona el rol “Operario”<br>ENTONCES el sistema aplica los permisos correspondientes<br>Y limita el acceso solo a funciones operativas<br><br>**Escenario 2: Cambiar el rol de un usuario existente**<br>DADO que se necesita actualizar el perfil de un usuario<br>CUANDO el supervisor modifica su rol a “Supervisor”<br>ENTONCES el sistema actualiza los permisos en tiempo real<br>Y registra el cambio en el historial<br><br>**Escenario 3: Visualizar resumen de roles y permisos**<br>DADO que el supervisor accede al módulo de administración de roles<br>CUANDO consulta los perfiles configurados<br>ENTONCES el sistema muestra un resumen de roles<br>Y lista las acciones permitidas para cada uno | EP10 |
| US24 | Eliminar usuarios inactivos | Como supervisor logístico, quiero eliminar las cuentas de usuarios que ya no usan el sistema para mantener la seguridad y el orden del acceso. | **Escenario 1: Eliminar manualmente un usuario inactivo**<br>DADO que el supervisor detecta inactividad prolongada<br>CUANDO accede al módulo de administración y selecciona “Eliminar cuenta”<br>ENTONCES el sistema marca la cuenta como inactiva<br>Y registra la fecha y motivo de desactivación<br><br>**Escenario 2: Agregar cuenta de usuario nuevamente**<br>DADO que un usuario fue eliminado previamente<br>CUANDO el supervisor decide regresarlo al sistema<br>ENTONCES el sistema lo agrega con normalidad<br>Y envía notificación al usuario con condiciones de uso | EP10 |
| US25 | Generar plan de actividades | Como supervisor logístico, quiero generar un plan de todas las actividades programadas según los recursos y prioridades, para organizar eficientemente las actividades del día. | **Escenario 1: Generar plan diario según recursos disponibles**<br>DADO que el supervisor desea organizar las actividades del día<br>CUANDO accede al módulo de planificación operativa<br>Y selecciona la opción “Generar plan de actividades”<br>ENTONCES el sistema agrupa las tareas por recurso (vehículo, operario, zona)<br>Y genera un listado estructurado con horarios estimados<br><br>**Escenario 2: Visualizar el plan en formato calendario o lista**<br>DADO que el plan ya fue generado<br>CUANDO el supervisor accede a la vista<br>ENTONCES el sistema ofrece una vista tipo calendario por hora/zona<br>Y otra vista tipo lista con detalles por recurso asignado<br><br>**Escenario 3: Filtrar actividades por estado**<br>DADO que el plan de actividades está disponible<br>CUANDO el supervisor aplica un filtro por estado (pendiente, en curso, finalizado)<br>ENTONCES el sistema muestra únicamente las actividades que coinciden con ese estado<br>Y actualiza dinámicamente la vista del plan<br><br>**Escenario 4: Filtro vacío o incorrecto**<br>DADO que el supervisor no aplica ningún filtro o ingresa un valor inválido<br>CUANDO intenta visualizar el plan de actividades<br>ENTONCES el sistema muestra todas las actividades programadas sin aplicar ningún filtro<br>Y notifica que el filtro no es válido (en caso de error) | EP11 |
| US26 | Ver tareas programadas y disponibilidad de recursos | Como supervisor logístico, quiero ver las tareas programadas junto con sus recursos utilizados, para evitar conflictos al registrar nuevas actividades | **Escenario 1: Visualizar tareas programadas por operario**<br>DADO que el supervisor desea revisar la carga de trabajo del personal<br>CUANDO accede al módulo de planificación<br>ENTONCES el sistema muestra las tareas asignadas a cada operario<br>Y permite aplicar filtros únicamente por estado (pendiente, en curso, finalizado)<br><br>**Escenario 2: Consultar uso de espacios logísticos en tareas**<br>DADO que se requiere programar una operación en un espacio logístico<br>CUANDO el supervisor revisa la programación de espacios<br>ENTONCES el sistema muestra qué espacios están ocupados y por qué tareas<br>Y detalla los horarios disponibles para nuevas actividades<br><br>**Escenario 3: Verificación de conflictos al registrar nueva tarea**<br>DADO que el supervisor desea registrar una nueva tarea con recursos asignados<br>CUANDO el sistema detecta que uno o más recursos ya están ocupados en el mismo horario<br>ENTONCES lanza un mensaje de error indicando el conflicto<br>Y no permite guardar la programación hasta resolver el solapamiento<br><br>**Escenario 4: Registro exitoso sin conflictos**<br>DADO que los recursos seleccionados están disponibles en el horario ingresado<br>CUANDO el supervisor confirma la nueva programación<br>ENTONCES el sistema registra la tarea exitosamente<br>Y la asocia a los recursos seleccionados | EP11 |
| US32 | Selección de plan de empresa según volumen de envíos | Como empresa usuaria de la aplicación, quiero poder seleccionar un plan de uso según el número de envíos que realizo, para contar con una solución adecuada a mis necesidades logísticas y presupuestarias. | **Escenario 1: Visualizar y elegir plan de empresa**<br>DADO que la empresa ha creado su cuenta<br>CUANDO accede al módulo de suscripción<br>ENTONCES el sistema muestra los tres planes disponibles<br>Y permite seleccionar el más adecuado según sus necesidades<br><br>**Escenario 2: Sugerencia automática de plan según volumen de envíos**<br>DADO que la empresa tiene un historial de envíos<br>CUANDO el sistema detecta que el promedio mensual supera el límite de su plan<br>ENTONCES sugiere el cambio al siguiente plan<br>Y muestra beneficios y nuevo costo<br><br>**Escenario 3: Restringir envíos si se excede el plan contratado**<br>DADO que la empresa tiene contratado el plan Básico<br>CUANDO intenta registrar un envío adicional<br>ENTONCES el sistema impide el registro<br>Y muestra un mensaje indicando que se alcanzó el límite del plan | EP10 |
| US33 | Acceder a la sección principal del sitio (Hero Section) | Como visitante de la landing page, quiero visualizar una sección principal con el nombre de la app y un mensaje claro, para entender rápidamente sobre qué trata la aplicación y cómo me puede ayudar. | **Escenario 1: Ver contenido introductorio al cargar la landing**<br>DADO que el visitante accede a la página<br>CUANDO se carga el contenido inicial<br>ENTONCES se muestra el nombre de la aplicación, un mensaje principal y un botón “Conocer más”<br><br>**Escenario 2: Hacer clic en el botón “Conocer más”**<br>DADO que el visitante ve el botón<br>CUANDO hace clic en él<br>ENTONCES el sistema realiza scroll hacia la sección de funcionalidades<br><br>**Escenario 3: Visualización desde móvil o tablet**<br>DADO que el visitante accede desde un dispositivo móvil<br>CUANDO se muestra la sección principal<br>ENTONCES esta se adapta correctamente al tamaño de pantalla sin perder información clave | EP02 |
| US34 | Navegar entre secciones fácilmente | Como visitante de la landing page, quiero usar un menú superior con enlaces a las distintas secciones del sitio, para moverme cómodamente por la página sin perderme. | **Escenario 1: Usar el menú para navegar**<br>DADO que el visitante ve el encabezado del sitio<br>CUANDO hace clic en un ítem del menú<br>ENTONCES el sistema realiza scroll automático a la sección correspondiente<br><br>**Escenario 2: Menú con estado activo**<br>DADO que el visitante navega entre secciones<br>CUANDO se encuentra en una sección<br>ENTONCES el ítem del menú correspondiente se resalta para indicar su posición<br><br>**Escenario 3: Ver menú en versión móvil**<br>DADO que el visitante accede desde un móvil<br>CUANDO visualiza la parte superior del sitio<br>ENTONCES el sistema muestra un ícono de “hamburguesa”<br>Y al hacer clic despliega el menú de secciones<br><br>**Escenario 4: Volver al inicio desde el logo**<br>DADO que el visitante está en cualquier parte del sitio<br>CUANDO hace clic en el logo de la aplicación<br>ENTONCES el sistema realiza scroll hacia el inicio de la página | EP02 |

## Technical Stories (TS)

| Epic/User Story ID | Título | Descripción | Criterios de aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| TS01 | Post Employee | Como desarrollador de SwiftPort, quiero registrar un nuevo empleado mediante una API para gestionar el personal disponible dentro del sistema. | **Escenario 1: Solicitud válida**<br>DADO que tengo acceso al endpoint POST /api/v1/employees<br>CUANDO envío una solicitud con un cuerpo válido (nombre, correo, etc.)<br>ENTONCES se crea el nuevo empleado en la base de datos<br>Y recibo un objeto EmployeeResource con los datos del empleado creado<br><br>**Escenario 2: Solicitud con datos inválidos**<br>DADO que tengo acceso al endpoint<br>CUANDO envío una solicitud con campos faltantes o inválidos<br>ENTONCES recibo una respuesta con error 400<br><br>**Escenario 3: Error inesperado al consultar después de crear**<br>DADO que se ejecutó correctamente la creación<br>CUANDO se intenta recuperar el empleado y no se encuentra<br>ENTONCES recibo un 404 Not Found | No corresponde |
| TS02 | Get Employee by ID | Como desarrollador de SwiftPort, quiero obtener los datos de un empleado específico mediante su ID, para mostrar información detallada o validar su estado. | **Escenario 1: Empleado existente**<br>DADO que existe un empleado registrado<br>CUANDO hago una solicitud GET a /api/v1/employees/{id}<br>ENTONCES recibo el objeto EmployeeResource correspondiente<br><br>**Escenario 2: No hay empleados registrados**<br>DADO que no existen empleados en el sistema<br>CUANDO hago una solicitud GET a /api/v1/employees<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS03 | Get All Employees | Como desarrollador de SwiftPort, quiero recuperar una lista de todos los empleados registrados mediante una API, para usarlos en la interfaz de gestión del personal. | **Escenario 1: Empleados disponibles**<br>DADO que existen empleados en el sistema<br>CUANDO hago una solicitud GET a /api/v1/employees<br>ENTONCES recibo una lista de objetos EmployeeResource<br><br>**Escenario 2: No hay empleados registrados**<br>DADO que la base de datos está vacía<br>CUANDO hago la solicitud<br>ENTONCES recibo una respuesta 404 | No corresponde |
| TS04 | Patch Employee Status | Como desarrollador de SwiftPort, quiero modificar el estado de disponibilidad de un empleado específico, para reflejar cambios operativos en tiempo real. | **Escenario 1: Cambio válido de estado**<br>DADO que existe un empleado<br>CUANDO hago una solicitud PATCH a /api/v1/employees/{id}/status con un estado válido<br>ENTONCES el estado del empleado se actualiza correctamente<br>Y recibo el objeto EmployeeResource actualizado<br><br>**Escenario 2: Empleado no existe**<br>DADO que el ID proporcionado no corresponde a un empleado existente<br>CUANDO hago la solicitud<br>ENTONCES recibo una respuesta 404 | No corresponde |
| TS05 | Get Employees by Status | Como desarrollador de SwiftPort, quiero consultar todos los empleados filtrados por su estado de disponibilidad, para tareas de asignación o monitoreo. | **Escenario 1: Hay empleados con el estado solicitado**<br>DADO que existen empleados con el estado “AVAILABLE” u otro<br>CUANDO hago una solicitud GET a /api/v1/employees/status/{status}<br>ENTONCES recibo una lista de objetos EmployeeResource<br><br>**Escenario 2: No hay empleados con ese estado**<br>DADO que no hay empleados que coincidan con el estado solicitado<br>CUANDO hago la solicitud<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS06 | Post Incident Report to Execution | Como desarrollador de SwiftPort, quiero registrar un reporte de incidente asociado a una ejecución específica, para documentar problemas ocurridos durante una tarea. | **Escenario 1: Ejecución existente y datos válidos**<br>DADO que tengo una ejecución registrada<br>CUANDO envío una solicitud POST a /api/v1/incident-reports/{executionId}/incidents con datos válidos<br>ENTONCES el reporte se crea y asocia correctamente<br>Y recibo un objeto IncidentReportResource con estado 201<br><br>**Escenario 2: Datos inválidos**<br>DADO que tengo acceso al endpoint<br>CUANDO envío datos inválidos<br>ENTONCES recibo un error 400<br><br>**Escenario 3: Ejecución no encontrada**<br>DADO que el executionId no corresponde a ninguna ejecución<br>CUANDO hago la solicitud<br>ENTONCES recibo un error 404 | No corresponde |
| TS07 | Get Incident Report by ID | Como desarrollador de SwiftPort, quiero obtener un reporte de incidente específico mediante su ID, para mostrar sus detalles en la interfaz de usuario. | **Escenario 1: Reporte existente**<br>DADO que el ID de incidente corresponde a un reporte<br>CUANDO hago una solicitud GET a /api/v1/incident-reports/incidents/{incidentId}<br>ENTONCES recibo el recurso correspondiente con código 200<br><br>**Escenario 2: Reporte no encontrado**<br>DADO que el ID no existe<br>CUANDO hago la solicitud<br>ENTONCES recibo un error 404 | No corresponde |
| TS08 | Get Incident Reports by Execution | Como desarrollador de SwiftPort, quiero obtener todos los reportes de incidentes asociados a una ejecución específica, para facilitar la trazabilidad y seguimiento de eventos. | **Escenario 1: Ejecución con reportes**<br>DADO que hay incidentes relacionados a una ejecución<br>CUANDO hago una solicitud GET a /api/v1/incident-reports/{executionId}/incidents<br>ENTONCES recibo una lista de IncidentReportResource<br><br>**Escenario 2: Ejecución sin reportes asociados**<br>DADO que la ejecución existe pero no tiene reportes de incidentes<br>CUANDO hago la solicitud<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS09 | Get All Incident Reports | Como desarrollador de SwiftPort, quiero obtener todos los reportes de incidentes del sistema, para mostrarlos en una vista general de administración. | **Escenario 1: Hay reportes disponibles**<br>DADO que existen incidentes registrados<br>CUANDO hago una solicitud GET a /api/v1/incident-reports/incidents<br>ENTONCES recibo una lista de IncidentReportResource<br><br>**Escenario 2: No hay reportes registrados**<br>DADO que no existen incidentes en el sistema<br>CUANDO hago la solicitud<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS10 | Patch Incident Report Description | Como desarrollador de SwiftPort, quiero actualizar la descripción de un reporte de incidente existente, para corregir o ampliar la información ingresada inicialmente. | **Escenario 1: Actualización válida**<br>DADO que el ID del incidente existe<br>CUANDO envío una solicitud PATCH a /api/v1/incident-reports/incidents/{id} con nueva descripción<br>ENTONCES la descripción se actualiza correctamente<br><br>**Escenario 2: ID inexistente**<br>DADO que el ID no corresponde a ningún incidente<br>CUANDO hago la solicitud<br>ENTONCES recibo un error 404<br><br>**Escenario 3: Entrada inválida**<br>DADO que la descripción está vacía o malformada<br>CUANDO hago la solicitud<br>ENTONCES recibo un error 400 | No corresponde |
| TS11 | Patch Employee ID on Incident Report | Como desarrollador de SwiftPort, quiero actualizar el ID del empleado asociado a un incidente, para reflejar una asignación o corrección de responsabilidad. | **Escenario 1: Actualización exitosa**<br>DADO que el incidente y el nuevo empleado existen<br>CUANDO envío un nuevo ID de empleado en la solicitud PATCH a /api/v1/incident-reports/{incidentReportId}/employeeId<br>ENTONCES el campo employeeId se actualiza<br>Y recibo el recurso IncidentReportResource actualizado con código 200<br><br>**Escenario 2: Reporte no encontrado**<br>DADO que el ID del incidente no existe<br>CUANDO hago la solicitud PATCH a /api/v1/incident-reports/{incidentReportId}/employeeId<br>ENTONCES recibo un error 404<br><br>**Escenario 3: Nuevo Empleado no encontrado (Escenario faltante)**<br>DADO que el incidente existe pero el nuevo ID de empleado NO existe<br>CUANDO hago la solicitud PATCH a /api/v1/incident-reports/{incidentReportId}/employeeId<br>ENTONCES recibo un error 404 (o 400 si la validación del ID de empleado es estricta) | No corresponde |
| TS12 | Post Sign-In | Como desarrollador de SwiftPort, quiero permitir a los usuarios iniciar sesión mediante una API de autenticación, para que accedan a sus recursos protegidos. | **Escenario 1: Credenciales válidas**<br>DADO que el usuario existe y sus credenciales son correctas<br>CUANDO realiza una solicitud POST a /api/v1/authentications/sign-in<br>ENTONCES recibe un objeto AuthenticatedUserResource con estado 200<br><br>**Escenario 2: Credenciales inválidas**<br>DADO que las credenciales proporcionadas son incorrectas o no pertenecen a un usuario existente<br>CUANDO se realiza la solicitud<br>ENTONCES el sistema responde con un error 401 Unauthorized y un cuerpo JSON con detalles del error | No corresponde |
| TS13 | Post Sign-Up | Como desarrollador de SwiftPort, quiero permitir a nuevos usuarios registrarse mediante una API, para que puedan autenticarse y usar la aplicación. | **Escenario 1: Registro exitoso**<br>DADO que el usuario envía datos válidos de registro<br>CUANDO hace una solicitud POST a /api/v1/authentications/sign-up<br>ENTONCES se crea el usuario y se retorna un UserResource con estado 201<br><br>**Escenario 2: Registro con datos inválidos**<br>DADO que el usuario envía un request con datos incompletos o inválidos<br>CUANDO hace la solicitud<br>ENTONCES el sistema devuelve un error 400 con detalles JSON del problema | No corresponde |
| TS14 | Post Execution | Como desarrollador de SwiftPort, quiero crear una nueva ejecución mediante la API, para registrar una programación de tareas. | **Escenario 1: Crear ejecución con datos válidos**<br>DADO que tengo acceso a la API y envío datos correctos<br>CUANDO realizo una solicitud POST a /api/v1/executions<br>ENTONCES se registra la ejecución y retorna el recurso con estado 201<br><br>**Escenario 2: Datos inválidos**<br>DADO que envío una solicitud con campos faltantes o malformados<br>CUANDO realizo la operación<br>ENTONCES se devuelve un código 400 | No corresponde |
| TS15 | Get Execution By ID | Como desarrollador, quiero obtener una ejecución específica por su ID desde la API, para ver sus detalles asociados. | **Escenario 1: Ejecución encontrada**<br>DADO que existe una ejecución registrada con el ID dado<br>CUANDO realizo GET a /api/v1/executions/{executionId}<br>ENTONCES obtengo el recurso con estado 200<br><br>**Escenario 2: Ejecución no encontrada**<br>DADO que no hay ejecución con ese ID<br>CUANDO realizo la solicitud<br>ENTONCES recibo un error 404 Not Found | No corresponde |
| TS16 | Get All Executions | Como desarrollador, quiero obtener todas las ejecuciones mediante la API, para revisar la información consolidada de tareas programadas. | **Escenario 1: Hay ejecuciones registradas**<br>DADO que existen ejecuciones<br>CUANDO hago GET a /api/v1/executions<br>ENTONCES el sistema devuelve una lista con estado 200<br><br>**Escenario 2: No hay ejecuciones**<br>DADO que no existen registros de ejecuciones<br>CUANDO realizo la solicitud<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS17 | Add Employee To Execution | Como desarrollador, quiero asignar un empleado a una ejecución mediante la API, para registrar su participación. | **Escenario 1: Asociación válida**<br>DADO que existen tanto ejecución como empleado<br>CUANDO hago POST a /api/v1/executions/{executionId}/employees/{employeeId}<br>ENTONCES el empleado se asocia a la ejecución y retorna el recurso actualizado<br><br>**Escenario 2: Ejecución o empleado no encontrados**<br>DADO que alguno de los IDs (executionId o employeeId) no existe<br>CUANDO se realiza la solicitud<br>ENTONCES se devuelve código 404 Not Found | No corresponde |
| TS18 | Add Equipment To Execution | Como desarrollador, quiero asociar un equipo a una ejecución, para reflejar los recursos utilizados. | **Escenario 1: Asociación exitosa**<br>DADO que hay ejecución y equipo válidos<br>CUANDO se realiza POST a /api/v1/executions/{executionId}/equipment/{equipmentId}<br>ENTONCES el sistema los vincula y responde con estado 200<br><br>**Escenario 2: Ejecución o equipo no encontrados**<br>DADO que alguno de los IDs (executionId o equipmentId) no es válido o no existe<br>CUANDO se hace la solicitud<br>ENTONCES el sistema responde con código 404 Not Found | No corresponde |
| TS19 | Put Execution | Como desarrollador, quiero actualizar completamente los campos editables de una ejecución mediante la API, para corregir información registrada. | **Escenario 1: Actualización exitosa**<br>DADO que envío una solicitud PUT a /api/v1/executions/{executionId} con datos válidos<br>CUANDO se procesa la solicitud<br>ENTONCES se actualiza la ejecución y retorna estado 200<br><br>**Escenario 2: Ejecución no encontrada**<br>DADO que el ID no corresponde a ninguna ejecución<br>CUANDO intento actualizar<br>ENTONCES se devuelve un error 404 | No corresponde |
| TS20 | Patch Execution Status | Como desarrollador, quiero actualizar solo el estado de ejecución de una tarea mediante la API, para mantener actualizado su progreso. | **Escenario 1: Cambio de estado exitoso**<br>DADO que se identifica una ejecución válida<br>CUANDO se realiza PATCH a /api/v1/executions/{executionId}/status con un nuevo estado<br>ENTONCES se actualiza y retorna estado 200<br><br>**Escenario 2: Ejecución no encontrada**<br>DADO que el ID proporcionado es inválido<br>CUANDO realizo la solicitud<br>ENTONCES se devuelve un error 404 | No corresponde |
| TS21 | Get All Roles | Como desarrollador, quiero obtener todos los roles disponibles mediante la API, para usarlos en la asignación de permisos o visualización. | **Escenario 1: Hay roles registrados**<br>DADO que existen roles en el sistema<br>CUANDO realizo GET a /api/v1/roles<br>ENTONCES recibo una lista con estado 200<br><br>**Escenario 2: No hay roles registrados**<br>DADO que no existen roles en el sistema<br>CUANDO realizo GET a /api/v1/roles<br>ENTONCES recibo una respuesta con código 200 y una lista vacía | No corresponde |
| TS22 | Get All Users | Como desarrollador, quiero obtener todos los usuarios registrados para el tenant actual mediante la API, para gestionarlos. | **Escenario 1: Existen usuarios registrados**<br>DADO que hay usuarios en el sistema<br>CUANDO hago GET a /api/v1/users<br>ENTONCES obtengo una lista con estado 200<br><br>**Escenario 2: No hay usuarios registrados**<br>DADO que no existen usuarios en el sistema para el tenant actual<br>CUANDO hago GET a /api/v1/users<br>ENTONCES obtengo una lista vacía con estado 200 | No corresponde |
| TS23 | Get User By ID | Como desarrollador, quiero obtener la información de un usuario específico por su ID, para visualizar sus datos. | **Escenario 1: Usuario encontrado**<br>DADO que se ingresa un ID válido<br>CUANDO hago GET a /api/v1/users/{userId}<br>ENTONCES obtengo el recurso del usuario con estado 200<br><br>**Escenario 2: Usuario no encontrado**<br>DADO que se ingresa un ID de usuario inexistente<br>CUANDO realizo la solicitud GET a /api/v1/users/{userId}<br>ENTONCES recibo una respuesta con código 404 Not Found y un cuerpo de error JSON | No corresponde |
| TS24 | Create User | Como desarrollador, quiero crear un nuevo usuario mediante la API, para registrar un nuevo acceso en el sistema. | **Escenario 1: Datos válidos**<br>DADO que envío un cuerpo JSON válido<br>CUANDO realizo POST a /api/v1/users<br>ENTONCES se crea el usuario y se retorna con estado 201<br><br>**Escenario 2: Datos inválidos**<br>DADO que envío una solicitud con un cuerpo JSON que contiene datos inválidos o faltantes<br>CUANDO realizo la solicitud POST a /api/v1/users<br>ENTONCES se retorna estado 400 Bad Request y un cuerpo de error JSON | No corresponde |
| TS25 | Update User | Como desarrollador, quiero actualizar los datos de un usuario por su ID, para modificar su información personal o de rol. | **Escenario 1: Actualización exitosa**<br>DADO que ingreso un ID válido y datos correctos<br>CUANDO realizo PUT a /api/v1/users/{userId}<br>ENTONCES se actualiza y retorna el usuario actualizado con estado 200<br><br>**Escenario 2: Usuario no encontrado**<br>DADO que ingreso un ID inexistente<br>CUANDO realizo la solicitud<br>ENTONCES se devuelve estado 404 | No corresponde |
| TS26 | Update User Status | Como desarrollador, quiero activar o desactivar un usuario mediante un endpoint, para controlar su acceso al sistema. | **Escenario 1: Activación/desactivación válida**<br>DADO que existe un usuario con el {userId} dado<br>CUANDO realizo PUT a /api/v1/users/{userId}/status con un cuerpo JSON que contiene el campo 'active' (true/false)<br>ENTONCES el estado del usuario se actualiza correctamente<br>Y recibo el recurso del usuario actualizado con estado 200<br><br>**Escenario 2: Usuario no encontrado**<br>DADO que el ID de usuario no existe<br>CUANDO realizo la solicitud<br>ENTONCES se retorna estado 404 Not Found | No corresponde |
| TS27 | Delete User | Como desarrollador, quiero eliminar (desactivar) un usuario mediante la API, para revocar su acceso al sistema. | **Escenario 1: Eliminación válida**<br>DADO que se ingresa un ID válido<br>CUANDO hago DELETE a /api/v1/users/{userId}<br>ENTONCES se desactiva el usuario y se retorna con estado 200<br><br>**Escenario 2: Usuario no encontrado**<br>DADO que se ingresa un ID innexistente<br>CUANDO el ID no existe<br>ENTONCES se retorna 404 | No corresponde |
| TS28 | Create Activity | Como desarrollador, quiero crear una nueva actividad mediante la API, para registrar tareas planificadas. | **Escenario 1: Datos válidos**<br>DADO que tengo un cuerpo JSON con datos válidos para la actividad<br>CUANDO hago POST a /api/v1/activities<br>ENTONCES se crea la actividad<br>Y retorna el recurso de la actividad creada con estado 201<br><br>**Escenario 2: Datos inválidos**<br>DADO que el cuerpo de la solicitud contiene datos incorrectos o faltantes<br>CUANDO realizo la solicitud<br>ENTONCES retorna estado 400 Bad Request y un cuerpo de error JSON | No corresponde |
| TS29 | Get Activity By ID | Como desarrollador, quiero obtener una actividad específica por su ID mediante la API, para ver sus detalles. | **Escenario 1: Actividad encontrada**<br>DADO que existe una actividad con el {activityId} dado<br>CUANDO hago GET a /api/v1/activities/{activityId}<br>ENTONCES se retorna el recurso de la actividad con estado 200 OK<br><br>**Escenario 2: Actividad no encontrada por ID**<br>DADO que el {activityId} proporcionado no corresponde a ninguna actividad existente<br>CUANDO hago GET a /api/v1/activities/{activityId}<br>ENTONCES retorna estado 404 Not Found<br><br>**Escenario 3: ID con formato inválido**<br>DADO que el {activityId} proporcionado tiene un formato incorrecto (ej. texto en lugar de número)<br>CUANDO hago GET a /api/v1/activities/{activityId}<br>ENTONCES retorna estado 400 Bad Request | No corresponde |
| TS30 | Get All Activities | Como desarrollador, quiero obtener todas las actividades disponibles mediante la API, para visualizar la planificación. | **Escenario 1: Actividades disponibles**<br>DADO que hay actividades registradas en el sistema<br>CUANDO realizo GET a /api/v1/activities<br>ENTONCES recibo una lista con estado 200<br><br>**Escenario 2: Lista vacía**<br>DADO que no hay actividades registradas en el sistema<br>CUANDO realizo GET a /api/v1/activities<br>ENTONCES recibo una lista vacía con estado 200 OK | No corresponde |
| TS31 | Get Activities By Status | Como desarrollador, quiero obtener las actividades filtradas por estado para mostrar las pendientes o completadas. | **Escenario 1: Existen actividades con ese estado**<br>DADO que hay actividades que coincidan con el estado solicitado<br>CUANDO hago GET a /api/v1/activities/status/{status}<br>ENTONCES obtengo una lista con estado 200<br><br>**Escenario 2: No existen actividades con ese estado**<br>DADO que no hay actividades que coincidan con el estado solicitado<br>CUANDO hago GET a /api/v1/activities/status/{status}<br>ENTONCES obtengo una lista vacía con estado 200 OK | No corresponde |
| TS32 | Update Activity Status | Como desarrollador, quiero actualizar el estado de una actividad para reflejar su progreso dentro del sistema. | **Escenario 1: Actualización exitosa**<br>DADO que existe una actividad con el {activityId} dado y un estado válido para actualizar<br>CUANDO hago PATCH a /api/v1/activities/{activityId}/status con el nuevo estado<br>ENTONCES el estado de la actividad se actualiza<br>Y se devuelve el recurso actualizado con estado 200 OK<br><br>**Escenario 2: Actividad no encontrada**<br>DADO que el ID de la actividad no corresponde a ninguna actividad existente<br>CUANDO hago PATCH a /api/v1/activities/{activityId}/status<br>ENTONCES se retorna estado 404 Not Found | No corresponde |
| TS33 | Create Task | Como desarrollador, quiero crear una nueva tarea mediante la API para planificar el trabajo de una actividad. | **Escenario 1: Datos válidos**<br>DADO que tengo un cuerpo JSON con datos válidos para la creación de una tarea<br>CUANDO hago POST a /api/v1/tasks<br>ENTONCES se crea la tarea<br>Y retorna el recurso de la tarea creada con estado 201 Created<br><br>**Escenario 2: Datos inválidos**<br>DADO que el cuerpo de la solicitud contiene datos incorrectos o faltantes<br>CUANDO realizo la solicitud POST a /api/v1/tasks<br>ENTONCES retorna estado 400 Bad Request | No corresponde |
| TS34 | Get Task By ID | Como desarrollador, quiero obtener una tarea específica por su ID para visualizar su detalle. | **Escenario 1: Tarea encontrada**<br>DADO que existe una tarea con el {taskId} dado<br>CUANDO hago GET a /api/v1/tasks/{taskId}<br>ENTONCES retorna estado 200 OK y el recurso de la tarea<br><br>**Escenario 2: Tarea no encontrada**<br>DADO que el {taskId} proporcionado no corresponde a ninguna tarea existente<br>CUANDO realizo la solicitud GET a /api/v1/tasks/{taskId}<br>ENTONCES retorna estado 404 Not Found<br><br>**Escenario 3: ID con formato inválido (Opcional pero recomendable)**<br>DADO que el {taskId} proporcionado tiene un formato incorrecto<br>CUANDO hago GET a /api/v1/tasks/{taskId}<br>ENTONCES retorna estado 400 Bad Request | No corresponde |
| TS35 | Get Tasks By Activity ID | Como desarrollador, quiero obtener las tareas de una actividad específica para mostrar su planificación. | **Escenario 1: Actividad con tareas**<br>DADO que existe una actividad con el {activityId} dado que tiene tareas asociadas<br>CUANDO hago GET a /api/v1/tasks/activities/{activityId}<br>ENTONCES retorna una lista de tareas con estado 200 OK<br><br>**Escenario 2: Actividad sin tareas**<br>DADO que existe una actividad con el {activityId} dado pero no tiene tareas asociadas<br>CUANDO realizo la solicitud GET a /api/v1/tasks/activities/{activityId}<br>ENTONCES retorna una lista vacía con estado 200 OK<br><br>**Escenario 3: Actividad no encontrada**<br>DADO que el {activityId} proporcionado no corresponde a ninguna actividad existente<br>CUANDO hago GET a /api/v1/tasks/activities/{activityId}<br>ENTONCES retorna estado 404 Not Found | No corresponde |
| TS36 | Update Task Employee ID | Como desarrollador, quiero actualizar el empleado asignado a una tarea para reasignar responsabilidades. | **Escenario 1: Tarea actualizada con empleado existente**<br>DADO que existe una tarea con el {taskId} dado y un empleado con el nuevo {employeeId}<br>CUANDO hago PATCH a /api/v1/tasks/{taskId}/employeeId con el nuevo ID de empleado en el cuerpo de la solicitud<br>ENTONCES la tarea se actualiza correctamente |  |

---

## 3.2. Impact Mapping  

<img src="https://github.com/Rodri2712/TaskOil/blob/9994e81b0bfde7ee3b12050245f902ca9ffc3eb9/img/Impact%20Mapping.png"/>

## 3.3. Product Backlog  

### Prioridad Alta (Must Have)  
| ID    | User Story                                                                 | Estimación (Story Points) | Sprint Objetivo |
|-------|----------------------------------------------------------------------------|----------------------------|-----------------|
| US-01 | Como supervisor, quiero crear tareas con descripción, prioridad y recursos asignados | 5 | Sprint 1 |
| US-05 | Como técnico, quiero acceder a mis tareas asignadas sin necesidad de conexión a internet | 8 | Sprint 1 |
| US-06 | Como técnico, quiero registrar el inicio y fin de cada tarea | 3 | Sprint 1 |
| US-12 | Como técnico, quiero poder usar todas las funciones esenciales sin conexión a internet | 13 | Sprint 2 |
| US-09 | Como supervisor, quiero configurar alertas automáticas basadas en condiciones específicas | 8 | Sprint 2 |
| US-10 | Como técnico, quiero recibir notificaciones push sobre alertas de seguridad | 5 | Sprint 2 |

---

### Prioridad Media (Should Have)  
| ID    | User Story                                                                 | Estimación (Story Points) | Sprint Objetivo |
|-------|----------------------------------------------------------------------------|----------------------------|-----------------|
| US-02 | Como supervisor, quiero asignar tareas a técnicos específicos o equipos    | 5 | Sprint 3 |
| US-03 | Como supervisor, quiero reprogramar tareas en tiempo real ante imprevistos | 8 | Sprint 3 |
| US-04 | Como supervisor, quiero visualizar el estado de todas las tareas en un dashboard | 8 | Sprint 3 |
| US-07 | Como técnico, quiero adjuntar fotografías como evidencia del trabajo realizado | 5 | Sprint 4 |
| US-13 | Como técnico, quiero que mis datos se sincronicen automáticamente cuando recupere conexión | 8 | Sprint 4 |
| US-15 | Como supervisor, quiero visualizar métricas de cumplimiento de tareas      | 5 | Sprint 4 |

---

### Prioridad Baja (Could Have)  
| ID    | User Story                                                                 | Estimación (Story Points) | Sprint Objetivo |
|-------|----------------------------------------------------------------------------|----------------------------|-----------------|
| US-08 | Como técnico, quiero reportar incidencias durante la ejecución de tareas   | 3 | Sprint 5 |
| US-11 | Como supervisor, quiero visualizar el historial de alertas y respuestas    | 5 | Sprint 5 |
| US-14 | Como gerente, quiero generar reportes personalizados de productividad operativa | 8 | Sprint 5 |
| US-16 | Como auditor, quiero acceder al historial completo de operaciones con evidencias | 8 | Sprint 6 |

---

### Criterios de Aceptación Generales:  
- Funcionamiento en condiciones de conectividad limitada  
- Interfaz intuitiva y fácil de usar para personal técnico  
- Cumplimiento de normativas de seguridad petrolera  
- Sincronización bidireccional de datos  
- Escalabilidad para múltiples ubicaciones operativas  
- Seguridad de datos y autenticación robusta  

---

### Definición de Terminado (DoD):  
- Código desarrollado y revisado  
- Pruebas unitarias implementadas (cobertura >80%)  
- Pruebas de integración completadas  
- Funcionalidad probada en entorno offline  
- Documentación técnica actualizada  
- Cumplimiento de estándares de seguridad  
- Aprobación por parte del product owner  

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
