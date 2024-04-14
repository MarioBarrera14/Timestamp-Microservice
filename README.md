# Timestamp Microservice

This is the boilerplate code for the Timestamp Microservice project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice


Aprobado :Debes proporcionar tu propio proyecto, no la URL de ejemplo.
Aprobado :Una solicitud /api/:date?con una fecha válida debe devolver un objeto JSON con una unixclave que sea una marca de tiempo Unix de la fecha de entrada en milisegundos (como tipo Número)
Aprobado :Una solicitud /api/:date?con una fecha válida debe devolver un objeto JSON con una utcclave que es una cadena de la fecha de entrada en el formato:Thu, 01 Jan 1970 00:00:00 GMT
Aprobado :Una solicitud /api/1451001600000debería regresar{ unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }
Aprobado :Su proyecto puede manejar fechas que pueden ser analizadas exitosamente pornew Date(date_string)
Aprobado :Si la cadena de fecha de entrada no es válida, la API devuelve un objeto que tiene la estructura{ error : "Invalid Date" }
Aprobado :Un parámetro de fecha vacío debería devolver la hora actual en un objeto JSON con una unixclave
Aprobado :Un parámetro de fecha vacío debería devolver la hora actual en un objeto JSON con una utcclave