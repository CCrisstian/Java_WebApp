<h1 align="center">Jakarta EE</h1>
<p>Jakarta EE (anteriormente conocido como Java EE) es una plataforma de desarrollo para la creación de aplicaciones empresariales en Java. Proporciona un conjunto de especificaciones y APIs que simplifican el desarrollo de aplicaciones empresariales robustas y escalables. Jakarta EE incluye tecnologías como servlets, JSP (JavaServer Pages), EJB (Enterprise JavaBeans), JPA (Java Persistence API), JMS (Java Message Service) y muchas otras.</p>
<p>JAKARTA EE Características:</p>

-	<b>Componentes web</b>: Proporciona tecnologías como Servlets y JSP para desarrollar aplicaciones web dinámicas.
-	<b>EJB 4.0</b>: Enterprise JavaBeans ofrece un modelo de componentes para crear aplicaciones empresariales distribuidas.
-	<b>Interoperabilidad</b>: Enterprise JavaBeans ofrece un modelo de componentes para crear aplicaciones empresariales distribuidas.
-	<b>Comunicación remota</b>: Permite la comunicación entre componentes distribuidos en diferentes máquinas.
-	<b>Control de la concurrencia</b>: Permite la comunicación entre componentes distribuidos en diferentes máquinas.
-	<b>Seguridad</b>: Ofrece herramientas y APIs para implementar medidas de seguridad en las aplicaciones, como autenticación y autorización.
-	<b>Transaccionalidad</b>: Permite administrar transacciones para garantizar la integridad de los datos en entornos distribuidos.
-	<b>Eventos utilizando JMS (Java Messaging Service)</b>: Utiliza Java Messaging Service para enviar y recibir mensajes entre componentes de una aplicación.
-	<b>Persistencia JPA 3.0</b>: Java Persistence API ofrece un conjunto de APIs para trabajar con bases de datos de manera más sencilla y transparente.
-	<b>Servicios de nombres y de directorio JNDI</b>: Java Naming and Directory Interface proporciona un mecanismo estándar para acceder a servicios de nombres y de directorio.
-	<b>Inyección de Dependencia CDI 3.0</b>: Contexts and Dependency Injection permite la inyección de dependencias de manera automática, facilitando la configuración y gestión de componentes.
-	<b>JAX-WS SOAP</b>: Java API for XML Web Services permite la creación de servicios web basados en el protocolo SOAP.
-	<b>JAX-RS Rest</b>: Java API for RESTful Web Services facilita la creación de servicios web RESTful utilizando el protocolo HTTP de manera sencilla y eficiente.

<p>Especificaciones principales de Jakarta EE 9:</p>

-	<b>Jakarta Servlet 5.0</b>: Especificación que define cómo los servlets interactúan con las solicitudes HTTP, permitiendo el desarrollo de aplicaciones web dinámicas en Java.
-	<b>Jakarta Server Pages 3.0</b>: Define la tecnología para crear páginas web dinámicas utilizando Java como lenguaje de script.
-	<b>Jakarta Server Faces 3.0</b>: Proporciona un marco de trabajo para construir interfaces de usuario web basadas en componentes reutilizables.
-	<b>Jakarta Contexts and Dependency Injection 3.0</b>: Estándar para la inyección de dependencias y la administración de contextos en aplicaciones empresariales.
-	<b>Jakarta Managed Beans 2.0</b>: Define el modelo de programación de JavaBeans administrados para la creación y gestión de componentes.
-	<b>Jakarta Persistence 3.0</b>: Ofrece un conjunto de APIs para trabajar con bases de datos de manera más sencilla y transparente en aplicaciones empresariales.
-	<b>Jakarta Transactions 2.0</b>: Especificación para administrar transacciones en aplicaciones empresariales distribuidas.
-	<b>Jakarta Enterprise Java Beans 4.0 Lite</b>: Proporciona un modelo de componentes para crear aplicaciones empresariales distribuidas de manera simplificada.
-	<b>Jakarta RESTFul Web Services 3.0</b>: Define estándares para el desarrollo de servicios web RESTful utilizando Java.
-	<b>Jakarta MVC</b>: Modelo-Vista-Controlador para el desarrollo de aplicaciones web.
-	<b>Jakarta Messaging</b>: Especificación para la creación y gestión de sistemas de mensajería en aplicaciones empresariales.
-	<b>Jakarta Authentication y Authorization 2.0</b>: Establece estándares para la autenticación y autorización en aplicaciones Jakarta EE.
-	<b>Jakarta Mail</b>: Define APIs para enviar y recibir correos electrónicos desde aplicaciones Java.

