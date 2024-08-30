# Rampart

Product: Sentinel

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1257109045723271192/1274742305080737884/UPCLogo.png?ex=66c35bc9&is=66c20a49&hm=f1d242afd6f2610d918693b6cf1a25608406f2ea70eefd2a6926ca8f5df8251a&">
</p>

## Ingenieria de Software

## 5to ciclo

## Aplicaciones Web

### **Sección:** WS51

### **Profesor:** Hugo Allan Mori Paiva

### Informe de Trabajo Final

### "Rampart"

### "Sabores Cercanos"

### **Integrantes:**

- Estefano Oscar Jaque Peña - u202225466
- Maria Jose Pezo Castilla - u20221c590
- Jose Antonio Alejo Cardenas - u202122484
- Diego Alonso Rosado Iporre - u201620127
- Sebastian Omar Real Calderón - u20221d964

### Agosto, 2024

## Registro de Versiones del Informe

## Project Report Collaboration Insights

## Contenido

### Tabla de contenidos

1. [**Capítulo I: Introducción**](#capítulo-i-introducción)
   1. [Startup Profile](#11-startup-profile)
      1. [Descripción de la Startup](#111-descripción-de-la-startup)
      2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   2. [Solution Profile](#12-solution-profile)
      1. [Antecedentes y problemática](#121-antecedentes-y-problemática)
      2. [Lean UX Process](#122-lean-ux-process)
         1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
         3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
         4. [Lean UX Canvas](#1224-lean-ux-canvas)
   3. [Segmentos objetivo](#13-segmentos-objetivo)
2. [**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)
   1. [Competidores](#21-competidores)
      1. [Análisis competitivo](#211-análisis-competitivo)
      2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
   2. [Entrevistas](#22-entrevistas)
      1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
      2. [Registro de entrevistas](#222-registro-de-entrevistas)
      3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
   3. [Needfinding](#23-needfinding)
      1. [User Personas](#231-user-personas)
      2. [User Task Matrix](#232-user-task-matrix)
      3. [User Journey Mapping](#233-user-journey-mapping)
      4. [Empathy Mapping](#234-empathy-mapping)
      5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)
   4. [Ubiquitous Language](#24-ubiquitous-language)
3. [**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification)
   1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)
   2. [User Stories](#32-user-stories)
   3. [Impact Mapping](#33-impact-mapping)
   4. [Product Backlog](#34-product-backlog)

4. [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
   1. [Style Guidelines](#41-style-guidelines)
      1. [General Style Guidelines](#411-general-style-guidelines)
      2. [Web Style Guidelines](#412-web-style-guidelines)
   2. [Information Architecture](#42-information-architecture)
      1. [Organization Systems](#421-organization-systems)
      2. [Labeling Systems](#422-labeling-systems)
      3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      4. [Searching Systems](#424-searching-systems)
      5. [Navigation Systems](#425-navigation-systems)
   3. [Landing Page UI Design](#43-landing-page-ui-design)
      1. [Landing Page Wireframe](#431-landing-page-wireframe)
      2. [Landing Page Mock-up](#432-landing-page-mock-up)
   4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)
      1. [Web Applications Wireframes](#441-web-applications-wireframes)
      2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
      3. [Web Applications Mock-ups](#443-web-applications-mock-ups)
      4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
   5. [Web Applications Prototyping](#45-web-applications-prototyping)
   6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
      1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)
      2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
      3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
   7. [Software Object-Oriented Design](#47-software-object-oriented-design)
      1. [Class Diagrams](#471-class-diagrams)
      2. [Class Dictionary](#472-class-dictionary)
   8. [Database Design](#48-database-design)
      1. [Database Diagram](#481-database-diagram)
5. [**Capítulo V: Product Implementation, Validation & Deployment**](#capítulo-v-product-implementation-validation--deployment)
   1. [Software Configuration Management](#51-software-configuration-management)
      1. [Software Development Environment Configuration](#511-software-development-environment-configuration)
      2. [Source Code Management](#512-source-code-management)
      3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
      4. [Software Deployment Configuration](#514-software-deployment-configuration)
   2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
      1. [Sprint 1](#521-sprint-1)
         1. [Sprint Planning 1](#5211-sprint-planning-1)
         2. [Sprint Backlog 1](#5212-sprint-backlog-1)
         3. [Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
         4. [Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
         5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
         6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
         7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
         8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)



## Student Outcome

_ABET – EAC - Student Outcome 5_

**Criterio:**  La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos. 

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5. 

| Criterio especifico                                                          | Acciones Realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Conclusiones |
| :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------- |
| 1.Trabaja en equipo para proporcionar liderazgo en forma conjunta   | **Estefano Oscar Jaque Peña**<br>TB1: Realice el Lean UX Prolem statements y los assumptions<br> **Diego Alonso Rosado Iporre**<br> TB1: Realice la "Descripción de la estrategia de la Startup" y 2 entrevistas <br>**Jose Antonio Alejo Cardenas:** <br>TB1: "Realice el Lean UX Hypothesis Statements y Lean UX Canvas" <br>**Sebastian**<br> TB1: "Lo que avanzaste en la TB1"<br>**Maria Jose Pezo Castilla** <br>TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática | **TB1:** <br>     |
| 2. Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.  | **Estefano Oscar Jaque Peña**<br>TB1: Realice el Lean UX Prolem statements y los assumptions<br> **Diego Alonso Rosado Iporre**<br> TB1: Realice la "Descripción de la estrategia de la Startup" y 2 entrevistas <br>**Jose Antonio Alejo Cardenas**<br> TB1: "Realice el Lean UX Hypothesis Statements y Lean UX Canvas" <br>**Sebastian**<br> TB1: "Lo que avanzaste en la TB1"<br>**Maria** <br>TB1: Realice la "Descripción de la Startup" y "Antecedentes y problemática | **TB1:** <br>     |

## Capítulo I: Introducción

### 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

   "Sabores Cercanos" es una plataforma web diseñada para conectar a cocineros caseros con universitarios y profesionales que carecen de tiempo para cocinar. La plataforma permite a los cocineros ofrecer sus servicios de comida, incluyendo menús personalizados, precios, ubicaciones, y ofertas especiales. Los consumidores pueden buscar, seleccionar y pedir comida casera de cocineros locales, basándose en sus preferencias alimenticias y restricciones dietéticas. Además, "Sabores Cercanos" promueve una comunidad culinaria activa donde se pueden compartir y descubrir recetas, fomentando la interacción entre cocineros y consumidores.

   La propuesta de valor de "Sabores Cercanos" se centra en proporcionar comida casera de calidad, personalizada y a precios asequibles, mientras que ofrece a los cocineros una vía para generar ingresos adicionales de forma flexible. A través de una interfaz intuitiva y procesos eficientes, "Sabores Cercanos" crea un ecosistema donde la pasión por la cocina y la necesidad de comidas prácticas y saludables se encuentran.

###### Misión:

   La misión de "Sabores Cercanos" es transformar la forma en que las personas acceden a la comida casera, conectando a cocineros apasionados con consumidores que buscan opciones de alimentación saludable y conveniente. Aspiramos a empoderar a los cocineros caseros, brindándoles la oportunidad de monetizar sus habilidades culinarias, mientras mejoramos la calidad de vida de nuestros consumidores a través de alimentos nutritivos y sabrosos. Fomentamos una comunidad en la que compartir la pasión por la cocina se convierte en una experiencia enriquecedora para todos.


###### Visión:

   Nuestra visión es ser la plataforma líder en conectar cocineros caseros y consumidores en América Latina, reconocida por ofrecer calidad, confianza y una experiencia gastronómica única. Queremos crear un movimiento que celebre la comida casera y las tradiciones culinarias locales, mientras promovemos estilos de vida saludables y sostenibles. Buscamos establecer un estándar en la economía colaborativa del sector alimentario, donde la comida casera se convierta en una opción accesible y preferida para todos, y donde cada cocinero tenga la oportunidad de compartir su talento y mejorar su vida.


### 1.1.2. Perfiles de integrantes del equipo

- Estefano Oscar Jaque Peña - U202225466

| <p align="center"><img src="https://cdn.discordapp.com/attachments/1246609784501833810/1275485196589732011/image.png?ex=66c60fa8&is=66c4be28&hm=28e9a7ace2f1c7416404ba1e95041b745cda9a5046b828c99ca1a5039445b645&"> </p> | Soy Estefano Oscar Jaque Peña, tengo 23 años y soy estudiante de la carrera de Ingeniería de Software,<br> una disciplina enfocada en el diseño, desarrollo y gestión de software para solucionar problemas <br>complejos. Desde temprana edad, he sentido fascinación por la tecnología y he buscado aprender <br>constantemente sobre las últimas tendencias en programación. He ampliado mis conocimientos a <br>través de cursos en Python, SQL, y C++, así como también explorando otros lenguajes de programación <br>por mi cuenta. Además, tengo habilidades en el uso avanzado de Excel para análisis de datos y gestión<br> de información. Mi experiencia trabajando en equipos me ha brindado habilidades de comunicación y <br>colaboración que considero fundamentales para contribuir de manera efectiva a proyectos innovadores<br> en el área de la Ingeniería de Software. |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

- Diego Alonso Rosado Iporre -   u201620127

| <p align="center"><img width="auto" height="auto" src="assets/images/Diego_profile.jpg"> </p> | Mi nombre es Diego Rosado, tengo 24 años. Mi interés en las base de datos y arquitectura de páginas web me impulsó a estudiar Ingeniería de Software. Tengo conocimiento de lenguajes como C#, C++, JavaScript, Python, base de datos como MySQL y me atrae el diseño de páginas web con HTML y CSS. Me considero una persona positiva, tolerante y creativa. Mi aporte al grupo es mi total compromiso, apoyo mutuo y el esfuerzo por asegurar que todos tengamos una visión compartida del proyecto a elaborar. Mis habilidades son resolución de problemas, adaptabilidad, trabajo en equipo y toma de decisiones.  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |

- Maria Jose Pezo Castilla - u20221c590

| <p align="center"><img width="3400" src="https://media.discordapp.net/attachments/901630327104098306/1276695934205563021/Captura_de_pantalla_2024-08-23_191337.png?ex=66ca773e&is=66c925be&hm=8ecdeeaa826af9558f127a149bcdfaf96f9b56561909f8922aad20b4abd50bc0&=&format=webp&quality=lossless&width=197&height=387"> </p> | Mi nombre es Maria Jose Pezo Castilla tengo 22 años, actualmente curso el quinto ciclo de la carrera de Ingeniería de Software. Soy una persona responsable, disciplinada y dedicada, tengo gran capacidad para adaptarme a diversos entornos y aportar siempre lo mejor de mi. Me caracterizo por mi facilidad para el trabajo en equipo y mi entusiasmo por aprender y desarrollar mis habilidades. He estudiado lenguajes de programación como C++, C# y HTML; y bases de datos como Microsoft SQL Server y Mongo DB.Asimismo, me considero una persona asertiva y empática con predisposición al aprendizaje continuo. Poseo habilidades para la programación y elaboracion de algoritmos que brinden soluciones efectivas a necesidades o problemáticas específicas.Mis principales hobbies son bailar, entrenar y lee. Para el desarrollo eficiente del presente proyecto pondre en práctica todos mis conocimientos aprendidos, brindare apoyo y entablare una comunicación efectiva. 
|-|-|
- José Antonio Alejo Cárdenas - U202122484

| <p align="center"><img width="3400" src="https://cdn.discordapp.com/attachments/1257109045723271192/1275483107750969374/431736242_1183080929593718_8350965829789705455_n.jpg?ex=66c60db6&is=66c4bc36&hm=474bf1421134dedcd161b88fdedca0785b7ee469488a854a42e817df68a83594&"> </p> | Soy José Alejo Cárdenas tengo 23 años soy estudiante de la carrera de Ingeniería de Software del quinto ciclo. Desde pequeño he sentido facinacion por la tecnologia en general sobretodo por el funcionamiento, desarrollo y proteccion del software. He estudiado lenguajes de programacion (java, python y C++), bases de datos (Microsoft SQL Server y Mongo DB) y Sistemas Operativos (Kali Linux y Windows). Asi mismo, tengo experiencia con hardware a nivel de esamblamiento de equipos y funcionamiento del mismo con sus especificaciones tecnicas. Además, mi constante comunicacion y organizacion durante cualquier trabajo grupal aportara mucho dinamismo al proyecto. Mis principales hobbies son entrenar en el gimnasio, jugar videojuegos con mis amigos y salir a conversar con estos ultimos durante algun almuerzo o cena. Para el proyecto aportare organizacion, comunicacion e inspiracion durante todo el transcurso del mismo.
|-|-|
- Sebastián Omar Real Calderón - U20221D964

| <p align="center"><img width="1000" src="https://cdn.discordapp.com/attachments/1257109045723271192/1275936058374094980/1724277214669.jpg?ex=66c7b38e&is=66c6620e&hm=a17b700270de2217e5f60519bc30e8e2445db4d076b675ce824f4eeda9f9a41f&"> </p> | Soy Sebastián Real Calderón, tengo 19 años y soy estudiante de la carrera de Ingeniería de Software. Tengo conocimientos sobre lenguajes de programación como C++, C# y Java. Principalmente me dedico al desarrollo de proyectos que me permitan desarrollar mis habilidades de programación, tales como videojuegos o programas sencillos, ya que apunto a volverme desarrollador. Dentro de mis hobbies están los videojuegos, las series, el baile y el fútbol.
|-|-|

### 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática



###### What?

- _¿Qué problema hay?_

   Muchas personas, especialmente universitarios y profesionales, no tienen tiempo para cocinar debido a sus horarios ocupados. Esto los lleva a depender de comida rápida o de baja calidad, afectando su salud y bienestar. Por otro lado, hay muchas personas que disfrutan cocinar y buscan una manera de generar ingresos adicionales desde casa.



- _¿Qué relación tiene el problema con el usuario/cliente?_

   Los consumidores buscan una opción de comida casera y saludable que se ajuste a su estilo de vida ocupado. Los cocineros buscan una manera de monetizar su habilidad culinaria sin tener que invertir en un restaurante completo o un negocio de catering.



###### When?

- _¿Cuándo sucede el problema?_

   El problema es continuo. Ocurre diariamente cuando los consumidores enfrentan la necesidad de comer mientras equilibran otras responsabilidades, como el trabajo o los estudios. El problema se intensifica durante las horas pico de almuerzo y cena, cuando el tiempo es limitado.



- _¿Cuándo el cliente necesita el programa?_

   Los consumidores necesitan la plataforma durante sus horarios de comida, especialmente durante el almuerzo y la cena. Los cocineros necesitan la plataforma para poder planificar y gestionar sus servicios de manera eficiente, incluyendo la publicación de menús y la preparación de pedidos.



###### Where?

- _¿Dónde el cliente usara el producto?_

   La aplicación se usará principalmente en entornos urbanos y semiurbanos, donde hay una alta concentración de profesionales y estudiantes. Los consumidores usarán la aplicación desde sus teléfonos móviles o computadoras para hacer pedidos mientras están en casa, en la oficina o en el campus.



- _¿A quién está destinado?_

   Está destinado a dos segmentos principales: cocineros caseros que buscan ingresos adicionales y consumidores, principalmente universitarios y profesionales, que buscan comida casera y saludable sin tener que cocinar.



###### Who?

- _¿Quiénes van a involucrarse con nuestra aplicación?_

   Cocineros caseros, consumidores (universitarios y profesionales), repartidores (si se incluye el servicio de entrega), y administradores de la plataforma. Además, pueden involucrarse socios de pago y servicios de logística.



- _¿Quiénes son afectados por el problema?_

   Los consumidores afectados son aquellos que tienen poco tiempo para cocinar pero valoran una alimentación saludable. Los cocineros que tienen habilidades culinarias y buscan monetizarlas también están afectados por la falta de plataformas accesibles para ofrecer sus servicios.



- _¿Quién utilizará este producto?_

   El producto será utilizado por cocineros caseros para ofrecer sus servicios y por consumidores que buscan comidas caseras y saludables. También podría ser utilizado por repartidores para gestionar las entregas.



###### Why?

- _¿Por qué ocurre el problema?_

   El ritmo de vida moderno es acelerado, dejando poco tiempo para cocinar. Además, hay una falta de opciones accesibles que ofrezcan comida casera y saludable. A menudo, la comida rápida es la opción más conveniente, pero no siempre es la más saludable.



- _¿Por qué los clientes elegirían utilizar nuestro producto?_

   Los clientes elegirían "Sabores Cercanos" porque ofrece una alternativa conveniente, saludable y asequible a la comida rápida, con el beneficio añadido de apoyar a cocineros locales. Además, la posibilidad de personalizar pedidos y conocer de antemano quién prepara la comida añade un valor significativo.



- _¿Por qué las personas estarán motivadas a usar nuestra aplicación?_

   Las personas estarán motivadas por la conveniencia de recibir comida casera y saludable, la variedad de opciones disponibles, y la conexión con su comunidad. Para los cocineros, la motivación proviene de la oportunidad de ganar dinero haciendo lo que aman, sin los costos y riesgos asociados con un negocio de restauración tradicional.


###### Who?

- _¿Cómo nos descubren nuestros clientes?_

   Los clientes pueden descubrir "Sabores Cercanos" a través de estrategias de marketing digital, publicidad en redes sociales, colaboraciones con universidades y espacios de trabajo, y a través del boca a boca en la comunidad local.



- _¿Cómo pueden los clientes acceder a nuestro contenido?_

   Los clientes pueden acceder al contenido a través de la aplicación móvil o el sitio web de "Sabores Cercanos". Además, recibirán notificaciones y alertas sobre nuevas ofertas y publicaciones de recetas.



- _¿Qué factores llevan a los clientes a elegirnos?_

   Factores como la conveniencia, la personalización de los pedidos, la calidad y la frescura de los ingredientes, la posibilidad de apoyar a cocineros locales, y la interacción dentro de una comunidad culinaria atractiva son claves para que los clientes elijan "Sabores Cercanos".


###### How much?

   La aplicación generará ingresos principalmente a través de comisiones por transacción. Los cocineros pueden usar la plataforma de forma gratuita, pero se retendrá un porcentaje de cada pedido realizado. Los consumidores pagan por los pedidos que realicen, con precios establecidos por los cocineros. Además, podría haber modelos de suscripción para acceder a recetas exclusivas o servicios premium.



### 1.2.2. Lean UX Process
El proceso Lean UX se adapta especialmente bien a startups como SSVR que buscan crear soluciones innovadoras y efectivas en el mercado. Este enfoque se caracteriza por su agilidad y centrado en el usuario, lo que significa que estamos constantemente buscando validar nuestras ideas y prototipos con los usuarios para garantizar que estamos abordando sus necesidades de manera adecuada. 
### 1.2.2.1. Lean UX Problem Statements
La aplicación generará ingresos principalmente a través de comisiones por transacción. Los cocineros pueden usar la plataforma de forma gratuita, pero se retendrá un porcentaje de cada pedido realizado. Los consumidores pagan por los pedidos que realicen, con precios establecidos por los cocineros. Además, podría haber modelos de suscripción para acceder a recetas exclusivas o servicios premium.

Hemos identificado un desafío significativo para los consumidores, quienes a menudo recurren a comida rápida o de baja calidad debido a la falta de tiempo para cocinar. Esto impacta negativamente su salud y bienestar. Simultáneamente, existen cocineros caseros que buscan oportunidades para monetizar sus habilidades culinarias, pero no tienen acceso a una plataforma que les permita hacerlo de manera flexible y sin grandes inversiones.

¿Cómo podemos mejorar la experiencia de los consumidores que buscan opciones de comida saludable y casera, y al mismo tiempo, ofrecer a los cocineros caseros una vía efectiva para generar ingresos adicionales?
### 1.2.2.2. Lean UX Assumptions
### Assumptions para "Sabores Cercanos"
**Assumptions:** 
1. Creo que mis clientes necesitan una opción accesible y saludable de comida casera que se adapte a su estilo de vida ocupado.
2. Estas necesidades se pueden resolver con una plataforma que conecte a consumidores con cocineros caseros locales.
3. Mis clientes iniciales son (o serán) universitarios y profesionales que tienen poco tiempo para cocinar.
4. El valor #1 que un cliente quiere de mi servicio es la conveniencia de recibir comida casera y personalizada.
5. El cliente también puede obtener estos beneficios adicionales apoyo a la economía local, la posibilidad de personalizar sus pedidos, y el acceso a una comunidad culinaria.
6. Voy a adquirir la mayoría de mis clientes a través de marketing digital, redes sociales, y colaboraciones con universidades y espacios de trabajo.
7. Haré dinero a través de comisiones por transacción en los pedidos realizados a través de la plataforma.
8. Mi competencia principal en el mercado será servicios de comida rápida y aplicaciones de delivery.
9. Los venceremos debido a la personalización, la calidad de la comida casera, y la conexión con la comunidad local.
10. Mi mayor riesgo de producto es que los cocineros no puedan cumplir con la demanda o que los consumidores no encuentren suficiente variedad.
11. Resolveremos esto a través de una cuidadosa gestión de la oferta y la demanda, y mediante incentivos para atraer a más cocineros a la plataforma.
Aquí tienes un conjunto de **assumptions (supuestos)** para "Sabores Cercanos":

1) **¿Quién es el usuario?**
   - Universitarios y profesionales ocupados que buscan opciones de comida casera y saludable.
   - Cocineros caseros interesados en generar ingresos adicionales.

2) **¿Dónde encaja nuestro producto en su trabajo o vida?**
   - Para los consumidores, la plataforma encaja en su rutina diaria, especialmente en las horas de almuerzo y cena, ofreciendo una solución conveniente y saludable.
   - Para los cocineros, la plataforma encaja en su vida como una oportunidad flexible para monetizar sus habilidades culinarias desde casa.

3) **¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**
   - Problema: Dificultad en personalizar las ofertas para diferentes dietas y preferencias alimenticias.
   - Solución: Implementar filtros avanzados y opciones de personalización en la plataforma para adaptarse a las necesidades específicas de los usuarios.

4) **¿Cuándo y cómo es usado nuestro producto?**
   - El producto se usa principalmente durante las horas de comida, cuando los consumidores necesitan una solución rápida y saludable. Se accede a través de dispositivos móviles o computadoras.

5) **¿Qué características son importantes?**
   - Facilidad de uso, personalización de menús, comunicación fluida entre cocineros y consumidores, y un sistema de notificaciones eficaz para pedidos y promociones.

6) **¿Cómo debe verse nuestro producto y cómo debe comportarse?**
   - El diseño debe ser atractivo, limpio y fácil de navegar, destacando la frescura y calidad de los ingredientes. Debe ser intuitivo, rápido, y confiable, con un énfasis en la comunidad y la conexión personal entre cocineros y consumidores.

**Business Outcomes:**

1. Incrementar la base de cocineros registrados en un 20% en los próximos seis meses.
2. Aumentar el número de pedidos diarios en un 30% en el primer año.
3. Mejorar la retención de clientes recurrentes en un 25% mediante promociones personalizadas.
4. Expandir la presencia de la plataforma en cinco nuevas ciudades dentro del próximo año.
5. Maximizar las ganancias por transacción incrementando el ticket promedio en un 15%.

**User Outcomes:**

1. Los consumidores obtendrán acceso rápido a comidas caseras personalizadas según sus preferencias dietéticas.
2. Los cocineros podrán generar ingresos adicionales sin complicaciones, ofreciendo sus menús a través de la plataforma.
3. Los usuarios disfrutarán de notificaciones oportunas sobre ofertas y promociones que se adapten a sus necesidades.
4. Facilitar la planificación de comidas diarias para profesionales ocupados con una experiencia de usuario intuitiva.
5. Garantizar la frescura y calidad de la comida casera entregada dentro de tiempos de espera reducidos.
   
### 1.2.2.3. Lean UX Hypothesis Statements


### 1.2.2.4. Lean UX Canvas

| Sección                                                                                             | Contenido                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Business Problem**                                                                                | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Business Outcomes**                                                                               | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Users and Customers**                                                                             | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **User Benefits**                                                                                   | N                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Solution Ideas**                                                                                  | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Hypotheses**                                                                                      | N. |
| **What's the most important <br> thing we need to learn first?**                                    | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **What's the least amount of <br> work we need to do to learn <br> the next most important thing?** | N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

### 1.3. Segmentos objetivo



## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

En esta sección, se presenta un análisis de los principales competidores de nuestra startup, centrado en aquellos que operan con modelos de negocio digitales similares o que, aunque no sean idénticos, ofrecen productos o servicios que se superponen parcialmente con los de Sabores Cercanos. Evaluamos tanto competidores directos, que se encuentran en el mismo segmento de mercado, como competidores indirectos, que abordan áreas relacionadas como la comida casera, recetas y servicios de entrega de alimentos. 

Este análisis nos permitirá comprender mejor el entorno competitivo y cómo podemos diferenciar nuestra oferta para destacar en el mercado.

Los competidores relevantes para nuestra startup son:

- **Cookpad (recetas de cocina, Global)**

Cookpad es una plataforma en línea dedicada a compartir recetas de cocina. Fundada en Japón en 1999, Cookpad se ha convertido en una de las comunidades de recetas más grandes del mundo, con usuarios de muchos países contribuyendo y compartiendo ideas culinarias.

En Cookpad, los usuarios pueden buscar recetas basadas en ingredientes, tipo de plato, o tiempo de preparación. La plataforma permite a los usuarios publicar sus propias recetas, así como seguir y comentar en las recetas de otros. Además, ofrece aplicaciones móviles para facilitar el acceso a recetas en cualquier momento.

 <p align="center"><img height="150px" src="assets/svg/Cookpad_logo.svg"> </p> 

- **Uber Eats (compra/venta de comida, Global)**

Uber Eats es una plataforma de entrega de alimentos a domicilio lanzada por Uber en 2014. Se ha convertido en una de las aplicaciones de entrega de comida más grandes y conocidas a nivel mundial.

Características destacadas:

- Cobertura Global: Opera en numerosas ciudades y países alrededor del mundo, ofreciendo una gran variedad de opciones de comida.

- Sistema de Calificación: Incluye calificaciones y reseñas para restaurantes y repartidores.

- Optimización de Rutas: Utiliza tecnología avanzada para optimizar las rutas de entrega.

- Innovaciones: Incluye características como entregas con drones y cocina en la nube.

<p align="center"><img height="80px" src="assets/svg/Uber-eats_logo.svg"> </p> 

- **HomeCooked (compra/venta de comida casera, Estados Unidos)**

HomeCooked es una plataforma que conecta a cocineros caseros con personas que buscan comidas preparadas en sus comunidades locales. Permite a los cocineros ofrecer sus comidas a través de la plataforma, donde los clientes pueden buscar opciones cercanas, ordenar y recoger las comidas directamente de las casas de los cocineros o recibirlas a domicilio.

Características principales:

- Marketplace de Comida Casera: Los cocineros pueden listar sus comidas, precios y horarios de disponibilidad.

- Flexibilidad: Los cocineros tienen la libertad de decidir qué platos ofrecer y cuándo.

- Diversidad Culinaria: Ofrece una variedad de opciones culinarias.

- Recogida o Entrega: Los consumidores pueden recoger las comidas en la casa del cocinero o recibirlas a domicilio.

<p align="center"><img height="150px" src="assets/svg/Homecooked_logo.svg"> </p>

- **DishDivvy (compra/venta comida casera, Estados Unidos)**

DishDivvy es una plataforma que conecta a cocineros caseros con personas que buscan comidas caseras frescas y auténticas en sus comunidades locales. Permite a los cocineros ofrecer sus platos a vecinos y clientes cercanos.

Características principales:

- Marketplace de Comida Casera: Los cocineros pueden crear perfiles, listar platos, fijar precios y horarios de disponibilidad.

- Entrega y Recogida: Los usuarios pueden optar por recoger la comida en la casa del cocinero o recibirla a domicilio.

- Diversidad Culinaria: Ofrece una amplia gama de platos que reflejan la diversidad cultural de las comunidades locales.

<p align="center"><img height="150px" src="assets/svg/Dishdivvy_logo.svg"> </p>

- **Nestlecocina (recetas de cocina, España)**

Nestlé Cocina es una plataforma digital creada por Nestlé que ofrece una amplia gama de recetas, desde platos principales y postres hasta opciones saludables y rápidas.

Características principales:

- Recetas Variadas: Incluye recetas categorizadas según los productos Nestlé utilizados.

- Recetas por Producto: Facilita la búsqueda de recetas basadas en productos específicos de Nestlé.

<p align="center"><img height="150px" src="assets/svg/Nestle-cocina_logo.svg"> </p>

- **Tasty (recetas de cocina y videos de cocina, Global)**

Tasty, lanzada por BuzzFeed en 2015, es conocida por sus videos cortos y visuales que muestran cómo preparar recetas de manera clara y atractiva. Está disponible a nivel mundial y se ha expandido a aplicaciones móviles y un sitio web.

Características principales:

- Recetas por Tipo y Ingredientes: Permite buscar recetas por tipo de plato, ingredientes, o nivel de dificultad.

- Secciones Temáticas: Incluye recomendaciones de recetas basadas en tendencias actuales o eventos especiales.

<p align="center"><img height="180px" src="assets/svg/Tasty_logo.svg"> </p>

### 2.1.1. Análisis competitivo

Para hacer el análisis competitivo, decidimos centrarnos en el modelo de negocio de:

- HomeCooked: Enfocado en comida casera y local. Ofrece una comparación directa en cuanto a cómo se gestionan los servicios de comida casera y las interacciones con la comunidad.

- DishDivvy: Se centra en la venta de comida casera en comunidades locales. Compararnos con esta plataforma nos dará ideas sobre la gestión y promoción de comida casera, así como sobre la logística de la plataforma.

- Cookpad: Aunque se enfoca en recetas, la comunidad activa y las funcionalidades para compartir recetas pueden inspirarnos en cómo fomentar una comunidad culinaria activa y mejorar la interacción entre usuarios y cocineros en nuestra plataforma.

Estas comparaciones nos permitirán entender mejor cómo otras plataformas manejan sus modelos de negocio, incluyendo la conexión con la comunidad, la gestión de comida casera y la funcionalidad de recetas, lo que nos ayudará a presentar una startup excelente.

| Nombre de <br>los Startups <br> o Empresas |                                                               | Nuestra startup | Competidor 1                                                                                                                                                                                                                                                                                                     | Competidor 2                                                                                                                                                                                       | Competidor 3                                                                                                                                                                                                      |
| ------------------------------------------ | ------------------------------------------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Perfil                                     | Overview                                                      | Sabores Cercanos   | HomeCooked                                                                                                                                                                                                                                                                                                            | DishDivvy                                                                                                                                                                                             | Cookpad                                                                                                                                                                                                           |
|                                            | Ventaja competitiva:<br>¿Qué valor ofrece<br> a los clientes? | Ofrecemos comidas caseras auténticas preparadas por cocineros locales que entienden las preferencias de la comunidad. Facilitamos el acceso a opciones personalizadas y promovemos una conexión directa entre cocineros y consumidores, enriqueciendo la experiencia culinaria con interacción comunitaria y diversidad cultural.             | Se centra en conectar cocineros caseros con consumidores locales, ofreciendo una experiencia culinaria más personalizada y auténtica. Esto permite a los cocineros adaptar sus ofertas a las preferencias locales y a los consumidores acceder a comidas caseras que no están disponibles en restaurantes tradicionales.      | Destaca por su amplia gama de platos que reflejan la diversidad cultural de las comunidades locales. La plataforma permite a los usuarios explorar y disfrutar de comidas caseras de diferentes cocinas del mundo, ofreciendo una alternativa única a la comida de restaurantes.         | Se beneficia de su gran comunidad de usuarios que contribuyen y comparten recetas. La plataforma fomenta la interacción entre los entusiastas de la cocina, permitiendo el intercambio de recetas, consejos y adaptaciones, lo que enriquece la experiencia del usuario. |
| Perfil de Marketing                        | Mercado Objetivo                                              | Nos dirigimos a cocineros caseros que desean monetizar sus habilidades y a universitarios y profesionales ocupados que buscan comidas caseras convenientes y nutritivas.            | Personas que buscan comida casera y auténtica en sus comunidades locales, así como cocineros caseros que desean monetizar sus habilidades culinarias. Principalmente enfocado en consumidores y cocineros en Estados Unidos.                                                                                                                                   | Consumidores que desean comidas caseras frescas y variadas, y cocineros caseros interesados en ofrecer sus platos a vecinos y clientes locales. Enfocado en comunidades locales en Estados Unidos.                       | Entusiastas de la cocina y personas que buscan recetas, consejos culinarios y una comunidad activa de cocina. La plataforma tiene un alcance global y atrae a usuarios interesados en compartir y descubrir recetas de todo el mundo. |
|                                            | Estrategias de Marketing                                      | Utilizamos influencers locales, campañas en redes sociales y eventos comunitarios para promover la plataforma y destacar nuestra oferta de comidas auténticas y personalizadas.            | Marketing Localizado: Enfoque en comunidades específicas. <br> Redes Sociales: Campañas para destacar la comida casera. | Marketing de Comunidad: Recomendaciones de usuarios y publicidad local. <br> Eventos Locales: Participación en ferias y eventos. | SEO y Contenido: Optimización para búsquedas de recetas. <br> Redes Sociales: Contenido visual y colaboración con influencers.       |
| Perfil del producto                        | Productos y servicios                                         | Ofrecemos un marketplace para la venta de comida casera y una funcionalidad para compartir recetas, con opciones de recogida o entrega.            | Comida Casera: Marketplace para vender comidas preparadas. <br> Recogida o Entrega: Opciones para recoger o recibir a domicilio. <br> Perfiles de Cocineros: Listado de menús, precios y disponibilidad.                | Comida Casera: Plataforma para ofrecer y vender platos locales. <br> Recogida o Entrega: Opciones para recoger o entrega a domicilio. <br> Perfiles de Cocineros: Menús, precios y horarios.        | Recetas de Cocina: Plataforma para buscar y compartir recetas. <br> Comunidad Culinaria: Comentarios y adaptaciones de recetas. <br> Aplicaciones Móviles: Acceso a recetas desde apps.            |
|                                            | Precios y Costos                                              | Los precios son fijados por los cocineros y los costos incluyen comisiones y tarifas por servicios premium, diseñados para ser accesibles y claros.            | Precios: Varían según el cocinero. <br> Costos: Comisión sobre ventas o tarifas de servicio.                                                                                                                                         | Precios: Establecidos por los cocineros. <br> Costos: Comisiones o tarifas de servicio.                                                                                     | Precios: Gratuito; funciones avanzadas pueden tener costo. <br> Costos: Financiado por anuncios y suscripciones premium.                                                                                                                                 |
|                                            | Canales de distribución <br>(Web y/o Móvil)                   | Contamos con una plataforma web y una app móvil para facilitar el acceso, navegación y pedidos desde cualquier dispositivo.            | Se distribuye principalmente a través de su sitio web oficial.                                                                                           | Se distribuía a través de su sitio web                                                      | Se distribuye principalmente a través de su sitio web oficial. <br> También cuenta con aplicación móvil.                                                                     |
| Análisis SWOT                              | Fortalezas                                                    | Nuestra conexión local y la diversidad de opciones culinarias nos permiten ofrecer comidas auténticas adaptadas a las necesidades de la comunidad.            | Comida Casera Auténtica: Ofrece comidas auténticas preparadas en casa. <br> Flexibilidad: Cocineros pueden ajustar menús y precios según sus preferencias.                                                                                                                                                                                                            | Diversidad Culinaria: Amplia variedad de platos de diferentes culturas. <br> Conexión Local: Fomenta la interacción dentro de la comunidad local.                                                                                                          | Comunidad Activa: Gran base de usuarios que comparte y comenta recetas. <br> Amplia Base de Recetas: Extensa colección de recetas de todo el mundo.                                                                                                                          |
|                                            | Debilidades                                                   | Enfrentamos desafíos de cobertura limitada y retención de usuarios frente a competidores más establecidos.            | Cobertura Limitada: Operaciones concentradas en ciertas áreas geográficas. <br> Control de Calidad: Variedad en la calidad y seguridad de las comidas.                                                                                                                                                                                                                                                       | Competencia Local: Competencia con otras opciones de comida casera y restaurantes. <br> Escalabilidad: Dificultad para expandir rápidamente a nuevas áreas.                                                                                                                | Dependencia de Usuarios: Calidad del contenido depende de las contribuciones de los usuarios. <br> Publicidad y Suscripciones: Anuncios y costos premium pueden afectar la experiencia del usuario.                                                                                                                         |
|                                            | Oportunidades                                                 | Podemos expandirnos a nuevos mercados y desarrollar nuevas funcionalidades, como suscripciones y recomendaciones personalizadas.            | Expansión en mercados emergentes,<br> desarrollo de nuevas <br> funcionalidades de IA.                                                                                                                                                                                                                           | Expansión de integraciones <br>y nuevas áreas locales y regionales.                                                                                                                  | Expansión en mercados globales, <br>mejoras continuas en <br>automatización y AI.                                                                                                                                 |
|                                            | Amenazas                                                      | La competencia intensa y posibles cambios regulatorios representan desafíos que necesitamos monitorear y adaptar nuestras estrategias.            | Presión de plataformas de entrega de comida más grandes y consolidadas.                                                                                                                                                                                                                                      | Desafíos para mantener una base de usuarios activa y una red de cocineros confiables.                                                                                                           | Competencia con otras plataformas de recetas y comunidades culinarias.                                                                                                                    |

### 2.1.2. Estrategias y tácticas frente a competidores

Nuestra estrategia se apoya en destacar la autenticidad y personalización de las comidas caseras que ofrecemos, aprovechando la rica y diversa tradición gastronómica de Perú, un país donde la comida es central en la vida social y cultural. A diferencia de plataformas más grandes que se enfocan en la eficiencia y rapidez, nos centramos en proporcionar una experiencia culinaria enriquecida que facilita una conexión directa entre cocineros locales y consumidores. En un entorno donde las personas son sociables y disfrutan compartir momentos alrededor de la comida, fomentamos una comunidad activa y diversa, adaptando nuestra oferta a las preferencias específicas de nuestros usuarios. Además, nuestra funcionalidad para compartir recetas nos diferencia de competidores centrados solo en la venta, posicionándonos como una opción más cercana y auténtica, ideal para quienes buscan una experiencia culinaria significativa y personalizada.

### 2.2. Entrevistas

En esta sección del informe se realizará el diseño, registro y análisis de las entrevistas de nuestros segmentos objetivos

### 2.2.1. Diseño de entrevistas

Antes de poder realizar las entrevistas, consideramos prudente poder concretar un análisis previo para poder realizar las entrevistas de una mejor manera. Es por ello, que para cada uno de nuestros segmentos proponemos estas preguntas para poder conocer un poco más sobre nuestro público objetivo.

### Preguntas para Entrevistar a Estudiantes/Profesionales Ocupados

**Preguntas principales:**

1. ¿Podrías presentarte y contarme un poco sobre tu rutina diaria y tus responsabilidades?
2. ¿Cómo manejas tus comidas diarias durante la semana laboral/estudiantil?
3. ¿Cuánto tiempo dedicas, en promedio, a cocinar tus propias comidas durante la semana?
4. ¿Qué haces cuando no tienes tiempo para cocinar? ¿Qué tipo de comida tiendes a elegir?
5. ¿Puedes contarme una experiencia reciente en la que te resultó difícil encontrar una comida saludable y conveniente?
6. ¿Qué importancia le das a la calidad nutricional de las comidas que consumes diariamente?
7. ¿Alguna vez te has sentido frustrado/a por no poder encontrar opciones de comida saludable y casera cerca de ti?
8. ¿Qué opinas de la idea de poder pedir comida casera a través de una plataforma que conecta a cocineros locales con consumidores?
9. ¿Te gustaría tener más opciones de comida casera accesible en tu área? ¿Por qué?
10. ¿Cómo te sentirías si pudieras personalizar un menú casero según tus preferencias alimenticias a través de una aplicación?
11. ¿Podrías compartir una situación en la que te hubiera gustado tener acceso a una opción de comida casera rápida y no lo encontraste?

**Preguntas Complementarias:**

12. ¿Qué tan a menudo comes fuera de casa? ¿Prefieres hacerlo por comodidad o por falta de tiempo?
13. ¿Qué importancia le das a saber quién prepara la comida que consumes?
14. ¿Qué opinas sobre la posibilidad de apoyar a cocineros locales al pedir comida casera?
15. ¿Cómo te sentirías si pudieras planificar tus comidas semanales con antelación a través de una plataforma?
16. ¿Alguna vez has utilizado servicios de comida a domicilio? ¿Cómo ha sido tu experiencia con ellos en cuanto a calidad y conveniencia?

### Preguntas para Entrevistar a Cocineros Caseros

**Preguntas principales:**

1. ¿Podrías presentarte y contarnos sobre tu experiencia en la cocina y tu interés en cocinar para otros?
2. ¿Qué tan a menudo cocinas para ti y/o para otras personas?
3. ¿Has considerado alguna vez monetizar tus habilidades culinarias? ¿Por qué?
4. ¿Qué barreras has encontrado al intentar vender comida casera o al considerar iniciar un negocio relacionado con la cocina?
5. ¿Puedes contarme una experiencia en la que te hubiera gustado poder vender tus comidas pero no tuviste los medios para hacerlo?
6. ¿Qué piensas sobre la posibilidad de ofrecer tus comidas caseras a través de una plataforma en línea?
7. ¿Cómo te sentirías si pudieras ganar dinero cocinando desde casa, sin necesidad de invertir en un restaurante o negocio formal?
8. ¿Qué tan importante sería para ti poder gestionar tu tiempo y pedidos de manera flexible a través de una aplicación?
9. ¿Crees que existe una demanda real de comida casera en tu comunidad? ¿Por qué?
10. ¿Alguna vez has recibido comentarios positivos de amigos o familiares sobre tu cocina? ¿Cómo te hizo sentir eso?
11. ¿Qué tan interesado/a estarías en unirte a una comunidad de cocineros caseros donde pudieras compartir recetas y aprender de otros?

**Preguntas Complementarias:**

12. ¿Qué tipo de platos disfrutas más cocinar? ¿Por qué?
13. ¿Has vendido alguna vez comida casera de manera informal? Si es así, ¿cómo fue esa experiencia?
14. ¿Qué opinas sobre la posibilidad de que tus clientes puedan personalizar los platos que ofreces?
15. ¿Cómo te sentirías si pudieras recibir retroalimentación directa de tus clientes a través de una aplicación?
16. ¿Qué valoras más en una plataforma que te permita vender tus comidas caseras: flexibilidad, facilidad de uso, o seguridad?

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

Tras la identificación de los segmentos objetivo (cocineros caseros y estudiantes/profesionales ocupados), se realizaron entrevistas a individuos pertenecientes a dichos segmentos con el objetivo de de hallar información relevante para el desarrollo del producto final, tal como sentimientos, deseos y necesidades. En esta sección se incluirán los esquemas de _User Personas_, _User Task Matrix_, _User Journey Mapping_ y _Empathy Mapping_.

### 2.3.1. User Personas

**User Persona del Segmento Objetivo 1: Cocineros Caseros**
---
| Attributes | <p align="center">Values</p> |
|--|--|
| Name | María Gonzales |
| Age | 42 Años |
| Occupation | Ama de casa |
| Status | Casada |
| Location | Lima, Perú |
| Tier | Madre de Familia |
| Archetype | Cocinera |
| Image | <br><p align="center"><img height="100px" src="assets/images/user-persona-1.jpg"></p> |
| Quote | _"Cada comida que preparo es una manera de compartir mi corazón con los demás."_ |
| Motivations | <p><ul><li>Incentive: **70 de 100**<li>Fear: **60 de 100**<li>Achievement: **60 de 100**<li>Growth: **50 de 100**<li>Power: **60 de 100**<li>Social: **80 de 100** |
| Goals | <p><ul><li>Generar ingresos adicionales para su familia.</li><li>Ser flexible en su trabajo, para poder gestionar mejor sus responsabilidades familiares.</li><li>Compartir su pasión por la cocina con una comunidad.</li></ul></p> |
| Frustrations | <p><ul><li>No muy hábil con la tecnología.<li>Competencia local.<li>No tiene suficiente espacio como para preparar grandes cantidades de comida todos los días. |
| Biography | <br><p>Desde que era pequeña, María siempre tuvo pasión por la cocina. Pasó su juventud ayudando y aprendiendo a cocinar en restaurantes locales, con lo que mejoró sus habilidades. Hoy en día es madre de dos niños pequeños, para los que prepara comida a diario. Ella busca una manera de sacarle provecho a sus habilidades culinarias de una manera que le permita ganar dinero y aportar a la economía familiar sin comprometer la cantidad de tiempo que puede pasar en casa para cuidar a sus hijos. |
| Personality | <p><ul><li>Extrovert: **80 de 100**<li>Thinking: **80 de 100**<li>Judging: **50 de 100** |
| Technology | <p><ul><li>IT and Internet: **50 de 100**<li>Software: **50 de 100**<li>Mobile Apps: **60 de 100**<li>Social Networks: **60 de 100** |
| Brands | <p><ul><li>Facebook<li>Youtube |

**User Persona del Segmento Objetivo 2: Estudiantes/Profesionales Ocupados**
---
| Attributes | <p align="center">Values</p> |
|--|--|
| Name | Ricardo Martinez |
| Age | 21 Años |
| Occupation | Estudiante Universitario |
| Status | Soltero |
| Location | Lima, Perú |
| Tier | Estudiante Pregrado |
| Archetype | Estudiante |
| Image | <br><p align="center"><img height="100px" src="assets/images/user-persona-2.jpg"></p> |
| Quote | _"El tiempo lo es todo, pero la salud también, por eso es importante encontrar un balance."_ |
| Motivations | <p><ul><li>Incentive: **90 de 100**<li>Fear: **60 de 100**<li>Achievement: **80 de 100**<li>Growth: **80 de 100**<li>Power: **60 de 100**<li>Social: **50 de 100** |
| Goals | <p><ul><li>Ahorrar tiempo.</li><li>Estar saludable.</li><li>Disfrutar de buena comida.</li></ul></p> |
| Frustrations | <p><ul><li>Poco tiempo libre para cocinar.<li>Falta de presupuesto.<li>No posee muchas opciones para obtener comida saludable. |
| Biography | <br><p>Ricardo es un estudiante de ingeniería de software(porque todos sabemos que en esta carrera nos sobreexplotan) que busca rendir lo mejor posible con tal de alcanzar sus metas de carrera. Sin embargo, la cantidad de clases, tareas y trabajos le hacen imposible conseguir un balance entre lo académico y su salud. Por ello, busca maneras de tener acceso a una dieta balanceada que a su vez sea asequible con los pocos ingresos con los que cuenta.  |
| Personality | <p><ul><li>Extrovert: **90 de 100**<li>Thinking: **80 de 100**<li>Judging: **60 de 100** |
| Technology | <p><ul><li>IT and Internet: **80 de 100**<li>Software: **80 de 100**<li>Mobile Apps: **90 de 100**<li>Social Networks: **60 de 100** |
| Brands | <p><ul><li>Uber Eats<li>Domicilios.com |

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

En Sabores Cercanos, utilizamos un lenguaje común para asegurar una comunicación clara y efectiva entre todos los miembros del equipo, cocineros, y usuarios. A continuación, se describen algunos de los términos clave:

### Términos generales

- Cocinero Casero: Persona que prepara comidas en su hogar para ofrecerlas a través de la plataforma. Este término abarca tanto a quienes cocinan de manera ocasional como a aquellos que lo hacen regularmente.

- Consumidor: Universitarios, profesionales y cualquier persona que busca acceder a comidas caseras a través de Sabores Cercanos.

- Ubicación: Lugar donde un cocinero casero prepara y/o entrega la comida, o donde el consumidor puede recoger su pedido.

- Perfil de Usuario: Información personal y preferencias de un consumidor o cocinero casero, utilizada para personalizar la experiencia en la plataforma.

- Plataforma de Pago: Mecanismos y proveedores utilizados para procesar pagos en la plataforma (e.g., tarjeta de crédito, billetera digital).

- Costo de Servicio: Comisiones o tarifas aplicadas a los cocineros caseros por usar la plataforma, o costos adicionales para los usuarios por servicios como la entrega a domicilio.

- Comunicación en Tiempo Real: Canal dentro de la plataforma para que cocineros y usuarios se comuniquen directamente sobre detalles del pedido.

### Perfiles de Usuario

Para el Consumidor:

- Menú: Conjunto de platos que un cocinero casero ofrece en la plataforma, incluyendo detalles como ingredientes, precios y disponibilidad.

- Filtro de Búsqueda: Herramienta que permite a los usuarios buscar platos y cocineros según criterios como precio, tipo de comida, horario de disponibilidad, etc.

- Recomendaciones Personalizadas: Sugerencias de platos y cocineros basadas en las preferencias y hábitos de compra de un usuario.

- Cesta de Compras: Sección donde un consumidor puede revisar y modificar los platos seleccionados antes de completar un pedido.

- Punto de Recogida: Lugar designado donde el consumidor puede ir a recoger su pedido.

- Entrega a Domicilio: Opción ofrecida por algunos cocineros caseros para llevar el pedido directamente al domicilio del consumidor.

- Reseña: Opinión y valoración que un consumidor deja sobre un cocinero casero o un plato después de haber realizado un pedido.

- Feedback: Retroalimentación que los usuarios proporcionan sobre su experiencia, utilizada para mejorar los servicios y la calidad en la plataforma.

- Notificación: Alerta enviada a los usuarios sobre nuevos menús, ofertas especiales, o actualizaciones de recetas en la plataforma.

- Programa de Lealtad: Sistema de recompensas para usuarios frecuentes, incentivando su permanencia en la plataforma.

Para el Cocinero Casero:

- Receta: Descripción detallada de los ingredientes y pasos para preparar un plato, compartida por cocineros en la plataforma.

- Oferta Especial: Promoción o descuento que un cocinero casero ofrece por tiempo limitado.

- Horario de Disponibilidad: Períodos en los que un cocinero casero está disponible para preparar y vender comidas a través de la plataforma.

- Capacidad de Producción: El número máximo de pedidos que un cocinero casero puede manejar en un período determinado.

- Certificación de Cocinero: Programas o insignias que certifican la calidad o especialización de un cocinero en la plataforma.

- Gestión de Reseñas: Sistema que permite a los cocineros y a la plataforma manejar y responder a las reseñas de los usuarios.

- Receta Estrella: Recetas destacadas que han recibido las mejores valoraciones de la comunidad y que son promovidas en la plataforma.

### Proceso de Pedido y Entrega

- Pedido: Transacción realizada por un consumidor para adquirir uno o más platos del menú de un cocinero casero.

- Cesta de Compras: Sección donde un consumidor puede revisar y modificar los platos seleccionados antes de completar un pedido.

- Tiempo de Preparación: Duración estimada que le toma a un cocinero casero preparar un plato después de que se realiza el pedido.

- Tiempo de Llegada: Tiempo estimado que tarda un pedido en llegar a su destino desde el momento en que se completa la preparación.

### Gestión y Administración

Para Administradores:

- Política de Devoluciones: Reglas y procedimientos para manejar devoluciones o reembolsos en caso de problemas con un pedido.

- Costo de Servicio: Comisiones o tarifas aplicadas a los cocineros caseros por usar la plataforma, o costos adicionales para los usuarios por servicios como la entrega a domicilio.

- Certificación de Cocinero: Programas o insignias que certifican la calidad o especialización de un cocinero en la plataforma. (Puede ser gestionado por administradores para asegurar estándares de calidad).

Para Cocineros Caseros:

- Gestión de Reseñas: Sistema que permite a los cocineros y a la plataforma manejar y responder a las reseñas de los usuarios.

- Receta Estrella: Recetas destacadas que han recibido las mejores valoraciones de la comunidad y que son promovidas en la plataforma.

- Oferta Especial: Promoción o descuento que un cocinero casero ofrece por tiempo limitado.

- Capacidad de Producción: El número máximo de pedidos que un cocinero casero puede manejar en un período determinado.

- Horario de Disponibilidad: Períodos en los que un cocinero casero está disponible para preparar y vender comidas a través de la plataforma.

### Datos y Análisis

- Tendencia de Consumo: Datos y patrones sobre las preferencias de comida de los usuarios, utilizados para mejorar la oferta de platos y servicios.

### Disponibilidad y Programación

- Horario de Disponibilidad: Períodos en los que un cocinero casero está disponible para preparar y vender comidas a través de la plataforma.

- Comunicación en Tiempo Real: Canal dentro de la plataforma para que cocineros y usuarios se comuniquen directamente sobre detalles del pedido.

Estos son los términos identificados hasta el avance de esta primera entrega del proyecto, fechada el 29 de agosto de 2024. Se actualizarán y ampliarán conforme avancemos en las siguientes etapas del desarrollo.

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

### 3.2. User Stories

### 3.3. Impact Mapping

### 3.4. Product Backlog

## Capítulo IV: Product Design

### 4.1. Style Guidelines. 

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

### 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

### 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.2. Web Applications Mock-ups

### 4.4.3. Web Applications User Flow Diagrams

### 4.5. Web Applications Prototyping

### 4.6. Domain-Driven Software Architecture

En esta sección, presentamos la arquitectura de software para nuestro proyecto Sabores Cercanos. Hemos diseñado esta arquitectura con un enfoque centrado en el dominio, asegurando que los aspectos más críticos de nuestra plataforma estén bien representados y alineados con las necesidades de nuestros usuarios y cocineros. A continuación, mostramos diagramas clave que describen cómo los diferentes componentes de nuestro sistema interactúan entre sí y con actores externos:

### 4.6.1. Software Architecture Context Diagram

Este diagrama muestra las interacciones principales entre el sistema y los actores externos, como los consumidores, los cocineros, y el administrador de la plataforma. Además, se incluyen las conexiones con sistemas externos como el Payment Gateway y el Email Service, proporcionando una vista general de cómo el sistema se integra y se comunica con el entorno externo.

<p align="center">
  <img src="assets/images/structurizr-SystemContext_Diagram.png">
</p>

### 4.6.2. Software Architecture Container Diagrams

Aquí se detalla los principales contenedores de software dentro del sistema, como la Web Application, la Mobile App, la Single-Page Application, la API, y la Database. Cada contenedor representa una parte clave de la arquitectura del sistema y se muestra cómo interactúan entre sí, manejando funciones como la gestión de usuarios, el procesamiento de pagos, y la comunicación con los servicios externos.

<p align="center">
  <img src="assets/images/structurizr-Containers_Diagram.png">
</p>

### 4.6.3. Software Architecture Components Diagrams

Este diagrama desglosa los componentes internos clave, como el Order Controller, el User Controller, el Payment Service, y el Notification Manager. El diagrama muestra las relaciones y dependencias entre estos componentes, ilustrando cómo trabajan juntos para proporcionar la funcionalidad central de la plataforma.

<p align="center">
  <img src="assets/images/structurizr-Component_Diagram.png">
</p>

### 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

### 4.7.2. Class Dictionary

### 4.8. Database Design

### 4.8.1. Database Diagram

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

### 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

### 5.2.1.2. Sprint Backlog 1

### 5.2.1.3. Development Evidence for Sprint Review

### 5.2.1.4. Testing Suite Evidence for Sprint Review

### 5.2.1.5. Execution Evidence for Sprint Review

### 5.2.1.6. Services Documentation Evidence for Sprint Review

### 5.2.1.7. Software Deployment Evidence for Sprint Review

### 5.2.1.8. Team Collaboration Insights during Sprint
