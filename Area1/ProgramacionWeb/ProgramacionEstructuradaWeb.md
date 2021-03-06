### Programación estructurada para Web: ###
**Definición:** Conjunto de técnicas que han ido evolucionando y aumentando considerablemente la productividad del programa reduciendo el tiempo de depuración y mantenimiento del mismo. Utiliza un número limitado de estructuras de control, reduciendo así considerablemente los errores. 

**Conceptos notables:**

  - **MVC:** _Model View Controller_. Patrón de arquitectura de software, que separa los datos y la lógica de negocio de una aplicación de la interfaz de usuario y el módulo encargado de gestionar los eventos y las comunicaciones.
Tiene 3 componentes principales:
    - **Model:**  Representación de la información con la cual el sistema opera. Gestiona todos los accesos a dicha información (consultas, actualizaciones, etc.) implementando también los privilegios de acceso que se hayan descrito en las especificaciones de la aplicación (lógica de negocio).
    - **View:**  También conocida como interfaz del usuario. Presenta el 'modelo' (información y lógica de negocio) en un formato adecuado para interactuar, por tanto requiere de dicho 'modelo' la información que debe representar como salida.
    - **Controller:** Es el intermediario entre la vista y el modelo. Responde a eventos (usualmente acciones del usuario) e invoca peticiones al 'modelo' cuando se hace alguna solicitud sobre la información (por ejemplo, editar un documento o un registro en una base de datos). También puede enviar comandos a su 'vista' asociada si se solicita un cambio en la forma en que se presenta el 'modelo' (por ejemplo, desplazamiento o scroll por un documento o por los diferentes registros de una base de datos). 

  - **DOM:** _Document Object Model_, una interfaz de programación que trata al HTML como una estructura de árbol, donde cada elemento es un nodo del árbol y los cambios a los mismos pueden ser realizados de manera programática.
