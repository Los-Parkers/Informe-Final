# <p align="center">Informe de Trabajo Final</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./assets/upc-logo.png" alt="Logo de UPC" />
</div>

<p align="center">Ingeniería de Software</p>
<p align="center">Aplicaciones Web - SW55</p>
<p align="center"><strong>Docente:</strong> Francisco José Cáceres Honores</p>
<p align="center"><strong>Startup:</strong> Parkers</p>
<p align="center"><strong>Producto:</strong> EzPark</p>

<p align="center"><strong>Team members:</strong></p>

| Nombre                            | Código     |
| --------------------------------- | ---------- |
| Oliveira Paucar, Mauricio         | U201719831 |
| Garro Vega, Marcelo Fabian        | U20201C410 |
| Méndez Vargas, Sebastian Orlando  | U20201F140 |
| Gonzales Arotinco, Bruno Leonardo | U201820037 |

<p align="center"><strong>Ciclo 2024-01</strong></p>

# Registro de versiones del informe

| Versión | Fecha      | Autor             | Descripción de modificación                                                                                                                                                                                                                                                                 |
| ------- | ---------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Row 1   | 03/04/2024 | Equipo de Parkers | En esta primera entrega se han incluido los capítulos:<br />Capítulo I: Introducción <br />Capítulo II: Requirements Elicitation & Analysis<br />Capítulo III: Requirements Specification<br />Capítulo IV: Product Design<br />Capítulo V: Product Implementation, Validation & Deployment |

# Student Outcomes

ABET – EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.

# Capítulo 1

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

EzPark surge como una solución ante la creciente preocupación por la escasez de espacios de estacionamiento en entornos urbanos. La agobiante congestión del tráfico y la ineficiente búsqueda de lugares para estacionar generan frustración y retrasos en la experiencia de los conductores a nivel global. A su vez, aquellos que poseen espacios de estacionamiento no utilizados se enfrentan al desafío de encontrar una manera efectiva de aprovechar estos activos.

EzPark se propone revolucionar la forma en que las personas encuentran y utilizan espacios de estacionamiento. Crearemos una aplicación que ofrecerá una interfaz intuitiva que les permitirá buscar, reservar y pagar por estacionamientos de manera rápida y fluida. Los usuarios podrán ubicar fácilmente espacios disponibles cerca de su destino, ahorrando tiempo y evitando la frustración de la búsqueda ineficiente. Por otro lado, los propietarios de espacios de estacionamiento podrán registrarse en la plataforma y ofrecer sus espacios disponibles para alquiler. La aplicación permitirá a los propietarios gestionar sus listados, establecer precios, disponibilidad y recibir pagos de manera segura. Esto les brindará una forma eficaz de aprovechar sus activos, generando ingresos adicionales mientras contribuyen a aliviar la congestión del tráfico.

### 1.1.2. Perfiles de integrantes del equipo

|                               | Oliveira Paucar, Mauricio                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="" alt="Mauricio" /> | <strong>Ingeniería de Software - U201719831</strong><br />Tengo 23 años, me gusta mucho aprender cosas nuevas sobre mi carrera, trabajar en equipo de manera proactiva y lograr los objetivos junto a mis compañeros. Me considero una persona ambiciosa, ya que mi meta es llegar a obtener un alto cargo en una empresa que me agrade o formar mi propia empresa relacionada al software. Gracias a ello siempre podré trabajar en algo que me guste. |

|                               | Garro Vega, Marcelo Fabian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="" alt="Mauricio" /> | <strong>Ingeniería de Software - U20201C410</strong><br />Soy un estudiante universitario de 21 años apasionado por el mundo de la tecnología y su capacidad para resolver problemas cotidianos. Me considero una persona organizada, responsable y optimista que busca la mejor manera solucionar los problemas. <br/> Me especializo en el ámbito del desarrollo frontend, priorizando siempre la experiencia del usuario. <br/>Me comprometo a ser un gran aporte al equipo, apoyando a mis compañeros y compartir mis conocimientos de desarrollo. |

