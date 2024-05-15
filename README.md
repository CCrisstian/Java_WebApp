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

