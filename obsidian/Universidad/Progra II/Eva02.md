## Paginas maestras
¿Que es una pagina maestra?
es una pagina ASP.NET regular en cuanto contiene tanto partes de codigo html como codigo c#, pero en lugar de definir html para una pagina especifica, aloka el contenido de la estructura comun del sitio web. cada nueva pagina asp.net pueder ser configurada para usar la apariencia de la pagina maestra y al actualizar  la pagina maestra todas las paginas que estan asociadas con ella.
## Panorama de una pagina maestra
los programas para diseñar sitios web y crear paginas web han ofrecido caracteristicas de plantilla desde hace algun tiempo. Esto significa que se puede crear una sola pagina de plantilla que contenga tanto el contenido comun cocmo las regiones que pueden ser personalizadas por cada pagina que use la plantilla

una pagina maestra es una plantilla que contiene dos porciones 
- Contenido: aparece en cada pagina de contenido.
- regiones: son marcaciones que pueden ser personalizadas por la pagina del contenido.


## Sintesis
Las paginas maestras es una pagina ASP.NET el cual esta asociada a otras paginas que llevan contenido, todos lo que se defina en la pagina maestra se hereda a las otras paginas de contenido, dentro de las paginas maestras hay regiones de contenido el cual puede ser asociada con el contenido de las otras paginas mediante la etiqueta `ContentPlaceHolder`

