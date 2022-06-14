## Índice
- [1. Introducción](#introduccion) 						 
- [2. Objetivos](#objetivos)  												  
- [3. Tecnologías escogidas y justificación](#tecnologias_escogidas)  						       	   	  
  - [3.1. Tecnologías escogidas y justificación](#tecnologias_escogidas_2)  			          	     		  
  - [3.2. Motor de bases de datos](#bases_datos)   						    		  
  - [3.3. Frameworks seleccionados](#frameworks_seleccionados)  						    		  
- [4. Diseño de la aplicación](#diseno)  										  
  - [4.1. Casos de uso](#casos_uso) 								     	  
  - [4.2. Modelo de dominio](#modelo)  						    	  						  
- [5. Arquitectura de la aplicación](#arquitectura)   						         	   		 
  - [5.1. Estructura del proyecto](#estructura)  						         		 
  - [5.2. Recursos externos](#recursos)  							        		  
- [6. Manual de despliegue](#despliegue)   										 
  - [6.1. Requisitos hardware y software aplicables](#requisitos)  			   		  
  - [6.2. Instrucciones de despliegue en Linux](#despliegue_linux)   			 		    	 
  - [6.3. Instrucciones de despliegue en Windows, Mac y en un proveedor en la nube](#despliegue_resto)   		  									       
  - [6.4. Configuración inicial](#configuracion) 
<a name="introduccion"></a>						     		
## 1. Introducción 	
La propuesta consiste en el desarrollo de una aplicación web destinado a crear una plataforma de videos de forma estática, donde podrás navegar a diferentes sitios y a diferentes categorías, con una gran variedad de videos. 
Está pensado para que el usuario conozca contenido que no sabía que iba a ver y que les 
salga contenido relacionado con lo que está viendo, de la misma temática, con lo que es importante centrarse en eso, y en que sea lo más interactiva posible.
Esta aplicación se desarrollará en la web, lo que quiere decir que no es necesario instalar ningún tipo de software en su equipo informático y con el único requisito de tener un acceso a internet y un navegador web
									  
## 2. Objetivos 
<a name="objetivos"></a>
La razón de la elaboración de este proyecto viene dada por la necesidad que tienen los agentes intervinientes en la elaboración de aceite de estar informados en todo momento y en tiempo real de los datos propios de la actividad principal de constantes. Con la introducción de esta aplicación en la empresa se obtendrán múltiples beneficios tales como una mayor facilidad para el almacenamiento y gestión de los datos tanto de los socios como de los empleados, una mayor posibilidad de dar a conocer sus servicios, más comodidad para los usuarios, etc.												 
<a name="tecnologias_escogidas"></a>
## 3. Tecnologías escogidas y justificación 
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
