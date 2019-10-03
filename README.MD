# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de emphasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~.
- Aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes

![github](https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg)

# Code Snippets
Codigo en java
```Java
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}

```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Agustin | Diaz | 1265431 |

# Citas
Esto es un texto referente a una cita que pondermos debajo
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otra cita.

# Lineas divisores
Esto es un texto que sera divido por guiones.

---
Esto es otro texto dividido por asteriscos

***

Esto es otro texto dividido por guiones bajos

___

## Saltos de linea 
Esto es nuestro primer parrafo.
Esto es nuestro segundo parrafo.
