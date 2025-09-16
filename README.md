# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/md-images/upc-logo.png" alt="Logo UPC" width="150px" /></p>
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

| **Nombre**                         | **Código** |
| ---------------------------------- | ---------- |
| Baldeón Vivar, Santiago Armando    | U202319881 |
| Oskar Rodrigo Sosa Soto            | U202212214 |
| Rodrigo Fabrizio Aguilar Untiveros | U202318309 |
| Santiago Valentino Solis Chang     | U20231B475 |
| Johan Giovani Huamán Cuba          | u202417448 |

<div>
  <p align="center"><b>Ciclo 2025 - 20</b></p>
</div>

# Contenido

1. **[Capítulo I: Introducción](#1-capítulo-i-introducción)**  
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

2. **[Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)**  
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
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4. [Ubiquitous Language](#24-ubiquitous-language)

3. **[Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)**  
   &nbsp;&nbsp;&nbsp;&nbsp;3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.2. [User Stories](#32-user-stories)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.3. [Impact Mapping](#33-impact-mapping)  
   &nbsp;&nbsp;&nbsp;&nbsp;3.4. [Product Backlog](#34-product-backlog)

4. **[Capítulo IV: Product Design](#4-capítulo-iv-product-design)**  
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
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.1. [Class Diagrams](#471-class-diagrams)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.7.2. [Class Dictionary](#472-class-dictionary)  
   &nbsp;&nbsp;&nbsp;&nbsp;4.8. [Database Design](#48-database-design)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.8.1. [Database Diagram](#481-database-diagram)

5. **[Capítulo V: Product Implementation, Validation & Deployment](#5-capítulo-v-product-implementation-validation--deployment)**  
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
   &nbsp;&nbsp;&nbsp;&nbsp;5.3. [Validation Interviews](#53-validation-interviews)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.1. [Diseño de Entrevistas](#531-diseño-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.2. [Registro de Entrevistas](#532-registro-de-entrevistas)  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.3.3. [Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  
   &nbsp;&nbsp;&nbsp;&nbsp;5.4. [Video About-the-Product](#54-video-about-the-product)

6. **[Conclusiones](#6-conclusiones)**  
   &nbsp;&nbsp;&nbsp;&nbsp;6.1. [Conclusiones](#61-conclusiones)  
   &nbsp;&nbsp;&nbsp;&nbsp;6.2. [Recomendaciones](#62-recomendaciones)

7. **[Bibliografía](#7-bibliografía)**

8. **[Anexos](#8-anexos)**

---

# Capítulo I: Introducción

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

**¿Cuál es el problema?**

El problema puede ser mencionado como la falta de un recurso tecnológico capaz de organizar, planificar y supervisar las operaciones críticas en campo dentro de empresas petroleras. Actualmente, la ausencia de un sistema centralizado que permita coordinar y monitorear las tareas provoca **descoordinación**, **errores operativos**, **pérdidas de tiempo**, **aumento de costos** y **riesgos de seguridad** tanto para el personal como para el entorno. Esto genera impactos negativos en la eficiencia, la productividad y la capacidad de respuesta ante incidentes.

#### 1.2.1.2. Who

**¿Quiénes están involucrados en el problema?**

Este problema involucra principalmente a **supervisores y planificadores de campo**, encargados de distribuir tareas y asignar recursos de manera eficiente; a **operarios y técnicos**, responsables de ejecutar las actividades y reportar incidencias en el terreno; y a **personal administrativo y gerencial**, que requiere información confiable y actualizada para la toma de decisiones estratégicas y operativas. La falta de integración y visibilidad entre estos actores genera cuellos de botella que afectan directamente la continuidad de las operaciones petroleras.

#### 1.2.1.3. Where

**¿Dónde surge el problema?**

El problema surge en **plataformas de perforación, campos de extracción, estaciones de bombeo y plantas de procesamiento**, donde la ejecución de tareas requiere un alto nivel de coordinación y control. También se presenta en las **oficinas de control y centros administrativos**, donde la falta de visibilidad en tiempo real sobre el estado de las operaciones limita la capacidad de reacción ante imprevistos, como fallas de equipo, cambios climáticos o emergencias operativas.

#### 1.2.1.4. When

**¿Cuándo se presenta el problema?**

El problema inicia desde la **planificación inicial de las operaciones** y se intensifica durante la ejecución en campo, cuando los supervisores no cuentan con información actualizada para tomar decisiones rápidas. Persiste hasta la etapa de **verificación y cierre de tareas**, especialmente en situaciones donde se presentan **cambios inesperados o emergencias** que requieren reprogramar actividades, reasignar recursos o emitir alertas inmediatas.

#### 1.2.1.5. Why

**¿Por qué surge el problema?**

La causa principal radica en la **desorganización y fragmentación de la comunicación** entre los diferentes equipos de trabajo, sumada a la **ausencia de herramientas digitales especializadas** para la industria petrolera que permitan un control integral, trazable y en tiempo real de todas las operaciones. La dependencia de procesos manuales o herramientas genéricas provoca que la información se pierda, se registre de manera incompleta o no esté disponible en el momento necesario.

#### 1.2.1.6. How

**¿Cómo se utilizará el producto?**

**PetroTask** se utilizará como una **plataforma web y móvil** diseñada para que supervisores, técnicos y operarios puedan:

- **Planificar y coordinar tareas** críticas en campo.
- **Registrar evidencias** mediante fotografías y reportes de avance.
- **Recibir alertas automáticas** de seguridad y fallas de equipos.
- **Reprogramar actividades** en tiempo real ante imprevistos.
- **Acceder a un historial digital** con trazabilidad completa de cada operación.

La plataforma funcionará en entornos con conectividad limitada, permitiendo la carga y sincronización de datos una vez restablecida la conexión.

#### 1.2.1.7. How much

**¿Cuál es la magnitud del problema?**

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

**Business Assumptions:**

- **Creemos que nuestros usuarios necesitan** una solución digital que centralice la planificación, ejecución y seguimiento de operaciones petroleras, eliminando procesos manuales y reduciendo los errores humanos.
- **Estas necesidades pueden satisfacerse** mediante una plataforma web y móvil que permita registrar tareas, asignar recursos, recibir alertas automáticas y reprogramar actividades en tiempo real, incluso sin conexión a internet.
- **Nuestros clientes iniciales serán** empresas operadoras de petróleo, contratistas de servicios petroleros y empresas de mantenimiento industrial que trabajan en campos de extracción, transporte y procesamiento.
- **El valor más importante que un cliente espera de nuestros servicios es** la reducción de tiempos muertos, el aumento de la seguridad operativa y la trazabilidad completa de cada tarea.
- **Vamos a obtener la mayoría de nuestros clientes mediante** alianzas con proveedores del sector, demostraciones piloto en campos petroleros, ferias industriales y campañas de marketing digital especializadas en B2B energético.
- **Vamos a obtener ingresos mediante** suscripciones mensuales o anuales bajo el modelo SaaS escalable, con planes ajustados según el número de usuarios, ubicaciones y módulos contratados.
- **Nuestra competencia en el mercado será** software de gestión genérico, herramientas no adaptadas a la industria petrolera o sistemas costosos con poca flexibilidad para entornos remotos.
- **Vamos a tener ventaja frente a nuestra competencia debido a** la adaptación al contexto petrolero, la compatibilidad con IoT y sensores industriales, y la facilidad de uso en condiciones adversas.
- **El mayor riesgo del servicio es** que el personal de campo no registre las actividades de forma consistente o que la empresa no adopte el sistema como parte de su flujo de trabajo.
- **Lo resolveremos ofreciendo** una interfaz intuitiva, capacitación enfocada en procesos reales del sector y un soporte técnico disponible 24/7, además de realizar pilotos con iteración constante para asegurar la adopción.

**User Assumptions:**

**¿Quién es el usuario?**

Los usuarios principales son **supervisores, planificadores, técnicos y operarios** que participan en operaciones petroleras, así como **personal administrativo y gerencial** encargado de la toma de decisiones. Estos usuarios intervienen en distintas etapas del ciclo operativo, desde la planificación de tareas hasta su verificación y cierre, necesitando herramientas que les permitan coordinarse y actuar con rapidez.

**¿Qué problemas busca resolver el producto?**

La **falta de control y trazabilidad** de las tareas críticas, la **descoordinación entre equipos**, la **dificultad para reprogramar actividades** ante imprevistos y la **ausencia de reportes confiables** para la gestión operativa y la toma de decisiones estratégicas.

**¿Qué funcionalidades son importantes?**

**PetroTask** permitirá:

- Planificar tareas y asignar recursos humanos y materiales.
- Recibir alertas automáticas por incidencias o riesgos detectados.
- Reprogramar actividades en tiempo real ante cambios o emergencias.
- Registrar evidencias fotográficas para documentar el avance de las tareas.
- Generar reportes analíticos que faciliten la toma de decisiones.

**¿Dónde encaja nuestro producto en su trabajo o vida?**

En el **flujo operativo diario de las operaciones petroleras**: desde la preparación de trabajos, el control y supervisión en campo, el registro de avances, hasta la verificación y cierre de actividades.

**¿Cuándo y cómo es nuestro producto usado?**

Durante cada punto crítico de la operación, por múltiples usuarios de manera simultánea, accediendo desde **celulares, tablets o dashboards de oficina**, garantizando la actualización en tiempo real.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**

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

**Descripción General**

Mandos intermedios encargados de planificar, asignar y supervisar operaciones petroleras en terreno. Este segmento incluye a jefaturas y coordinadores que gestionan el uso de personal, equipos y recursos para cumplir con los objetivos operativos, garantizando seguridad y eficiencia en cada tarea.

**Perfil Demográfico**

- Edad: 30 a 55 años
- Experiencia: técnica-operativa en el sector petrolero, con alta responsabilidad en la coordinación de equipos
- Ubicación: regiones con actividad petrolera (como Loreto, Piura, Tumbes, Ucayali)
- Nivel digital: medio; familiarizados con hojas de cálculo, radio-comunicación, GPS y sistemas de gestión básicos

**Datos del Sector**

De acuerdo con reportes del sector energético en Latinoamérica, las operaciones petroleras requieren una coordinación precisa entre áreas para evitar retrasos y riesgos de seguridad. Las condiciones adversas del entorno, la infraestructura limitada y la necesidad de cumplir estándares internacionales de seguridad impulsan la adopción de soluciones tecnológicas adaptadas a entornos remotos.

**Necesidad**

Automatizar la planificación, trazabilidad y reprogramación de tareas críticas, permitiendo a los supervisores responder con agilidad ante imprevistos y generar reportes confiables para la toma de decisiones.

---

#### Segmento objetivo #2: Operarios de Campo / Técnicos Petroleros

**Descripción General**

Trabajadores encargados de ejecutar actividades operativas en plataformas, campos y plantas petroleras. Son responsables de llevar a cabo tareas de extracción, mantenimiento, transporte y control, así como de registrar avances, incidencias y condiciones del entorno de trabajo.

**Perfil Demográfico**

- Edad: 20 a 50 años
- Formación: técnica o empírica relacionada con operaciones de campo en el sector petrolero
- Herramientas: teléfonos móviles, radios, tablets (ocasionalmente)
- Nivel digital: bajo a medio; priorizan sistemas simples, rápidos y fáciles de usar

**Datos del Sector**

El personal de campo en la industria petrolera enfrenta condiciones ambientales exigentes y, en muchas ocasiones, limitaciones de conectividad. La adopción de herramientas móviles que funcionen sin conexión y permitan registrar información en tiempo real es clave para garantizar la trazabilidad y la seguridad de las operaciones.

**Necesidad**

Contar con una herramienta que facilite la consulta de tareas, el registro de datos reales (como hora de ejecución, cambios de recursos o incidencias) y la recepción de alertas rápidas, incluso en entornos sin conectividad.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

#### Segmento objetivo #1: Planificadores de actividades de campo

Actividades actuales

- ¿Cómo organizas las actividades que tu equipo realiza en campo?
- ¿Qué herramientas usas para planificar y asignar tareas?
- ¿Tienes algún proceso estándar para reagendar o modificar tareas?
- ¿Cuánto tiempo te toma asignar tareas para un día o semana?

Monitoreo y control

- ¿Cómo haces seguimiento a la ejecución de las tareas?
- ¿Cómo sabes si una actividad se completó correctamente?
- ¿Con qué frecuencia ocurren imprevistos o desviaciones?
- ¿Qué tan importante es para ti contar con reportes o estadísticas?

Tecnología y digitalización

- ¿Has usado alguna solución digital (app, sistema web) para estas tareas?
- ¿Qué te gustó o no te gustó de esas herramientas?
- ¿Qué funcionalidades consideras más importantes en un sistema de planificación y monitoreo?

Dolores y frustraciones

- ¿Qué es lo que más te complica en la planificación de campo?
- ¿Te resulta difícil coordinar con los operarios durante el día?
- ¿Qué consecuencias tiene una mala planificación en tu equipo?

Expectativas

- Si pudieras tener una herramienta ideal, ¿qué haría por ti?

---

#### Segmento objetivo #2: Operarios de campo

Flujo de trabajo

- ¿Cómo sabes qué tareas debes hacer cada día?
- ¿Recibes instrucciones claras sobre lo que se espera de ti?
- ¿Qué tipo de tareas haces normalmente?

Herramientas y comunicación

- ¿Qué dispositivos usas durante el trabajo? (celular, radio, tablet, etc.)
- ¿Cómo reportas que una tarea ya fue completada?
- ¿Te ha pasado que no sabes cómo proceder en una tarea? ¿Qué haces?

Seguimiento y ubicación

- ¿Alguna vez han rastreado tu ubicación mientras trabajas?
- ¿Estás de acuerdo con que se monitoree tu ubicación por razones de seguridad u operación?

Problemas frecuentes

- ¿Qué es lo más difícil de tu trabajo diario?
- ¿Qué pasa cuando hay un cambio de último minuto o problema en el campo?
- ¿Cómo te sientes con la forma actual en que se te asignan tareas?

Experiencia digital

- ¿Has usado alguna aplicación para recibir o reportar tareas?
- ¿Te parece fácil usar tecnología para trabajar o prefieres métodos tradicionales?

Mejoras posibles

- ¿Qué haría más fácil tu día a día en el campo?
- Si una aplicación pudiera ayudarte, ¿qué te gustaría que hiciera?

---

### 2.2.2. Registro de entrevistas

[**URL del video en Microsoft Stream:** ]()

#### Segmento objetivo #1: Supervisores y Planificadores de Campo

##### Entrevista 1: Supervisor de planta

- **Edad:** 30 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 1 captura de pantalla](assets/md-images/Entrevista1_SupervisorPlanta.png)

##### Resumen descriptivo de la entrevista:

El entrevistado se desempeña como **supervisor de planta** y organiza las actividades de su equipo en campo mediante **Excel** y reuniones rápidas al inicio del turno. Entrega planes impresos diariamente, aunque reconoce que los **imprevistos obligan a reprogramar casi todos los días**. El seguimiento se realiza por **WhatsApp o radio**, lo que a menudo genera **retrasos en la información**. Señala como mayor frustración la **falta de visibilidad en tiempo real** y considera clave contar con un **tablero digital que muestre el estado de las tareas al momento**.

##### Características objetivas:

- **Rol:** Supervisor de planta
- **Herramientas de trabajo:** Excel, impresiones, radio, WhatsApp
- **Canal de comunicación:** Reuniones diarias, mensajes digitales
- **Tecnología usada:** Básica (Excel, mensajería), sin sistemas especializados
- **Flujo de trabajo:** Planificación diaria, asignación manual, seguimiento reactivo

##### Características subjetivas:

- **Personalidad:** Práctico, resolutivo, busca eficiencia
- **Influencias:** Cambios operativos diarios, presión por cumplimiento
- **Necesidades:** Visibilidad en tiempo real, mejor comunicación, reducción de imprevistos
- **Disposición a adoptar tecnología:** Alta, busca soluciones simples y ágiles

---

##### Entrevista 2: Planificador de mantenimiento

- **Edad:** 30 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 2 captura de pantalla](assets/md-images/Entrevista2_PlanificadorMantenimiento.png)

##### Resumen descriptivo de la entrevista:

Este planificador realiza **cronogramas semanales en Excel** que ajusta manualmente con frecuencia. La validación de tareas se realiza mediante **fotos enviadas por WhatsApp**, aunque expresa dudas sobre su **autenticidad y trazabilidad**. Comenta que en su empresa probaron un **software de gestión**, pero fue descartado porque **no funcionaba sin conexión**. Considera que su mayor dificultad es la **falta de trazabilidad y control centralizado**, lo cual consume gran parte de su tiempo. Sugiere como ideal un sistema que **integre ubicación, hora y evidencia en un solo paso**.

##### Características objetivas:

- **Rol:** Planificador de mantenimiento
- **Herramientas de trabajo:** Excel, WhatsApp
- **Canal de comunicación:** Mensajes digitales, reportes manuales
- **Tecnología usada:** Software de proyectos fallido por falta de modo offline
- **Flujo de trabajo:** Planificación semanal, ajustes manuales, evidencias dispersas

##### Características subjetivas:

- **Personalidad:** Analítico, estructurado, crítico con herramientas poco prácticas
- **Influencias:** Necesidad de trazabilidad, presión por validación de resultados
- **Necesidades:** Centralización de evidencias, confiabilidad en los reportes
- **Disposición a adoptar tecnología:** Alta, siempre que funcione offline

---

##### Entrevista 3: Coordinador de operaciones

- **Edad:** 33 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 3 captura de pantalla](assets/md-images/Entrevista3_CoordinadorOperaciones.png)

##### Resumen descriptivo de la entrevista:

El coordinador organiza las órdenes mediante un **calendario impreso en la oficina** y depende de los **supervisores de turno** para ejecutar las actividades. Reconoce que los **retrasos y problemas se informan al final del día**, lo cual limita la posibilidad de reaccionar a tiempo. Los reportes llegan en **distintos formatos** (papel, correos, WhatsApp), generando dispersión de información. Aunque está abierto al uso de apps, admite que los **más jóvenes las dominan mejor que él**. Señala que una **plataforma unificada y operativa sin conexión** sería la herramienta ideal.

##### Características objetivas:

- **Rol:** Coordinador de operaciones
- **Herramientas de trabajo:** Calendario impreso, correos, WhatsApp, papeles
- **Canal de comunicación:** Supervisores de turno
- **Tecnología usada:** Básica, sin integración
- **Flujo de trabajo:** Planificación manual, comunicación indirecta, reportes fragmentados

##### Características subjetivas:

- **Personalidad:** Abierto al cambio, pero conservador en métodos actuales
- **Influencias:** Flujo de información disperso, dependencia de supervisores
- **Necesidades:** Centralización de reportes, alertas en tiempo real
- **Disposición a adoptar tecnología:** Media-alta, condicionado a facilidad de uso

---

#### Segmento objetivo #2: Operarios de Campo

##### Entrevista 4: Técnico de mantenimiento

- **Edad:** 24 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 4 captura de pantalla](assets/md-images/Entrevista4_TecnicoMantenimiento.png)

##### Resumen descriptivo de la entrevista:

Este técnico recibe instrucciones de su jefe al inicio de la jornada mediante **papel o radio**. Cuando hay cambios, depende de la comunicación por radio, lo que genera **demoras**. Usa **celular y radio**, aunque no siempre hay señal confiable. Indica que en ocasiones **no sabe si sus reportes fueron registrados**. Plantea que lo más útil sería una **aplicación en la que pueda marcar tareas completadas y adjuntar fotos fácilmente**.

##### Características objetivas:

- **Rol:** Técnico de mantenimiento
- **Herramientas de trabajo:** Papel, radio, celular
- **Canal de comunicación:** Instrucciones verbales, radio
- **Tecnología usada:** Ninguna aplicación formal
- **Flujo de trabajo:** Planificación diaria, reporte manual o verbal

##### Características subjetivas:

- **Personalidad:** Responsable, busca claridad en procesos
- **Influencias:** Limitaciones de señal, dependencia del supervisor
- **Necesidades:** Confirmación de tareas registradas, trazabilidad
- **Disposición a adoptar tecnología:** Alta, con enfoque en simplicidad

---

##### Entrevista 5: Operario de extracción

- **Edad:** 26 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 5 captura de pantalla](assets/md-images/Entrevista5_OperarioExtraccion.png)

##### Resumen descriptivo de la entrevista:

El operario recibe instrucciones del **capataz**, aunque muchas veces **no son claras en cuanto a responsabilidades específicas**. Su comunicación principal es **radio y WhatsApp** cuando hay señal disponible. Indica que los problemas más frecuentes se dan cuando ocurre una **falla técnica y nadie sabe cómo proceder**, generando **tiempos muertos**. Probó una **aplicación de inspecciones**, pero la abandonaron porque era **lenta y compleja**. Considera que la herramienta ideal sería una **app que guíe paso a paso y permita enviar fotos de las actividades**.

##### Características objetivas:

- **Rol:** Operario de extracción
- **Herramientas de trabajo:** Radio, WhatsApp
- **Canal de comunicación:** Capataz, mensajes
- **Tecnología usada:** App de inspecciones (abandonada)
- **Flujo de trabajo:** Instrucciones generales, resolución improvisada de problemas

##### Características subjetivas:

- **Personalidad:** Proactivo, adaptable, pragmático
- **Influencias:** Claridad en las órdenes, fallas técnicas imprevistas
- **Necesidades:** Guías claras paso a paso, comunicación efectiva
- **Disposición a adoptar tecnología:** Alta, con preferencia por apps simples y rápidas

---

##### Entrevista 6: Técnico de transporte

- **Edad:** 29 años
- **Distrito:** —
- **Marcas de tiempo de entrevista:**
- **Duración:**
- **Screenshot del video:**  
  ![Entrevista 6 captura de pantalla](assets/md-images/Entrevista6_TecnicoTransporte.png)

##### Resumen descriptivo de la entrevista:

Este técnico recibe su **hoja de rutas al inicio de cada turno**. Cuando hay cambios, suele enterarse tarde, lo que le hace perder tiempo en viajes innecesarios. Reconoce que su camión ya cuenta con **GPS**, pero este solo refleja la ubicación del vehículo y **no las actividades realizadas**. Está de acuerdo con un **sistema de rastreo personal** si se justifica por razones de seguridad. Su principal problema es llegar a recoger equipos que aún **no están listos**. Considera clave una **aplicación que le notifique cambios en tiempo real y evite desplazamientos inútiles**.

##### Características objetivas:

- **Rol:** Técnico de transporte
- **Herramientas de trabajo:** Hoja impresa, camión con GPS
- **Canal de comunicación:** Jefe de turno, llamadas, radio
- **Tecnología usada:** GPS de vehículo, sin apps
- **Flujo de trabajo:** Planificación diaria, rutas fijas, cambios tardíos

##### Características subjetivas:

- **Personalidad:** Responsable, orientado a resultados, paciente
- **Influencias:** Logística de materiales, coordinación de equipos
- **Necesidades:** Notificaciones en tiempo real, integración con rutas
- **Disposición a adoptar tecnología:** Media-alta, siempre que sea simple y práctica

---

### 2.2.3. Análisis de entrevistas

**Segmento objetivo #1: Supervisores y Planificadores de Campo**

#### Características Objetivas:

1. **Herramientas utilizadas**:

   - Todos los entrevistados usan **Excel** como principal medio de planificación y ajustes (100%).
   - La comunicación depende de **WhatsApp**, **radio** y **correos**; los reportes llegan en diferentes formatos (papel, fotos, mensajes).
   - No cuentan con un **software unificado ni especializado**.
   - Intentos previos de usar herramientas digitales fracasaron por **no contar con funcionalidad offline**.

2. **Tiempo dedicado**:

   - La planificación se realiza de manera **diaria o semanal**; en promedio, se invierte entre **1–3 horas por día** en ajustar planes.
   - Entre un **30% y 40%** de las tareas planificadas sufren desviaciones por imprevistos logísticos, técnicos o climáticos.

3. **Reportes y métricas**:
   - El seguimiento se hace de manera **reactiva**: validación con fotos enviadas por WhatsApp o llamadas.
   - Las métricas más relevantes son: **tareas completadas vs. planificadas**, **retrasos** y **evidencias de campo**.
   - No existe **trazabilidad formal** ni un sistema de consolidación de reportes en tiempo real.

#### Características Subjetivas:

1. **Desafíos en la planificación**:

   - Los imprevistos constantes (clima, fallas de equipos, cambios de última hora) obligan a **rehacer los planes con frecuencia**.
   - La falta de **información en tiempo real** genera retrasos y pérdida de control.
   - La dispersión de reportes (papel, fotos, WhatsApp, correos) **aumenta la carga administrativa**.

2. **Satisfacción con el sistema actual**:

   - **Baja**. Consideran que el sistema manual no les da seguridad ni eficiencia.
   - Los supervisores sienten que siempre **“corren detrás de los problemas”** en lugar de anticiparse.

3. **Expectativas de tecnologías emergentes**:
   - Existe **alta disposición** a usar nuevas herramientas, siempre que sean **simples, intuitivas y funcionen offline**.
   - Esperan un sistema que **centralice la planificación, ejecución y evidencias**, con **tableros de seguimiento en tiempo real**.

---

**Segmento objetivo #2: Operarios de Campo**

#### Características Objetivas:

1. **Herramientas utilizadas**:

   - El flujo de trabajo inicia con **órdenes verbales, hojas impresas o radios**.
   - El **celular** y **WhatsApp** se usan como soporte, aunque dependen de la señal.
   - Algunos probaron **apps**, pero fueron descartadas por ser **lentas o complicadas**.

2. **Tiempo dedicado**:

   - El trabajo no involucra tiempo de planificación, sino de **ejecución**; sin embargo, los operarios **pierden tiempo** cuando:
     - Reciben **órdenes tardías o poco claras**.
     - Deben **esperar materiales o instrucciones**.
   - Los retrasos se estiman en **30–40%** de las actividades diarias.

3. **Reportes y métricas**:
   - El registro de tareas se hace **verbalmente o enviando fotos al supervisor**.
   - El **GPS solo rastrea vehículos**, no actividades ni personas.
   - No existe **confirmación clara** de que el reporte fue registrado.

#### Características Subjetivas:

1. **Desafíos operativos**:

   - La falta de **claridad en las instrucciones** genera confusión.
   - Los **cambios de último minuto** y la ausencia de **protocolos digitales** ralentizan el trabajo.
   - Problemas frecuentes:
     - No saber si una tarea fue registrada.
     - Esperar por materiales no listos.
     - Recibir notificaciones tardías.

2. **Satisfacción con el sistema actual**:

   - **Baja a media**. Valoran los métodos tradicionales por su simplicidad, pero reconocen que generan **retrasos y falta de control**.
   - Existe frustración cuando sienten que **“trabajan sin guía”** o que sus reportes **“se pierden”**.

3. **Expectativas de tecnologías emergentes**:
   - Muestran **alta disposición** a usar apps si son **rápidas, simples y con mínimos pasos**.
   - Esperan soluciones como:
     - **Checklists digitales**.
     - **Subida de fotos y evidencias directas**.
     - **Notificaciones en tiempo real** para cambios de tareas o rutas.

---

### Conclusión del Análisis General

1. **Falta de digitalización**: Ambos segmentos dependen fuertemente de métodos manuales (**Excel, papel, radio, WhatsApp**). Esto genera **duplicidad de trabajo, retrasos y pérdida de trazabilidad**.
2. **Alta frecuencia de imprevistos**: Entre un **30–40%** de las actividades planificadas sufren cambios no anticipados. Esto impacta directamente en **eficiencia y tiempos de respuesta**.
3. **Problemas de comunicación**: La comunicación fragmentada (radio, mensajes, papel) hace difícil **coordinar en tiempo real**. Supervisores pierden visibilidad y operarios se sienten sin guía.
4. **Receptividad a la tecnología**: Tanto supervisores como operarios están abiertos a soluciones digitales, pero condicionan su uso a que sean **intuitivas, rápidas, offline y con integración de fotos/evidencias**.
5. **Necesidad compartida**:
   - Supervisores quieren **tableros en tiempo real y centralización de reportes**.
   - Operarios quieren **simplicidad, claridad de tareas y confirmación inmediata de sus reportes**.

Esto muestra un punto de encuentro claro: una herramienta que **conecte ambos niveles (planificación ↔ ejecución)** mediante una **plataforma digital ligera, integrada y offline**.

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV: Product Design

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

### 4.6.1. Software Architecture Context Diagram

### 4.6.2. Software Architecture Container Diagrams

### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

### 4.7.2. Class Dictionary

## 4.8. Database Design

### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

# Conclusiones

# Bibliografía

# Anexos
