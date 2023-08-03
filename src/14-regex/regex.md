## Resumen 

### Todas las consultas se pueden efectuar correctamente sin usar el operador $regex.

## Consultas

### /line/ => nos devuelve los doc que tengan la palabra line, exactamente como esta escrita.

### /line/i => nos devuelve los doc que tengan la palabra line, ignorando minus-mayus.

### /line$/ => nos devuelve los doc que terminen con la palabra line.

### /^Single/ => nos devuelve los doc que empiecen con la palabra Single.

### /^S/m => nos devuelve los doc que empiecen por S, ignorando los saltos de linea. Ej:( Single line Second line ).