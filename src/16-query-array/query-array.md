# Operadores de arrays:

### $in => para seleccionar documentos que tengan un campo con un valor que coincida con cualquiera de los valores especificados en un array.

### $nin => selecciona documentos que no tengan un campo con un valor que coincida con ninguno de los valores especificados en un array. (Contrario a $in)

### $all => selecciona documentos que tengan un campo con un array que contenga todos los valores especificados en la consulta.

### $elemMatch => para seleccionar documentos que tengan un campo con un array que contenga al menos un elemento que cumpla con ciertos criterios de consulta.

### $size => selecciona documentos que tengan un campo con un array de un tamaño específico.