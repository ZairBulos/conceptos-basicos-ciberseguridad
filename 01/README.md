# Descripción de amenazas, ataques y mitigaciones básicos de ciberseguridad 👾🚫

Los ciberataques afectan a personas y empresas a un ritmo alarmante. Estar informado sobre el panorama de amenazas en constante evolución y los tipos comunes de ataques, algo que es fundamental para aprender a protegerse frente a ataques.

### Objetivos de aprendizaje:

* Definir qué es la ciberseguridad
* Describir el panorama básico de amenazas
* Describir los diferentes tipos de malware
* Descripción de estrategias básicas de mitigación

<hr/>

## Introducción

En la actualidad, estamos inundados de informes de ciberataques y sus ramificaciones. Escuchamos hablar de ataques a cadenas de suministro globales que tienen consecuencias económicas importantes. Casi de forma rutinaria, observamos que los ciberdelincuentes han robado la información personal de millones de consumidores a través de plataformas que se usan a diario. A veces, incluso se habla de servicios sanitarios y gubernamentales vitales que sufren bloqueos y extorsiones a cambio de un rescate.

Los ciberataques evolucionan continuamente. La ciberseguridad es un campo importante, grande y en crecimiento en un mundo en el que las empresas y las instituciones compiten por trasladar y mantener sus negocios en línea. A lo largo de este módulo, conocerá los conceptos básicos sobre la ciberseguridad.

<hr/>

## Describir qué es la ciberseguridad

Las personas, las organizaciones y los gobiernos son víctimas habituales de los ciberataques. Constantemente escuchamos referencias a conceptos como ciberseguridad, ciberataques, ciberdelincuentes, etc. Todo esto puede parecer abrumador y difícil de entender. Para protegerse a sí mismo y a los usuarios que le rodean, deberá tener una comprensión básica de estos conceptos.

### ¿Qué es un ciberataque?

Un ciberataque se define normalmente como un intento de obtener acceso no autorizado a un equipo o sistema informático para causar daños. Pero solo pensar en equipos o sistemas informáticos, en el sentido tradicional, es una limitación. La realidad es que un ciberataque puede producirse en casi cualquier dispositivo digital moderno. El impacto puede abarcar desde molestias a un individuo hasta una alteración económica y social en todo el mundo.

Un atacante puede usar personas, equipos, teléfonos, aplicaciones, mensajes y procesos del sistema para llevar a cabo un ataque. Los individuos, las organizaciones, las instituciones y los gobiernos pueden ser víctimas de un ataque. Estos atacantes podrían hacer lo siguiente:

* Bloquear datos y procesos y exigir un rescate.
* Quitar información vital para causar daños graves.
* Robar información.
* Exponer públicamente información privada.
* Detener la ejecución de procesos y sistemas empresariales vitales para provocar interrupciones y errores de funcionamiento.

Con los ciberataques en constante evolución, es importante recordar que los atacantes no necesitan solo un equipo para llevar a cabo un ataque. Además, la naturaleza y el ámbito de los ataques pueden variar significativamente. Cualquier dispositivo o entidad conectado digitalmente se puede usar como parte de un ataque o estar sujeto a un ataque.

### ¿Qué es un ciberdelincuente?

Un ciberdelincuente es cualquier persona que lleva a cabo un ciberataque. Los ciberdelincuentes pueden ser:

* Una sola persona o un grupo de personas.
* Una organización de alquiler.
* Una entidad gubernamental.

Los ciberdelincuentes se pueden encontrar en cualquier lugar, incluso dentro de una organización o institución, para causar daños desde dentro.

### ¿Qué es la ciberseguridad?

La ciberseguridad hace referencia a tecnologías, procesos y aprendizaje que ayudan a proteger los sistemas, las redes, los programas y los datos frente a ciberataques, daños y accesos no autorizados. La ciberseguridad le permite lograr los siguientes objetivos:

