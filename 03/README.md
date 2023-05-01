# Descripción de la autenticación y la autorización en ciberseguridad ✔️🔓	

La autenticación y la autorización seguras son una de las piedras angulares de la protección frente a las amenazas de ciberseguridad. Obtenga información sobre los ataques comunes basados en la identidad, los distintos métodos de autenticación y las formas de protegerse contra el acceso no autorizado.

### Objetivos de aprendizaje:

* Definir la autenticación
* Describir los ataques comunes basados en la autenticación
* Describir las técnicas de seguridad de autorización

<hr/>

## Introducción

Una buena ciberseguridad depende de numerosos factores para proporcionar la confianza y la garantía de que los datos están protegidos y se usan según lo previsto. La autenticación es uno de estos factores. Proporciona un mecanismo que le permite confiar en que una persona es realmente quien dice ser. Para ser eficaz, la autenticación debe ser sólida y sencilla de usar.

Cuando haya autenticado un usuario, deberá decidir qué puede hacer. La autorización concede a cada usuario un nivel específico de acceso a los datos y los recursos. Por lo general, a los usuarios se les deben conceder permisos suficientes para acceder a los recursos que necesitan.

Supongamos que está en el aeropuerto para coger un vuelo. Para poder obtener la tarjeta de embarque, debe demostrar quién es. Se presenta con su pasaporte y, si las identidades coinciden, ha superado el proceso de autenticación y recibe la tarjeta de embarque. Ahora que tiene una tarjeta de embarque, puede usarla para subir al avión. La tarjeta de embarque es la autorización, ya que solo le permitirá subir al avión que realiza el vuelo que ha reservado.

Mientras que la autenticación es la llave que abre la puerta, la autorización decide adónde puede ir y qué puede ver.

<hr/>

## Definir la autenticación

La autenticación es el proceso de demostrar que una persona es quien dice ser. Cuando alguien compra un artículo con una tarjeta de crédito, es posible que tenga que mostrar una forma adicional de identificación. De esta manera, demuestra que es la persona cuyo nombre aparece en la tarjeta. En este ejemplo, el usuario puede mostrar el DNI, que sirve como forma de autenticación y verifica su identidad.

Si quiere acceder a un equipo o un dispositivo, se encontrará con el mismo tipo de autenticación. Es posible que se le pida que escriba un nombre de usuario y una contraseña. El nombre de usuario indica quién es, pero no es suficiente por sí solo para concederle acceso. Cuando lo combina con la contraseña, que solo usted debe conocer, obtiene acceso a los sistemas. El nombre de usuario y la contraseña son una forma de autenticación.

Los métodos de autenticación sólida son esenciales para mantener una buena ciberseguridad y garantizar que solo los usuarios autorizados puedan obtener acceso a datos y recursos confidenciales.

Si bien la autenticación comprueba la identidad del usuario, no rige lo que puede hacer una vez que se ha autenticado. El control de lo que un usuario puede hacer se denomina autorización. Más adelante en este módulo veremos en qué consiste.

### Métodos de autenticación

La autenticación se puede dividir en tres tipos: algo que sabe, algo que tiene y algo que forma parte de usted.

* Algo que **sabe**, por ejemplo:
    - Contraseñas
    - Números PIN
    - Preguntas de seguridad
* Algo que **tiene**, por ejemplo:
    - Documentos de identidad
    - Llaves USB
    - Computers
    - Teléfonos móviles
* Algo que **forma parte** de usted, por ejemplo:
    - Una huella digital
    - Reconocimiento facial
    - Un examen de retina
    - Otras formas de identificación biométrica

La identificación biométrica se compone de características físicas que identifican de forma única a una persona.

