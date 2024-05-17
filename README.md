TAREA CLASE 5

Ejercicio de práctica Control de Flujo en Python. Deberán realizar la actividad en un archivo Jupyter Notebook. Y deberán entregar el link del repositorio de GitHub.
    1.	Calculadora Simple: Crea un programa que solicite al usuario dos números y una operación (suma, resta, multiplicación o división). Luego, utilizando estructuras condicionales (if, elif, else), realiza la operación seleccionada e imprime el resultado.
    2.	Contador de Números Pares e Impares: Escribe un programa que recorra una lista de números del 1 al 20. Utilizando un bucle for, determina cuántos de estos números son pares y cuántos son impares. Al final, imprime la cantidad de números pares e impares.
    3.	Validación de Contraseña: Pide al usuario que ingrese una contraseña. Utiliza un bucle while para seguir solicitando la contraseña hasta que coincida con una contraseña predefinida (por ejemplo, "python123"). Muestra un mensaje de éxito cuando la contraseña es correcta.
    4 .	Identificador de Números Primos: Crea un programa que solicite al usuario un número entero. Utilizando un bucle for, verifica si el número es primo (es decir, solo divisible por 1 y por sí mismo). Imprime un mensaje indicando si el número es primo o no.
    5.	Juego de Adivinanza: Genera un número aleatorio entre 1 y 50. Pide al usuario que adivine el número. Utiliza un bucle while para permitir múltiples intentos. Da pistas al usuario si el número ingresado es demasiado alto o bajo. Finaliza el juego cuando el usuario adivine correctamente.

Esta actividad tuve que investigar mediante copilot
informacion: 
a)"es necesario agregar import random al principio del código porque el módulo random de Python proporciona funciones para generar números aleatorios, entre otras cosas. En este caso, utilizamos random.randint(1, 50) para generar un número entero aleatorio entre 1 y 50, que es el número que el usuario debe adivinar en el juego.Sin import random, Python no sabría cómo generar el número aleatorio y el programa no funcionaría."
b) El bloque try y except en Python se utiliza para manejar excepciones durante la ejecución de un programa. Aquí está cómo funciona:
Bloque try:
    Contiene el código que quieres ejecutar.
    Puede generar errores durante su ejecución.
    Si ocurre un error, el control pasa al bloque except.
Bloque except:
    Se ejecuta cuando el bloque try falla debido a un error.
    Debes especificar el tipo de error que esperas manejar.
    Proporciona contexto sobre lo que salió mal en el bloque try.
Bloque else:
    Opcional.
    Se ejecuta solo si el bloque try se ejecuta sin errores.
    Útil para continuar el código después del bloque try.
Bloque finally:
    Opcional.
    Siempre se ejecuta, independientemente de si hubo errores o no.
    Útil para liberar recursos después de la ejecución.
En resumen, el bloque try intenta ejecutar el código, el bloque except maneja errores específicos, el bloque else se ejecuta si no hay errores, y el bloque finally siempre se ejecuta

    6.	Tabla de Multiplicar: Pide al usuario que ingrese un número entero. Utiliza un bucle for para imprimir la tabla de multiplicar de ese número del 1 al 10. Por ejemplo, si el usuario ingresa 7, el programa debe imprimir:
