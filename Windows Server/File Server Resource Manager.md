# 📂 File Server Resource Manager (FSRM)

El **File Server Resource Manager** (FSRM) es una herramienta de gestión de almacenamiento incluida en **Windows Server** que permite a los administradores supervisar y controlar cómo se utiliza el almacenamiento en los servidores de archivos. FSRM proporciona un conjunto de funcionalidades avanzadas para gestionar de manera eficiente los datos almacenados y aplicar políticas de uso de almacenamiento en una organización.

---

### **¿Qué es exactamente FSRM?**
FSRM es un conjunto de herramientas administrativas que permite:
1. **Gestionar cuotas** para limitar el espacio de almacenamiento utilizado por los usuarios o carpetas.
2. **Implementar filtros de archivo** para restringir los tipos de archivos que se pueden guardar en ciertas ubicaciones.
3. **Supervisar el uso del almacenamiento** y generar informes detallados sobre los datos almacenados.
4. **Configurar tareas automatizadas** basadas en eventos relacionados con el almacenamiento, como notificaciones cuando se alcanzan ciertos límites.

---

### **Funciones principales de FSRM**

#### 1. **Gestión de cuotas**
- Permite establecer límites de espacio en carpetas o volúmenes específicos.
- Dos tipos de cuotas:
  - **Cuotas rígidas**: Restringen estrictamente el uso de almacenamiento; los usuarios no pueden exceder el límite establecido.
  - **Cuotas flexibles**: Notifican a los usuarios cuando se acercan o alcanzan el límite, pero no bloquean el almacenamiento adicional.

#### 2. **Filtros de archivo**
- Controla qué tipos de archivos se pueden guardar en carpetas específicas.
- Por ejemplo, se puede bloquear el almacenamiento de archivos multimedia (MP3, MP4) en carpetas compartidas de trabajo.
- Soporta listas personalizadas de extensiones permitidas o bloqueadas.

#### 3. **Generación de informes de almacenamiento**
- Proporciona análisis detallados sobre el uso del almacenamiento, como:
  - Archivos más grandes.
  - Archivos más antiguos.
  - Distribución de archivos por tipo.
  - Duplicación de archivos.
- Los informes ayudan a identificar patrones de uso y a optimizar el almacenamiento.

#### 4. **Clasificación de archivos**
- Permite clasificar automáticamente los archivos según sus propiedades, como tipo, tamaño o fecha de modificación.
- Ayuda a implementar políticas de retención o mover archivos obsoletos a ubicaciones específicas.

#### 5. **Gestión automatizada con tareas**:
- FSRM puede ejecutar tareas automatizadas basadas en eventos, como:
  - Enviar notificaciones por correo electrónico cuando se alcanzan ciertos umbrales.
  - Ejecutar scripts personalizados para mover o eliminar archivos.

---

### **Ventajas de usar FSRM**

1. **Control centralizado**:
   - Facilita la administración del uso de almacenamiento en servidores de archivos.
2. **Optimización del almacenamiento**:
   - Ayuda a liberar espacio eliminando o moviendo archivos innecesarios.
3. **Seguridad y cumplimiento**:
   - Restringe el almacenamiento de archivos no autorizados, como contenido personal o potencialmente peligroso.
4. **Notificaciones proactivas**:
   - Informa a los usuarios y administradores sobre problemas de almacenamiento antes de que afecten la operación.
5. **Informes detallados**:
   - Proporciona una visión completa del uso del almacenamiento para planificar futuras necesidades.

---

### **Escenarios comunes de uso**

1. **Gestión de espacio en servidores compartidos**:
   - Establecer cuotas para limitar el uso de espacio por departamento o usuario.
   
2. **Bloqueo de archivos no deseados**:
   - Evitar que los empleados almacenen contenido multimedia personal en carpetas de trabajo.

3. **Cumplimiento de políticas de datos**:
   - Implementar políticas de retención para mover archivos antiguos o no utilizados a un archivo central.

4. **Monitoreo de crecimiento de datos**:
   - Identificar áreas donde el almacenamiento se está agotando y planificar la expansión.

---

### **Cómo configurar FSRM en Windows Server**

1. **Instalar el rol de FSRM**:
   - Desde el Administrador del servidor, agregar el rol **File Server Resource Manager**.

2. **Configurar cuotas**:
   - Crear una plantilla de cuota y aplicarla a carpetas o volúmenes específicos.

3. **Establecer filtros de archivo**:
   - Configurar listas de extensiones permitidas o bloqueadas y aplicarlas a carpetas.

4. **Generar informes**:
   - Configurar informes periódicos para supervisar el uso del almacenamiento.

5. **Configurar tareas automatizadas**:
   - Asociar eventos, como el alcance de un umbral de cuota, con acciones específicas.

---

### **Conclusión**
El **File Server Resource Manager** es una herramienta esencial para organizaciones que necesitan gestionar eficientemente el almacenamiento en sus servidores de archivos. Con FSRM, los administradores pueden implementar políticas de uso, optimizar recursos, garantizar el cumplimiento de normativas y mantener el rendimiento de los sistemas de almacenamiento.