![authentication-types](https://learn.microsoft.com/es-es/training/wwl-sci/describe-authentication-authorization-cybersecurity/media/authentication-types.png)

#### Autenticación de factor único

La autenticación de un solo factor es un sistema en el que solo se usa un tipo de autenticación, lo que lo convierte en el método menos seguro, pero el más sencillo.

Un ejemplo de este sistema sería cuando el usuario proporciona algo que sabe (como una contraseña) para autenticarse. Las contraseñas simples son fáciles de recordar, pero los delincuentes pueden piratearlas fácilmente. Las contraseñas complejas pueden parecer más seguras, pero son imposibles de recordar. Es muy probable que la persona escriba en algún sitio este tipo de contraseña, lo que hace que sea mucho menos segura.

Otro método de autenticación de un solo factor consiste en usar algo que tiene. Por ejemplo, puede usar el teléfono móvil para pagar por un artículo. Un servicio de tocar para pagar autentica al usuario a través de algo que tiene, pero no requiere otro método de comprobación.

Una característica biométrica (es decir, algo que forma parte de usted) se puede usar como método de autenticación de un solo factor, pero en algunos escenarios comunes no es necesariamente más segura. Piense, por ejemplo, en cuando usa la huella digital para desbloquear el teléfono móvil. Probablemente en alguna ocasión la huella digital no se reconocía fácilmente y se le ofrecía la opción de escribir un PIN. Esto puede hacer que resulte más fácil de adivinar. En la mayoría de los casos, las características biométricas se usan junto con otra forma de autenticación.

La autenticación de un solo factor es cómoda, pero no se considera adecuada para un sistema altamente seguro.

#### Autenticación multifactor

La autenticación multifactor es un sistema en el que se usan dos o incluso tres tipos de autenticación. Al proporcionar *algo que sabe*, *algo que tiene* y *algo que forma parte de usted*, la seguridad del sistema aumenta enormemente. Por ejemplo, en un sistema de autenticación multifactor que usa dos tipos de autenticaciones, es posible que se le pida una contraseña y, luego, se le envíe un número al teléfono móvil. Debe introducir este número, lo que demuestra que sabe la contraseña y tiene el teléfono móvil. Este es un procedimiento habitual cuando se usa la autenticación multifactor para acceder a una cuenta bancaria en línea. La autenticación multifactor reduce la probabilidad de que una persona con malas intenciones pueda obtener acceso a información confidencial.

Como ya se ha mencionado, la autenticación biométrica suele usarse junto con otro método de autenticación. Piense, por ejemplo, en un banco que tiene una zona protegida donde mantiene las cajas de seguridad de los clientes. Para que alguien pueda obtener acceso, normalmente primero se le pide que escriba correctamente una contraseña y que supere un examen de la huella digital.

La autenticación multifactor es un método primordial para que los usuarios y las organizaciones mejoren la seguridad. Debería ser el procedimiento predeterminado para la autenticación.

<hr/>

## Descripción de los ataques basados en la autenticación

Los ataques de autenticación se producen cuando alguien intenta robar las credenciales de una persona. Después, puede simular que es esa persona. Dado que un objetivo de este tipo de ataques es suplantar a un usuario legítimo, a menudo también se les puede denominar ataques de identidad. Entre los ataques comunes se incluyen los siguientes:

* Atacante por fuerza bruta
* Ataque de diccionario
* Relleno de credenciales
* Registro de claves
* Ingeniería social

#### Atacante por fuerza bruta

En un ataque por fuerza bruta, un delincuente intenta obtener acceso simplemente probando diferentes combinaciones de nombre de usuario y contraseña. Normalmente, los atacantes tienen herramientas que automatizan este proceso mediante el uso de millones de combinaciones de nombre de usuario y contraseña. Las contraseñas simples, con autenticación de un solo factor, son vulnerables a los ataques por fuerza bruta.

#### Ataque de diccionario

Un ataque por diccionario es una forma de ataque por fuerza bruta, en el que se aplica un diccionario de palabras de uso frecuente. Para evitar los ataques por diccionario, es importante usar símbolos, números y combinaciones de varias palabras en una contraseña.

#### Relleno de credenciales

El relleno de credenciales es un método de ataque que aprovecha el hecho de que numerosas personas usan el mismo nombre de usuario y contraseña en muchos sitios. Los atacantes usarán las credenciales robadas, normalmente obtenidas después de una vulneración de datos en un sitio, para intentar acceder a otras áreas. Los atacantes suelen usar herramientas de software para automatizar este proceso. Para evitar el relleno de credenciales, es importante no reutilizar las contraseñas y cambiarlas periódicamente, sobre todo después de una vulneración de seguridad.

#### Registro de claves

El registro de claves implica el uso de software malintencionado que registra pulsaciones de teclas. Con un registrador de claves, un atacante puede registrar (robar) combinaciones de nombre de usuario y contraseña, que luego se pueden usar para ataques de relleno de credenciales. Se trata de un ataque común en cibercafés o en cualquier lugar en el que se usen equipos compartidos. Para evitar el registro de claves, no instale software que no sea de confianza y use software de confianza para la detección de virus.

El registro de claves no se limita a los equipos informáticos. Supongamos que una persona malintencionada instala un dispositivo sobre el lector de tarjetas y el teclado de un cajero automático. Cuando usted inserta la tarjeta, pasa primero a través del lector de tarjetas de la persona malintencionada, que captura los detalles de la tarjeta antes de que se introduzca en el lector de tarjetas del cajero automático. Ahora, cuando introduzca su PIN con el teclado de la persona malintencionada, también obtendrá esta información.

#### Ingeniería social

La ingeniería social conlleva intentar que una persona revele información o realice una acción para hacer posible un ataque.

La mayoría de los ataques de autenticación implican la vulneración de equipos o el proceso de probar muchas combinaciones de credenciales. Los ataques de ingeniería social son diferentes, ya que aprovechan las vulnerabilidades de las personas. El atacante intenta ganarse la confianza del usuario legítimo y persuadirle para que divulgue información o realice una acción que posibilite causar daños o robar información.

Se pueden usar varias técnicas de ingeniería social para el robo de autenticación, entre las que se incluyen las siguientes:

* La **suplantación de identidad (phishing)** se produce cuando un atacante envía un correo electrónico aparentemente legítimo con el objetivo de lograr que un usuario revele sus credenciales de autenticación. Por ejemplo, puede parecer que un correo electrónico lo ha enviado el banco del usuario. Incluye un vínculo a lo que parece ser la página de inicio de sesión del banco, pero en realidad es un sitio falso. Cuando el usuario inicia sesión en el sitio falso, sus credenciales quedan a disposición del atacante. Existen diversas variantes de suplantación de identidad, incluido el phishing de objetivo definido, que suele estar dirigido a organizaciones, empresas o personas concretas.
* El **pretexto** es un método por el cual un atacante se gana la confianza de la víctima y le convence para que divulgue información segura. Después, puede usar estos datos para robar su identidad. Por ejemplo, un hacker podría llamarle por teléfono fingiendo ser del banco y pedirle su contraseña para comprobar su identidad. Otro método conlleva el uso de las redes sociales. Podrían pedirle que responda a una encuesta o un cuestionario con preguntas aparentemente aleatorias e inocentes que le harán revelar datos personales, o bien podrían enviarle un mensaje con un juego divertido, como crear el nombre de su grupo de pop imaginario con su lugar de nacimiento y el nombre de su primera mascota.
* El **baiting** es una forma de ataque en el que el delincuente ofrece una recompensa o un premio falsos para animar a la víctima a divulgar información segura.

<hr/>

## Describir las técnicas de seguridad de autorización

Cuando autentique a un usuario, tendrá que decidir adónde puede ir y qué se le permite ver y tocar. Este proceso se denomina autorización.

Supongamos que quiere pasar la noche en un hotel. Lo primero que hará es ir a la recepción para iniciar el "proceso de autenticación". Una vez que el recepcionista haya comprobado quién es, le dará una tarjeta-llave y ya podrá dirigirse a su habitación. Piense en la tarjeta-llave como el proceso de autorización. La tarjeta-llave solo le permitirá abrir las puertas y los ascensores a los que puede acceder, como la puerta de su habitación.

En términos de ciberseguridad, la autorización determina el nivel de acceso de una persona autenticada a los datos y los recursos. Existen diferentes técnicas de seguridad que las organizaciones usan para administrar la autorización.

#### Acceso condicional

Como su nombre indica, el acceso condicional implica el acceso con condiciones. Una manera de pensar en el acceso condicional es con instrucciones if-then. Si algo es cierto, se le concede acceso, pero si es falso, se le deniega.

Veamos cómo funcionaría esto en un escenario de IT. Cada vez más personas trabajan desde casa. Probablemente usan su equipo personal para acceder a contenido relacionado con el trabajo. Con el acceso condicional, una organización podría conceder acceso a un usuario autenticado a un sistema confidencial, como el de las nóminas, solo si se usan equipos corporativos seguros ubicados en su sede central. Si el usuario autenticado intenta acceder al sistema de nóminas desde un equipo personal en casa, se bloquearía el acceso.

#### Acceso con privilegios mínimos

El concepto de privilegio mínimo consiste en conceder a un usuario los derechos mínimos que necesita. Esto se aplica a todas las configuraciones relacionadas con la seguridad.

Por ejemplo, cuando sube a un avión, tiene acceso a la zona principal de la cabina para llegar a su puesto, pero no se permite que ningún pasajeros entre en la cabina del piloto. Además, si viaja con un billete de clase turista, solo podrá sentarse en esa zona. Para mejorar la seguridad, cada persona solo puede acceder a las áreas que necesita.

El mismo concepto se aplica en el contexto de la ciberseguridad. Piense en el caso de los usuarios que tienen acceso a una carpeta pública de una red. Si solo necesitan leer un archivo, se les debe conceder ese permiso específico.

Un usuario casi siempre se pondrá en contacto con el administrador si no tiene los derechos suficientes para desempeñar su rol. En cambio, rara vez le comunicará que tiene demasiados derechos. Así pues, el riesgo de ser demasiado cautelosos al asignar derechos de usuario es escaso.

Al implementar el acceso con privilegios mínimos, reducirá las acciones de un atacante si se produce una vulneración.

#### Desplazamiento lateral

Si un atacante obtiene acceso a un sistema, podría usar la cuenta en peligro para recopilar más información, que a su vez podría permitirle infiltrarse en otros sistemas u obtener acceso elevado. El atacante puede moverse por el sistema y buscar más recursos hasta alcanzar su objetivo. Dado que el atacante intentará moverse entre distintas secciones, es poco probable que el ataque final proceda de la cuenta en peligro inicial.

Piense en un edificio de oficinas en el que un delincuente supera el control de seguridad de la zona de recepción principal. Por lo general, podrá moverse por el resto del edificio y acceder a diferentes plantas y oficinas. Es importante proporcionar capas de seguridad adicionales para protegerse frente a intrusiones en áreas confidenciales.

Por ejemplo, muchos edificios de oficinas requieren un código de seguridad para acceder a las plantas en las que se encuentra el equipo ejecutivo. Todas las oficinas de esas plantas están cerradas y solo se permite el acceso a los empleados que disponen de una tarjeta especial. Es evidente que no quiere que un delincuente acceda a su edificio, pero si asume que podría producirse una vulneración y agrega capas de seguridad adicionales para protegerse contra este tipo de desplazamiento lateral, puede limitar los daños.

El mismo concepto se aplica en un escenario de IT. Debe partir de una autenticación segura para reducir la probabilidad de que un atacante acceda a los sistemas. Ningún sistema es infalible, pero puede proporcionar capas de seguridad adicionales. Estas medidas ayudarán a mitigar la probabilidad de que un atacante que entra en el sistema pueda acceder a otros recursos más confidenciales mediante el desplazamiento lateral.

#### Confianza cero

El término "Confianza cero" es habitual en ciberseguridad. Se trata de un método que mitiga los ataques cada vez más comunes que se producen hoy en día.

La Confianza cero es un modelo que permite a las organizaciones proporcionar acceso seguro a sus recursos, ya que nos enseña a "nunca confiar, siempre comprobar". Se basa en tres principios que emplean conceptos con los que ya está familiarizado.

* **Comprobar explícitamente**: con la Confianza cero, todas las solicitudes se autentican y autorizan por completo antes de conceder acceso. Las organizaciones pueden implementar la autenticación multifactor y el acceso condicional para asegurarse de que todas las solicitudes se comprueban explícitamente.
* **Usar el acceso con privilegios mínimos**: como ya se mencionó en esta unidad, el concepto de privilegios mínimos consiste en autorizar a un usuario solamente con los derechos mínimos que necesita. Esto limita los daños que puede hacer un usuario y reduce los desplazamientos laterales.
* **Asumir la vulneración**: al asumir que se ha producido o que se producirá una vulneración, una organización puede planear mejor los niveles de seguridad adicionales. Esto minimiza el radio de vulneración de un atacante y evita el desplazamiento lateral.

Al emplear un modelo de seguridad de Confianza cero, las organizaciones pueden adaptarse mejor a un área de trabajo distribuida moderna que proporciona acceso seguro a los recursos.

<hr/>

## Resumen

La autenticación y la autorización seguras son una de las piedras angulares de la protección frente a las amenazas de ciberseguridad en el trabajo y en el hogar. Cuando se implementan correctamente, la autenticación y la autorización pueden ayudar a protegerse contra las personas malintencionadas, al mismo tiempo que se mantiene la confidencialidad de los datos y los recursos.

Como ya ha visto en este módulo, la autenticación se centra en identificar correctamente a un usuario. Ha aprendido que la autenticación multifactor se basa en tres conceptos (algo que tiene, algo que forma parte de usted y algo que sabe) para proporcionar un medio sólido para demostrar que es quien dice ser. Ha descubierto que los ciberdelincuentes aprovecharán cualquier oportunidad para obtener información que les permita suplantarle, desde el registro de claves hasta la ingeniería social. Por último, ha visto que la autorización controla y limita adónde pueden ir los usuarios y qué datos y recursos pueden ver. Juntas, la autenticación y la autorización mejoran en gran medida la confidencialidad de los datos y reducen la probabilidad de que los datos acaben en las manos equivocadas.