|                               | Méndez Vargas, Sebastian Orlando                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="" alt="Mauricio" /> | <strong>Ingeniería de Software - U20201F140</strong><br />Tengo 21 años y disfruto de temas relacionados a la tecnología moderna (IA, machine learning, etc). Aprendo mucho al trabajar en equipos y soy creativo a la hora de proponer ideas y soluciones tecnológicas. Me considero como una persona sociable y que le gusta compartir ideas con sus compañeros, todo sea por dar lo mejor de nosotros en cada trabajo. |

|                               | Gonzales Arotinco, Bruno Leonardo                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="" alt="Mauricio" /> | <strong>Ingeniería de Software - U201820037</strong><br />Mi edad es 24 años y disfruto adquiriendo nuevos conocimientos sobre mi carrera. Me destaco por colaborar de forma activa en equipos y alcanzar metas junto a ellos. Soy una persona divertida, ya que intento buscarle lo divertido a la vida y a nivel profesional busco establecer mi propio negocio en el ámbito del software. Esta ambición me motiva a trabajar en un área que me apasione de manera constante. |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

**Antecedentes**
En la actualidad, las áreas urbanas experimentan un aumento constante en la congestión del tráfico debido al crecimiento de la población y al incremento del uso de vehículos motorizados.

Este problema de tráfico, agravado por la ineficiente búsqueda de espacios de estacionamiento, ha generado una experiencia frustrante para los conductores en todo el mundo. Además, esta situación también representa un desafío para quienes poseen espacios de estacionamiento no utilizados en áreas urbanas, ya que no cuentan con una plataforma efectiva para aprovechar estos activos.

**Problemática**

What?

La problemática percibida por nuestra startup es la escasez de espacios de estacionamiento en los entornos urbanos y la complejidad actual en la búsqueda de lugares para estacionar. Esto es debido a la alta demanda de vehículos motorizados para las actividades cotidianas.

When?

Esta preocupación ha estado aumentando a lo largo del tiempo, a medida que las ciudades han experimentado un crecimiento de la población y, por lo tanto, la cantidad de vehículos en circulación, la congestión de tráfico y la búsqueda ineficiente de estacionamiento se ha vuelto más apremiante en los últimos años.

Where?

El problema surge principalmente en áreas urbanas densamente pobladas de todo el mundo, donde el espacio es limitado y la demanda de vehículos es alta.

Who?

Los afectados por este problema son los conductores que enfrentan las dificultades para encontrar lugares de estacionamiento convenientes. Además, muchos propietarios de espacios de estacionamiento tienden a enfrentarse a empresas grandes dedicadas a este rubro, dificultando la promoción de sus servicios.

Why?

Esto ocurre debido a la insuficiencia de lugares de estacionamiento disponibles en áreas urbanas, lo que lleva a una congestión de tráfico más intensa y a la dificultad para los conductores de encontrar estacionamientos de manera oportuna.

How?

El problema sucede cuando la congestión del tráfico y la falta de espacios de estacionamiento disponibles conlleva a que la población tenga dificultades de encontrar estacionamientos de manera conveniente y eficiente.

How much?

El problema de la escasez de espacios de estacionamiento afecta de manera significativa a Lima, la capital, donde de acuerdo con un estudio realizado por la ONG Luz Ámbar en 2016 se ha demostrado que hay una insuficiencia de alrededor de 45,000 estacionamientos vehiculares en cinco distritos. Sin embargo, esta cifra resulta insuficiente en comparación con el tamaño del parque automotor de la ciudad, que consta de aproximadamente 1 millón 800,000 unidades. Esta disparidad entre la cantidad de vehículos y la disponibilidad de estacionamientos contribuye a la congestión del tráfico y al desafío constante para los conductores de encontrar lugares para estacionar de manera eficiente.

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

**Problem Statement 1: Usuario de parking**

En la actualidad, el uso de vehículos motorizados ha sido un gran avance para la movilidad de los ciudadanos en las zonas urbanas del Perú. Debido a la alta demanda, muchos establecimientos dedicados al servicio de estacionamientos experimentaron escasez de espacios disponibles.

Hemos encontrado en los conductores dificultades para encontrar espacios disponibles para estacionar, lo que genera una gran pérdida de tiempo y una experiencia frustrante. En la mayoría de los casos, terminan dejando sus vehículos en las vías públicas expuestos a cualquier riesgo.