![confidentiality-integrity-availability-triangle](https://learn.microsoft.com/es-es/training/wwl-sci/describe-basic-cybersecurity-threats-attacks-mitigations/media/confidentiality-integrity-availability-triangle.png)

* **Confidencialidad**: la información solo debe ser visible para las personas correctas.
* **Integridad**: la información solo deben cambiarla las personas o los procesos adecuados.
* **Disponibilidad**: la información debe ser visible y accesible siempre que sea necesario.

Esto se conoce normalmente como el *modelo de confidencialidad, integridad y disponibilidad* (CIA) en el contexto de la ciberseguridad. En el resto de este módulo, conocerá los tipos de ataques que usan los ciberdelincuentes para perturbar estos objetivos y causar daños. También verá algunas estrategias básicas de mitigación de amenazas.

<hr/>

## Describir el panorama de amenazas

Ya ha obtenido información sobre los ciberataques, los ciberdelincuentes y la ciberseguridad. Pero también deberá conocer los recursos que los ciberdelincuentes pueden usar para llevar a cabo ataques y lograr sus objetivos. Para ello, aprenderá conceptos como el panorama de amenazas, los vectores de ataque, las infracciones de seguridad, etc.

### ¿Qué es el panorama de amenazas?

Independientemente de si una organización es grande o pequeña, el panorama digital completo con el que interactúa representa un punto de entrada para un ciberataque. Estas pueden incluir:

* Cuentas de correo
* Cuentas de redes sociales
* Dispositivos móviles
* Infraestructura tecnológica de la organización
* Servicios en la nube
* Personas

Colectivamente, se conocen como el *panorama de amenazas*. Observe que el panorama de amenazas puede abarcar más que solo equipos y teléfonos móviles. Puede incluir cualquier elemento cuya titularidad o administración recaiga o no en una organización. Como aprenderá a continuación, los delincuentes usarán cualquier recurso que puedan para montar y llevar a cabo un ataque.

### ¿Qué son los vectores de ataque?

Un vector de ataque es un punto de entrada o una ruta para que un atacante obtenga acceso a un sistema.

![attack-vectors](https://learn.microsoft.com/es-es/training/wwl-sci/describe-basic-cybersecurity-threats-attacks-mitigations/media/attack-vectors.png)

El correo electrónico quizá sea el vector de ataque más común. Los ciberdelincuentes enviarán correos electrónicos aparentemente legítimos que provocarán que los usuarios realicen alguna acción. Esto puede incluir la descarga de un archivo o la selección de un vínculo que pondrá en peligro su dispositivo. Otro vector de ataque común es a través de redes inalámbricas. Los agentes malintencionados suelen aprovechar las redes inalámbricas no seguras en aeropuertos o cafeterías, en busca de vulnerabilidades en los dispositivos de los usuarios que acceden a la red inalámbrica. La supervisión de cuentas de redes sociales o incluso el acceso a dispositivos que no están seguros son otras rutas de uso común para los ciberataques. Sin embargo, debe saber que los atacantes no solo se basan en estos vectores. Pueden usar una variedad de vectores de ataque menos obvios. Estos son algunos ejemplos:

* **Medios extraíbles**. Un atacante puede usar medios como unidades USB, cables inteligentes, tarjetas de almacenamiento y mucho más para poner en peligro un dispositivo. Por ejemplo, los atacantes pueden cargar código malintencionado en dispositivos USB que posteriormente se proporcionan a los usuarios como un obsequio gratuito o se dejan en espacios públicos para que alguien los encuentre. Cuando se conectan, se provoca el daño.
* **Explorador**. Los atacantes pueden usar sitios web malintencionados o extensiones del navegador para que los usuarios descarguen software malintencionado en sus dispositivos o cambien la configuración del explorador de un usuario. A continuación, el dispositivo puede verse comprometido, lo que proporciona un punto de entrada al sistema o a la red más amplios.
* **Servicios en la nube**. Las organizaciones dependen cada vez más de los servicios en la nube para el negocio y los procesos diarios. Los atacantes pueden poner en peligro servicios o recursos mal protegidos en la nube. Por ejemplo, un atacante podría poner en peligro una cuenta en un servicio en la nube y obtener el control de todos los recursos o servicios accesibles para esa cuenta. También podrían obtener acceso a otra cuenta incluso con más permisos.
* **Agentes internos**. Los empleados de una organización pueden actuar como un vector de ataque en un ciberataque, ya sea intencionadamente o no. Un empleado podría convertirse en la víctima de un ciberdelincuente que lo suplanta como una persona de autoridad para obtener acceso no autorizado a un sistema. Se trata de una forma de ataque de ingeniería social. En este escenario, el empleado actúa como un vector de ataque involuntario. Sin embargo, en algunos casos, un empleado con acceso autorizado puede usarlo para robar intencionadamente o causar daños.

### ¿Qué son las infracciones de seguridad?

Cualquier ataque que da lugar a que alguien obtenga acceso no autorizado a dispositivos, servicios o redes se considera una infracción de seguridad. Imagine una infracción de seguridad como similar a un allanamiento en el que un intruso (atacante) logra entrar en un edificio (un dispositivo, una aplicación o una red).

Las infracciones de seguridad tienen diferentes formas, entre las que se incluyen las siguientes:

#### Ataques de ingeniería social

Es habitual pensar que las infracciones de seguridad aprovechan algún error o vulnerabilidad en un servicio tecnológico o en parte de un equipo. Del mismo modo, podría pensar que las infracciones de seguridad solo se producen debido a vulnerabilidades en la tecnología. Pero ese no es el caso. Los atacantes pueden usar ataques de ingeniería social para aprovecharse de los usuarios o manipularlos con la intención de concederles acceso no autorizado a un sistema.

En la ingeniería social, los ataques de suplantación se producen cuando un usuario no autorizado (el atacante) pretende ganarse la confianza de un usuario autorizado al hacerse pasar por una persona de autoridad para acceder a un sistema a partir de alguna actividad fraudulenta. Por ejemplo, un ciberdelincuente podría hacerse pasar por un ingeniero de soporte técnico para conseguir que un usuario revele su contraseña para acceder a los sistemas de una organización.

#### Ataques del explorador

Ya sea en un escritorio, portátil o teléfono, los exploradores son una herramienta de acceso importante para Internet. Las vulnerabilidades de seguridad de un explorador pueden tener un impacto significativo debido a su generalización. Por ejemplo, suponga que un usuario está trabajando en un proyecto importante con una fecha límite inminente. Quiere averiguar cómo resolver un problema determinado para su proyecto. Encuentra un sitio web que cree que proporcionará una solución.

El sitio web pide al usuario que realice algunos cambios en la configuración del explorador para poder instalar un complemento. El usuario sigue las instrucciones del sitio web. Aunque no lo sabe, el explorador ahora está en peligro. Se trata de un ataque modificador del explorador, uno de los muchos tipos diferentes que usan los ciberdelincuentes. Un atacante ahora puede usar el explorador para robar información, supervisar el comportamiento del usuario o poner en peligro un dispositivo.

#### Ataques a contraseñas

Un ataque de contraseña es cuando alguien intenta usar la autenticación de una cuenta protegida con contraseña para obtener acceso no autorizado a un dispositivo o sistema. Los atacantes suelen usar software para acelerar el proceso de descifrar y adivinar contraseñas. Por ejemplo, suponga que un atacante ha descubierto de algún modo el nombre de usuario de alguien para su cuenta profesional.

A continuación, el atacante intenta una gran cantidad de combinaciones de contraseñas posibles para acceder a la cuenta del usuario. La contraseña solo tiene que ser correcta una vez para que el atacante obtenga acceso. Esto se conoce como un ataque por fuerza bruta y es una de las muchas maneras en que un ciberdelincuente puede usar ataques de contraseña.

### ¿Qué son las infracciones de datos?

Una infracción de datos es cuando un atacante logra acceder a los datos o controlarlos. Con el ejemplo del intruso, esto sería similar a esa persona que obtenía acceso a documentos vitales e información dentro del edificio o que los robaba:

![data-breach-v3](https://learn.microsoft.com/es-es/training/wwl-sci/describe-basic-cybersecurity-threats-attacks-mitigations/media/data-breach-v3.png)

Cuando un atacante logra cometer una infracción de seguridad, su objetivo serán los datos, porque representan información vital. Una seguridad deficiente de los datos puede provocar que un atacante obtenga acceso a los datos y los controle. Esto puede provocar consecuencias graves para la víctima, ya sea una persona, una organización o incluso un gobierno. Esto se debe a que los datos de la víctima podrían ser objeto de abusos de muchas maneras. Por ejemplo, se pueden retener como rescate o usarse para causar daños financieros o a la reputación.

<hr/>

## Descripción de malware

Ha escuchado hablar de términos como malware, virus y gusanos, entre otros. Pero, ¿qué significan? ¿Un gusano es un virus? ¿Qué hace el malware exactamente? Estos son solo algunos de los conceptos básicos que aprenderá en esta unidad.

### ¿Qué es el malware?

El malware procede de la combinación de las palabras malintencionado y software. Es un fragmento de software que usan los ciberdelincuentes para infectar los sistemas y llevar a cabo acciones dañinas. Esto podría incluir el robo de datos o la interrupción del uso y los procesos normales.

El malware tiene dos componentes principales:

* Mecanismo de propagación
* Carga

### ¿Qué es un mecanismo de propagación?

La propagación es la forma en que el malware se propaga entre uno o varios sistemas. Estos son algunos ejemplos de técnicas de propagación comunes:

![worms-virus-trojan-v3](https://learn.microsoft.com/es-es/training/wwl-sci/describe-basic-cybersecurity-threats-attacks-mitigations/media/worms-virus-trojan-v3.png)

#### Virus 🦠

La mayoría de nosotros ya estamos familiarizados con este término. Pero, ¿qué significa realmente? En primer lugar, vamos a pensar en los virus en términos no técnicos. En biología, por ejemplo, un virus entra en el cuerpo humano y, una vez dentro, puede propagarse y causar daños. Los virus basados en la tecnología dependen de alguna forma de acceso, específicamente una acción del usuario, para entrar en un sistema. Por ejemplo, un usuario podría descargar un archivo o conectar un dispositivo USB que contiene el virus que contamina el sistema. Esto es una infracción de seguridad.

#### Gusano 🐛

A diferencia de un virus, un gusano no necesita ninguna acción del usuario para propagarse por los sistemas. En su lugar, un gusano causa daños al encontrar sistemas vulnerables de los que se puede aprovechar. Una vez dentro, el gusano se puede propagar a otros sistemas conectados. Por ejemplo, un gusano podría infectar un dispositivo al aprovechar una vulnerabilidad en una aplicación que se ejecuta en él. A continuación, el gusano se puede propagar por otros dispositivos en la misma red y otras redes conectadas.

#### Troyano 🐴

Un ataque de caballo de Troya debe su nombre a la historia clásica, donde los soldados se escondían dentro de un caballo de madera que se ofrecía como un regalo a los troyanos. Cuando los troyanos llevaron el caballo de madera a su ciudad, los soldados salieron de su escondite y atacaron. En el contexto de la ciberseguridad, un troyano es un tipo de malware que pretende ser un componente de software original. Cuando un usuario instala el programa, puede pretender que funcione como se anuncia, pero el programa también realiza de forma secreta acciones malintencionadas, como robar información.

### ¿Qué es una carga?

La *carga* es la acción que realiza un fragmento de malware en un dispositivo o sistema infectado. Estos son algunos tipos comunes de carga:

* El **ransomware** es una carga que bloquea sistemas o datos hasta que la víctima paga un rescate. Supongamos que hay una vulnerabilidad no identificada en una red de dispositivos conectados. Un ciberdelincuente puede aprovechar esto para acceder a todos los archivos de esta red y cifrarlos después. A continuación, el atacante exige un rescate a cambio de descifrar los archivos. Podría amenazar con quitar todos los archivos si el rescate no se ha pagado en una fecha límite establecida.
* El **spyware** es un tipo de carga que espía un dispositivo o sistema. Por ejemplo, el malware puede instalar software de examen de teclado en el dispositivo de un usuario, recopilar detalles de contraseñas y transmitirlos al atacante, y todo sin que el usuario lo sepa.
* **Puertas traseras** es una carga que permite a un ciberdelincuente aprovechar una vulnerabilidad en un sistema o dispositivo para eludir las medidas de seguridad existentes y causar daños. Imagine que un ciberdelincuente se infiltra en una empresa de desarrollo de software y deja algún código que le permite realizar ataques. Esto se convierte en una puerta trasera que el ciberdelincuente podría usar para piratear la aplicación, el dispositivo en el que se ejecuta e incluso las redes y los sistemas de la organización y los clientes.
* **La red de robots (botnet)** es un tipo de carga que une un equipo, un servidor u otro dispositivo a una red de dispositivos infectados de forma similar que se pueden controlar de forma remota para llevar a cabo alguna acción fraudulenta. Una aplicación común de malware de red de robots (botnet) es la minería de datos de cifrado (a menudo denominada malware de minería de datos de cifrado). En este caso, el malware conecta un dispositivo a una red de robots (botnet) que consume la potencia informática del dispositivo para extraer o generar criptomonedas. Es posible que un usuario observe que su equipo se ejecuta más lentamente de lo normal y que empeora con los días.

<hr/>

## Descripción de estrategias básicas de mitigación

Ha aprendido que hay muchos tipos diferentes de ciberataques. Pero, ¿cómo puede a su organización frente a los ciberdelincuentes? Hay varias maneras diferentes de mantener a raya a los ciberdelincuentes, desde la autenticación multifactor hasta la mejora de la seguridad del explorador y la información y capacitación de los usuarios.

### ¿Qué es una estrategia de mitigación?

Una *estrategia de mitigación* es una medida o colección de pasos que una organización realiza para evitar un ciberataque o defenderse de él. Esto se hace normalmente mediante la implementación de directivas y procesos tecnológicos y organizativos diseñados para protegerse frente a ataques. Estas son algunas de las muchas estrategias de mitigación diferentes disponibles para una organización:

#### Autenticación multifactor

Tradicionalmente, si la contraseña o el nombre de usuario de alguien están en peligro, esto permite que un ciberdelincuente pueda obtener el control de la cuenta. Pero se introdujo la autenticación multifactor para combatir esto.

La autenticación multifactor funciona exigiendo a un usuario que proporcione varias formas de identificación para comprobar que es quien dice ser. La forma más común de identificación que se usa para comprobar o autenticar a un usuario es una contraseña. Esto representa algo que el usuario sabe.

Otros dos métodos de autenticación proporcionan algo que el usuario *es*, como una huella digital o un escaneo de retina (una forma biométrica de autenticación) o proporcionan algo que el usuario *tiene*, como un teléfono, una clave de hardware u otro dispositivo de confianza. La autenticación multifactor emplea dos o más de estas formas de prueba para comprobar un usuario válido.

Por ejemplo, un banco podría exigir que un usuario proporcione códigos de seguridad enviados a su dispositivo móvil, además de su nombre de usuario y contraseña, para acceder a su cuenta en línea.

#### Seguridad del explorador

Todos dependemos de los exploradores para acceder a Internet para trabajar y llevar a cabo nuestras tareas diarias. Como ha aprendido anteriormente, los atacantes pueden poner en peligro los exploradores poco seguros. Un usuario puede descargar un archivo malintencionado o instalar un complemento malintencionado que pueda poner en peligro el explorador, el dispositivo e incluso propagarse a los sistemas de una organización. Las organizaciones pueden protegerse frente a estos tipos de ataques mediante la implementación de directivas de seguridad que:

* Impiden la instalación de extensiones o complementos del navegador no autorizados.
* Solo permiten que los exploradores permitidos se instalen en dispositivos.
* Bloquean determinados sitios mediante filtros de contenido web.
* Mantienen actualizados los exploradores.

#### Educación de los usuarios

Los ataques de ingeniería social se basan en las vulnerabilidades de las personas para causar daños. Las organizaciones pueden defenderse contra los ataques de ingeniería social mediante la capacitación de su personal. Los usuarios deben aprender a reconocer contenido malintencionado que reciben o encuentran, y saber qué hacer cuando detectan algo sospechoso. Por ejemplo, las organizaciones pueden enseñar a los usuarios a:

* Identificar elementos sospechosos en un mensaje.
* No responder nunca a solicitudes externas de información personal.
* Bloquear dispositivos cuando no están en uso.
* Almacene, comparta y quite datos solo según las directivas de la organización.

#### Información sobre amenazas

El panorama de amenazas puede ser amplio. Las organizaciones pueden tener muchos vectores de ataque que son todos los posibles objetivos de los ciberdelincuentes. Esto significa que las organizaciones deben tomar tantas medidas como sea posible para supervisar, evitar, defenderse contra los ataques e incluso identificar posibles vulnerabilidades antes de que los ciberdelincuentes las usen para llevar a cabo ataques. En resumen, deben usar la inteligencia sobre amenazas.

La inteligencia sobre amenazas permite a una organización recopilar información sobre sistemas, detalles sobre vulnerabilidades, información sobre ataques, etc. En función del conocimiento que se tenga de esta información, la organización puede implementar directivas de seguridad, dispositivos, acceso de usuarios, etc., para defenderse contra los ciberataques. La colección de información para obtener conclusiones y responder a los ciberataques se conoce como inteligencia sobre amenazas.

Las organizaciones pueden usar soluciones tecnológicas para implementar inteligencia sobre amenazas en sus sistemas. A menudo se trata de soluciones inteligentes contra amenazas que pueden recopilar automáticamente información e incluso buscar ataques y vulnerabilidades y responder a ellos.

Estas son solo algunas de las estrategias de mitigación que las organizaciones pueden adoptar para protegerse frente a ciberataques. Las estrategias de mitigación permiten a una organización adoptar un enfoque sólido en relación con la ciberseguridad. Esto protegerá en última instancia la confidencialidad, integridad y disponibilidad de la información.

<hr/>

## Resumen

En este módulo, ha aprendido conceptos como ciberataques, ciberseguridad, panorama de amenazas y malware. También ha visto cómo mitigar los ciberataques.

Ha aprendido que los ciberdelincuentes usan ciberataques para obtener acceso o control no autorizados en dispositivos, sistemas y datos. A continuación, pueden poner en peligro la confidencialidad, integridad o disponibilidad de la información (el modelo CIA).

Además, ha visto que la ciberseguridad es la forma de proteger y mantener la confidencialidad, la integridad y la disponibilidad de la información. Esto se debe a que la ciberseguridad le permite implementar estrategias de mitigación que puede usar para protegerse frente a ciberataques.