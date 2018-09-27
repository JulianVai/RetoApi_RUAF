# RetoApi_RUAF
Reto para solucionar Una api del registro único de afiliados de Colombia.

### Detalles del problema:
La página web del registro único de afiliados al sistema de salud tiene la siguiente URL: http://ruafsvr2.sispro.gov.co/TerminosCondiciones.aspx
Se debe entonces lograr una forma automática de superar el filtro de Términos y Cóndiciones dando click en aceptar, lograr esto los deberá conducir a la URL donde se encuentra
el formulario de consulta que tiene los campos de *Tipo de Documento* y *Numero de Identificación*. 
Estos campos deben ser llenados de manera programática a partir de la información extraida de un request que contiene la infomración 
necesaria para la consulta. 
Una vez obtenido el resultado de la consulta, deben guardarse TODOS LOS DATOS en un documento JSON y los regrese al solicitante
El timeout máximo para la solicitud y respuesta son 30 segundos.

El primer postulante que complete de manera efectiva todas las condiciones gana el reto :)
