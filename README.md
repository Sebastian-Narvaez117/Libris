# Libris
Repositorio para el desarrollo de la aplicacion de una biblioteca virtual

Aqui se añadira toda la informacion para el desarrollo del proyecto

**Requerimientos del Proyecto**

**Requisitos Funcionales**

* RF1. El sistema permitirá el registro de usuarios mediante un correo electrónico válido.
  
* RF2. El sistema permitirá el inicio de sesión y cierre de sesión con credenciales seguras.
  
* RF3. El sistema permitirá la búsqueda de libros mediante filtros (título, autor, género, categoría).

* RF4. El sistema mostrará dos secciones diferenciadas: Educativa y Entretenimiento.

* RF5. Cada sección mostrará los 10 libros más leídos, indicando únicamente el título.
  
* RF6. En la página principal se mostrarán los libros más leídos con portada y calificación visible.

* RF7. El sistema permitirá leer libros directamente en línea con dos modos: Desplazamiento continuo (scroll)., Una página a la vez.

* RF8 El sistema registrará el historial de lectura mostrando portada y última página leída.

* RF9. El sistema permitirá a los usuarios guardar libros en su biblioteca personal.

* RF10. Los usuarios recibirán notificaciones si un libro guardado recibe actualizaciones.

* RF11. El sistema indicará el estado de las obras (finalizado, en pausa o en emisión).

**Requisitos No Funcionales**

* RNF1. Las contraseñas deberán tener mínimo 8 caracteres, con mayúsculas, minúsculas, números y al menos un carácter especial.

* RNF2. Los datos de los usuarios deberán almacenarse cifrados.

* RNF3. Las búsquedas deberán responder en un máximo de 6 segundos independientemente del dispositivo.

* RNF4. El sistema debe estar disponible al menos el 90% del tiempo.

* RNF5. El sistema debe funcionar correctamente en dispositivos móviles Android y navegadores de escritorio.

* RNF6. La interfaz debe ser responsive, adaptándose a distintos tamaños de pantalla.

* RNF7. La interfaz debe ser intuitiva, diferenciando claramente las secciones de Educación y Entretenimiento.


**Arquitectura Seleccionada**

* Cliente (Frontend): Navegador web con HTML5, CSS3, JavaScript. Opcional: Templates Django.

* Servidor (Backend): Django con Python, estructurado en apps siguiendo buenas prácticas.

* Base de datos: MySQL, gestionada mediante el ORM de Django.

* Patrón: MVC (Modelo Vista Controlador)


**Estándares de Codificación Adoptados**

* Python/Django: PEP 8 (nombres de variables, indentación de 4 espacios, docstrings).

* Frontend:
* HTML5 semántico.
* CSS con convenciones BEM.

* Base de datos:
* Nombres de tablas en singular/plural consistente.
* Uso de claves primarias con id autoincremental.


**Flujo de Trabajo con Gitflow** 

* Branch principal: main → siempre estable.
*-Branch de desarrollo: develop.
* Branches de soporte:
  * feature/nombre → nuevas funcionalidades.
  * release/x.x.x → preparar una versión.
  * hotfix/nombre → arreglos críticos en producción.


**Instrucciones de Ejecución**
