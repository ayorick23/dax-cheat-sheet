# Funciones de Filtro

- `FILTER(<table>, <filter>)`: Devuelve una tabla que es un subconjunto de otra tabla o expresión.
- `CALCULATE(<expression>[, <filter1> [, <filter2> [, …]]])`: Evalúa una expresión en un contexto de filtro.
- `HASONEVALUE(<columnName>)`: Devuelve el valor TRUE cuando el contexto de columnName se ha filtrado a un solo valor distinto. De lo contrario, es FALSE.
- `ALLNOBLANKROW(<table> | <column>[, <column>[, <column>[,…]]])`: Devuelve una tabla que es un subconjunto de otra tabla o expresión.
- `ALL([<table> | <column>[, <column>[, <column>[,…]]]])`: Devuelve todas las filas de una tabla o todos los valores de una columna, ignorando cualquier filtro que se haya podido aplicar.
- `ALLEXCEPT(<table>, <column>[, <column>[,..]])`: Devuelve todas las filas de una tabla excepto aquellas filas que se ven afectadas por los filtros de columna especificados.
- `REMOVEFILTERS([<table> | <column>][, <column>[, <column>[,…]]]])`: Borrar todos los filtros de las tablas o columnas designadas.
