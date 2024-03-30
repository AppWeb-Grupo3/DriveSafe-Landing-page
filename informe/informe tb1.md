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








