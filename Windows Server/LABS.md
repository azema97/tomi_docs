# 🔐 LABS - Local Administrator Password Solution

La **Local Administrator Password Solution (LAPS)** es una herramienta desarrollada por Microsoft que ayuda a gestionar las contraseñas de las cuentas de administrador local en equipos que están unidos a un dominio. Aquí tienes un resumen de sus principales características:

- **Gestión de contraseñas**: LAPS genera contraseñas únicas y aleatorias para las cuentas de administrador local en cada equipo del dominio.
- **Almacenamiento seguro**: Las contraseñas se almacenan en Active Directory (AD) en un atributo confidencial, protegido por listas de control de acceso (ACL).
- **Acceso autorizado**: Solo usuarios autorizados pueden leer o solicitar la restablecimiento de las contraseñas.
- **Seguridad mejorada**: Ayuda a mitigar ataques como "Pass-the-Hash" y "lateral-traversal" al evitar el uso de contraseñas comunes en todos los equipos.
- **Compatibilidad**: Funciona con Windows Server 2019 y versiones posteriores, así como con Windows 10 y Windows 11.

En resumen, LAPS simplifica la gestión de contraseñas y mejora la seguridad de los equipos en un entorno de dominio from Official. 

[Descargar LAPS](https://www.microsoft.com/en-us/download/details.aspx?id=46899&gt).

---

### Configurar LABS en Windows Server

[Instalar y configurar Windows LAPS (Local Administrator Password Solution) en Windows Server 2022](https://blog.ragasys.es/instalar-y-configurar-windows-laps-local-administrator-password-solution-en-windows-server-2022?form=MG0AV3)

Para implementar LAPS en Windows Server, sigue estos pasos:

1. **Actualizar el esquema de Active Directory**: Primero, asegúrate de que el esquema de Active Directory esté actualizado. Abre PowerShell en el controlador de dominio y ejecuta el comando:
   ```powershell
   Import-Module LAPS
   Update-LapsADSchema
   ```

2. **Concesión de permisos**: Configura los permisos necesarios en Active Directory para permitir que LAPS modifique los atributos de las cuentas de equipo. Ejecuta el siguiente comando en PowerShell:
   ```powershell
   Set-LapsADComputerSelfPermission -Identity "OU=Equipos,DC=ejemplo,DC=com"
   ```

3. **Configurar permisos de consulta**: Asegúrate de que los permisos de consulta estén configurados correctamente para que los usuarios autorizados puedan leer las contraseñas almacenadas. Ejecuta:
   ```powershell
   Set-AdmPwdComputerSelfPermission -Identity "OU=Equipos,DC=ejemplo,DC=com"
   ```

4. **Configurar permisos de restablecimiento**: Configura los permisos para que los usuarios autorizados puedan restablecer las contraseñas. Ejecuta:
   ```powershell
   Set-AdmPwdResetPasswordPermission -Identity "OU=Equipos,DC=ejemplo,DC=com"
   ```

5. **Instalar el cliente LAPS**: Instala el cliente LAPS en los equipos que formarán parte del dominio. Esto se puede hacer manualmente o mediante un script de implementación.

6. **Configurar la política de contraseñas**: Configura la política de contraseñas para determinar el período de validez y otros parámetros. Esto se puede hacer a través de la interfaz de administración de LAPS o mediante PowerShell.

7. **Probar la implementación**: Una vez configurado todo, prueba la implementación para asegurarte de que las contraseñas se generan y almacenan correctamente en Active Directory.


---

### Vídeos
- [What is Microsoft (LAPS) Local Administrator Password Solution?](https://youtu.be/H5Bx2_9JgHc)
- [Cómo funciona LAPS de Windows Server para administrar Passwords locales en el dominio](https://youtu.be/7EUJZ9B_uYk)