# 📗 Amazon S3 (Simple Storage Service)

Amazon S3 (Simple Storage Service) es un servicio de almacenamiento de objetos en la nube ofrecido por **Amazon Web Services (AWS)**. Está diseñado para almacenar y recuperar cualquier cantidad de datos desde cualquier lugar del mundo, proporcionando una solución escalable, segura y altamente duradera para datos.

### Características principales de Amazon S3:
1. **Almacenamiento de objetos**: 
   - S3 organiza los datos en "buckets" (contenedores) y permite almacenar archivos, llamados objetos, junto con metadatos asociados.
   - Cada objeto puede tener hasta 5 TB de tamaño.

2. **Escalabilidad y disponibilidad**:
   - S3 escala automáticamente para manejar grandes cantidades de datos y tráfico.
   - Diseñado para ofrecer una disponibilidad del 99.99% y una durabilidad del 99.999999999% (11 nueves).

3. **Clases de almacenamiento**:
   - Ofrece diferentes clases según el caso de uso:
     - **S3 Standard**: Para acceso frecuente.
     - **S3 Intelligent-Tiering**: Optimiza automáticamente los costos moviendo datos entre clases según patrones de acceso.
     - **S3 Standard-IA (Infrequent Access)**: Para datos accedidos con poca frecuencia.
     - **S3 Glacier y Glacier Deep Archive**: Para archivado a largo plazo.

4. **Seguridad**:
   - Ofrece controles de acceso detallados mediante políticas, listas de control de acceso (ACL) y cifrado de datos (en reposo y en tránsito).
   - Compatible con estándares de cumplimiento como GDPR, HIPAA y más.

5. **Integración con otros servicios AWS**:
   - Funciona con servicios como AWS Lambda, Amazon EC2, Amazon RDS, y más.

6. **Costos**:
   - Basado en el modelo de pago por uso, los costos dependen del almacenamiento, solicitudes y transferencia de datos.

### Casos de uso comunes:
- **Copia de seguridad y recuperación**: Ideal para almacenar respaldos de datos.
- **Almacenamiento de contenido multimedia**: Hospedaje de imágenes, videos o documentos.
- **Data lakes y análisis de datos**: Actúa como un repositorio central para análisis de big data.
- **Hosting de sitios web estáticos**: Permite almacenar y servir sitios web estáticos.

En resumen, Amazon S3 es una herramienta versátil y confiable para manejar necesidades de almacenamiento en la nube, desde simples respaldos hasta arquitecturas complejas de datos.