¿Cómo podemos facilitar a los usuarios una forma eficiente y rápida de encontrar espacios disponibles para estacionar sus vehículos motorizados?

**Problem Statement 2: Anfitriones**

Nuestra aplicación ofrece al usuario la posibilidad de promocionar sus garajes con el propósito de ponerlos en alquiler para el uso de los conductores del Perú. generando ingresos pasivos al propietario.

Hemos encontrado que los propietarios sienten inseguridad al permitir que las personas desconocidas tengan acceso a sus garajes, puesto que estos por lo general forman parte de las viviendas.

¿Cómo podemos brindar al propietario la seguridad de sus bienes inmobiliarios al promocionar sus servicios de estacionamiento en nuestra aplicación?

#### 1.2.2.2. Lean UX Assumptions.

**<ins>Business Assumptions</ins>**

1. **Creo que mis usuarios necesitan** una mejor manera de encontrar lugares de estacionamientos y, de ser posible, reservarlos.
2. **Estas necesidades se pueden resolver** con una aplicación que les permite a los conductores reservar en los garajes de la ciudad, debido a que la mayoría del tiempo se encuentran desocupados o libres.
3. **Mis clientes iniciales son** los ciudadanos que cuenten con algún vehículo motorizado con dificultades para encontrar estacionamiento y/o deseen poner en alquiler sus garajes.
4. **El valor #1 que el cliente requiere de mi servicio** es encontrar y reservar espacios para estacionar en un corto periodo de tiempo. Además, los usuarios desean saber si esta metodología es totalmente segura para ambos tipos de usuario.
5. **Voy a adquirir a mis clientes a través de** estrategias de Marketing en diversas redes sociales, resaltando las principales características y beneficios de la aplicación.
6. **Mi competencia en el mercado** serán las empresas que se dedican a ofrecer sus servicios de estacionamiento.
7. **Los venceremos debido a que** ofrecemos a los usuarios poder generar ingresos de manera pasiva al rentar sus garajes como estacionamiento.
8. **Mis mayores riesgos del producto es** no encontrar una manera de brindar seguridad a los conductores como a los propietarios de los garajes.
9. **Resolveremos esto con** la incorporación de un sistema que se encargue de validar los parámetros de seguridad de los conductores y los garajes en alquiler para ofrecer una mayor seguridad al público.

**Sabremos que hemos tenido éxito cuando veamos los siguientes cambios en el comportamiento de nuestros clientes:**

- Reducción significativa en los tiempos de búsqueda de espacios disponibles para estacionar.
- Ingresos económicos en los propietarios con garajes registrados en la aplicación.

**¿Qué otras suposiciones tenemos que, de probarse falsas, pueden causar el fracaso del proyecto?**

- El permitir el acceso a cualquier usuario con propósitos malignos o perversos generará en todos los usuarios inseguridad. Por consiguiente, muchos de ellos dejarán la aplicación.

**<ins>User Assumptions</ins>**
**Clientes de parking**
¿Quién es el usuario?
Conductores que en su día a día necesitan encontrar estacionamiento para sus vehículos motorizados.

¿Dónde encaja nuestro servicio? ¿En su trabajo o en su vida?
Nuestro servicio encaja tanto para su trabajo como para sus actividades diarias. El usuario tiene la necesidad de encontrar un estacionamiento cercano a su puesto de trabajo. Asimismo, para otras actividades en algún punto específico de la ciudad desean tener su vehículo en un lugar cercano.

¿Qué problema tiene nuestro servicio y cómo se resuelve?
Problema será la posible inseguridad del usuario al alquilar en una cochera de cualquier persona desconocida.
Lo podemos resolver mediante un sistema de filtros que garanticen al usuario la seguridad de la cochera y contar con bases legales para la publicación del producto.

¿Cuándo y cómo es usado nuestro producto?
El producto es usado mayormente cuando el usuario necesita encontrar algún lugar de estacionamiento para cualquier actividad.
La aplicación se puede usar como un sistema de búsqueda y reserva de cocheras.

