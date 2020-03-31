# GCI
Tarea de Teoria de la computacion, programa para una ramatica dada.

Dada la gramática

EXPR -> TERM + EXPR | TERM - EXPR | TERM
TERM -> FACT * TERM | TERM / EXPR | FACT
FACT -> NUM | ( EXPR) | -FACT
NUM -> 0 | 1 | 2 | ... | 9

Escriba un reconocedor que la implemente y pruebe su programa con tres diferentes cadenas (dos correctas y una incorrecta )). Entregue su código fuente y las imágenes de sus tres corridas del programa
