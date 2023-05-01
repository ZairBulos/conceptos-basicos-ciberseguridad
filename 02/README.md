# Descripción de los conceptos de criptografía 🔑🔐	

La criptografía es fundamental para proteger la confidencialidad, la integridad y la disponibilidad de la información, así como para defenderse de los ciberataques. A lo largo de este módulo, conocerá los distintos elementos de la criptografía y su aplicación en la ciberseguridad.

### Objetivos de aprendizaje:

* Describir algunos de los conceptos básicos de la criptografía
* Describir el cifrado y sus usos en la ciberseguridad
* Describir el hashing y la firma digital
* Describir el concepto y el uso de certificados digitales

<hr/>

## Introducción

Las palabras "criptografía" y "cifrado" pueden hacer pensar en espías y operaciones clandestinas, o en piratas informáticos sentados en habitaciones sin ventanas. Sin embargo, gran parte del mundo en línea moderno actual no sería posible sin estos dos conceptos.

La criptografía y el cifrado son los pilares de cualquier buena solución de ciberseguridad. Por ejemplo, ayudan a mantener los mensajes de correo electrónico a salvo de miradas indiscretas y protegen los pagos en línea.

A medida que continúe su recorrido por el mundo de la ciberseguridad, verá cómo usamos la criptografía y el cifrado para protegernos en las actividades cotidianas.

<hr/>

## Descripción de la criptografía

El deseo de mantener cierta información en secreto nos ha acompañado desde que aprendimos a comunicarnos. A lo largo de la historia, hemos desarrollado nuevos métodos y formas de comunicarnos y, a su vez, ha crecido la necesidad de compartir secretos con amigos y aliados.

### Definición de criptografía

El término "criptografía", derivado de la palabra griega "*kryptos*", que significa *oculto* o *secreto*, hace referencia a la aplicación de una comunicación segura en cualquier forma entre un remitente y un destinatario. Normalmente, la criptografía se usa para ocultar el significado de un mensaje escrito, pero también se puede aplicar a imágenes.

El primer uso conocido de la criptografía se remonta al antiguo Egipto y al uso de jeroglíficos complejos. Uno de los primeros cifrados utilizados para proteger las comunicaciones militares provino del emperador romano Julio César.

Estos dos ejemplos muestran claramente que la criptografía tiene muchos usos y no se limita al mundo digital. Sin embargo, desde esos humildes orígenes, hay una cosa que está clara: la criptografía es ahora un requisito fundamental para ayudar a proteger nuestro planeta conectado digitalmente.

* Cada vez que se usa un explorador para acceder, por ejemplo, a una dirección HTTPS, a una tienda minorista en línea, a una cuenta bancaria o incluso a este sitio de Learn, los elementos de criptografía preservan la seguridad y la confidencialidad de las interacciones.
* Cada vez que conecta un dispositivo de forma inalámbrica a un enrutador para acceder a Internet, la criptografía ayuda a protegerlo.
* Se puede usar también para proteger los archivos del almacenamiento externo o interno.
* Los smartphones han cambiado la forma en que nos comunicamos, desde llamadas de vídeo y audio a mensajería de texto. La criptografía se usa para mantener la confidencialidad y la integridad de estas comunicaciones.

Al igual que con todos los sistemas, la criptografía tiene sus propios términos y fraseología. Dos de los términos más importantes son "texto no cifrado" y "texto cifrado".

* El término **texto no cifrado** representa cualquier mensaje, incluidos los documentos, la música, las imágenes, las películas, los datos y los programas informáticos, que se encuentre a la espera de una transformación criptográfica.
* Una vez que el texto no cifrado se convierte en un mensaje secreto, se denomina **texto cifrado**. Este término representa los datos cifrados o protegidos.

<hr/>

## Descripción del cifrado y sus usos en la ciberseguridad

Como hemos visto en la unidad anterior, la criptografía es el arte de ocultar el significado de un mensaje a todos los usuarios, menos al destinatario previsto. Esto requiere que el mensaje de texto no cifrado se transforme en texto cifrado. El mecanismo que hace esto posible se denomina "cifrado".

Los métodos usados para cifrar un mensaje han evolucionado a lo largo de miles de años, desde el intercambio de una letra por otra hasta dispositivos mecánicos más elaborados, como la máquina Enigma.