<h1 align="center">Apache Tomcat</h1>
<p>Tomcat es un servidor web de código abierto y contenedor de servlets desarrollado por la Apache Software Foundation. Se utiliza principalmente para ejecutar aplicaciones web basadas en Java, implementando las especificaciones de servlets y JSP (JavaServer Pages).</p>
<p>Como servidor web, Tomcat puede manejar solicitudes HTTP y servir contenido estático, como páginas HTML, imágenes y archivos CSS, además de ejecutar servlets y JSP para generar contenido dinámico.</p>
<p>Es ampliamente utilizado en la industria para alojar aplicaciones web de diversos tamaños y complejidades, desde sitios web pequeños hasta aplicaciones empresariales complejas.</p>
<p>Además de ser un servidor web, Tomcat también funciona como un contenedor de servlets, lo que significa que puede administrar y ejecutar servlets y JSP de manera eficiente. Esto permite a los desarrolladores crear aplicaciones web dinámicas utilizando Java y las tecnologías relacionadas de manera efectiva.</p>
<p>Algunas de las principales características y ventajas de Apache Tomcat son:</p>

-	<b>Implementación de Especificaciones Servlet y JSP</b>: Tomcat implementa las especificaciones de servlets y JSP, lo que significa que puede ejecutar aplicaciones web desarrolladas utilizando estas tecnologías estándar de Java.
-	<b>Servidor Web Ligero</b>: Tomcat es conocido por ser ligero y de bajo consumo de recursos, lo que lo hace ideal para ejecutar aplicaciones web en entornos con recursos limitados.
-	<b>Código Abierto</b>: Tomcat es un proyecto de código abierto bajo la Apache License, lo que significa que es gratuito para su uso y modificación, y cuenta con una amplia comunidad de desarrolladores que contribuyen a su desarrollo y mejora continua.
-	<b>Facilidad de Configuración</b>: Tomcat ofrece una configuración flexible y fácil de administrar a través de archivos de configuración XML simples y claros. Esto facilita la personalización del entorno de ejecución según las necesidades del proyecto.
-	<b>Administración y Monitoreo</b>: Tomcat proporciona una serie de herramientas y utilidades para administrar y monitorear el servidor, incluidas interfaces gráficas y de línea de comandos para realizar tareas de administración como la implementación de aplicaciones, la configuración del servidor y la supervisión del rendimiento.
-	<b>Compatibilidad con Java EE</b>: Aunque Tomcat es principalmente un contenedor de servlets y JSP, también puede integrarse con otras tecnologías de Java EE, como JDBC para la conexión a bases de datos, JNDI para la gestión de recursos y JTA para la transaccionalidad, lo que lo hace adecuado para implementar una amplia gama de aplicaciones empresariales.

<h1 align="center">Servlets</h1>
<p>Los <b>servlets</b> en Jakarta EE 9 son componentes Java que se ejecutan en un servidor web y están diseñados para responder a solicitudes HTTP, como las generadas por navegadores web. Los <b>servlets</b> son una parte fundamental de la especificación Jakarta Servlet 5.0. Permiten la creación de aplicaciones web dinámicas y se utilizan comúnmente para procesar formularios, manejar solicitudes de usuario, interactuar con bases de datos, generar respuestas dinámicas y realizar muchas otras tareas relacionadas con la web.</p>
<p align="center"><img width="719" alt="image" src="https://github.com/CCrisstian/Java_WebApp/assets/111469216/59a3e412-fefc-42e9-bd0a-1b1ba2948dd3"></p>
<p>Funcionamiento básico de los servlets en Jakarta EE 9:</p>

-  <b>Cliente realiza una solicitud HTTP</b>: Un cliente, como un navegador web, realiza una solicitud HTTP (GET, POST, etc.) al servidor web.
-  <b>Servidor web recibe la solicitud</b>: El servidor web, donde está desplegado el contenedor de servlets (como Apache Tomcat), recibe la solicitud HTTP.
-  <b>Contenedor de servlets maneja la solicitud</b>: El contenedor de servlets intercepta la solicitud y la dirige al servlet correspondiente basado en la configuración de mapeo de URL.
-  <b>Servlet procesa la solicitud</b>: El servlet ejecuta su método `service()`, que delega a los métodos `doGet()`, `doPost()`, `doPut()`, etc., según el tipo de solicitud. En estos métodos, el servlet procesa la solicitud (por ejemplo, leyendo parámetros, interactuando con bases de datos, realizando lógica de negocio).
-  <b>Servlet genera una respuesta</b>: El servlet crea una respuesta (usualmente en forma de HTML, JSON, XML, etc.) y la envía de vuelta al cliente a través del objeto `HttpServletResponse`.
-  <b>Cliente recibe la respuesta</b>: El navegador u otro cliente recibe la respuesta HTTP y la muestra o la procesa según sea necesario.

