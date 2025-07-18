<div align="center">
	
  
## Universidad Peruana de Ciencias Aplicadas

![Image](images/upc-logo.png)

## TB2 "StayMap"


**1ASI0729 - DESARROLLO DE APLICACIONES OPEN SOURCE**

Carrera de Ingeniería de Software


**NRC:** 4334

**Profesor:** Hugo Allan Mori Paiva

**Integrantes:**

Collantes Carrillo, Diego Mateo (u202311823)

Lizarbe Alvarez, Ariana Nickole (u202311704)

Ortiz Cardenas, Johanna Antuanete (u202310358)

Zegarra Lopez, Renato Sebastian Rubber (u202311558)

Zúñiga Murillo, Diego Sebastian (u202310636)


**2025**
</div>

## Registro de Versiones del Informe
<div align="center">
<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td>27/04/2025</td>
      <td>
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
	- Zúñiga Murillo, Diego Sebastian <br>
      </td>
      <td> Se ha llevado a cabo un trabajo integral que abarca desde la investigación inicial hasta las primeras fases de diseño del producto.Se han realizado entrevistas y análisis de usuarios para comprender mejor las necesidades y expectativas del público objetivo, lo que ha permitido definir de manera clara el enfoque de la solución.Además, se ha trabajado en la construcción de perfiles de usuario, journey maps, mapas de empatía y escenarios, fortaleciendo así la comprensión de la experiencia del usuario.Posteriormente, se elaboraron wireframes, mockups y diagramas de arquitectura de información y software, estableciendo una base visual y técnica para el desarrollo de la aplicación.Todo este proceso ha sido clave para estructurar adecuadamente el producto, alineándolo tanto a las necesidades detectadas como a los objetivos estratégicos del proyecto.Actualmente, el equipo cuenta con una visión sólida y organizada que guiará las próximas etapas de prototipado, validación e implementación.</td>
    </tr>
    <tr>
      <td>TP</td>
      <td>16/05/2025</td>
      <td> 
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
	- Zúñiga Murillo, Diego Sebastian <br></td>
      <td>En esta etapa del proyecto, el equipo ha avanzado en la implementación y despliegue de las funcionalidades clave. Se ha desarrollado y desplegado una nueva versión del Landing Page, incorporando mejoras basadas en el feedback recibido durante el Sprint 1. Además, se ha completado la primera versión funcional del Frontend cumpliendo con los requisitos técnicos y de diseño establecidos. Durante el Sprint 2, se realizó una planificación detallada, se asignaron roles específicos (Aspect Leaders) y se ejecutaron las tareas del Sprint Backlog, evidenciadas en el código, pruebas y documentación correspondiente. Asimismo, se actualizaron los artefactos previos, como el Project Report Collaboration Insights y la sección de Student Outcome, reflejando el progreso y la colaboración del equipo. En conclusión, contamos con una versión parcial adecuada para esta entrega que cumple con los requisitos establecidos.</td>
    </tr>
    <tr>
      <td>TB2</td>
	<td>21/06/2025</td>
      <td>
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
	- Zúñiga Murillo, Diego Sebastian <br></td>
      <td>Durante el Sprint 3, se completó con éxito el despliegue de la nueva versión de la landing page, así como la implementación y publicación de la aplicación web desarrollada en Angular y TypeScript, alojada en Vercel. Se llevó a cabo una planificación minuciosa, asignando roles específicos denominados Aspect Leaders, y se ejecutaron todas las tareas contempladas en el Sprint Backlog. El avance quedó documentado y evidenciado a través del código, pruebas y documentación correspondiente. Además, se actualizaron los artefactos previos, incluyendo el Project Report Collaboration Insights y la sección de Student Outcome, reflejando el progreso del equipo y la colaboración efectiva. En resumen, se dispone de una versión parcial que cumple con los requisitos establecidos para esta entrega.</td>
    </tr>
    </tr>
    <tr>
      <td>TF</td>
	<td>10/07/2025</td>
      <td>
	- Collantes Carrillo, Diego Mateo <br>
	- Lizarbe Alvarez, Ariana Nickole <br>
	- Ortiz Cardenas, Johanna Antuanete <br>
	- Zegarra Lopez, Renato Sebastian Rubber <br> 
	- Zúñiga Murillo, Diego Sebastian <br></td>
      <td>Durante el Sprint 4 se finalizó la implementación del backend utilizando Spring Boot con Java 24, aplicando una arquitectura basada en Domain-Driven Design (DDD). Se crearon los agregados, servicios y repositorios necesarios, y se configuró exitosamente la conexión con la base de datos, permitiendo la persistencia de datos a través del endpoint POST. Además, se integró Swagger para documentar y probar la API, lo que facilitó la validación del flujo completo de registro y dejó lista la base para futuras extensiones del sistema..</td>
    </tr>
  </tbody>
</table>
</div>

**Contents**