**Anfitriones de garajes**
¿Quién es el usuario?
Personas con garajes que desean poner en alquiler para generar ingresos pasivos.

¿Dónde encaja nuestro servicio? ¿En su trabajo o en su vida?
Nuestro servicio encaja en su vida porque pueden poner en alquiler sus garajes mientras realizan cualquier actividad.

¿Qué problema tiene nuestro servicio y cómo se resuelve?
El problema será el proceso para poder registrar sus cocheras, debido a que puede llegar a ser confuso o tedioso para el anfitrión.
Lo podemos resolver mediante capacitación sobre el proceso de filtros para facilitar al usuario el registro.

¿Cuándo y cómo es usado nuestro producto?
Nuestra aplicación es usada principalmente cuando el anfitrión dispone de cualquier garaje disponible que desee poner en alquiler para generar ingresos.
Nuestro producto es usado como un gestor de cocheras sobre reservas, estados, recibos, etc.

**<ins>Features</ins>**

¿Qué características son importantes?

- Hacer reservas de estacionamientos desde cualquier ubicación con conexión a internet, ya sea mediante un ordenador o un dispositivo móvil.
- Inscribir estacionamientos para alquilar y obtener ingresos adicionales según la tarifa establecida por el propietario.
- Verificar la disponibilidad de estacionamientos dentro de la zona o dirección especificada.

¿Cómo debe verse y comportarse nuestro producto?

- La interfaz de usuario contará con un diseño intuitivo, sencillo y atractivo, siguiendo las pautas de estilo específicas de nuestro sector.
- Se enfocará principalmente en la experiencia del usuario para garantizar una alta eficiencia en el funcionamiento de la aplicación.
- Estará disponible las 24 horas del día, los 7 días de la semana.
- Se respalda con una sólida arquitectura de software para abordar cualquier incidencia que pueda surgir.

#### 1.2.2.3. Lean UX Hypothesis Statements.

1. **Creemos que** la función de reservar cocheras facilitará al usuario conseguir un espacio para estacionamiento.
   **Sabremos que** tendremos éxito
   **Cuando** la mayoría de los usuarios demoren en conseguir estacionamiento en un plazo máximo de 5 minutos.

2. **Creemos que** la implementación del mapa de Google Maps permitirá al usuario una mejor búsqueda de cocheras.
   **Sabremos que** estaremos en lo cierto
   **Cuando** el 100% de nuestros usuarios no presentan dificultades para encontrar cocheras.

3. **Creemos que** proporcionar al usuario registrar sus cocheras aumentará la cantidad de estacionamientos
   **Sabremos que** estaremos en lo cierto
   **Cuando** el índice de escasez de estacionamientos se reduzca en un 20%.

#### 1.2.2.4. Lean UX Canvas.

### 1.3. Segmentos objetivos.

Nuestro segmento objetivo está compuesto por dos tipos de usuarios:

**Guest:** Individuo que busca soluciones convenientes y accesibles para sus necesidades de buscar estacionamiento en entornos urbanos para su vehículo.

**Host:** Propietario de una vivienda cuente con una cochera privada que busque sacar provecho de forma efectiva de estos mismos.

# Capítulo 2

## 2.1. Competidores

## 2.1.1. Análisis competitivo

## 2.1.2. Análisis competitivo

Entre las principales estrategias y tácticas que ejecutaremos como startup se encuentran:

- Nuestra estrategia se centra en aprovechar nuestra principal ventaja competitiva: precios altamente competitivos en comparación con otros servicios similares en el mercado. Nuestro objetivo es atraer la mayor cantidad de clientes posible mediante esta ventaja de precios. Una vez que hayamos consolidado una base sólida de clientes, planeamos realizar encuestas de satisfacción y, si es posible, llevar a cabo entrevistas con ellos.

- Nuestra estrategia implica buscar oportunidades para integrar nuestro software con otras herramientas ampliamente utilizadas y reconocidas en el sector empresarial, como Google Calendar, Zoom, Google Maps entre otras. Al hacerlo, nuestro objetivo es construir un ecosistema cohesivo que se adapte de manera fluida al contexto y las necesidades específicas de cada usuario. Esta integración permitirá a nuestros usuarios disfrutar de una experiencia web más completa y sin interrupciones al utilizar nuestra aplicación.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Segmento objetivo: Usuario de Parking y Anfitrión

