## Que es SQL?
#universidad 

SQl (Structures Query Lanaguage) es un lenguaje de consultas dedicado a las bases de datos relacionales y a la manipulación de estas fue creado por IBM en la de década de 1970, SQL es un estandar que permite interactuar con sistemas de bases de datos como MySQL, PostgreSQL , ORACLE , SQL SERVER.

SQL es un lenguaje declarativo , es decir, se tiene que describir lo que se desea obtener mas que en como obtenerlo.

Entre las diversas operaciones que permite SQL son:

1. Consultas: Recuperar datos específicos de una base de datos

```SQL
SELECT nombre,edad FROM usuarios WHERE edad > 30
```


2. Inserciones: Añadir nuevos registros a una base de datos.
```SQL
INSERT INTO usuarios (nombre, edad) VALUES ('Juan', 25);
```

3. Actualizaciones: Modificar datos existentes en una base de datos.
```SQL
UPDATE usuarios SET edad = 26 WHERE nombre = 'Juan';
```

4. Eliminaciones: Borrar registros de una base de datos.
```SQL
DELETE FROM usuarios WHERE nombre = 'Juan';
```

5. Creación de tablas y bases de datos: Definir nuevas tablas y estructuras de bases de datos.

```SQL
CREATE TABLE usuarios (
    id INT PRIMARY KEY,
    nombre VARCHAR(50),
    edad INT
);
```

6. Control de acceso y permisos: Gestionar quien tiene acceso a que datos y que operaciones pueden realizar

```SQL

GRANT SELECT, INSERT ON usuarios TO 'usuario1';

```



