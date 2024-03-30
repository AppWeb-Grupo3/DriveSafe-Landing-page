# Universidad Peruana de Ciencias Aplicadas  

### INFORME DEL TRABAJO 1 (TB1)
![icono](https://github.com/AppWeb-Grupo3/informe/assets/89095594/c749a45e-dbf1-402b-9160-b9948f5ddd5a)

**Curso:** Desarrollo de Aplicaciones Open Source

**Sección:** WX53

**Profesor:** Naldo Reupo Musayon Gastulo

**Carrera:** Ingeniería de Software

**Ciclo:** 2024-01

**Startup:** ARSAA

**Producto:** DriveShare



| Nombre                            | Código       |
|-----------------------------------|--------------|
| ______| _________   |
| P____________ | _______ |
| ____________-| _________ |
| _______________        | ________   |
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
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | Leonel Alfaro Cumba <br>**TB1**<br>Completado del capítulo 1 del informe<br>| **TB1**<br>Nos reunimos como equipo y decidimos las partes del proyecto de las que se encargaría cada miembro. Asimismo logramos ganar la confianza de todos mostrando empatía y responsabilidad el uno con el otro|
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.     | Leonel Alfaro Cumba<br>**TB1**<br>Completado del capítulo 1 del informe<br>   | <br>**TB1**<br>Aprendimos a usar GitHub y GitHub Desktop. Además, entendimos cómo hacer commits en esta herramienta y cómo nos podrán ayudar en el desarrollo de este proyecto.<br>|



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
| ||  |
|  || |
|  Carlos Andres Rojas Ccama  |![Foto Carlor andres](https://github.com/AppWeb-Grupo3/informe/assets/89095594/c14e0c6e-bcc4-41fa-810c-4379e9b2ac64)   |Mi nombre es Carlos Andres Rojas Ccama, estudio la carrera de Ingeniería de Software. Mi carrera consiste en crear softwares inteligentes y sistemas informáticos usando un lenguaje de programación con lógica, asociado a la tecnología, herramientas para el diseño, mantenimiento de software, etc. Me considero una persona responsable y colaborativo como ayudar a las personas y dar ideas, especialmente en grupos. En este trabajo en equipo se requiere dar una buena comunicación, por ello, siempre daré mi opinión y escuchar las opiniones de mis compañeros con respeto. |
| Leonel Alfaro Cumba                 |![FotoLeonel](https://github.com/AppWeb-Grupo3/informe/assets/89095594/5b77db63-ca8e-4e81-a98d-83f550c2d46a)|Estudiante de Ingeniería de Software con gran interés en la tecnología y la innovación. Motivado por ampliar conocimientos y desarrollarse constantemente.|
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

<br>
<br>

## 1.3 Segmentos objetivo

**Se identificó dos  segmentos objetivos**


- Personas mayores de 18 años con licencia de conducir interesadas en encontrar alquileres de automóviles a tarifas justas y transparentes, que se ajusten a su presupuesto.

- Personas mayores de 18 años que tengan por lo menos un vehículo legalmente registrado y documentado, y deseen alquilarlo de forma segura a través de plataformas digitales.











