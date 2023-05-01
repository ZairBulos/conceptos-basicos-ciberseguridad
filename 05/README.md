# Descripción de las amenazas basadas en dispositivos y los controles de seguridad 📱🚧

Los dispositivos conectados a Internet están en todas partes y los usuarios y las organizaciones dependen de ellos prácticamente en todas las facetas de la vida diaria y el uso empresarial. A lo largo de este módulo, aprenderá sobre amenazas de dispositivos y técnicas de mitigación.

### Objetivos de aprendizaje:

* Descripción de lo que el dispositivo sabe de usted
* Descripción de cómo son los dispositivos y se convierten en amenazas de ciberseguridad
* Descripción de cómo mitigar las amenazas relacionadas con el dispositivo

<hr/>

## Introducción

En nuestro mundo moderno, las personas y las organizaciones confían en los dispositivos conectados para satisfacer sus necesidades diarias más vitales. Los dispositivos acceden y almacenan datos empresariales y personales importantes a la vez que recopilan continuamente información sobre nosotros. Como resultado, los ciberdelincuentes tienen como destino dispositivos con el fin de obtener acceso y control no autorizados de datos valiosos, lo que crea estragos para usuarios y organizaciones. En este módulo, aprenderá a protegerse contra ciberataques basados en dispositivos para proteger los datos y mitigar el impacto en personas y organizaciones.

<hr/>

## Descripción de lo que el dispositivo sabe de usted

Los dispositivos son una parte importante del día a día y dependemos de ellos para muchas cosas. Para llevar a cabo su trabajo de forma eficaz, los dispositivos deben capturar, almacenar y compartir todo tipo de información confidencial sobre nosotros. Es posible que no nos demos cuenta de la medida en que usamos algunos dispositivos. Se han vuelto casi invisibles para nosotros. Con el fin de proteger la información confidencial a la que tienen acceso nuestros dispositivos, debemos tener en cuenta cómo los estamos usando, independientemente de si es de forma consciente o subconsciente.

### ¿Qué son los dispositivos?

Cuando escucha hablar de "dispositivos", ¿qué es lo primero que se le viene a la mente? Probablemente piense en los que está familiarizado, como el teléfono, un portátil o una tableta. Los dispositivos abarcan mucho más que esto. Por ejemplo:

* Unidades USB.
* Cualquier dispositivo conectado a la red doméstica, incluidos dispositivos de asistencia doméstica siempre conectados, impresoras, televisiones, dispositivos, cámaras de puerta, impresoras, etc.
* Paneles de automóviles, incluido el sistema de navegación y el control de voz.
* Zonas Wi-Fi.

Desde nuestras casas hasta nuestras oficinas y en todas partes, entramos en contacto con los dispositivos.

Echemos un vistazo a Kayla. En su casa está rodeada de dispositivos como su teléfono, un asistente para el hogar siempre activo, una tableta, un reloj inteligente, un enrutador inalámbrico, etc.

