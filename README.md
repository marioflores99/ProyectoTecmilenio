# ProyectoTecmilenio

Nombre: Mario Andrés Flores Madero 	Matrícula: 2735271
Nombre del curso: 
Taller de productividad basada en herramientas tecnológicas.	Nombre del profesor: 
Carlos Javier Guel Martínez
Módulo: 	Actividad: Fase 4. Resultados.
Fecha: 05/25/2021 
Bibliografía:  

Ficha del documento
Autor:	Mario Andrés Flores Madero
Proyecto:	
Lugar de realización:	
Nombre del documento:	
Código:	
Control de versiones:	
Aprobación:	
Fecha de inicio:	

 
Tabla de contenidos
Introducción
Planteamiento del problema
Justificación
Antecedentes
Requerimientos
Objetivo general
Objetivos específicos
Arquitectura y relación del proyecto
Arquitectura de la solución
Diseño de base de datos


 
Introducción 
Un producto de software es una herramienta que te permite aumentar la productividad de un negocio y aumentar el control en todos los procesos donde se realicen la gestión de tareas dentro de una empresa. A su vez puedes compartir información en tiempo real con el resto de los trabajadores de tu empresa. Es por lo que la empresa “Comercializadora de chiles del pacifico S.A. de C.V.” ha solicitado que se le desarrolle una herramienta que pueda permitir la gestión y monitoreo de las siembras de chiles y se les permita compartir la información en tiempo real a los demás empleados de la empresa.  

Planteamiento del problema
El mayor problema que tiene la empresa en este momento es el recabado de información, ya que es una empresa de agricultura, tiene que ir una persona periódicamente a los campos agrícolas con el fin de monitorear el estatus de las siembras, para así poder determinar una fecha de corte y exportación. Durante el traslado se pierde dinero y tiempo del personal en solo ir a recabar dicha información, por lo tanto, se planea implementar una aplicación para gestionar esos datos con el resto de la empresa.

Justificación
Con la realización de este proyecto la empresa podrá dejar de mandar a un representante a revisar las siembras tan seguido, de esta manera la información se tendrá almacenada en una aplicación web y estará funcionando en tiempo real, así ya no habrá demora en producción, en ventas y se dejará de gastar recursos en mandar a un empleado a las siembras. 

Antecedentes
La empresa ha estado gastando tiempo y recursos teniendo que mandar a uno de sus empleados a revisar las siembras cada determinado tiempo a monitorear el estatus de los chiles. Además, al tener que esperar a que un representante revisa las siembras, el resto del equipo de ventas no tiene información exacta en tiempo real por lo que no puede vender cargamentos hasta tener información concreta de las siembras. Esto ha estado ocasionado perdidas y demoras en el área de ventas.

Requerimientos
Requerimientos (funcionalidades usuario)	Dependencia	Prioridad
Poder realizar registros nuevos sobre siembras.	Conexión a la base de datos.	Alta
Poder modificar, actualizar y eliminar registros de las siembras.
	Conexión a la base de datos.
Depende de que ya exista un registro. 	Alta
Poder visualizar la información en pantalla acerca de las siembras.
	Conexión a la base de datos.
Depende de que ya exista un registro.	Alta
Tener un indicador para cada registro acerca de una fecha estimada de corte para los chiles.
	Conexión a la base de datos.
Depende de que ya exista un registro.	Media
Poder registrar y visualizar la lista de insumos y sus precios para ver el gasto que se ha realizado en cada parcela de las siembras.
	Se deberá tener un registro de siembra previo para poder anotar insumos a cada parcela.	media
Creación de usuarios y contraseñas para tener acceso a la aplicación web.
	Conexión a la base de datos.
	alta
Requerimientos (diseño)		
Diseño de la página con los colores y logotipos de la empresa.
	Se deberá obtener imágenes de logotipo y acomodar la paleta de colores con respecto a los de la empresa.	media
Diseño de la página con campos textuales para el tipo de insumo que estas ingresando y campos numéricos para el precio del producto.	Se deberá de haber designado antes el tipo de carácter que tendrá cada campo.	baja
En el campo de fecha se podrá insertar fechas anteriores, la actual y vendrá en formato DD/MM/YYYY.
	Se deberá de haber designado antes el tipo de carácter que tendrá cada campo.	baja
Diseño de una base de datos relacional.
	Se deberá diseñar con los campos sugeridos por el cliente.	alta
