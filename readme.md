# Positioning en CSS

El posicionamiento en CSS permite colocar elementos en diferentes lugares dentro de un documento HTML. La propiedad position define el método de posicionamiento para un elemento y puede tomar los siguientes valores: static, relative, absolute, fixed y sticky.

1. Position: static
Es el valor por defecto. Los elementos se posicionan de acuerdo al flujo normal del documento.
Uso: No se usa explícitamente ya que es el valor por defecto.

2. Position: relative
El elemento se posiciona en relación a su posición original en el flujo del documento.

3. Position: absolute
El elemento se posiciona en relación a su ancestro posicionado más cercano (no static). Si no hay un ancestro posicionado, se posiciona en relación al viewport.

4. Position: fixed
El elemento se posiciona en relación al viewport y no se mueve al hacer scroll.

5. Position: sticky
Descripción: El elemento se comporta como relative hasta que se desplaza a una posición específica en el scroll, momento en el que se comporta como fixed.

# Propiedades de un Elemento Posicionado

Para que las propiedades top, right, bottom y left tengan efecto, el elemento debe tener una propiedad position distinta de static. Aquí están las descripciones y usos de cada una:

1. Top: Desplaza el borde superior de un elemento desde su posición normal (para relative) o desde el borde superior de su contenedor posicionado (para absolute, fixed y sticky).

2. Right: Desplaza el borde derecho de un elemento desde su posición normal (para relative) o desde el borde derecho de su contenedor posicionado (para absolute, fixed y sticky).

3. Bottom: Desplaza el borde inferior de un elemento desde su posición normal (para relative) o desde el borde inferior de su contenedor posicionado (para absolute, fixed y sticky).

4. Left: Desplaza el borde izquierdo de un elemento desde su posición normal (para relative) o desde el borde izquierdo de su contenedor posicionado (para absolute, fixed y sticky).

5.  Z-Index: Controla el orden de apilamiento de los elementos posicionado. Un elemento con un z-index más alto se superpone a un elemento con un z-index más bajo.

