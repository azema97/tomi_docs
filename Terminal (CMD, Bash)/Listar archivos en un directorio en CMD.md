# Listar archivos y documentos con CMD 📁📄

Para listar documentos en la línea de comandos de Windows (CMD), puedes usar el comando `dir`. Aquí tienes cómo hacerlo:

1. Abre el símbolo del sistema (CMD).
2. Navega al directorio donde quieres listar los documentos usando el comando `cd`.
3. Usa el comando `dir` para listar los archivos y directorios.

---

En la línea de comandos de Windows (CMD), hay varias opciones para listar archivos y directorios con el comando `dir`. Aquí tienes algunas de las más útiles:

- **`dir /A`**: Muestra archivos con atributos específicos. Por ejemplo, `dir /A:H` muestra archivos ocultos.
- **`dir /B`**: Muestra solo los nombres de los archivos y carpetas (formato simple).
- **`dir /S`**: Lista archivos en el directorio actual y en todos los subdirectorios.
- **`dir /O`**: Ordena la lista. Puedes especificar criterios como `N` para nombre, `E` para extensión, `D` para fecha, etc. Por ejemplo, `dir /O:N` ordena por nombre.
- **`dir /P`**: Muestra la lista página por página, útil para directorios con muchos archivos.
- **`dir /Q`**: Muestra el propietario de cada archivo.
- **`dir /T`**: Controla qué fecha se muestra (creación, último acceso, última modificación). Por ejemplo, `dir /T:C` muestra la fecha de creación.

Puedes combinar estas opciones según tus necesidades. Por ejemplo, `dir /A:H /B` mostrará solo los nombres de los archivos ocultos.