1. ¿Cuál es su nombre?
1. ¿Que edad tiene?
1. ¿En qué distrito reside?
1. ¿A que se dedica?
1. ¿Actualmente cuenta con algún tipo de vehículo?
1. ¿Cuántas veces a la semana usa su auto?
1. ¿Tiene dificultad para encontrar estacionamiento?
1. ¿En qué distritos suele buscar con mayor frecuencia un estacionamiento?
1. ¿Cuáles cree que son las horas más difíciles para encontrar estacionamiento?
1. ¿Estaría dispuesto a utilizar una cochera diferente a la tradicional?
1. ¿Con qué frecuencia usaría este servicio?
1. ¿Cree que sería de utilidad una aplicación que le ayude a buscar de manera más eficiente estos tipos 1. de estacionamientos?
1. ¿Qué requisitos mínimos cree que deberían cumplir los estacionamientos para que se sienta seguro de 1. dejar su vehículo en dichos lugares?
1. ¿Cuenta usted con algún espacio de estacionamiento disponible en su hogar?
1. ¿Usted estaría dispuesto a alquilarlo? ¿Por qué?
1. ¿Cada cuánto tiempo alquilaría su cochera?
1. ¿Cree que sería de utilidad una aplicación que le ayude a alquilar y publicitar su espacio de una manera eficiente?

### 2.2.2. Registro de entrevistas.

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 1: Juan Carlos Bodoque Bolaños (26 años - San Miguel) - 4 de abril del 2023
URL del video: (enlace) (Comienzo 00:00:00 - Fin 00:21:10)
<img src="" alt="Entrevista de Juan Carlos" />

Resumen:
Después de entrevistar a Juan Carlos Bodoque Bolaños, un abogado de 26 años residente en el distrito de San Miguel, se han obtenido detalles significativos sobre sus necesidades y preferencias en relación con el estacionamiento. Juan Carlos mencionó tener dificultades para encontrar estacionamiento en su centro de labores en el distrito de San Isidro, así como en zonas turísticas como Miraflores. Destacó que los horarios laborales presentan mayores desafíos para encontrar estacionamiento. Expresó interés en utilizar una plataforma de alquiler de espacios de estacionamiento sí ofrece beneficios económicos y afirmó que la utilizaría diariamente durante los días laborales. En términos de seguridad, señaló la importancia de verificar la identidad de los ocupantes de los espacios y la presencia de agentes de seguridad.
Por otro lado, reveló que tiene dos espacios de estacionamiento disponibles en su hogar y estaría dispuesto a alquilar uno de ellos en todo momento, ya que rara vez lo utiliza. Sugirió que sería útil tener la función de alquiler de espacios de estacionamiento junto con la búsqueda de espacios disponibles en una misma plataforma para mayor eficiencia y para generar ganancias adicionales.

---

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 2: Liliana Fu Ye (22 años - Jesús María) - 4 de abril del 2023
URL del video: (enlace) (Comienzo 00:00:00 - Fin 00:21:10)
<img src="" alt="Entrevista de Liliana Fu Ye" />
Resumen:
Después de entrevistar a Liliana Fu Ye, una estudiante de 22 años de Ingeniería de Software en la UPC y practicante en el banco Interbank, se han recopilado detalles importantes sobre sus hábitos de estacionamiento y sus preferencias en cuanto a la utilización de espacios de estacionamiento. Liliana mencionó que reside en el distrito de Jesús María y utiliza un vehículo prestado por su madre para desplazarse al trabajo y hacer compras los fines de semana en el distrito del Callao. Suele visitar los distritos de San Isidro y el Callao. Identificó las horas laborales y las ocasiones en las que almuerza con amigos en Miraflores como momentos difíciles para encontrar estacionamiento. Expresó su disposición para utilizar un estacionamiento privado y consideró útil una aplicación que muestre estos lugares, ya que actualmente se apoya en GPS que no son precisos para este propósito.
En cuanto a seguridad, sugirió que los estacionamientos deberían ubicarse en lugares privados o contar con personal vigilante en caso de ser públicos. Reveló que tiene dos espacios de estacionamiento en su hogar, pero solo utiliza uno y estaría dispuesta a alquilar el espacio no utilizado de manera indefinida, ya que su padre se ha mudado a otra ciudad con su vehículo. Propuso que la función de alquilar espacios propios esté integrada en la misma aplicación que ayuda a buscar espacios de otros usuarios para mayor comodidad. En cuanto a la tarifa de alquiler mensual, sugirió un precio aproximado de 300 soles, y consideraría cobrar por horas a partir de 5, aunque requiere una deliberación más detenida sobre esta opción.

