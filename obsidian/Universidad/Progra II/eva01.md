## Arquitectura de las aplicaciones web

### ¿Que es el modelo de capas?
Es una arquitectura la cual consta de capas, cada capa se encarga de realizar una función y se comunica con las capas adyacentes a traves de una interfaz muy bien elaborada

### ¿Que es el modelo de dos capas?
dentro del contexto del desarrollo de software el modelo de dos capas se refiere a una arquitectura cuya lógica de la aplicación consta de dos capas

- Capa presentación: es la interfaz donde el usuario interactuar con la aplicación
- Capa de datos: en esta capa se encuentran los datos provenientes de una base de datos, también esta capa se encarga de acceder a los mismos.

### ¿Que es el modelo de tres capas?
Esta modelo consta de tres capas ya que esta diseñado para superar las limitaciones del modelo de dos capas, a este modelo se le introduce una nueva capa intermedia entre la capa presentación y la capa de datos llamada capa de proceso,el propósito de esta nueva capa es centralizar la lógica del negocio, haciendo que el manejo y la administración de la misma sea mas sencilla.

las capas de este modelo son:
- Capa de presentación: una parte de esta capa esta en el cliente y otra en el servidor, esta capa recoge la información del usuario y la envía al servidor y genera la presentación del proyecto.

- Capa de proceso (servidor web): recibe los datos de la capa de presentación,los procesa para posteriormente interactuar con la capa de datos y realizar las operaciones de negocios correspondientes.

- Capa de datos: almacena datos.

### ¿Que es ASP.NET?

