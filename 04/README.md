# Describir las amenazas de red y las mitigaciones 📶⚠️

Las redes constituyen la columna vertebral de nuestro mundo conectado digitalmente. También representan un punto de entrada para los ciberataques. En este módulo, aprenderá sobre las amenazas a la seguridad de la red y cómo mitigarlas.

### Objetivos de aprendizaje:

* Describir los conceptos básicos sobre redes
* Describir las amenazas a la seguridad de la red
* Describir formas de proteger la red
* Describir formas de conectarse y comunicarse de forma segura a través de una red

<hr/>

## Introducción

La necesidad de comunicar y compartir conocimientos ha estado con nosotros desde la primera vez que aprendimos a hacer marcas en una superficie. A medida que hemos crecido y hemos pasado de asentamientos a pueblos y ciudades, también lo ha hecho el tamaño de la red de comunicación necesaria para ayudar a compartir noticias e ideas. Desde un jinete que entregaba una carta a una ciudad vecina, hasta la invención del telegrama y, finalmente, Internet y el correo electrónico, hemos construido redes más grandes y complejas. En la actualidad, el mundo es un lugar mucho más pequeño gracias a la red más grande del mundo, Internet.

Proteger la red es esencial en el moderno mundo en línea de hoy en día, donde la información es la nueva moneda de cambio. Cada día, miles de ciberataques amenazan a las redes. En su mayor parte, estos ataques se frustran, pero de vez en cuando, los titulares de las noticias informan sobre un robo de datos.

Aquí descubrirá los diferentes tipos de redes que existen, los medios por los que se conecta a ellas y cómo se mueven los datos en una red. Tendrá una idea de los tipos de ataques que los ciberdelincuentes utilizarán para entrar en una red, y de las herramientas disponibles para ayudarle a detenerlos.

<hr/>

## Describir los distintos tipos de redes

En el mundo moderno actual, las redes existen en todas partes. Las redes de inicio conectan su portátil, equipo, televisión, consola de juegos, smartphones, tabletas y dispositivos de Internet de las cosas (IoT). Esto les permite comunicarse entre sí y con Internet. En un negocio, ya sea una humilde organización que funciona en un garaje o empresas de mayor envergadura, las redes son la columna vertebral que les permite funcionar y compartir datos, ideas y recursos.

Las redes se utilizan para acceder a información de todo tipo, desde las fotos que comparte con sus amigos, hasta información confidencial como las transacciones bancarias y de tarjetas de crédito. La aplicación bancaria del dispositivo móvil usa varias redes para llegar al banco. A continuación, navegará por la red del banco para llegar a sus detalles.

### ¿Qué es una red?

Una red es una agrupación de componentes físicos interconectados que funcionan juntos para proporcionar una columna vertebral sin fisuras para que todos sus dispositivos se comuniquen. La nube e Internet pueden parecer intangibles, pero incluso tienen raíces físicas. Aunque hay docenas de elementos que ayudan a definir una red, los que es más probable que encuentre son: enrutadores, conmutadores, firewalls, puntos de acceso y centros de conectividad. Aunque la mayoría de ellos quedan fuera del ámbito de esta unidad, hay dos que merecen ser destacados.

* El **conmutador** es el bloque de creación fundamental de una red moderna. Permite que varios dispositivos se comuniquen entre sí.
* El **enrutador** permite que distintas redes se comuniquen entre sí.

