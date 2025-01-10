# cURL command

El comando cURL en Linux es una herramienta de línea de comandos que permite transferir datos desde o hacia un servidor. cURL soporta una amplia variedad de protocolos, incluyendo HTTP, HTTPS, FTP, SFTP, SCP, entre otros.

cURL es útil para muchas tareas, incluyendo:

1. Descargar archivos: Puedes usar cURL para descargar archivos desde un servidor remoto directamente a tu máquina local. Ejemplo:
    
    ```cmd
    curl -O http://ejemplo.com/archivo.txt
    ```

2. Enviar solicitudes HTTP: cURL puede ser usado para enviar solicitudes GET, POST, DELETE, PUT y otras a una API o página web. Ejemplo:

    ```cmd
    curl -X POST -d "param1=valor1&param2=valor2" http://ejemplo.com/api/endpoint
    ```

3. Depuración: cURL es útil para probar y depurar APIs o servidores web, ya que puedes ver exactamente qué está siendo enviado y recibido.

4. Transferencia de datos: cURL también puede ser utilizado para transferir datos entre diferentes servidores, utilizando protocolos como FTP o SCP.

En resumen, cURL es una herramienta muy versátil para trabajar con URLs y realizar transferencias de datos en línea de comandos.

[Linux/Mac Terminal Tutorial: How To Use The cURL Command](https://youtu.be/WxUVU0b95Oc?feature=shared)