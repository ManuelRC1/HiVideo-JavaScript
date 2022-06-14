## Índice
- [1. Introducción](#introduccion) 																
- [2. Tecnologías escogidas y justificación](#tecnologias_escogidas)  						       	   	  
  - [2.1. Tecnologías FrontEnd](#tecnologias_escogidas_1)
  - [2.1. Tecnologías FrontEnd](#tecnologias_escogidas_2) 
- [3. ¿Por qué he elegido este proyecto?](#por_que_elegir)
  - [3.1. ¿Cómo está el mercado respecto a este tipo de proyecto que se desea desarrollar?](#casos_uso) 
  - [3.2. Objetivo del proyecto](#casos_uso)  	
  - [3.3. Planificación](#casos_uso)  					    		  
- [4. Diseño de la aplicación](#diseno)  										  
  - [4.1. Diagrama de flujo](#casos_uso) 								     	  
  - [4.2. Prototipo de pantallas](#modelo) 

  - [4.3. Inserción del código](#modelo) 
					    	  						 
- [5. Implementación y documentación](#arquitectura)   						         	   		 
  - [5.1. Estructura del proyecto](#estructura)  						         		 
  - [5.2. Recursos externos](#recursos)  	

  - [5.3. Implementación del diseño responsive](#recursos)

   - [5.3.1 Funcionamiento](#recursos)	
		
- [6. Manual de la aplicación](#despliegue)   

- [6. Despliegue de la aplicación](#despliegue)   	

- [6. Resultados y discusión](#despliegue)   	

- [6. Conclusiones](#despliegue)   	
	  									       
<a name="introduccion"></a>						     		
## 1. Introducción 	
La propuesta consiste en el desarrollo de una aplicación web destinado a crear una 
plataforma de videos de forma estática, donde podrás navegar a diferentes sitios y a 
diferentes categorías, con una gran variedad de videos. 
Está pensado para que el usuario conozca contenido que no sabía que iba a ver y que les 
salga contenido relacionado con lo que está viendo, de la misma temática, con lo que es 
importante centrarse en eso, y en que sea lo más interactiva posible.
Esta aplicación se desarrollará en la web, lo que quiere decir que no es necesario instalar 
ningún tipo de software en su equipo informático y con el único requisito de tener un 
acceso a internet y un navegador web

<a name="tecnologias_escogidas></a>
## 2. Tecnologías escogidas y justificación 

<a name="tecnologias_escogidas_1"></a>
### 2.1 Tecnologias FrontEnd

Son aquellas que se utilizan en el lado Cliente, las que se utilizan en los diferentes dispositivos que utilizamos para conectarnos con el servidor a través de internet. Las tecnologías usadas son:

- HTML5

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas de Hipertexto), es el lenguaje de marcado predominante para la construcción de páginas Web. Es usado para describir la estructura y el contenido en forma de texto, así como para complementar el texto con objetos tales como imágenes. HTML se escribe en formade "etiquetas", rodeadas por corchetes angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el comportamiento de navegadores Web y otros procesadores de HTML.HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía más ampliamente como un término genérico para el HTML, ya sea en forma descendida del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML (como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la extensión .htm o .html

- CSS

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas de Hipertexto), es el lenguaje de marcado predominante para la 
construcción de páginas Web. Es usado para describir la estructura y 
el contenido en forma de texto, así como para complementar el texto 
con objetos tales como imágenes. 
HTML se escribe en formade "etiquetas", rodeadas por corchetes 
angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un 
documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el 
comportamiento de navegadores Web y otros procesadores de HTML.
HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía 
más ampliamente como un término genérico para el HTML, ya sea en forma descendida 
del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML 
(como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la 
extensión .htm o .html


- JQuery

HTML, siglas de HyperText Markup Language (Lenguaje de Marcas 
de Hipertexto), es el lenguaje de marcado predominante para la 
construcción de páginas Web. Es usado para describir la estructura y 
el contenido en forma de texto, así como para complementar el texto 
con objetos tales como imágenes. 
HTML se escribe en formade "etiquetas", rodeadas por corchetes 
angulares (<,>). HTML también puede describir, hasta un cierto punto, la apariencia de un 
documento, y puede incluir un script (por ejemplo, JavaScript), el cual puede afectar el 
comportamiento de navegadores Web y otros procesadores de HTML.
HTML también es usado para referirse al contenido del tipo de MIME text/html o todavía 
más ampliamente como un término genérico para el HTML, ya sea en forma descendida 
del XML (como XHTML 1.0 y posteriores) o en forma descendida directamente de SGML 
(como HTML 4.01 y anteriores). Por convención, los archivos de formato HTML usan la 
extensión .htm o .html

- BxSlider

Permite transición vertical y horizontal. Las diapositivas 
pueden contener imágenes, videos o contenido HTML. 
Advanced touch / golpe soporte incorporado. Utiliza 
transiciones CSS para animación de diapositivas

<a name="tecnologias_escogidas_2"></a>
### 2.1 Tecnologias BackEnd

Son aquellas que se utilizan en el lado Servidor, las que 
utiliza el Servidor para gestionar las diferentes peticiones de información que le 
llegan y para gestionar las bases de datos alojadas en los mismos. Los usados son:

- JavaScript
				 
JavaScript es un lenguaje de programación 
interpretado, es decir, que no requiere
compilación, utilizado principalmente en páginas 
Web, con una sintaxis semejante ala del lenguaje 
Java y el lenguaje C. 
Al igual que Java, JavaScript es un lenguaje 
orientado a objetos propiamente dicho, ya que dispone de Herencia, si bien ésta se realiza 
siguiendo el paradigma de programación basada en prototipos, ya que las nuevas clases 
se generan clonándolas clases base (prototipos) y extendiendo su funcionalidad. 
Todos los navegadores modernos interpretan el código JavaScript integrado dentro de las 
páginas Web. Para interactuar con una página Web se provee al lenguaje JavaScript de 
una implementación del DOM	

- JSON
				 
JSON, que significa JavaScript Object Notation, es 
una formatación usada para estructurar datos en 
forma de texto y transmitirlos de un sistema a otro, 
como en aplicaciones cliente-servidor o en 
aplicaciones móviles.
Una manera de emplearlo es a través de requisiciones AJAX, en que la aplicación 
recupera los datos almacenados en el servidor de hosting sin la necesidad de recargar la 
página.
La especificación del archivo JSON surgió alrededor del año 200, pero solo pasó a formar 
parte del lenguaje JavaScript después del lanzamiento de la versión 5 del ECMAScript.
Actualmente, diversos tipos de lenguaje de programación soportan este formato, además 
de ser una alternativa más liviana que el modelo XML.
				      
- AJAX
				 
AJAX, acrónimo de Asynchronous JavaScript And XML (JavaScript 
asíncrono y XML), es una técnica de desarrollo Web para crear
aplicaciones interactivas oRIA (RichInternet Applications). Estas 
aplicaciones se ejecutan en el cliente, es decir, en el navegador de los 
usuarios mientras se mantiene la comunicación asíncrona con el 
servidor en segundo plano. De esta forma es posible realizar cambios 
sobre las páginas sin necesidad de recargarlas, lo que significa 
aumentar la interactividad, velocidad y usabilidad en las aplicaciones. 
Ajax es una tecnología asíncrona, en el sentido de que los datos 
adicionales se requieren al servidor y se cargan en segundo plano sin interferir con la 
visualización ni el comportamiento de la página. 
JavaScript es el lenguaje interpretado (scripting language) en el que normalmente se 
efectúan las funciones de llamada de Ajax mientras que el acceso a los datos se realiza 
mediante XMLHttpRequest, objeto disponible en los navegadores actuales. En cualquier 
caso, no es necesario que el contenido asíncrono esté formateado en XML. Ajax es una 
técnica válida para múltiples plataformas y utilizable en muchos sistemas operativos y 
navegadores dado que está basado en estándares abiertos como JavaScript y Document 
Object Model (DOM)				      
				      
<a name="por_que_elegir></a>
## 3. ¿Por qué he elegido este proyecto?

Llevo pensando desde hace tiempo pensando en hacer una plataforma de videos, y me 
supone un gran reto ya que amplia muchos temas y es muy extenso, también no tiene 
límites para seguir extendiéndolo.

<a name="por_que_elegir></a>
### 3.1 ¿Cómo está el mercado respecto a este tipo de proyecto que se desea desarrollar?

Crear una plataforma de videos es algo que requiere mucho tiempo, tanto para crearse 
como para comprobar de que no se tiene ningún problema, pero he visto ciertos puntos a 
destacar:
	 
• Como bien dije antes, se requiere mucho tiempo por si hay algún problema, pero la 
ventaja de esto es que está disponible las 24 horas y los 365 días del año, lo que 
me permitirá tener mi plataforma de videos permanentemente.
	 
• Ahorro en gastos no implica en incurrir en gastos de licencias de apertura, local 
físico...
	 
• Análisis completo y detalla de los clientes, ya que la analítica web y marketing digital 
permiten profundizar en el análisis del cliente, su comportamiento, gustos y 
preferencias. El fin es localizar los puntos fuertes y los puntos en los que se puede 
mejorar para el contenido y la publicidad añadida en sitios estratégicos
	 
• Anticipación a la competencia, donde la tecnología y el mundo avanza a pasos 
agigantados, es importante estar en continua actualización por lo que cuanto antes 
nos adaptemos a los nuevos cambios mayor ventaja compet	 
	 
	 
	 

La aplicación dará servicio a distintos tipos distintos de usuarios:
- `Anónimo`: Podrán acceder a la página principal de la aplicación dentro de la cuál podrán conocer los servicios ofrecidos por la empresa, así como otros datos referentes a la misma.
- `Usuario:` Podrán acceder mediante una autenticación a sus datos de carácter personal y podrán interactuar con la misma dependiendo del rol específico de cada uno. Los usuarios podrán ser:
  - `Socio:` Cada uno de ellos tiene una participación en los beneficios de la empresa. Son los que descargan la aceituna en la almazara para su proceso de elaboración. Uno de ellos es el administrador de la aplicación.
    - `Administrador:` Es el encargado del mantenimiento principal de la aplicación, gestión de socios, restablecimiento de contraseñas… A su vez es también comercial.
  - `Empleado:` No todos los empleados de la empresa tienen un rol específico en la aplicación. Por ejemplo, un peón de mantenimiento no necesita usar la aplicación para el desarrollo de su trabajo. Los que si la necesitan son:
    - `Comercial:` Encargado de la gestión de ventas, clientes, precios y otros aspectos relacionados con la economía de la empresa. El administrador tiene por defecto el rol de comercial.
    - `Dependiente:` Es el encargado de realizar ventas, generalmente en la tienda de la almazara, aunque esta aplicación no le restringe el acceso a ningún tipo de clientes ni ventas.
    - `Encargado:` Es el responsable de almazara y como tal el encargado de insertar los datos derivados del trabajo en la misma (descargas de aceituna, análisis de aceite, stock de productos…).
  - `Cliente:` Todos los usuarios pueden realizar compras de aceite. Pero existen usuarios externos a la almazara que no son ni socios ni empleados. Estos son clientes.						       	   	  
<a name="tecnologias_escogidas_2"></a>
### 3.1. Tecnologías escogidas y justificación 
La aplicación se desarrolla en su mayor parte usando lenguaje de servidor PHP. No obstante, existen partes de la misma realizadas en lenguaje cliente Javascript y su biblioteca multiplataforma `Jquery.` 			          	     		 

Cabe mencionar que todo el software utilizado es libre, con lo que la empresa tendrá un considerable ahorro en concepto de licencias. El software seleccionado no lo ha sido sólo por  gratuito, sino porque además es unas de las tecnologías más utilizada en la actualidad en el desarrollo de aplicaciones web debido a su fiabilidad y a su versatilidad. 

Pero lo más importante a destacar es que el lenguaje de programación escogido va asociado al framework. La selección del framework se desarrolla en el punto [3.3](#frameworks_seleccionados)
<a name="bases_datos"></a>
### 3.2. Motor de bases de datos 
El motor de bases de datos usado es `MySql`. Las razones de su elección son las siguientes:
- Su adquisición es gratuita, lo que permite reducción de costes para el cliente.
- Es multiplataforma para Windows, Linux y Mac (los sistemas operativos más extendidos) con lo cual se podrá disponer él en cualquiera de estos.
- Es un motor muy extendido en la comunidad de desarrolladores, con lo que conseguir ayuda es muy sencillo.
- La labor de mantenimiento de una base de datos MySql es muy fácil debido a que presenta menos funciones frente a otros sistemas gestores. Esto, aunque pueda parecer una desventaja, tiene a su favor que el mantenimiento de la aplicación lo puede llevar el propio desarrollador, sin tener que recurrir a un administrador de bases de datos.
- Es escalable, lo cual nos da una ventaja con vistas al futuro. 						    		  
<a name="frameworks_seleccionados"></a>
### 3.3. Frameworks seleccionados
El framework usado es `Symfony3.2.4`. Las razones de su elección son las siguiente:
- Es un framework gratuito.
- Lleva muy bien a la práctica el concepto Modelo-Vista-Controlador, lo cual es muy recomendable para el mantenimiento de aplicaciones.
- Está construido en lenguaje PHP, lo cual nos da una ventaja en el sentido de que este lenguaje es de los más extendidos en el mundo actualmente.
- La comunidad de desarrolladores Symfony es muy amplia. Como consecuencia de esto encontraremos infinidad de módulos reutilizables ya probados que podemos añadir a nuestro código de forma sencilla y que nos ahorrará es tener que crearlos y probarlos nosotros mismos.
- La ayuda de Symfony es muy buena e intuitiva.
- Los módulos existentes están muy estandarizados desde el punto de vista del código, con lo que estamos facilitando la interoperatividad.
- Buena comunicación entre el back-end y el front-end.
- Organiza las funcionalidades en paquetes o Bundles. Estos, si no vienen con el core pueden instalarse y podremos aprovechar su funcionalidad.
- El core de Symfony se basa en la integración de cuatro productos muy potentes ya existentes en el mercado:
  - `Twig:`  Es el gestor de plantillas html. Resuelve muy bien la separación entre las mismas y los controladores. Permite herencia y bloques html, lo que permite la no repetición de código innecesario.
  - `Doctrine:` Es un ORM (Object Relational Mapping) consistente en la equivalencia entre tablas de la base de datos y entidades. Esto permite al desarrollador olvidarse del lenguaje SQL y centrarse en su aplicación.
  - `Swiftmailer:` Es una librería para el envío de correos electrónicos. Permite usar varios transporters como SMTP o GMAIL.
  - `Monolog:` Es una librería para el registro de la actividad de una aplicación en ficheros.
<a name="diseno"></a>						    		  
## 4. Diseño de la aplicación 	
<a name="casos_uso"></a>									  
### 4.1. Casos de uso 
![Texto alternativo](web/images/135.jpg)
![Texto alternativo](web/images/136.jpg)
![Texto alternativo](web/images/137.jpg)
![Texto alternativo](web/images/138.jpg)
![Texto alternativo](web/images/139.jpg)
![Texto alternativo](web/images/140.jpg)
![Texto alternativo](web/images/141.jpg)
![Texto alternativo](web/images/142.jpg)
<a name="modelo"></a>									     	  						    	 
### 4.2. Modelo de dominio 			
![Texto alternativo](web/images/143.jpg)
<a name="arquitectura"></a>					   	 
## 5. Arquitectura de la aplicación  	
<a name="estructura"></a>					         	   		  
### 5.1. Estructura del proyecto 
La estructura de la aplicación es la típica de un proyecto Symfony3. Las principales carpetas son:
- `app`: contiene la configuración de la aplicación, vistas y traducciones
  - `Resources`
    - `translations`: contiene los archivos `yml` de traducciones
    - `views`: contiene las distintas plantillas Twig organizadas en subcarpetas
  - `config`: contiene los archivos de configuración de la aplicación
- `bin`: contiene los archivos referentes a los comandos ejecutables desde la terminal.
- `src`: contiene el código fuente de la aplicación
  - `AppBundle`
    - `Controller`: contiene los controladores que dan funcionalidad a la aplicación.
    - `DataFixtures`: contiene los ficheros donde se definen los datos de inicio de la aplicación.
    - `Entity`: contiene los distintos ficheros donde se definen las entidades ORM.
    - `EventListener`: contiene los escuchadores de eventos.
    - `Form`: contiene las clases correspondientes a los formularios.
    - `Repository`: contiene las clases que albergan todas las acciones de consulta en base de datos.
    - `Service`: contiene el código de los servicios creados para esta aplicación.
- `tests`: contiene los controladores de tests.
- `var`: contiene los archivos de caché, logs, sesión…
- `vendor`: contiene el core de Symfony y las librerías externas.
- `web`: contiene todos los ficheros necesarios para la web como hojas de estilos, imágenes...
  - `bootstrap`: contiene todos los ficheros de Bootstrap.
  - `font-awesome`: contiene todos los ficheros de los iconos Font Awesome.
  - `images`: contiene todas las imágenes usadas en la aplicación.
  - `squery`: contiene todos los ficheros de Jquery.
  - `script`: contiene todos los ficheros Javascript usados en la aplicación.
  - `styles`: contiene todas las hojas de estilos de la aplicación.
  - `uploads`: contiene todos los ficheros subidos a la aplicación.	
<a name="recursos"></a>					         		  
### 5.2. Recursos externos 
En esta aplicación se han usado diversos recursos externos, es decir, librerías y código no escrito por el desarrollador de esta aplicación. Los recursos externos usados son:
- `Bootstrap`: para el aspecto visual de la aplicación.
- `Font Awesome`: iconos para los distintos elementos html.
- `Jquery`: librería de Javascript.
- `FixturesBundle`: bundle de Symfony para la introducción de registros en la base de datos. En este caso, se usa para tener datos iniciales en la aplicación.
- `LiuggioExcelBundle`: bundle de Symfony para la lectura de datos en ficheros xls.
- `KnpPaginatorBundle`: bundle de Symfony para la paginación y ordenación de tablas.
- `MpdfBundle`: bundle de Symfony para generar ficheros formato pdf desde código html.
<a name="despliegue"></a>							  
