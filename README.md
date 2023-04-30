
##Despliegue de apps Spring Boot en Railway

Crear archivo 'system.properties' en el proyecto con el contenido:

java.runtime.version=19

1. Crear cuenta en Railway.com y github.com
2.  Tener configurado el git en el ordenador
    1. 'git cofig --global user.name "Jorge Gómez"
    2. 'git cofig --global' user.email "jagmig@outlook.com"
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4. Desde Railway, crear app y elegir el método Github y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy. Y listo. 