![switch-router](https://learn.microsoft.com/es-es/training/wwl-sci/describe-network-based-threats-mitigations/media/switch-router.png)

Es posible que haya oído hablar de diferentes tipos de redes, como redes inalámbricas y redes de área local. Sin embargo, fundamentalmente, todas ellas entran en una de las dos categorías siguientes:

* Una **red privada** es aquella en la que se requiere un nivel de autenticación y autorización para acceder a dispositivos y recursos, como la puede encontrar en su lugar de trabajo.
* Una **red pública**, como Internet, está abierta a cualquier usuario.

#### Conexión a la red

Con independencia del tipo de red que use, existen varias maneras diferentes de conectarse a ella.

* La conexión **cableada** o **Ethernet** sigue siendo la manera más común de conectarse a la red de una oficina. Para ello, hace falta un cable de red físico para conectar el equipo de escritorio o portátil a un conmutador de la red.
* Una conexión **inalámbrica** permite que el dispositivo se conecte a la red mediante Wi-Fi. Se usa normalmente en casa o en grandes lugares públicos.
* Una conexión **Bluetooth** conecta un dispositivo de corto alcance al método de comunicación del dispositivo. Los dispositivos pequeños, como los podómetros, los auriculares y los relojes inteligentes, tienden a usar Bluetooth.

### La topología cliente-servidor

Aunque las redes permiten que los dispositivos o las aplicaciones se comuniquen entre sí, una de las implementaciones de red más comunes se conoce como topología cliente-servidor. En este modelo, el cliente puede ser uno o varios dispositivos o aplicaciones en un dispositivo que quiera hacer algo. El servidor es responsable de procesar cada solicitud de cliente y de devolver una respuesta.

![client-server](https://learn.microsoft.com/es-es/training/wwl-sci/describe-network-based-threats-mitigations/media/client-server.png)

Un ejemplo del modelo cliente-servidor es cuando se usa un smartphone o una tableta para acceder a un servicio de streaming digital. El dispositivo es el cliente, que realiza una solicitud al servidor de streaming para acceder al programa de televisión o a la película que quiere ver. El servidor responde transmitiendo el contenido al dispositivo. Otro ejemplo es cuando se usa el explorador para acceder al contenido desde Internet.

<hr/>

## Descripción de cómo se mueven los datos por una red

Una red existirá cuando tenga dos o más dispositivos que compartan datos. Como se ha visto en la unidad anterior, una red se compone de muchas partes físicas diferentes que trabajan juntas para garantizar que los datos lleguen a donde se necesitan. Esta transmisión de datos a través de una red está habilitada por un conjunto de protocolos de comunicación, a menudo denominado TCP/IP. Se denomina por los dos protocolos principales: el protocolo de control de transmisión (TCP), que controla la conexión entre dos dispositivos, y el protocolo de Internet (IP), que es responsable de enrutar la información a través de la red.

Todas las redes del planeta comparten y mueven datos cada segundo del día. Estos datos pueden tener todo tipo de forma y tamaño, desde un simple mensaje hasta imágenes e incluso las películas que se transmiten a su hogar.

### El datagrama o paquete

Existen redes para facilitar la comunicación entre dispositivos o sistemas. Sea cual sea el tamaño de los datos, todo debe dividirse en fragmentos pequeños y uniformes. Estos fragmentos se denominan datagramas, pero también se conocen más comúnmente como paquetes.

Imagine que quiere transmitir una película al dispositivo. Dado el tamaño enorme de los datos implicados, el servidor de streaming no puede ofrecer toda la película de una sola vez. En su lugar, la película se divide en miles de millones de paquetes. Cada paquete contiene una pequeña parte de la película, que se envía al dispositivo. El dispositivo tiene que esperar hasta que se reciban suficientes paquetes para poder empezar a ver la película. En segundo plano, el servidor sigue enviando un flujo constante de paquetes a su dispositivo justo antes de lo que se muestra. Si la velocidad de red se ralentiza, es posible que los paquetes no lleguen a tiempo. Es posible que la imagen que vea se desvirtúe o bloquee y que haya lagunas en el sonido.

### Direcciones IP

Cuando quiera enviar una carta a un amigo, primero escribirá la carta antes de meterla en un sobre. A continuación, escribirá la dirección de su amigo en el sobre antes de enviarla. El servicio postal lo recoge y, después de pasar por varias oficinas de clasificación, finalmente se entrega.

Las redes funcionan de forma similar. El mensaje está contenido en el paquete, como un sobre. A continuación, se agregan al paquete las direcciones del remitente y del destinatario.

La función principal del protocolo de Internet (IP) es asegurarse de que todos los dispositivos de una red se puedan identificar de forma única. Para que un paquete se pueda enviar a través de la red, se le debe decir la dirección IP a dónde va y la dirección IP de dónde procede.

Actualmente hay dos estándares de dirección IP denominados IPv4 e IPv6. Los detalles están fuera del ámbito de este módulo, pero el tipo más común de dirección IP y con el que puede estar familiarizado es IPv4. Se trata de cuatro grupos de dígitos separados por un punto, por ejemplo: 127.100.0.1.

### DNS

Al igual que todos los dispositivos de una red necesitan una dirección IP única, cada sitio web de acceso público necesita su propia dirección IP. Podría usar la dirección IP para visitar su tienda, banco o servicio de vídeo de streaming en línea favoritos. Pero con tantos sitios web disponibles, esto sería difícil de recordar. En su lugar, puede escribir el nombre del servicio que busca en el explorador y este le llevará al sitio web que quiera. Todo esto es gracias al servicio de nombres de dominio o DNS.

El DNS contiene una tabla con el nombre del sitio web; por ejemplo, [microsoft.com](https://microsoft.com/), que se asigna a su dirección IP correspondiente. El explorador lo usa para encontrar el sitio web real de la misma manera que podría usar una libreta de teléfono para buscar un número de teléfono.

![dns-lookup-table](https://learn.microsoft.com/es-es/training/wwl-sci/describe-network-based-threats-mitigations/media/dns-lookup-table.png)

Cada vez que el dispositivo se conecta a Internet, usa un servidor DNS local para encontrar el nombre del sitio web que está buscando. Si el DNS no encuentra el sitio, comprueba otros servidores DNS. Si no se encuentra el sitio o se agota el tiempo de espera de la solicitud, recibirá un mensaje de error como "El servidor DNS no responde".

### Enrutamiento

Cuando se han agregado las direcciones IP al paquete, ya se puede transmitir a través de la red. Si la dirección IP existe en la red, el paquete se envía directamente al dispositivo. Sin embargo, si la dirección IP está fuera de la red, tendrá que pasar por un enrutador. Un enrutador es un dispositivo físico que conecta una red a otra.

Siguiendo con nuestro ejemplo de la carta, si su amigo solo estuviera a unas cuantas calles de distancia, podría decidir entregar el mensaje en mano. Su amigo está dentro de la red local.

Sin embargo, si su amigo está en otra ciudad, país o región, deberá enviarlo y dejar que el servicio postal lo entregue. En este caso, el servicio postal es el enrutador. Toma el mensaje de la red y, a continuación, busca la mejor ruta para llegar a la red de su amigo para su entrega.

### Animación de vídeo

En este breve vídeo de dos minutos, verá cómo las actividades diarias crean redes, desde hablar con sus amigos por teléfono hasta compartir correos electrónicos. A continuación, veremos cómo se desglosan los mensajes en paquetes que se pueden enviar a través de la red. Por último, verá cómo cada paquete de un mensaje se enruta a través de Internet para llegar a su destinatario.

🔗 [Vídeo](https://www.microsoft.com/es-es/videoplayer/embed/RWP56O?postJsllMsg=true&autoCaptions=es-es)

<hr/>

## Descripción de las amenazas a la seguridad de la red

Las redes son la columna vertebral de nuestro mundo moderno, ya que nos permiten comunicarnos, comprar, jugar y trabajar desde cualquier lugar. Permiten acceder a una gran cantidad de información no solo sobre nosotros mismos, sino también de las empresas. Esto las convierte en un objetivo principal para los ciberdelincuentes que ven la información como la nueva moneda de cambio. Una seguridad de red débil corre el riesgo de exponer los datos críticos sensibles y de dañar la confidencialidad, la disponibilidad y la integridad de los datos almacenados.

Comprender las amenazas es una parte fundamental de la creación de una red de seguridad fuerte.

### Ataques de red comunes

Las formas en que se pueden atacar las redes son demasiado numerosas como para detallarlas aquí. Veamos las más comunes:

*** Ataques de tipo "Man in the middle"** o **"eavesdropping":** este tipo de ataque puede producirse cuando los ciberdelincuentes comprometen o emulan rutas en la red, lo que les permite interceptar los paquetes de información. Se podría considerar como una forma de intervención telefónica. Los atacantes no solo roban datos, sino que ponen en peligro la integridad de estos.
* **Ataques de denegación de servicio distribuido (DDoS)**: el objetivo de un ataque DDoS es poner en peligro la disponibilidad de la red o del servicio de destino. Lo que hacen los atacantes es bombardear la red o el servicio objetivo con millones de peticiones simultáneas, procedentes de orígenes distribuidos por toda la red, lo que hace que se desborde y provoque su caída.

#### Animación de vídeo

En este breve vídeo, verá una simulación de cómo funciona cada uno de estos ataques. En el caso del ataque de tipo "Man in the middle", hemos elegido usar solo una ruta para simplificarlo. Con el ataque DDoS, se usan cientos de miles o incluso decenas de millones de equipos. Una vez más, por motivos de simplicidad, solo se muestran unos pocos.

🔗 [Vídeo](https://www.microsoft.com/es-es/videoplayer/embed/RWP56P?postJsllMsg=true&autoCaptions=es-es)

### Ataque DNS común

Un ataque DNS busca aprovechar los puntos débiles del servidor DNS, ya que estos servidores están diseñados para mejorar la eficacia y la facilidad de uso, y no con la seguridad en mente. Un ataque DNS común es el **envenenamiento de DNS**. En este tipo de ataque el atacante cambia las direcciones IP de las tablas de búsqueda DNS para desviar el tráfico de un sitio legítimo y dirigirlo a un sitio ilegítimo que puede contener vínculos malintencionados u otro malware.

### Ataques inalámbricos comunes

Las redes inalámbricas permiten que nuestros dispositivos se conecten fácilmente a redes de todas partes. En su casa, la red inalámbrica permite que su smartphone y sus dispositivos IoT siempre activos se conecten a Internet. La amplia disponibilidad de estas redes las convierte en el objetivo perfecto para los ciberdelincuentes. Hay muchas maneras diferentes de atacar una red inalámbrica:

* **Wardriving**: este término se popularizó en un par de películas de los 80. El atacante, que normalmente trabaja desde un vehículo, busca redes inalámbricas no seguras que tengan vulnerabilidades. La mayoría de los ataques de "wardriving" buscan usar la red para actividades delictivas, como la piratería de otros equipos y el robo de información personal.
* **Suplantación de zonas Wi-Fi**: es parecido a un ataque de tipo "Man in the middle". El atacante usa su portátil o un dispositivo conectado a él para ofrecer un punto de acceso de red que imita un punto de acceso original. Por ejemplo, si está en una cafetería y quiere acceder a Internet mediante su Wi-Fi de invitado, es posible que vea un par de puntos de acceso que tienen el nombre de la cafetería. Pero puede ocurrir que uno de ellos proceda de un actor malintencionado. Una vez que se haya conectado al punto de acceso falso, todo lo que haga a través de la red se puede interceptar. También permite que el ciberdelincuente le dirija a sitios web poco seguros o capture sus datos privados.

### Ataque Bluetooth

Se ha producido un crecimiento de los dispositivos Bluetooth, desde los relojes inteligentes y los dispositivos de audio hasta la comunicación entre dispositivos. Los ataques a las redes Bluetooth son menos comunes que los que sufren las redes inalámbricas, principalmente porque el atacante debe estar dentro del alcance del dispositivo, pero sigue siendo un vector de ataque válido. Un ataque bluejacking es donde un atacante envía mensajes no solicitados a cualquier dispositivo que tenga habilitado el Bluetooth y que esté dentro de su alcance. El ataque de tipo Bluejacking es similar a cuando alguien llama a la puerta y, a continuación, se marcha antes de que pueda responder. Es principalmente molesto.

<hr/>

## Protección de su red

La protección de redes es una parte esencial de una directiva de seguridad sólida. Como vimos en la unidad anterior, hay muchas maneras de atacar una red. No existe una solución única que proteja su red; sin embargo, la mayoría de estos ataques pueden mitigarse mediante una combinación de soluciones de hardware y software.

### Cómo un firewall protege la red

Un firewall suele ser la primera línea de defensa de la red. Se trata de un dispositivo que se encuentra entre Internet y la red, y filtra todo el tráfico que sale y entra. Un firewall puede estar basado en software o hardware, pero para obtener la mejor protección, es recomendable tener ambos tipos. Un firewall supervisa el tráfico entrante y saliente. Mediante el uso de reglas de seguridad, mantendrá fuera el tráfico no deseado, al tiempo que permitirá que el tráfico autorizado pase libremente.

### Mantenimiento de una red en buen estado mediante un antivirus

Los virus vienen en todas las formas y tamaños y ninguno de ellos es bueno para los dispositivos y servidores que utilizan su red. Los ciberdelincuentes pueden utilizarlos con muchos fines, desde obtener las credenciales de los usuarios para poder acceder a su red, hasta tipos más dañinos que cifran todos los datos de un dispositivo o servidor a menos que se paguen grandes sumas de dinero. Igual que el cuerpo lucha contra un virus cuando se infecta, los equipos también pueden protegerse utilizando un software antivirus. Una vez instalado el software antivirus, se ejecuta en segundo plano y analiza todos los datos que llegan al dispositivo. Un virus detectado se eliminará automáticamente para evitar que el usuario lo ejecute accidentalmente.

Ahora puede tener un antivirus en la mayoría de sus dispositivos, incluidos servidores, equipos, tabletas, smartphones y cualquier otro dispositivo conectado a Internet.

### Mejora de la autenticación mediante el control de acceso de red

Aunque un firewall impide que los dispositivos no deseados accedan a la red, todavía necesita controlar los que quiere usar. El control de acceso a la red (NAC) es una solución de seguridad que controla el acceso de dispositivos y usuarios mediante la aplicación de directivas estrictas. Las directivas de dispositivo controlan lo que se puede hacer en la red y limitan lo que hace el usuario en un dispositivo. A través de NAC, puede mejorar la seguridad al solicitar que todos los usuarios usen la autenticación multifactor para iniciar sesión en la red. NAC le permite definir los dispositivos y usuarios que pueden acceder a los recursos de red, lo que reduce las amenazas y detiene el acceso no autorizado.

### División de la red en partes

Cada habitación de su casa tiene un propósito diferente, como la cocina, el salón, la sala de estar, el estudio, las habitaciones y los baños. Puede controlar el acceso a cada una de estas estancias colocando cierres digitales en todas las puertas. Cuando llegue un invitado, puede darle una llave que le permita acceder a estancias específicas de su casa. Puede hacer el mismo tipo de cosas con la red mediante el concepto de segmentación de red.

La segmentación de la red crea límites en torno a las operaciones o recursos críticos, de la misma manera que pondría a su equipo de finanzas en su propia oficina. Esto mejora la integridad de los recursos de red al garantizar que, incluso si se accede a la red de forma maliciosa, el atacante no pueda llegar a las áreas segmentadas.

### Protección de las conexiones mediante una red privada virtual

Una red privada virtual o VPN sirve de conexión dedicada y segura a través de Internet, entre un dispositivo y un servidor. Una conexión VPN cifra todo el tráfico de Internet y, luego, lo oculta para que sea imposible conocer la identidad del dispositivo original. Este tipo de conexión segura dificulta que los ciberdelincuentes realicen un seguimiento de sus actividades y obtengan datos. Si alguna vez se ha conectado a la red de trabajo desde una zona Wi-Fi pública, como el aeropuerto, lo más probable es que haya usado una VPN. La VPN establece una conexión segura a través de una red pública no segura. Los proveedores de VPN se han vuelto muy comunes no solo para escenarios de trabajo remotos, sino también para uso personal.

### Cifrado de la red inalámbrica

Tanto si configura un punto de acceso inalámbrico en su hogar como en su lugar de trabajo, la habilitación del cifrado es fundamental para protegerse de los ataques. El acceso protegido Wi-Fi 2 o WPA2 es el método de cifrado Wi-Fi que se usa de forma más habitual. Emplea el Estándar de cifrado avanzado (AES) para proteger la conexión.

<hr/>

## Resumen

Las redes constituyen la columna vertebral de nuestro mundo conectado digitalmente.  También representan un punto de entrada para los ciberataques.

En este módulo, hemos mostrado los distintos tipos de red que existen y cómo se conectaría a ellas. Ha aprendido los conceptos básicos de la comunicación de red y cómo los datos se mueven por una red de cualquier tamaño. Asimismo, ya se ha hecho una idea de las muchas formas que un ciberdelincuente puede usar para intentar entrar en una red, y de las herramientas disponibles para detenerlo.