El cifrado ahora tiene lugar en el mundo digital. Se usan equipos y matemáticas para combinar números primos altos aleatorios con el fin de crear claves que se emplean tanto en el cifrado simétrico como en el asimétrico.

### ¿Qué es el cifrado?

El cifrado es el mecanismo por el que los mensajes de texto no cifrado se convierten en texto cifrado ilegible. El uso del cifrado mejora la *confidencialidad* de los datos que se comparten con el destinatario, ya sea un amigo, un compañero de trabajo o una empresa.

El descifrado es el mecanismo por el que el destinatario de un mensaje de texto cifrado puede volver a convertirlo en texto no cifrado legible.

Para facilitar los procesos de cifrado y descifrado, debe usar una clave de cifrado secreta. Esta clave es muy parecida a la que usaría para abrir el coche o la puerta de su casa. Las claves de cifrado pueden ser de dos tipos:

* Claves simétricas
* Claves asimétricas

#### Claves simétricas

El cifrado de claves simétricas se basa en la idea de usar la misma **clave criptográfica** tanto para el *cifrado* del mensaje de texto no cifrado como el *descifrado* del mensaje de texto cifrado. Esto hace que el método de cifrado sea rápido y proporciona un grado de confidencialidad en cuanto a la seguridad del texto cifrado.

Con este método de cifrado, la clave criptográfica se trata como un *secreto compartido* entre dos o más partes. El secreto debe protegerse cuidadosamente para evitar que lo encuentre una persona con malas intenciones. Todas las partes deben tener la misma clave criptográfica para poder enviar mensajes seguros. La distribución de la clave representa uno de los desafíos asociados al cifrado simétrico.

Imagine un grupo u organización en el que cada individuo necesite la capacidad de comunicarse de forma segura con otra persona. Si el grupo consta de tres individuos, solo necesita tres claves.

![symmetric-encryption](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/symmetric-encryption.png)

Ahora, imaginemos el caso de una organización con solo 100 empleados en la que cada persona necesite comunicarse de forma segura con todas las demás. En este caso, es necesario crear, compartir y administrar de forma segura 4950 claves. Por último, imaginemos una organización gubernamental con 1000 empleados donde cada individuo necesite comunicarse de forma segura. Se necesitan 499 500 claves. Este crecimiento se puede expresar con la fórmula `p x (p-1)/2`, donde "p" es el número de personas que necesitan comunicarse.

A medida que crece el número de personas de la organización, el número de claves aumenta significativamente. Esto hace que la administración y la distribución seguras de las claves secretas, que se usan en el cifrado simétrico, sean difíciles y costosas.

#### Cifrado asimétrico o de clave pública

El cifrado asimétrico se desarrolló en los años 70. Aborda la distribución y la proliferación seguras de claves asociadas al cifrado simétrico.

El cifrado asimétrico cambió la forma en la que se compartían las claves criptográficas. En lugar de una clave de cifrado, una clave asimétrica se compone de dos elementos: una **clave privada** y una **clave pública**, que forman un **par de claves**. La clave pública, como su nombre sugiere, se puede compartir con cualquier persona, por lo que ahorra a particulares y organizaciones tener que preocuparse por su distribución segura.

La clave privada debe protegerse. Solo la supervisará la persona que haya generado el par de claves y no se compartirá con nadie. Un usuario que necesite cifrar un mensaje usará la clave pública y solo la persona que tenga la clave privada podrá descifrarlo.

![key-pair-generation](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/key-pair-generation.png)

El cifrado asimétrico, con su uso de claves públicas y privadas, elimina la molestia de tener que distribuir de forma segura las claves. Este concepto también aborda la proliferación de claves que vimos cuando hablamos del cifrado simétrico. Piense en el ejemplo de la organización gubernamental de 1000 empleados en la que cada individuo debe poder comunicarse de forma segura. Con el cifrado asimétrico, cada persona generará un par de claves, lo que dará como resultado 2000 claves. Con el cifrado simétrico, se habrían requerido 450 000 claves.

##### ¿Cómo funciona el cifrado asimétrico?

Aunque los algoritmos y las matemáticas que respaldan el cifrado asimétrico son complejos, el principio de su funcionamiento es relativamente sencillo.