---

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 3: Leonardo Jesús Vargas Navarro (26 años - Ate) - 5 de abril del 2023
URL del video: https://youtu.be/lYCCdxyKcik (Comienzo 00:00:00 - Fin 00:09:11)
<img src="" alt="Entrevista de Leonardo Jesús Vargas" />
Resumen:
Después de entrevistar a Leonardo Jesús Vargas Navarro, un ingeniero civil de 26 años que trabaja actualmente en la empresa D'site Perú y que reside en el distrito de Ate Vitarte, pudimos informarnos sobre su rutina semanal que tiene para con su vehículo y algunas preferencias que tiene a la hora de usar espacios de estacionamiento. Más adelante, Leonardo nos comenta que es dueño de un Hyundai Sedán y cuenta con un garaje para el mismo en su hogar.
En cuanto a sus destinos frecuentes, él suele ir con su vehículo hasta el distrito de San Miguel por temas de trabajo, además de pasear de vez en cuando por distritos como San Isidro o La Molina. Luego, nos comentó que es un poco más complicado conseguir espacios de estacionamiento en las mañanas y al mediodía. Por otro lado, nos expresó que le parecía buena la idea de utilizar un estacionamiento privado, especialmente para los días que va a trabajar.
Sin embargo, identificó algunos aspectos de seguridad que podrían ser útiles para la aplicación, como el hecho de saber quién alquila el espacio privado o que estos espacios existan solo en distritos "no tan movidos". Sobre su disponibilidad para rentar alquilar su espacio de estacionamiento privado,

---

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 4: Jesus Pedro Casana (San Miguel) - 5 de Abril, 2024
<img src="" alt="Entrevista de Jesus Pedro Casana" />
Terminada la entrevista a Jesus Pedro Casana, el nos comenta que es joven universitario que estudia y trabaja y cuenta con carro propio. Él es consciente que debido a su trabajo le demanda ir a varios distritos de Lima y casi la mayoría del tiempo no consigue un estacionamiento adecuado debido a la gran cantidad de vehículos estacionados que se encuentran por la zona. El también comenta que cuenta con una amplia cochera donde guarda su auto. El entrevistado manifestó su disposición a utilizar estacionamientos privados y reconoció el valor de una aplicación que facilite la visualización de estos lugares. Señaló que actualmente se apoya en sistemas de GPS que no son precisos para encontrar estacionamiento, por lo que considera útil una herramienta que le brinde información específica sobre los espacios disponibles en estacionamientos privados.

---

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 5: Edu Arturo Antayhua Ticona (San Miguel) - 6 de Abril, 2024
<img src="" alt="Entrevista de Edu Arturo Antayhua" />
Se ha entrevistado a Edu Arturo Antayhua Ticona que tiene 21 años y trabaja de bartender. El menciona que usa su vehículo todos los días para ir a trabajar, estudiar y salir con su familia a pasear. Del mismo modo también dice que se le dificulta mucho salir a pasear con su vehículo ya que no encuentra un estacionamiento seguro por las zonas donde él normalmente se moviliza. También menciona que el uso de una aplicación con los servicios que mencionamos le serían de gran ayuda para su día a día..

---