<h1 align="center">Patrón MVC</h1>
<p>El patrón <b>MVC (Modelo-Vista-Controlador)</b> es un patrón de diseño arquitectónico que separa una aplicación en tres componentes principales: el <b>Modelo</b>, la <b>Vista</b> y el <b>Controlador</b>. Esta separación facilita la gestión y el mantenimiento de la aplicación, permitiendo que cada componente tenga una responsabilidad bien definida:</p>

-  <b>Modelo</b>: Maneja la lógica de negocio y los datos de la aplicación. Es responsable de acceder y manipular los datos, usualmente interactuando con una base de datos.
-  <b>Vista</b>: Es responsable de presentar los datos al usuario. Esta capa muestra la interfaz de usuario y la forma en que los datos se presentan.
-  <b>Controlador</b>: Actúa como intermediario entre la Vista y el Modelo. Procesa la entrada del usuario, invoca métodos en el Modelo y determina qué Vista mostrar como resultado.

<p align="center"><img width="719" alt="image" src="https://github.com/CCrisstian/Java_WebApp/assets/111469216/ee5da5fa-2288-4d87-818a-b87bdff6ddc0"></p>

-  <b>Cliente (Navegador Web)</b>: Los usuarios interactúan con la aplicación web a través del navegador.
-  <b>HTTP Request</b>: Cuando el usuario realiza una acción (por ejemplo, hacer clic en un enlace o enviar un formulario), se envía una solicitud HTTP al servidor web.
-  <b>Contenedor Web</b>: Es el entorno donde se despliegan y ejecutan las aplicaciones web. En este caso, el contenedor web incluye la "Capa Web MVC".
-  <b>Capa Web MVC:</b>
    -  <b>Servlets</b>: Actúan como el <b>Controlador</b> en el patrón <b>MVC</b>. Los <b>servlets</b> reciben la solicitud HTTP del cliente, procesan la entrada, interactúan con el modelo para recuperar o actualizar datos, y luego deciden cuál vista (por ejemplo, una JSP) mostrar al usuario.
    -  <b>JSP (JavaServer Pages)</b>: Actúan como la <b>Vista</b>. Las <b>JSP</b> son responsables de generar la interfaz de usuario dinámica en respuesta a las solicitudes del cliente. Pueden incluir HTML, CSS y JavaScript, y se utilizan para presentar los datos proporcionados por el <b>Controlador</b>.
    -  <b>Model (Modelo)</b>: Representa la lógica de negocio y la gestión de datos. Los <b>servlets</b> interactúan con el modelo para realizar operaciones sobre los datos, como consultas a la base de datos o cálculos lógicos.
-  <b>HTTP Response</b>: Después de procesar la solicitud, el <b>servlet</b> selecciona la vista adecuada y genera una respuesta HTTP, que se envía de vuelta al navegador del cliente. Esta respuesta puede incluir la página HTML generada por la JSP con los datos dinámicos.

<h1 align="center">"Request" y "Response"</h1>
<h3>Request (Petición Web)</h3>
<p>Un <b>Request</b> es una solicitud enviada por un cliente (como un navegador web) al servidor. Incluye varios componentes esenciales:</p>

-    <b>Información que es enviada desde un cliente hacia el servidor</b>: Esto incluye todo el contenido de la solicitud que el cliente envía al servidor.
-    <b>Datos ingresados y enviados por el usuario</b>: Cuando un usuario interactúa con un formulario web y lo envía, esos datos se incluyen en la solicitud.
-    <b>Métodos HTTP (`Get` o `Post`):</b>
        -    `GET`: Este método se usa para solicitar datos de un servidor. Los datos de la solicitud se envían en la URL. Es comúnmente utilizado para obtener recursos, como páginas web o imágenes.
        -    `POST`: Este método se usa para enviar datos al servidor para que sean procesados, como al enviar un formulario. Los datos se envían en el cuerpo de la solicitud y no en la URL, lo que lo hace más seguro para enviar información sensible.
-    <b>Cabeceras HTTP (Headers)</b>: Proveen información adicional sobre la solicitud. Algunos ejemplos incluyen:
        -    `User-Agent`: Informa sobre el cliente que está realizando la solicitud.
        -    `Accept`: Especifica los tipos de contenido que el cliente puede procesar.
        -    `Content-Type`: Indica el tipo de contenido que se está enviando en el cuerpo de la solicitud, por ejemplo, `application/json` para datos en formato JSON.
