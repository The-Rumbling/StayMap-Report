<div align="center">
  
## Universidad Peruana de Ciencias Aplicadas

![Image](images/upc-logo.png)

## TB1 "StayMap"


**1ASI0729 - DESARROLLO DE APLICACIONES OPEN SOURCE**

Carrera de Ingeniería de Software


**NRC:** 2510-4334

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
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TP</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TB2</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TF</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Contents

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
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME
ABET - EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
<tbody>
    <tr>
      <td>Comunica oralmente con efectividad a diferentes rangos de audiencia</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Comunica por escrito con efectividad a diferentes rangos de audiencia</td>
      <td></td>
      <td></td>
    </tr>
    </tbody>
</table>

# CAPÍTULO I: INTRODUCCIÓN

# 1.1. Startup Profile

## 1.1.1. Descripción de la Startup
MIROH es una startup creativa y tecnológica comprometida con transformar la manera en que las personas descubren, conectan y viven la música en vivo. Creemos que cada concierto, sin importar su tamaño, tiene el poder de generar emociones únicas y crear vínculos duraderos entre artistas y fans. Por ello, trabajamos en soluciones digitales innovadoras que conectan al público con experiencias musicales auténticas y accesibles.
Nos enfocamos en el desarrollo de StayMap, una aplicación web interactiva que actúa como un puente entre los amantes de la música y los escenarios de su ciudad. A través de un mapa dinámico con geolocalización, los usuarios pueden explorar eventos en tiempo real, seguir a sus artistas favoritos, conocer las fechas de sus giras, hacer check-in en conciertos y compartir momentos con otros fans. Además, brindamos herramientas de promoción y visibilidad para bandas emergentes, contribuyendo activamente al crecimiento de la escena musical independiente.
En MIROH, apostamos por el poder de la comunidad, el descubrimiento espontáneo y la tecnología como medio para enriquecer las experiencias culturales. Nuestra visión es construir una red global donde cada presentación en vivo —desde un bar local hasta un festival internacional— pueda ser descubierta, compartida y vivida al máximo, celebrando la diversidad y el dinamismo del mundo musical.
Con pasión, creatividad y enfoque social, desde el corazón de MIROH impulsamos proyectos como StayMap, que reimaginan el futuro de la música en vivo y lo acercan a quienes más lo disfrutan.

## 1.1.2. Perfiles de integrantes del equipo

<table>
  <thead>
    <tr>
      <th>Estudiante</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="assets/profile_images/diego_collantes.png" alt="team member profile photo" style="width: 300px">Collantes Carrillo, Diego Mateo (u202311823)</td>
      <td>Mi nombre es Diego Collantes. Tengo 19 años. Soy estudiante de quinto ciclo en la Universidad Peruana de Ciencias Aplicadas (UPC). Disfruto de leer, redactar y escuchar música en mi tiempo libre. Elegí esta carrera, ya que me interesó todo el proceso que hay detrás de cada aplicación o programa que usamos en nuestro día a día. Personalmente, espero ampliar mis conocimientos en este ámbito a lo largo de este curso. Además, estoy comprometido a contribuir en todo lo que sea posible con el equipo y a desempeñarme de manera adecuada.
</td>
    </tr>
    <tr>
       <td><img src="assets/profile_images/ariana_lizarbe.png" alt="team member profile photo" style="width: 300px">Lizarbe Alvarez, Ariana Nickole (u202311704)</td>
      <td>Mi nombre es Ariana Lizarbe, tengo 19 años y estoy cursando el cuarto ciclo de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. En mi tiempo libre fuera de la universidad, procuro mejorar mis habilidades blandas, como la empatía o inteligencia emocional. También, me esfuerzo en adquirir conocimientos que pueden ayudarme a desarrollarme como futura profesional, como distintos lenguajes de programación. A su vez, disfruto de escuchar música, podcasts, leer y ver series de televisión. Me comprometo a colaborar de manera activa y responsable en la creación de esta startup, aportando mis habilidades en pensamiento crítico, trabajo en equipo y adaptabilidad para alcanzar un trabajo de calidad sobresaliente.
</td>
    </tr>
    <tr>
      <td><img src="assets/profile_images/antuanete_ortiz.png" alt="team member profile photo" style="width: 300px">Ortiz Cardenas, Johanna Antuanete (u202310358)</td>
      <td>Mi nombre es Johanna Antuanete Ortiz Cárdenas, tengo 18 años y me encuentro en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona proactiva y responsable, siempre buscando que mis trabajos sean de la mejor calidad posible. Me apasiona investigar sobre tecnología, lo que me permite estar al tanto de las últimas novedades y tendencias. En mi tiempo libre, disfruto jugar videojuegos, escuchar música y leer cómics. En el presente proyecto grupal, me comprometo a colaborar de manera activa, aportando ideas y siendo puntual con los entregables para garantizar resultados sobresalientes.