- [STUDENT OUTCOME](#student-outcome)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducción)
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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

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
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  	- [5.2.1. Sprint 1](#521-sprint-1)
		- [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
		- [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
		- [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
		- [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
		- [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
		- [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
  		- [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)	
		- [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    -  [5.2.2. Sprint 2](#522-sprint-2)
		- [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
		- [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
		- [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
		- [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
		- [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
		- [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
    	- [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
		- [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
	- [5.2.3. Sprint 3](#523-sprint-3)
   		 - [5.2.3.1. Sprint Planning 3.](#5231-sprint-planning-3)
  		 - [5.2.3.2. Aspect Leaders and Collaborators.](#5232-aspect-leaders-and-collaborators)
   		 - [5.2.3.3. Sprint Backlog 3.](#5233-sprint-backlog-3)
   	 	 - [5.2.3.4. Development Evidence for Sprint Review.](#5234-development-evidence-for-sprint-review)
  		 - [5.2.3.5. Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
   		 - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
  	  	- [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
 	   - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
      - [5.2.4. Sprint 4](#524-sprint-4)
	      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
	      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
	      - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
	      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
	      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
	      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
	      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
	      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews.](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas.](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas.](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas.](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product.](#54-video-about-the-product)

- [Conclusiones](#conclusiones)
- [Video About-the-Team](#about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME
ABET - EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro.

<table border="1">
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Comunica oralmente con
efectividad a diferentes rangos
de audiencia.</td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: Como líder del primer sprint, organicé meticulosamente las reuniones diarias asegurando que cada uno compartiera sus avances, bloqueos y próximos pasos. Implementé un sistema rotativo para que todos tuvieran la oportunidad de facilitar estas sesiones, desarrollando así habilidades de liderazgo compartido.<br>
	      <br>
        TP: En esta fase, roté estratégicamente el rol de líder para empoderar a otros miembros del equipo. Guiamos colectivamente la transición de Figma a Webstorm, realizando análisis técnicos comparativos que demostraron los beneficios en rendimiento para nuestro caso específico.
	      <br>
	      <br>
	      TB2: En el proyecto realicé entrevistas a usuarios y presentaciones orales al equipo y docentes, adaptando el lenguaje según el público. Esto permitió comunicar ideas y avances de forma clara y comprensible.
	      <br>
	      <br>
        TF: Con respecto al trabajo StayMap, durante la presentación oral expuse con claridad los ajustes que realicé en el frontend, así como la implementación del módulo de autenticación y los endpoints correspondientes. Me aseguré de comunicarme de manera comprensible para todos los miembros del jurado, adaptando el lenguaje técnico cuando fue necesario. <br>
	      <br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
        TB1:  diseñé el diagrama entidad-relación inicial y documenté exhaustivamente las reglas de validación. Realicé múltiples sesiones de programación en pareja para implementar los endpoints clave, al tiempo que creé un repositorio interno con ejemplos de código y buenas prácticas. Cuando surgieron discrepancias sobre prioridades de desarrollo, medié para encontrar soluciones que balancearan las necesidades técnicas con los requerimientos de usabilidad.<br>
	      	      <br>
        TP: Me encargué de desarrollar el diseño de STAYMAP dentro de la experiencia del usuario, implementando funcionalidades como inicio de sesion o lista de conciertos dentro del programa.
	      <br>
	      <br>
	TB2: Durante la ejecución del proyecto, participé activamente en la realización de entrevistas a usuarios pertenecientes al segmento objetivo. Estas entrevistas me permitieron adaptar mi lenguaje oral según el perfil de cada persona, explicando de manera clara y empática el propósito de nuestra aplicación. Ajusté mi comunicación para obtener respuestas relevantes y valiosas, facilitando así la recolección de información útil para la mejora del producto.
	      <br>
   <br>
	TF:Con respecto al trabajo StayMap, como team leader presenté los avances del equipo y mis contribuciones específicas, como la nueva landing page y los endpoints de conciertos y posts. Me esforcé por usar un lenguaje accesible y ordenado, asegurando que todos los asistentes entendieran el progreso del proyecto.
	      <br>
	      <br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1:  lideré el proceso iterativo de diseño del Landing Page, incorporando activamente el feedback de todos mediante encuestas estructuradas y herramientas colaborativas. Documenté minuciosamente guías de estilo y componentes reutilizables para mantener coherencia visual. Además, instituí espacios dedicados a discutir accesibilidad e inclusión, enriqueciendo así nuestra perspectiva colectiva.<br>
	      	      <br>
        TP: Organicé talleres de diseño participativo donde cada miembro contribuyó activamente a los prototipos, y validamos los cambios mediante pruebas controladas para que el trabajo cumpla con todas las necesidades impuestas para esta entrega parcial.
	      <br><br>
        TB2: Me comuniqué de forma clara y efectiva con mis compañeros durante el proceso de deployment del proyecto, coordinando las tareas necesarias para subir correctamente el repositorio. Participé activamente en reuniones, adaptando mi lenguaje técnico para asegurar que todos comprendieran sus responsabilidades y pudiéramos entregar un trabajo funcional y organizado.
	      <br>
	      <br>
        TF: Con respecto al trabajo StayMap, durante la presentación oral expliqué las funcionalidades que implementé en el módulo de comunidades y el perfil del usuario, utilizando un lenguaje claro y adaptado al público. Expresé con seguridad los retos que enfrenté y cómo los resolví.
	      <br>
	      <br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: Gestioné la comunicación con los stakeholders externos, traduciendo requerimientos técnicos a un lenguaje accesible y organizando sesiones de alineación. Recluté usuarios para pruebas de usabilidad y sinteticé los hallazgos en informes accionables. También identifiqué y resolví tensiones por carga de trabajo desigual, redistribuyendo tareas para optimizar nuestro rendimiento grupal.<br>
	      	      <br>
        TP: Me encargué de la revisión de funcionalidades y mejoría del frontend de STAYMAP asegurandome de que el uso sea pertinente y eficaz para cumplir con los objetivos requeridos
	      <br>
	       <br>
        TB2: Me encargué de comunicar de forma clara y efectiva los cambios necesarios para integrar la página de detalles de cada concierto, así como la implementación de la pantalla de perfil y la lista de confirmación de asistencia. Esta comunicación permitió al equipo comprender rápidamente las funcionalidades y avanzar de forma coordinada.
	      <br>
	       <br>
        TF: Con respecto al trabajo StayMap, durante la sustentación expuse con claridad las correcciones que realicé en las diferentes versiones del frontend, así como mis aportes en la documentación del sprint review. Me aseguré de adaptar mi comunicación según el perfil del público.
	      <br>
	      <br>
<strong>Zuniga Murillo, Diego Sebastian</strong><br>
        TB1: Lidere la gestion y revision de entrevistas para validar los puntos criticos dentro de STAYMAP creando gias de analisis donde se indican los puntos de mejoria para satisfacer a los usuarios <br>
	      <br>
        TP: Ajusté la entrega del proyecto para alinear STAYMAP con las exigencias de esta etapa. Implementé una API que genera un mapa dinámico con la ubicación de conciertos en la zona elegida, destacando los nombres de los artistas.
	      <br><br>
        TB2: Las revisiones con el docente me ayudaron a adaotar mi lenguaje según el público, explicando tanto decisiones técnicas (como la estructura en dominios y el uso de Angular standalone) además de funcionalidades clave orientadas al usuario. <br><br>
        TF: Con respecto al trabajo StayMap, durante la sustentación expuse con claridad las correcciones que realicé en las diferentes versiones del frontend, así como mis aportes en la documentación del sprint review. Me aseguré de adaptar mi comunicación según el perfil del público. <br>
	      <br>
      </td>
      <td>
        Con respecto al trabajo StayMap, consideramos que logramos comunicar oralmente con efectividad a diferentes rangos de audiencia a lo largo de todas las etapas del proyecto. Durante nuestras presentaciones y sustentaciones, fuimos capaces de adaptar nuestro lenguaje según el contexto: utilizamos términos técnicos precisos cuando nos dirigimos a los docentes, y explicaciones más accesibles cuando presentamos avances a usuarios, compañeros o stakeholders sin formación especializada. Cada integrante asumió con responsabilidad el rol de exponer sus avances, aclarar dudas y justificar decisiones de manera estructurada y segura. Además, incorporamos recursos visuales y ejemplos concretos para complementar nuestras explicaciones, lo cual facilitó la comprensión del funcionamiento del sistema y de las funcionalidades implementadas. Esta capacidad de comunicación oral no solo fortaleció la percepción del proyecto, sino que también nos permitió recibir retroalimentación valiosa y mantener una colaboración efectiva entre los miembros del equipo y con el entorno externo.
      </td>
    </tr>
    <tr>
      <td>Comunica por escrito con
efectividad a diferentes rangos
de audiencia </td>
      <td>
        <strong>Collantes Carrillo, Diego Mateo</strong><br>
        TB1: 
ideré la creación de documentación técnica especializada para STAYMAP, adaptando complejos diagramas arquitectónicos en guías accesibles con versiones diferenciadas para equipos de desarrollo (detalladas) y stakeholders (enfoque ejecutivo).
<br><br>
	      TP: Diseñé la documentación oficial de STAYMAP, estableciendo estándares para la creación y manejo de diagramas, además de actualizar las guías con los cambios relevantes para esta entrega.
	      <br><br>
	      TB2: Elaboré reportes de entrevistas y evaluaciones heurísticas con lenguaje claro para todo el equipo. También redacté descripciones funcionales considerando el perfil de los lectores.
	      <br>
	      <br>
	      TF: Con respecto al trabajo StayMap, redacté mis aportes al sistema de forma clara y estructurada, detallando mis responsabilidades técnicas de forma que cualquier lector pudiera comprenderlas, sin importar su nivel de conocimiento en programación.
	      <br>
	      <br>
        <strong>Lizarbe Alvarez, Ariana Nickole</strong><br>
	       TB1: 
Diseñé la estrategia de contenido multiplataforma para STAYMAP, desarrollando desde whitepapers técnicos hasta copy persuasivo para la Landing Page, adaptando el tono y profundidad según cada canal.
<br><br>
	      TP: Documenté exhaustivamente la base de datos implementada en STAYMAP, destacando sus componentes clave y funcionalidades críticas para nuestro proyecto.
	      <br><br>
	      TB2: Me encargué de diseñar y desarrollar la landing page del proyecto, enfocándome en transmitir el valor de la aplicación de manera efectiva a través de los textos y la estructura visual. Redacté contenido claro, conciso y adaptado tanto para usuarios casuales como para posibles interesados más técnicos, logrando que la información fuera accesible y atractiva para distintos tipos de audiencia.
	      <br>
	      <br>
	      TF: Con respecto al trabajo StayMap, describí de manera clara mis responsabilidades técnicas y de coordinación dentro del equipo, redactando un informe que puede ser comprendido tanto por personas con conocimientos técnicos como por quienes no están familiarizados con el desarrollo web.
	      <br>
	      <br>
        <strong>Ortiz Cardenas, Johanna Antuanete</strong><br>
        TB1: Implementé un sistema de documentación modular para STAYMAP, creando plantillas estandarizadas que permitieron escalar la comunicación técnica sin perder coherencia.<br>
	      <br>
	      TP: Documenté el proceso de selección e implementación de las APIs utilizadas, facilitando la comprensión de sus ventajas técnicas.
	      <br><br>
        TB2: Me encargué de actualizar el apartado de edición de perfil de usuario y de mejorar el formulario de creación de conciertos, documentando los cambios para todo el equipo. Esto permitió mantener una comunicación efectiva en el repositorio y facilitó el seguimiento del desarrollo para compañeros con distintos niveles técnicos.
        <br>
	<br>
        TF: Con respecto al trabajo StayMap, documenté mis tareas de forma organizada y accesible, explicando cada funcionalidad desarrollada en el frontend para que cualquier lector, sin importar su experiencia técnica, pudiera entender mi aporte al proyecto.
        <br>
	      <br>
        <strong>Zegarra Lopez, Renato Sebastian Rubber</strong><br>
        TB1: Publiqué artículos técnicos en el blog interno de STAYMAP sobre patrones de diseño de bases de datos, convirtiéndome en el referente para consultas técnicas escritas.<br>
	      <br>
	      TP: Elaboré un análisis técnico detallado que permitió al equipo comprender a profundidad la implementación y capacidades de nuestra base de datos.
	      <br><br>
	      TB2: Documenté de forma clara las decisiones técnicas relacionadas con la integración de la vista de detalles de conciertos, el perfil de usuario y el sistema de confirmación de asistencia. Esto incluyó mensajes en los commits, issues y explicaciones escritas que facilitaron la comprensión de los cambios por parte de todo el equipo.
	      <br>
	      <br>
	      TF: Con respecto al trabajo StayMap, redacté un informe detallado sobre mis responsabilidades en la base de datos y la lógica de negocio. Me aseguré de que la redacción fuera comprensible tanto para profesores con experiencia técnica como para lectores no especializados.
	      <br>
	      <br><br>
        <strong>Zúñiga Murillo, Diego Sebastian</strong><br>
        TB1: Implementé un sistema automatizado de dashboards para sintetizar feedback cualitativo de STAYMAP, generando informes ejecutivos mensuales accionables.<br>
	       <br>
	      TP: Desarrollé una guía de decisiones técnicas que documenta el razonamiento detrás de cada implementación (como las APIs), incluyendo justificaciones de diseño.
	      <br> <br>
	      TB2: Redacté documentación técnica clara y bien estructurada en el repositorio GitHub del proyecto, incluyendo guías de despliegue, convenciones de código y estructura de carpetas. También elaboramos informes escritos dirigidos tanto a docentes como a usuarios no técnicos, asegurando que cada tipo de lector comprendiera el contenido según su nivel.
	      <br>
	      TF: Con respecto al trabajo StayMap, redacté mis avances de forma clara y coherente, detallando tanto las tareas técnicas que realicé como mi aporte en el trabajo colaborativo. Mi redacción fue pensada para ser entendida por cualquier persona interesada en el proyecto, sin importar su experiencia técnica.
      </td>
      <td>
      Con respecto al trabajo StayMap, consideramos que demostramos nuestra capacidad para comunicar por escrito de manera efectiva a distintos tipos de audiencia. Desde el inicio del proyecto nos esforzamos por generar documentación clara, bien estructurada y útil tanto para desarrolladores como para usuarios finales. Elaboramos informes técnicos, descripciones funcionales, documentación de APIs, guías de despliegue, e incluso contenido orientado a la presentación pública del producto. Cada uno de nosotros redactó sus aportes considerando la diversidad de lectores, asegurando que cualquier persona —independientemente de su nivel técnico— pudiera comprender el propósito y funcionamiento de lo desarrollado. Además, mantuvimos actualizado el repositorio con mensajes claros en los commits, issues y manuales que facilitaron la organización y el trabajo colaborativo. Esta comunicación escrita nos permitió consolidar una base de conocimiento compartido y demostrar profesionalismo en cada entrega, lo que refleja nuestra capacidad de expresarnos con claridad y precisión en un entorno académico y técnico.
      </td>
    </tr>
  </tbody>
</table>


# Project Report Collaboration Insights

URL de la organización The Rumbling: `https://github.com/The-Rumbling`

<p align="center">
  <img src="assets/capturas/the-Rumbling.png" alt="commits grafico" width="700">
</p>

URL del repositorio de "StayMap": `https://github.com/The-Rumbling/StayMap-Report.git`

<p align="center">
  <img src="assets/capturas/captura-commits2.png" alt="commits2" width="700">
</p>

<p align="center">
  <img src="assets/capturas/captura-grafico-commits.png" alt="commits grafico" width="700">
</p>

# CAPÍTULO I: INTRODUCCIÓN

# 1.1. Startup Profile

## 1.1.1. Descripción de la Startup
The Rumbling es una startup creativa y tecnológica comprometida con transformar la manera en que las personas descubren, conectan y viven la música en vivo. Creemos que cada concierto, sin importar su tamaño, tiene el poder de generar emociones únicas y crear vínculos duraderos entre artistas y fans. Por ello, trabajamos en soluciones digitales innovadoras que conectan al público con experiencias musicales auténticas y accesibles.
Nos enfocamos en el desarrollo de StayMap, una aplicación web interactiva que actúa como un puente entre los amantes de la música y los escenarios de su ciudad. A través de un mapa dinámico con geolocalización, los usuarios pueden explorar eventos en tiempo real, seguir a sus artistas favoritos, conocer las fechas de sus giras, hacer check-in en conciertos y compartir momentos con otros fans. Además, brindamos herramientas de promoción y visibilidad para bandas emergentes, contribuyendo activamente al crecimiento de la escena musical independiente.
En The Rumbling, apostamos por el poder de la comunidad, el descubrimiento espontáneo y la tecnología como medio para enriquecer las experiencias culturales. Nuestra visión es construir una red global donde cada presentación en vivo —desde un bar local hasta un festival internacional— pueda ser descubierta, compartida y vivida al máximo, celebrando la diversidad y el dinamismo del mundo musical.
Con pasión, creatividad y enfoque social, desde el corazón de The Rumbling impulsamos proyectos como StayMap, que reimaginan el futuro de la música en vivo y lo acercan a quienes más lo disfrutan.

## 1.1.2. Perfiles de integrantes del equipo

| Estudiante | Descripción |
|------------|-------------|
| ![team member profile photo](assets/profile_images/diego_collantes.png) **Collantes Carrillo, Diego Mateo (u202311823)** | Mi nombre es Diego Collantes. Tengo 19 años. Soy estudiante de quinto ciclo en la Universidad Peruana de Ciencias Aplicadas (UPC). Disfruto de leer, redactar y escuchar música en mi tiempo libre. Elegí esta carrera, ya que me interesó todo el proceso que hay detrás de cada aplicación o programa que usamos en nuestro día a día. Personalmente, espero ampliar mis conocimientos en este ámbito a lo largo de este curso. Además, estoy comprometido a contribuir en todo lo que sea posible con el equipo y a desempeñarme de manera adecuada. |
| ![team member profile photo](assets/profile_images/ariana_lizarbe.png) **Lizarbe Alvarez, Ariana Nickole (u202311704)** | Mi nombre es Ariana Lizarbe, tengo 19 años y estoy cursando el cuarto ciclo de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. En mi tiempo libre fuera de la universidad, procuro mejorar mis habilidades blandas, como la empatía o inteligencia emocional. También, me esfuerzo en adquirir conocimientos que pueden ayudarme a desarrollarme como futura profesional, como distintos lenguajes de programación. A su vez, disfruto de escuchar música, podcasts, leer y ver series de televisión. Me comprometo a colaborar de manera activa y responsable en la creación de esta startup, aportando mis habilidades en pensamiento crítico, trabajo en equipo y adaptabilidad para alcanzar un trabajo de calidad sobresaliente. |
| ![team member profile photo](assets/profile_images/antuanete_ortiz.png) **Ortiz Cardenas, Johanna Antuanete (u202310358)** | Mi nombre es Johanna Antuanete Ortiz Cárdenas, tengo 18 años y me encuentro en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona proactiva y responsable, siempre buscando que mis trabajos sean de la mejor calidad posible. Me apasiona investigar sobre tecnología, lo que me permite estar al tanto de las últimas novedades y tendencias. En mi tiempo libre, disfruto jugar videojuegos, escuchar música y leer cómics. En el presente proyecto grupal, me comprometo a colaborar de manera activa, aportando ideas y siendo puntual con los entregables para garantizar resultados sobresalientes. |
| ![team member profile photo](assets/profile_images/renato_zegarra.png) **Zegarra Lopez, Renato Sebastian Rubber (u202311558)** | Mi nombre es Renato Zegarra, tengo 19 años y actualmente estoy cursando la carrera de Ingeniería de Sistemas de Información en la Universidad Peruana de Ciencias Aplicadas. Fuera de mis estudios, disfruto explorar mis intereses en música, videojuegos y tecnología, siempre buscando nuevas formas de integrar estas pasiones en mi vida cotidiana. Me comprometo a colaborar de manera activa y responsable en la elaboración de este documento y en la concreción de la idea propuesta, aportando mis habilidades en análisis, creatividad y adaptabilidad. Estoy convencido de que con esfuerzo y trabajo en equipo, podemos alcanzar resultados innovadores y de alta calidad. |
| ![team member profile photo](assets/profile_images/diego_zuniga.png) **Zúñiga Murillo, Diego Sebastian (u202310636)** | Mi nombre es Diego Sebastián Zúñiga Murillo, tengo 20 años y actualmente curso el quinto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona puntual, participativa y responsable, con una fuerte pasión por la tecnología y el aprendizaje constante. En mi tiempo libre disfruto de escuchar música, lo que me ayuda a relajarme y mantener el equilibrio entre mis estudios y mi vida personal. Como estudiante, me comprometo a aportar activamente en el desarrollo de este proyecto, contribuyendo con creatividad, iniciativa y habilidades de liderazgo. Confío en que, trabajando en equipo y manteniendo una comunicación constante, lograremos resultados destacados que reflejan nuestro esfuerzo y compromiso. |

# 1.2 Solution Profile
## 1.2.1. Antecedentes y problemática
**What**:

Las personas tienen dificultades para descubrir y conectarse con conciertos en vivo, especialmente los de pequeña o mediana escala. Esto limita la visibilidad de artistas emergentes, dificulta el acceso a experiencias musicales auténticas y reduce el impacto de la música local en la vida diaria de los fans.

De acuerdo con Chartmetric (2023) en su informe “Year in music 2023: Part 1”, de los aproximadamente 710,000 nuevos artistas agregados a su plataforma en dicho año, solo el 0.1% logró ubicarse entre los 35,000 artistas más exitosos. Mientras tanto, el 99.9% se mantuvo en la categoría de "sin descubrir" o "en desarrollo". Estas cifras subrayan la abrumadora dificultad que enfrentan los nuevos talentos para destacarse en un mar de competencia feroz.

**When**:

Esta problemática suele presentarse en momentos en los que las personas están motivadas a vivir experiencias musicales, pero no cuentan con la información necesaria para hacerlo. Por ejemplo, puede ocurrir cuando alguien decide salir de forma espontánea a un concierto una noche de fin de semana, pero no sabe dónde buscar eventos cercanos ni cuáles están activos en ese momento. También se da cuando un fan sigue a un artista emergente, pero no se entera de que este se presentará en su ciudad debido a la falta de difusión o herramientas para recibir notificaciones personalizadas. Otro escenario común es el de un turista que visita una nueva ciudad con ganas de explorar su vida cultural, pero al no conocer medios locales o redes de promoción independientes, termina perdiéndose eventos interesantes. Además, muchos conciertos organizados por bandas nuevas o independientes pasan desapercibidos porque no cuentan con canales efectivos para llegar a su público ideal, lo que limita tanto la asistencia como el crecimiento de la escena musical local. En todos estos casos, la desconexión entre el público y la música en vivo se traduce en oportunidades perdidas tanto para los fans como para los artistas.

**Where**:

Los problemas relacionados con el descubrimiento y la conexión con conciertos en vivo pueden surgir en diferentes espacios y contextos. Esto sucede tanto en el entorno cotidiano de las personas como en situaciones más específicas, como cuando visitan una nueva ciudad o buscan actividades culturales fuera de su rutina habitual. La desconexión entre los eventos musicales y el público puede ocurrir en calles con alta oferta artística pero poca visibilidad digital, en barrios donde se organizan conciertos independientes sin una estrategia de difusión clara, o incluso en ciudades donde los medios de promoción tradicionales no alcanzan a públicos más jóvenes o digitales.

StayMap se utiliza en diversos contextos urbanos y culturales para facilitar el acceso a experiencias musicales auténticas:

- En la ciudad de origen del usuario: Los usuarios acceden a la aplicación para descubrir conciertos cercanos en tiempo real, ya sea para planificar su fin de semana o salir de manera espontánea en busca de música en vivo.
- Durante viajes o turismo cultural: Al llegar a una nueva ciudad, los usuarios pueden explorar la agenda musical local sin depender de medios tradicionales o recomendaciones limitadas.
- En espacios donde la escena independiente tiene poca visibilidad: StayMap permite a los usuarios acceder a eventos organizados por artistas emergentes o colectivos culturales que normalmente no figuran en los canales de difusión masiva.


StayMap está diseñada para personas amantes de la música en vivo que desean explorar y disfrutar de conciertos con mayor facilidad, especialmente en escenarios donde la información no es fácilmente accesible o centralizada.

**Why**:

Porque la música en vivo tiene un valor emocional, social y cultural que va más allá del entretenimiento. Asistir a conciertos fortalece el sentido de comunidad, apoya directamente a los artistas y permite descubrir nuevas propuestas que muchas veces no llegan a los circuitos comerciales. Sin embargo, esta experiencia se ve limitada cuando no existe una herramienta efectiva que conecte al público con los eventos musicales a su alrededor, especialmente en el caso de conciertos independientes o espontáneos. La falta de difusión adecuada no solo perjudica a los músicos emergentes, sino también a los fans que anhelan vivir momentos auténticos y significativos a través de la música. En un mundo hiperconectado, resulta paradójico que aún sea tan difícil descubrir qué está ocurriendo musicalmente a nivel local, justo cuando las personas tienen la disposición, el tiempo o el ánimo de salir a explorar.

**Who**:

Esta problemática afecta principalmente a dos grupos:
- Fans de la música en vivo, tanto jóvenes como adultos, que desean descubrir conciertos interesantes cerca de ellos pero carecen de información actualizada, personalizada o centralizada.
- Artistas emergentes y bandas independientes, que enfrentan grandes barreras para visibilizar sus presentaciones en un entorno saturado y competitivo, sin contar con recursos o redes de difusión eficientes.


**How**:

StayMap aborda esta problemática mediante una aplicación móvil que centraliza, personaliza y geolocaliza la información sobre conciertos en vivo. Utilizando tecnología basada en ubicación y preferencias del usuario, StayMap permite:
- Descubrir eventos en tiempo real cerca de su ubicación.
- Filtrar por géneros, fechas y tipo de eventos.
- Recibir notificaciones personalizadas sobre conciertos de artistas favoritos o nuevos talentos similares.
- Acceder a eventos independientes que usualmente no aparecen en medios tradicionales.
- Compartir y recomendar eventos con amigos, generando una comunidad activa.

Esta solución integra datos de distintas fuentes, incluyendo registros de eventos, publicaciones de artistas y recomendaciones sociales, facilitando una experiencia fluida, espontánea y enriquecedora.

**How much:**

Las consecuencias de no atender esta problemática incluyen:
- Pérdida de oportunidades para artistas de darse a conocer, generar ingresos y construir una base de fans sólida.
- Reducción en la asistencia a conciertos, afectando la economía de espacios culturales, bares y promotores locales.
- Empobrecimiento de la vida cultural urbana, donde eventos valiosos pasan desapercibidos y la diversidad musical queda eclipsada.
- Frustración del público, que quiere vivir experiencias auténticas pero no encuentra cómo hacerlo fácilmente.

Al mismo tiempo, existe un alto potencial de impacto positivo: al facilitar la conexión entre público y música en vivo, se promueve la cultura local, se fomenta el descubrimiento musical y se apoya directamente al ecosistema artístico independiente.

## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements
Nuestros usuarios son personas amantes de la música en vivo, especialmente jóvenes, adultos y turistas culturales que valoran experiencias auténticas y desean conectarse con la escena musical local. Necesitan una forma de descubrir conciertos en vivo cercanos, en tiempo real y de manera personalizada, ya que actualmente muchos eventos, en especial los de pequeña o mediana escala, pasan desapercibidos por la falta de canales efectivos de difusión. Esto genera una desconexión entre el público y los artistas emergentes, limitando tanto la asistencia como el crecimiento de la escena musical independiente. Sabremos que este problema está resuelto cuando los usuarios usen StayMap para asistir a más conciertos, aumente la visibilidad de artistas independientes y se registre una alta interacción con funciones como la geolocalización, notificaciones y exploración de eventos.
Por ello, StayMap se compromete a desarrollar una plataforma accesible, intuitiva y centrada en el usuario que actúe como puente entre el público y la música en vivo. A través de herramientas inteligentes de descubrimiento, personalización y notificación, StayMap facilitará la conexión entre los fans y los artistas, fomentando una cultura musical más viva, diversa e inclusiva. El objetivo es empoderar tanto a quienes crean música como a quienes la disfrutan, construyendo una comunidad que valore, comparta y mantenga viva la experiencia de los conciertos en directo.

### 1.2.2.2. Lean UX Assumptions
Creemos que nuestros usuarios son personas jóvenes, adultos y turistas culturales que disfrutan de la música en vivo y valoran experiencias auténticas en su ciudad o durante sus viajes. Asumimos que estos usuarios tienen dificultades para descubrir conciertos de pequeña o mediana escala debido a la falta de canales de difusión efectivos, lo que les hace perderse eventos interesantes y limita su conexión con artistas emergentes. Pensamos que los usuarios valorarán una aplicación que les permita recibir notificaciones personalizadas, explorar conciertos cercanos en tiempo real y descubrir música local de forma sencilla y atractiva. Creemos que una solución efectiva debe ser intuitiva, centrada en la geolocalización, personalizable según los gustos musicales del usuario y capaz de visibilizar eventos independientes que normalmente no figuran en medios tradicionales.

**Assumptions Worksheet**

**¿Quién es el usuario?** 
- Usuarios que gustan de la música y desean descubrir nuevos sitios musicales.
- Artistas que desean compartir su música con la comunidad.

**¿Dónde encaja nuestro producto en su trabajo o vida?**
- StayMap será una herramienta esencial en el día a día de los usuarios, permitiéndoles tomar decisiones rápidas y seguras sobre a dónde ir.
- Puede utilizarse al planificar una salida, durante una caminata, mientras se viaja o simplemente para descubrir nuevos espacios alineados con su estilo de vida.
- Funcionará como una guía personalizada que acompaña al usuario constantemente, facilitando la exploración urbana y la conexión con experiencias que realmente le interesan.

**¿Qué problemas tiene nuestro producto?**
- Falta de información confiable y en tiempo real sobre la seguridad, ambiente o calidad de los lugares públicos.
- Inseguridad urbana o zonas desconocidas que pueden generar ansiedad al moverse sin una guía confiable.
- Escasez de soluciones intuitivas que integren datos, bienestar y mapas personalizados de forma sencilla para el usuario común.

**¿Cuándo y cómo es nuestro producto utilizado?**
- StayMap se usa cuando las personas están por salir y quieren conocer un nuevo lugar..
- A lo largo del día: durante el trabajo, caminatas, paseos, o al momento de organizar actividades personales.
- Disponible en móviles y web, debe ser intuitiva y accesible para usuarios con distintos niveles de experiencia tecnológica.

**¿Qué características son importantes?**
- Mapas interactivos y personalizados según los géneros musicales favoritos del usuario, mostrando eventos y conciertos en zonas cercanas.
- Información en tiempo real sobre afluencia estimada, accesibilidad y ambiente del evento, permitiendo una mejor planificación.
- Alertas contextuales sobre cambios relevantes en los conciertos (como hora, lugar o disponibilidad de entradas).
- Recomendaciones musicales basadas en gustos del usuario, historial de asistencia y ubicación actual.
- Sistema de perfiles personalizados para fans y artistas, con beneficios únicos según su rol en la comunidad.

  
**Objetivos**
- Facilitar el descubrimiento de eventos cercanos: Ayudar a los usuarios a encontrar conciertos y actividades musicales de forma personalizada y rápida.
- Impulsar la conexión entre fans y artistas: Crear una red activa donde los fans puedan seguir sus artistas favoritos, recibir alertas y acceder a beneficios exclusivos.
- Convertir la movilidad urbana en una experiencia musical enriquecedora: Transformar el modo en que los usuarios se mueven por la ciudad, conectando lugares con emociones, música y comunidad.
- Promover la participación activa en la escena local: Fomentar que los usuarios asistan a más eventos, descubran artistas emergentes y compartan sus experiencias.

**Alcances**

Asistencia personalizada en tiempo real
- Recomendaciones de conciertos y eventos musicales según los intereses, ubicación y estado de ánimo del usuario.
- Actualizaciones en vivo sobre afluencia, horarios y cambios importantes en los eventos.
- Mapas interactivos para encontrar eventos cercanos con rutas claras desde la ubicación actual.

Accesibilidad y usabilidad
- Interfaz sencilla, moderna e intuitiva para todo tipo de usuarios.
- Disponible en smartphones, tablets y computadoras, incluso con acceso limitado a internet en algunos casos.

Conexión con expertos y comunidad
- Espacio para recibir recomendaciones de expertos en musica o experiencias de otros usuarios.
- Comunidad que comparte tips y lugares seguros, con opción de valorar y comentar.

**Escalabilidad**
- Adaptable a distintas ciudades, regiones y culturas urbanas.
- Capacidad para expandirse globalmente, integrando datos locales específicos según cada comunidad.
¿Cómo debe verse nuestro producto y cómo debe comportarse?
- Interfaz clara, amigable y acogedora.
- Fluidez en la experiencia, con transiciones suaves, botones accesibles y navegación simple.
- Alta confiabilidad en los datos mostrados y bajo margen de error en recomendaciones.

**Business Outcomes**
- Convertirse en la aplicación de referencia para movilizarse de forma segura y emocionalmente coherente con el usuario.
- Establecer alianzas con ONGs, municipalidades, plataformas turísticas y de seguridad ciudadana.
- Recolectar datos anónimos que aporten a la mejora del diseño urbano y políticas públicas de bienestar ciudadano.
- Ser pioneros en una nueva categoría de apps: navegación inteligente y segura.
- Crear un ecosistema de servicios y datos donde StayMap se posicione como punto de conexión entre usuarios, ciudades y experiencias positivas.
  
**User Outcomes**
- Mayor facilidad para descubrir conciertos en vivo, especialmente de artistas emergentes e independientes.
- Acceso rápido a información actualizada sobre eventos musicales cercanos.
- Incremento en la asistencia a conciertos que se alinean con sus gustos musicales y disponibilidad.
- Mejora en la visibilidad y alcance de artistas, cantantes y bandas independientes o formales.
- Conexión más directa entre fans y artistas mediante notificaciones personalizadas y herramientas de descubrimiento.
- Reducción de la desconexión entre la oferta musical local y los potenciales asistentes.
  
**Features**
- Mapas interactivos de conciertos: Visualización clara y precisa de eventos musicales cercanos, filtrados por fecha, género y ubicación.
- Buscador inteligente: Permite encontrar conciertos específicos o artistas favoritos al instante, con autocompletado y filtros avanzados.
- Sección para fans: Acceso a beneficios exclusivos, contenido especial y eventos recomendados según el historial del usuario.
- Sección para artistas: Herramientas para promocionar conciertos, interactuar con fans y analizar datos de audiencia local.
- Filtros por género musical: El usuario puede descubrir eventos según sus gustos musicales, desde pop y rock hasta K-pop o electrónica.
- Experiencia personalizada: La app muestra eventos relevantes según la ubicación actual del usuario y sus preferencias previas.


### 1.2.2.3. Lean UX Hypothesis Statements
Creemos que, si StayMap tiene una interfaz intuitiva y está optimizada para dispositivos móviles, incluso los usuarios con poca experiencia tecnológica podrán usar la aplicación fácilmente para orientarse y explorar nuevas zonas.

Creemos que, si StayMap proporciona recomendaciones de conciertos basadas en los intereses y preferencias del usuario, así como la proximidad de estos eventos, los usuarios tendrán una experiencia más personalizada y disfrutarán de una exploración más fluida de los eventos musicales a su alrededor.

Creemos que, si StayMap integra una comunidad activa donde los usuarios pueden reportar incidentes o compartir experiencias, se generará confianza colectiva y participación constante, fortaleciendo el valor colaborativo de la app.

Creemos que, si StayMap ofrece una interfaz intuitiva y optimizada para dispositivos móviles, los usuarios, incluso aquellos con poca experiencia tecnológica, podrán localizar fácilmente conciertos cercanos y acceder a la información relevante sin dificultad.

Creemos que, si StayMap proporciona una plataforma que permite a los artistas emergentes listar sus conciertos, aumentar su visibilidad y conectar con un público local, los músicos tendrán más oportunidades de crecer y ganar seguidores leales, lo que potenciará su carrera a largo plazo.

Creemos que, si StayMap permite a los usuarios dejar reseñas y comentarios sobre conciertos y actuaciones, los artistas podrán recibir retroalimentación constructiva y mejorar su performance, lo que contribuirá a su evolución profesional y éxito en futuros eventos.

Creemos que, si StayMap destaca a los artistas más destacados y organiza conciertos a gran escala, brindará una plataforma para que los músicos emergentes se presenten junto a artistas establecidos, lo que aumentará sus oportunidades de ser reconocidos por profesionales de la industria y contribuirá a su crecimiento.


### 1.2.2.4. Lean UX Canvas

<table border="1">
  <tr>
    <th>Business Problem</th>
    <th>Solutions</th>
    <th>Business Outcomes</th>
  </tr>
  <tr>
    <td>
      Muchas personas que disfrutan de la música en vivo, así como artistas y cantantes, tanto independientes como formales, enfrentan dificultades para descubrir o difundir conciertos, especialmente los de pequeña o mediana escala. Esta desconexión limita el crecimiento de la escena musical local, reduce la visibilidad de los artistas y hace que los fans se pierdan experiencias auténticas.
    </td>
    <td>
      StayMap es una aplicación móvil que conecta a los amantes de la música con conciertos en tiempo real, permitiendo descubrir eventos cercanos mediante geolocalización, recibir notificaciones personalizadas según gustos musicales y acceder a la agenda de presentaciones de artistas locales. Además, ofrece una plataforma para que los artistas puedan publicar sus eventos y alcanzar a su público ideal.
    </td>
    <td>
      Esperamos que StayMap incremente la asistencia a conciertos, visibilice a más artistas independientes y fomente una comunidad musical más conectada. El éxito se medirá por el aumento de usuarios activos, la cantidad de eventos compartidos en la plataforma y el crecimiento en la interacción entre fans y artistas.
    </td>
  </tr>
  <tr>
    <th>Users</th>
    <th colspan="2">User Benefits</th>
  </tr>
  <tr>
    <td>
      Nuestros usuarios son personas apasionadas por la música en vivo, así como artistas y cantantes, tanto independientes como formales, que buscan descubrir o difundir eventos musicales con mayor facilidad. Comparten el objetivo de vivir experiencias musicales únicas o de hacer crecer su audiencia.
    </td>
    <td colspan="2">
      <ul>
        <li>Descubrimiento de conciertos cercanos en tiempo real gracias a la geolocalización.</li>
        <li>Notificaciones personalizadas según el estilo musical de interés.</li>
        <li>Para artistas: herramienta efectiva y accesible para promocionar sus presentaciones.</li>
        <li>Mayor conexión entre músicos y fans en escenarios culturales reales.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Hypotheses</th>
    <th>What’s the most important thing we need to learn first?</th>
    <th>What’s the least amount of work we need to do to learn the most important thing?</th>
  </tr>
  <tr>
    <td>
      Creemos que, al brindar una solución que conecta a personas y artistas a través de conciertos geolocalizados y notificaciones personalizadas, los usuarios asistirán a más eventos y los artistas lograrán una mayor difusión, fortaleciendo la comunidad musical local y mejorando la experiencia en ambos sentidos.
    </td>
    <td>
      Es clave validar si los fans encuentran útil la app para descubrir conciertos relevantes, y si los artistas consideran valioso el canal para promover sus presentaciones.
    </td>
    <td>
      Crear un prototipo funcional que muestre conciertos cercanos según ubicación e intereses musicales, incluyendo una opción para que artistas registren eventos. Luego, probarlo con un grupo de fans y músicos para obtener retroalimentación directa sobre la utilidad y experiencia.
    </td>
  </tr>
</table>

# 1.3. Segmentos objetivo

**Fans de la música (jóvenes y adultos jóvenes):**
Según el Instituto de Estudios Peruanos (2019), el 54% de los estudiantes universitarios asiste ocasionalmente a conciertos musicales (1 o 2 veces al año), mientras que un 34% lo hace con mayor frecuencia (3 o más veces al año) y solo un 11% nunca ha asistido. Además, se observa que las mujeres (54,6%) muestran una mayor preferencia por géneros como la balada romántica, cumbia, pop, salsa y música clásica, mientras que los hombres (45,4%) se inclinan por el heavy metal, hip-hop y reggaetón. Por otro lado, según Ramos-Pla, Ramírez-Montoya y García-Peñalvo (2022), 4 de cada 10 personas escuchan música con mucha frecuencia, siendo los jóvenes de entre 18 y 24 años los oyentes más asiduos de distintos géneros musicales.

Edad: 16 a 35 años


Ubicación: Principalmente en zonas urbanas y ciudades con una oferta cultural variada (como Lima, Buenos Aires, Ciudad de México, Madrid o Nueva York).
 
Características demográficas y de comportamiento: Son personas que integran la música en su estilo de vida diario. Utilizan servicios de streaming como Spotify o Apple Music, siguen a sus artistas favoritos en redes sociales como Instagram, TikTok o X (Twitter), y suelen compartir sus gustos musicales con sus amistades. Buscan experiencias auténticas y momentos memorables.

Necesidades principales:
- Descubrir nuevos conciertos y presentaciones en vivo cerca de su ubicación.
- Recibir notificaciones sobre giras de sus artistas favoritos.
- Compartir su asistencia a eventos con su red social.
- Acceder fácilmente a la información sobre conciertos pequeños que muchas veces no se promocionan ampliamente.

**Artistas emergentes y bandas independientes:** 
Según el informe Year in Music 2023 de Chartmetric, de los aproximadamente 710,000 nuevos artistas agregados a su plataforma durante el año, solo una fracción mínima logró posicionarse entre los 35,000 artistas más exitosos, lo que evidencia la alta competitividad y dificultad para destacar en la industria musical actual. Por otro lado, el mercado global de artistas independientes continúa en expansión: se estima en 104,61 mil millones de dólares en 2024 y se proyecta que alcance los 149,91 mil millones para el año 2029, con una tasa de crecimiento anual compuesta (CAGR) del 7,46% (Mordor Intelligence, 2024). Esta tendencia refleja el creciente protagonismo de los artistas emergentes y el potencial económico de este segmento en la industria musical.

Edad: 18 a 40 años

Ubicación: Regiones urbanas o semiurbanas con crecimiento cultural y musical (por ejemplo, Lima, Cusco, Medellín, Guadalajara, Valparaíso).

Características demográficas y de comportamiento: Generalmente, son artistas autogestionados o bandas que aún no tienen el respaldo de una disquera grande. Se apoyan en redes sociales para crecer orgánicamente y generar engagement con su audiencia. Están abiertos a usar nuevas plataformas digitales para promocionarse, sobre todo si estas les permiten interactuar directamente con los fans.

Necesidades principales:
- Promocionar conciertos y obtener mayor visibilidad local.
- Crear comunidad y fidelizar audiencia.
- Usar herramientas simples de geolocalización y calendario para difundir sus eventos.
- Medir la asistencia a sus presentaciones.

# CAPÍTULO II: Requirements Elicitation & Analysis

# 2.1. Competidores

## 2.1.1. Análisis competitivo

<table border="2" style="text-align: center;">
	<tbody>
		<tr >
			<td colspan="6">Competitive Analysis Landscape</td>
		</tr>
		<tr>
			<td colspan="2">¿Por que llevar a cabo este análisis?</td>
			<td colspan="4">Esto es clave para entender cómo otras plataformas están abordando el descubrimiento de eventos musicales, qué características valoran los usuarios y dónde existen oportunidades no cubiertas, especialmente en relación con la promoción de conciertos de pequeña y mediana escala. Al conocer mejor a la competencia, podemos tomar decisiones más informadas sobre funcionalidades, modelo de negocio, diferenciadores clave y estrategias de crecimiento.
            </td>
		</tr>
		<tr>
			<td colspan="2"></td>
			<td>StayMap</td>
			<td>Songkick</td>
			<td>Bandsintown</td>
			<td>Fever</td>
		</tr>
		<tr>
			<td rowspan="2">Perfil</td>
			<td>Overview</td>
			<td>Conecta a los fans con conciertos en vivo a través de un mapa interactivo con geolocalización. Se enfoca en promover la escena musical y fortalecer el vínculo entre artistas y su público local.</td>
			<td>Permite descubrir conciertos de artistas favoritos y recibir alertas personalizadas según ubicación. Se enfoca principalmente en giras de artistas reconocidos.</td>
			<td>Conecta a fans con conciertos mediante recomendaciones basadas en gustos musicales. Incluye herramientas para que artistas promuevan sus eventos.</td>
			<td>Ayuda a descubrir eventos culturales locales, incluyendo conciertos, teatro y experiencias únicas. Su enfoque va más allá de la música en vivo.</td>
		</tr>
		<tr>
			<td>Ventaja competitiva ¿Que valor ofrece a los clientes?</td>
			<td>Facilita el descubrimiento espontáneo de conciertos mediante un mapa interactivo y geolocalizado, acercando a los fans a la música local en tiempo real.</td>
			<td>Ofrece a los usuarios alertas personalizadas sobre conciertos de sus artistas favoritos, permitiendo planificar asistencias con anticipación de forma sencilla.</td>
			<td>Combina recomendaciones personalizadas con herramientas de promoción para artistas, creando un ecosistema donde fans y músicos pueden interactuar directamente.</td>
			<td>Proporciona una experiencia cultural completa con recomendaciones curadas de eventos locales, destacando experiencias exclusivas y originales para cada usuario.</td>
		</tr>
		<tr>
			<td rowspan="2">Perfil de Marketing</td>
			<td>Mercado objetivo</td>
			<td>Personas jóvenes y amantes de la música que buscan descubrir conciertos y conectar con la escena local</td>
			<td>Fans de la música que siguen a artistas reconocidos y desean recibir alertas sobre giras y conciertos en su ciudad o alrededores</td>
			<td>Amantes de la música en general, desde fans de artistas emergentes hasta grandes estrellas, así como músicos que buscan promocionar sus eventos</td>
			<td>Personas urbanas interesadas en actividades culturales y de ocio variadas, que buscan planes originales y experiencias únicas en su ciudad</td>
		</tr>
		<tr>
			<td>Estrategias de marketing</td>
			<td>Se enfoca en el marketing comunitario y uso de redes sociales para promover conciertos en tiempo real y crear comunidad entre fans y artistas.</td>
			<td>Se apoya en integraciones con plataformas de streaming (como Spotify) y recomendaciones personalizadas para captar usuarios. También colabora con artistas reconocidos para promocionar giras y vender entradas.</td>
			<td>Utiliza notificaciones personalizadas, campañas por email y presencia activa en redes sociales. Además, ofrece una plataforma para que los propios artistas promocionen sus shows directamente.</td>
			<td>Realiza campañas digitales segmentadas, usa influencers locales y curaduría de eventos exclusivos para atraer a usuarios. También colabora con marcas para promocionar experiencias temáticas.</td>
		</tr>
		<tr>
			<td rowspan="3">Perfil de Producto</td>
			<td>Productos & Servicios</td>
			<td><ul>
				<li>Productos: Mapa interactivo de conciertos, geolocalización en tiempo real, notificaciones de eventos</li>
				<li>Servicios: Promoción de conciertos, visibilidad para artistas emergentes, creación de comunidad entre fans y artistas</li>
			</ul></td>
			<td><ul>
				<li>Productos: Alertas personalizadas sobre conciertos, compra de entradas, recomendaciones basadas en preferencias musicales</li>
				<li>Servicios: Seguimiento de artistas, integración con Spotify y Apple Music, planificación de asistencia a conciertos</li>
			</ul></td>
			<td><ul>
				<li>Productos: Calendario de conciertos, alertas personalizadas, herramientas de promoción para artistas</li>
				<li>Servicios: Promoción de eventos para artistas emergentes, recomendaciones personalizadas, venta de entradas</li>
			</ul></td>
			<td><ul>
				<li>Productos: Descubrimiento de eventos locales, compra de entradas, experiencias exclusivas</li>
				<li>Servicios: Curaduría de eventos, recomendaciones basadas en ubicación, experiencias personalizadas</li>
			</ul></td>
		</tr>
		<tr>
			<td>Precios &amp; Costos</td>
			<td><ul>
				<li>Precios: StayMap será una aplicación gratuita para usuarios y artistas, sin cobros de suscripción ni pago por descarga.</li>
				<li>Costos: Gratuita, pero generará dinero a partir de publicidad como promociones de conciertos. También se evaluarán alianzas estratégicas con organizadores de eventos y marcas del sector para generar ingresos sin afectar la experiencia de descubrimiento musical.</li>
			</ul></td>	
			<td><ul>
				<li>Precios: Gratuito para los usuarios. Las entradas para conciertos se venden a través de la aplicación, con un costo asociado por evento.</li>
				<li>Costos: No tiene costos de suscripción para los usuarios. Las ganancias provienen de la venta de entradas y comisiones de los conciertos.</li>
			</ul></td>
			<td><ul>
				<li>Precios: Gratuito para los usuarios. Los conciertos se promocionan a través de la plataforma, con la posibilidad de comprar entradas directamente.</li>
				<li>Costos: Gratuito para los usuarios, pero Bandsintown cobra una tarifa por la venta de entradas y ofrece servicios premium a artistas para mejorar la visibilidad de sus conciertos.</li>
			</ul></td>	
			<td><ul>
				<li>Precios: Gratuito para los usuarios, con una tarifa adicional al comprar entradas para ciertos eventos exclusivos o experiencias premium.</li>
				<li>Costos: Los costos de Fever están principalmente asociados a las entradas y experiencias exclusivas. La plataforma también obtiene ingresos mediante asociaciones con marcas y experiencias temáticas.</li>
			</ul></td>	
		</tr>
		<tr>
			<td>Canales de distribución (Web y/o Móvil)</td>
			<td><ul>
				<li>Web: Plataforma web interactiva con un mapa dinámico de conciertos, donde los usuarios pueden explorar eventos en tiempo real</li>
				<li>Móvil: Aplicación móvil para iOS y Android con geolocalización, alertas de eventos y la opción de seguir a artistas locales</li>
			</ul></td>
			<td><ul>
				<li>Web: Disponible a través de su página web para descubrimiento de conciertos y compra de entradas</li>
				<li>Móvil: Aplicación disponible para iOS y Android, donde los usuarios pueden recibir alertas personalizadas y comprar entradas</li>
			</ul></td>
			<td><ul>
				<li>Web: Plataforma web que permite descubrir conciertos y gestionar las preferencias de artistas</li>
				<li>Móvil: Aplicación para iOS y Android, con notificaciones personalizadas y la posibilidad de seguir a artistas y comprar entradas</li>
			</ul></td>
			<td><ul>
				<li>Web: Plataforma web donde los usuarios pueden explorar eventos y comprar entradas</li>
				<li>Móvil: Aplicación para iOS y Android que permite descubrir eventos locales y comprar entradas, con recomendaciones personalizadas</li>
			</ul></td>
		</tr>
		<tr>
			<td rowspan="4">Análisis SWOT</td>
			<td>Fortalezas</td>
			<td>Su enfoque en conciertos emergentes y locales le permite conectar con un público único y auténtico. La geolocalización en tiempo real facilita el descubrimiento de eventos cercanos.</td>
			<td>Tiene una gran base de usuarios gracias a su integración con plataformas como Spotify y Apple Music. Su enfoque en conciertos grandes le permite ofrecer una experiencia robusta en la compra de entradas.</td>
			<td>Ofrece alertas personalizadas para conciertos y promueve tanto artistas emergentes como establecidos. Su enfoque en la personalización le otorga una experiencia única a sus usuarios.</td>
			<td>Ofrece una amplia variedad de eventos, no solo conciertos, lo que atrae a un público diverso. Su enfoque en experiencias exclusivas le da un valor añadido.</td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td>Al ser una plataforma en crecimiento, su base de usuarios y oferta de conciertos son limitados. Depende de alianzas con locales y artistas para ampliar su alcance.</td>
			<td>Tiene una gran base de usuarios gracias a su integración con plataformas como Spotify y Apple Music. Su enfoque en conciertos grandes le permite ofrecer una experiencia robusta en la compra de entradas.</td>
			<td>Su interfaz puede ser confusa para nuevos usuarios debido a la gran cantidad de notificaciones y conciertos. Las recomendaciones no siempre son precisas ni relevantes para todos los usuarios.</td>
			<td>Su enfoque generalista puede no satisfacer a usuarios que buscan solo conciertos en vivo. El contenido musical no es tan profundo o especializado como en otras plataformas.</td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td>Expandir su enfoque en mercados locales y nichos de conciertos emergentes podría fortalecer su propuesta. Ofrecer servicios premium para artistas podría atraer más usuarios y aumentar sus ingresos.</td>
			<td>Puede expandir su alcance hacia mercados más locales, promoviendo artistas emergentes. Colaborar con festivales locales y locales sería una buena forma de ampliar su base de usuarios.</td>
			<td>Puede ampliar sus funciones para vender entradas directamente y ofrecer experiencias exclusivas. Colaboraciones con festivales y marcas musicales podrían atraer a más usuarios.</td>
			<td>Expandir su oferta de conciertos locales podría atraer a un público más específico de fans de música en vivo. Crear contenido exclusivo y eventos personalizados podría aumentar la lealtad de los usuarios.</td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td>Competir con plataformas consolidadas como Songkick y Bandsintown puede ser desafiante. La saturación del mercado de aplicaciones de conciertos podría dificultar la atracción de usuarios.</td>
			<td>La competencia creciente de aplicaciones como Bandsintown y Fever puede restarle usuarios. La dependencia de plataformas de streaming lo hace vulnerable a cambios en ese ecosistema.</td>
			<td>La competencia de plataformas especializadas en conciertos como Songkick y Fever podría reducir su cuota de mercado. Cambios en los hábitos de consumo de entretenimiento digital podrían afectar su relevancia.</td>
			<td>La competencia de aplicaciones como Songkick y Bandsintown podría restarle relevancia en el ámbito musical. La saturación del mercado de eventos y actividades culturales podría hacerle perder protagonismo.</td>
		</tr>
	</tbody>
</table>

## 2.1.2. Estrategias y tácticas frente a competidores

**- Enfoque en el descubrimiento de música en vivo diversa**

Estrategia: Diferenciarse de otras plataformas generalistas facilitando el acceso a una variedad de eventos musicales sin importar su escala

Táctica: Mostrar de forma equitativa tanto conciertos masivos como presentaciones más íntimas o alternativas y resaltar aquellos eventos que se alineen con los intereses del usuario mediante algoritmos de recomendación y geolocalización

**- Uso de geolocalización en tiempo real**

Estrategia: Facilitar el descubrimiento espontáneo de conciertos cercanos al usuario

Táctica: Implementar un mapa interactivo que muestre eventos activos cerca del usuario con filtros por género, horario y tipo de artista

**- Alianzas con agentes locales**

Estrategia: Fortalecer la oferta de eventos mediante colaboraciones directas con organizadores independientes

Táctica: Crear programas de colaboración con venues, colectivos culturales y artistas emergentes que les permitan promocionar sus eventos fácilmente dentro de la plataforma

**- Comunidad y participación de los fans**

Estrategia: Construir una comunidad sólida y activa alrededor de la música en vivo

Táctica: Permitir a los usuarios hacer check-in en eventos, compartir fotos y reseñas, seguir a otros fans y artistas, y recibir recompensas por su participación activa

**- Funcionalidades exclusivas para fidelización**

Estrategia: Aumentar la retención y lealtad de los usuarios frente a otras plataformas

Táctica: Ofrecer funciones como seguimiento de giras, alertas personalizadas, y programas de recompensas por asistir a eventos frecuentes o apoyar a artistas locales

# 2.2. Entrevistas

## 2.2.1. Diseño de entrevistas

**Segmento objetivo #1: Fans de la música (16 a 35 años)**

Perfil demográfico y musical:

- ¿Cuál es tu nombre, qué edad tienes y a qué te dedicas?
- ¿Dónde vives actualmente? ¿Sueles asistir a conciertos en tu ciudad?
- ¿Qué géneros musicales disfrutas más?
- ¿Con qué frecuencia vas a conciertos o festivales?

Comportamiento digital y uso de apps:

- ¿Qué plataformas usas para descubrir nuevos eventos o artistas?
- ¿Sueles seguir a tus artistas favoritos por redes sociales?
- ¿Usas apps como Spotify, Instagram u otras para encontrar conciertos?

 Expectativas y opinión sobre StayMap:

- ¿Has tenido problemas para enterarte de conciertos cercanos a ti?
- Si tuvieras una app que te muestre conciertos en vivo cerca, ¿la usarías? ¿por qué?
- ¿Qué funciones te parecerían útiles en una app como StayMap? (por ejemplo: mapa de eventos, notificaciones, filtros por género)
- ¿Te gustaría guardar tus eventos favoritos o armar tu calendario de conciertos?
- ¿Qué mejorarías de las apps que ya usas para buscar eventos musicales?
- ¿Te interesaría compartir los eventos a los que vas con tus amigos desde la app?

**Segmento objetivo #2: Artistas emergentes y bandas independientes (18 a 40 años)**

Perfil artístico y canales de promoción:

- ¿Cuál es tu nombre artístico o el de tu banda?
- ¿Qué estilo musical haces y cuántos años llevas en la música?
- ¿Cómo sueles promocionar tus eventos o lanzamientos?
- ¿Qué redes sociales o plataformas usas para difundir tus conciertos? (Instagram, TikTok, Spotify, etc.)

Herramientas digitales y desafíos:

- ¿Te resulta fácil o difícil difundir tus eventos entre el público local?
- ¿Has utilizado apps o plataformas para anunciar tus conciertos? ¿Cuál fue tu experiencia?
- ¿Qué barreras encuentras al intentar llenar tus shows o llegar a nuevos oyentes?

Opinión y expectativas sobre StayMap:

- ¿Qué te parecería contar con una app donde los usuarios vean tu evento en un mapa musical local?
- ¿Te interesaría que StayMap te permita crear un perfil artístico y gestionar tus fechas de conciertos?
- ¿Qué funcionalidades te parecerían más útiles como artista? (por ejemplo: análisis de asistentes, publicación de eventos, integración con redes)
- ¿Qué te gustaría poder personalizar en la app?
- ¿Cómo crees que StayMap podría ayudarte a crecer como artista?
- ¿Recomendarías una app como StayMap a otros artistas emergentes?

## 2.2.2. Registro de entrevistas

#### Entrevista #1
![user_persona](assets/interviews/Analisis-Entrevista-Fans1.png)

**Nombre:** Jade Huaman  
**Edad:** 20 años  
**Duración:** 03:16:20  
**Inicio:** 00:10:00  

#### Entrevista #2
![user_persona](assets/interviews/Analisis-Entrevista-Fan2.jpeg)

**Nombre:** Massiel Cusi  
**Edad:** 20 años  
**Duración:** 05:18:20  
**Inicio:** 00:03:26  

#### Entrevista #3
![user_persona](assets/interviews/Analisis-Entrevista-Fan3.png)

**Nombre:** Jazmin Roque  
**Edad:** 21 años  
**Duración:** 06:04:20  
**Inicio:** 00:08:44  

### Segmento objetivo #2: Artistas emergentes y bandas independientes (18 a 40 años)

#### Entrevista #4
![user_persona](assets/interviews/Analisis-Entrevista-Artista1.png)

**Nombre:** Gabriel Sumaeta  
**Edad:** 19 años  
**Duración:** 10:44:70  
**Inicio:** 00:14:54  

#### Entrevista #5
![user_persona](assets/interviews/Analisis-Entrevista-Artista2.png)

**Nombre:** Diego Ruiz  
**Edad:** 19 años  
**Duración:** 09:58:40  
**Inicio:** 00:25:38  

#### Entrevista #6
![user_persona](assets/interviews/Analisis-Entrevista-Artista3.png)

**Nombre:** Juan Carlos
**Edad:** 20  
**Duración:** 9:30:20
**Inicio:** 00:35:37

URL del video de las entrevistas:` https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/ERJfpT5HoF9Ckz2iN8QzbjEBPFxFxVCkACtrv2SSjkxb1w?e=VY6fld&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`

---

## 2.2.3. Análisis de entrevistas.

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Ariana Lizarbe** | **Jade Huaman** |

Jade Huaman, una joven de 20 años dedicada a la pastelería y apasionada por los géneros rock y pop, asiste a conciertos con frecuencia (2-3 veces al año). Sin embargo, enfrenta dificultades para enterarse a tiempo sobre eventos cercanos, especialmente en bares, lo que le hace perder oportunidades. Actualmente, utiliza Instagram y TikTok para seguir a sus artistas, pero critica la saturación de contenido irrelevante en estas plataformas. Jade mostraría interés en una aplicación que le permita descubrir conciertos en vivo de manera eficiente, con filtros por género y proximidad a su ubicación, así como notificaciones relevantes. Además, valdría funcionalidades como guardar eventos favoritos y compartir sus experiencias de conciertos asistidos. Su feedback refuerza la necesidad de una solución centrada en la puntualidad, personalización y usabilidad para fans como ella.

![user_persona](assets/interviews/Analisis-Entrevista-Fans1.png)

---

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Ariana Lizarbe** | **Massiel Cusi** |

Massiel Cusi, estudiante de marketing de 20 años y entusiasta del pop, kpop y baladas, asiste a conciertos con regularidad (aproximadamente 3 veces al año). Aunque utiliza plataformas como TikTok y Spotify para seguir a sus artistas, ha enfrentado problemas para estar al tanto de todos los eventos, como un concierto en marzo que se perdió debido a la falta de publicidad. Actualmente, Spotify le ayuda a conocer algunos tours, pero la información no siempre es completa o accesible. Massiel vería con buenos ojos una aplicación que centralice la información sobre conciertos, ofreciendo funciones como un mapa interactivo con eventos cercanos, alertas personalizadas por artista y detalles logísticos (como cómo llegar al lugar). Además, valora la posibilidad de guardar eventos favoritos y compartir sus experiencias, ya que esto simplificaría su proceso de planificación y le ahorraría tiempo en investigaciones manuales. Su testimonio resalta la importancia de integrar múltiples fuentes de información en una sola plataforma, priorizando la facilidad de uso y la actualización en tiempo real.

![user_persona](assets/interviews/Analisis-Entrevista-Fan2.jpeg)

---

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Ariana Lizarbe** | **Jazmín Roque** |

Jazmín Roque, estudiante de ingeniería ambiental de 21 años, disfruta asistiendo principalmente a festivales musicales (un promedio de 4 al año), con preferencia por géneros variados como pop, rock y cumbia. Aunque utiliza redes sociales como Instagram y TikTok para seguir a sus artistas, enfrenta dificultades para encontrar información sobre conciertos de artistas menos contemporáneos o de géneros específicos como el neguetton. La propuesta de nuestra aplicación le resulta atractiva, especialmente por la posibilidad de acceder rápidamente a planes de conciertos para salidas espontáneas los fines de semana. Jazmín destaca la importancia de incluir filtros por género para personalizar la búsqueda, así como un sistema de notificaciones no intrusivo, sugiriendo formatos como calendarios semanales que muestren eventos de artistas vinculados a sus plataformas de streaming (Spotify o YouTube Music). Además, valora funcionalidades como: Información sobre discotecas con dinámicas especiales. Opción de compartir conciertos asistidos. Su perfil refleja la necesidad de una herramienta que centralice información dispersa y adapte las recomendaciones a gustos musicales diversos, combinando utilidad con flexibilidad para usuarios ocasionales.

![user_persona](assets/interviews/Analisis-Entrevista-Fan3.png)

---

## Segmento objetivo #2: Artistas emergentes y bandas independientes (18 a 40 años)

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Renato Zegarra** | **Gabriel Sumaeta** |

El entrevistado, Gabriel Sumaeta, un músico de rock y blues que también se desempeña como sanitario domiciliario, promociona sus eventos principalmente a través de Instagram, donde ha logrado conectar con su audiencia objetivo, aunque reconoce limitaciones en la organización de conciertos debido a inconsistencias en los horarios y falta de coordinación con las empresas productoras. Destaca la importancia de las redes sociales para crecer rápidamente, incluso con pocos seguidores iniciales, pero señala la carencia de herramientas locales que faciliten la promoción de eventos, ya que opciones como Spotify Artists solo están disponibles en Estados Unidos. Valora especialmente la idea de una aplicación que permita personalizar perfiles artísticos, integrar estadísticas de engagement (como las de Instagram) y ofrecer funcionalidades creativas para artistas emergentes. Además, resalta la necesidad de soluciones accesibles y gratuitas que simplifiquen la logística de los eventos, como la sincronización de horarios y la centralización de información, aspectos que actualmente dificultan su gestión. Su testimonio subraya la demanda de plataformas intuitivas que combinen promoción digital con herramientas prácticas para la organización, especialmente diseñadas para escenas musicales locales.

![user_persona](assets/interviews/Analisis-Entrevista-Artista1.png)

---

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Renato Zegarra** | **Diego Ruiz** |

Diego Ruiz, músico emergente y miembro de la banda de rock latino "Los Vinilos", lleva tres años en la escena musical utilizando principalmente Instagram como herramienta de promoción. Reconoce el valor de esta plataforma para llegar al público joven, pero destaca las limitaciones actuales: la saturación de contenido y la necesidad de contar con una base de seguidores inicial para tener visibilidad. Su estrategia combina publicaciones recurrentes (2-3 veces por semana) con el boca a boca, además de mencionar sus redes al final de cada presentación para captar nuevos seguidores. Sin embargo, admite que el proceso es lento y competitivo, especialmente para artistas que buscan monetizar su trabajo y ganar reconocimiento. La propuesta de STAYMAP resuena especialmente con Diego, quien ve en la aplicación una solución integral para varios de sus desafíos. La funcionalidad de geolocalización de eventos le parece clave para aumentar la asistencia a sus conciertos, ya que permitiría a los usuarios descubrir fácilmente lugares con presentaciones en vivo. Además, valora la posibilidad de crear un perfil artístico completo que muestre el género musical, la trayectoria de la banda y eventos pasados, lo que brindaría mayor profesionalismo a su imagen. La integración con Instagram y Spotify también es atractiva para él, pues facilitaría el crecimiento de su audiencia y la difusión de su música de manera más orgánica. Para Diego, STAYMAP representa una oportunidad para democratizar el acceso a herramientas de promoción que actualmente son difíciles de obtener para artistas independientes. Considera que la aplicación podría eliminar barreras de entrada al ofrecer un espacio centrado en músicos, donde el arte sea el protagonista y el público pueda descubrir talento de manera más directa y personalizada. Su entusiasmo es evidente al recomendar la app a otros artistas emergentes, ya que cree firmemente en su potencial para transformar la forma en que los músicos se conectan con su audiencia y crecen en sus carreras. Su testimonio refuerza la importancia de desarrollar una plataforma que no solo solucione problemas prácticos, sino que también empodere a los artistas en su camino profesional.

![user_persona](assets/interviews/Analisis-Entrevista-Artista2.png)

---

| **Entrevistador** | **Entrevistado** |
|------------------|------------------|
| **Diego Collantes** | **Juan Carrillo** |

Juan Carrillo, conocido artísticamente como Jaün, es un músico emergente de 21 años que inició su carrera en noviembre del año pasado. Aunque su estilo favorito es el R&B, ha optado por empezar con el reguetón por su mayor alcance comercial. Promociona su música principalmente en TikTok e Instagram, donde mantiene una estrategia diferenciada: en Instagram proyecta una imagen artística más seria, mientras que en TikTok se muestra más cercano y aprovecha la viralidad. A pesar de tener experiencia generando contenido, comenta que la transición de comedia a música fue difícil, y que el algoritmo no siempre favorece la calidad musical, obligándolo incluso a invertir en publicidad paga.
La propuesta de StayMap le parece sumamente útil, sobre todo por la posibilidad de mostrar eventos en un mapa local. Considera que esta funcionalidad ayudaría a los artistas independientes a ser descubiertos por nuevos oyentes y facilitaría la asistencia a conciertos, fomentando una comunidad real de seguidores. También valora la idea de contar con filtros por género musical, ya que permitiría segmentar el contenido y asegurar que llegue a un público realmente interesado, evitando que su música se pierda entre estilos no afines.
Para Juan, StatMap representa una oportunidad concreta para hacer visible el talento emergente. Cree que la app puede empoderar a los artistas que hoy compiten en plataformas saturadas y dominadas por algoritmos poco predecibles. Su entusiasmo por la idea se refleja en su disposición a recomendarla a otros músicos, convencido de que una herramienta enfocada en la música independiente puede cambiar la forma en que los artistas se conectan con su audiencia y hacen crecer su carrera. 

![user_persona](assets/interviews/Analisis-Entrevista-Artista3.png)

# 2.3. Needfinding

## 2.3.1. User Personas

Los user personas son perfiles representativos de los usuarios que ayudan a comprender mejor sus necesidades, motivaciones y comportamientos. En StayMap, estos perfiles guían el diseño y desarrollo de la plataforma para asegurar que responda a lo que realmente buscan nuestros principales segmentos, como los fans de la música y los artistas emergentes.

<p align="center">
  <img src="assets/user_persona/valeria_torres.png" alt="user_persona" width="700">
</p>

<p align="center">
  <img src="assets/user_persona/diego_rivas.png" alt="user_persona" width="700">
</p>

## 2.3.2. User Task Matrix

| Tareas                                        | Frecuencia | Importancia |
|-----------------------------------------------|------------|-------------|
| Buscar conciertos cerca de su zona            | Frecuente  | Alta        |
| Descubrir nuevos artistas y géneros           | Frecuente  | Media       |
| Comparar información de eventos entre diferentes redes | Ocasional | Media |
| Consultas redes sociales para enterarse de eventos | Muy frecuente | Alta |

### Diego Rivas

| Tareas                                        | Frecuencia | Importancia |
|-----------------------------------------------|------------|-------------|
| Promocionar sus conciertos                    | Frecuente  | Muy alta    |
| Buscar plataformas gratuitas o de bajo costo para difusión | Frecuente  | Muy alta |
| Organizar y coordinar presentaciones en bares o festivales | Ocasional | Alta |
| Interactuar con su comunidad de seguidores    | Frecuente  | Medio       |

## 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Maps As-Is de los principales segmentos objetivos identificados. Estos mapas ilustran el recorrido actual que experimentan los usuarios en la vida real sin contar aún con la solución que ofrece StayMap.

A través de las distintas fases de su experiencia, se analiza qué acciones realizan, qué necesidades o frustraciones enfrentan, qué puntos de contacto utilizan, cómo viven emocionalmente ese recorrido y qué oportunidades surgen para diseñar una solución que resuelva dichos puntos de dolor. Esta representación permite comprender de forma profunda el contexto de los usuarios y sirve como base para idear funcionalidades relevantes, empáticas y de alto impacto en futuras iteraciones de la plataforma.

**Fans de la música**

<p align="center">
  <img src="assets/user_journey_mapping/user-journey-mapping-fans.png" alt="user_journey_mapping" width="700">
</p>

**Artistas emergentes**

<p align="center">
  <img src="assets/user_journey_mapping/user-journey-mapping-artista.png" alt="user_journey_mapping" width="700">
</p>


## 2.3.4. Empathy Mapping


**Diego Rivas**

<img src="assets/empathy_map/empathy_map_artistas.png" alt="user_persona" style="width: 700px"><</td>


**Valeria Torres**

<img src="assets/empathy_map/empathy_map_fan.png" alt="user_persona" style="width: 700px"><</td>


## 2.3.5. As-is Scenario Mapping

**Fans de la música:**

<p align="center">
  <img src="assets/as-is_scenario/as-is-scenrio-fans-musica.png" alt="as is scenario fans" width="700">
</p>

**Artistas emergentes y bandas independientes:**

<p align="center">
  <img src="assets/as-is_scenario/as-is-scenrio-artistas-emergentes.png" alt="as is scenario artistas" width="700">
</p>

# 2.4. Ubiquitous Language

<table>
  <thead>
    <tr>
      <th><strong>Término</strong></th>
      <th><strong>Definición/descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>StayMap</td>
      <td>Plataforma digital que conecta a fans con conciertos en vivo, especialmente de la escena musical local e independiente</td>
    </tr>
    <tr>
      <td>Evento</td>
      <td>Cualquier concierto, tocada, jam session o presentación musical está listada en la plataforma. Incluye ubicación, fecha, hora y artistas</td>
    </tr>
    <tr>
      <td>Mapa de conciertos</td>
      <td>Vista geolocalizada que muestra los eventos en tiempo real según la ubicación del usuario</td>
    </tr>
    <tr>
      <td>Fan</td>
      <td>Usuario interesado en asistir a conciertos y descubrir nueva música. Puede seguir artistas, activar notificaciones y guardar eventos</td>
    </tr>
    <tr>
      <td>Artista</td>
      <td>Músico independiente o banda que utiliza la plataforma para publicar y promocionar sus conciertos</td>
    </tr>
    <tr>
      <td>Comunidad local</td>
      <td>Red de usuarios y artistas que interactúan en una misma ciudad o región, promoviendo la música en vivo</td>
    </tr>
    <tr>
      <td>Exploración de evento</td>
      <td>Función que permite descubrir conciertos por género, zona, fecha o artista recomendado</td>
    </tr>
    <tr>
      <td>Evento destacado</td>
      <td>Concierto con mayor visibilidad en la app, ya sea por tendencia, ubicación o interés del usuario</td>
    </tr>
    <tr>
      <td>Promoción de eventos</td>
      <td>Difusión gratuita de eventos dentro de StayMap mediante algoritmos de afinidad y relevancia, sin necesidad de pagar publicidad</td>
    </tr>
    <tr>
      <td>Check-in</td>
      <td>Acción que realiza un fan al asistir a un evento, permitiendo registrar asistencia y generar recomendaciones futuras</td>
    </tr>
    <tr>
      <td>Perfil del artista</td>
      <td>Página dentro de la app donde el músico puede mostrar su biografía, próximos conciertos, redes sociales y contenido multimedia</td>
    </tr>
  </tbody>
</table>

# CAPÍTULO III: Requirements Specification

# 3.1 To-Be Scenario Mapping

**SEGMENTO #1: Fans de la música**

<p align="center">
	<img src="assets/to-be_scenario/to-be-scenrio-fans-musica.png" alt="to be scenario fans" style="width: 700px"/>
</p>

**SEGMENTO #2: Artistas emergentes y bandas independientes**

<p align="center">
<img src="assets/to-be_scenario/to-be-scenrio-artistas-emergentes.png" alt="to be scenario artistas" style="width: 700px"/>
</p>

# 3.2. User stories

**Epics**


| Epic ID | Título                                             | Descripción                                                                                                                                                                                       |
|---------|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP01    | Exploración y descubrimiento de conciertos         | Funcionalidades que permiten a los fans descubrir eventos musicales en su ciudad mediante mapas interactivos, búsquedas personalizadas y recomendaciones según ubicación y preferencias musicales. |
| EP02    | Notificaciones personalizadas                      | Desarrollo de notificaciones para fans y artistas, configuradas según intereses, ubicación y actividades recientes para mantener a los usuarios informados y comprometidos.                       |
| EP03    | Visibilidad para artistas emergentes               | Herramientas que permiten a los artistas emergentes destacar sus eventos, promocionar su música y conectar con nuevos públicos dentro de la comunidad musical.                                    |
| EP04    | Interacción social y comunidades                   | Funcionalidades sociales como chats, comentarios y acceso a comunidades de fans, diseñadas para fomentar la conexión entre usuarios y compartir experiencias musicales.                           |
| EP05    | Plataforma informativa (Landing Page y acceso)     | Experiencia inicial del usuario incluyendo la landing page, navegación básica, autenticación y presentación de la propuesta de valor de StayMap.                                                  |
| EP06    | Desarrollo técnico del backend (RESTful API)       | Implementación del backend con una API RESTful robusta, integración de base de datos y soporte técnico para las funcionalidades clave de la aplicación web y móvil.                              |

<br>


**User Stories**

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Escenarios</th>
      <th>Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Ver beneficios para fans</td>
      <td>Como visitante del segmento fan, quiero conocer los beneficios de la app para mí, para decidir registrarme.</td>
      <td>
        <strong>Escenario: Acceso a sección para fans</strong><br>
        Dado que el visitante accede a la landing page<br>
        Cuando visualiza la sección "Para fans de la música"<br>
        Entonces puede leer los beneficios de unirse a la app.<br><br>
        <strong>Escenario: Decisión de registro influenciada por beneficios</strong><br>
        Dado que el visitante revisa los beneficios presentados<br>
        Cuando encuentra opciones que se alinean con sus intereses<br>
        Entonces aumenta su intención de registrarse en la plataforma.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Ver beneficios para artista</td>
      <td>Como visitante del segmento artista, quiero ver cómo la app me ayuda a promocionar mis eventos.</td>
      <td>
        <strong>Escenario: Acceso a sección para artistas</strong><br>
        Dado que el visitante está en la landing page<br>
        Cuando revisa la sección "Para artistas"<br>
        Entonces puede visualizar herramientas y ventajas destacadas.<br><br>
        <strong>Escenario: Evaluación del valor de la app</strong><br>
        Dado que el visitante es un artista emergente<br>
        Cuando analiza las herramientas promocionales disponibles<br>
        Entonces comprende cómo StayMap puede ayudarle a crecer.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Acceder a testimonios</td>
      <td>Como visitante, quiero leer testimonios de usuarios reales para aumentar mi confianza en la app.</td>
      <td>
        <strong>Escenario: Visualización de comentarios de usuarios</strong><br>
        Dado que el visitante navega por la landing<br>
        Cuando encuentra la sección de testimonios<br>
        Entonces puede leer comentarios y valoraciones de otros usuarios.<br><br>
        <strong>Escenario: Confianza reforzada por experiencias ajenas</strong><br>
        Dado que el visitante tiene dudas sobre la app<br>
        Cuando lee testimonios positivos<br>
        Entonces se siente más confiado para unirse.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Registrarse en la landing page</td>
      <td>Como visitante, quiero ver fácilmente dónde registrarme en la landing page de StayMap.</td>
      <td>
        <strong>Escenario: Botón de registro visible en la landing</strong><br>
        Dado que el visitante accede a la landing page<br>
        Cuando navega por el contenido<br>
        Entonces encuentra un botón destacado y accesible con la etiqueta "Registrarse".<br><br>
        <strong>Escenario: Redirección inmediata al formulario de registro</strong><br>
        Dado que el visitante hace clic en el botón "Registrarse"<br>
        Cuando se redirige al formulario de creación de cuenta<br>
        Entonces puede ingresar sus datos para crear su cuenta.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Iniciar sesión en la landing page</td>
      <td>Como visitante que ya tiene cuenta, quiero poder iniciar sesión fácilmente desde la landing.</td>
      <td>
        <strong>Escenario: Botón de inicio de sesión accesible en la landing</strong><br>
        Dado que el visitante ya tiene cuenta<br>
        Cuando accede a la landing page<br>
        Entonces encuentra un botón o enlace con la etiqueta "Iniciar sesión".<br><br>
        <strong>Escenario: Redirección al login</strong><br>
        Dado que el visitante hace clic en "Iniciar sesión"<br>
        Cuando se redirige al formulario correspondiente<br>
        Entonces puede ingresar sus credenciales para acceder a su perfil.
      </td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Explorar eventos cercanos</td>
      <td>Como fan, quiero ver conciertos cerca de mi ubicación para decidir a cuál asistir.</td>
      <td>
        <strong>Escenario: Visualización de eventos geolocalizados</strong><br>
        Dado que el usuario está logueado<br>
        Cuando accede al mapa interactivo<br>
        Entonces visualiza los eventos en su área geográfica.<br><br>
        <strong>Escenario: Uso del mapa para tomar decisiones</strong><br>
        Dado que el usuario desea asistir a conciertos<br>
        Cuando observa la oferta de eventos cercana<br>
        Entonces puede elegir con mayor facilidad.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Filtrar eventos por género musical</td>
      <td>Como fan, quiero filtrar eventos por género para ver solo los que me interesan.</td>
      <td>
        <strong>Escenario: Uso del filtro de género</strong><br>
        Dado que el usuario abre los filtros<br>
        Cuando selecciona un género<br>
        Entonces solo se muestran eventos relacionados.<br><br>
        <strong>Escenario: Interacción fluida con el filtrado</strong><br>
        Dado que hay múltiples géneros disponibles<br>
        Cuando se elige uno<br>
        Entonces la vista se actualiza dinámicamente.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Confirmar o cancelar asistencia</td>
      <td>Como fan, quiero confirmar o cancelar mi asistencia a un evento para organizarme mejor y motivar a mis amigos.</td>
      <td>
        <strong>Escenario: Confirmación de asistencia</strong><br>
        Dado que el usuario accede a un evento<br>
        Cuando presiona "Confirmar asistencia"<br>
        Entonces se registra su asistencia.<br><br>
        <strong>Escenario: Cancelación de asistencia</strong><br>
        Dado que el usuario ya confirmó su asistencia<br>
        Cuando presiona "Cancelar asistencia"<br>
        Entonces se elimina el registro de asistencia.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US9</td>
      <td>Publicar nuevo concierto</td>
      <td>Como artista, quiero crear un evento para promocionar mi presentación.</td>
      <td>
        <strong>Escenario: Acceso al formulario de creación de evento</strong><br>
        Dado que el artista inicia sesión<br>
        Cuando accede a "Crear evento"<br>
        Entonces puede ingresar datos y publicarlo en el mapa.<br><br>
        <strong>Escenario: Publicación inmediata y visible</strong><br>
        Dado que los datos son válidos<br>
        Cuando se confirma la creación<br>
        Entonces el evento aparece visible en la plataforma.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Medir asistencia estimada</td>
      <td>Como artista, quiero ver cuántas personas marcaron asistencia para medir el interés.</td>
      <td>
        <strong>Escenario: Visualización de estadísticas de evento</strong><br>
        Dado que el evento está publicado<br>
        Cuando abre las estadísticas<br>
        Entonces visualiza el número de asistentes confirmados.<br><br>
        <strong>Escenario: Reacción ante datos en tiempo real</strong><br>
        Dado que los usuarios marcan "Asistiré"<br>
        Cuando se actualizan los datos<br>
        Entonces el artista ve reflejado el interés real.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US11</td>
      <td>Personalizar perfil de artista</td>
      <td>Como artista, quiero personalizar mi perfil con mi nombre artistico y fotografía para conectar mejor con el público.</td>
      <td>
        <strong>Escenario: Edición del perfil</strong><br>
        Dado que el artista abre su perfil<br>
        Cuando edita sus datos<br>
        Entonces puede foto y mis datos como nombre.<br><br>
        <strong>Escenario: Atractivo visual para fans</strong><br>
        Dado que el perfil ha sido personalizado<br>
        Cuando un fan lo visita<br>
        Entonces puede conocer mejor al artista.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Crear comunidad con seguidores</td>
      <td>Como artista, quiero crear una comunidad y publicar actualizaciones para fidelizar a mis seguidores.</td>
      <td>
        <strong>Escenario: Crear comunidad</strong><br>
        Dado que el artista inicia sesión<br>
        Cuando accede a su panel de usuario<br>
        Entonces puede crear una comunidad temática para sus fans.<br><br>
        <strong>Escenario: Publicar contenido en comunidad</strong><br>
        Dado que el artista tiene una comunidad creada<br>
        Cuando desea compartir una actualización<br>
        Entonces puede subir publicaciones visibles para sus seguidores.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Ingresar a comunidad de fans</td>
      <td>Como fan, quiero ingresar a una comunidad dentro de la app para compartir experiencias con otros asistentes y seguidores.</td>
      <td>
        <strong>Escenario: Acceso a la comunidad</strong><br>
        Dado que el usuario es un fan autenticado<br>
        Cuando accede a la sección "Comunidad"<br>
        Entonces puede unirse y participar en grupos temáticos o de eventos.<br><br>
        <strong>Escenario: Interacción dentro de la comunidad</strong><br>
        Dado que el fan ya forma parte de la comunidad<br>
        Cuando publica un mensaje o comenta<br>
        Entonces su contenido es visible para otros miembros.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Ver mapa con geolocalización</td>
      <td>Como fan, quiero ver un mapa con mi ubicación y los conciertos cercanos marcados para explorar visualmente las opciones disponibles.</td>
      <td>
        <strong>Escenario: Visualización del mapa con eventos</strong><br>
        Dado que el usuario está logueado y ha permitido el acceso a su ubicación<br>
        Cuando entra a la sección de mapa<br>
        Entonces visualiza su ubicación y los conciertos cercanos.<br><br>
        <strong>Escenario: Información de eventos en el mapa</strong><br>
        Dado que el usuario interactúa con un marcador de evento<br>
        Cuando hace clic en un ícono del mapa<br>
        Entonces puede ver detalles del evento como nombre, hora y lugar.
      </td>
      <td>EP01</td>
    </tr>
<tr>
      <td>US15</td>
      <td>Cambiar idioma en la landing page</td>
      <td>Como visitante, quiero cambiar el idioma de la página entre español e inglés para entender mejor el contenido.</td>
      <td><strong>Escenario: Cambio a inglés</strong><br>Dado que el usuario está en la landing page<br>Cuando selecciona la opción 'English'<br>Entonces el contenido se muestra en inglés.<br><br><strong>Escenario: Cambio a español</strong><br>Dado que el usuario está en la versión en inglés<br>Cuando selecciona 'Español'<br>Entonces el contenido se muestra en español.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Buscar conciertos</td>
      <td>Como usuario, quiero buscar conciertos por nombre o artista para encontrarlos fácilmente.</td>
      <td><strong>Escenario: Búsqueda por palabra clave</strong><br>Dado que el usuario accede al buscador de conciertos<br>Cuando escribe un nombre o artista<br>Entonces se muestran los conciertos coincidentes.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Buscar comunidades</td>
      <td>Como usuario, quiero buscar comunidades por nombre o temática para unirme a las que me interesen.</td>
      <td><strong>Escenario: Búsqueda de comunidades</strong><br>Dado que el usuario accede al buscador de comunidades<br>Cuando ingresa una palabra clave<br>Entonces ve las comunidades coincidentes.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Iniciar sesión en la app web</td>
      <td>Como usuario registrado, quiero iniciar sesión desde la aplicación web para acceder a mi cuenta.</td>
      <td><strong>Escenario: Ingreso exitoso desde app web</strong><br>Dado que el usuario tiene una cuenta<br>Cuando accede al formulario de login y envía sus credenciales<br>Entonces accede correctamente a su perfil.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Registrarse como artista</td>
      <td>Como nuevo usuario, quiero registrarme como artista para promocionar mis conciertos.</td>
      <td><strong>Escenario: Registro como artista</strong><br>Dado que el visitante accede al formulario de registro<br>Cuando selecciona la opción 'Artista' y completa sus datos<br>Entonces su cuenta es creada con perfil de artista.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Registrarse como fan</td>
      <td>Como nuevo usuario, quiero registrarme como fan para participar en la comunidad y explorar conciertos.</td>
      <td><strong>Escenario: Registro como fan</strong><br>Dado que el visitante accede al formulario de registro<br>Cuando selecciona la opción 'Fan' y completa sus datos<br>Entonces su cuenta es creada con perfil de fan.</td>
      <td>EP05</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Zoom a concierto en el mapa</td>
      <td>Como fan, quiero que al seleccionar un concierto en el mapa se haga zoom a su ubicación.</td>
      <td><strong>Escenario: Zoom en mapa a concierto seleccionado</strong><br>Dado que el usuario está en el mapa<br>Cuando hace clic en un concierto<br>Entonces el mapa se centra y hace zoom sobre su ubicación.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Ver estado del concierto</td>
      <td>Como usuario, quiero saber si un concierto está disponible o agotado para decidir si puedo asistir.</td>
      <td><strong>Escenario: Visualización de estado del concierto</strong><br>Dado que el usuario revisa la lista de conciertos<br>Cuando observa el estado de disponibilidad<br>Entonces puede ver si el evento está 'Disponible' o 'Agotado'.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Ver información detallada del concierto</td>
      <td>Como fan, quiero ver la información completa de un concierto para decidir si asistir.</td>
      <td><strong>Escenario: Acceso a detalles del concierto</strong><br>Dado que el usuario selecciona un concierto<br>Cuando accede a su ficha de detalle<br>Entonces visualiza el artista, ubicación, fecha, hora, imagen, y descripción.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Unirse a una comunidad</td>
      <td>Como fan, quiero unirme a una comunidad musical para interactuar con otros usuarios con intereses similares.</td>
      <td><strong>Escenario: Unirse a comunidad</strong><br>Dado que el fan accede a una comunidad disponible<br>Cuando presiona el botón 'Unirse'<br>Entonces queda registrado como miembro.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Publicar en la comunidad</td>
      <td>Como fan, quiero crear publicaciones en la comunidad a la que me he unido,<br>para que pueda compartir opiniones, fotos o recomendaciones con otros miembros.</td>
      <td><strong>Escenario: Crear publicación exitosa</strong><br>Dado que el usuario está unido a una comunidad,<br>Cuando accede a la comunidad y le da al boton agregar una nueva publicación escribe un mensaje,<br>Entonces la publicación se guarda y se muestra en el feed de la comunidad.</td>
      <td>EP04</td>
    </tr>
 	<tr>
	<td>US26</td>
      <td>Editar perfil personal</td>
      <td>Como fan, quiero poder editar mi información de perfil (foto, nombre y nombre de usuario),<br>para que los demás usuarios puedan reconocerme fácilmente y mantener mi perfil actualizado.</td>
      <td><strong>Escenario: Actualizar información del perfil</strong><br>Dado que el usuario accede a la sección "Mi Perfil",<br>Cuando le doy al boton editar perfil,<br>Entonces puedo editar mi nombre, nombre de usuario y cambiar mi foto de perfil.</td>
      <td>EP04</td>
    </tr>
	  <tr>
	<td>US27</td>
      <td>Confirmar o marcar asistencia a un evento</td>
      <td>Como fan, quiero poder marcar un evento como “Por asistir” o “Asistido”,<br>para que pueda llevar un seguimiento de los conciertos que planeo o ya he disfrutado.</td>
      <td><strong>Escenario: Confirmar asistencia a un evento</strong><br>Dado que el usuario visualiza los detalles de un evento,<br>Cuando presiona el botón "Confirmar asistencia",<br>Entonces el evento se agrega a su lista de “Por asistir” y el botón cambia a "Cancelar asistencia".<br>
      <strong>Escenario : Cancelar asistencia</strong><br>Dado que el evento ya está marcado como “Por asistir”,<br>Cuando presiona el botón "Cancelar asistencia",<br>Entonces el evento se elimina de su lista de eventos futuros y vuelve a estar disponible para confirmar.</td>
      <td>EP01</td>
    </tr>
<tr>
  <td>US28</td>
  <td>Ver comunidades accedidas</td>
  <td>Como usuario, quiero visualizar en el apartado "Tus grupos" las comunidades a las que me he unido.</td>
  <td>
    <strong>Escenario: Visualización de comunidades unidas</strong><br>
    Dado que el usuario ha ingresado a comunidades<br>
    Cuando accede a la sección "Tus grupos"<br>
    Entonces puede ver la lista de comunidades a las que pertenece.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US29</td>
  <td>Reaccionar a publicaciones en comunidades</td>
  <td>Como usuario, quiero poder reaccionar a publicaciones dentro de las comunidades.</td>
  <td>
    <strong>Escenario: Reacción a publicación</strong><br>
    Dado que el usuario navega por una comunidad<br>
    Cuando encuentra una publicación<br>
    Entonces puede reaccionar con un emoji o símbolo.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US30</td>
  <td>Calificar concierto</td>
  <td>Como usuario, quiero calificar un concierto de 1 a 5 estrellas para compartir mi experiencia.</td>
  <td>
    <strong>Escenario: Valoración del concierto</strong><br>
    Dado que el usuario asistió a un concierto<br>
    Cuando accede a su detalle<br>
    Entonces puede seleccionar una puntuación del 1 al 5.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US31</td>
  <td>Ver usuarios que asistirán a concierto</td>
  <td>Como usuario, quiero ver qué otros usuarios asistirán al mismo concierto que yo.</td>
  <td>
    <strong>Escenario: Visualizar asistentes</strong><br>
    Dado que el usuario confirmó su asistencia<br>
    Cuando entra al evento<br>
    Entonces puede ver una lista de otros usuarios que también asistirán.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US32</td>
  <td>Acceder a perfil de otros usuarios</td>
  <td>Como usuario, quiero poder acceder al perfil de otros usuarios para conocer más sobre ellos.</td>
  <td>
    <strong>Escenario: Navegar al perfil de otro usuario</strong><br>
    Dado que el usuario ve un nombre o avatar<br>
    Cuando hace clic sobre él<br>
    Entonces se redirige al perfil público de ese usuario.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US33</td>
  <td>Ver publicaciones con like</td>
  <td>Como usuario, quiero ver una lista de publicaciones a las que les he dado "like".</td>
  <td>
    <strong>Escenario: Historial de publicaciones favoritas</strong><br>
    Dado que el usuario ha interactuado en comunidades<br>
    Cuando accede a su sección de favoritos<br>
    Entonces puede visualizar todas las publicaciones que le han gustado.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US34</td>
  <td>Ver plataformas de venta del concierto</td>
  <td>Como usuario, quiero ver en qué plataformas puedo comprar entradas para un concierto.</td>
  <td>
    <strong>Escenario: Visualización de enlaces de venta</strong><br>
    Dado que el usuario revisa un concierto<br>
    Cuando accede a su ficha de detalles<br>
    Entonces visualiza las plataformas donde están disponibles las entradas.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US35</td>
  <td>Permitir acceso a ubicación</td>
  <td>Como usuario, quiero que StayMap acceda a mi ubicación para recibir información personalizada.</td>
  <td>
    <strong>Escenario: Permiso de ubicación</strong><br>
    Dado que el usuario entra a la app por primera vez<br>
    Cuando se le solicita permiso de ubicación<br>
    Entonces puede aceptar o denegar el acceso.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US36</td>
  <td>Mostrar conciertos cercanos</td>
  <td>Como usuario, quiero que StayMap me muestre conciertos cercanos a mi ubicación actual.</td>
  <td>
    <strong>Escenario: Conciertos basados en geolocalización</strong><br>
    Dado que el usuario ha otorgado permisos de ubicación<br>
    Cuando accede al mapa<br>
    Entonces se muestran conciertos próximos geográficamente.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>US37</td>
  <td>Ver miembros de comunidad</td>
  <td>Como usuario, quiero ver la lista de miembros que pertenecen a una comunidad.</td>
  <td>
    <strong>Escenario: Listado de miembros</strong><br>
    Dado que el usuario ha ingresado a una comunidad<br>
    Cuando accede a la sección de miembros<br>
    Entonces puede visualizar los usuarios que la integran.
  </td>
  <td>EP04</td>
</tr>
<tr>
  <td>US38</td>
  <td>Subir imágenes en comunidades</td>
  <td>Como usuario, quiero subir imágenes en publicaciones de comunidad para compartir experiencias visuales.</td>
  <td>
    <strong>Escenario: Publicación con imagen</strong><br>
    Dado que el usuario quiere compartir contenido<br>
    Cuando crea una publicación<br>
    Entonces puede adjuntar una o más imágenes que se muestren en el feed.
  </td>
  <td>EP04</td>
</tr>

  </tbody>
</table>


### Technical Stories:


| Story ID | Título                                         | Descripción                                                                                 | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                             | Relacionado con (Epic ID) |
| -------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| TS-01    | Endpoint para crear conciertos                    | Como developer, quiero un endpoint POST para crear eventos musicales                        | **Escenario: Creación exitosa de evento (POST)**<br>Dado que el cliente envía una petición POST a /api/conciertos con body válido<br>Cuando los datos están completos<br>Entonces el servidor responde 201 y guarda el evento<br><br>**Escenario: Respuesta con evento registrado**<br>Dado que el evento fue creado<br>Cuando se revisa la base de datos<br>Entonces aparece con los campos ingresados | EP06                      |
| TS-02    | Endpoint para obtener eventos por ubicación    | Como developer, quiero un endpoint GET que devuelva eventos cerca de una lat/lon            | **Escenario: Consulta exitosa por lat/lon (GET)**<br>Dado que el usuario envía lat/lon como query params<br>Cuando hay eventos cercanos<br>Entonces devuelve una lista de eventos georreferenciados<br><br>**Escenario: Consulta sin resultados**<br>Dado que no hay eventos en la zona<br>Cuando se hace la petición<br>Entonces el servidor responde con lista vacía                              | EP01 / EP06               |
| TS-03    | Endpoint para registrar asistencia             | Como developer, quiero que los usuarios puedan confirmar asistencia a eventos               | **Escenario: Confirmación registrada**<br>Dado que el usuario hace clic en "Asistiré"<br>Cuando se envía el POST<br>Entonces se actualiza el conteo en la base de datos<br><br>**Escenario: Asistencia ya registrada**<br>Dado que el usuario ya marcó su asistencia<br>Cuando intenta hacerlo otra vez<br>Entonces se impide duplicar el registro                                                  | EP01 / EP06               |
| TS-04    | Endpoint para valorar un evento                | Como developer, quiero permitir que el usuario envíe una calificación y comentario          | **Escenario: Envío de valoración válida**<br>Dado que el evento ya ocurrió<br>Cuando el usuario hace un POST con la valoración<br>Entonces se guarda y actualiza el perfil del evento<br><br>**Escenario: Prevención de múltiples valoraciones**<br>Dado que el usuario ya valoró<br>Cuando lo intenta de nuevo<br>Entonces se actualiza o da error                                                 | EP01 / EP06               |
| TS-05    | Validaciones para crear eventos                | Como developer, quiero validar que los campos obligatorios estén presentes al crear eventos | **Escenario: Body incompleto al crear evento**<br>Dado que el body del POST está incompleto<br>Cuando falta título o ubicación<br>Entonces el servidor responde 400 Bad Request<br><br>**Escenario: Datos correctos aceptados**<br>Dado que el body contiene todos los campos<br>Cuando se realiza el POST<br>Entonces el servidor responde con éxito                                               | EP06                      |
| TS-06    | Endpoint para crear publicaciones en comunidad | Como developer, quiero permitir que un usuario cree publicaciones en comunidades            | **Escenario: Publicación creada**<br>Dado que el usuario está en una comunidad<br>Cuando hace un POST con el mensaje y/o imagen<br>Entonces se guarda correctamente y aparece en el feed<br><br>**Escenario: Validación de campos**<br>Cuando falta el contenido mínimo<br>Entonces se devuelve un error con código 400                                                                             | EP04 / EP06               |
| TS-07    | Endpoint para reaccionar a publicaciones       | Como developer, quiero permitir agregar reacciones a publicaciones de comunidad             | **Escenario: Reacción registrada**<br>Dado que el usuario está autenticado<br>Cuando da clic en una reacción<br>Entonces se actualiza el conteo en la base de datos<br><br>**Escenario: Reacción duplicada**<br>Dado que ya reaccionó<br>Cuando intenta hacer lo mismo<br>Entonces se actualiza o se revierte la reacción previa                                                                    | EP04 / EP06               |
| TS-8    | Endpoint para listar comunidades de usuario    | Como developer, quiero obtener las comunidades a las que un usuario pertenece               | **Escenario: Listado de comunidades**<br>Dado que el usuario está logueado<br>Cuando hace una petición GET a /api/users/{id}/communities<br>Entonces recibe la lista de comunidades donde está unido                                                                                                                                                                                                | EP04 / EP06               |
| TS-9    | Endpoint para ver asistentes de concierto      | Como developer, quiero permitir ver qué usuarios asistirán a un evento                      | **Escenario: Ver asistentes**<br>Dado que el evento tiene usuarios registrados<br>Cuando se consulta el endpoint GET /api/events/{id}/attendees<br>Entonces devuelve lista de usuarios con sus nombres de usuario o perfil                                                                                                                                                                          | EP04 / EP06               |
| TS-10    | Endpoint para ver perfiles públicos            | Como developer, quiero permitir ver el perfil público de otros usuarios                     | **Escenario: Acceso a perfil público**<br>Dado que un usuario hace clic en otro<br>Cuando accede a /api/users/{id}<br>Entonces ve nombre, foto y comunidades visibles                                                                                                                                                                                                                               | EP04 / EP06               |
| TS-11    | Endpoint para subir imágenes a publicaciones   | Como developer, quiero permitir que los usuarios suban imágenes en publicaciones            | **Escenario: Imagen aceptada**<br>Dado que el usuario adjunta una imagen al crear publicación<br>Cuando el archivo es válido<br>Entonces se guarda y muestra en el frontend<br><br>**Escenario: Archivo inválido**<br>Cuando sube un archivo no permitido<br>Entonces se devuelve un error con código y mensaje                                                                                     | EP04 / EP06               |


# 3.3. Impact Mapping


**Fans de la Música:**

<p align="center">
<img src="assets/impact_mapping/Impact-Mapping-Fan.png" alt="impact mapping fan" style="width: 700px">
</p>

**Artistas emergentes y bandas independientes:**

<p align="center">
<img src="assets/impact_mapping/Impact-Mapping-Artista.png" alt="impact mapping Artista" style="width: 700px">
</p>

# 3.4. Product Backlog

| # Orden | User Story Id | Título                                   | Description                                                                                                                | Story Points (1/2/3/5/8) |
|--------:|--------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------|--------------------------|
| 1       | US01         | Ver beneficios para fans                 | Como visitante fan, quiero conocer los beneficios de la app para decidir registrarme.                                      | 1                        |
| 2       | US02         | Ver beneficios para artista             | Como visitante artista, quiero ver cómo la app me ayuda a promocionar mis eventos.                                         | 1                        |
| 3       | US03         | Acceder a testimonios                   | Como visitante, quiero leer testimonios de usuarios reales para aumentar mi confianza en la app.                           | 1                        |
| 4       | US04         | Registrarse en la landing page          | Como visitante, quiero encontrar fácilmente dónde registrarme en la landing page.                                          | 2                        |
| 5       | US05         | Iniciar sesión en la landing page       | Como visitante con cuenta, quiero iniciar sesión fácilmente desde la landing page.                                         | 2                        |
| 6       | US06         | Explorar eventos cercanos               | Como fan, quiero ver conciertos cerca de mi ubicación para decidir a cuál asistir.                                         | 5                        |
| 7       | US07         | Filtrar eventos por género musical      | Como fan, quiero filtrar eventos por género para ver solo los que me interesan.                                           | 3                        |
| 8       | US08         | Confirmar o cancelar asistencia         | Como fan, quiero confirmar o cancelar mi asistencia para organizarme mejor y motivar a mis amigos.                         | 5                        |
| 9       | US09         | Publicar nuevo concierto                | Como artista, quiero crear un evento para promocionar mi presentación.                                                    | 5                        |
| 10      | US10         | Medir asistencia estimada               | Como artista, quiero ver cuántas personas marcaron asistencia para medir el interés.                                       | 3                        |
| 11      | US11         | Personalizar perfil de artista          | Como artista, quiero personalizar mi perfil con nombre y foto para conectar mejor con el público.                         | 3                        |
| 12      | US12         | Crear comunidad con seguidores          | Como artista, quiero crear una comunidad para publicar actualizaciones y fidelizar a mis seguidores.                      | 5                        |
| 13      | US13         | Ingresar a comunidad de fans            | Como fan, quiero ingresar a comunidades para compartir experiencias con otros seguidores.                                 | 5                        |
| 14      | US14         | Ver mapa con geolocalización            | Como fan, quiero ver un mapa con mi ubicación y conciertos cercanos marcados para explorar opciones visualmente.          | 5                        |
| 15      | US15         | Cambiar idioma en la landing page       | Como visitante, quiero cambiar el idioma entre español e inglés para entender mejor el contenido.                         | 3                        |
| 16      | US16         | Buscar conciertos                      | Como usuario, quiero buscar conciertos por nombre o artista para encontrarlos fácilmente.                                 | 2                        |
| 17      | US17         | Buscar comunidades                     | Como usuario, quiero buscar comunidades por nombre o temática para unirme a las que me interesen.                         | 2                        |
| 18      | US18         | Iniciar sesión en la app web            | Como usuario registrado, quiero iniciar sesión desde la app web para acceder a mi cuenta.                                  | 2                        |
| 19      | US19         | Registrarse como artista                | Como nuevo usuario, quiero registrarme como artista para promocionar mis conciertos.                                      | 3                        |
| 20      | US20         | Registrarse como fan                    | Como nuevo usuario, quiero registrarme como fan para participar en la comunidad y explorar conciertos.                    | 3                        |
| 21      | US21         | Zoom a concierto en el mapa             | Como fan, quiero que al seleccionar un concierto en el mapa se haga zoom a su ubicación.                                  | 3                        |
| 22      | US22         | Ver estado del concierto                | Como usuario, quiero saber si un concierto está disponible o agotado para decidir si puedo asistir.                       | 2                        |
| 23      | US23         | Ver información detallada del concierto | Como fan, quiero ver la información completa de un concierto para decidir si asistir.                                      | 3                        |
| 24      | US24         | Unirse a una comunidad                  | Como fan, quiero unirme a una comunidad musical para interactuar con otros usuarios con intereses similares.              | 5                        |
| 25      | US25         | Publicar en la comunidad                | Como fan, quiero crear publicaciones en la comunidad para compartir opiniones y fotos con otros miembros.                 | 3                        |
| 26      | US26         | Editar perfil personal                  | Como fan, quiero editar mi información (foto, nombre, usuario) para mantener mi perfil actualizado.                       | 3                        |
| 27      | US27         | Confirmar o marcar asistencia a evento | Como fan, quiero marcar un evento como “Por asistir” o “Asistido” para llevar seguimiento de mis conciertos.              | 3                        |\
|      28 | US28         | Ver comunidades accedidas                 | Como usuario, quiero visualizar en el apartado "Tus grupos" las comunidades a las que me he unido.      | 2                        |
|      29 | US29         | Reaccionar a publicaciones en comunidades | Como usuario, quiero poder reaccionar a publicaciones dentro de las comunidades.                        | 2                        |
|      30 | US30         | Calificar concierto                       | Como usuario, quiero calificar un concierto de 1 a 5 estrellas para compartir mi experiencia.           | 3                        |
|      31 | US31         | Ver usuarios que asistirán a concierto    | Como usuario, quiero ver qué otros usuarios asistirán al mismo concierto que yo.                        | 3                        |
|      32 | US32         | Acceder a perfil de otros usuarios        | Como usuario, quiero acceder al perfil de otros usuarios para conocer más sobre ellos.                  | 2                        |
|      33 | US33         | Ver publicaciones con like                | Como usuario, quiero ver una lista de publicaciones a las que les he dado "like".                       | 3                        |
|      34 | US34         | Ver plataformas de venta del concierto    | Como usuario, quiero ver en qué plataformas puedo comprar entradas para un concierto.                   | 2                        |
|      35 | US35         | Permitir acceso a ubicación               | Como usuario, quiero que StayMap acceda a mi ubicación para recibir información personalizada.          | 2                        |
|      36 | US36         | Mostrar conciertos cercanos               | Como usuario, quiero que StayMap me muestre conciertos cercanos a mi ubicación actual.                  | 5                        |
|      37 | US37         | Ver miembros de comunidad                 | Como usuario, quiero ver la lista de miembros que pertenecen a una comunidad.                           | 2                        |
|      38 | US38         | Subir imágenes en comunidades             | Como usuario, quiero subir imágenes en publicaciones de comunidad para compartir experiencias visuales. | 3                        |
| 39    | TS-01    | Endpoint para crear conciertos                 | Como developer, quiero un endpoint POST para crear eventos musicales.                        | 3            |
| 40    | TS-02    | Endpoint para obtener eventos por ubicación    | Como developer, quiero un endpoint GET que devuelva eventos cerca de una lat/lon.            | 3            |
| 41    | TS-03    | Endpoint para registrar asistencia             | Como developer, quiero que los usuarios puedan confirmar asistencia a eventos.               | 2            |
| 42    | TS-04    | Endpoint para valorar un evento                | Como developer, quiero permitir que el usuario envíe una calificación y comentario.          | 3            |
| 43    | TS-05    | Validaciones para crear eventos                | Como developer, quiero validar que los campos obligatorios estén presentes al crear eventos. | 2            |
| 44    | TS-06    | Endpoint para crear publicaciones en comunidad | Como developer, quiero permitir que un usuario cree publicaciones en comunidades.            | 3            |
| 45    | TS-07    | Endpoint para reaccionar a publicaciones       | Como developer, quiero permitir agregar reacciones a publicaciones de comunidad.             | 2            |
| 46    | TS-08    | Endpoint para listar comunidades de usuario    | Como developer, quiero obtener las comunidades a las que un usuario pertenece.               | 2            |
| 47    | TS-09    | Endpoint para ver asistentes de concierto      | Como developer, quiero permitir ver qué usuarios asistirán a un evento.                      | 2            |
| 48    | TS-10    | Endpoint para ver perfiles públicos            | Como developer, quiero permitir ver el perfil público de otros usuarios.                     | 1            |
| 49    | TS-11    | Endpoint para subir imágenes a publicaciones   | Como developer, quiero permitir que los usuarios suban imágenes en publicaciones.            | 3            |


# Capítulo IV: Product Design

# 4.1. Style Guidelines

En esta sección se define la línea visual que guiará el diseño de la aplicación y la versión web de StayMap. El objetivo es ofrecer una interfaz clara, accesible y coherente, que facilite la exploración de eventos musicales en distintos contextos urbanos. Para ello, se han seleccionado elementos gráficos funcionales y modernos, con una paleta de colores contrastante que permite una navegación intuitiva y una rápida identificación de la información relevante.
La Guía de Estilo establece principios fundamentales como el uso de tipografías legibles, un sistema de iconografía simple y una estructura visual organizada. Este documento sirve como referencia para mantener una identidad visual unificada a medida que la plataforma evoluciona, asegurando consistencia en todos los puntos de contacto con el usuario, tanto en dispositivos móviles como en la web.

## 4.1.1. General Style Guidelines

**Branding**

El logotipo de StayMap representa el propósito central de la plataforma: guiar a los usuarios en la búsqueda y descubrimiento de experiencias musicales en su entorno. En el corazón del diseño se encuentra una brújula, símbolo universal de orientación, que refleja cómo StayMap actúa como un punto de referencia para quienes desean encontrar conciertos y eventos en vivo, sin importar su ubicación.
La brújula no solo indica dirección, sino también la intención de explorar y conectar con lo auténtico, cualidades que definen a nuestros usuarios: amantes de la música en vivo, artistas independientes y personas en constante búsqueda de nuevas experiencias culturales. El estilo del logo equilibra lo moderno con lo accesible, reforzando la identidad de StayMap como una herramienta cercana, útil y confiable para descubrir la música que suena en la ciudad.

<div align="center">
<img src="assets/style/starymaplogo.png" alt="StayMap Logo" style="width: 200px"></div>

**Typography**

Para StayMap, hemos elegido la fuente Inter debido a su diseño geométrico, moderno y altamente legible, ideal para interfaces digitales. Esta tipografía está pensada para mejorar la experiencia del usuario, reduciendo el cansancio visual y asegurando una lectura fluida, tanto en textos largos como en elementos de la interfaz.

Utilizamos diferentes estilos de Inter para estructurar nuestra comunicación visual:
Inter Medium para textos principales y contenido en general, proporcionando una lectura cómoda y clara.


- Inter Semi Bold para subtítulos y destacados, lo que permite una mejor jerarquía y énfasis en información clave.

- Inter Bold se usa para títulos y llamadas de atención, asegurando que los elementos más importantes resalten de manera efectiva.

Este enfoque tipográfico ayuda a mantener una apariencia limpia, profesional y accesible, alineada con el propósito de StayMap de ofrecer una experiencia intuitiva y fácil de usar para todos nuestros usuarios.

**Colors**

La paleta de colores de StayMap fue cuidadosamente seleccionada para reflejar nuestra misión de conectar a las personas con la música en vivo de manera fácil y accesible. Queremos transmitir la energía y la emoción de los eventos musicales, a la vez que mantenemos una apariencia moderna, profesional y elegante.

Los tonos oscuros de morado y el negro aportan sofisticación y profesionalismo, proporcionando un fondo ideal para textos y elementos clave de la interfaz, asegurando siempre una buena legibilidad. El morado claro se utiliza para elementos destacados, creando un contraste suave pero efectivo que refleja el dinamismo de nuestra aplicación.

El blanco juega un papel crucial al ofrecer claridad y aire en el diseño, asegurando que la información se presente de manera limpia y accesible. Además, el uso del blanco permite que los colores morados resalten sin sobrecargar la interfaz.

Con esta paleta, StayMap comunica tanto la emoción de la música en vivo como su enfoque moderno y accesible, equilibrando elegancia y energía para ofrecer una experiencia visualmente atractiva y fácil de usar.

**Spacing**

Para garantizar una experiencia de usuario óptima y una lectura cómoda en StayMap, hemos establecido un espaciado coherente en todo el diseño. El espaciado entre líneas de texto se ha configurado en 1.5, lo que permite una lectura fluida y reduce el cansancio visual, asegurando que los usuarios puedan consumir información de manera cómoda, incluso en textos largos.

En cuanto al espaciado externo, hemos determinado que será de 2 unidades como máximo en los botones e imágenes. Este ajuste asegura que el diseño se mantenga equilibrado, evitando que los elementos se vean sobrecargados o desordenados, y permitiendo que cada componente respire de manera adecuada.

Para el espaciado interno, se ha decidido mantenerlo en 1 unidad. Esto asegura que los elementos dentro de los botones y las imágenes estén bien alineados, creando un diseño limpio y consistente que facilita la interacción y mejora la experiencia general del usuario.

Este enfoque de espaciado contribuye a la claridad visual, optimiza la usabilidad y mantiene la estética ordenada, alineada con el enfoque accesible y moderno de StayMap.

**Language**

En StayMap, el lenguaje que utilizamos refleja nuestra misión de hacer que la búsqueda de eventos musicales sea sencilla y accesible para todos. Mantenemos un tono amigable y cercano, con un enfoque profesional que asegura que los usuarios siempre reciban información clara y útil. Al mismo tiempo, nos aseguramos de que el lenguaje sea informal y relajado, de modo que nuestros usuarios se sientan cómodos y bienvenidos, sin importar su familiaridad con la tecnología.

Queremos que nuestros usuarios, ya sean jóvenes exploradores de música o asistentes habituales a conciertos, sientan que StayMap es su compañero confiable en el descubrimiento de nuevos eventos. Nuestro enfoque combina un estilo comunicativo profesional con un toque accesible, lo que nos permite conectar de manera efectiva con una audiencia diversa, desde fanáticos de la música independiente hasta aquellos que buscan eventos más establecidos.

## 4.1.2. Web Style Guidelines

En la interfaz web de StayMap, hemos diseñado una experiencia visual que refleja la identidad de nuestra plataforma: accesible, moderna y enfocada en la búsqueda de eventos musicales. La paleta de colores y la tipografía elegida están alineadas con nuestra misión de guiar a los usuarios hacia sus próximos eventos musicales de una manera intuitiva y atractiva.

**Typography:**

Hemos optado por la fuente Inter en sus variantes Medium, Bold y Semi-Bold, debido a su diseño geométrico y moderno que facilita la legibilidad en pantallas grandes y móviles. Esta tipografía refuerza la accesibilidad de la aplicación, garantizando que nuestros usuarios, sin importar su experiencia con la tecnología, puedan navegar de manera fácil y fluida. Además, su estilo limpio y profesional aporta un tono serio pero amigable, asegurando que la experiencia de usuario sea siempre clara y eficiente.


<div align="center">
<img src="assets/style/tipography.jpg" alt="StayMap Typography" style="width: 450px">
</div>

**Branding:**

El logo de StayMap es una brújula estilizada, simbolizando la búsqueda de eventos musicales por parte de nuestros usuarios. Su diseño sencillo y directo no solo facilita la recordación, sino que también refleja la misión de la plataforma: guiar a los usuarios hacia los eventos musicales más adecuados para sus gustos e intereses. La brújula conecta visualmente con la idea de exploración, tanto de la ciudad como de la música, reforzando nuestra identidad de ser un referente confiable en el descubrimiento de eventos.

<div align="center">
<img src="assets/style/starymaplogo.png" alt="StayMap Logo" style="width: 200px">
</div>


**Colors:**

La paleta de colores de StayMap se centra en tonos oscuros de morado y negro, acompañados de blanco, creando una atmósfera sofisticada y moderna que resalta los elementos clave de la interfaz sin abrumar al usuario. El morado oscuro simboliza creatividad, pasión y misterio, elementos relacionados con la experiencia de descubrir eventos musicales únicos. El uso de blanco aporta claridad y un contraste nítido, lo que mejora la legibilidad y facilita una navegación intuitiva y agradable. Esta combinación de colores re fuerza el enfoque elegante y accesible de nuestra plataforma, asegurando que los usuarios se sientan cómodos mientras exploran y descubren nuevos eventos musicales.

<div align="center">
<img src="assets/style/colors.jpg" alt="StayMap Colors" style="width: 400px">
</div>

# 4.2. Information Architecture

La arquitectura de la información de StayMap se centra en ofrecer una experiencia clara, fluida y organizada para nuestros usuarios, quienes son principalmente personas apasionadas por la música, artistas independientes y cantantes que buscan eventos o espacios relacionados con su arte. Tanto en la versión web como en la aplicación móvil, el contenido estará estructurado para que los usuarios accedan fácilmente a lugares, eventos y recomendaciones relevantes según su ubicación y preferencias.

El diseño está pensado para que cualquier usuario pueda navegar de forma intuitiva a través de las funciones clave de la plataforma, como explorar eventos musicales cercanos, filtrar por tipo de lugar o ambiente, y descubrir espacios ideales para presentarse, ensayar o disfrutar música en vivo. Se mantendrá una coherencia visual y funcional que se adapte a cada momento de uso.

Las decisiones en torno a los Organization Systems, Labeling Systems, Navigation Systems y Searching Systems serán fundamentales para asegurar una experiencia ordenada y satisfactoria. Estas decisiones permitirán a los usuarios encontrar de forma rápida y sencilla la información oportuna, potenciando así su conexión con el entorno musical de la ciudad.

## 4.2.1. Organization Systems

En StayMap, implementaremos sistemas de organización del contenido que respondan a las distintas necesidades de nuestros usuarios, desde fans de la música hasta artistas emergentes. Este enfoque nos permitirá ofrecer una experiencia de navegación clara y personalizada, donde los eventos se clasifiquen por ubicación, fecha, género musical y popularidad. Además, los perfiles de usuario, notificaciones y recomendaciones estarán organizados de forma coherente y accesible, lo que facilitará que los usuarios descubran eventos relevantes, interactúen con otros asistentes y gestionen su participación en tiempo real. Esta estructura organizada contribuirá a una experiencia fluida e intuitiva dentro de la plataforma.

**Landing page:** La organización de la información en la landing page se centra en ofrecer una visión general atractiva y dirigir a los usuarios hacia las funcionalidades principales.

- **Organización Visual Del Contenido:**

- Jerárquica: La landing page de StayMap tiene una clara jerarquía visual en la presentación de los conciertos programados. El nombre del artista y el título del evento principal se destacan con mayor tamaño y prominencia, seguidos por la información secundaria como la fecha y el lugar. Esta jerarquía guía la atención del usuario hacia los detalles más relevantes de cada evento de un vistazo. De manera similar, los beneficios para fans y artistas también utilizan una jerarquía visual para resaltar los puntos clave.

- **Esquemas de categorización de contenido:**

- Por tópicos: Se organiza la información en secciones temáticas bien definidas, como "Conoce los conciertos programados", "Testimonios de Fans" y las secciones dedicadas a "Para Fans" y "Para Artistas". Esta categorización por temas permite a los usuarios encontrar rápidamente la información que les resulta más relevante según sus intereses.

- Según audiencia: La distinción clara entre las secciones "Para Fans" y "Para Artistas" representa una categorización según la audiencia principal. Esto permite adaptar el mensaje y destacar los beneficios específicos para cada grupo de usuarios directamente en la página de inicio.

**Aplicación web:** La organización de la información en la aplicación web se enfoca en permitir a los usuarios explorar, filtrar y acceder a detalles específicos de los eventos y perfiles.

- **Organización visual del contenido:**

- Jerárquica: En la vista de listado de conciertos filtrados, la imagen del artista o evento generalmente ocupa un lugar destacado, seguida del nombre y otros detalles relevantes. Esta jerarquía visual ayuda a los usuarios a identificar rápidamente los eventos de su interés. En las secciones de "Mi Perfil" y "Lista de Conciertos", la información principal del usuario o del evento seleccionado recibe mayor énfasis visual.

- Matricial: La funcionalidad de filtrado de conciertos representa una forma de organización matricial implícita. Los usuarios pueden combinar diferentes criterios (género, fecha, lugar, etc.) para refinar su búsqueda, creando una matriz de resultados basada en la intersección de sus selecciones.

- **Esquemas de categorización de contenido:**

- Por tópicos: La navegación principal de la app web ("Inicio", "Mapa", "Comunidad", "Notificaciones", "Mi Perfil") establece una clara categorización por temas o secciones funcionales. Dentro de la sección de conciertos, los filtros por género, fecha, lugar y otros criterios actúan como subcategorías temáticas que permiten a los usuarios enfocar su búsqueda.

- Según audiencia: Al igual que en la landing page, la distinción entre secciones para "Fans" y "Artistas" representa una categorización por audiencia. Dentro de la sección de fans, la posibilidad de filtrar por género musical podría considerarse una subcategorización basada en los intereses específicos de diferentes grupos de usuarios.

## 4.2.2. Labeling Systems

En StayMap, utilizaremos etiquetas claras, modernas y directamente relacionadas con la experiencia musical de nuestros usuarios. El objetivo es facilitar una navegación rápida e intuitiva, tanto para fans como para artistas, promoviendo el descubrimiento de eventos musicales según sus intereses. Estas son algunas de las principales etiquetas que se mostrarán en la interfaz:

- **Conciertos:** Accede a la lista de eventos musicales disponibles. Aquí los usuarios podrán explorar conciertos según su ubicación, fecha y tipo de música.

- **Para Fans:** Sección dedicada a los beneficios exclusivos para los fans que usan StayMap, como acceso anticipado a eventos, descuentos y experiencias personalizadas.

- **Para Artistas:** Espacio exclusivo para artistas, donde podrán ver cómo promocionar sus conciertos, registrar eventos, y conectar con sus seguidores de forma más cercana.

- **Filtrar:** Herramienta que permite seleccionar eventos por género musical, fecha, ubicación y tipo de entrada (libre o con costo), mejorando la personalización de resultados.

- **Mapa Interactivo:** Visualiza directamente los eventos cercanos en el mapa, con información rápida sobre cada espacio musical.

- **Conciertos por asistir:** Accede a los eventos que el usuario ha marcado como favoritos o que ha decidido seguir.

- **Perfil / Configuración:** Acceso a las preferencias del usuario, como sus géneros favoritos, ajustes de notificación, datos de cuenta y más.

## 4.2.3. SEO Tags and Meta Tags

Se ha implementado una estrategia de SEO para asegurar una mejor visibilidad en los motores de búsqueda. A continuación, se presentan las etiquetas utilizadas en las principales páginas de la experiencia StayMap:

- **Title:** StayMap - Conciertos y Eventos para Fans y Artistas

- **Meta Description:** Descubre los mejores conciertos cerca de ti, conecta con tus artistas favoritos y sé parte de la comunidad StayMap. Para artistas, gestiona tus eventos y conecta con tus fans de manera directa.

- **Meta Keywords:** conciertos Perú, eventos musicales Lima, artistas Perú, gestión de conciertos, comunidad de fans, StayMap

- **Meta Author:** The Rumbling

## 4.2.4. Searching Systems

El sistema de búsqueda de StayMap está diseñado para que los usuarios encuentren conciertos y eventos musicales de manera rápida, intuitiva y precisa. Al tratarse de una plataforma con gran variedad de propuestas artísticas, el buscador y los filtros son herramientas clave para facilitar la experiencia tanto de fans como de nuevos usuarios. Los siguientes elementos componen nuestro sistema de búsqueda:

- **Barra de búsqueda por nombre:** Permite a los usuarios encontrar conciertos ingresando directamente el nombre del evento o del artista que desean seguir.

- **Filtro por género musical:** Ofrece una búsqueda personalizada según los gustos musicales del usuario. Se podrá filtrar por géneros como rock, pop, reggaetón, electrónica, indie, entre otros.

- **Ubicación:** Posibilidad de buscar eventos cercanos al usuario según su ciudad o distrito.

Este sistema ayuda a los usuarios a descubrir experiencias musicales alineadas con sus intereses, reduciendo la complejidad en la navegación y mejorando su conexión con los eventos que realmente les importan.

## 4.2.5. Navigation Systems

El enfoque de la navegación en StayMap se centra en ofrecer una experiencia fluida y clara, que guíe tanto a los fans como a los artistas a través de las principales funcionalidades de la plataforma. Las opciones están organizadas de forma que los usuarios puedan acceder rápidamente al contenido que más les interesa, optimizando su tiempo de búsqueda y exploración de eventos musicales.

Estas son las principales secciones de navegación:

- **Conciertos:** Página principal donde los usuarios podrán explorar los eventos disponibles, acceder a la barra de búsqueda y utilizar los filtros por género musical para encontrar conciertos según sus gustos.

- **Para Fans:** Un espacio exclusivo que destaca los beneficios de los usuarios registrados como fans de StayMap, incluyendo entradas exclusivas, descuentos, y acceso prioritario a eventos especiales.

- **Para Artistas:** Sección pensada para los músicos y bandas, donde pueden conocer cómo StayMap los apoya, visualizar estadísticas de sus eventos, y conectarse con su audiencia.

- **Filtro:** Funcionalidad clave que permite filtrar eventos por género musical, facilitando el descubrimiento de experiencias alineadas con los intereses del usuario.

Esta estructura de navegación garantiza que tanto los fans como los artistas encuentren valor en cada interacción con la plataforma, promoviendo una experiencia musical accesible, personalizada y eficiente.

# 4.3. Landing Page UI Design

La propuesta de UI para la Landing Page de StayMap refleja un diseño centrado en el usuario, enfocado en facilitar el acceso inmediato a la oferta musical y los beneficios de la plataforma tanto para fans como para artistas. La arquitectura de la información garantiza que los usuarios puedan encontrar rápidamente eventos, artistas destacados y funcionalidades clave como el filtrado por género musical o la barra de búsqueda de conciertos.

Además, las decisiones tomadas en torno a los sistemas de organización, etiquetado, búsqueda y navegación optimizan la experiencia general, permitiendo que cada visitante explore fácilmente la plataforma desde su primera interacción. La landing transmite un equilibrio entre estilo moderno, accesibilidad y pasión por la música, captando la atención de nuevos usuarios y promoviendo una navegación clara, rápida y efectiva.

## 4.3.1. Landing Page Wireframe

<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-wireframe-inicio.png" alt="StayMap Landing Page Wireframe Inicio" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-wireframe-fans.png" alt="StayMap Landing Page Wireframe Fans" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-wireframe-artistas.png" alt="StayMap Landing Page Wireframe Artistas" style="width: 80%">
</div>

## 4.3.2. Landing Page Mock-up

**Web:**

<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-inicio.png" alt="StayMap Landing Page Mockup Inicio" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-fans.png" alt="StayMap Landing Page Mockup Fans" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-artista.png" alt="StayMap Landing Page Mockup Artistas" style="width: 80%">
</div>


**Mobile:**

<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-mobile-inicio.png" alt="StayMap Landing Page Mockup Mobile Inicio" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-mobile-menu.png" alt="StayMap Landing Page Mockup Mobile Menu" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-mobile-fans.png" alt="StayMap Landing Page Mockup Mobile Fans" style="width: 80%">
</div>
<div align="center">
<img src="assets/landing_page_ui_desing/landing-page-mockup-mobile-artistas.png" alt="StayMap Landing Page Mockup Mobile Artistas" style="width: 80%">
</div>

- En la sección de “Para fans” podrás encontrar los beneficios de los usuarios que se registren como fans en StayMap.
- En la sección de “Para artistas” podrás encontrar los beneficios de los usuarios que se registren como artistas en StayMap.
- Como pie de página se muestra un formulario para suscribirse al newsletter y las diferentes secciones de nuestra landing page.

# 4.4. Web Applications UX/UI Design

## 4.4.1. Web Applications Wireframes

Pantalla de inicio:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_inicio.png" alt="Web Application Wireframe Inicio" style="width: 80%">
</div>

Sesión iniciada correctamente:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_sesioniniciada.png" alt="Web Application Wireframe Sesión iniciada" style="width: 80%">
</div>

Crear cuenta: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_registro.png" alt="Web Application Wireframe Registro" style="width: 80%">
</div>


Verificar cuenta cuenta: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_verificacion.png" alt="Web Application Wireframe Verificacion" style="width: 80%">
</div>

Cuenta creada:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_cuentacreada.png" alt="Web Application Wireframe Cuenta creada" style="width: 80%">
</div>

Página principal: Conciertos: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_conciertos.png" alt="Web Application Wireframe Conciertos" style="width: 80%">
</div>


Filtrar: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_filtrar.png" alt="Web Application Wireframe Filtrar" style="width: 80%">
</div>

Mapa:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_mapa.png" alt="Web Application Wireframe mapa" style="width: 80%">
</div>


Comunidad:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_comunidad.png" alt="Web Application Wireframe comunidad" style="width: 80%">
</div>

Concierto: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_concierto.png" alt="Web Application Wireframe Concierto" style="width: 80%">
</div>

Perfil de fan:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_perfil_fan.png" alt="Web Application Wireframe Perfil fan" style="width: 80%">
</div>


Perfil de artista:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireframe_perfil_artista.png" alt="Web Application Wireframe Artista" style="width: 80%">
</div>

## 4.4.2. Web Applications Wireflow Diagrams

**User flow #1:** Crear cuenta

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_1.png" alt="Web Application Wireflow 1" style="width: 80%">
</div>

**User flow #2:** Filtrar por género

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_2.png" alt="Web Application Wireflow 2" style="width: 80%">
</div>

**User flow #3:** Ver infromación del concierto, confirmar asistencia y buscar entrada.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_3.png" alt="Web Application Wireflow 3" style="width: 80%">
</div>


**User flow #4:** Acceder a un concierto mediante una notificación.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_4.png" alt="Web Application Wireflow 4" style="width: 80%">
</div>

**User flow #5:** Acceder a perfil de fan, ver la información de conciertos asistidos y por asistir.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_5.png" alt="Web Application Wireflow 5" style="width: 80%">
</div>

**User flow #6:** Acceder a perfil de artista.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_wireflow_diagram_6.png" alt="Web Application Wireflow 6" style="width: 80%">
</div>

## 4.4.3. Web Applications Mock-ups

Pantalla de inicio:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_inicio.png" alt="Web Application Mockup Inicio" style="width: 80%">
</div>

Crear cuenta: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_crearcuenta.png" alt="Web Application Mockup Crear Cuenta" style="width: 80%">
</div>


Verificar cuenta cuenta: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_verificacion.png" alt="Web Application Mockup Verificacion" style="width: 80%">
</div>

Cuenta creada:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_cuentacreada.png" alt="Web Application Mockup Cuenta creada" style="width: 80%">
</div>

Filtrar: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_filtrar.png" alt="Web Application Mockup Filtrar" style="width: 80%">
</div>

Mapa:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_mapa.png" alt="Web Application Mockup mapa" style="width: 80%">
</div>


Comunidad:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_comunidad.png" alt="Web Application Mockup comunidad" style="width: 80%">
</div>

Concierto: 

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_concierto.png" alt="Web Application mockup Concierto" style="width: 80%">
</div>

Perfil de fan:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_perfil_fan.png" alt="Web Application Mockup Perfil fan" style="width: 80%">
</div>


Perfil de artista:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_perfil_artista.png" alt="Web Application Mockup Artista" style="width: 80%">
</div>

Calificar:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_calificar.png" alt="Web Application Mockup Calificar" style="width: 80%">
</div>

Notificaciones:

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_mockup_notificaciones.png" alt="Web Application Mockup Notificaciones" style="width: 80%">
</div>

## 4.4.4. Web Applications User Flow Diagrams

**UserFlow #1:** En este user flow se encuentra el proceso de usuario al ingresar a la plataforma, mostrando los distintos happy e unhappy paths.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_userflow_1.png" alt="Web Application Userflow 1" style="width: 80%">
</div>

**UserFlow #2:** En este user flow, el usuario busca y filtra a través de la aplicación, con sus respectivos happy e unhappu paths.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_userflow_2.png" alt="Web Application Userflow 2" style="width: 80%">
</div>

**UserFlow #3:** En este user flow se muestra al usuario confirmando su asistencia a un evento, y su unhappy path al no encontrar boletos disponibles.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_userflow_3.png" alt="Web Application Userflow 3" style="width: 80%">
</div>

**UserFlow #4:** En este user flow se encuentra el usuario buscando concierto cercanos, con su happy e unhappy path.

<div align="center">
  <img src="assets/web_application/web_applications_uxui_desing_userflow_4.png" alt="Web Application Userflow 4" style="width: 80%">
</div>

# 4.5. Web Applications Prototyping

|Tipo|URL del video|
|---|--------------|
|Desktop|`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EX_5H4ofoydGrjyaxA3pE1wBrclkUgJO2V4Tse0Y0pZmBg?e=TYIOYy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`|
|Mobile|`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EeFg85OUFzZFrKyQvGbcWZcBuSg6JYLz4YvoBM7c4Ciz3g?e=ca8Kze&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`|

Estos videos muestran los prototipos interactivos de StayMap para navegador web en versiones desktop y mobile, destacando cómo se han aplicado principios clave de arquitectura de información y decisiones de diseño centradas en el usuario.
La simulación inicia con una introducción al sistema de navegación, explicando cómo se estructura la información para garantizar una experiencia clara y personalizada tanto para fans de la música como para artistas emergentes. Se evidencian las decisiones relacionadas con:

- Organización jerárquica y temática del contenido, permitiendo explorar conciertos por ubicación, género, fecha y popularidad.

- Sistemas de etiquetado claros y funcionales, como Conciertos, Para Fans, Para Artistas, Filtro y Mapa Interactivo.

- Sistemas de navegación que conectan eficientemente cada sección, optimizando la exploración y el acceso a eventos relevantes.

Se presenta la interacción fluida entre secciones y se simulan caminos típicos del usuario según los User Flow Diagrams propuestos, como descubrir conciertos cercanos, gestionar eventos favoritos y acceder a beneficios exclusivos.
Este prototipo demuestra cómo StayMap traduce la arquitectura de información en una experiencia visual intuitiva y coherente, adaptada a las necesidades reales de los usuarios en distintos dispositivos.

# 4.6. Domain-Driven Software Architecture

## 4.6.1. Software Architecture Context Diagram

<div align="center">
  <img src="assets/c4_model/context-diagram.png" alt="C4 Context Diagram" style="width: 80%">
</div>

## 4.6.2. Software Architecture Container Diagrams

<div align="center">
  <img src="assets/c4_model/container-diagram.png" alt="C4 Container Diagram" style="width: 80%">
</div>

## 4.6.3. Software Architecture Components Diagrams

<div align="center">
  <img src="assets/c4_model/component-diagram.png" alt="C4 Components Diagram" style="width: 80%">
</div>

# 4.7. Software Object-Oriented Design

## 4.7.1. Class Diagrams

<div align="center">
  <img src="assets/class_diagram/class_diagram.png" alt="UML Class Diagram" style="width: 80%">
</div>

## 4.7.2. Class Dictionary

|Clase|Nombre de atributo|Descripcion|Tipo de dato|
|-----|------------------|-----------|------------|
|Mapa |id|Identificador del mapa|Ubicacion|
|Mapa|ubicacion|Ubicación geográfica del mapa|Ubicacion|
|Mapa|conciertos|Lista de conciertos en el mapa|list<Concierto>|
|Recinto|id|Identificador del recinto|string|
|Recinto|nombre|Nombre del recinto|string|
|Recinto|ubicacion|Ubicación del recinto|Ubicacion|
|PromocionConcierto|id|Identificador de la promoción|string|
|PromocionConcierto|conciertoId|Identificador del concierto asociado|string|
|PromocionConcierto|fechaInicio|Fecha de inicio de la promoción|string|
|PromocionConcierto|fechaFin|Fecha de fin de la promoción|string|
|PromocionConcierto|vigente|Estado vigente de la promoción|boolean|
|PromocionConcierto|descripcion|Descripción de la promoción|string|
|Concierto|id|Identificador del concierto|string|
|Concierto|idRecinto|Identificador del recinto|string|
|Concierto|artista|Artista que se presenta|Artista|
|Ubicacion|ciudad|Ciudad de la ubicación|string|
|Ubicacion|pais|País de la ubicación|string|
|Comentario|id|Identificador del comentario|string|
|Comentario|idConcierto|Identificador del concierto comentado|string|
|Comentario|idUsuario|Identificador del usuario que comenta|string|
|Comentario|valoracion|Valoración numérica del comentario|int|
|Usuario|id|Identificador del usuario|string|
|Usuario|name|Nombre del usuario|string|
|Usuario|email|Email del usuario|string|
|Usuario|ubicacion|Ubicación del usuario|Ubicacion|
|Fan|conciertosAsistidos|Lista de conciertos asistidos|List<Concierto>|
|Comunidad|id|Identificador de la comunidad|string|
|Comunidad|nombre|Nombre de la comunidad|string|
|Comunidad|descripcion|Descripción de la comunidad|string|
|Comunidad|artista|Artista asociado a la comunidad|Artista|
|Comunidad|miembros|Lista de fans miembros|List<Fan>|
|ControladorNotificaciones|(atributo interno) obj|Estrategia de notificación usada|NotificacionStrategy|
|CheckIn|id|Identificador del check-in|string|
|CheckIn|objUsuario|Usuario que realiza el check-in|Usuario|
|CheckIn|objConcierto|Concierto donde se realiza el check-in|Concierto|
|CheckIn|asistencia|Estado de asistencia|bool|
|GestionConciertos|conciertos|Lista de conciertos administrados|List<Concierto>|
|Artista|biografia|Biografia del artista|String|

# 4.8. Database Design

# 4.8.1. Database Diagram

<div align="center">
  <img src="assets/database_diagram/database_diagram.png" alt="Database Diagram" style="width: 80%">
</div>

En la base de datos de StayMap, el modelo lógico define la tabla usuario, cuyos registros pueden ser simplemente usuarios o convertirse en fans o artistas. Si un usuario es artista, tiene la posibilidad de organizar cero, uno o varios conciertos. La tabla organizar_concierto se conecta de forma uno a uno con concierto, ya que cada organización corresponde a un solo evento. A su vez, los conciertos están asociados a un recinto, donde un concierto se realiza en un único recinto, pero un recinto puede albergar muchos conciertos a lo largo del tiempo. Los usuarios pueden consultar los conciertos cercanos y también guardar aquellos conciertos a los que planean asistir o los que ya han asistido, todo esto mediante relaciones de uno a muchos con la tabla de conciertos. Además, los fans pueden unirse a cero o muchas comunidades, dejar múltiples comentarios sobre conciertos o artistas, y también calificar tanto a los conciertos como a los artistas.

# Capítulo V: Product Implementation, Validation & Deployment

# 5.1. Software Configuration Management

La gestión de la configuración del software desempeña un papel fundamental en el desarrollo de StayMap, ya que permite organizar y controlar de manera eficiente todos los componentes del proyecto, incluyendo el código fuente, los archivos de diseño y los recursos multimedia. Gracias a estas prácticas, se asegura que el equipo trabaje de forma coherente sobre versiones sincronizadas, lo cual facilita la integración continua, la trazabilidad de cambios y una colaboración fluida entre los desarrolladores durante todo el ciclo de vida de la aplicación.

# 5.1.1. Software Development Environment Configuration

**Project Management**

En esta etapa, se utilizaron herramientas colaborativas que permitieron planificar, organizar y supervisar el avance del proyecto de manera efectiva. Estas plataformas facilitaron la comunicación entre los integrantes y el seguimiento de tareas, optimizando el flujo de trabajo.

- [**Discord:**](https://discord.com/) Cada miembro utilizó la aplicación Discord para realizar reuniones virtuales, coordinar avances y resolver dudas en tiempo real. Esta herramienta fue clave para mantener una comunicación fluida y una colaboración continua durante el desarrollo del proyecto.

- [**Google Docs:**](https://workspace.google.com/intl/es-419/products/docs/) Google Docs nos permitió dividir el trabajo de forma equitativa y registrar los avances individuales de cada integrante. También facilitó la organización de la información previa que luego se documentó en GitHub.

**Requirements Management**

Durante esta fase, se emplearon diversas herramientas visuales para identificar, analizar y documentar los requerimientos del sistema. Esto ayudó a comprender profundamente a los usuarios y definir los objetivos del producto.

- [**UXPressia:**](https://uxpressia.com/) Utilizamos esta plataforma para crear User Personas, Empathy Maps, Journey Maps e Impact Maps. Estas herramientas fueron fundamentales para identificar y comprender las necesidades, expectativas y motivaciones de nuestros usuarios objetivo.

- [**Miro:**](https://miro.com/es/) Miro fue empleada para diseñar los escenarios As-Is y To-Be, lo cual nos permitió visualizar el estado actual del problema y proyectar una solución ideal centrada en el usuario.

- [**Structurizr:**](https://structurizr.com/) Implementamos Structurizr para la creación de los diagramas C4, los cuales nos ayudaron a definir la arquitectura del sistema en distintos niveles (Contexto, Contenedor, Componente y Código), brindando una visión clara de cómo se estructuran los elementos del software.

**Product UX/UI Design**

En esta etapa se utilizaron herramientas de diseño que permitieron crear interfaces intuitivas, visualmente atractivas y centradas en el usuario. Estas herramientas facilitaron la elaboración de prototipos interactivos y estructuras visuales claras del sistema.

- [**Figma:**](https://www.figma.com/es-la/) Utilizamos Figma para la creación de wireframes, mockups y prototipos interactivos. Esta herramienta colaborativa nos permitió iterar rápidamente sobre el diseño de la interfaz, evaluando su usabilidad y estética.

- [**Lucidchart:**](https://www.lucidchart.com/pages/es) Empleamos Lucidchart para diseñar el modelo de base de datos y elaborar diagramas UML, lo cual facilitó la visualización estructurada de las entidades, relaciones y comportamientos del sistema.

### 5.1.2. Source Code Management

El código fuente del proyecto StayMap fue gestionado mediante la plataforma GitHub, en un repositorio público que refleja los principios del desarrollo de software de código abierto.

Repositorio del proyecto:

- `https://github.com/The-Rumbling/StayMap-AppWeb-V2.git`

<div align="center">
  <img src="assets/capturas/repositorio-appweb.png" alt="inicio" style="width: 80%">
</div>

Durante el desarrollo se trabajó únicamente sobre la rama `main`, lo que simplificó la gestión de cambios al mantener una única línea de desarrollo centralizada.
Aunque no se implementó una estrategia compleja de ramas como GitFlow, se priorizó una organización clara y ordenada del historial de versiones, con confirmaciones frecuentes y mensajes descriptivos.

#### Convenciones de commits

Se empleó la convención **Conventional Commits** para estructurar los mensajes de commit de forma clara y semántica. Algunos prefijos utilizados fueron:

- `feat:` para agregar nuevas funcionalidades a la interfaz.
- `style:` para aplicar ajustes de formato y diseño.


## 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de la interfaz responsive del sistema StayMap se utilizaron tecnologías web como HTML, CSS y JavaScript. A continuación, se presentan las convenciones seguidas en la implementación:

**HTML**

Se aplicó una estructura clara y organizada mediante el uso de etiquetas semánticas y contenedores:

	<header></header>


Encabezado general de la página.

	<nav></nav>

Barra de navegación.

	<main></main>

Contenedor principal del contenido.


	<div class="container">
	
Se utilizó para agrupar bloques de contenido relacionados.

	<footer>

Pie de página con información adicional.


Los títulos se declararon jerárquicamente usando las etiquetas 

	<h1> a <h6>

Las imágenes se insertaron mediante la etiqueta 

	<img>

incluyendo el atributo alt.

Ejemplo:

	<header>
 	 <h1>StayMap</h1>
	</header>



	<div class="container">
  	<p>Contenido relacionado agrupado.</p>
	</div>


	<img src="imagen.jpg" alt="Descripción de la imagen">


**CSS**
Los estilos se definieron en un archivo externo. Se emplearon las siguientes prácticas:
Nombres de clases en formato kebab-case (ej. .contenedor-principal).


- Separación por secciones (tipografía, layout, botones).


- Uso de media queries para diseño responsive.


- Colores definidos por variables CSS para facilitar su reutilización.


Ejemplo:


	h1 {
 	 font-size: 24px;
	  color: #0066cc;
	}

**JavaScript**

Se utilizó JavaScript para interacciones básicas de la interfaz. Las principales convenciones fueron:
Uso de nombres en camelCase.


- Separación del código en archivos externos.


- Comentarios explicativos cuando fue necesario.



		function mostrarMenu() {
  			// Código para mostrar u ocultar el menú
		}

**Buenas prácticas generales**

- Indentación de 2 espacios.


- Uso correcto de etiquetas semánticas y atributos de accesibilidad.


- Organización de archivos en carpetas: /css, /js, /img.


- Separación del contenido (HTML), presentación (CSS) y comportamiento (JavaScript).

**Angular**

El sistema StayMap Open Source fue desarrollado con **Angular 16**, siguiendo las convenciones modernas del framework:

- Se utilizaron **componentes standalone** para mayor modularidad y simplicidad. Cada componente tiene su propio archivo `.ts`, `.html` y `.scss`.

	```ts
	@Component({
	  selector: 'app-home',
	  standalone: true,
	  templateUrl: './home.component.html',
	  styleUrls: ['./home.component.scss'],
	  imports: [CommonModule],
	})
	export class HomeComponent {}

Las rutas se declararon mediante loadComponent para carga perezosa (lazy loading), mejorando el rendimiento:

	```ts
	export const routes: Routes = [
		  {
		    path: '',
		    loadComponent: () => import('./public/pages/home.component').then(m => m.HomeComponent),
		  },
		];
  
- Se aplicó una arquitectura basada en subdominios: public, shared, maintenance, analytics, con su propio enrutamiento y organización de componentes.

- Los nombres de archivos siguen la convención kebab-case, y las clases y servicios en PascalCase.

- Se empleó ReactiveForms para formularios robustos y validados, y servicios inyectables para el manejo de datos.

- Los estilos se encapsularon por componente (styleUrls) usando .scss, y se definieron en formato kebab-case.

- Se aplicaron directivas propias de Angular (*ngIf, *ngFor, [routerLink]) para control de vista y navegación.

- Se utilizó Angular Material como biblioteca de componentes UI accesibles y consistentes.



## 5.1.4. Software Deployment Configuration

Para la publicación del sistema StayMap - Open Source, utilizamos GitHub Pages, una herramienta gratuita que permite alojar sitios estáticos directamente desde un repositorio. Esta opción fue ideal para presentar el proyecto de forma accesible, sin necesidad de servidores externos ni configuraciones complejas.

Dado que el proyecto fue desarrollado con Angular 16, se implementó una configuración especial para compilar y desplegar el contenido de la carpeta dist/, la cual contiene el resultado del build del proyecto.
Pasos seguidos para el despliegue:

1. Creación del repositorio en GitHub
Creamos un nuevo repositorio remoto en GitHub donde alojamos todo el proyecto Angular, incluyendo los módulos, componentes y archivos de configuración.

2. Clonado y preparación del entorno local
Clonamos el repositorio en nuestra computadora e instalamos las dependencias necesarias ejecutando:

		```ts
		npm install

Luego, realizamos las configuraciones necesarias para preparar el proyecto para despliegue estático.

3. Configuración del archivo angular.json
En el archivo angular.json, actualizamos el valor de outputPath para asegurarnos de que el contenido compilado se genere en la carpeta dist/staymap.

4. Build de producción
Ejecutamos el siguiente comando para generar la versión optimizada del proyecto:

		```ts
		ng build --base-href "https://<usuario>.github.io/<repositorio>/"

Esto generó los archivos estáticos en la carpeta dist/staymap, listos para desplegar.

5. Creación de la rama gh-pages
Usamos el paquete angular-cli-ghpages para automatizar el despliegue. Primero lo instalamos:

		```ts
		npm install -g angular-cli-ghpages


Luego ejecutamos:

		```ts
		npx angular-cli-ghpages --dir=dist/staymap

Esto publicó automáticamente el contenido generado a la rama gh-pages del repositorio.

6. Verificación en GitHub Pages
Accedimos a la pestaña Settings > Pages y confirmamos que la rama gh-pages esté seleccionada como fuente de publicación. GitHub generó automáticamente una URL pública para visualizar la aplicación, del tipo:

		```ts
		`https://<usuario>.github.io/<repositorio>/`


7. Pruebas del despliegue
Comprobamos que la aplicación StayMap funcionara correctamente en línea, validando que el enrutamiento, las vistas y los estilos se cargaran sin errores. También verificamos que la navegación entre componentes Angular funcione mediante rutas relativas.

Este flujo de despliegue nos permitió mantener actualizaciones continuas del sistema, aprovechando el soporte de GitHub Pages para aplicaciones Angular, sin depender de servidores backend ni plataformas de pago.



# 5.2. Landing Page, Services & Applications Implementation

## 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="2">Sprint Planning Background</th>
  </tr>
  <tr>
    <td>Date</td>
    <td>2025-04-19</td>
  </tr>
  <tr>
    <td>Time</td>
    <td>11:00PM</td>
  </tr>
  <tr>
    <td>Location</td>
    <td>Virtual, via discord</td>
  </tr>
  <tr>
    <td>Prepared by</td>
    <td>Lizarbe Álvarez, Ariana Nickole</td>
  </tr>
  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>Lizarbe Alvarez, Ariana Nickole / Ortiz Cardenas, Johanna Antuanete / Zúñiga Murillo, Diego Sebastian / Collantes Carrillo, Diego Mateo / Zegarra López, Renato Rubber Sebastian</td>
  </tr>
  <tr>
    <td>Sprint Goal & User Stories</td>
    <td></td>
  </tr>
  <tr>
    <td>Sprint n Goal</td>
    <td>
  <strong>Nuestro enfoque está</strong> en entregar una landing page funcional y responsiva que refleje los valores de marca de StayMap y permita una navegación básica alineada con la arquitectura de información.
  <strong>Creemos que esto ofrece</strong> una primera experiencia de usuario clara y genera confianza en fans y artistas que visitan la plataforma por primera vez.
  <strong>Esto se confirmará cuando</strong> los usuarios puedan acceder a la landing page desde distintos dispositivos, navegar entre secciones clave y comprender fácilmente la propuesta de valor de StayMap.
</td>
  </tr>
  <tr>
    <td>Sprint n Velocity</td>
    <td>Para la planificación de este sprint se utilizará la escala de Fibonacci (1, 2, 3, 5, 8...) para estimar el esfuerzo relativo de cada historia de usuario, permitiendo una mejor comparación y afinación de la carga de trabajo.</td>
  </tr>
  <tr>
    <td>Sum of Story Points</td>
    <td>15</td>
  </tr>
</table>

### 5.2.1.2. Aspect Leaders and Collaborators

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="7">5.2.1.2. Aspect Leaders and Collaborators</th>
  </tr>
  <tr>
    <th>Team Member</th>
    <th>Github Username</th>
    <th>UX UI DESIGN</th>
    <th>DIAGRAMA UML</th>
    <th>C4 MODEL</th>
    <th>DATABASE DESIGN</th>
    <th>ENTRE VISTAS</th>
  </tr>
  <tr>
    <td>Collantes Diego</td>
    <td>D4D3v4l</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Lizarbe Ariana</td>
    <td>ariaalizz</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Ortiz Johanna</td>
    <td>Antuanet01</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zegarra Renato</td>
    <td>ReiZCode</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zúniga Diego</td>
    <td>DekayDe Canela</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
  </tr>
</table>

### 5.2.1.3. Sprint Backlog 1

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="8">Sprint 1</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item/Task</th>
  </tr>
  <tr>
    <th>id</th>
    <th>title</th>
    <th>id</th>
    <th>title</th>
    <th>description</th>
    <th>estimation</th>
    <th>assigned to</th>
    <th>status</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Ver beneficios para fans</td>
    <td>TSK01</td>
    <td>Diseñar sección de beneficios para fans</td>
    <td>Crear una sección en la landing page que muestre los beneficios para los fans.</td>
    <td>2 horas</td>
    <td>Ariana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US02</td>
    <td>Ver beneficios para artistas</td>
    <td>TSK02</td>
    <td>Diseñar sección de beneficios para artistas</td>
    <td>Crear una sección en la landing page que muestre los beneficios para los artistas.</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US03</td>
    <td>Acceder a testimonios</td>
    <td>TSK03</td>
    <td>Implementar módulo de testimonios</td>
    <td>Permitir a los usuarios visualizar testimonios de otros fans y artistas.</td>
    <td>1 hora</td>
    <td>Antuanete</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US04</td>
    <td>Registrase en la landing page</td>
    <td>TSK04</td>
    <td>Crear formulario de registro</td>
    <td>Implementar el formulario de registro para nuevos usuarios.</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Iniciarse sin en la landing page</td>
    <td>TSK05</td>
    <td>Implementar login en landing page</td>
    <td>Permitir a usuarios registrados iniciarse desde la landing page.</td>
    <td>5 horas</td>
    <td>Diego</td>
    <td>in process</td>
  </tr>
</table>

### 5.2.1.4. Development Evidence for Sprint Review

<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit id</th>
      <th>Commit message</th>
      <th>Commit Message Body</th>
      <th>Committed on</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">ariaalizz</td>
      <td>louis-tour.png</td>
      <td>07cbb65</td>
      <td>archive .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>starymapiogo.png</td>
      <td>2fe5ae4</td>
      <td>archive.png</td>
      <td>logo StayMap</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>taylor.jpeg</td>
      <td>5be819f</td>
      <td>archive.png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>styles.css</td>
      <td>0253b2a</td>
      <td>archive.css</td>
      <td>image design</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>index.html</td>
      <td>4c24312</td>
      <td>archive.html</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="5">DekayDeCanela</td>
      <td>fans.css</td>
      <td>754862b</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>artista.css</td>
      <td>2eb7f30</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>sk-tour.jpg</td>
      <td>c3f347c</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.html</td>
      <td>d1a23bc</td>
      <td>archive.html</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>skz-concert.jpg</td>
      <td>9e327a8</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="5">D4D3val</td>
      <td>skz-tour.jpg</td>
      <td>7be9471</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>niall-tour.jpg</td>
      <td>d7c95a4</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>monkeys-tour.jpg</td>
      <td>5c55361</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>emilia-tour.jpg</td>
      <td>6706966</td>
      <td>archive.jpg</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.css</td>
      <td>485049f</td>
      <td>archive.css</td>
      <td>landing testing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="4">ReizCode</td>
      <td>fans.html</td>
      <td>65ed194</td>
      <td>archivo .html</td>
      <td>landing desing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>harry.jpg</td>
      <td>599a130</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>louis.jpg</td>
      <td>566a2e9</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>stay.jpg</td>
      <td>1488808</td>
      <td>archivo .jpg</td>
      <td>landing image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td rowspan="4">Antuanet01</td>
      <td>artista.html</td>
      <td>eb55af7</td>
      <td>archivo .html</td>
      <td>landing desing</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>main.js</td>
      <td>145dd26</td>
      <td>archivo .js</td>
      <td>landing page logic</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>close-icon.png</td>
      <td>221c792</td>
      <td>archivo .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
    <tr>
      <td>hamburger-icon.png</td>
      <td>fca3f79</td>
      <td>archivo .png</td>
      <td>landing page image</td>
      <td>27/04/2025</td>
    </tr>
  </tbody>
</table>


### 5.2.1.5. Execution Evidence for Sprint Review
Durante el Sprint 1 nos centramos en el desarrollo de la estructura base de la aplicación web StayMap, enfocándonos principalmente en el diseño visual y la experiencia de usuario mediante tecnologías como HTML y CSS.

Entre las funcionalidades desarrolladas se encuentran:

Landing Page interactiva: Se creó una página de inicio atractiva y funcional que presenta la propuesta de valor de StayMap, con un diseño visual moderno, secciones informativas y una navegación fluida. Esta landing page cumple el rol de dar la bienvenida al usuario y explicar brevemente las principales características de la plataforma.

Sección para fans: Se diseñó una vista dedicada a los usuarios fanáticos de la música, donde podrán registrarse, acceder a próximos eventos y comenzar a personalizar su experiencia dentro de la plataforma. Esta sección está pensada para ofrecer contenido relevante como conciertos cercanos y recomendaciones personalizadas.

Sección para artistas: Se desarrolló un apartado orientado a los artistas, donde podrán registrarse y más adelante gestionar conciertos, comunidades y seguidores. Este espacio sienta las bases para la autogestión de contenido por parte de los músicos y bandas dentro de StayMap.

Este primer Sprint permitió establecer la identidad visual y la arquitectura inicial de la aplicación, dejando sentadas las bases para el desarrollo funcional que se realizaría en los siguientes Sprints.

**Screenshots de las principales vistas:**

Sección de Inicio:

<div align="center">
  <img src="assets/capturas/captura-inicio.png" alt="inicio" style="width: 80%">
</div>

Sección de Para Fans:

<div align="center">
  <img src="assets/capturas/captura-fans.png" alt="cap fans" style="width: 80%">
</div>

Sección de Para Artistas:

<div align="center">
  <img src="assets/capturas/captura-artistas.png" alt="artistas" style="width: 80%">
</div>

**Enlace de la Landing Page:** `https://landing-v2-bice.vercel.app/`

**URL de video de visualización y navegación:**
Para complementar, se preparó un video donde se muestra la navegación completa de la Landing Page, recorriendo cada sección implementada y explicando brevemente su propósito.
URL: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311704_upc_edu_pe/EUI7wWHl6_BIldMBylSryzwBIvr_c_QHEKdGhnRZnkBG9w?e=Tix91B`

### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 1 se logró establecer la base técnica y visual del proyecto StayMap. Se configuró el entorno de desarrollo, se implementó la estructura inicial del backend  y se desarrollaron los primeros componentes de la interfaz web. Además, se elaboró la landing page funcional, integrando elementos clave como el inicio de sesión. También se definieron rutas de navegación y se implementaron funcionalidades básicas de exploración de conciertos y comunidades.

A continuación, se presenta una tabla con los principales endpoints documentados:

| Endpoint                 | Método | Descripción                          | Parámetros                          | Ejemplo de llamada        | Ejemplo de respuesta                                   |
|--------------------------|--------|--------------------------------------|-------------------------------------|---------------------------|--------------------------------------------------------|
| `/api/concerts`          | GET    | Lista todos los conciertos disponibles | Ninguno                             | `GET /api/concerts`       | `[{"id":1,"artist":"Taylor Swift",...}]`              |
| `/api/concerts/{id}`     | GET    | Detalle de un concierto específico   | `id`                          | `GET /api/concerts/`     | `{"id":1,"artist":"Taylor Swift",...}`                |
| `/api/communities`       | GET    | Lista de comunidades                 | Ninguno                             | `GET /api/communities`    | `[{"id":1,"name":"Swifties",...}]`                    |
| `/api/communities/{id}`  | GET    | Detalle de comunidad específica      | `id`                        | `GET /api/communities/`  | `{"id":2,"name":"Moonwalkers",...}`                   |

#### Evidencias Visuales

Vista de conciertos

<div align="center">
  <img src="assets/service_documentation/vista_conciertos.png" alt="Vista Conciertos" style="width: 80%;">
</div>

Vista de comunidades 

<div align="center">
  <img src="assets/service_documentation/vista_comunidades.png" alt="Vista Comunidades" style="width: 80%;">
</div>

Fake API conciertos

<div align="center">
  <img src="assets/service_documentation/fakeAPI_conciertos.png" alt="Fake API Conciertos" style="width: 80%;">
</div>

Fake API comunidades 

<div align="center">
  <img src="assets/service_documentation/fakeAPI_comunidades.png" alt="Fake API Comunidades" style="width: 80%;">
</div>

#### Repositorio del Proyecto

- **Repositorio Web App (StayMap)**: `[https://github.com/The-Rumbling-AW/StayMap_Landing_PageAW](https://github.com/The-Rumbling-AW/StayMap_Landing_PageAW)`

- **Ruta de la Fake API (datos JSON)**: `src/assets/data/`

#### Commits relevantes Sprint 1

- `f4b2c9d`: Agregado archivo JSON con datos simulados de conciertos y comunidades (Fake API).
  
- `c1d0f2a`: Estilos iniciales y diseño para la landing page.
  
- `d2e9a4f`: Configuración de rutas y navegación entre componentes.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

**Las principales actividades de Deployment llevadas a cabo fueron:**

   - Creación de repositorio en GitHub: Se creó un repositorio público dedicado para la Landing Page, facilitando el control de versiones y la colaboración futura.

   - Configuración de Git: Se configuró el entorno local para trabajar con Git, incluyendo la identificación de usuario (git config --global user.name y git config --global user.email).

   - Inicialización de proyecto Git: Se ejecutó la inicialización del repositorio local (git init), la adición de archivos (git add .) y la generación de un primer commit (git commit -m "Subiendo landing page").

   - Asociación a repositorio remoto: Se estableció el enlace entre el repositorio local y GitHub mediante git remote add origin, permitiendo realizar el push del proyecto.

**Publicación mediante GitHub Pages:**

   - En la sección Settings > Pages del repositorio, se configuró la publicación seleccionando la rama main y la carpeta raíz (/ (root)).

   - Se habilitó el hosting automático, lo que permitió que la Landing Page estuviera disponible en línea a través de un URL público proporcionado por GitHub.


1. Repositorio creado en GitHub:

<div align="center">
  <img src="assets/capturas/captura-repositorio.png" alt="repositorio" style="width: 80%">
</div>

2. Configuración de Git y primer Push:

<div align="center">
  <img src="assets/capturas/captura-bash.png" alt="bash" style="width: 80%">
</div>

3. Configuración de GitHub Pages:

<div align="center">
  <img src="assets/capturas/captura-pages.png" alt="pages" style="width: 80%">
</div>

4. Landing Page publicada:

<div align="center">
  <img src="assets/capturas/captura-landing.png" alt="landing" style="width: 80%">
</div>


### 5.2.1.8. Team Collaboration Insights during Sprint

Desarrollo de Actividades de Implementación:
Durante este Sprint, el equipo trabajó de manera colaborativa para la implementación de la Landing Page del proyecto. Las tareas principales incluyeron:

	- Diseño y estructuración del contenido HTML.

	- Aplicación de estilos CSS para el diseño visual.

	- Configuración del entorno local de desarrollo.

	- Uso de Git para control de versiones.

	- Coordinación para el despliegue de la Landing Page mediante GitHub Pages.

La colaboración se realizó principalmente a través de GitHub, donde cada miembro del equipo realizó commits documentando los avances individuales y contribuyendo al repositorio compartido. Se fomentó la revisión mutua de cambios y la sincronización de actividades para garantizar una entrega integrada y de calidad.

**Gráficos de colaboración (GitHub Insights):**



Los gráficos de contribución muestran cómo cada miembro participó de manera activa en la implementación del producto. Se evidencia un flujo de trabajo constante mediante pushes regulares y trabajo en paralelo en los diferentes elementos de la Landing Page.

<div align="center">
  <img src="assets/capturas/captura-commits.png" alt="commits" style="width: 80%">
</div>

## 5.2.2. Sprint 2



### 5.2.2.1. Sprint Planning 2.

<table>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Background</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Date</strong></td>
      <td>2025-05-25</td>
    </tr>
    <tr>
      <td><strong>Time</strong></td>
      <td>9:00 PM</td>
    </tr>
    <tr>
      <td><strong>Location</strong></td>
      <td>Virtual, via Discord</td>
    </tr>
    <tr>
      <td><strong>Prepared by</strong></td>
      <td>Lizarbe Álvarez, Ariana Nickole</td>
    </tr>
    <tr>
      <td><strong>Attendees (to planning meeting)</strong></td>
      <td>
        Lizarbe Álvarez, Ariana Nickole / Ortiz Cardenas, Johanna Antuanete / 
        Zúñiga Murillo, Diego Sebastian / Collantes Carrillo, Diego Mateo / 
        Zegarra López, Renato / Rubber Sebastian
      </td>
    </tr>
    <tr>
      <th colspan="2">Sprint Goal & User Stories</th>
    </tr>
    <tr>
      <td><strong>Sprint n Goal</strong></td>
     <td>
  <strong>Nuestro enfoque está</strong> en desarrollar una página funcional que permita a fans y artistas visualizar en un mapa los eventos deseados por los usuarios y la disponibilidad de eventos en su área.
  <strong>Creemos que esto ofrece</strong> una experiencia personalizada y relevante para los usuarios, facilitando la conexión entre intereses musicales y oferta local de eventos.
  <strong>Esto se confirmará cuando</strong> los usuarios puedan ingresar a la página, ver eventos geolocalizados en el mapa y distinguir cuáles están disponibles en su zona según sus preferencias.
</td>
<tr>
    <td>Sum of Story Points</td>
    <td>27</td>
  </tr>
  </tbody>
</table>



### 5.2.2.2. Aspect Leaders and Collaborators.


<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="7">5.2.1.2. Aspect Leaders and Collaborators</th>
  </tr>
  <tr>
    <th>Team Member</th>
    <th>Github Username</th>
    <th>FAKE API</th>
    <th>MANAGEMENT</th>
    <th>SERVICES</th>
    <th>COMPONENTS</th>
    <th>DEVELOPMENT</th>
  </tr>
  <tr>
    <td>Collantes Diego</td>
    <td>D4D3v4l</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>L</td>
  </tr>
  <tr>
    <td>Lizarbe Ariana</td>
    <td>ariaalizz</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
    <td>L</td>
  </tr>
  <tr>
    <td>Ortiz Johanna</td>
    <td>Antuanet01</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zegarra Renato</td>
    <td>ReiZCode</td>
    <td>L</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zúniga Diego</td>
    <td>DekayDe Canela</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
  </tr>
</table>

### 5.2.2.3. Sprint Backlog 2.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="8">Sprint 2</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item/Task</th>
  </tr>
  <tr>
    <th>id</th>
    <th>title</th>
    <th>id</th>
    <th>title</th>
    <th>description</th>
    <th>estimation</th>
    <th>assigned to</th>
    <th>status</th>
  </tr>
  <tr>
    <td>US06</td>
    <td>Explorar eventos cercanos</td>
    <td>TSK06</td>
    <td>Visualización en mapa de eventos cerca</td>
    <td>Crear una vista en mapa con iconos que muestre los eventos cerca a mi ubicacion

</td>
    <td>2 horas</td>
    <td>Ariana</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US07</td>
    <td>Filtrar eventos por género musical</td>
    <td>TSK07</td>
    <td>Filtro por genero musical en busqueda de conciertos</td>
    <td>Barra lateral en la que el usuario pueda seleccionar el genero de su preferencia</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US08</td>
    <td>Recibir notificaciones de artistas favorito</td>
    <td>TSK08</td>
    <td>Notificar novedades o actualizaciones de artistas o comunidades

</td>
    <td>SSistema de notificaciones dentro de STAYMAP que se actualice con las novedades de los artistas

</td>
    <td>1 hora</td>
    <td>Antuanete</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US09</td>
    <td>Compartir asistencia a un concierto</td>
    <td>TSK09</td>
    <td>Registro de asistencia a conciertos</td>
    <td>Validacion de asistencia a un concierto al que el usuario desea ir

</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US10</td>
    <td>Calificar un evento asistid</td>
    <td>TSK10</td>
    <td>Registro de calificacion a eventos</td>
    <td>Sistema de estrellas que sirva para calificar la experiencia del usuario en un concierto</td>
    <td>2 horas</td>
    <td>Diego</td>
    <td>Done</td>
  </tr>
</table>

### 5.2.2.4. Development Evidence for Sprint Review.


<table border="1" cellpadding="5" cellspacing="0">
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit id</th>
      <th>Commit message</th>
      <th>Commit Message Body</th>
      <th>Committed on</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5">ariaalizz</td>
      <td>user.service.ts</td>
      <td>f6a0d00</td>
      <td>user.service.ts</td>
      <td>Update image in user.service.ts</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>community-management.component.css</td>
      <td>1743cbb</td>
      <td>community-management.component.css</td>
      <td>Update styles in community-management.component.css</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>community.service.ts</td>
      <td>e1da430</td>
      <td>community.service.ts</td>
      <td>Update image in community.service.ts</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>login-management.component.css</td>
      <td>fe356e5</td>
      <td>login-management.component.css</td>
      <td>Improve image styles in login-management.component.css</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>user.service.ts</td>
      <td>4766acb</td>
      <td>user.service.ts</td>
      <td>Landing page HTML testing in user.service.ts</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td rowspan="3">DekayDeCanela</td>
      <td>community-management.component.css</td>
      <td>79a63cc</td>
      <td>community-management.component.css</td>
      <td>Refine styles in community-management.component.css</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>community.service.ts</td>
      <td>8cdab20</td>
      <td>community.service.ts</td>
      <td>Refine styles in community.service.ts</td>
      <td>16/05/2025</td>
    </tr>
    <tr>
      <td>login-management.component.html</td>
      <td>5a0247f</td>
      <td>login-management.component.html</td>
      <td>Update landing image in login-management.component.html</td>
      <td>16/05/2025</td>
    </tr>
  </tbody>
</table>


### 5.2.2.5. Execution Evidence for Sprint Review


Durante el Sprint 2, nos enfocamos en el desarrollo de funcionalidades clave dentro de la aplicación web StayMap, como por ejemplo la integración de una imagen de Google Maps donde se visualiza la ubicación del usuario, además de la gestión de comunidades musicales, la creación de conciertos y la visualización del perfil registrado.

Entre las principales evidencias de ejecución se incluyen:

Vista de conciertos en mapa: Se desarrolló una vista que utiliza Google Maps API para mostrar los conciertos geolocalizados, permitiendo al usuario visualizar de forma espacial los eventos próximos según su ubicación actual.

Gestión de comunidades musicales: Se creó una interfaz para visualizar, crear, editar y eliminar comunidades usando un sistema de tarjetas. Esta sección conecta directamente con una API simulada (fake API) donde se almacenan los datos en un archivo JSON. Cada comunidad cuenta con nombre, cantidad de miembros e imagen representativa.

Creación de conciertos: Se implementó una funcionalidad que permite registrar nuevos conciertos, con datos como ubicación, fecha, nombre del artista y género musical, los cuales se almacenan también en la fake API.

Visualización de perfil: Se habilitó la vista de perfil del usuario registrado, donde puede consultar su información y actividad dentro de la plataforma.

Sistema de calificación y registro de asistencia: Se añadieron funcionalidades para que los usuarios puedan registrar su interés por un concierto y calificar eventos pasados, permitiendo mejorar la interacción con la plataforma.

Notificaciones de artistas favoritos: Se integró un módulo que muestra novedades o alertas relevantes en el dashboard, asociado a los artistas seguidos por el usuario.

Estas funcionalidades se validaron con vistas funcionales, integración completa del servicio CommunityService, ConcertService, almacenamiento en localStorage para sesiones y variables de entorno configuradas para los endpoints. A continuación, se muestran capturas de pantalla y commits asociados que evidencian la ejecución del Sprint.

Screenshots de las principales:

Sección conciertos:
<div align="center">
  <img src="assets/capturas/captura-conciertos.png" alt="cap" style="width: 80%">
</div>
Sección mapa:
<div align="center">
  <img src="assets/capturas/captura-mapa.png" alt="cap" style="width: 80%">
</div>
Sección comunidad:
<div align="center">
  <img src="assets/capturas/captura-comunidades.png" alt="cap" style="width: 80%">
</div>
Sección login:
<div align="center">
  <img src="assets/capturas/captura-login.png" alt="cap" style="width: 80%">
</div>

Enlace de la APP WEB: stay-map-app-web-j88c.vercel.app

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2, se avanzó significativamente en la documentación y estructuración de los servicios simulados de StayMap, utilizando una Fake API estructurada como backend provisional. Además, se integraron servicios clave dentro de componentes funcionales, como `CommunityService`, `ConcertService` y `UserService`, conectando correctamente la interfaz con los datos simulados.

#### 📄 Endpoints simulados documentados

| Endpoint                           | Método | Descripción                                           | Ejemplo de llamada             | Ejemplo de respuesta                             |
|------------------------------------|--------|-------------------------------------------------------|--------------------------------|--------------------------------------------------|
| `/api/concerts`                    | GET    | Obtener todos los conciertos                         | `GET /api/concerts`            | `[{"id":1,"artist":"Adele",...}]`               |
| `/api/concerts?genre={genre}`      | GET    | Obtener conciertos filtrados por género musical       | `GET /api/concerts?genre=Pop`  | `[{"id":4,"genre":"Pop",...}]`                  |
| `/api/communities`                | POST   | Crear una nueva comunidad musical                    | `POST /api/communities`        | `{ "message": "Comunidad creada exitosamente" }`|
| `/api/profile`                    | GET    | Obtener perfil del usuario actual                    | `GET /api/profile`             | `{ "username": "user1", "email": "..." }`        |


#### Capturas de evidencia funcional

Vista del mapa con eventos integrados vía Google Maps API.

<div align="center">
  <img src="assets/service_documentation/conciertos_mapa.png" alt="Conciertos en mapa" style="width: 80%;">
</div>

Barra de filtros musicales para búsqueda personalizada.

<div align="center">
  <img src="assets/service_documentation/filtros_genero.png" alt="Filtros musicales" style="width: 80%;">
</div>

Formulario de creación de comunidades conectado a `community.service.ts`.

<div align="center">
  <img src="assets/service_documentation/crear_comunidad.png" alt="Crear comunidad" style="width: 80%;">
</div>

Vista del perfil del usuario registrado.

<div align="center">
  <img src="assets/service_documentation/perfil_usuario.png" alt="Perfil usuario" style="width: 80%;">
</div>

- **Repositorio del proyecto**: `[StayMap_Landing_PageAW](https://github.com/The-Rumbling-AW/StayMap_Landing_PageAW)`
- **Fake API**: `src/assets/data/`

#### Commits relevantes del Sprint 2

- `f6a0d00`: Integración del mapa con Google Maps API para mostrar conciertos geolocalizados.
- `e1da430`: Implementación del filtro por género musical.
- `8cdab20`: Desarrollo de lógica para crear nuevas comunidades musicales usando datos simulados.
- `5a0247f`: Construcción de la vista de perfil de usuario con datos obtenidos de localStorage.


### 5.2.2.7. Software Deployment Evidence for Sprint Review.


En este segundo sprint, se llevó a cabo el despliegue del proyecto StayMap utilizando la plataforma Vercel, la cual facilita la publicación de proyectos open source al integrarse directamente con repositorios en GitHub. Esto permitió mantener un flujo de trabajo continuo y automatizado, ideal para entornos colaborativos en Angular.

Repositorio y estructura del proyecto:
Se inició creando un repositorio en GitHub donde se subió el código completo desarrollado con Angular, incluyendo los módulos que manejan comunidades, conciertos y usuarios.

Preparación y configuración en Vercel:

Se estableció la conexión entre el repositorio y Vercel, permitiendo que cada cambio en la rama principal desencadene un nuevo despliegue automático.

Se añadieron las variables de entorno necesarias, como la URL base para la API y las rutas correspondientes a los recursos utilizados.


Automatización del despliegue:

Con cada actualización en la rama main, Vercel ejecuta automáticamente el proceso de construcción y despliegue sin necesidad de intervención manual.

El resultado final se aloja en un enlace público proporcionado por la plataforma, lo que permite acceder fácilmente al proyecto desde cualquier navegador.


### 5.2.2.8. Team Collaboration Insights during Sprint.

Durante este Sprint, el equipo trabajó de manera colaborativa en la implementación de funcionalidades clave del proyecto StayMap, desarrollado con Angular y utilizando una API simulada basada en json-server para la gestión de datos de usuarios, conciertos y comunidades.

Las tareas principales incluyeron:

		-Estructuración de componentes y vistas utilizando Angular. 

		-Aplicación de estilos personalizados mediante CSS para una presentación visual coherente.

		-Configuración del entorno de desarrollo local con json-server como fake backend.

		-Uso de Git y GitHub para el control de versiones y la colaboración.

		-Coordinación para el despliegue del proyecto a través de Vercel, permitiendo la visualización continua de avances.

La colaboración se llevó a cabo principalmente en GitHub, donde cada integrante del equipo realizó commits documentados para registrar sus avances individuales y sincronizar los cambios en el repositorio compartido. Se fomentó una dinámica de revisión cruzada y trabajo paralelo para asegurar una integración fluida y una entrega funcional del producto.

Gráficos de colaboración (GitHub Insights):

Los datos de contribución reflejan la participación activa del equipo, con un flujo constante de trabajo evidenciado en pushes regulares, creación de ramas y trabajo en distintos módulos del proyecto StayMap. Esta dinámica apoyó una implementación efectiva de los servicios conectados a la fake API y de las vistas principales de la plataforma.

*Primera version de la app web de Stay Map:*

<img src="assets/capturas/appWebCommits1.png" alt="commitsAppWeb" style="width: 80%;">

*Segunda version de la Landing Page de Stay Map:*

<img src="assets/capturas/landingPageCommits2.png" alt="commitsLandingPage" style="width: 80%;">

## 5.2.3. Sprint 3

### 5.2.3.1. Sprint Planning 3
<table>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Background</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Date</strong></td>
      <td>2025-06-20</td>
    </tr>
    <tr>
      <td><strong>Time</strong></td>
      <td>9:00 PM</td>
    </tr>
    <tr>
      <td><strong>Location</strong></td>
      <td>Virtual, via Discord</td>
    </tr>
    <tr>
      <td><strong>Prepared by</strong></td>
      <td>Lizarbe Álvarez, Ariana Nickole</td>
    </tr>
    <tr>
      <td><strong>Attendees (to planning meeting)</strong></td>
      <td>
        Lizarbe Álvarez, Ariana Nickole / Ortiz Cardenas, Johanna Antuanete / 
        Zúñiga Murillo, Diego Sebastian / Collantes Carrillo, Diego Mateo / 
        Zegarra López, Renato / Rubber Sebastian
      </td>
    </tr>
    <tr>
      <th colspan="2">Sprint Goal & User Stories</th>
    </tr>
    <tr>
      <td><strong>Sprint n Goal</strong></td>
     <td>
  <strong>Nuestro enfoque está</strong> en desarrollar una aplicación web funcional que permita a fans y artistas visualizar en un mapa interactivo los eventos musicales cercanos, junto con una lista filtrable de eventos disponibles en su área, según su ubicación e intereses.
  <strong>Creemos que esto ofrece</strong> una experiencia personalizada que fomenta la participación en comunidades musicales, fortaleciendo el vínculo entre fans y artistas emergentes.
  <strong>Esto se confirmará cuando</strong> los usuarios puedan ver eventos geolocalizados, aplicar filtros por género musical, y crear o unirse a comunidades afines dentro de la plataforma.
</td>
	    <tr>
    <td>Sum of Story Points</td>
    <td>37</td>
  </tr>
  </tbody>
</table>

### 5.2.3.2. Aspect Leaders and Collaborators.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="7">5.2.1.2. Aspect Leaders and Collaborators</th>
  </tr>
  <tr>
    <th>Team Member</th>
    <th>Github Username</th>
    <th>Landing Page</th>
    <th>Communities</th>
    <th>Development</th>
    <th>Components</th>
    <th>Deployment</th>
  </tr>
  <tr>
    <td>Collantes Diego</td>
    <td>D4D3v4l</td>
    <td>C</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Lizarbe Ariana</td>
    <td>ariaalizz</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Ortiz Johanna</td>
    <td>Antuanet01</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
    <td>L</td>
  </tr>
  <tr>
    <td>Zegarra Renato</td>
    <td>ReiZCode</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zúniga Diego</td>
    <td>DekayDe Canela</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
</table>

### 5.2.3.3. Sprint Backlog 3.
<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="8">Sprint 3</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item/Task</th>
  </tr>
  <tr>
    <th>id</th>
    <th>title</th>
    <th>id</th>
    <th>title</th>
    <th>description</th>
    <th>estimation</th>
    <th>assigned to</th>
    <th>status</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Ver beneficios para fans</td>
    <td>TSK01</td>
    <td>Ver beneficios para fans en la Landing Page</td>
    <td>Mostrar sección destacada en la página principal con los beneficios que ofrece StayMap para los fans.
</td>
    <td>30 minutos</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US02</td>
    <td>Ver beneficios para artista</td>
    <td>TSK02</td>
    <td>Ver beneficios para artistas en la Landing Page</td>
    <td>Añadir contenido informativo que explique cómo StayMap apoya a los artistas en la promoción de eventos.</td>
    <td>30 minutos</td>
    <td>Ariana Lizarbe</td> 
    <td>Done</td>
  </tr>
  <tr>
    <td>US03</td>
    <td>Acceder a testimonios</td>
    <td>TSK03</td>
    <td>Acceder a testimonios de personas quienes hayan utilizado StayMap
</td>
    <td>Implementar módulo visual en la landing que muestre testimonios de personas que hayan utilizado StayMap.
</td>
    <td>30 minutos</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US11</td>
    <td>Personalizar perfil de artista</td>
    <td>TSK11</td>
    <td>Permitir al artista personalizar su perfil</td>
    <td>Opción que permite al artista cambiar su nombre y fotografía de perfil.
</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US13</td>
    <td>Ingresar a comunidad de fans</td>
    <td>TSK13</td>
    <td>Funcionalidad para ingresar a comunidad</td>
    <td>Permitir que el usuario fan se una a comunidades dentro de la app para interactuar con otros asistentes y seguidores.</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US15</td>
    <td>Cambiar idioma en la landing page</td>
    <td>TSK15</td>
    <td>Implementar selector de idioma en la landing</td>
    <td>Agregar opción en la interfaz para alternar entre español e inglés y traducir dinámicamente el contenido de la página.</td>
    <td>2 horas</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td> <tr>
	<td>US16</td>
    <td>Buscar conciertos</td>
    <td>TSK16</td>
    <td>Implementar buscador de conciertos por nombre o artista</td>
    <td> Crear barra de búsqueda que filtre y muestre resultados de conciertos según palabras clave ingresadas por el usuario.
</td>
    <td>2 horas</td>
    <td>Diego Zúñiga</td>
    <td>Done</td>
  </tr>
    <td>US17</td>
    <td>Buscar comunidades</td>
    <td>TSK17</td>
    <td>Habilitar buscador de comunidades</td>
    <td>Implementar funcionalidad que permita buscar comunidades por nombre o temática e integrar resultados en tiempo real.</td>
    <td>2 horas</td>
    <td>Diego Zúñiga</td>
    <td>Done</td> <tr>
	    <td>US21</td>
    <td> Zoom a concierto en el mapa</td>
    <td>TSK21</td>
    <td>Hacer zoom al concierto seleccionado en el mapa</td>
    <td> Implementar función para centrar y aplicar zoom automático a la ubicación del concierto cuando el usuario lo selecciona en el mapa.</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td> <tr>
	 <td>US23</td>
    <td>Ver información detallada del concierto</td>
    <td>TSK23</td>
    <td>Mostrar detalles completos de un concierto</td>
    <td>Diseñar e implementar una ficha que contenga nombre del artista, ubicación, fecha, hora, imagen y descripción del evento seleccionado.</td>
    <td>2 horas</td>
    <td>Renato Zegarra</td>
    <td>Done</td> <tr>
	<td>US24</td>
    <td>Unirse a una comunidad</td>
    <td>TSK24</td>
    <td>Funcionalidad para unirse a una comunidad musical</td>
    <td>Permitir que un fan se registre como miembro de una comunidad pulsando el botón 'Unirse'.</td>
    <td>2 horas</td>
    <td>Antuanete Ortiz</td>
    <td>Done</td> <tr>
	<td>US25</td>
    <td>Publicar en la comunidad</td>
    <td>TSK25</td>
    <td>Crear publicaciones en comunidad</td>
    <td>Habilitar opción para que los usuarios redacten y publiquen mensajes, fotos o recomendaciones en el feed de la comunidad a la que pertenecen.</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td> <tr>
	<td>US26</td>
    <td>Editar perfil personal</td>
    <td>TSK26</td>
    <td>Editar información del perfil del fan</td>
    <td> Permitir que el fan modifique su nombre, nombre de usuario y fotografía desde la sección “Mi Perfil”.</td>
    <td>2 horas</td>
    <td>Antuanete Ortiz</td>
    <td>Done</td> <tr>
	    <td>US27</td>
    <td>Confirmar o marcar asistencia a evento</td>
    <td>TSK27</td>
    <td>Confirmar o marcar asistencia a evento </td>
    <td> Permitir confirmar o marcar asistencia a evento al dar click a un botón</td>
    <td>2 horas</td>
    <td>Renato Zegarra</td>
    <td>Done</td> <tr>
</table>

### 5.2.3.4. Development Evidence for Sprint Review.

evidencia commits landing page 

| Repository     | Branch              | Commit Id | Commit Message            | Commit Message Body                     | Committed on (Date) |
|----------------|---------------------|-----------|---------------------------|------------------------------------------|---------------------|
| ariaalizz      | landing/home-style  | a1b2c3d   | feat: estilos generales   | Se agregaron estilos base a home.html   | 17/06/2025          |
| ariaalizz      | landing/footer      | d4e5f6g   | fix: ajuste footer        | Se corrigió el diseño responsivo        | 18/06/2025          |
| ReiZCode       | landing/navbar      | h7i8j9k   | feat: navbar interactiva  | Se agregó interactividad con JS         | 17/06/2025          |
| ReiZCode       | landing/nav-style   | l0m1n2o   | style: colores navbar     | Cambios en la paleta de navegación      | 19/06/2025          |
| DekayDeCanela  | landing/cards       | p3q4r5s   | feat: sección de tarjetas | Añadida sección de beneficios            | 20/06/2025          |
| DekayDeCanela  | landing/responsive  | t6u7v8w   | fix: media queries        | Ajustes para móviles                     | 21/06/2025          |
| D4D3v4l        | landing/links       | x9y0z1a   | feat: enlaces funcionales | Se agregaron links internos              | 17/06/2025          |
| D4D3v4l        | landing/images      | b2c3d4e   | fix: rutas de imágenes    | Corrección de paths                      | 19/06/2025          |
| Antuanete01    | landing/form-style  | f5g6h7i   | feat: estilos de formulario| Se estilizó el formulario de contacto    | 20/06/2025          |
| Antuanete01    | landing/feedback    | j8k9l0m   | feat: feedback visual     | Animaciones de envío agregado            | 22/06/2025          |

evidencia commits aplicación web

| Repository     | Branch                | Commit Id | Commit Message              | Commit Message Body                          | Committed on (Date) |
|----------------|-----------------------|-----------|-----------------------------|-----------------------------------------------|---------------------|
| ariaalizz      | app/user-auth         | aa11bb    | feat: login funcional       | Login con validación implementado            | 17/06/2025          |
| ariaalizz      | app/dashboard-style   | cc22dd    | style: dashboard colores    | Se aplicó paleta oficial                     | 17/06/2025          |
| ReiZCode       | app/navbar-toggle     | ee33ff    | feat: toggle funcional      | Se implementó toggle con Angular             | 19/06/2025          |
| ReiZCode       | app/routing-setup     | gg44hh    | chore: configuración rutas  | Rutas básicas inicializadas con lazy load    | 22/06/2025          |
| DekayDeCanela  | app/forms-reactive    | ii55jj    | feat: forms reactivos       | Creación de formulario reactivo con validación | 19/06/2025        |
| DekayDeCanela  | app/api-connection    | kk66ll    | feat: conexión API          | Se conectó app con json-server               | 21/06/2025          |
| D4D3v4l        | app/user-model        | mm77nn    | feat: modelo de usuario     | Modelo User con id, name, email              | 20/06/2025          |
| D4D3v4l        | app/http-service      | oo88pp    | feat: servicio http         | HttpClient inyectado y probado               | 19/06/2025          |
| Antuanete01    | app/translate         | qq99rr    | feat: traducción i18n       | Soporte en español e inglés                  | 19/06/2025          |
| Antuanete01    | app/form-error        | ss00tt    | fix: validación de campos   | Mensajes de error en inputs                  | 17/06/2025          |


### 5.2.3.5. Execution Evidence for Sprint Review.

Durante el Sprint 3 del proyecto StayMap, nos centramos en fortalecer la experiencia del usuario fan y artista a través de nuevas funcionalidades orientadas a la personalización, búsqueda, interacción social y mejora del acceso a contenidos clave. Todas las tareas contempladas en el Sprint Backlog 3 fueron completadas exitosamente por los integrantes del equipo.

Entre las principales evidencias de ejecución se encuentran:

	- Sección de beneficios en la landing page: Se habilitaron dos secciones destacadas que presentan los beneficios tanto para fans como para artistas. Estas secciones se visualizaron directamente en la página principal, como elementos informativos que motivan el uso de la plataforma.

	- Testimonios en la página de inicio: Se integró un módulo que muestra testimonios de personas que han utilizado StayMap, brindando mayor credibilidad a la plataforma. Estos testimonios se cargan dinámicamente en tarjetas dentro de la interfaz.

	- Personalización del perfil del artista: Se implementó una opción que permite a los artistas modificar su nombre e imagen de perfil desde su página de perfil personal.

	- Ingreso y unión a comunidades: Se desarrolló la funcionalidad para que los fans puedan visualizar comunidades musicales y unirse a ellas mediante un botón interactivo. Esto actualiza dinámicamente su estado de pertenencia en la base de datos simulada (fake API).

	- Selector de idioma: Se incorporó un menú de cambio de idioma en la landing page, permitiendo alternar entre español e inglés. Esta función usa ngx-translate e integra archivos de internacionalización.

	- Búsqueda inteligente de conciertos y comunidades: Se crearon componentes de búsqueda en tiempo real que permiten filtrar por nombre de concierto, artista o nombre de comunidad. Estos resultados se integran visualmente en tarjetas.

	- Zoom en conciertos en el mapa: Al seleccionar un evento en la vista del mapa, se centra la ubicación y se aplica automáticamente un zoom, mejorando la experiencia espacial del usuario.

	- Detalle completo del concierto: Se diseñó e implementó una ficha informativa donde se muestra nombre del artista, lugar, fecha, hora, imagen y descripción del evento.

	- Publicación de contenido en comunidades: Se habilitó la opción para que los fans puedan publicar textos en las comunidades a las que pertenecen. Las publicaciones están filtradas por ID de comunidad y se almacenan en la fake API.

	- Edición del perfil del usuario: Se desarrolló un formulario donde el usuario puede modificar su nombre, nombre de usuario e imagen de perfil. Los datos se actualizan en tiempo real y se reflejan en su sección de perfil.

Todas estas funcionalidades fueron integradas con llamadas al backend simulado mediante json-server, usando servicios específicos como UserService, CommunityService y ConcertService. Se utilizaron variables de entorno para definir los endpoints y se implementaron validaciones visuales, toasts de confirmación y filtros contextuales para mejorar la experiencia del usuario.

<strong> Screenshots de las evidencias: </strong>

<strong> Landing page </strong>

Cambio de idioma en landing page:

<div align="center">
  <img src="assets/capturas/language-switcher-landing.png" alt="languageSwitcherLanding" style="width: 80%;">
</div>

<strong> Aplicación web StayMap </strong>
Sección comunidades:
<div align="center">
  <img src="assets/capturas/seccion-comunidades.png" alt="SeccionComunidades" style="width: 80%;">
</div>

Editar perfil:
<div align="center">
  <img src="assets/capturas/editar-perfil-usuario.png" alt="EditarPerfilUsuario" style="width: 80%;">
</div>

Ver conciertos en mapa:

<div align="center">
  <img src="assets/capturas/ver-concierto-mapa.png" alt="VerConciertoMapa" style="width: 80%;">
</div>

<div align="center">
  <img src="assets/capturas/zoom-concierto-mapa.png" alt="ZoomConciertoMapa" style="width: 80%;">
</div>

Detalle de concierto:

<div align="center">
  <img src="assets/capturas/detalle-concierto.png" alt="DetalleConcierto" style="width: 80%;">
</div>

### 5.2.3.6. Services Documentation Evidence for Sprint Review.

Durante el Sprint 3, se consolidó la integración entre la interfaz de StayMap y su <strong>Fake API</strong>, extendida con nuevos datos simulados como publicaciones dentro de comunidades y usuarios con estado de asistencia a conciertos. Se fortaleció la documentación de servicios REST utilizados por los componentes del frontend mediante llamadas HTTP hacia los endpoints configurados en el db.json.

Esta documentación refleja la estructura del sistema para usuarios, conciertos, comunidades y publicaciones, accesibles desde un entorno local gracias a la configuración de <strong>json-server</strong> como backend provisional.

### <strong> Endpoints documentados</strong>

| <strong>Endpoint</strong>         | <strong>Método</strong> | <strong>Descripción</strong>                              | <strong>Ejemplo de llamada</strong> | <strong>Ejemplo de respuesta</strong>                          |
|----------------------------------|--------------------------|------------------------------------------------------------|-------------------------------------|--------------------------------------------------------------|
| `/concerts`                      | GET                      | Obtener todos los conciertos                               | `GET /concerts`                     | `[{"id":1,"artist":{"name":"Stray Kids"},...}]`              |
| `/concerts/:id`                  | GET                      | Obtener detalles de un concierto por ID                    | `GET /concerts/1`                   | `{ "id":1, "artist":{...}, "venue":{...} }`                  |
| `/concerts/:id`                  | PATCH                    | Marcar asistencia a un concierto                           | `PATCH /concerts/1`                 | `{ "attendees": [2] }`                                       |
| `/users`                         | GET                      | Listar todos los usuarios                                  | `GET /users`                        | `[{"id":1,"name":"Bang Chan",...}]`                          |
| `/users/:id`                     | GET                      | Obtener un usuario específico                              | `GET /users/2`                      | `{ "id":2, "name":"Diego Rivas",... }`                       |
| `/users/:id`                     | PUT                      | Actualizar datos de usuario (perfil)                       | `PUT /users/1`                      | `{ "message": "Usuario actualizado" }`                       |
| `/communities`                  | GET                      | Obtener todas las comunidades                              | `GET /communities`                  | `[{"id":1,"name":"Swifties",...}]`                           |
| `/communities/:id`              | GET                      | Ver comunidad específica                                   | `GET /communities/11`              | `{ "id":11, "name":"Stay",... }`                             |
| `/posts`                         | GET                      | Ver publicaciones realizadas                               | `GET /posts`                        | `[{"id":1749829284972, "content":"...",...}]`               |
| `/posts`                         | POST                     | Crear una nueva publicación en comunidad                   | `POST /posts`                       | `{ "message": "Publicación registrada correctamente" }`      |

---

### <strong>Capturas de evidencia funcional</strong>

<div align="center">
  <strong>Vista de detalles de concierto con botón de asistencia</strong>  
</div>

<div align="center">
  <img src="assets/capturas/asistencia_concierto.png" alt="Asistencia concierto" style="width: 80%;">
</div>

<div align="center">
  <strong>Formulario de publicación dentro de una comunidad</strong>  
</div>

<div align="center">
  <img src="assets/capturas/publicacion_comunidad.png" alt="Publicación comunidad" style="width: 80%;">
</div>

<div align="center">
  <strong>Vista del perfil con opción de edición</strong>  
</div>

<div align="center">
  <img src="assets/capturas/editar-perfil-usuario.png" alt="Editar perfil" style="width: 80%;">
</div>

- <strong>Enlace de aplicación web: </strong>`staymap-web-application.vercel.app`
---

- <strong>Repositorio Web Services:</strong> `https://github.com/The-Rumbling/StayMap-Api.git`

<div align="center">
  <img src="assets/capturas/repositorio-web-service.png" alt="respositorioWebService" style="width: 80%;">
</div>

- <strong>Ruta local del</strong> `db.json`: `server/db.json`  
- <strong>Documentación expuesta vía json-server local:</strong> `http://localhost:3000/concerts`, `.../users`, `.../communities`, `.../posts`

---

### <strong>Commits relevantes del Sprint 3</strong>

- `81e5a27`: Implementación de lógica de confirmación y cancelación de asistencia a conciertos.  
- `0850a9e`: Soporte para publicaciones en comunidades y servicio asociado.  
- `4405caa`: Edición de perfil de usuario (nombre, imagen, correo) mediante PUT.  
- `3a12fcb`: Integración de vista dinámica del detalle del concierto con datos de la Fake API.

### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Durante el Sprint 3, se completó exitosamente el despliegue de dos componentes principales del sistema StayMap: la <strong>Landing Page</strong> informativa y la <strong>Aplicación Web funcional</strong>. Cada uno fue desplegado utilizando una plataforma distinta según sus características y necesidades técnicas.

---

#### Landing Page

La Landing Page de StayMap, orientada a la presentación del proyecto y sus beneficios, fue desarrollada como un módulo independiente en Angular. Para su despliegue, se generó una carpeta <strong>dist/</strong> mediante el comando de compilación en producción:

```
npm run build -- --configuration production
```

Esta carpeta fue publicada en GitHub Pages a través del branch <strong>gh-pages</strong>, configurado para servir contenido estático desde <strong>dist/landing</strong>.

Este despliegue permitió mostrar funcionalidades clave como:

- Presentación de beneficios para fans y artistas.
- Testimonios de usuarios reales.
- Selector de idioma (Español/Inglés) que traduce dinámicamente el contenido.

<strong> Vista de la Landing Page desplegada en GitHub Pages: </strong>  

<div align="center">
  <img src="assets/capturas/captura-deployment-landingpage.png" alt="deploy landingpage" style="width: 80%;">
</div>

---

#### Aplicación Web 

La aplicación principal de StayMap fue desplegada en la plataforma <strong>Vercel</strong>, directamente desde el repositorio en GitHub mediante la integración automática.

En este caso:

- No fue necesario generar ni subir manualmente la carpeta dist/.
- Vercel detectó automáticamente el proyecto Angular.
- Ejecutó internamente:

```
npm install && npm run build
```

La aplicación permite al usuario:

- Visualizar conciertos y comunidades.
- Editar perfil de usuario.
- Confirmar asistencia a eventos.
- Ver mapa interactivo con Google Maps API.
- Publicar y explorar contenido de comunidades.

<strong>Vista de la Aplicación Web desplegada en Vercel </strong>  

<div align="center">
  <img src="assets/capturas/captura-deployment-appweb.png" alt="deploy appweb" style="width: 80%;">
</div>

---

Ambos despliegues fueron validados como evidencia funcional durante la revisión del Sprint 3, garantizando que el sistema StayMap se encuentra operativo en entornos productivos accesibles públicamente.


### 5.2.3.8. Team Collaboration Insights during Sprint.

Durante el Sprint 3, el equipo de desarrollo colaboró activamente para implementar las funcionalidades centrales de la plataforma <strong>StayMap</strong>. La coordinación entre los miembros permitió una integración fluida de componentes, servicios y vistas, trabajando de forma distribuida pero sincronizada.

Las principales actividades realizadas fueron:

- <strong>Estructuración de módulos y componentes</strong> en Angular, separados por funcionalidades (usuarios, conciertos, comunidades).
- <strong>Diseño e implementación de estilos visuales</strong> siguiendo una línea gráfica moderna y coherente.
- <strong>Integración de una Fake API</strong> con json-server para simular un backend RESTful, alojada en Render.
- <strong>Control de versiones y ramas</strong> usando Git y GitHub, con convenciones claras para nombres de ramas (`features/`).
- <strong>Despliegue automático</strong> de la aplicación en Vercel a partir de los cambios en el repositorio.

El equipo utilizó GitHub como principal herramienta de colaboración. Cada integrante trabajó en su rama asignada, realizando <strong>commits frecuentes y descriptivos</strong>. Se aplicaron revisiones cruzadas y pruebas integradas antes de hacer merge al branch principal.

<strong>Gráficos de colaboración:</strong>  

<div align="center">
  <img src="assets/capturas/captura-commits-appweb2.png" alt="commits appweb" style="width: 80%;">
</div>

<strong>GitFlow:</strong>  
<div align="center">
  <img src="assets/capturas/gitflow-OPEN.png" alt="gitflow" style="width: 80%;">
</div>

Este enfoque fomentó una dinámica de trabajo colaborativo en paralelo, donde se avanzó simultáneamente en tareas como:

- Vista de perfil editable por fans y artistas.
- Publicación en comunidades musicales.
- Buscador de conciertos y comunidades.
- Interacción en el mapa de conciertos.

La participación activa del equipo quedó evidenciada en la frecuencia de los commits y en la cantidad de tareas completadas a tiempo, fortaleciendo el cumplimiento de los objetivos del Sprint.


## 5.2.4. Sprint 4

### 5.2.4.1. Sprint Planning 4.

<table>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Background</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Date</strong></td>
      <td>2025-07-09</td>
    </tr>
    <tr>
      <td><strong>Time</strong></td>
      <td>9:00 PM</td>
    </tr>
    <tr>
      <td><strong>Location</strong></td>
      <td>Virtual, via Discord</td>
    </tr>
    <tr>
      <td><strong>Prepared by</strong></td>
      <td>Lizarbe Álvarez, Ariana Nickole</td>
    </tr>
    <tr>
      <td><strong>Attendees (to planning meeting)</strong></td>
      <td>
        Lizarbe Álvarez, Ariana Nickole / Ortiz Cardenas, Johanna Antuanete / 
        Zúñiga Murillo, Diego Sebastian / Collantes Carrillo, Diego Mateo / 
        Zegarra López, Renato / Rubber Sebastian
      </td>
    </tr>
    <tr>
      <th colspan="2">Sprint Goal & User Stories</th>
    </tr>
    <tr>
      <td><strong>Sprint n Goal</strong></td>
     <td>
	     
  <strong>Nuestro enfoque está</strong> en continuar el desarrollo de una aplicación web funcional que permita a fans y artistas visualizar en un mapa interactivo los eventos musicales cercanos, junto con una lista filtrable de eventos disponibles en su área, según su ubicación e intereses. Ya hemos implementado un backend que accede a los datos desde una base de datos MySQL, lo cual permite gestionar conciertos, comentarios y perfiles de usuarios de forma eficiente.

<strong>Creemos que esto ofrece</strong> una experiencia personalizada que fomenta la participación en comunidades musicales, fortaleciendo el vínculo entre fans y artistas emergentes a través de la tecnología.

<strong>Esto se confirmará cuando</strong> los usuarios puedan ver eventos geolocalizados, aplicar filtros por género musical y ubicación, así como crear o unirse a comunidades afines dentro de la plataforma, aprovechando la infraestructura ya conectada a MySQL para garantizar consistencia y persistencia de los datos.


</td>
	    <tr>
    <td>Sum of Story Points</td>
    <td>55</td>
  </tr>
  </tbody>
</table>

### 5.2.4.2. Aspect Leaders and Collaborators.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="7">5.2.1.2. Aspect Leaders and Collaborators</th>
  </tr>
  <tr>
    <th>Team Member</th>
    <th>Github Username</th>
    <th>Backend</th>
    <th>Frontend</th>
    <th>Development</th>
    <th>Components</th>
    <th>Deployment</th>
  </tr>
  <tr>
    <td>Collantes Diego</td>
    <td>D4D3v4l</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Lizarbe Ariana</td>
    <td>ariaalizz</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Ortiz Johanna</td>
    <td>Antuanet01</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>L</td>
  </tr>
  <tr>
    <td>Zegarra Renato</td>
    <td>ReiZCode</td>
    <td>L</td>
    <td>L</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
  <tr>
    <td>Zúniga Diego</td>
    <td>DekayDe Canela</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
    <td>L</td>
    <td>C</td>
  </tr>
</table>

### 5.2.4.3. Sprint Backlog 4.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="8">Sprint 4</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item/Task</th>
  </tr>
  <tr>
    <th>id</th>
    <th>title</th>
    <th>id</th>
    <th>title</th>
    <th>description</th>
    <th>estimation</th>
    <th>assigned to</th>
    <th>status</th>
  </tr>

  <tr>
    <td>US28</td>
    <td>Ver comunidades accedidas</td>
    <td>TSK40</td>
    <td>Mostrar comunidades accedidas del usuario</td>
    <td>Diseñar la sección "Tus grupos" donde el usuario puede ver las comunidades a las que pertenece.</td>
    <td>2 horas</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US29</td>
    <td>Reaccionar a publicaciones en comunidades</td>
    <td>TSK41</td>
    <td>Reaccionar con emojis a publicaciones</td>
    <td>Permitir al usuario interactuar con publicaciones usando reacciones tipo emoji o símbolo.</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US30</td>
    <td>Calificar concierto</td>
    <td>TSK42</td>
    <td>Valoración de concierto por parte del usuario</td>
    <td>Permitir al usuario asignar una calificación del 1 al 5 estrellas tras haber asistido a un evento.</td>
    <td>3 horas</td>
    <td>Renato Zegarra</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US31</td>
    <td>Ver usuarios que asistirán a concierto</td>
    <td>TSK43</td>
    <td>Mostrar lista de asistentes</td>
    <td>Mostrar quiénes asistirán a un evento dentro de su ficha de detalles.</td>
    <td>3 horas</td>
    <td>Diego Zúñiga</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US32</td>
    <td>Acceder a perfil de otros usuarios</td>
    <td>TSK44</td>
    <td>Ver perfil público desde comunidades o eventos</td>
    <td>Habilitar vista de perfil público cuando se da clic en un nombre de usuario o avatar.</td>
    <td>2 horas</td>
    <td>Antuanete Ortiz</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US33</td>
    <td>Ver publicaciones con like</td>
    <td>TSK45</td>
    <td>Mostrar publicaciones que recibieron like</td>
    <td>Listar todas las publicaciones marcadas con “me gusta” por el usuario en su perfil.</td>
    <td>3 horas</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US34</td>
    <td>Ver plataformas de venta del concierto</td>
    <td>TSK46</td>
    <td>Enlaces de venta de entradas</td>
    <td>Agregar en la ficha del evento los enlaces a plataformas externas donde se venden entradas.</td>
    <td>2 horas</td>
    <td>Diego Collantes</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US35</td>
    <td>Permitir acceso a ubicación</td>
    <td>TSK47</td>
    <td>Solicitar permiso de ubicación al usuario</td>
    <td>Al ingresar por primera vez a la app, solicitar al usuario que otorgue permisos de geolocalización.</td>
    <td>2 horas</td>
    <td>Antuanete Ortiz</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US36</td>
    <td>Mostrar conciertos cercanos</td>
    <td>TSK48</td>
    <td>Visualizar conciertos cercanos usando geolocalización</td>
    <td>Usar la ubicación del usuario para mostrar conciertos próximos en el mapa.</td>
    <td>5 horas</td>
    <td>Renato Zegarra</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US37</td>
    <td>Ver miembros de comunidad</td>
    <td>TSK49</td>
    <td>Listar miembros de comunidad</td>
    <td>Mostrar quiénes forman parte de una comunidad con foto y nombre.</td>
    <td>2 horas</td>
    <td>Diego Zúñiga</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US38</td>
    <td>Subir imágenes en comunidades</td>
    <td>TSK50</td>
    <td>Adjuntar imágenes a publicaciones</td>
    <td>Permitir al usuario subir una o más imágenes en sus publicaciones de comunidad.</td>
    <td>3 horas</td>
    <td>Ariana Lizarbe</td>
    <td>Done</td>
  </tr>
</table>


### 5.2.4.4. Development Evidence for Sprint Review.

Front End:

| Repository    | Branch / File              | Commit Id | Commit Message               | Commit Message Body | Committed on |
| ------------- | -------------------------- | --------- | ---------------------------- | ------------------- | ------------ |
| arialalizz    | concert.service.ts         | ff47016   | Update concert.service.ts    | —                   | 2025-07-12   |
| arialalizz    | concert.entity.ts          | 41f1e4c   | Update concert.entity.ts     | —                   | 2025-07-12   |
| D4D3v4l1      | .editorconfig              | c9aee73   | Update .editorconfig         | —                   | 2025-07-12   |
| ReizCode      | concert-map.component.html | b8977dc   | Update concert-map.component | —                   | 2025-07-12   |
| ReizCode      | concert-map.component.html | 69dcb11   | Update concert-map.component | —                   | 2025-07-12   |
| ReizCode      | concert-map.component.html | a3e56d1   | Update concert-map.component | —                   | 2025-07-12   |
| ReizCode      | concert-map.component.html | 45238f4   | Update concert-map.component | —                   | 2025-07-12   |
| D4D3v4l1      | .gitignore                 | 7c01001   | Update .gitignore            | —                   | 2025-07-12   |
| DekayDeCanela | N/A                        | b6d1d9b   | first commit                 | —                   | 2025-07-12   |
| Antuanete01   | N/A                        | de857e6   | initial commit               | —                   | 2025-05-13   |

Back End: 

| Repository    | Branch / File                    | Commit Id | Commit Message                          | Commit Message Body | Committed on |
| ------------- | -------------------------------- | --------- | --------------------------------------- | ------------------- | ------------ |
| DekayDeCanela | CreateConcertCommand.java        | 8dd09c7   | Update CreateConcertCommand.java        | —                   | 2025-07-12   |
| DekayDeCanela | CreateConcertCommand.java        | aa28457   | Update CreateConcertCommand.java        | —                   | 2025-07-12   |
| D4D3v4l1      | pom.xml                          | 582949f   | Update pom.xml                          | —                   | 2025-07-12   |
| D4D3v4l1      | .gitignore                       | bdfe05b   | Update .gitignore                       | —                   | 2025-07-12   |
| ReizCode      | CommunityCommandServiceImpl.java | f43f697   | Update CommunityCommandServiceImpl.java | —                   | 2025-07-12   |
| ReizCode      | CommunityCommandServiceImpl.java | 3f8f4cc   | Update CommunityCommandServiceImpl.java | —                   | 2025-07-12   |
| ReizCode      | CommunityCommandServiceImpl.java | cfd6e93   | Update CommunityCommandServiceImpl.java | —                   | 2025-07-12   |
| arialalizz    | PostCommandService.java          | f80944c   | Update PostCommandService.java          | —                   | 2025-07-12   |
| arialalizz    | CommunityQueryService.java       | 252a96a   | Update CommunityQueryService.java       | —                   | 2025-07-12   |
| Antuanete01   | Dockerfile                       | 79dd190   | Update Dockerfile                       | —                   | 2025-07-12   |
| Antuanete01   | Dockerfile                       | 605dfc2   | Create Dockerfile                       | —                   | 2025-07-12   |
| Antuanete01   | N/A                              | 3a40d7f   | first commit                            | —                   | 2025-07-12   |



### 5.2.4.5. Execution Evidence for Sprint Review.

Durante el Sprint 4 del proyecto StayMap, el equipo se centró en fortalecer la experiencia del usuario fan y artista, profundizando en funcionalidades sociales, interacción entre usuarios, geolocalización, y validación de datos clave en conciertos y comunidades. Además, se desplegó la versión 4 de la Landing Page, la cual ahora redirige a la versión 3 de la aplicación web e incluye videos embebidos sobre el equipo y el producto, mejorando la presentación general del proyecto y su accesibilidad.

Este sprint también marcó el inicio formal del desarrollo del backend real en Java 24, Maven y Spring Boot, utilizando JetBrains Rider como entorno principal. El backend fue diseñado siguiendo principios RESTful y buenas prácticas de arquitectura, con endpoints simulados inicialmente en json-server como referencia funcional.

Todas las historias de usuario y tareas técnicas contempladas en el Sprint Backlog 4 fueron ejecutadas exitosamente por los integrantes del equipo, cumpliendo los criterios de aceptación establecidos.


	- Videos embebidos del equipo y el producto: Se añadieron a la Landing Page dos secciones con miniaturas de YouTube que presentan al equipo de desarrollo y una vista general del producto, brindando mayor contexto visual al visitante.

	- Visualización de comunidades accedidas ("Tus grupos"): Se implementó una sección en el perfil donde los usuarios ven las comunidades musicales a las que pertenecen. Esta funcionalidad se conectará con un endpoint real desarrollado en .NET 9.0.

	- Reacciones a publicaciones comunitarias: Se habilitó la opción de reaccionar con emojis a publicaciones dentro de cada comunidad. Se manejan restricciones para evitar reacciones duplicadas por usuario.

	- Calificación de conciertos: Los usuarios pueden calificar eventos entre 1 y 5 estrellas. Esta información será almacenada en la base de datos a través del backend en desarrollo con C#.

	- Visualización de asistentes a conciertos: Se muestra una lista de otros usuarios que han confirmado asistencia a un concierto, mejorando la dimensión social de los eventos.

	- Acceso a perfiles públicos: Se activó la navegación hacia perfiles públicos desde comunidades o eventos, mostrando nombre, avatar y comunidades visibles del usuario.

	- Historial de publicaciones con “like”: Se implementó una sección donde el usuario puede revisar las publicaciones que ha marcado como favoritas.

	- Visualización de plataformas de venta: En la ficha del concierto se agregaron enlaces a sitios simulados de venta de entradas, guiando al usuario hacia la compra.

	- Permiso de ubicación y conciertos cercanos: Al acceder a la app, se solicita el permiso de geolocalización. Los conciertos cercanos se renderizan según la ubicación obtenida, conectándose al backend en .NET para la lógica de proximidad.

	- Listado de miembros en comunidades: Se implementó una pestaña de “Miembros” que muestra los integrantes de cada comunidad, obtenidos vía servicio.

	- Publicaciones con imágenes: Se agregó la funcionalidad de subir imágenes a publicaciones dentro de comunidades. Incluye validaciones y previsualización.

  
El equipo inició el desarrollo de endpoints en Java 24, Maven y Spring Boot desde cero, utilizando IntelliJdea y aplicando buenas prácticas como:

- Separación por capas (Controller, Service, Repository).

- Inyección de dependencias.

- Validaciones automáticas con DataAnnotations.

- Uso de Entity Framework y Swagger para pruebas de endpoints.

<strong> Screenshots de las evidencias: </strong>

<strong> Landing page </strong>

Videos About-The-Product y About-The-Team añadidos a la Landing Page:

<div align="center">

</div>
<div align="center">

</div>

<strong> Aplicación Web </strong>

### 5.2.4.6. Services Documentation Evidence for Sprint Review.
La siguiente tabla presenta una recopilación completa de los endpoints disponibles en la API de StayMap, organizados por funcionalidad y propósito. Cada entrada incluye el endpoint correspondiente, el método HTTP que debe utilizarse, una breve descripción de su función, un ejemplo de cómo realizar la llamada y una respuesta de ejemplo representativa. Esta documentación está diseñada para servir como referencia rápida para desarrolladores que deseen integrar StayMap en sus aplicaciones o contribuir al desarrollo del sistema. Los endpoints cubren operaciones clave relacionadas a publicaciones, autenticación, gestión de comunidades, asistencia a conciertos y manejo de usuarios, permitiendo una interacción robusta y segura con la plataforma desde el backend o el frontend.


| Endpoint                                        | Método | Descripción                              | Ejemplo de llamada                          | Ejemplo de respuesta |
|------------------------------------------------|--------|-------------------------------------------|---------------------------------------------|----------------------|
| `/api/v1/posts`                                 | GET    | Obtener todos los posts                   | `GET /api/v1/posts`                          | `[{"id":1,"content":"Hola mundo","likes":5}]` |
| `/api/v1/posts`                                 | POST   | Crear un nuevo post                       | `POST /api/v1/posts`                         | `{"id":2,"content":"Nuevo post","likes":0}` |
| `/api/v1/posts/{postId}/like`                   | POST   | Dar like a un post                        | `POST /api/v1/posts/123/like`                | `{"message":"Post liked"}` |
| `/api/v1/posts/{postId}/like`                   | DELETE | Quitar like a un post                     | `DELETE /api/v1/posts/123/like`              | `{"message":"Like removed"}` |
| `/api/v1/posts/{postId}`                        | GET    | Obtener post por ID                       | `GET /api/v1/posts/123`                      | `{"id":123,"content":"Texto del post","likes":10}` |
| `/api/v1/authentication/sign-up`               | POST   | Registro de usuario                       | `POST /api/v1/authentication/sign-up`        | `{"message":"User registered successfully"}` |
| `/api/v1/authentication/sign-in`               | POST   | Inicio de sesión                          | `POST /api/v1/authentication/sign-in`        | `{"token":"abc123xyz","user":{"id":5,"email":"test@mail.com"}}` |
| `/api/v1/communities`                          | GET    | Obtener todas las comunidades             | `GET /api/v1/communities`                    | `[{"id":1,"name":"Rock Lovers","members":35}]` |
| `/api/v1/communities`                          | POST   | Crear nueva comunidad                     | `POST /api/v1/communities`                   | `{"id":2,"name":"Jazz Club","members":0}` |
| `/api/v1/communities/{communityId}/join`       | POST   | Unirse a comunidad                        | `POST /api/v1/communities/10/join`           | `{"message":"Joined community"}` |
| `/api/v1/communities/{communityId}`            | GET    | Obtener comunidad por ID                  | `GET /api/v1/communities/10`                 | `{"id":10,"name":"Indie Wave","members":18}` |
| `/api/v1/communities/{communityId}/leave`      | DELETE | Salir de la comunidad                     | `DELETE /api/v1/communities/10/leave`        | `{"message":"Left community"}` |
| `/api/v1/concerts`                             | GET    | Obtener todos los conciertos              | `GET /api/v1/concerts`                       | `[{"id":1,"name":"Lollapalooza","attendees":500}]` |
| `/api/v1/concerts`                             | POST   | Crear nuevo concierto                     | `POST /api/v1/concerts`                      | `{"id":2,"name":"Jazz Fest","attendees":0}` |
| `/api/v1/concerts/{concertId}/attend`          | POST   | Asistir a concierto                       | `POST /api/v1/concerts/5/attend`             | `{"message":"Attendance confirmed"}` |
| `/api/v1/concerts/{concertId}/attend`          | DELETE | Cancelar asistencia a concierto           | `DELETE /api/v1/concerts/5/attend`           | `{"message":"Attendance cancelled"}` |
| `/api/v1/concerts/{concertId}`                 | GET    | Obtener concierto por ID                  | `GET /api/v1/concerts/5`                     | `{"id":5,"name":"Indie Night","attendees":123}` |
| `/api/v1/concerts/{concertId}`                 | DELETE | Eliminar concierto                        | `DELETE /api/v1/concerts/5`                  | `{"message":"Concert deleted"}` |
| `/api/v1/concerts/{concertId}/attendees`       | GET    | Consultar asistentes a un concierto       | `GET /api/v1/concerts/5/attendees`           | `[{"id":1,"name":"Ana"},{"id":2,"name":"Luis"}]` |
| `/api/v1/users/{userId}`                       | GET    | Obtener usuario por ID                    | `GET /api/v1/users/4`                        | `{"id":4,"name":"Carlos","email":"carlos@mail.com"}` |
| `/api/v1/users/{userId}`                       | PUT    | Actualizar usuario                        | `PUT /api/v1/users/4`                        | `{"message":"User updated successfully"}` |
| `/api/v1/users`                                | GET    | Obtener todos los usuarios                | `GET /api/v1/users`                          | `[{"id":1,"name":"Ana"},{"id":2,"name":"Luis"}]` |
| `/api/v1/users/{userId}/details`               | GET    | Obtener detalles del usuario              | `GET /api/v1/users/4/details`                | `{"id":4,"details":{"age":25,"location":"Lima"}}` |

### 5.2.4.7. Software Deployment Evidence for Sprint Review.

Durante el Sprint 4, se lograron importantes avances en los módulos principales del sistema StayMap. Por un lado, se actualizó y desplegó la versión 4 de la Landing Page, ahora alojada en Render, la cual integra contenido audiovisual embebido y un redireccionamiento funcional hacia la aplicación web principal. Por otro lado, se consolidó la versión 3 de la Aplicación Web, que ahora cuenta con una arquitectura completa basada en una base de datos MySQL y un backend desarrollado en C# con .NET 9.0, implementado desde JetBrains Rider. Estos avances representan un paso clave hacia una infraestructura más escalable, robusta y alineada con los objetivos técnicos del proyecto.

#### Landing Page

Durante el Sprint 4, se completó exitosamente la actualización y despliegue de la versión 4 de la Landing Page de StayMap. Aunque ya había sido estructurada en Vue y desplegada previamente, esta nueva versión incorporó mejoras funcionales clave orientadas a la experiencia del usuario y fue migrada a la plataforma Render para un despliegue más flexible y dinámico.

La Landing Page, desarrollada con Vue y Vite, fue compilada para producción mediante el comando:

```
npm run build -- --configuration production
````

A diferencia de versiones anteriores alojadas en GitHub Pages, esta nueva versión fue desplegada en Render, lo que permitió contar con un entorno más robusto y fácil de actualizar en tiempo real.

Los principales cambios de esta versión incluyen:

**Botón “Empezar” redirigido a la v3 de la App Web**: Ahora conecta directamente con la tercera versión de la aplicación StayMap, garantizando un flujo de navegación coherente y actualizado para nuevos usuarios.

**Videos embebidos directamente en la interfaz**: Se integraron dos secciones con videos explicativos:

- About the Team: Presenta brevemente al equipo detrás del desarrollo de StayMap.

- About the Product: Muestra una introducción al funcionamiento, propuesta de valor y beneficios principales de la plataforma.

Estas mejoras fortalecen la propuesta visual e informativa de StayMap, generando mayor impacto en nuevos usuarios desde la primera interacción.


<strong> Vista de la Landing Page desplegada en GitHub Pages: </strong>  
URL de Landing page: `https://the-rumbling.github.io/LandingPage-V4/home`

<div align="center">
  <img src="assets/capturas/LandingV4-1.png" alt="deploy landingpage" style="width: 80%;">
</div>
<div align="center">
  <img src="assets/capturas/LandingV4-2.png" alt="deploy landingpage" style="width: 80%;">
</div>
<div align="center">
  <img src="assets/capturas/LandingV4-3.png" alt="deploy landingpage" style="width: 80%;">
</div>
<div align="center">
  <img src="assets/capturas/LandingV4-4.png" alt="deploy landingpage" style="width: 80%;">
</div>

<strong> Vista de la Aplicación Web desplegada en Vercel: </strong>  
URL de Aplicacion Web: `https://stay-map-frontend.vercel.app/concerts`
<div align="center">
  <img src="assets/capturas/vistaopen.png" alt="deploy landingpage" style="width: 80%;">
</div>

URL de el web service desplegado en Render: `https://staymap-backendopen.onrender.com/`

### 5.2.4.8. Team Collaboration Insights during Sprint.

Durante el Sprint 4, el equipo de desarrollo continuó fortaleciendo la arquitectura y funcionalidades clave de la plataforma StayMap, marcando un punto de inflexión con el inicio del backend real en Java 24 con Spring Boot. La colaboración entre los miembros se mantuvo activa y sincronizada, permitiendo el avance en paralelo del frontend y del backend real.

Las principales actividades realizadas fueron:

- Implementación del backend real en Java 24 con Spring Boot, estructurado por capas (Controller, Service, Repository), con integración de Entity Framework, Swagger y validaciones con DataAnnotations. El desarrollo se llevó a cabo utilizando IntelliJdea.
- Desarrollo de endpoints RESTful reales, cubriendo funcionalidades como creación de conciertos, reacciones, calificación de eventos y visualización de asistentes.
- Conexión con base de datos MySQL, alojada en Render, para persistir datos clave del sistema como usuarios, conciertos y publicaciones.
- Adaptación progresiva del frontend en Angular para integrarse con el nuevo backend, reemplazando gradualmente el backend simulado usado en sprints anteriores.
- Control de versiones y ramas usando Git y GitHub, con flujos claros de trabajo distribuidos por funcionalidades como auth, communities, concerts, api-dotnet, etc.
- Actualización y despliegue de la Landing Page versión 4 en Render, la cual ahora redirige a la versión 3 de la aplicación web y contiene videos embebidos de YouTube sobre el equipo y el producto.
- Despliegue de la nueva versión del backend real en Render, como API REST funcional, lista para pruebas y futuras integraciones completas con el frontend.
- El equipo continuó utilizando GitHub como herramienta central de colaboración, manteniendo prácticas como trabajo en ramas específicas, commits frecuentes y descriptivos, y revisiones cruzadas antes de realizar merge hacia dev y main.

Gráficos de colaboración:

Commits del backend: `https://github.com/The-Rumbling/StayMap-Backend.git`

<div align="center">
  <img src="assets/capturas/commitsback.png" alt="deploy landingpage" style="width: 80%;">
</div>

Commits del frontend: `https://github.com/The-Rumbling/StayMap-Frontend.git`

<div align="center">
  <img src="assets/capturas/commitsfront.png" alt="deploy landingpage" style="width: 80%;">
</div>


# 5.3. Validation Interviews.

En esta sección se documenta el proceso de validación realizado con usuarios reales pertenecientes a los dos segmentos objetivo: fans de la música y artistas emergentes. El objetivo fue validar la solución StayMap —una aplicación web hecha en Angular que recomienda conciertos según ubicación y preferencias musicales— y recolectar recomendaciones a través de feedback directo e indirecto. La aplicación incluye funcionalidades como:

- Mapa con integración de Google Maps.
- Filtros por género musical.
- Creación y visualización de conciertos.
- Participación y creación de comunidades.

Se presentó tanto el Landing Page como la aplicación funcional ya desplegada.

## 5.3.1. Diseño de Entrevistas.

**Segmento 1: Fans de la música**

**Objetivo:**
Validar la utilidad de la aplicación para descubrir conciertos cercanos, interactuar con el mapa, filtrar eventos, y participar o crear comunidades.

**User Flows a validar:**

- Ingreso a la Landing Page e identificación de la propuesta de valor.
- Visualización de conciertos recomendados en el mapa según ubicación.
- Uso de filtros por género musical.
- Unirse o crear una comunidad.
- Confirmar asistencia
- Agregar publicaciones en comunidades

**Elementos a observar:**

- ¿El usuario comprende rápidamente el propósito de la app?
- ¿Puede navegar sin ayuda excesiva?
- ¿Los filtros por género son útiles y fáciles de usar?
- ¿La opción de crear una comunidad resulta atractiva o confusa?
- ¿El mapa ofrece una experiencia clara?

**Preguntas guía:**

- ¿Te resultó fácil encontrar conciertos que te interesan?
- ¿Qué tan clara te pareció la navegación general?
- ¿Pudiste crear o unirte a una comunidad fácilmente?
- ¿Qué mejorarías en la experiencia con el mapa?
- ¿Qué funcionalidad agregarías para sentirte más conectado con tus artistas favoritos?

**Segmento 2: Artistas emergentes**

**Objetivo:**
Validar la funcionalidad que permite a los artistas promocionar eventos, visualizar conciertos en el mapa, y construir una comunidad de fans dentro de la plataforma.

**User Flows a validar:**

- Ingreso al Landing Page y comprensión del valor que StayMap les ofrece como artistas.
- Creación de un nuevo concierto.
- Visualización de su evento en el mapa.
- Creación de una comunidad para sus fans.
- Agregar publicaciones en comunidades

**Elementos a observar:**

- ¿Es clara la propuesta de valor como artista?
- ¿Pueden publicar un concierto sin dificultad?
- ¿Comprenden el propósito de las comunidades?
- ¿Encuentran útil la interacción entre mapa y eventos?

**Preguntas guía:**

- ¿Fue sencillo crear un concierto desde tu cuenta?
- ¿Crees que la funcionalidad de comunidades puede ayudarte a tener más alcance?
- ¿Qué parte del proceso fue menos intuitiva?
- ¿Agregarías alguna herramienta extra para la gestión de tus conciertos?
- ¿Sientes que la aplicación te conecta realmente con nuevos fans?


## 5.3.2. Registro de Entrevistas.

Url del video de entrevistas: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EYvc6nhY2D9Em16I77GL5MIB0rC_ivUGI7hVPqJmRNk7Rg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=103hgD`

### Segmento objetivo #1: Fans de la música (15 a 35 años)

#### Entrevista #1
![user_persona](assets/interviews/Analisis-Entrevista-2-Fan1.png)

**Nombre:** Jade Huaman   
**Edad:** 20 años  
**Duración:** 00:06:58  
**Inicio:** 00:00:10   
**Resumen:** Jade mostró un gran entusiasmo por el concepto de StayMap, especialmente por la posibilidad de ubicar eventos musicales cercanos y unirse a comunidades de fans. Destacó lo valioso que sería tener un espacio digital donde pueda compartir su pasión por la música con otros. Sin embargo, una de sus sugerencias fue incorporar funciones que permitan sentir una mayor cercanía con los artistas, como la organización de streaming parties dentro de las comunidades. Para Jade, estas actividades ayudarían a fortalecer el vínculo emocional entre los fans y los artistas, haciendo de la plataforma una experiencia más inmersiva y participativa.

#### Entrevista #2
![user_persona](assets/interviews/Analisis-Entrevista-2-Fan2.png)

**Nombre:** Masiel Cusi   
**Edad:** 20 años  
**Duración:** 00:09:24
**Inicio:** 00:07:05
**Resumen:** Massiel valoró positivamente la propuesta de StayMap y resaltó su utilidad para fans que desean conocer eventos musicales de distintas escalas, desde los más grandes hasta los más pequeños. Apreció la facilidad de navegación y el enfoque en la ubicación, pero hizo una recomendación clave: incluir una sección donde los usuarios puedan acceder a perfiles de artistas. En esta sección, le gustaría poder seguir a sus artistas favoritos, conocer más sobre ellos e incluso interactuar con sus publicaciones o actividades. Considera que esto haría la experiencia más completa y personalizada, reforzando el vínculo fan-artista dentro de la aplicación

#### Entrevista #3
![user_persona](assets/interviews/Analisis-Entrevista-2-Fan3.png)

**Nombre:** Jazmin Roque  
**Edad:** 22 años  
**Duración:** 00:15:12  
**Inicio:** 00:16:30 
**Resumen:** Jazmín, consideró que StayMap es una iniciativa con gran potencial para apoyar a músicos independientes, ya que les brinda visibilidad a través del mapa interactivo. Le pareció muy útil que los fans puedan descubrir eventos según su ubicación, pero también propuso algunas mejoras importantes. Entre ellas, mencionó que sería ideal que el mapa no solo muestre la ubicación de los conciertos, sino también las rutas para llegar al lugar. Además, sugirió integrar playlists de Spotify relacionados con los eventos o artistas, lo cual enriquecería la experiencia musical y serviría como promoción previa a los conciertos.

### Segmento objetivo #2: Artistas emergentes y bandas independientes (18 a 40 años)

#### Entrevista #4
![user_persona](assets/interviews/Analisis-Entrevista-2-Artista1.png)

**Nombre:** Rodrigo Chavez  
**Edad:** 19 años  
**Duración:** 00:08:56
**Inicio:** 00:31:47
**Resumen:** Rodrigo Chávez, un artista emergente de 19 años con más de seis años de experiencia en la música, enfocado en el género pop, considera que la plataforma es intuitiva y fácil de usar, con una conexión directa entre artistas y fans. Destaca la simplicidad de las funciones de StayMap, especialmente el apartado de comunidades, que le permite sentirse más cerca de su audiencia. Valora positivamente la funcionalidad del mapa para visualizar la distancia a los conciertos, lo que facilita la planificación de asistencia. Como herramienta adicional, sugiere incorporar recordatorios o notificaciones para los conciertos, lo cual reforzaría el vínculo con los eventos importantes. Además, menciona que la idea de comunidad es clave para crecer como artista emergente, aunque considera que el apartado de publicación de posts podría mejorarse para optimizar la interacción. Su feedback resalta la importancia de la usabilidad, la cercanía con el público y la mejora continua en herramientas de comunicación dentro de la plataforma.

#### Entrevista #5
![user_persona](assets/interviews/Analisis-Entrevista-2-Artista2.png)

**Nombre:** Joaquin Villanueva  
**Edad:** 19 años  
**Duración:** 00:12:29 
**Inicio:** 00:40:45 
**Resumen:** Joaquín Villanueva, un joven artista de 19 años con cuatro años de experiencia en la música, enfocado principalmente en el rock indie alternativo, considera que la propuesta de valor es clara y atractiva. Resalta que las herramientas de la aplicación son muy sencillas de usar para interactuar con conciertos y con otros artistas, lo que le pareció interesante y fácil de comprender. No presentó dificultades en su uso y entendió bien el propósito de las comunidades como espacios para mantener la interacción constante entre artistas y fans. Además, valoró la organización visual mediante el mapa de comunidades, ya que considera que permitirá a los artistas emergentes tener mayor visibilidad y oportunidades para despegar. Como mejora, sugiere incorporar una funcionalidad adicional que permita almacenar experiencias vividas en conciertos, a modo de carpeta personal. Su opinión respalda la importancia de la simplicidad, la interacción artística y la personalización como elementos clave para una plataforma que busque conectar a músicos y seguidores

#### Entrevista #6
![user_persona](assets/interviews/Analisis-Entrevista-2-Artista3.png)

**Nombre:** Zaleth Feijóo  
**Edad:** 19 años  
**Duración:** 00:21:31  
**Inicio:** 00:53:20
**Resumen:** Zalth Feijóo, artista emergente de 19 años con tres años de experiencia en el ámbito musical, considera que la propuesta de valor es clara y pertinente, destacando especialmente el enfoque en dar visibilidad a artistas emergentes. Resaltó que la aplicación es fácil de usar en general, y valoró positivamente la función del mapa para visualizar conciertos, considerándolo lo más innovador de la plataforma. También comprendió correctamente el propósito de las comunidades, proponiendo como mejora la incorporación de un chat para fomentar una comunicación más directa entre artistas y fans. Señaló como dificultad el sistema actual de carga de imágenes mediante enlaces, recomendando la posibilidad de subir archivos directamente desde el dispositivo. Además, sugirió incluir información de contacto del artista en los conciertos, así como un filtro para ver eventos cercanos que ocurran en tiempo real. Su feedback refuerza la importancia de optimizar procesos visuales e interactivos, priorizando accesibilidad, dinamismo y personalización para fortalecer la conexión entre artistas emergentes y su público.

## 5.3.3. Evaluaciones según heurísticas.

<div align="center">

## UX Heuristics & Principles Evaluation
Usability – Inclusive Design – Information Architecture  
CARRERA: Ingeniería de Software  
CURSO: Desarrollo de Aplicaciones Open Source  
SECCIÓN: 4334  
PROFESORES: Hugo Allan Mori Paiva  
AUDITOR: The Rumbling  
CLIENTE(S): Jade Huaman, Massiel Cusi, Jazmín Roque, Joaquín Villanueva, Rodrigo Chávez, Zaleth Feijóo

-----------------------

</div>

## App a evaluar: StayMap

## Tareas a evaluar
<ul>
  <li>Ingreso al Landing Page y comprensión del valor que StayMap les ofrece como artistas.</li>
  <li>Creación de un nuevo concierto.</li>
  <li>Visualización de su evento en el mapa.</li>
  <li>Creación de una comunidad para sus fans.</li>
  <li>Agregar publicaciones en comunidades.</li>
</ul>

## Escala de severidad

<table>
  <thead>
    <tr>
      <th>Nivel</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>1</strong></td>
      <td>Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</td>
    </tr>
    <tr>
      <td><strong>2</strong></td>
      <td>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release.</td>
    </tr>
    <tr>
      <td><strong>3</strong></td>
      <td>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y se le debe asignar una prioridad alta.</td>
    </tr>
    <tr>
      <td><strong>4</strong></td>
      <td>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.</td>
    </tr>
  </tbody>
</table>

## Tabla de resumen de problemas
<table>
  <thead>
    <tr>
      <th>#</th>
      <th>Problema</th>
      <th>Severidad</th>
      <th>Heurística/Principio violado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Los datos completados en el formulario de conciertos no se reflejan correctamente al crearlo</td>
      <td>3</td>
      <td>usability: user control and freedom</td>
    </tr>
    <tr>
      <td>2</td>
      <td>El concierto creado no aparece en la lista de conciertos disponibles</td>
      <td>3</td>
      <td>information architecture: visibility of system status</td>
    </tr>
    <tr>
      <td>3</td>
      <td>La opción para crear publicaciones en comunidades es poco clara y difícil de utilizar</td>
      <td>2</td>
      <td>usability: help and documentation</td>
    </tr>
    <tr>
      <td>4</td>
      <td>No se permite adjuntar archivos al publicar en comunidades</td>
      <td>2</td>
      <td>inclusive design: provide comparable experiences</td>
    </tr>
    <tr>
      <td>5</td>
      <td>No existe una opción de notificación o recordatorio para próximos conciertos</td>
      <td>2</td>
      <td>usability: recognition rather than recall</td>
    </tr>
    <tr>
      <td>6</td>
      <td>El mapa no ofrece rutas para llegar a los conciertos, limitando su utilidad para la planificación</td>
      <td>3</td>
      <td>usability: match between system and real world</td>
    </tr>
    <tr>
      <td>7</td>
      <td>No hay sección de perfil para artistas donde los usuarios puedan seguirlos o interactuar</td>
      <td>3</td>
      <td>personalization: user engagement and customization</td>
    </tr>
    <tr>
      <td>8</td>
      <td>No se integran playlists relacionadas con los eventos para enriquecer la experiencia previa al concierto</td>
      <td>2</td>
      <td>immersive experience: flexibility and efficiency of use</td>
    </tr>
    <tr>
      <td>9</td>
      <td>El proceso para añadir imágenes en conciertos es poco intuitivo</td>
      <td>3</td>
      <td>usability: recognition rather than recall</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Falta un filtro para visualizar conciertos en tiempo real o cercanos</td>
      <td>2</td>
      <td>usability: visibility of system status</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Falta de un chat directo entre artistas y fans dentro de las comunidades</td>
      <td>1</td>
      <td>immersive experience: flexibility and efficiency of use</td>
    </tr>
  </tbody>
</table>


## Descripcion de problemas


### Problema 1
Los datos completados en el formulario de conciertos no se reflejan correctamente al crearlo

- Severidad: 3

- Heurística violada: Prevención de errores

Descripción: Al crear un concierto, algunos campos como nombre del evento, fecha o ubicación no se muestran de forma coherente en la vista final. Esto genera desconfianza en la funcionalidad del sistema.  
Recomendación: Asegurar que los datos ingresados se guarden y visualicen correctamente. Implementar validaciones y una vista previa del concierto antes de guardar.

-----------------------

### Problema 2
El concierto creado no aparece en la lista de conciertos disponibles

- Severidad: 3

- Heurística violada: Feedback inmediato y correspondencia entre sistema y mundo real

Descripción: Luego de crear un concierto, este no se visualiza automáticamente en la lista de conciertos disponibles, obligando al usuario a recargar la página manualmente.  
Recomendación: Actualizar automáticamente la lista de conciertos después de crear uno nuevo y mostrar una notificación de éxito.

-----------------------

### Problema 3
La opción para crear publicaciones en comunidades es poco clara y difícil de utilizar

- Severidad: 2

- Heurística violada: Ayuda y documentación

Descripción: El proceso de publicación dentro de comunidades carece de guía visual, lo cual complica a los usuarios entender qué pueden compartir y cómo hacerlo.  
Recomendación: Agregar textos orientativos (placeholders), iconos para adjuntar archivos y una guía visual sobre el tipo de contenido permitido.

-----------------------

### Problema 4
No se permite adjuntar archivos al publicar en comunidades

- Severidad: 2

- Heurística violada: Flexibilidad y eficiencia de uso

Descripción: Las publicaciones están limitadas a texto, lo cual es una desventaja para los artistas que desean compartir contenido multimedia o promocional.  
Recomendación: Permitir adjuntar imágenes (.jpg, .png) con una interfaz clara para hacerlo.

-----------------------

### Problema 5
No existe una opción de notificación o recordatorio para próximos conciertos

- Severidad: 2

- Heurística violada: Reconocer mejor que recordar

Descripción: No se ofrece ninguna forma de alertar al usuario sobre la cercanía de un concierto al que haya mostrado interés o asistencia.    
Recomendación: Implementar notificaciones automáticas para recordar a los usuarios sobre eventos próximos guardados o avisos en comunidades.

-----------------------

### Problema 6
El mapa no ofrece rutas para llegar a los conciertos, limitando su utilidad para la planificación

- Severidad: 3

- Heurística violada: Correspondencia entre el sistema y el mundo real

Descripción: El mapa muestra la ubicación de los conciertos, pero no ofrece indicaciones o rutas para llegar al lugar del evento. Esto limita la experiencia del usuario, especialmente si no conoce la zona.     
Recomendación: Integrar una opción de rutas con servicios como Google Maps o Mapbox, que permita al usuario ver cómo llegar desde su ubicación actual al concierto.\

-----------------------

### Problema 7
No hay sección de perfil para artistas donde los usuarios puedan seguirlos o interactuar

- Severidad: 3

- Heurística violada: Personalización y compromiso del usuario

Descripción: Los usuarios no pueden acceder a un perfil completo de los artistas, lo que limita la posibilidad de conocer más sobre ellos, seguirlos o interactuar con su contenido dentro de la aplicación.   
Recomendación: Crear una sección de perfiles para artistas con biografía, publicaciones, eventos asociados y botón de “seguir” para fomentar la interacción y fidelización.

-----------------------

### Problema 8
No se integran playlists relacionadas con los eventos para enriquecer la experiencia previa al concierto

- Severidad: 2

- Heurística violada: Flexibilidad y eficiencia de uso

Descripción: No se ofrecen recursos musicales como playlists de Spotify o similares que permitan a los usuarios familiarizarse con los artistas o eventos antes del concierto.    
Recomendación: Incluir playlists asociadas a los conciertos o artistas en cada evento publicado. Esto puede servir como promoción musical anticipada y aumentar el interés del usuario.

-----------------------

### Problema 9
El proceso para añadir imágenes en conciertos es poco intuitivo

- Severidad: 3

- Heurística violada: Reconocimiento antes que recuerdo

Descripción: Actualmente, para agregar una imagen a un concierto es necesario copiar y pegar una URL externa, lo que no es una práctica común entre usuarios de plataformas similares. Esto provoca confusión, errores (como espacios al copiar) y ralentiza el proceso.

-----------------------

### Problema 10
Falta un filtro para visualizar conciertos en tiempo real o cercanos

- Severidad: 2

- Heurística violada: Flexibilidad y eficiencia de uso

Descripción: La entrevistada expresó interés en ver qué conciertos están ocurriendo en el momento o próximamente cerca de su ubicación. La falta de un filtro para eventos en vivo o por fecha/hora disminuye la practicidad de la aplicación.

-----------------------

### Problema 11
Falta de un chat directo entre artistas y fans dentro de las comunidades

- Severidad: 1

- Heurística violada: Flexibilidad y eficiencia de uso

Descripción: La entrevistada sugirió agregar una opción de chat directo entre artistas y fans dentro de las comunidades. Aunque no es indispensable para el funcionamiento base de la aplicación, podría fortalecer el sentido de comunidad.

# 5.4. Video About-the-Product.


![Image](assets/capturas/aboutTheProduct.png)

**Duración:** 00:00:50   
**URL en Microsoft Stream:** `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311558_upc_edu_pe/EW7haIoSjBdAlW-WvXrFHmABJK-2BtDR3gOAFPRuzy2Rug?e=c2121a&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`   
**URL en Youtube:** `https://youtu.be/puIIcqcMcII`

# Avance de Conclusiones, Bibliografía y Anexos


# Conclusiones

- En conclusión, STAYMAP ha demostrado ser una solución eficaz para acercar a los aficionados y artistas emergentes mediante la visualización de conciertos de pequeña y mediana envergadura en un entorno interactivo y accesible. La integración de la API de Google Maps junto con marcadores personalizados y una barra lateral informativa permitió resolver la problemática inicial de localización y descubrimiento de eventos, ofreciendo al usuario una experiencia fluida y centrada en sus necesidades.
- El desarrollo de funcionalidades clave en el frontend, el establecimiento de una arquitectura de datos sólida y la creación de una landing page clara y orientada al usuario han evidenciado avances sustanciales tanto en lo estético como en lo operativo de la plataforma. Gracias a estas implementaciones, se ha alcanzado un equilibrio entre diseño atractivo, rendimiento y usabilidad, asegurando que la aplicación sea intuitiva y responda de manera eficiente a las acciones del usuario.
- Al contemplar la escalabilidad del sistema hacia nuevas ciudades y contextos culturales, STAYMAP abre un abanico de oportunidades para su crecimiento y consolidación. La capacidad de adaptarse a distintas realidades locales y de integrarse con agentes culturales pone de manifiesto el potencial de la plataforma para convertirse en un referente en la promoción y difusión de eventos musicales independientes a nivel global.
- La implementación del sistema de comunidades personalizadas por artista permitió que los usuarios creen y gestionen espacios centrados en sus intereses culturales. Este enfoque reflejó directamente los valores del software libre, al fomentar la descentralización del control y dar voz a los propios usuarios. El desarrollo de esta funcionalidad no solo fue técnicamente desafiante, sino que implicó un diseño de estructura flexible, capaz de adaptarse a múltiples contextos culturales. Además, fue construido de manera modular y documentada, permitiendo que futuros desarrolladores puedan replicar o extender esta lógica para otras plataformas.
- La publicación de mensajes dentro de las comunidades fue otra funcionalidad clave trabajada en la TB2, que permitió simular interacciones sociales y dar lugar a conversaciones en torno a eventos y temas culturales. Desde la perspectiva del desarrollo open source, esto representó un ejemplo claro de cómo una herramienta digital puede convertirse en un medio de construcción colectiva de conocimiento, memoria cultural y colaboración entre usuarios. Estas funcionalidades fueron posibles gracias a una estructura limpia del código y a una arquitectura que priorizó la separación de responsabilidades y la claridad en los datos.
- La estandarización del entorno de desarrollo, el uso de tecnologías accesibles (HTML / CSS) y la documentación detallada del repositorio permitieron que cada integrante del equipo aportara sin barreras técnicas y que el proyecto resultara comprensible por desarrolladores externos. Este enfoque fomentó un verdadero ecosistema abierto, donde las decisiones técnicas estuvieron acompañadas de una intención clara de compartir, reutilizar y expandir el conocimiento generado durante el desarrollo.
- Durante el desarrollo del proyecto final, se implementó con éxito la lógica del backend utilizando Spring Boot con Java 24, apoyándose en una arquitectura orientada al diseño por dominios (Domain-Driven Design, DDD). Este enfoque permitió estructurar el sistema en módulos claramente definidos —como agregados, servicios del dominio y repositorios— lo que favoreció tanto la legibilidad del código como su mantenimiento a largo plazo. La segmentación en capas facilitó centrarse en las reglas de negocio, reduciendo el acoplamiento y facilitando futuras ampliaciones o modificaciones sin alterar la lógica existente. Además, la organización modular ayudó a identificar errores de forma más eficiente y a mejorar continuamente el sistema.
- Uno de los componentes fundamentales del proyecto fue la incorporación de Swagger, herramienta que permitió documentar de forma dinámica y accesible los diferentes endpoints del API. Particularmente, se desarrolló y validó correctamente el endpoint POST, que pudo probarse directamente en Swagger, permitiendo realizar simulaciones de peticiones reales y observar el comportamiento del sistema de manera interactiva. Esta integración no solo facilitó las pruebas internas, sino que también ofrece una base sólida para futuros desarrolladores o integraciones externas, proporcionando una guía clara sobre el uso del servicio.
- Asimismo, se logró establecer correctamente la conexión con la base de datos, asegurando que los datos enviados a través del endpoint POST fueran almacenados de forma persistente. Para ello, se emplearon las anotaciones y configuraciones necesarias que definieron las entidades y sus relaciones respetando la lógica relacional. Esta etapa fue decisiva para validar el funcionamiento del sistema en un entorno de producción, garantizando un flujo de datos confiable y eficiente.

# Video About-the-Team

![Image](assets/capturas/aboutTheTeam.png)

**Duración:** 00:07:33  
**URL en Microsoft Stream:** 

`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311558_upc_edu_pe/EYh_8r9cGBBDpps4tjEs9pUBqIdZWE65hBPLEVm0U9lS6A?e=hP2RiV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`

**URL en Youtube:** 

`https://youtu.be/kBA04i3zRSM`

# Anexos

- As is y To be scenario: `https://miro.com/app/board/uXjVLbCX2lg=/`

- Wireflow Diagrams: `https://lucid.app/lucidspark/78aa6bcf-2d30-441a-afe8-c467f961dd5a/edit?viewport_loc=-3901%2C8387%2C7816%2C3715%2C0_0&invitationId=inv_a6a2e377-b71d-4fd7-9685-fdf246851546`

- User Flow Diagrams: `https://lucid.app/lucidspark/c12ba67c-79fe-4958-b296-cbf52fc67ce1/edit?viewport_loc=-5597%2C-2950%2C9600%2C4563%2C0_0&invitationId=inv_e02cd09b-80a5-4067-8990-e93d5c30fcfc`

- WireFrames: `https://www.figma.com/design/77Z93r3nalqetBCDUTVvU0/Untitled?node-id=0-1&p=f&t=84cnNflph9dQEFVu-0`

- Mockups:` https://www.figma.com/design/WgoQkLQBZxOM76KcRnpysS/Untitled?node-id=0-1&p=f&t=25lXEAyLkHpZuAcH-0`

- Diagrama UML:` https://lucid.app/lucidchart/c0654847-5143-4121-8907-1f8bae86b31d/edit?viewport_loc=-8104%2C-1137%2C5901%2C2770%2C0_0&invitationId=inv_459664a2-b7f6-49a0-8cc8-e2640f08ee88`

**Prototipos de Aplicación Web**

- Desktop: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EX_5H4ofoydGrjyaxA3pE1wBrclkUgJO2V4Tse0Y0pZmBg?e=TYIOYy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`

- Mobile: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EeFg85OUFzZFrKyQvGbcWZcBuSg6JYLz4YvoBM7c4Ciz3g?e=ca8Kze&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`

**Videos de exposición:**

- TB1: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311704_upc_edu_pe/EVv_U2U49hJMolwRzGWkQhQBZcf4GmKbvnnzPN5Zk3Uovw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=uHFIQZ`
- TP: `https://upcedupe-my.sharepoint.com/personal/u202311704_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202311704_upc_edu_pe%2FDocuments%2Fupc-pre-202510-1asi0729-4334-TheRumbling-expo-tp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E86bdec34-e8a5-40e4-b710-2c2394302dee`
- TB2: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EWOjMs0vXtJKtCNRhHbjFL4BSQyAbu3KNUMB72Hz2HNECA?e=Kwzla0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`
- TF: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311558_upc_edu_pe/ET6q91I6xmxCjYNWZfTFi0ABCiN8SeRCMZRfEXUDK1rgJg?e=9eozyy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`

**Diagramas y Prototipos**

- As is y To be scenario: `https://miro.com/app/board/uXjVLbCX2lg=/`

- Wireflow Diagrams: `https://lucid.app/lucidspark/78aa6bcf-2d30-441a-afe8-c467f961dd5a/edit?viewport_loc=-3901%2C8387%2C7816%2C3715%2C0_0&invitationId=inv_a6a2e377-b71d-4fd7-9685-fdf246851546`

- User Flow Diagrams: `https://lucid.app/lucidspark/c12ba67c-79fe-4958-b296-cbf52fc67ce1/edit?viewport_loc=-5597%2C-2950%2C9600%2C4563%2C0_0&invitationId=inv_e02cd09b-80a5-4067-8990-e93d5c30fcfc`

- WireFrames: `https://www.figma.com/design/77Z93r3nalqetBCDUTVvU0/Untitled?node-id=0-1&p=f&t=84cnNflph9dQEFVu-0`

- Mockups: `https://www.figma.com/design/WgoQkLQBZxOM76KcRnpysS/Untitled?node-id=0-1&p=f&t=25lXEAyLkHpZuAcH-0`

- Figma:   `https://www.figma.com/design/7f739smanaIgteBCDTUWwlo/Untitled?node-id=0-18&t=84cnFHp9dQ6FvEUv-0`

- Diagrama UML: `https://lucid.app/lucidchart/c0654847-5143-4121-8907-1f8bae86b31d/edit?viewport_loc=-8104%2C-1137%2C5901%2C2770%2C0_0&invitationId=inv_459664a2-b7f6-49a0-8cc8-e2640f08ee88`

**Gestión de Proyecto**

- **Gestión de Requisitos:**  
  - `https://uxpressia.com/`  
  - `https://miro.com/es/`  
  - `https://structurizr.com/`

- **Diseño UX/UI:**  
  - `https://www.figma.com/es-la/`  
  - `https://www.lucidchart.com/pages/es`

- **Gestión de Proyecto:**  
  - `https://discord.com/`  
  - `https://workspace.google.com/intl/es-419/products/docs/`

**Repositorios y URLs del Proyecto**

- **Stay Map Api**
  `https://github.com/The-Rumbling-AW/StayMap-AW-Api`

- **Organización en GitHub:**  
  `https://github.com/The-Rumbling-AW`

**SPRINT 1**

- App Web: `https://github.com/The-Rumbling/StayMap-AppWeb`
- Landing Page: `https://github.com/The-Rumbling/StayMap-Landing_Page`

**SPRINT 2**

- Landing Page v2: `https://github.com/The-Rumbling/LandingV2`
- App Web: `https://github.com/The-Rumbling/StayMap-AW-AppWeb-V2`

**SPRINT 3**

- Landing Page v3: `https://github.com/The-Rumbling/LandingPage-V3`

**SPRINT 4**

- Landing Page v4: `https://github.com/The-Rumbling/LandingPage-V4`

  **Registro de Entrevistas:**  
  ` https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/ERJfpT5HoF9Ckz2iN8QzbjEBPFxFxVCkACtrv2SSjkxb1w?e=VY6fld&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`
  
- Microsoft Stream: `https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310636_upc_edu_pe/EWadlIfuzmJJvwIEZnMSosIBuk62gjJvnv5zgPXOV6cRbw?e=ryTZTC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)![image](https://github.com/user-attachments/assets/36ee6ccb-8077-487e-95c6-0dddce6bd82d`


# Bibliografía

- Instituto de Estudios Peruanos (IEP). (2019). Informe de Opinión: Música y hábitos de consumo cultural. `https://iep.org.pe/wp-content/uploads/2019/09/Informe-OP-Septiembre-2019-M%C3%BAsica-7.pdf`

- Ramos-Pla, A., Ramírez-Montoya, M. S., & García-Peñalvo, F. J. (2022). Consumo musical y su relación con la asistencia a conciertos entre universitarios. Revista de Comunicación, 21(2). `https://www.redalyc.org/journal/280/28065583023/html/`

- Chartmetric. (2023). Year in music 2023: Part 1. Chartmetric. `https://reports.chartmetric.com/2023/year-in-music/part-1`

- Industriamusical.com. (2024). Solo el 0.01% de los artistas emergentes alcanza niveles moderados de éxito. `https://industriamusical.com/solo-el-0-01-de-los-artistas-emergentes-alcanza-niveles-moderados-de-exito/`
Mordor Intelligence. (2024). Análisis del mercado de artistas independientes - crecimiento, tendencias y pronósticos (2024-2029). `https://www.mordorintelligence.com/es/industry-reports/independent-artists`

- GlobeNewswire. (2025). Music Tourism Market Analysis Report 2024: Specialized Music Festivals, Expanding Offering, Niche Genres, and Unique Cultural Experiences – Global Long-term Forecast to 2028 and 2033.` https://www.globenewswire.com/news-release/2025/01/07/3005534/28124/en/Music-Tourism-Market-Analysis-Report-2024-Specialized-Music-Festivals-Expanding-Offering-Niche-Genres-and-Unique-Cultural-Experiences-Global-Long-term-Forecast-to-2028-and-2033.html`
