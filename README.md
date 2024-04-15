
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

-Muestra todos los usuarios en una tabla, permitiendo la visualización rápida de la información. También proporciona enlaces para agregar, editar o eliminar usuarios.
- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

-Permite a los usuarios ingresar nuevos detalles de usuario a través de un formulario, con validación de datos para garantizar la integridad de la información antes de enviarla a la base de datos.
- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

-Ofrece la capacidad de modificar los detalles de usuarios existentes, presentando un formulario prellenado con la información actual y permitiendo la actualización de los datos en la base de datos.
- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

-Facilita la eliminación de usuarios de la base de datos basada en su ID, proporcionando una forma de mantener la información actualizada y limpia
- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.
 
Además de las tecnologías utilizadas y las funcionalidades descritas, aquí hay más información sobre la aplicación PHP CRUD:

### Seguridad y Validación de Datos:
- La aplicación puede incorporar medidas de seguridad como la validación de datos de entrada para prevenir ataques de inyección de SQL o de scripts entre sitios (XSS).
- Se pueden aplicar técnicas como la sanitización de datos para asegurar que los datos ingresados por los usuarios sean seguros antes de ser almacenados en la base de datos.

### Escalabilidad:
- Aunque esta aplicación es una demostración básica, se puede mejorar para manejar grandes volúmenes de datos y aumentar su escalabilidad.
- Se pueden implementar técnicas como la paginación para gestionar grandes conjuntos de resultados de manera eficiente y mejorar el rendimiento.

### Internacionalización y Localización:
- Para hacer la aplicación más accesible a una audiencia global, se pueden agregar funciones de internacionalización y localización.
- Esto incluiría la capacidad de mostrar la interfaz de usuario en varios idiomas y adaptarse a diferentes formatos de fecha, hora y moneda según la región del usuario.

### Control de Versiones y Pruebas:
- Es importante mantener un control de versiones adecuado utilizando herramientas como Git para rastrear cambios en el código y colaborar de manera efectiva en el desarrollo.
- Se pueden realizar pruebas unitarias y de integración para garantizar que la aplicación funcione correctamente en diferentes escenarios y entornos.

### Documentación y Comentarios:
- La documentación clara del código y los comentarios significativos ayudarán a otros desarrolladores a comprender fácilmente el funcionamiento de la aplicación y a realizar contribuciones o modificaciones si es necesario.
- También se puede proporcionar documentación para los usuarios finales sobre cómo utilizar la aplicación y sus diferentes características.



## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