Segmento objetivo: Usuario de Parking y Anfitrión
Entrevista 6. Rodrigo Tornero Loayza (Santiago de Surco) - 6 de Abril, 2024
<img src="" alt="Entrevista de Rodrigo Tornero Loayza" />
Se le ha realizado una entrevista a Rodrigo Tornero Loayza que cuenta con 21 años. El menciona que usó su vehículo de Lunes a Sábado para ir a la universidad y comprar algunas cosas que necesita para su universidad. El menciona también que durante la tarde cuando necesite un estacionamiento no hay debido a la alta demanda. El cree que usar la app que brinda nuestro servicio podría solucionar esos problemas y le ayudará a ahorrar un poco de tiempo. Respecto a los servicios de nuestra app, Rodrigo menciona que él considera viable la opción de alquilar una cochera a una persona si los estacionamiento se encuentran ocupados. Del mismo modo el dice que también sería capaz de alquilar su cochera si en algún momento no llegará a usarlo.

### 2.2.3. Análisis de entrevistas.

- Los entrevistados han comentado que sería de mucha utilidad el uso de una aplicación con los servicios que nosotros ofrecemos.. Además ellos son conscientes de la dificultad para conseguir un estacionamiento seguro fuera de su domicilio debido a las altas frecuencias de robo de vehículos.

- El 100% de los entrevistados destacan como aspecto positivo de la integración de herramientas de software para el proceso de búsqueda de estacionamientos que se optimiza significativamente el tiempo que se destina a desarrollar el proceso.

- El 100% de los entrevistados denotan interés y expresaron la utilidad de la plataforma que busca ofrecer Testigos de Vue con JobSync. Especialmente, expresaron que sería de gran utilidad que las pequeñas y medianas empresas que suelen tener presupuesto limitado para la adquisición de estos tipos de software

- Un porcentaje de los entrevistados comentaron que el proceso de búsqueda resultaba ser tedioso/laborioso por la gran cantidad de posibles estacionamientos a encontrar y que algunos no sean de su entera confianza.

## 2.3. Needfinding

En esta sección se presentarán los artefactos resultantes del proceso de análisis de la información recolectada de los segmentos objetivos

### 2.3.1. User Personas

User Persona del Usuario de Parking

<img src="" alt="Usuario de Parking" />

User Persona del Usuario de Anfitrión

<img src="" alt="Usuario de Anfitrion" />

### 2.3.2. User Task Matrix

En esta sección se presenta el user task matrix, herramienta centrada en los segmentos objetivos que nos permitirá identificar las tareas y objetivos claves de los usuarios

### 2.3.3. User Journey Matrix

User Journey Mapping de Anfitrión

<img src="" alt="Usuario Journey Mapping de Anfitrion" />

User Journey Mapping de Usuario de Parking

<img src="" alt="Usuario Journey Mapping de Parking" />

### 2.3.4. Empathy Mapping.

En esta sección se presenta el Empathy Mapping, herramienta para crear un perfil detallado de los user personas y desarrollar una comprensión profunda de su perspectiva y experiencia. Para cada user persona, se incluyen cinco elementos clave: lo que el usuario ve, lo que el usuario escucha, lo que el usuario dice, lo que el usuario hace y lo que el usuario siente. Además, se incluyen los pains y gains identificados en base a las preguntas: ¿Qué le preocupa?

Empathy Mapping de Anfitrión

<img src="" alt="Empathy Mapping de Anfitrion" />

Empathy Mapping de Usuario de Parking

<img src="" alt="Empathy Mapping de Parking" />

### 2.3.5. As-is Scenario Mapping.

En esta sección se presentan los As-is Scenario mapping para el segmento objetivo

<img src="" alt="As-is Scenario Mapping Usuario de parking" />

<br />

<img src="" alt="As-is Scenario Mapping Anfitrion" />

## 2.4 Ubiquitous Language

Parqueo: Espacio designado para estacionar vehículos.

Usuario: Persona que utiliza la aplicación para buscar parqueos disponibles.

Búsqueda de parqueo: Acción de encontrar espacios de estacionamiento disponibles en una ubicación específica.

Disponibilidad: Estado de un parqueo que indica si está libre u ocupado.

Ubicación: Lugar donde se encuentra el parqueo disponible.

Precio: Tarifa cobrada por el uso del parqueo, si es aplicable.

Reserva: Acción de asegurar un parqueo disponible para un momento específico en el futuro.

