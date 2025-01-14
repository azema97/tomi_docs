# Validación de Datos - Campos con valores únicos

Puedes lograr que una columna de una tabla solo permita valores únicos o en blanco la función de **Validación de Datos** en Excel. Aquí te dejo los pasos para configurar esta validación:

1. **Selecciona la columna** donde deseas aplicar la validación.
2. Ve a la pestaña **"Datos"** en la cinta de opciones.
3. Haz clic en **"Validación de datos"** en el grupo de herramientas de "Herramientas de datos".
4. En la ventana de Validación de Datos, selecciona la pestaña **"Configuración"**.
5. En el campo **"Permitir"**, selecciona **"Personalizada"**.
6. En el campo **"Fórmula"**, ingresa la siguiente fórmula:
   ```excel
   =CONTAR.SI(A:A; A1)<=1
   ```
   Esta fórmula asume que estás trabajando en la columna A. Si estás trabajando en otra columna, ajusta la referencia de la columna en la fórmula.

7. Ve a la pestaña **"Mensaje de entrada"** y escribe un mensaje que aparecerá cuando alguien seleccione una celda en la columna.
8. Ve a la pestaña **"Mensaje de error"** y escribe el mensaje que aparecerá si alguien intenta ingresar un valor duplicado. Por ejemplo:
   - **Título:** "Valor duplicado"
   - **Mensaje de error:** "Este valor ya existe en la columna. Por favor, ingrese un valor único."

9. Haz clic en **"Aceptar"** para aplicar la validación.

Con estos pasos, Excel mostrará un mensaje de error si alguien intenta ingresar un valor duplicado en la columna seleccionada.