<h3>Response (Respuesta Web)</h3>
<p>Un <b>Response</b> es la respuesta enviada por el servidor al cliente en respuesta a una solicitud. Incluye varios componentes esenciales:</p>

-    <b>Información que es enviada al cliente desde el servidor</b>: Contiene todos los datos y mensajes que el servidor envía de vuelta al cliente.
-    <b>Texto (html, plain, json, xml) o datos binarios (imágenes, pdf, videos)</b>: El contenido de la respuesta puede ser de varios tipos, dependiendo de lo que se esté solicitando:
        -    <b>HTML</b>: Para páginas web.
        -    <b>Plain text</b>: Texto sin formato.
        -    <b>JSON</b>: Datos en formato JSON, comúnmente usados en aplicaciones web modernas para enviar datos estructurados.
        -    <b>XML</b>: Otro formato para datos estructurados.
        -    <b>Datos binarios</b>: Archivos como imágenes, videos, documentos PDF, etc.
-    <b>HTTP headers, cookies, etc.</b>: Al igual que las solicitudes, las respuestas también contienen cabeceras que proveen información adicional sobre la respuesta:
        - `Content-Type`: Indica el tipo de contenido de la respuesta, por ejemplo, text/html para HTML.
        - `Set-Cookie`: Utilizado para enviar cookies al cliente.
        - `Content-Length`: Indica la longitud del contenido de la respuesta.

<h1 align="center">Métodos HTTP soportados</h1>
<p align="center"><img width="719" alt="image" src="https://github.com/CCrisstian/Java_WebApp/assets/111469216/3d20e565-73fb-46c6-afaa-fc1c2b029adf"></p>

-    `doDelete`
        - <b>Propósito</b>: Maneja solicitudes `HTTP DELETE`.
        - <b>Uso Común</b>: Eliminar un recurso especificado por la URL.
        - <b>Descripción</b>: Se utiliza cuando un cliente quiere eliminar un recurso específico. En aplicaciones RESTful, corresponde a la operación DELETE.
-    `doGet`
        - <b>Propósito</b>: Maneja solicitudes `HTTP GET`.
        - <b>Uso Común</b>: Recuperar información del servidor, como una página web o datos de una API.
        - <b>Descripción</b>:  Es el método más común y se utiliza para obtener datos del servidor sin modificar su estado.    
-    `doHead`
        - <b>Propósito</b>: Maneja solicitudes `HTTP HEAD`.
        - <b>Uso Común</b>: Recuperar los encabezados de una respuesta sin el cuerpo.
        - <b>Descripción</b>: Similar a `doGet`, pero no devuelve el cuerpo del mensaje, solo los encabezados. Útil para obtener metadatos sobre un recurso.   
-    `doOptions`
        - <b>Propósito</b>: Maneja solicitudes `HTTP OPTIONS`.
        - <b>Uso Común</b>: Determinar los métodos HTTP permitidos para un recurso específico.
        - <b>Descripción</b>: Proporciona información sobre las capacidades del servidor y los métodos HTTP que acepta.       
-    `doPost`
        - <b>Propósito</b>: Maneja solicitudes `HTTP POST`.
        - <b>Uso Común</b>: Enviar datos al servidor para crear o actualizar un recurso.
        - <b>Descripción</b>: Se utiliza para enviar datos al servidor, como formularios o archivos. A menudo provoca cambios en el servidor.       
-    `doPut`
        - <b>Propósito</b>: Maneja solicitudes `HTTP PUT`.
        - <b>Uso Común</b>: Actualizar un recurso existente o crear uno nuevo si no existe.
        - <b>Descripción</b>: Similar a `POST`, pero se usa para enviar datos que reemplazan un recurso existente o crean uno nuevo en una ubicación específica.   
-    `doTrace`
        - <b>Propósito</b>: Maneja solicitudes `HTTP TRACE`.
        - <b>Uso Común</b>: Realizar una solicitud de eco para fines de depuración.
        - <b>Descripción</b>:  Devuelve la solicitud original que recibió el servidor, útil para ver cómo las solicitudes son modificadas por los servidores intermedios.       

<h1 align="center">Clases e Interfaces del Servlet</h1>
<p align="center"><img width="800" alt="image" src="https://github.com/CCrisstian/Java_WebApp/assets/111469216/94cda8bf-21d0-4ed6-85e3-a1013979734d"></p>

<h3>Clases</h3>

-    <b>Servlet</b>
        - <b>Descripción</b>: Es la interfaz base que define los métodos que deben implementar todos los servlets.
        - <b>Métodos Principales:</b>
                -    init(): Inicializa el servlet.
                -    service(): Procesa las solicitudes del cliente.
              
-    <b>ServletRequest</b>
-    <b>ServletResponse</b>
