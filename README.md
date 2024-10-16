# Práctico: Backend - JPA
Este proyecto consiste en la implementación de una capa de persistencia utilizando JPA (Java Persistence API) con una base de datos H2 en memoria.

## Características de Ejecución

1. En la raíz del proyecto, encontrarás los siguientes archivos y carpetas importantes:
   - `src/main/java`: Contiene el código fuente de las entidades JPA y las clases de lógica de negocio.
   - `src/main/resources/META-INF/persistence.xml`: Archivo de configuración de JPA.
   - `build.gradle`: Archivo de configuración de Gradle para gestionar las dependencias.
2. Configuración del Entorno de Desarrollo:
  - Gradle instalado.
  - IDE (IntelliJ IDEA, Eclipse, VS Code con la extensión Java).
  - JDK 17

   ### Ejecutar desde un IDE (como IntelliJ IDEA o Eclipse)

   - Haz clic derecho en la clase principal y selecciona Run para iniciar la aplicación.

   ### Visualización de la Base de Datos H2

   - Abre el navegador y dirígete a http://localhost:8082.
   - Usa la URL jdbc:h2:tcp://localhost/~/test y las credenciales:
     Usuario: sa
     Contraseña: (vacío)
    
## Siguiente TP: Envers (auditoría)
Link al próximo TP: https://github.com/AgusAstuDev/PbaEnvers.git
