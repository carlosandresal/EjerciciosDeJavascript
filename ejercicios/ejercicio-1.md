# Sentencia for

Este tipo de bucle ejecuta las instruccicones de su bloque recorriendo un rango de valores de forma secuencial haste que la condicion deja de cumplirse (valor falso). Su sintaxis es la siguiente:
```
for ( expresión inicicial; condición; expresión actualización) {
	//Mi bloque de instrucciones 
}
```
* Expresión inicial: se utiliza para inicializar una o varias variables que sirvan a modo de contacto, aunque puede contener expresiones más complejas. Representa el primer valor de todo rango que se va  a utilizar dentro del bucle.
* Condición: evaúa en cada iteracion si el valor de una variable(normalmente la usada como contador) cumple la expresión especificada. Si no lo hace(valor falso), significa que el bucle finaliza.
* Expresión actualización: se utiliza para actualizar el valor del contador declarado en la expresión inicial, con el fin de hacer  falsa la condición en algun momento.SE puede usar cualquier tipo de expresión, aunque lo más común es hacer uso del operador de incremento (++).

Veamos un rápido ejemplo para clarar el funcionamiento de esta estructura

```
for (var x = 1; x < 10; x++) {
    console.log(' la variable x vale ' + x + ' en la iteracion(vuelta)' + x );
}
```

## Ejercicio N° 1

Crear una variable que reciba un string y retorne la misma, pero agregando después de cada carácter su índice correspondiente. Es decir, que retorne el mismo string transformado de la siguiente forma.

```

    En el indice 0 posición 1 es igual a la letra C
    En el indice 1 posición 2 es igual a la letra a
    En el indice 2 posición 3 es igual a la letra r
    En el indice 3 posición 4 es igual a la letra l
    En el indice 4 posición 5 es igual a la letra o
    En el indice 5 posición 6 es igual a la letra s

```