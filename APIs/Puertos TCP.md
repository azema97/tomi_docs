# Puertos TCP

Un puerto TCP (Protocolo de Control de Transmisión) **es un punto final o una interfaz en la comunicación entre dos aplicaciones que se ejecutan en diferentes sistemas de red**. Específicamente, un puerto TCP es un número de identificación único para diferentes aplicaciones o procesos en un sistema que utilizan la red.

El protocolo TCP utiliza estos números de puerto para dirigir los paquetes de datos a una aplicación específica en un sistema. Cada conexión TCP en un sistema se identifica de forma única por un par de direcciones IP (la dirección IP del remitente y la del receptor) y un par de números de puerto (el puerto del remitente y el del receptor).

Los números de puerto TCP pueden variar desde 0 hasta 65535, pero generalmente se dividen en tres rangos:

- **Puertos bien conocidos (0-1023)**: Estos puertos están reservados para servicios de red estándar que son ampliamente utilizados, como HTTP (puerto 80), HTTPS (puerto 443), FTP (puerto 21), SMTP (puerto 25), DNS (puerto 53), etc.
- **Puertos registrados (1024-49151)**: Estos puertos están registrados por el IANA para ciertas aplicaciones y servicios.
- **Puertos dinámicos o privados (49152-65535)**: Estos puertos pueden ser utilizados por cualquier aplicación y no están regulados por el IANA.

En resumen, un puerto TCP es esencialmente una dirección para la comunicación de red en un sistema, permitiendo que las aplicaciones envíen y reciban datos correctamente.