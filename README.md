# Actividad9
Continúa con el proyecto Poker e integra la entrada de datos desde el teclado de la siguiente manera:

Implementa un método showMenu en la clase principal que muestre en la pantalla un menú interactivo. El menú permitirá al usuario realizar las cuatro acciones determinadas en los métodos anteriores, de tal forma que cuando el usuario ejecute el programa deberá ver un menú parecido al siguiente:
Bienvenido a Poker!
Selecciona una opción:
1 Mezclar deck
2 Sacar una carta
3 Carta al azar
4 Generar una mano de 5 cartas
0 Salir


El método showMenu deberá regresar la opción seleccionada.

De acuerdo a la opción seleccionada se deberá llamar a alguno de los 4 métodos implementados en la clase Deck:
shuffle: mezclar el deck. El método deberá imprimir en pantalla el siguiente mensaje:

Se mezcló el Deck.
head: mostrar la primera carta del deck, la carta deberá removerse del deck. El método deberá imprimir en pantalla un mensaje con el siguiente formato:
{Palo},{Color},{Valor}
Quedan {número de cartas en deck}

pick: seleccionar una carta al azar, la carta deberá removerse del deck. El método deberá imprimir en pantalla un mensaje con el siguiente formato:
{Palo},{Color},{Valor}
Quedan {número de cartas en deck}

hand: regresará un arreglo de 5 cartas del deck, las cartas deberán removerse del deck. El método deberá imprimir en pantalla un mensaje con el siguiente formato:
{Palo},{Color},{Valor}
{Palo},{Color},{Valor}
{Palo},{Color},{Valor}
{Palo},{Color},{Valor}
{Palo},{Color},{Valor}
Quedan {número de cartas en deck}

Si se selecciona una opción inválida, el programa deberá mostrar un mensaje de “Opción no válida” y volver a preguntar por una opción válida.
Realiza un reporte sobre la solución implementada para el problema, explicando el funcionamiento del programa, incluye capturas de pantalla como evidencia del funcionamiento del programa.
