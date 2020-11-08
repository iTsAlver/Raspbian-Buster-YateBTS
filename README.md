#	PRIVATE BTS.

*	Este repositorio incluye:
	*	Una imagen con el sistema operativo con los paquetes instalados y configurados.
	*	Una presentación en formato .pptx y .pdf.
	*	Un archivo .zip con la imagen.
	
*	La BTS es plug and play, al ser alimentada se configura y lanza los comandos necesarios para iniciarla.

*	La BTS proporciona números privados a cada usuario subscrito.

*	No hay métodos de autenticación implementados.

*	Existe la posibilidad de exportar las llamadas fuera de la BTS via internet y protocolo SIP.

*	Contiene un servidor de configuración APACHE2.

*	La BTS proporciona servicio GPRS a los usuarios mediante el punto de acceso a internet de la Raspberry.

*	Punto de acceso plug and play:
	*	Nombre:	SOURCE_BTS
	*	Clave:	avgp3838
		*	Se recomienda enormemente cambiar la clave, debido a que un usuario de la BTS no debe de ser capaz de acceder al punto de acceso, dado que tendría el poder de modificar la configuación de la misma desde el servidor APACHE2.

#	Autores:

*	Alberto Palomo Alonso.
*	Krupskaya del Cisne Quinche.

#	Agradecimientos:

*	Gonzalo Corral, por la enorme ayuda en la instalación y correción de la misma.
*	blog.strcpy, por proporcionar una guía, aunque con paquetes rotos, del proceso.
*	Departamento de Teoría de la Señal y Comunicaciones de la Universidad de Alcalá de Henares, por proporcionar el hardware necesario.

