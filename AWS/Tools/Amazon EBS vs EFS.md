# Amazon EBS vs EFS

---

### **¿Qué es Amazon EBS?**
**Amazon Elastic Block Store (EBS)** es un servicio de **almacenamiento en bloque** diseñado para ser utilizado con instancias de Amazon EC2 (máquinas virtuales). Ofrece almacenamiento persistente, de alto rendimiento y de baja latencia para aplicaciones que requieren acceso a discos duros virtuales.

#### **Características de Amazon EBS:**
1. **Almacenamiento en bloque**:
   - Similar a un disco duro tradicional.
   - Cada volumen EBS se conecta a una sola instancia EC2 a la vez.
2. **Persistencia**:
   - Los datos permanecen almacenados incluso si la instancia EC2 se detiene o se reinicia.
3. **Tipos de volúmenes**:
   - **SSD General Purpose (gp3/gp2)**: Para uso general.
   - **Provisioned IOPS (io1/io2)**: Para aplicaciones con alta carga de entrada/salida.
   - **HDD Throughput Optimized (st1)**: Para grandes volúmenes de datos secuenciales.
   - **Cold HDD (sc1)**: Para almacenamiento infrecuente y económico.
4. **Respaldo**:
   - Se pueden tomar instantáneas (snapshots) para copias de seguridad y recuperación.
5. **Casos de uso**:
   - Bases de datos, aplicaciones empresariales, y almacenamiento de datos transaccionales.

---

### **¿Qué es Amazon EFS?**
**Amazon Elastic File System (EFS)** es un servicio de **almacenamiento en red** basado en sistemas de archivos que permite a múltiples instancias EC2 acceder a los mismos datos simultáneamente, como si se tratara de un sistema de archivos compartido.

#### **Características de Amazon EFS:**
1. **Almacenamiento de sistemas de archivos**:
   - Proporciona acceso compartido a un sistema de archivos para múltiples instancias EC2.
   - Compatible con el protocolo NFS (Network File System).
2. **Escalabilidad automática**:
   - Se ajusta automáticamente al crecimiento o reducción de datos sin necesidad de gestión manual.
3. **Clases de almacenamiento**:
   - **Standard**: Para acceso frecuente.
   - **One Zone**: Para datos no críticos, almacenados en una sola zona de disponibilidad.
   - **Infrequent Access (IA)**: Para datos menos accedidos, con menor costo.
4. **Durabilidad y disponibilidad**:
   - Diseñado para ofrecer alta disponibilidad y durabilidad (replicado en múltiples zonas de disponibilidad).
5. **Casos de uso**:
   - Sistemas de archivos compartidos, aplicaciones web distribuidas, y análisis de big data.

---

### **Diferencias clave entre Amazon EBS y Amazon EFS:**

| **Aspecto**              | **Amazon EBS**                              | **Amazon EFS**                              |
|--------------------------|---------------------------------------------|---------------------------------------------|
| **Tipo de almacenamiento** | Almacenamiento en bloque                  | Almacenamiento de sistemas de archivos      |
| **Acceso**                | Solo una instancia EC2 a la vez            | Acceso compartido por múltiples instancias  |
| **Escalabilidad**         | Capacidad fija, ajustable manualmente      | Escalabilidad automática                    |
| **Casos de uso**          | Bases de datos, almacenamiento transaccional | Sistemas compartidos, aplicaciones distribuidas |
| **Durabilidad**           | Alta, pero dentro de una zona de disponibilidad | Alta, replicada entre zonas de disponibilidad |
| **Costo**                 | Más económico para almacenamiento específico | Más costoso debido a la funcionalidad compartida |
| **Protocolos compatibles** | Compatible solo con EC2                   | Compatible con EC2 y protocolo NFS          |

---

### **Resumen:**
- **Usa Amazon EBS** si necesitas un almacenamiento en bloque de alto rendimiento, accesible por una sola instancia EC2, como bases de datos o discos para aplicaciones específicas.
- **Usa Amazon EFS** si necesitas un sistema de archivos compartido y accesible por múltiples instancias EC2, ideal para aplicaciones distribuidas o colaboración en tiempo real.

