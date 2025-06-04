# Operadores en DAX

| Operadores de comparación | Significado           |
| ------------------------- | --------------------- |
| `=`                       | Igual a               |
| `==`                      | Estrictamente igual a |
| `>`                       | Mayor que             |
| `<`                       | Menor que             |
| `>=`                      | Mayor o igual que     |
| `<=`                      | Menor o igual que     |
| `<>`                      | No es igual           |

| Operador de texto | Significado                | Ejemplo                  |
| ----------------- | -------------------------- | ------------------------ |
| `&`               | Concatena valores de texto | `[Ciudad]&”, “&[Estado]` |

| Operador lógico | Significado                   | Ejemplo                                            |
| --------------- | ----------------------------- | -------------------------------------------------- |
| `&&`            | Condición `AND`               | `([Ciudad] = “SaS”) && ([Ubicación] = “Centro”)`   |
| `\|\|`          | Condición `OR`                | `([Ciudad] = “SaS”) \|\| ([Ubicación] = “Centro”)` |
| `IN {}`         | Condición `OR` para cada fila | `Producto[Color] IN {”Azul”, “Rojo”, “Gris”}`      |
