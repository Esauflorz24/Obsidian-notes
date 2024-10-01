## ¿Qué es MVC?

Es un patrón de arquitectura que separa una aplicación en tres grupos de componentes principales: Modelos, Vistas y controladores, con este patrón , las solicitudes del usuario se enrutan a un controlador que se encarga de trabajar con el modelo para realizar las acciones del usuario a recuperar los resultados de consultas. El controlador elige la vista para mostrar al usuario y proporciona cualquier dato
![[Pasted image 20240926121104.png]]

Con esta delineación de responsabilidades es mas sencillo escalar la aplicación, porque resulta mas fácil codificar, depurar y probar algo que tenga un solo trabajo, Es mas difícil actualizar, probar y depurar código que tenga dependencias repartidas entre dos o mas de estas tres áreas.

## ¿Cuál es la responsabilidad del modelo?

El modelo se encarga de cualquier lógica de negocios u operaciones que esta deba realizar. La lógica de negocios debe encapsularse en el modelo, junto con cualquier lógica de implementación para conversar el estado de la aplicación.


## ¿Cuál es la responsabilidad de las vistas?

Las vistas se encargan de presentar el contenido a través de la interfaz de usuario. usan el motor de vistas Razor para incrustar código .NET en forma HTML. Debería haber la mínima lógica entre las vistas y cualquier lógica en ellas debe estar relacionada con la presentación de contenido.

## ¿Cuál es la responsabilidad del controlador?

Se encargan de controlar la interacción del usuario, trabajan con el modelo y en la ultima instancia, seleccionan una vista para presentarla. En una aplicación de MVC, la vista solo muestra información; el controlador controla y responde a la interacción y los datos que introducen los usuarios. En el patrón de MVC, el controlador es el punto de entrada inicial que se encarga de seleccionar con que tipos de modelo trabajar y que vistas representar.


## Síntesis

MVC es un patrón de diseñó o una arquitectura de software donde se separa el código en tres componentes, Modelo, vistas y controlador, permitiendo que el código sea mas escalable.

El modelo contiene toda la lógica del programa, su estructura, el manejo y solicitudes a una base de datos. Contiene métodos para que se puedan interactuar directamente con los datos proporcionados.

La vista no es nada mas que la interfaz grafica, proporciona al usuario los datos retornados por el modelo. en ASP.NET core las vistas se definen en Razor Pages , que permiten mezclar código HTML con la sintaxis C#.


El controlador es el flujo central del programa, es  un intermediario el cual recibe las solicitudes del cliente. Si el cliente requiere visualizar los datos, el controlador interactúa con el modelo para obtenerlos, y finalmente seleccionar una vista con la cual presentar los resultados, una vez hecho todo este proceso el controlador devuelve la solicitud al usuario para que se puedan visualizar los datos.