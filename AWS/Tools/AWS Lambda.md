# 🧪 AWS Lambda

**AWS Lambda** es un servicio de computación sin servidor (serverless) ofrecido por **Amazon Web Services (AWS)**. Permite ejecutar código en respuesta a eventos sin necesidad de administrar servidores. Con Lambda, solo pagas por el tiempo de ejecución del código y los recursos consumidos, eliminando la necesidad de mantener infraestructura activa.

---

### **Características principales de AWS Lambda:**

1. **Computación sin servidor**:
   - No necesitas provisionar, administrar ni escalar servidores.
   - AWS Lambda ejecuta el código automáticamente cuando se produce un evento.

2. **Activación basada en eventos**:
   - Se integra con una amplia gama de servicios de AWS, como:
     - **Amazon S3**: Ejecuta código al cargar o modificar archivos.
     - **Amazon DynamoDB**: Responde a cambios en tablas de datos.
     - **Amazon API Gateway**: Maneja solicitudes HTTP/HTTPS.
     - **Amazon SNS y SQS**: Procesa mensajes y eventos.
     - **Amazon CloudWatch**: Automatiza tareas basadas en métricas o logs.

3. **Escalabilidad automática**:
   - Lambda escala automáticamente la ejecución del código en función del número de eventos.
   - Puede manejar desde unas pocas solicitudes por segundo hasta miles.

4. **Modelos de ejecución flexibles**:
   - **Invocación sincrónica**: El cliente espera el resultado.
   - **Invocación asincrónica**: Los eventos se procesan en segundo plano.
   - **Ejecución en tiempo real**: Ideal para flujos de trabajo reactivos.

5. **Compatibilidad con múltiples lenguajes**:
   - Soporta lenguajes como Python, Node.js, Java, Go, Ruby, .NET, y más.
   - Permite usar imágenes de contenedor personalizadas.

6. **Facturación basada en uso**:
   - Pagas solo por el tiempo que tu código está en ejecución, en incrementos de milisegundos.
   - Incluye una capa gratuita (1 millón de invocaciones y 400,000 GB-segundos al mes).

7. **Gestión simplificada**:
   - AWS Lambda se encarga de la administración del entorno de ejecución, como la asignación de recursos, mantenimiento y actualizaciones.

---

### **Casos de uso comunes de AWS Lambda**:

1. **Procesamiento de datos**:
   - Procesar archivos cargados en Amazon S3 (como redimensionar imágenes o transformar datos).
2. **Automatización de tareas**:
   - Responder a eventos en tiempo real, como la actualización de bases de datos.
3. **Backend para aplicaciones**:
   - Crear microservicios o APIs sin necesidad de gestionar servidores.
4. **Integración de servicios**:
   - Conectar servicios de AWS para flujos de trabajo personalizados.
5. **Procesamiento de transmisiones en tiempo real**:
   - Procesar datos en flujos de Amazon Kinesis o DynamoDB Streams.

---

### **Ventajas de AWS Lambda**:

1. **Costo-efectivo**:
   - Solo pagas por lo que usas, sin costos iniciales.
2. **Alta escalabilidad**:
   - Escala automáticamente según la demanda.
3. **Sin infraestructura**:
   - Elimina la necesidad de administrar servidores.
4. **Integración nativa con AWS**:
   - Funciona perfectamente con otros servicios de AWS.
5. **Reducción del tiempo de desarrollo**:
   - Facilita la creación rápida de soluciones sin preocuparse por la infraestructura.

---

### **Limitaciones de AWS Lambda**:

1. **Tiempo máximo de ejecución**:
   - Cada función tiene un límite de 15 minutos por invocación.
2. **Restricciones de recursos**:
   - Memoria limitada a 10 GB y almacenamiento temporal a 512 MB.
3. **Cold starts**:
   - Las funciones pueden experimentar latencia adicional al ejecutarse por primera vez después de un período de inactividad.

---

### **Resumen**:
AWS Lambda es una solución poderosa y flexible para ejecutar código sin servidores. Es ideal para aplicaciones basadas en eventos, automatización de tareas y desarrollo ágil. Al combinarlo con otros servicios de AWS, permite crear arquitecturas altamente escalables y costo-efectivas.