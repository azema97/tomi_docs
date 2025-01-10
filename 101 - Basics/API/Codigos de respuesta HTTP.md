# Códigos de respuesta HTTP

Los códigos de estado de respuesta HTTP indican si una solicitud HTTP específica se ha completado con éxito. Las respuestas se agrupan en cinco clases:

- Respuestas informativas (100–199),
- Respuestas satisfactorias (200–299),
- Redirecciones (300–399),
- Errores de los clientes (400–499),
- Errores de los servidores (500–599).

Aquí hay algunos de los códigos de estado HTTP más comunes:

- **100 Continue**: El servidor ha recibido los encabezados de la solicitud, y el cliente debería proceder a enviar el cuerpo de la solicitud.
- **200 OK**: La solicitud ha tenido éxito.
- **201 Created**: La solicitud ha tenido éxito y se ha creado un nuevo recurso como resultado.
- **204 No Content**: La solicitud ha tenido éxito, pero no necesita devolver un cuerpo de entidad.
- **301 Moved Permanently**: Este y todos los futuros pedidos deben dirigirse a la URL dada.
- **302 Found**: Este es un ejemplo de redireccionamiento industrial o cambio de dirección.
- **400 Bad Request**: La solicitud no pudo ser entendida por el servidor debido a una sintaxis mal formada.
- **401 Unauthorized**: Similar al 403 Forbidden, pero específicamente para casos cuando la autenticación es requerida y ha fallado o aún no ha sido proporcionada.
- **403 Forbidden**: El servidor entendió la solicitud, pero se niega a autorizarla.
- **404 Not Found**: El recurso solicitado no pudo ser encontrado en el servidor.
- **500 Internal Server Error**: Un mensaje de error genérico, dado cuando no se dispone de un mensaje más específico.
- **502 Bad Gateway**: El servidor estaba actuando como una puerta de enlace o proxy y recibió una respuesta inválida del servidor ascendente.
- **503 Service Unavailable**: El servidor no está listo para manejar la solicitud.

Estos son solo algunos ejemplos y hay muchos otros códigos de estado HTTP.