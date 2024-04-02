# Universidad Peruana de Ciencias Aplicadas  

### INFORME DEL TRABAJO 1 (TB1)
![icono](https://github.com/AppWeb-Grupo3/informe/assets/89095594/c749a45e-dbf1-402b-9160-b9948f5ddd5a)

**Curso:** Desarrollo de Aplicaciones Open Source

**Sección:** WX53

**Profesor:** Naldo Reupo Musayon Gastulo

**Carrera:** Ingeniería de Software

**Ciclo:** 2024-01

**Startup:** ARSAA

**Producto:** DriveSafe



| Nombre                            | Código       |
|-----------------------------------|--------------|
| Nelson Elías Serrano Ircañaupa | U202214733   |
| Carlos Andres Rojas Ccama | U202114657 |
| Jhan Clinton Antonio Salazar | U20201B312 |
| Luis Enrique Aquije Quiroga       | U202114936   |
| Leonel Alfaro Cumba         | u20201A930   |


### Registro de Informes

| Versión | Fecha | Autor | Descripción de modificación |
|--------------|--------------|--------------|--------------|
| Entrega 1 (TB1)      | 30/03/2024      | -Leonel Alfaro Cumba<br>   | -Se creo el mardraw(completado) <br>-Se creó la estructura del informe (completado)|
| Entrega 2  (TP)      |       |     |  |
| Entrega 3 (TB2)      |    |  | |
| Entrega 4 (TF1)      |      | |  |


### Project Report Collaboration Insights




### Tabla de contenidos
- [Capítulo I: Introducción](#cap%C3%ADtulo-i-introducci%C3%B3n)
- [Capítulo II: Requirements Elicitation & Analysis](#cap%C3%ADtulo-ii-requirements-elicitation--analysis)
- [Capítulo III: Requirements Specification](#cap%C3%ADtulo-iii-requirements-specification)
- [Capítulo IV: Product Design](#cap%C3%ADtulo-iv-product-design)
- [Capítulo V: Product Implementation, Validation & Deployment](#cap%C3%ADtulo-v-product-implementation-validation--deployment)

### Studen Outcome



| Criterio Específico | AccionesRealizadas | Conclusiones |
|---------------------|--------------------|--------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | Leonel Alfaro Cumba <br>**TB1**<br>Completado del capítulo 1 del informe<br><br>Jhan Clinton Antonio Salazar<br>**TB1**<br>Completado de la parte del web application del capítulo 4 del informe.<br><br>Nelson Elías Serrano Ircañaupa<br>**TB1**<br> Completado del capítulo 2 del informe. <br><br> Carlos Andres Rojas Ccama <br>**TB1**<br> Ayude a completar el capitulo 2 con mi compañero. | **TB1**<br>Nos reunimos como equipo y decidimos las partes del proyecto de las que se encargaría cada miembro. Asimismo logramos ganar la confianza de todos mostrando empatía y responsabilidad el uno con el otro.|
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.     | Leonel Alfaro Cumba<br>**TB1**<br>Completado del capítulo 1 del informe.<br><br>Jhan Clinton Antonio Salazar<br>**TB1**<br>Completado de la parte del web application del capítulo 4 del informe.<br>  | <br>**TB1**<br>Aprendimos a usar GitHub y GitHub Desktop. Además, entendimos cómo hacer commits en esta herramienta y cómo nos podrán ayudar en el desarrollo de este proyecto.<br>|



# Capítulo I: Introducción

## 1.1 Startup Profile
Como ARSSA un startup que se ha propuesto resolver los desafíos inherentes a la industria de alquiler de vehículos mediante el empleo de soluciones tecnológicas innovadoras, nos destacamos por características distintivas como la retención de pagos, seguimiento GPS, una amplia selección de vehículos y un servicio al cliente de primera calidad. Estas características no solo garantizan la seguridad y protección de nuestros clientes, sino que también les proporcionan comodidad y ahorro. Fundada por estudiantes universitarios que tiene el propósito de transformar la experiencia de alquiler de autos a través de la aplicación de tecnología en una experiencia agradable y enfocado en el cliente.

**Misión**

- Nuestra misión es ayudar a las personas a reducir los contratiempos que puedan tener al momento de rentar o poner en renta un auto para que estas puedan hacerlo de forma sencilla y segura. Pensamos lograr esto mediante el lanzamiento de aplicaciones web que se enfoquen en atacar dichos contratiempos.

**Visión**
- Nuestra visión es tener una aplicación dedicada al nicho de la renta de autos que se encuentre en el top 10 de dicho nicho en Perú. Asimismo, planeamos expandir nuestros productos a nivel latinoamérica para que más personas puedan disfrutar de estos.

### 1.1.2 Descripción de la Startup

| Integrante                           | Foto | Descripción del Perfil                                                                                          |
|-------------------------------------|-------|-----------------------------------------------------------------------------------------------------------|
| Nelson Elías Serrano Ircañaupa|![image](https://github.com/AppWeb-Grupo3/informe/assets/89095594/2ba540f8-4888-4bc1-9cc6-0d712a50e759)|Me llamo Nelson Serrano, estudiante de Ingeniería de Software con el código estudiantil U202214733. Mi carrera se basa en crear soluciones digitales e innovadoras para distintas problemáticas del mundo real . Las habilidades en las que puedo aportar en el grupo son dominio y práctica lenguajes de programación como C++ y python, documentación de proyectos y metodologías ágiles y conocimientos básicos de base de datos.  |
| Luis Enrique Aquije Quiroga | ![FotoLuis](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/LuisFoto.png)| Soy Luis Enrique Aquije Quiroga, me encuentro en el 6to ciclo de la carrera de Ingeniería de Software. Desde pequeño siempre me sentí atraido por las computadoras y lo que uno puede hacer con ella. Al indagar aun mas sobre de que trataba la carrera supe que esto era lo mío y a lo que me iba a dedicar. Actualmente me siento atraído por lo relacionado a ciberseguridad y estoy seguro que lo aprendido en este curso me servirá para mi futuro profesional |
|  Carlos Andres Rojas Ccama  |![Foto Carlor andres](https://github.com/AppWeb-Grupo3/informe/assets/89095594/c14e0c6e-bcc4-41fa-810c-4379e9b2ac64)   |Mi nombre es Carlos Andres Rojas Ccama, estudio la carrera de Ingeniería de Software. Mi carrera consiste en crear softwares inteligentes y sistemas informáticos usando un lenguaje de programación con lógica, asociado a la tecnología, herramientas para el diseño, mantenimiento de software, etc. Me considero una persona responsable y colaborativo como ayudar a las personas y dar ideas, especialmente en grupos. En este trabajo en equipo se requiere dar una buena comunicación, por ello, siempre daré mi opinión y escuchar las opiniones de mis compañeros con respeto. |
| Leonel Alfaro Cumba                 |![FotoLeonel](https://github.com/AppWeb-Grupo3/informe/assets/89095594/5b77db63-ca8e-4e81-a98d-83f550c2d46a)|Estudiante de Ingeniería de Software con gran interés en la tecnología y la innovación. Motivado por ampliar conocimientos y desarrollarse constantemente.|
| Jhan Clinton Antonio Salazar                |![foto jhan](https://github.com/AppWeb-Grupo3/informe/assets/83793319/9a549bfc-d2fa-49fb-805e-33a995146bc7)|EActualmente, soy estudiante de ingeniería de software. Me apasiona la tecnología y el desarrollo de soluciones innovadoras para mejorar la vida de las personas. Estoy emocionado de seguir aprendiendo y creciendo en este campo emocionante y en constante evolución.|
| || |

## 1.2 Solution Profile


### 1.2.1 Antecedentes y problemática

El empleo de vehículos se ha vuelto una necesidad en nuestra sociedad, sea para fines recreativos, laborales o personales. Sin embargo, ¿qué ocurre cuando requieres un automóvil y no posees uno? La opción común es alquilarlo, pero esto puede acarrear problemas como tarifas altas, costos ocultos, mantenimiento deficiente o carencia de seguro para el vehículo. Además, hay quienes desean obtener ingresos extra alquilando sus automóviles en períodos de inactividad, pero carecen de un medio seguro para hacerlo o de clientes potenciales. Para atender estos dilemas, se plantea crear una aplicación web en Perú que ofrezca soluciones efectivas a los desafíos mencionados.
Who
Este servicio está dirigido a personas que desean alquilar vehículos de forma segura y a precios más accesibles que los ofrecidos por las plataformas convencionales. Además, está destinado a propietarios de vehículos que buscan una manera segura de rentar sus automóviles durante los períodos en que no los utilizan para obtener ingresos adicionales.
 
What
El aplicativo aborda una serie de problemas comunes asociados con el alquiler y uso de vehículos, tales como el mantenimiento deficiente de los automóviles, la falta de seguimiento de su ubicación, la ausencia de un seguro adecuado, los precios elevados y el riesgo de posibles estafas.
 
Where
Las complicaciones pueden surgir en diversos lugares donde se alquilan o utilizan vehículos, incluyendo concesionarios, hogares, oficinas, calles y autopistas. Este amplio alcance geográfico resalta la importancia de contar con un aplicativo que pueda ofrecer soluciones en cualquier ubicación donde se necesite un automóvil.
When
 
Los problemas pueden manifestarse en cualquier momento, desde el proceso de alquiler hasta el uso del vehículo. Esto puede incluir desde la fase inicial de reserva y firma de contratos hasta situaciones que ocurren mientras el vehículo está en tránsito o en uso por parte del arrendatario.
 
Why
Las complicaciones técnicas con los vehículos a menudo se deben a la falta de mantenimiento por parte de los propietarios, mientras que los cargos no declarados suelen surgir debido a las prácticas comerciales de los concesionarios que buscan maximizar sus ganancias. Las estafas y los problemas con vehículos desaparecidos pueden ser consecuencia de la falta de integridad por parte de algunos arrendatarios.
 
 
How
 
Las estafas generalmente ocurren cuando un arrendatario realiza un pago anticipado al propietario, quien luego no cumple con su parte del acuerdo. Además, pueden surgir casos en los que los arrendatarios utilicen métodos fraudulentos para simular pagos o no devuelvan el vehículo según lo acordado.
 
How Much
Estos problemas pueden ser costosos tanto en términos financieros como en tiempo y esfuerzo dedicados a resolverlos. Por ejemplo, una garantía no reembolsada puede representar una pérdida significativa de dinero para un arrendatario. Por eso, es fundamental contar con una plataforma confiable que minimice estos riesgos para ambas partes involucradas en el proceso de alquiler de vehículos.

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

El alquiler de automóviles conlleva diversos riesgos tanto para el arrendatario como para el arrendador. Estos riesgos van desde fallas técnicas en los vehículos hasta casos de estafa, lo que repercute negativamente en la confianza en el negocio de alquiler de autos. Los problemas mencionados anteriormente son solo una muestra de cómo tanto arrendatarios como arrendadores buscan mayor seguridad y transparencia en el proceso. Tras analizar esta situación, se ha formulado la siguiente pregunta como base para abordar esta problemática:


¿Qué medidas podemos implementar para asegurar la seguridad y la transparencia tanto para quienes alquilan como para quienes ofrecen autos en alquiler?

#### 1.2.2.2 Lean UX Assumptions


**Business Outcomes** 

- Considero que mis clientes necesitan una solución que les permita alquilar o poner en alquiler automóviles de manera segura y transparente.
- Mis clientes iniciales son o serán hispanohablantes adultos en el  Perú que deseen alquilar o poner en alquiler un auto.
- Estas necesidades pueden ser satisfechas mediante una aplicación web de alquiler de autos segura entre personas naturales
- Planeo atraer a la mayoría de mis clientes a través de anuncios en redes sociales.
- Mi principal competencia en el mercado son las plataformas de alquiler de autos ya establecidas.
- La principal prioridad para un cliente será la seguridad de que el contrato se cumpla correctamente y de que el auto esté en buenas condiciones.
- Los clientes también valorarán beneficios adicionales como precios más bajos que los de la competencia, registro de mantenimiento del vehículo, seguimiento GPS y acceso a la documentación actualizada del auto.
- Planeo superar a la competencia ofreciendo precios más bajos, mayor transparencia en la documentación y estado de los autos, y una mayor seguridad.
- El mayor riesgo que enfrento es el fraude o las estafas antes, durante y después del servicio de alquiler de autos.
- Abordaré este problema reteniendo el pago hasta que el servicio se haya completado satisfactoriamente.
- Generar ingresos mediante el cobro de comisiones por cada alquiler realizado a través de la aplicación y mediante publicidad dentro de la misma.

**User Outcomes**

¿Quién es el usuario?
 
- El usuario de nuestro producto son personas hispanohablantes adultas en el Perú que buscan una solución conveniente y segura para alquilar o poner en alquiler un automóvil. Pueden ser tanto propietarios de vehículos que desean generar ingresos adicionales mediante el alquiler de sus autos, como personas que necesitan un vehículo temporalmente para viajes o actividades específicas.

¿Dónde se aplica nuestro producto?
 
- Nuestro producto se integra en la vida cotidiana del usuario, ya que el alquiler o puesta en alquiler de un auto puede ser una necesidad ocasional para muchas personas. Se puede acceder al servicio desde cualquier lugar con conexión a internet, lo que brinda una gran flexibilidad y conveniencia a los usuarios, ya sea que estén en casa o en el trabajo.

¿Qué problemas aborda nuestro producto y cómo los resuelve?
 
- Nuestro producto aborda el problema de prácticas fraudulentas y la falta de seguridad en el proceso de alquiler de vehículos. Para resolver estos problemas, implementamos medidas como la inclusión de documentación del auto en la aplicación, la retención del pago hasta la finalización del servicio y el seguimiento del vehículo mediante GPS. Esto proporciona tranquilidad tanto a los propietarios como a los arrendatarios, asegurando una transacción segura y sin contratiempos.

¿Cuándo y cómo se utiliza nuestro producto?
 
- Nuestro producto se utiliza cuando los usuarios desean alquilar o poner en alquiler un automóvil. Se puede acceder a través de dispositivos con navegador web, lo que permite una experiencia fácil y conveniente. Los usuarios pueden buscar, reservar y gestionar sus alquileres desde la comodidad de su hogar o mientras están en movimiento, lo que les brinda flexibilidad y control total sobre sus transacciones de alquiler de autos.

¿Qué características son importantes?
 
- Es fundamental que nuestro producto tenga una interfaz amigable, intuitiva y adaptable para garantizar una experiencia de usuario positiva. Además, características como la reserva de vehículos, colocar vehículos para alquilar y los pagos integrados. 
¿Cómo debe ser la apariencia y el comportamiento de nuestro producto?
La apariencia de nuestro producto debe reflejar su objetivo de ser fácil de usar y comprender para todos los usuarios. La interfaz debe ser limpia, organizada y visualmente atractiva, con elementos intuitivos que guíen al usuario a través de los diferentes pasos del proceso de alquiler o colocar en alquiler el vehículo.


#### 1.2.2.3 Hipótesis Lean UX


**Hipótesis 1**
 
Creemos que las personas estarán interesadas en una aplicación web que permite alquilar y poner en alquiler autos a precios más bajos que los de la competencia. Confirmaremos esto si la cantidad de usuarios de nuestro producto aumenta en un 5% semanal durante los primeros 4 meses después de su lanzamiento.
 
**Hipótesis 2**
 
Creemos que nuestro producto enfrentará problemas después de su lanzamiento. Confirmaremos esto si la cantidad de usuarios comienza a disminuir en un 8% semanal.
 
**Hipótesis 3**
 
Creemos que la visualización de la documentación de los vehículos en la aplicación será un valor agregado importante. Confirmaremos esto si el 65% de las reseñas de vehículos en la aplicación son positivas.

**Hipótesis 4**

Creemos que la prestación de un servicio al cliente rápido y efectivo mejorará la reputación del producto y fomentará la lealtad de los usuarios. Confirmaremos esto si observamos un aumento del 20% en las calificaciones positivas del servicio al cliente en las reseñas del aplicativo.

**Hipótesis 5**

Creemos que la transparencia en las políticas de precios y condiciones de alquiler aumentará la confianza del cliente en la plataforma. Confirmaremos esto si observamos un aumento del 15% en las reseñas positivas. 

#### 1.2.2.4 Lean UX Canvas


 <table>
            <tr>
              <td valign="top"><p><b>Business Problem</b></p><br>
                <p>•	Estafas en la renta de autos </p><br>
                <p>•	Precios altos</p><br>
                <p>•	Falta de transparencia en el estado del auto</p><br>  <p>•	Tarifas ocultas</p><br>
               </td>
              <td rowspan="2" valign="top"><p><b>Solution Ideas</b></p><br>
                <p>•	Precios competitivos</p><br>
                <p>•	Inclusión de documentación actualizada del auto</p><br>
                <p>•	Seguimiento vía GPS</p><br>
                <p>•	Retención del pago hasta finalizar el servicio </p></td>
              <td valign="top"><p><b>Business Outcomes</b></p><br>
              <p>•	Gran cantidad de usuarios</p><br>
              <p>•	Reseñas mayormente positivas</p><br>
              <p>•	Se convierte en una de las aplicaciones más utilizadas en Perú para alquiler de autos</p><br>
            </td>
            </tr>
            <tr>
              <td valign="top"><p><b>Users and Customers</b></p><br>
                <p>•	Hispanohablantes adultos en Perú que buscan alquilar un auto.</p>
                <p>•Hispanohablantes adultos en Perú que cuenten con un auto y deseen ponerlo en alquiler.</p>
                </td>
              <td valign="top"><p><b>User Benefits</b></p><br>
                <p>•	Costos más bajos</p><br>
                <p>•	Garantía del estado del auto</p><br>
                <p>•	Prevención de fraudes</p><br>
                <p>•	Acceso a la información del arrendatario</p><br>
                </td>
            </tr>
            <tr><td valign="top"><p><b>Hypothesis</b></p><br>
                <p> •	Creemos que nuestro producto enfrentará problemas después de su lanzamiento. Confirmaremos esto si la cantidad de usuarios comienza a disminuir en un 8% semanal.</p>
                <p>•	Creemos que nuestro producto enfrentará problemas después de su lanzamiento. Confirmaremos esto si la cantidad de usuarios comienza a disminuir en un 8% semanal.<br></p>
                <p>•	Creemos que la visualización de la documentación de los vehículos en la aplicación será un valor agregado importante. Confirmaremos esto si el 65% de las reseñas de vehículos en la aplicación son positivas.</p>
            </td>
              <td valign="top"><p><b>What’s the most important thing we need to learn first?</b></p><br>
                <p>•	Necesidades reales de los usuarios</p><br> 
                <p>•	Disposición para alquilar autos vía aplicación</p><br>
                <p>•	Análisis de costos y beneficios de la competencia</p><br>
                </td>
              <td valign="top"><p><b>What's the least amount of work we need to do to learn the next most important thing?</b></p><br>
                <p>•	Entrevistas a los segmentos objetivos
                </p><br>       
                <p>•	Envío de formularios clave a los segmentos objetivos</p><br>
                <p>•	Implementación de feedback en el aplicativo</p></td></tr>
          </table>

<br><br>


## 1.3 Segmentos objetivo

**Se identificó dos  segmentos objetivos**


- Personas mayores de 18 años con licencia de conducir interesadas en encontrar alquileres de automóviles a tarifas justas y transparentes, que se ajusten a su presupuesto.

- Personas mayores de 18 años que tengan por lo menos un vehículo legalmente registrado y documentado, y deseen alquilarlo de forma segura a través de plataformas digitales.



# Capítulo II: Requirements Elicitation & Analysis

## Competidores

### Análisis competitivo

<table border="1">
  <thead>
    <tr>
      <th colspan="6" style="text-align:center;"><strong>Competitive Analysis Landscape</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="1" style="text-align:center;">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5" style="text-align:center;">El objetivo de este análisis es comprender el posicionamiento de nuestra startup, DriveShare, en comparación con sus competidores principales en la industria de alquiler de vehículos.</td>
    </tr>
    <tr>
      <td colspan="2" style="text-align:center;">Competidores</td>
      <td style="text-align:center;">DriveShare</td>
      <td style="text-align:center;">Turo</td>
      <td style="text-align:center;">Zipcar</td>
      <td style="text-align:center;">Getaround</td>
    </tr>
    <tr>
      <td rowspan="2" style="text-align:center;">Perfil</td>
      <td style="text-align:center;">Overview</td>
      <td style="text-align:center;">Plataforma de alquiler de vehículos con un enfoque centrado en la tecnología y la comodidad del cliente</td>
      <td style="text-align:center;">Plataforma de alquiler de vehículos que se destaca por su gran comunidad de usuarios y su enfoque en la conveniencia y la accesibilidad.</td>
      <td style="text-align:center;">Servicio de alquiler de coches que se enfoca en la movilidad urbana y la flexibilidad</td>
      <td style="text-align:center;">Plataforma de alquiler de coches que se destaca por su presencia global y su enfoque en la comunidad de alquiler de vehículos compartidos.s</td>
    </tr>
    <tr>
      <td style="text-align:center;">Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</td>
      <td style="text-align:center;">Retención de pagos, seguimiento GPS, amplia selección de vehículos, servicio al cliente de primera calidad</td>
      <td style="text-align:center;">Plataforma de alquiler de vehículos entre particulares</td>
      <td style="text-align:center;">Servicio de alquiler de coches por horas o días</td>
      <td style="text-align:center;">Mercado de alquiler de coches entre particulares</td>
    </tr>
    <tr>
      <td rowspan="2" style="text-align:center;">Perfil de Marketing</td>
      <td style="text-align:center;">Mercado objetivo</td>
      <td style="text-align:center;">Personas mayores de edad y conductores con licencia en regla</td>
      <td style="text-align:center;">Personas que buscan alquilar vehículos de particulares</td>
      <td style="text-align:center;">Usuarios urbanos que necesitan un coche por horas</td>
      <td style="text-align:center;">Viajeros y propietarios de vehículos que desean alquilarlos</td>
    </tr>
    <tr>
      <td style="text-align:center;">Estrategias de marketing</td>
      <td style="text-align:center;">Marketing digital enfocado en las experiencias de usuario, informando las ventjas y seguridad del servicio</td>
      <td style="text-align:center;">Marketing digital, promoción entre comunidades locales</td>
      <td style="text-align:center;">Publicidad en medios urbanos, marketing digital</td>
      <td style="text-align:center;">Marketing digital, promoción en redes sociales</td>
    </tr>
    <tr>
      <td rowspan="3" style="text-align:center;">Perfil de producto</td>
      <td style="text-align:center;">Productos & Servicios</td>
      <td style="text-align:center;">Alquiler de vehículos y la funcionalidad de disponer vehículos en alquiler</td>
      <td style="text-align:center;">Plataforma de alquiler entre particulares</td>
      <td style="text-align:center;">Servicio de alquiler de coches por horas o días</td>
      <td style="text-align:center;">Plataforma de alquiler de coches entre particulares</td>
    </tr>
    <tr>
      <td style="text-align:center;">Precios & Costos</td>
      <td style="text-align:center;">Plataforma gratuita, y desde S/100 por día de alquiler</td>
      <td style="text-align:center;">Determinados por los propietarios de los vehículos, el mínimo encontrado es S/120</td>
      <td style="text-align:center;">Tarifas por horas o días, desde S/20 la hora o S/110 el día</td>
      <td style="text-align:center;">Varían según el vehículo y la ubicación, desde S/240</td>
    </tr>
    <tr>
      <td style="text-align:center;">Canales de distribución<br>(Web y/o Móvil)</td>
      <td style="text-align:center;">Plataforma web y aplicación móvil</td>
      <td style="text-align:center;">Plataforma web y aplicación móvil</td>
      <td style="text-align:center;">Aplicación móvil y ubicaciones físicas</td>
      <td style="text-align:center;">Plataforma web y aplicación móvil</td>
    </tr>
    <tr>
      <td rowspan="4" style="text-align:center;">Análisis SWOT</td>
      <td style="text-align:center;">Fortalezas</td>
      <td style="text-align:center;">Tecnología avanzada, amplia selección de vehículos</td>
      <td style="text-align:center;">Gran comunidad de usuarios, conveniencia</td>
      <td style="text-align:center;">Acceso inmediato a vehículos, flexibilidad en el alquiler</td>
      <td style="text-align:center;">Variedad de vehículos disponibles, presencia global</td>
    </tr>
    <tr>
      <td style="text-align:center;">Debilidades</td>
      <td style="text-align:center;">Dependencia de la tecnología, posible resistencia al cambio</td>
      <td style="text-align:center;">Dependencia de los propietarios de vehículos, regulaciones locales</td>
      <td style="text-align:center;">Limitación geográfica, posible competencia de transporte público</td>
      <td style="text-align:center;">Dependencia de la confiabilidad del arrendador y del arrendatario</td>
    </tr>
    <tr>
      <td style="text-align:center;">Oportunidades</td>
      <td style="text-align:center;">Expansión a nuevos mercados, colaboraciones estratégicas</td>
      <td style="text-align:center;">Crecimiento del mercado de alquiler entre particulares, internacionalización</td>
      <td style="text-align:center;">Innovación tecnológica, expansión a áreas suburbanas</td>
      <td style="text-align:center;">Crecimiento del mercado de alquiler de vehículos compartidos, alianzas con empresas de viajes</td>
    </tr>
    <tr>
      <td style="text-align:center;">Amenazas</td>
      <td style="text-align:center;">Competencia de grandes empresas de alquiler de vehículos, cambios en regulaciones gubernamentales</td>
      <td style="text-align:center;">Competencia de empresas establecidas, cambios en la percepción de compartir vehículos</td>
      <td style="text-align:center;">Entrada de nuevos competidores, cambios en las preferencias de movilidad</td>
      <td style="text-align:center;">Regulaciones gubernamentales, percepción negativa sobre el alquiler de vehículos compartidos</td>
    </tr>
  </tbody>
</table>

### Estrategias y tácticas frente a competidores

-Continuar innovando en características distintivas como la retención de pagos, seguimiento GPS y servicio al cliente de primera calidad para destacar la propuesta de valor única de DriveShare en comparación con sus competidores.
-Priorizar la satisfacción del cliente a través de un servicio personalizado, atención al cliente ágil y resolución rápida de problemas.
-Desarrollar campañas de marketing que resalten las fortalezas de DriveShare en medios audiovisuales de corta duración para atraer a clientes potenciales familiarizados con estos medios.
-Realizar investigaciones de mercado y recopilar comentarios de los usuarios para identificar áreas de mejora en la plataforma y desarrollar nuevas características que satisfagan las necesidades y expectativas de los clientes.
-Incentivar a los usuarios a referir a amigos y familiares mediante programas de referidos que ofrezcan descuentos o créditos en el servicio a cambio de nuevas inscripciones exitosas.
-Continuar mejorando la interfaz de usuario de la plataforma, simplificando el proceso de reserva y garantizando una experiencia fluida y sin problemas para los usuarios en todas las etapas del viaje de alquiler de vehículos.


## **2.2. Entrevistas.**

### **2.2.1. Diseño de entrevistas.**

Preguntas Generales para Ambos Segmentos:

-   ¿Cuál es su nombre?

-   ¿Qué edad tiene?

-   ¿Dónde reside actualmente?

-   ¿Cuál es su ocupación actual?

Preguntas para Arrendatarios:

-   ¿Alguna vez tuvo experiencias sobre alquilar un auto?¿cómo resultó?

-   ¿Qué características específicas buscaría en un servicio de alquiler de vehículos?

-   ¿Cómo cree que la tecnología podría mejorar su experiencia al alquilar un vehículo?

-   ¿Prefiere alquilar un vehículo por períodos cortos o largos? ¿Por qué?

-   ¿Qué opina sobre la disponibilidad de una amplia selección de vehículos en un servicio de alquiler?

-   ¿Qué influiría en su decisión de llegar a alquilar un automóvil: el precio, la disponibilidad o la reputación del servicio de alquiler?

-   ¿Qué opina sobre alquilar un automóvil a través de una aplicación web o móvil?

Preguntas para Arrendadores:

-   ¿Usted en alguna oportunidad puso en alquiler su vehículo?

-   ¿Qué preocupaciones tiene respecto a poner su vehículo en alquiler?

-   ¿Qué ventajas encuentra en la idea de utilizar la tecnología para gestionar el alquiler de su vehículo?

-   ¿Qué opinión tiene sobre el seguimiento GPS como medida de seguridad para su vehículo mientras está en alquiler?

-   ¿Qué nivel de importancia le da al seguro de vehículos al momento de poner su vehículo en alquiler?

-   ¿Qué características específicas de su automóvil cree que son más atractivas para los posibles arrendatarios?

-   ¿Cómo cree que la flexibilidad en los métodos de pago puede afectar la demanda de alquiler de su vehículo?

-   ¿Usted estaría interesado en poner en alquiler su auto por medio de una aplicación web móvil?

### **2.2.2. Registro de entrevistas.**

### **2.2.3. Análisis de entrevistas.**

## **2.3. Needfinding**



### **2.3.1. User Persona**

Con el objetivo de realizar una investigación exhaustiva sobre los segmentos objetivo al cual estará dirigido nuestra e-commerce, se llevó a cabo un proceso el cual acaba en los User Persona que representan a estos individuos.

**Segmento Arrendatarios: Personas mayores de 18 años con licencia de conducir interesadas en encontrar alquileres de automóviles a tarifas justas y transparentes, que se ajusten a su presupuesto.**

![foto_user_story_1](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/user%20story%20arrendatario.png)

**Segmento Arrendadores: Personas mayores de 18 años que tengan por lo menos un vehículo legalmente registrado y documentado, y deseen alquilarlo de forma segura a través de plataformas digitales.**

![foto_user_story_2](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/user%20story%20arrendador.png)

### **2.2.3. User Task Matrix**

En la redacción de los User Task matrix se toma en cuenta los segmentos antes mencionados

Arrendatario

| User Task : Arrendatario         | Frecuencia | Importancia |
| --- | --- | --- |
| Buscar un vehículo para alquilar | Siempre    | Alta       |
| Comunicarse con la empresa/persona encargada | Siempre | Alta |
| Seleccionar un vehículo | Siempre | Alta |
| Verificar disponibilidad | Seguido | Alta |
| Reservar el vehículo | Siempre | Alta |
| Recoger el vehículo | Siempre | Alta |
| Hacer uso del vehículo | Siempre | Alta |
| Devolver el vehículo | Siempre | Alta |
| Finalizar alquiler | Siempre | Alta |
| Proporcionar feedback | A veces | Media |

Arrendador

| User Task : Arrendador        | Frecuencia | Importancia |
| --- | --- | --- |
| Buscar alguien a quien alquilarle | Seguido  | Media    |
| Comunicarse con la persona interesada |   Seguido  | Alta    |
| Proporcionarle el vehículo que necesita |  Siempre   | Alta    |
| Proporcionarle la disponibilidad del vehículo |  Siempre | Alta    |
| Realizar la transacción |   Siempre  | Alta    |
| Entregar el auto a la persona |  Siempre   | Alta    |
| Recibir información del estado y ubicación del vehículo |  Siempre   | Alta    |
| Obtener de vuelta el auto |   Siempre  |  Alta   |
| Dar por finalizado el alquiler |   Siempre  | Alta   |
| Analizar informes y métricas de rendimiento |  A veces   |  Media   |

### **2.3.3. User Journey Mapping**

**Segmento Arrendatario**

![foto_user_journey_map_1](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/arrendatario_userjourneymapping.jpeg)

**Segmento Arrendador**

![foto_user_journey_map_2](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/arrendador_userjourneymapping.jpeg)

### 2.3.4. **Empathy Mapping**

**Segmento Arrendatario**

![foto_empahty_map_1](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/arrendatario_empathy%20map.jpeg)

**Segmento Arrendador**

![foto_empahty_map_2](https://github.com/AppWeb-Grupo3/informe/blob/main/imagenes/arrendador_empathy%20map.jpeg)

### ***2.3.4. As-Is Scenario Mapping**

Arrendatario

Maria Gonzales quiere buscar

| FASES | Búsqueda | Reserva | Uso | Finalización |
| --- | --- | --- | --- | --- |
| DOING | Buscando y explorando opciones de vehículos disponibles. | Seleccionando un vehículo específico y completando el proceso de reserva en línea. | Dirigiéndose al lugar de recogida para obtener el vehículo alquilado y haciendo uso de él durante el período acordado. | Devolviendo el vehículo al lugar designado y completando el proceso de devolución. |
| FEELING | Curiosidad por encontrar el vehículo adecuado y cierta anticipación por el próximo viaje. | Confianza al tomar decisiones de reserva y cierta ansiedad por confirmar la disponibilidad del vehículo deseado. | Emoción por empezar el viaje con el vehículo nuevo y cierto alivio al comprobar que todo está en orden. | Satisfacción al finalizar el viaje y motivación de recomendarlo a un conocido |
| THINKING | Considerando las diferentes opciones disponibles y evaluando qué vehículo se adapta mejor a las necesidades y presupuesto. | Revisando los detalles de reserva y asegurándose de que todos los términos y condiciones sean comprendidos y aceptados. | Planificando el itinerario del viaje y considerando aspectos logísticos relacionados con el uso del vehículo. | Reflexionando sobre la experiencia de alquiler y considerando proporcionar comentarios para mejorar el servicio en el futuro. |

Arrendador

| FASES | Búsqueda | Reserva | Uso | Finalización |
| --- | --- | --- | --- | --- |
| DOING | Buscando activamente posibles arrendatarios para sus vehículos disponibles. | Comunicándose con los arrendatarios interesados y acordando los términos del alquiler. | Preparando el vehículo para su entrega al arrendatario en el lugar y momento acordados. | Recibiendo el vehículo de vuelta del arrendatario al final del período de alquiler. |
| FEELING | Expectativa y anticipación por encontrar arrendatarios adecuados para maximizar la utilización de la flota de vehículos. | Confianza en la selección del arrendatario adecuado y cierta ansiedad por garantizar un proceso de reserva sin problemas. | Satisfacción al facilitar el uso del vehículo y cierta preocupación por la seguridad y el cuidado del mismo durante el período de alquiler. | Alivio al recibir el vehículo en buenas condiciones y cierta nostalgia al despedirse del arrendatario. |
| THINKING | Evaluando las solicitudes y considerando la idoneidad de los arrendatarios potenciales.. | Evaluando la disponibilidad de los vehículos y confirmando la idoneidad del arrendatario. | Considerando aspectos logísticos y asegurando que el vehículo esté en condiciones adecuadas para el arrendatario. | Evaluando el estado del vehículo y asegurando que se cumplan todos los términos del contrato de alquiler. |

# Capítulo III: Requirements Specification
### 3.1. **To-Be Scenario Mapping**
## **Usuario: Propietario**

| STEPS | Encuentra arrendatarios que están interesados en el alquiler del auto | Se comunica con el arrendatario interesado | Se encuentra con el arrendatario en el lugar acordado | Entrega del auto | 
| ------------- | ------ | ----- | ---- | - |
| DOING | Abre la aplicación para ver si alguna persona consulto por el alquiler del auto| Ingreso de usuarios | Como usuario no identificado en el sistema, quiero iniciar sesión en la aplicación, para lograr acceder a mi cuenta personal. | Entregan el auto al arrendatario | 
| THINKING | Se recibe solicitudes de arrendatarios interesados al alquiler del auto  | Fue rápido, directo y sencilla la comunicación con el arrendatario interesado en el alquiler | Conocer al arrendatario me da seguridad al saber a quien le estoy alquilando mi auto. | El contrato del auto fue fue sencillo, rapido y a un precio muy comodo | 
| FEELING | Una emoción de alegría al ver que hay personas interesadas en alquilar un auto | Asombrado por la facilidad de comunicación | Alivio al ver que puede alquilar el auto sin tanto demora | Emocionado de ver que pudo conseguir arrendar sin gastar tiempo |

## **Usuario: Arrendatario**

| STEPS | Buscar un propietario que aquile un auto  | Se comunica con el propietario | Se encuentra con el propietario para ver el auto | Recojo del auto alquilado | 
| ------------- | ------ | ----- | ---- | - |
| DOING | Abre la aplicación para buscar un propietario que alquile un auto | Acuerdan la fecha y hora para ver el auto | Se encuentra con el propietario y le muestra el auto | Recojo del auto en la fecha establecida según el contrato | 
| THINKING | Necesito alquilar un auto en un precio cómodo | Fue rapido, directo y sencillo la comunicación con el propietario | Conocer al propietario y ver el auto me da seguridad y confianza | El contrato del auto fue sencillo, rápido y a un precio cómodo | 
| FEELING | Aliviado por encontrar fácilmente propietarios que alquilen autos | Aliviado por encontrar fácilmente un propietario que alquile su auto | Seguridad al ver el estado del auto y conocer al propietario | Aliviado a encontrar y arrendar un auto en buen precio |

### 3.2. **User Stories**
| User Story ID | Titulo | Descripcion | Criterios de Aceptacion |
| ------------- | ------ | ----- | ---- |
| HU001 | Ingreso de Usuarios | Como usuario no identificado en el sistema, quiero iniciar sesión en la aplicación, para lograr acceder a mi cuenta personal. | Escenario N°1: Usuario inicia sesión con sus datos personales Dado que el usuario necesitará registrarse para ingresar por primera vez a la aplicación, deberá completar su información personal básica Cuando el usuario coloca en los campos “Correo electrónico” y “Contraseña” Y luego el usuario hace click en el botón “Acceder” entonces el sistema asigna una sesión de usuario | 
| HU002 | Registro del Arrendatario | Como Arrendatario, quiero registrarme dentro del aplicación para poder alquilar un auto según mi presupuesto. | Escenario°1: El arrendatario quiere crear una cuenta Dado que el arrendatario se encuentra en sección de "inicio" Cuando el arrendatario no se encuentra registrado en el aplicativo y al seleccionar “Crear una Cuenta” Entonces el sistema le redireccionará al registro.  Escenario N°2: El arrendatario rellena sus datos correctamente Dado que el arrendatario se encuentra en la sección de registro y selecciona la sección "Arrendatario" Cuando el arrendatario rellena todos los datos correctamente. Entonces el sistema registra los datos ingresados a la base de datos correctamente y mostrará "Usted se registró correctamente". |
| HU003 | Registro del Propietario | Como Propietario quiero registrarme dentro de la aplicación para ofrecer en alquiler mi auto | Escenario 1: El propietario quiere crear una cuenta Dado que el Propietario se encuentra en sección de "inicio" Cuando el arrendador no se encuentra registrado en la aplicación Entonces al seleccionar “Crear Cuenta” el sistema le redireccionará al registro. Escenario 2: rellenado de datos correctamente. Dado que el Propietario se encuentra en la sección de registro y selecciona la sección "propietario" Cuando el propietario rellene todos los datos correctamente Entonces el sistema registra sus datos ingresados a la base de datos y mostrará "Usted se registro correctamente ". |
| HU004 | Búsqueda de autos según características | Como Arrendatario quiero poder buscar autos según datos específicos para asi descartar otros tipos de autos | Escenario 1: El Arrendatario visualiza cuando existen datos específicos que desee Dado que el Arrendatario este en la sección "Buscar Autos" Cuando ingrese los datos en cada sección específica y encuentre información de estos. Entonces el sistema mostrará todos los autos que tenga estos en su informe. |
| HU005 | Notificaciones via correo o sms | Como usuario del sistema, quiero poder configurar notificaciones, para luego ser notificado y no perderme ningún evento | Escenario N°1: Usuario busca configurar notificaciones Dado que el sistema mostrará opciones de notificaciones, el usuario podrá configurarlo Cuando el usuario cambie el tono y tiempo que desee que llegue la alarma Y de click en “guardar cambios” Entonces el sistema guardara automáticamente esas nuevas modificaciones |
| HU006 | Interacción con los usuarios | Como administrador del sistema quiero poder comunicarme con los usuarios, para poder ofrecerles un servicio más personalizado. | Escenario N°1: Usuario recibe el servicio de atención al cliente Dado que el sistema muestra una sección de atención al cliente And este busca ayudar al usuario con algunas de sus consultas Cuando el usuario busca respuestas a sus consultas Entonces el sistema le enviara un asesor que le ayude en sus dudas de manera personalizada. |
| HU007 | Publicación de anuncio de alquiler de auto | Como propietario de un automóvil, quiero poder crear un anuncio para alquilar mi auto. | Escenario 1: Publicación de anuncio correctamente Dado que el propietario se encuentre en sección "Registro de Vehículo" Cuando rellene los detalles del automóvil, las tarifas de alquiler y seleccione "Registrar"Entonces el sistema lo guardará en la base de datos y móstrara en pantalla el contrato de alquiler. |
| HU008 | Autos disponibles en una área | Como arrendatario que busca alquilar un auto, quiero poder visualizar todos los autos disponibles de una área para elegir los que se ubican en mi zona. | Escenario 1: Visualización de autos correctamente Dado que el arrendatario se encuentre en sección "Buscar auto" Cuando rellene la opción de "Ubicación" Entonces el sistema mostrará todos los autos disponibles de la areá seleccionada. |
| HU009 | Solicitud de Alquiler de auto | Como arrendatario, Deseo solicitar el alquiler del auto para asi poder utilizar el auto.| Escenario 1: Solicitud de contrato del auto correctamente Dado que el arrendatario se encuentre en sección "Buscar auto" Cuando firma el documento y seleccione "Solicitar alquiler" Entonces el sistema mandará un mensaje de envío correctamente y mandará la solicitud al propietario. | 
| HU010 | Visualización de un sitio web de información de la aplicación. | Como un invitado, deseo visualizar una publicidad de la aplicación. | Escenario 1: Visualización de la landing page Dado que el invitado es nuevo y busca información de la aplicación Cuando ingrese al link de la landing page Entonces el sistema mostrará la landing page de la aplicación. |

### 3.3. **Impact Mapping**
![foto_impact_mapping](https://github.com/AppWeb-Grupo3/informe/blob/415e070e37948856d81fcaa3181903a2c8f397c6/imagenes/Impact_Mapping.png)

### 3.4. **Product Backlog**

| #Orden | User Story ID | Titulo | Descripción | Story Points |
| ------------- | ------ | ----- | ---- | ----- |
| 1 | HU001 | Ingreso de usuarios | Como usuario no identificado en el sistema, quiero iniciar sesión en la aplicación, para lograr acceder a mi cuenta personal. | 1 | 
| 2 | HU002 | Registro del Arrendatario | Como Arrendatario, quiero registrarme dentro del aplicacion para poder alquilar un auto según mi presupuesto. | 3 |
| 3 | HU003 | Registro del Propietario | Como Propietario quiero registrarme dentro de la aplicación para ofrecer en alquiler mi auto | 3 | 
| 4 | HU004 | Búsqueda de autos según características | Como Arrendatario quiero poder buscar autos según datos específicos para asi descartar otros tipos de autos | 8 |
| 5 | HU005 | Notificaciones via correo | Como usuario del sistema, quiero poder configurar notificaciones, para luego ser notificado y no perderme ningún evento | 5 | 
| 6 | HU006 | Interacción con los usuarios | Como administrador del sistema quiero poder comunicarme con los usuarios, para poder ofrecerles un servicio más personalizado | 5 | 
| 7 | HU007 | Publicación de anuncio de alquiler de auto | Como propietario de un automóvil, quiero poder crear un anuncio para alquilar mi auto | 8 |
| 8 | HU008 | Autos disponibles en una área | Como arrendatario que busca alquilar un auto, quiero poder visualizar todos los autos disponibles de una área para elegir los que se ubican en mi zona | 5 | 
| 9 | HU009 | Solicitud de Alquiler de auto | Como arrendatario, quiero solicitar el alquiler del auto para asi poder utilizar el auto | 5 |
| 10 | HU010 | Visualización de un sitio web de información de la aplicación | Como un invitado, quiero visualizar una publicidad de la aplicación | 8 |