</td>
    </tr>
    <tr>
      <td><img src="assets/profile_images/renato_zegarra.png" alt="team member profile photo" style="width: 300px">Zegarra Lopez, Renato Sebastian Rubber (u202311558)</td>
      <td>Mi nombre es Renato Zegarra, tengo 19 años y actualmente estoy cursando la carrera de Ingeniería de Sistemas de Información en la Universidad Peruana de Ciencias Aplicadas. Fuera de mis estudios, disfruto explorar mis intereses en música, videojuegos y tecnología, siempre buscando nuevas formas de integrar estas pasiones en mi vida cotidiana. Me comprometo a colaborar de manera activa y responsable en la elaboración de este documento y en la concreción de la idea propuesta, aportando mis habilidades en análisis, creatividad y adaptabilidad. Estoy convencido de que con esfuerzo y trabajo en equipo, podemos alcanzar resultados innovadores y de alta calidad.
</td>
    </tr>
    <tr>
       <td><img src="assets/profile_images/diego_zuniga.png" alt="team member profile photo" style="width: 300px">Zúñiga Murillo, Diego Sebastian (u202310636)</td>
      <td>Mi nombre es Diego Sebastián Zúñiga Murillo, tengo 20 años y actualmente curso el quinto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona puntual, participativa y responsable, con una fuerte pasión por la tecnología y el aprendizaje constante.
En mi tiempo libre disfruto de escuchar música, lo que me ayuda a relajarme y mantener el equilibrio entre mis estudios y mi vida personal. Como estudiante, me comprometo a aportar activamente en el desarrollo de este proyecto, contribuyendo con creatividad, iniciativa y habilidades de liderazgo.
Confío en que, trabajando en equipo y manteniendo una comunicación constante, lograremos resultados destacados que reflejan nuestro esfuerzo y compromiso.
</td>
    </tr>
  </tbody>
</table>

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
- Servirá como una guía personalizada que los acompaña constantemente, promoviendo el bienestar, la seguridad y la exploración responsable.

**¿Qué problemas tiene nuestro producto?**
- Falta de información confiable y en tiempo real sobre la seguridad, ambiente o calidad de los lugares públicos.
- Inseguridad urbana o zonas desconocidas que pueden generar ansiedad al moverse sin una guía confiable.
- Escasez de soluciones intuitivas que integren datos, bienestar y mapas personalizados de forma sencilla para el usuario común.

**¿Cuándo y cómo es nuestro producto utilizado?**
- StayMap se usa cuando las personas están por salir y quieren conocer un nuevo lugar..
- A lo largo del día: durante el trabajo, caminatas, paseos, o al momento de organizar actividades personales.
- Disponible en móviles y web, debe ser intuitiva y accesible para usuarios con distintos niveles de experiencia tecnológica.

**¿Qué características son importantes?**
- Mapas interactivos y personalizados según los gustos del usuario.
- Información actualizada sobre seguridad, afluencia, accesibilidad y ambiente del lugar.
- Alertas sobre zonas peligrosas o inconvenientes según el perfil del usuario.
- Recomendaciones en tiempo real basadas en preferencias, historial y localización.
- Integración con sensores o API externas para datos de tráfico, clima, etc.
  
**Objetivos**
- Evitar riesgos: Brindar información de zonas a evitar por seguridad, saturación o inadecuación con el perfil del usuario.
- Descubrimiento personalizado: Impulsar la exploración de lugares nuevos según gustos, intereses y momentos del día.
- Fomentar la conexión positiva con el entorno urbano: Convertir la movilidad urbana en una experiencia positiva, intuitiva y segura.
  
**Alcances**

Asistencia personalizada en tiempo real
- Recomendaciones de lugares seguros, tranquilos o estimulantes según el estado de ánimo del usuario.
- Guías para llegar de forma segura y eficiente a los destinos deseados.
  
Optimización de la experiencia urbana
- Ahorro de tiempo y energía evitando lugares inadecuados o con problemas (tráfico, obras, peligro, etc.).
- Visualización en mapas de los mejores espacios para descansar, trabajar, socializar o pasear.
  
