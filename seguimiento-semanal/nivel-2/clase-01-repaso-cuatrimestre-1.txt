# Clase N° 1 — Repaso del cuatrimestre 1

**Fecha:** 10/08/2026

## Resumen de la clase
Primera clase del segundo cuatrimestre. Repaso de la diferencia entre `input()` como texto y como número, y cómo convertirlo con `int()`.

## Código / errores trabajados en clase
```python
# primera clase del 2 cuatrimestre
# vamos a comenzar con un repaso
# diferencia entre caracter y numero

nombre = input("ingrese su nombre: ")
# ingrese su nombre: kevin

# la variable input sirve para pedir datos por pantalla, veamos que pasa con un numero
a = 10
b = input("ingrese un numero: ")
# ingrese un numero: 8

a + b
# TypeError: unsupported operand type(s) for +: 'int' and 'str'

# cuando cargo un input lo carga como caracter
# para pasarlo a numero voy a usar la funcion int()
b = int(b)
c = int(input("ingrese un numero"))
# ingrese un numero: 6

a + c
# 16
```

## Observaciones
Antes de llegar al código de arriba, surgieron dos errores comunes al escribir a mano: un typo (`imput` en vez de `input`) y un error de sintaxis por un carácter de más. Sirvieron como ejemplo real de cómo leer un mensaje de error en la consola.
