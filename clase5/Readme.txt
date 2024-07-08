# Clase número 5

## Fecha: 03/07/2024

### Tema: Flexbox y grid


### Flexbox
 - Trabaja con ejes: permite alinear los elementos tanto de manera vertical como horizontal
 - Se aplica en el elemento padre (contenedor) pero se usa en los elementos hijos (items)
 - Flex en modo por defecto, genera una disposición en fila (u horizontal)
 - Propiedades más usadas:
    - Justify-content
        * space-between: deja los elementos con un espacio igual entre ellos
        * center: centra el contenido dejando espacios iguales a los extremos
        * space-around: similar al primero pero considera espacios en los extremo (dejando los espacios de extremos igual) y entre los elementos
        * space-evenly: deja espacios iguales entre elementos 
    - flex-direction: designa si el eje sobre el cual se van a posicionar los elementos sera en fila (de izq a der o viceversa) o en columna (de abajo arriba o viceversa)
    - flex-wrap: nowrap ocupan todos los elementos un espacio similar, con wrap pasa los elementos que superen el tamaño del div a la linea siguiente