Confirmación: Aviso que indica que la reserva de parqueo ha sido aceptada.

Cancelar reserva: Acción de anular una reserva previamente realizada.

Calificación: Valoración dada por los usuarios sobre la calidad y conveniencia de un parqueo.

Comentarios: Opiniones escritas por los usuarios sobre su experiencia en un parqueo específico.

Historial de reservas: Registro de las reservas de parqueo realizadas por un usuario.

Notificaciones: Mensajes enviados a los usuarios sobre la disponibilidad de parqueos, confirmaciones de reservas, etc.

Favoritos: Parqueos marcados por un usuario como sus preferidos para un acceso rápido en el futuro.

Tipo de parqueo: Categorización del parqueo según características como cubierto, al aire libre, subterráneo, etc.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se presentan los To-Be Scenario Mapping para cada segmento objetivo donde se reflejarán, a partir de los As-is Scenario Mapping, la experiencia de usuario ideal si se resuelven los puntos de dolor y necesidades. La herramienta empleada para su desarrollo ha sido Miro.

To-Be Scenario Mapping: Usuario de Parking

<img src="" alt="To-be Scenario Mapping Usuario de parking" />

To-Be Scenario Mapping: Anfitrión

<img src="" alt="To-be Scenario Mapping Anfitrion" />

## 3.2. User Stories

Redactamos historias de usuarios que nos ayuden a generar funciones del software que estamos desarrollando para los usuarios finales. Las épicas identificadas son: Landing page, autenticación y perfil de usuario, dashboard de usuario, organización empresarial para reclutamientos, organización de proceso de reclutamiento y participación en proceso de reclutamiento.

## 3.3. Impact Mapping

Con el fin de mejorar nuestra comprensión de los grupos a los que nos dirigimos, en esta sección emplearemos la herramienta Impact Map. Esta herramienta nos permite establecer una conexión entre las necesidades de nuestros usuarios y los objetivos de nuestro proyecto mediante la identificación de impactos y entregables. Los impactos nos muestran las acciones que nuestros usuarios deben llevar a cabo para acercarnos a nuestros objetivos, mientras que los entregables nos indican de qué manera podemos apoyarlos para alcanzar dichos objetivos. A continuación, presentamos los mapas de impacto de los usuarios.

Impact Mapping: Usuario de Parking
<img src="" alt="Impact Mapping Usuario de parking" />

Impact Mapping: Anfitrión
<img src="" alt="Impact Mapping Usuario de parking" />

## 3.4. Product Backlog

A continuación se muestra la elaboración del Product Backlog en la herramienta Trello:

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

**Branding**
El logo principal está conformado por los colores principales de la aplicación. Tiene variantes donde se puede adaptar para diferentes dimensiones como horizontal, vertical o espacios pequeños.

![Imagen de Logos](./assets/branding.png)

**Typography**
Para la fuente a emplear usaremos dos tipografías, ambas en sus variantes de peso Regular, Medium, Semi Bold y Bold.
Rubik. Principalmente usado para los títulos, subtítulos y encabezados de artículos.
Mulish. Empleado para contenido como párrafos, texto informativo, articulos, etc.
Elaboramos unas reglas para un estilo uniforme en los contenidos de la Landing Page y Aplicación Web. Cabe recalcar que el sistema varía con el principio de Responsive Design.

![Imagen de Tipografia](./assets/typography.png)

**Spacing System**
Para el sistema de espaciado se ha decidido que se usará una cantidad de medida múltiple de 4px para mantener una continuidad en todos los elementos y sus distancias entre ellos.
![Imagen de Espaciados](./assets/spacing.png)

**Colors**
Como equipo, hemos decidido seleccionar colores que brindan al usuario una sensación de confianza, seguridad y aventura. Para ello, seleccionamos los colores Azules y Naranja con sus códigos #3C4E67 y #EF6C42 respectivamente. Además, para agregar una mayor utilidad al sistema decidimos usar sus tonalidades desde la más clara hasta la más oscura. Por último, para los textos optamos por los un color negro y gris oscuro.
![Imagen de Colores](./assets/spacing.png)