![living-room-labelled](https://learn.microsoft.com/es-es/training/wwl-sci/describe-device-based-threats-security-controls/media/living-room-labelled.png)

Kayla usa su coche para empezar a trabajar. Su automóvil tiene dispositivos integrados que puede usar mientras conduce, como el sistema de navegación y el punto de acceso inalámbrico que permite que su automóvil sirva como zona con cobertura inalámbrica móvil.

![car-zero-threats-labelled](https://learn.microsoft.com/es-es/training/wwl-sci/describe-device-based-threats-security-controls/media/car-zero-threats-labelled.png)

En el trabajo, el teléfono móvil y el equipo de Kayla se conectan de forma inalámbrica a la red de su organización para acceder a los recursos corporativos, incluida una impresora. También usa una unidad USB para almacenar determinados archivos y presentaciones.

![office-labelled](https://learn.microsoft.com/es-es/training/wwl-sci/describe-device-based-threats-security-controls/media/office-labelled.png)

En el contexto de ciberseguridad, todo lo que pueda tocar o con lo que pueda interactuar y que también pueda conectarse a otra cosa se considera un dispositivo. Es posible que esté usando un dispositivo conscientemente, como cuando usa el teléfono o cuando inserta una unidad USB en el portátil. O es posible que no se dé cuenta de que está usando un dispositivo porque una conexión se produce automáticamente, como cuando el teléfono se conecta a una zona Wi-Fi o porque lo configura una vez y luego se olvida de él, como el enrutador de la red doméstica.

Lo importante aquí es que debemos expandir lo que nos viene a la mente cuando pensemos en los dispositivos. Es importante hacerlo, ya que, en el contexto de ciberseguridad, todos ellos se pueden considerar vectores de amenazas, destinos para ciberdelincuentes que quieren causar daños.

### Dispositivos y datos

¿Por qué los dispositivos son una parte integral de nuestra vida? En gran medida, se debe a que recopilan y almacenan información, y nos mantienen conectados a otros dispositivos y servicios.

Piense en la comodidad de recibir información de tráfico en tiempo real en el teléfono móvil o en la molestia cuando llegan anuncios al dispositivo en función del historial de búsqueda en Internet. Este tipo de contenido de destino se envía porque nuestros dispositivos, a través de sus aplicaciones, recopilan enormes cantidades de información sobre nosotros. Esto incluye detalles de ubicación, sitios web visitados, cuánto tiempo permanecemos en un sitio y mucho más.

Los dispositivos conectados también nos permiten acceder fácilmente a la información y compartirla. Por ejemplo, probablemente haya usado el teléfono móvil para compartir fotos familiares con sus amigos, acceder a un documento de trabajo o pagar por algo en una tienda.

Tanto si usa el dispositivo por motivos personales como laborales, o ambos, la información accesible suele ser confidencial y privada. Los ciberdelincuentes lo saben e intentan poner en peligro los dispositivos como medio para acceder a los datos.

<hr/>

## Descripción de cómo los dispositivos se convierten en amenazas de ciberseguridad

Ha aprendido que estamos rodeados de dispositivos y que estos contienen todo tipo de información personal. También ha visto que los ciberdelincuentes se dirigirán a los dispositivos para obtener esta información. Pero, ¿cómo lo hacen?

### Dispositivos como vectores de amenazas

Aunque los dispositivos nos ayudan a realizar nuestro trabajo y nuestra vida diaria, también presentan oportunidades a los ciberdelincuentes que quieren causar daños. Esto se debe a que son vectores de amenazas: proporcionan diferentes formas en que los ciberdelincuentes pueden llevar a cabo ataques. Por ejemplo:

* **Teléfono, portátil o tableta**: la descarga de una aplicación malintencionada puede dar lugar a que el dispositivo esté contaminado con malware que puede filtrar datos confidenciales almacenados localmente, sin el conocimiento del usuario. Esto pone en peligro la confidencialidad y la integridad porque el ciberdelincuente ahora puede ver o modificar los datos.
* **Unidades USB**: los ciberdelincuentes pueden colocar software o archivos malintencionados en una unidad USB e insertarlo en un dispositivo como un portátil. Por ejemplo, la unidad podría ejecutar ransomware, lo que significa que la disponibilidad de los datos se ha puesto en peligro porque está bloqueada a cambio de un rescate.
* **Dispositivos de asistencia para el hogar siempre en marcha**: estos dispositivos siempre escuchan u observan. Un ciberdelincuente puede colocar software malintencionado en las tiendas de aplicaciones para estos dispositivos. Si un usuario lo instala, el ciberdelincuente podría, por ejemplo, atacar el dispositivo con spyware para grabar información de forma secreta y poner en peligro la confidencialidad de los datos. También podrían moverse lateralmente a otros dispositivos del hogar y poner en peligro sus datos.

Echemos un vistazo al siguiente vídeo para ver cómo los dispositivos que nos rodean pueden convertirse en vectores de amenazas:

🔗 [Vídeo](https://www.microsoft.com/es-es/videoplayer/embed/RWPb1R?postJsllMsg=true&autoCaptions=es-es)

### Vulnerabilidades del dispositivo

Un dispositivo puede verse comprometido debido a un estado deficiente, ya sea porque no tiene las actualizaciones de seguridad más recientes o porque tiene una autenticación débil. Si conecta este tipo de dispositivo a una zona Wi-Fi, por ejemplo, en un aeropuerto, es un objetivo fácil para los atacantes. Conocen las vulnerabilidades comunes de los dispositivos y las aplicaciones, así como la forma de obtener acceso no autorizado.

Una vez que un atacante consigue el acceso, puede ejecutar scripts para instalar malware. En la mayoría de los casos, el malware como puertas traseras o redes de robots (botnets) puede persistir en el dispositivo incluso después de actualizarlo. Esto provoca un daño mayor cuando un usuario conecta el dispositivo infectado a una red doméstica o de trabajo.

Algunos usuarios quieren obtener más control de sus dispositivos para la personalización u otros fines, y podrían recurrir al *jailbreaking*. Aquí es donde un usuario encuentra formas no oficiales de obtener acceso total a los sistemas principales de un dispositivo. El dispositivo se vuelve vulnerable porque esta acción podría sortear las medidas de seguridad. Esto ofrece a los ciberdelincuentes la oportunidad de proporcionar instrucciones falsas o software que ponga en peligro el dispositivo.

Cualquier dispositivo conectado puede ser un vector de amenaza si no está protegido correctamente. Una vez aprendido esto, podemos pensar en las distintas formas de proteger nuestros dispositivos.

<hr/>

## Descripción de cómo mitigar las amenazas relacionadas con el dispositivo

Hemos aprendido que los dispositivos pueden ser vectores de amenazas para los ciberdelincuentes que quieren obtener acceso o control de los datos para causar daños. Pero, ¿qué podemos hacer para protegernos?

### Medidas de mitigación

Hay diferentes maneras de proteger los dispositivos y los datos. Echemos un vistazo a algunas de las más comunes:

#### Protección de dispositivos

La protección de dispositivos es la forma en que se minimiza la posibilidad de que se puedan aprovechar las vulnerabilidades del dispositivo. Puede usar los siguientes métodos:

* Asegúrese de que los dispositivos tienen las actualizaciones de seguridad más recientes.
* Apague los dispositivos no usados.
* Habilite las características de seguridad admitidas a través del sistema operativo del dispositivo.
* Requiera PIN o biometría (como el reconocimiento facial) para acceder a los dispositivos.

Muchos sistemas operativos modernos tienen funcionalidades que admiten la protección de dispositivos. Por ejemplo, los usuarios pueden habilitar las actualizaciones automáticas del sistema operativo para ayudar a protegerse frente a vulnerabilidades conocidas y garantizar la disponibilidad continua del dispositivo. Las actualizaciones también admiten características de seguridad como la protección contra virus y amenazas, y la funcionalidad de firewall.

Estas características se habilitan fácilmente y pueden ayudar a proteger el dispositivo conectado para mantener la confidencialidad y la integridad de los datos accesibles.

#### Cifrado

El cifrado es un proceso que convierte la información del dispositivo en datos ininteligibles. La única manera de que esta información sea útil es invertir el cifrado. Esto requiere una contraseña o clave específica que solo está disponible para el usuario autorizado. Una vez cifrada la información, deja de ser útil sin la clave o contraseña correctas. De este modo, se mantiene la confidencialidad de los datos. El contenido de un dispositivo se puede cifrar de diversas maneras. Por ejemplo, algunos sistemas operativos incluyen herramientas integradas que le permiten cifrar la unidad de disco duro del equipo o cualquier dispositivo de almacenamiento al que se conecte.

#### Limitación del acceso al dispositivo de la aplicación

Hasta ahora, hemos visto las distintas formas en que las aplicaciones y los dispositivos podrían verse comprometidos y los pasos que puede seguir para mitigar las amenazas. Pero uno de los vectores de ataque más pasados por alto es cuando alguien usa directamente las aplicaciones en el dispositivo físico.

Supongamos que ha dejado el smartphone en el escritorio y se apresuró para ir a una reunión urgente. Una persona con malas intenciones podría usar el teléfono para acceder a cualquiera de las aplicaciones. Podría enviar mensajes, acceder a cuentas bancarias y realizar compras, todo ello mediante el uso de aplicaciones desde el dispositivo. Si es inteligente, dejará el dispositivo donde lo encontró, por lo que nunca lo sabrá.

Esta amenaza también se aplica al equipo de trabajo. Supongamos que está ocupado trabajando en datos importantes y confidenciales y se aleja del equipo para tomar un café. Un delincuente podría usar ahora el equipo no seguro para buscar datos confidenciales o secretos, o descargarlos en una unidad USB.

En estos dos casos, todo lo que haga el actor malintencionado se registrará y se realizará un seguimiento en su nombre. Hay pocas probabilidades de que se haga un seguimiento de las acciones para llegar hasta el actor malintencionado, y usted tendrá que afrontar las consecuencias y la limpieza.

La mejor manera de limitar el acceso a las aplicaciones es asegurarse de que se cierran o protegen cuando no se usan. Para ello, bloquee el dispositivo cuando se aparte de él. Si el dispositivo es lo suficientemente pequeño, lléveselo.

<hr/>

## Resumen

Ha aprendido que los dispositivos pueden ser la clave para la información fundamental sobre individuos y organizaciones, y que los ciberdelincuentes tienen como destino los dispositivos para obtener acceso no autorizado a los datos. Los ciberdelincuentes usan diversos medios para poner en peligro los dispositivos. Si se protegen los datos, se protegen las personas y las organizaciones. Ha aprendido a proteger los dispositivos a través de medidas de ciberseguridad que le ayudan a lograr y mantener la confidencialidad, la integridad y la disponibilidad de los datos.