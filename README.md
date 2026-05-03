1. El archivo: ".gitignore" permite que Git ignore archivos innecesarios, evitando que el historial del proyecto se ensucie.

2. Los archivos que son convenientes ignorar son:
               Archivos del sistema: se crean automáticamente para saber como mostrar los iconos o carpetas, un ejemplo de Windows sería "Thumbs.db".
               Dependencias: son herramientas externas que se descargan para que el programa funcione, un ejemplo sería "node_modules/".
               Archivos de configuración o secretos: allí se guardan contraseñas, llaves de bases o nombres de usuarios.
               Copilados o temporales: son archivos que se crean después de ejecutar un código, por ejemplo, los ".log" son notas que escribe la computadora sobre los errores que hubo.

3. Un archivo ignorado no se sube a GitHub, si está correctamente listado en .gitignore y no fue trackeado previamente, Git ni lo detecta para subirlo.
