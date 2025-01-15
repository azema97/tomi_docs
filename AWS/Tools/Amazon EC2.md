# 🖥️ Amazon EC2

Amazon EC2 (**Elastic Compute Cloud**) es un servicio de computación en la nube de **Amazon Web Services (AWS)** que permite a los usuarios lanzar y administrar máquinas virtuales, conocidas como **instancias**, para ejecutar aplicaciones y cargas de trabajo. Es altamente escalable, flexible y se adapta a una variedad de necesidades de computación.

---

### **Características principales de Amazon EC2:**

1. **Instancias personalizables**:
   - Puedes elegir el tipo de instancia (CPU, memoria, almacenamiento y capacidad de red) que mejor se adapte a tus necesidades.
   - Hay cientos de configuraciones disponibles para optimizar costos y rendimiento.

2. **Elasticidad**:
   - Escala vertical y horizontalmente según sea necesario.
   - Puedes agregar o eliminar instancias en función de la demanda de tu aplicación.

3. **Variedad de tipos de instancias**:
   - **General Purpose**: Para cargas de trabajo equilibradas (ej. T, M).
   - **Compute Optimized**: Para aplicaciones que requieren mucha CPU (ej. C).
   - **Memory Optimized**: Para aplicaciones intensivas en memoria (ej. R, X).
   - **Storage Optimized**: Para procesamiento de grandes volúmenes de datos (ej. I, D).
   - **Accelerated Computing**: Para tareas de alto rendimiento como aprendizaje automático (ej. P, G).

4. **Opciones de almacenamiento**:
   - Compatible con **Amazon EBS** (almacenamiento en bloque).
   - **Almacenamiento en instancias** para datos temporales.
   - Integración con **Amazon S3** y **Amazon EFS** para almacenamiento adicional.

5. **Seguridad**:
   - Usa **Amazon VPC** para un entorno de red seguro y aislado.
   - Ofrece grupos de seguridad y control de acceso detallado para gestionar quién puede acceder a las instancias.

6. **Opciones de precios**:
   - **On-Demand**: Paga solo por lo que usas, sin compromisos a largo plazo.
   - **Reserved Instances**: Costos más bajos a cambio de un compromiso de uso a largo plazo.
   - **Spot Instances**: Acceso a capacidad no utilizada a precios reducidos.
   - **Savings Plans**: Descuentos flexibles según uso comprometido.

7. **Variedad de sistemas operativos**:
   - Soporta Linux, Windows y otros sistemas operativos personalizados.

---

### **Casos de uso comunes:**
1. **Hospedaje de aplicaciones web**: Despliega servidores web y backend escalables.
2. **Bases de datos**: Aloja bases de datos relacionales o no relacionales.
3. **Análisis de datos**: Procesa grandes volúmenes de datos en tiempo real.
4. **Aprendizaje automático**: Entrena modelos con GPU de alto rendimiento.
5. **Pruebas y desarrollo**: Proporciona entornos aislados para desarrollo de software.

---

### **Ventajas de Amazon EC2:**
- **Flexibilidad**: Personalización total de las instancias según necesidades.
- **Escalabilidad**: Ajuste dinámico a la carga de trabajo.
- **Global**: Despliegue en regiones de todo el mundo.
- **Costo-efectivo**: Opciones de precios adaptadas al uso.

Amazon EC2 es una solución poderosa y versátil para empresas de cualquier tamaño, desde startups hasta grandes corporaciones, que buscan capacidad de computación confiable y escalable.