Supongamos que tenemos dos personas, Quincy y Mónica, que necesitan comunicarse de forma segura y privada. Mediante el uso de las herramientas de software disponibles, cada una de ellas crea su propio par de claves.

Lo primero que harán es compartir sus **claves públicas** la una con la otra. Dado que las claves públicas no son secretas, pueden intercambiarlas por correo electrónico.

![asymmetric-public-key-sharing](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/asymmetric-public-key-sharing.png)

Cuando Quincy quiere enviar un mensaje protegido a Mónica, usa su clave pública para cifrar el texto no cifrado y crear el texto cifrado. A continuación, Quincy enviará el texto cifrado a Mónica por el medio que quiera; por ejemplo, por correo electrónico. Cuando Mónica reciba el texto cifrado, usará su clave privada para descifrarlo y lo volverá a convertir en texto no cifrado.

![asymmetric-encryption-process](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/asymmetric-encryption-process.png)

Cuando Mónica quiera responder, usará la **clave pública** de Quincy para cifrar el mensaje antes de enviarlo. Luego, Quincy usará su clave privada para descifrarlo.

Supongamos que a Eve le interesa conocer los mensajes que están intercambiando Quincy y Mónica. Eve intercepta un mensaje de texto cifrado que Quincy ha enviado a Mónica. Además, Eve conoce la clave pública de Mónica.

Dado que no conoce la clave privada de Mónica, no tiene forma de descifrar el texto cifrado. Si Eve intenta descifrar el texto cifrado con la clave pública de Mónica, verá texto incomprensible.

Dada la naturaleza del cifrado asimétrico, incluso aunque se conozca la clave pública, es imposible detectar la clave privada.

En este vídeo de dos minutos, se muestra cómo funcionan el cifrado simétrico y el asimétrico y cómo estos protegen los documentos de la lectura por parte de personas no autorizadas.