El campo para el ingreso del nombre de la siembra permitirá caracteres alfanuméricos.
	Se deberá de haber designado antes el tipo de carácter que tendrá cada campo.	baja
El campo para el ingreso del personal permitirá únicamente caracteres alfabéticos.	Se deberá de haber designado antes el tipo de carácter que tendrá cada campo.	baja
Requerimientos no funcionales.		
Toda transacción del usuario debe funcionar en menos de 5 segundos.
	Conexión a la base de datos.	alta
Los datos modificados deben ser actualizados para todos los usuarios.
	Conexión a la base de datos.	alta
El sistema deberá proporcionar mensajes de error cuando un dato no vaya acorde a su tipo de carácter.
	Se deberá de haber designado antes el tipo de carácter que tendrá cada campo.	media

Objetivo general
Crear una aplicación web en la cual los trabajadores de la empresa puedan revisar en tiempo real la información relacionada a las siembras y poder agregar nuevos registros, así como modificarlos, eliminarlos y que estos puedan ser almacenados en una base de datos. Para ello utilizaremos HTML y CSS para el diseño del frontend y para el backend utilizaremos Java y JavaScript. 

Objetivos específicos
•	Poder realizar registros nuevos sobre siembras.
•	Poder modificar, actualizar y eliminar registros de las siembras.
•	Poder visualizar la información en pantalla acerca de las siembras.
•	Tener un indicador para cada registro acerca de una fecha estimada de corte para los chiles.
•	Poder registra y visualizar la lista de insumos y sus precios para ver el gasto que se ha realizado en cada parcela de las siembras.
•	Creación de usuarios y contraseñas para tener acceso a la aplicación web.

Arquitectura y relación del proyecto
Para la realización del proyecto tuvimos que dividir la carga de trabajo en 4 etapas

Fase 1: Introspección.
Generar un portafolio de evidencia con la documentación necesaria para identificar fortalezas y áreas de oportunidad.

Fase 2: Planteamiento.
Definir la empresa u organización donde se realizará la labor de consultoría para delimitar el producto como resultado del proyecto.
Obtener especificaciones de requerimiento de software.

Fase 3: Ejecución. 
Diseñar un plan de acción para el diseño.
Desarrollo.
Pruebas e implementación de los requisitos definidos de la solución.

Fase 4: Resultados
Generar la documentación 
Configuración y uso de la solución desarrollada 
Diagrama de flujo de proceso:
 
 
 

Arquitectura de la solución
Para nuestro proyecto utilizamos un modelo  
Diseño de base de datos
Para la base de datos utilizaremos MySQL.
Base de datos relacional

Manual de uso
Login
Para entrar deberás ingresar tu usuario y contraseña y dar click en el botón de “Login”, de no tener registrado tu usuario y contraseña deberás hacer click en “Registrar nuevo usuario”, una vez que se despliega el nuevo formato, deberás ingresar tu correo y contraseña y hacer click en “Registrar”.
Para crear un nuevo registro
Hacer click en el botón de “Crear nuevo registro”, una vez que se despliega la ventana emergente se desplegara un formato con los campos: id, agricultor, variedad, ubicación, insumos, fotos. Deberás ingresar todos los campos, a excepción del de fotos, ese campo es opcional. Una vez que termines de llenar cada campo deberás hacer click en “Guardar”, esto automáticamente guardara la información en la base de datos y podrás ver desplegado tu nuevo registro en el grid principal.
Para actualizar un registro.
Deberás hacer click en el registro que desees actualizar, una vez que des click aparecerá una venta emergente con los campos existentes y sus datos. Deberás hacer click en el campo que desees actualizar y agregar la información que desees corregir. Una vez hecho esto puedes proseguir a dar click en el botón “Actualizar”.

Para eliminar un registro.   
Deberás hacer click en el registro que desees eliminar, una que des click aparecerá una ventana emergente con un botón que dice ”Eliminar registro”, hacer click en el botón eliminar y tu registro dejara de aparecer en el grid principal.

Contribución
Para contribuir con el desarrollo del proyecto es preciso que se haga una bifurcación del proyecto.
Deberás realizar una clonación del proyecto en el que deseas trabajar. 
Deberás realizar cambios o fixes en el proyecto.
Una vez que tengas todo listo y verificado deberás asignar el repositorio al cual deseas hacer el pull request de tu proyecto.
Una vez que el autor original este conforme con tus cambios podrá hacer un merge del proyecto y agregará tus cambios al proyecto original.  

  
