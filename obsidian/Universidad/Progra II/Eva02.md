## Paginas maestras
¿Que es una pagina maestra?
es una pagina ASP.NET regular en cuanto contiene tanto partes de cogido html como código c#, pero en lugar de definir html para una pagina especifica, el contenido de la estructura común del sitio web. cada nueva pagina asp.net puede ser configurada para usar la apariencia de la pagina maestra y al actualizar  la pagina maestra todas las paginas que están asociadas con ella.
## Panorama de una pagina maestra
los programas para diseñar sitios web y crear paginas web han ofrecido características de plantilla desde hace algún tiempo. Esto significa que se puede crear una sola pagina de plantilla que contenga tanto el contenido común como las regiones que pueden ser personalizadas por cada pagina que use la plantilla

una pagina maestra es una plantilla que contiene dos porciones 
- Contenido: aparece en cada pagina de contenido.
- regiones: son marcaciones que pueden ser personalizadas por la pagina del contenido.


## Síntesis
Las paginas maestras es una pagina ASP.NET el cual esta asociada a otras paginas que llevan contenido, todos lo que se defina en la pagina maestra se hereda a las otras paginas de contenido, dentro de las paginas maestras hay regiones de contenido el cual puede ser asociada con el contenido de las otras paginas mediante la etiqueta `ContentPlaceHolder`