Promoción de bienestar y seguridad
- Alertas y notificaciones ante zonas inseguras o poco recomendadas según el momento del día.
- Sugerencias que promueven el autocuidado y la conexión positiva con el entorno.

Accesibilidad y usabilidad
- Interfaz sencilla, moderna e intuitiva para todo tipo de usuarios.
- Disponible en smartphones, tablets y computadoras, incluso con acceso limitado a internet en algunos casos.

Conexión con expertos y comunidad
- Espacio para recibir recomendaciones de expertos (psicólogos, urbanistas, etc.) o experiencias de otros usuarios.
- Comunidad que comparte tips y lugares seguros, con opción de valorar y comentar.

**Escalabilidad**
- Adaptable a distintas ciudades, regiones y culturas urbanas.
- Capacidad para expandirse globalmente, integrando datos locales específicos según cada comunidad.
¿Cómo debe verse nuestro producto y cómo debe comportarse?
- Interfaz clara, amigable y acogedora.
- Fluidez en la experiencia, con transiciones suaves, botones accesibles y navegación simple.
- Alta confiabilidad en los datos mostrados y bajo margen de error en recomendaciones.
- Capacidad de adaptarse al perfil emocional y de movilidad de cada usuario.

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
- Mapas personalizados según perfil del usuario, hora del día y contexto local.
- Alertas en tiempo real sobre zonas peligrosas, congestionadas o poco recomendadas.
- Modo "estado de ánimo" para sugerencias según cómo se siente el usuario (relajado, ansioso, social, introspectivo...).
- Evaluaciones y puntuaciones de lugares según criterios de seguridad, ambiente, accesibilidad, etc.
- Módulo de comunidad para compartir experiencias y recomendaciones.
- Panel de control con estadísticas sobre hábitos de movilidad, zonas favoritas, y mejoras sugeridas.

#### 1.2.2.3. Lean UX Hypothesis Statements.
Creemos que, si StayMap tiene una interfaz intuitiva y está optimizada para dispositivos móviles, incluso los usuarios con poca experiencia tecnológica podrán usar la aplicación fácilmente para orientarse y explorar nuevas zonas.
Creemos que, si StayMap proporciona datos actualizados en tiempo real sobre zonas seguras e inseguras, los usuarios podrán planificar mejor sus recorridos y evitar áreas de riesgo, mejorando su experiencia de movilidad.
Creemos que, si StayMap ofrece recomendaciones de lugares según intereses del usuario y zonas seguras cercanas, se fomentará la exploración urbana con mayor confianza y seguridad, atrayendo a viajeros más curiosos.
Creemos que, si StayMap integra una comunidad activa donde los usuarios pueden reportar incidentes o compartir experiencias, se generará confianza colectiva y participación constante, fortaleciendo el valor colaborativo de la app.
Creemos que, si StayMap funciona eficazmente en zonas con conectividad limitada o intermitente, será útil para viajeros en contextos rurales o en ciudades con poca cobertura de red, aumentando su alcance y utilidad.
Creemos que, si StayMap ofrece notificaciones personalizadas sobre alertas de seguridad, eventos o cambios en zonas frecuentadas, los usuarios podrán reaccionar rápidamente y sentirse más seguros al desplazarse.
Creemos que, si StayMap permite guardar rutas favoritas y recibir sugerencias basadas en comportamientos pasados, los usuarios tendrán una experiencia más personalizada y práctica, incrementando su uso continuo.
Creemos que, si StayMap incluye un modo offline con mapas básicos y alertas descargadas previamente, los usuarios podrán seguir navegando con seguridad incluso sin conexión, reforzando la confianza en la app.

#### 1.2.2.3. Lean UX Canvas. 

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

# 1.3. Segmentos objetivo.

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

#### 2.1.1. Análisis competitivo
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
				<li>Basic: $99</li>
				<li>Pro: $199</li>
				<li>Enterprise: $399</li>
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

## 2.1.2. Estrategias y tácticas frente a competidores.

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

## 2.2. Entrevistas.

## 2.2.1. Diseño de entrevistas.

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

## 2.2.2. Registro de entrevistas.
## 2.3. Needfinding.
## 2.3.1. User Personas.
Los user personas son perfiles representativos de los usuarios que ayudan a comprender mejor sus necesidades, motivaciones y comportamientos. En StayMap, estos perfiles guían el diseño y desarrollo de la plataforma para asegurar que responda a lo que realmente buscan nuestros principales segmentos, como los fans de la música y los artistas emergentes.

<img src="assets/user_persona/valeria_torres.png" alt="user_persona1" style="width: 600px">





