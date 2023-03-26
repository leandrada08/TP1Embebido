Se pueden seguir estos pasos para crear un archivo ".gitignore":
1.  Abre un editor de texto y crea un nuevo archivo llamado ".gitignore" en la raíz del repositorio Git.
2.  Agrega las siguientes líneas al archivo ".gitignore":
```
*.html *.java
mi_carpeta/*
```

Esto indica a Git que ignore todos los archivos con la extensión ".html" y ".java". Al igual que estoy omitiendo todos los archivos de la carpaeta mi carpeta
- El asterisco (_) es un comodín que representa cualquier cantidad de caracteres, lo que significa que se puede utilizar para coincidir con cualquier archivo que tenga una determinada extensión o nombre. En el caso del ejemplo mencionado anteriormente, el patrón "_.html" significa "ignorar cualquier archivo con la extensión .html", y el patrón "*.java" significa "ignorar cualquier archivo con la extensión .java".*
Si no se utiliza el asterisco en las líneas del archivo ".gitignore", Git interpretará la línea de manera literal y no como un patrón, lo que significa que solo ignorará archivos que tengan el nombre exacto que se especificó en la línea. Esto no es lo que generalmente se quiere lograr al utilizar un archivo ".gitignore", ya que el objetivo es ignorar todos los archivos de un cierto tipo, independientemente de su nombre exacto. Por lo tanto, es importante incluir el asterisco en las líneas de patrón del archivo ".gitignore".
- Modificacion distinta