
Si no sabes qué es eduroam, este es el lugar idóneo, la FAQ (preguntas frecuentes) de eduroam:

[toc]

### ¿Qué es eduroam?

eduroam es una [iniciativa a nivel internacional](https://www.eduroam.org) que pretende crear un espacio único de movilidad dentro del ámbito académico. eduroam pone el foco en la seguridad del usuario, manteniendo a la vez la facilidad de uso.

eduroam ES, es el nombre que recibe la iniciativa en España, y es operado por [RedIRIS](https://www.rediris.es), donde también se coordinan a las organizaciones participantes en dicha iniciativa en nuestro país. Este espacio único de movilidad agrupa a un amplio grupo de organizaciones que en base a una política de uso y una serie de requerimientos tecnológicos y funcionales, permiten que sus usuarios puedan desplazarse entre ellas, disponiendo en todo momento de servicios móviles que estos pudieran necesitar. 

El objetivo último es que los usuarios al llegar a otra organización dispongan, de la manera más transparente posible, conexión segura a Internet, acceso a servicios y recursos de su organización origen, así como acceso a servicios y recursos de la organización que en ese momento les acoge.

### ¿Cómo puedo saber si puedo conectarme a eduroam?

Necesitarás saber si la organización a la que perteneces ya está en eduroam. Puedes encontrar un listado de todas las instituciones en España [en este mismo sitio web](https://www.eduroam.es/instituciones.es.php). Aparte, necesitarás un dispositivo que soporte WPA/WPA2 Enterprise y que permita configurar el tipo de autenticación soportado por tu organización.

Si tu organización no está en eduroam, pero se trata de una [institución perteneciente](https://www.rediris.es/rediris/instituciones/lista/) a la red académica, te aconsejamos solicites al servicio de informática de tu organización que se unan.

### ¿Dónde puedo conectarme a eduroam?

Puedes encontrar [mapas mostrándote las ubicaciones](https://monitor.eduroam.org/map_service_loc.php) donde encontrar eduroam tanto en España, como en el resto de países donde está disponible.

### ¿Cuál es el tipo de autenticación que soporta mi organización?

Deberás consultarlo a tu institución. Es muy posible que tu institución haga uso de la herramienta [eduroam CAT](https://cat.eduroam.org), que permite una configuración segura que hayan preparado para ti los administradores de tu organización.

Con carácter general, **debes seguir las instrucciones que facilite tu institución**. Recomendamos en particular que cualquier duda que puedas tener, tanto cuando estás en tu propio campus o edificio, como si te encuentras fuera en otra organización, la dirijas siempre al personal técnico de tu propia institución. Es posible que si te encuentras fuera de tu organización puedas recibir soporte, pero es preferible ser siempre atendido por tu propia institución.

### Mi organización no dice nada sobre el dispositivo o sistema operativo con el que quiero conectarme, pero en otra organización he visto que se puede, ¿me puedo conectar yo también?

Dependerá del dispositivo, sistema operativo y del tipo de autenticación que soporte tu organización.

Un dispositivo que soporte PEAP, pero no EAP-TTLS no te permitirá conectarte si tu institución no soporta PEAP (o al contrario). Los dispositivos en general sólo soportan un subconjunto de modos EAP, por lo que es esencial que un técnico compruebe la compatibilidad. 

**Lo mejor es que consultes con el personal técnico de tu propia institución. Una configuración incorrecta, aparte de un funcionamiento deficiente, puede poner en riesgo los datos de tu cuenta.**

### ¿Por qué mi organización no soporta el tipo de autenticación de mi dispositivo?

Cada organización ha elegido sus modos de autenticación en función a cómo se adaptan estos a la infraestructura que ya tenían para dar soporte a la autenticación de sus usuarios en general (correo, aplicaciones web, campus virtuales, plataformas de e-learning,...).

Hay varios factores que habrán influido, tales como la seguridad o el coste, pero en cualquier caso, deberías plantear más bien la pregunta inversa: ¿por qué mi dispositivo no soporta el método de autenticación que me ofrece mi organización?

### ¿Por qué en mi nuevo dispositivo no puedo conectarme a la red eduroam?

En una gran mayoría de casos, sobre todo en el caso de portátiles, móviles y tabletas, debería haber compatibilidad. Es preferible siempre seguir el procedimiento que indique tu organización, así como hacer uso de instaladores oficiales, si te los proporciona.

Determinados dispositivos es posible que puedan conectarse sólo si son compatibles con los métodos de autenticación que soporta tu institución, si bien en determinadas ocasiones no será posible una configuración automática (deberá realizarse de manera manual), e incluso a veces no podrá realizarse una configuración fiable o segura del todo, por limitaciones del dispositivo.

También es posible, aunque poco probable, que exista algún tipo de incompatibilidad entre el dispositivo y la red.

En todos estos casos, **es preferible siempre consultar con el soporte técnico para recibir asesoramiento, antes de realizar una configuración que pueda poner en riesgo tu cuenta**.

### ¿Es la red eduroam segura?

Sí. eduroam provee mecanismos para que el usuario pueda en todo momento facilitar sus credenciales allá donde se conecte, y estas se transmitan de manera segura a través de Internet. Esto sin embargo no excluye que se puedan realizar ataques a clientes que estén mal configurados.

Por otro lado, hay que tener en cuenta que la conexión a Internet, una vez el usuario se ha identificado para tener acceso a la misma, ofrece un nivel de seguridad equivalente a cualquier conexión a Internet, por tanto deberán tomarse las medidas habituales de protección del dispositivo que recomiende el fabricante o desarrollador del sistema operativo que utiliza el usuario.

### He oído que las credenciales de mi universidad pueden filtrarse a atacantes bajo determinadas circunstancias. ¿de qué va esto?

El modelo de seguridad de eduroam está bien meditado y ha sido extensamente estudiado (puedes consultar por ejemplo la sección sobre seguridad en la [RFC 7593](https://datatracker.ietf.org/doc/html/rfc7593#page-29)). Tus credenciales están bien protegidas siempre que tu dispositivo esté correctamente configurado; esta configuración correcta es por tanto crucial. Siempre que los parámetros de configuración necesarios estén correctamente configurados, cualquiera de los métodos de autenticación usados habitualmente en eduroam (PEAP, TTLS-PAP, EAP-TLS) es seguro.

Tu proveedor de identidad eduroam te proporciona como mínimo unas instrucciones de instalación que permiten una configuración correcta y segura – la parte más crítica de estas, es la que permite configurar tu dispositivo para confiar en una Autoridad de Certificación (CA) y el nombre del servidor del proveedor de identidad-.

Muchos proveedores de identidad eduroam van un paso más lejos y te proporcionan programas de instalación o ficheros de configuración que contienen la información de seguridad relevante, a través de un proceso de instalación sencillo. Uno de estos programas es "[eduroam CAT](https://cat.eduroam.org)" - comprueba si tu institución está listada.

**Haz uso de los programas de instalación o instrucciones de configuración proporcionadas por tu proveedor de identidad eduroam para estar a salvo de posibles ataques.**

Si no sigues las instrucciones de configuración, o en el caso improbable de que el proveedor de identidad no te las proporcione, entonces los datos de la cuenta que usas para acceder a eduroam estarán en riesgo de ataques denominados Man-in-the-middle. Para los proveedores de identidad, no proporcionar suficientes instrucciones de configuración está en contra de la política de participación. Desde eduroam ES agradeceremos que nos notifiques en estos casos.

PD: este tipo de problemas no es específico de eduroam, cualquier despliegue de redes inalámbricas de tipo Enterprise está en la misma situación.

### ¿Cuáles son las normas de seguridad mínimas que debo seguir al conectarme a eduroam?

Podrían resumirse en sólo tres puntos:

* Nunca facilites tus credenciales eduroam a través de un portal web. eduroam utiliza tecnología 802.1x, y sus usuarios no deberían facilitar sus credenciales en portales web (salvo que estés en tu propia institución, y esta así te lo haya indicado). 
* Nunca confíes en un certificado del que no tengas garantías de su validez. Generalmente el software utilizado para conectarte (conocido como suplicante) te avisará cuando el certificado de tu organización presente algún problema. Si esto sucede, te recomendamos que contactes con los responsables de eduroam en tu organización y les comentes este tipo de incidencias. 
* En general, sigue las normas habituales de protección de tu equipo de cara a conectarte a la red (mantén actualizado tu equipo, instala un antivirus o cortafuegos si lo precisas, no visites webs que podrían dañar tu equipo, etc...).

### La conexión a eduroam me va lenta, ¿qué puedo hacer?

El que el identificador de la red sea eduroam no debería influir en la velocidad que obtengas al conectarte. Lo más habitual es que exista un problema de saturación de la red en el lugar desde el que te conectas, pero podrían existir otros problemas que habría que descartar, como interferencias, o algún problema técnico en la infraestructura de red inalámbrica. 

Lo más aconsejable en estos casos es que contactes con el servicio de informática de tu organización y les plantees el problema, indicándoles el lugar y horas a las que has notado la lentitud en la conexión a Internet. 