🔗 [Vídeo](https://www.microsoft.com/es-es/videoplayer/embed/RWNyAM?postJsllMsg=true&autoCaptions=es-es)

#### Diferentes tipos de cifrados

Hay varios tipos de cifrado simétrico y asimétrico y se inventan nuevas versiones constantemente. Estos son algunos de los que puede encontrarse:

* **Data Encryption Standard (DES)** y **Triple DES**. Se trata de uno de los primeros estándares de cifrado simétricos que se usaron.
* **Advanced encryption standard (AES)**. AES reemplazó al cifrado DES y Triple DES, y se sigue usando mucho en la actualidad.
* **RSA**. Se trata de uno de los primeros estándares de cifrado asimétrico que se usaron y del que actualmente se siguen utilizando variaciones.

### ¿Dónde se usa el cifrado?

El cifrado se usa en todo el mundo y en casi todos los ámbitos de la vida, desde para hacer una llamada con el móvil hasta para usar la tarjeta de crédito para una compra en una tienda. El cifrado se usa aún más al navegar por Internet.

*Exploración web*: es posible que se dé cuenta, pero cada vez que va a un sitio web cuya dirección comienza por "https" o se muestra un icono de candado, se está usando el cifrado. Si observa la barra de direcciones de esta página web, verá que comienza por "https://". Del mismo modo, cuando se conecte a su banco a través de la Web o realice una compra en línea en la que proporcione información confidencial, como un número de tarjeta de crédito, deberá asegurarse de que aparezca "https://" en la barra de direcciones.

*Cifrado de dispositivos*: muchos sistemas operativos proporcionan herramientas para habilitar el cifrado de unidades de disco duro y dispositivos portátiles. Por ejemplo, Windows BitLocker, una característica del sistema operativo Windows, proporciona cifrado para el disco duro del equipo o las unidades portátiles que se puedan conectar en el puerto USB.

*Aplicaciones de mensajería*: algunas de las aplicaciones de mensajería conocidas y disponibles habitualmente cifran los mensajes.

*Comunicaciones móviles*: independientemente de si usa un smartphone u otro dispositivo de comunicaciones móviles, se usa el cifrado para registrarlo de forma segura en el mástil o la torre de telecomunicaciones que haya más cerca. Esto garantiza que siempre tenga la mejor intensidad de señal.

<hr/>

## Descripción del hashing y su aplicación en la firma digital

Hasta ahora, ha visto cómo se usa la criptografía, mediante el uso del cifrado, para proteger los mensajes de miradas indiscretas. La criptografía también se usa para comprobar que los datos, como los documentos y las imágenes, no se hayan alterado. Esto se realiza a través de un proceso denominado "hashing".

### ¿Qué es el hashing?

El hashing utiliza un algoritmo, también conocido como función hash para convertir el texto original en un valor de longitud fija único. Esto se denomina "valor hash". Cada vez que se aplica un algoritmo hash al mismo texto mediante el mismo algoritmo, se genera el mismo valor hash. Ese hash se puede usar como identificador único de los datos asociados.

![hashing-function-example](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/hashing-function-example.png)

El hashing es diferente del cifrado, ya que no usa claves, y el valor al que se aplica el algoritmo hash no puede descifrarse para convertirse en el valor original.

Existen muchos tipos de funciones hash. Uno que es conocido y que puede que escuche en las conversaciones con profesionales de seguridad es el algoritmo hash seguro (SHA). SHA es una familia de algoritmos hash en la que cada uno funciona de forma diferente. No entraremos en detalles en este contenido, pero uno de los SHA más usados es el SHA-256, que genera un valor hash de 256 bits de longitud.

### ¿Qué es una firma digital?

Una aplicación común del hashing es la firma digital. Al igual que una firma manuscrita, una firma digital valida que el documento lleva la firma que procede realmente de la persona que lo firmó. Además, las firmas digitales se usan para validar que el documento no se haya alterado.

#### ¿Cómo funciona una firma digital?

Una firma digital siempre será única para cada persona que firme un documento, de forma muy parecida a una firma manuscrita. Todas las firmas digitales usan un par de claves asimétricas: la privada y la pública.

Con un servicio de firma digital, Mónica puede asignar una firma digital al documento para demostrar que este no ha cambiado. Al firmar el documento, se crea un hash con marca de tiempo. A continuación, este hash se cifra mediante la clave privada de Mónica. A continuación, el servicio de firma anexa el hash al documento original, que no está cifrado. Por último, tanto el documento firmado digitalmente como la clave pública de Mónica se envían a Victoria.

Cuando esta última recibe el documento firmado digitalmente, usa el mismo servicio de firma digital para extraer el hash de Mónica del documento y generar un hash nuevo para el documento de texto no cifrado original. A continuación, con la clave pública de Mónica, se descifra el hash cifrado. Si el hash descifrado de Mónica coincide con el que creó Victoria para el documento, la firma digital será válida. Y así Victoria sabrá que el documento no se ha alterado.

En el siguiente vídeo de dos minutos verá cómo funcionan las firmas digitales y cómo se muestran estas si se ha alterado un documento.

🔗 [Vídeo](https://www.microsoft.com/es-es/videoplayer/embed/RWNvVP?postJsllMsg=true&autoCaptions=es-es)

La firma digital requiere el uso de un servicio de firma digital. Muchas empresas ofrecen esta funcionalidad. Dos de los más populares son DocuSign y Adobe Sign.

<hr/>

## Descripción de los certificados digitales

La criptografía tiene muchas aplicaciones en el mundo moderno actual. Ha visto cómo el cifrado puede garantizar la confidencialidad de los mensajes. También ha aprendido cómo se usa el hash en firmas digitales para comprobar que un mensaje no se ha alterado. En esta unidad, obtendrá información sobre los certificados digitales y cómo proporcionan una capa adicional de seguridad.

Los certificados abordan la posibilidad de que una persona poco ética intercepte, modifique o falsifique mensajes, algo que puede ocurrir en la comunicación digital.

Básicamente, un certificado digital es una credencial emitida por una **entidad de certificación** (CA) que se usa para comprobar la identidad de la persona o entidad a la que se emite el certificado, que se denomina firmante. En este sentido, un certificado digital es como un pasaporte u otra credencial de identidad emitida por una autoridad de confianza o una agencia gubernamental para comprobar una identidad. Los datos de un certificado incluyen información sobre el firmante y su clave pública de su par de claves pública y privada, y han sido comprobados por la CA.

Para obtener un certificado digital, la persona o entidad envía una solicitud de certificación a una CA de confianza. Los detalles de la identidad del solicitante y su clave pública, del par de claves pública y privada generadas a partir de una herramienta disponible, se incluyen en la solicitud de certificado. En algunos casos, el solicitante puede pedir que la CA emita un par de claves en su nombre como parte de la solicitud. En cualquier caso, la entidad o persona siempre mantiene en secreto la clave privada. La CA revisa toda la información de identidad enviada en la solicitud para determinar si cumple los criterios para emitir un certificado. Si la CA aprueba la solicitud, firma y emite un certificado que contiene información sobre el firmante y su clave pública.

La duración de un certificado digital tiende a ser de un año, después del cual expira. Cuando esto sucede, se muestra un mensaje de advertencia sobre los certificados expirados. La advertencia indica que no se puede confirmar la identidad del firmante.

Una aplicación común de los certificados digitales, que es visible para el usuario, está en la comunicación basada en web. Los certificados digitales se emplean en sitios web que usan la comunicación *HTTPS* segura, que se denota mediante un icono de un candado en la barra de direcciones del explorador. Al seleccionar el candado en la barra de direcciones, se pueden elegir varias opciones y obtener información adicional.

![digital-certificates-step-1-inline](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/digital-certificates-step-1-inline.png)

Al seleccionar "La conexión es segura", se proporciona información sobre la conexión, como se muestra en la imagen siguiente.

![digital-certificates-step-2-inline](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/digital-certificates-step-2-inline.png)

Al seleccionar el icono de certificado, se proporcionan detalles sobre el certificado digital.

![digital-certificates-step-3-inline](https://learn.microsoft.com/es-es/training/wwl-sci/describe-concepts-of-cryptography/media/digital-certificates-step-3-inline.png)

### ¿Por qué necesitamos certificados digitales?

En una unidad anterior, describimos el proceso de cifrado asimétrico y cómo se usan los pares de claves pública y privada. En el ejemplo, Quincy y Monica quieren comunicarse de forma segura, así que cada uno genera su par de claves con software al que se puede acceder fácilmente. Monica y Quincy comparten su clave pública entre sí, pero mantienen en secreto su clave privada. Cuando Quincy quiere enviale un mensaje seguro a Monica, utiliza la clave pública de Monica para cifrar y enviar el mensaje. A su vez, Monica utiliza su clave privada para descifrar el mensaje.

El uso del cifrado asimétrico, descrito en el ejemplo, garantiza la confidencialidad del mensaje. Dado que las claves públicas son públicas, no hay nada que confirme que la clave pública que usó Quincy proviene realmente de Monica. Del mismo modo, no hay nada que confirme que fue Quincy quien, efectivamente, envió el mensaje. Existe la posibilidad de que una persona poco ética intercepte, altere o falsifique los mensajes. Los certificados digitales desempeñan un papel importante a la hora de abordar este riesgo.

Supongamos que una CA de confianza le ha emitido a Monica un certificado digital y que lo comparte con Quincy. El certificado vincula la identidad de Monica con la clave pública. Dado que Quincy usa la clave pública del certificado de Monica, Quincy está seguro de que la clave pública procede de Monica y solo la clave privada de Monica descifrará el mensaje.

Supongamos que Quincy también ha obtenido un certificado digital a través de una CA de confianza. Quincy usa su clave privada para firmar digitalmente el mensaje. Quincy envía el mensaje firmado a Monica junto con el certificado digital que contiene su clave pública. El certificado digital vincula la identidad de Quincy a la clave pública, por lo que el uso de la clave pública del certificado sirve para comprobar que el mensaje no se ha alterado y verifica que el mensaje procede de Quincy. Sin el certificado digital, una firma digital solo sirve para comprobar que el mensaje no se ha alterado.

<hr/>

## Resumen

La criptografía es fundamental para proteger la confidencialidad, la integridad y la disponibilidad de la información. También sirve para defenderse de los ciberataques.

En nuestro recorrido por la criptografía y el cifrado, ha visto cómo los mensajes secretos han evolucionado desde el cifrado simétrico hasta la aplicación moderna del cifrado de claves asimétricas en el correo electrónico y la ciberseguridad en línea.

A continuación, ha visto cómo el hashing y las firmas digitales usan el cifrado para validar la identidad y la autenticidad del mensaje y el contenido que se envía. Por último, ahora entiende por qué los certificados son esenciales para mantener una buena ciberseguridad.
