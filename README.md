Explicación del Codigo.
Almacenamiento y recuperación de inventarios en archivos:
Método cargar_desde_archivo: Este método se ejecuta al iniciar el programa para cargar los productos desde el archivo inventario.txt. Si el archivo no existe, se notifica al usuario y el archivo se creará cuando se añadan productos.
Método guardar_en_archivo: Este método se llama después de cada operación (añadir, eliminar, actualizar) para guardar el estado actual del inventario en inventario.txt.
Manejo de excepciones:
Se implementa manejo de excepciones con try-except para capturar errores comunes como FileNotFoundError, PermissionError, y otros posibles errores durante la manipulación de archivos.
Interfaz de usuario en la consola:
Se han añadido mensajes informativos para notificar al usuario sobre el éxito o fallo de las operaciones de archivo, como guardar o cargar el inventario.
