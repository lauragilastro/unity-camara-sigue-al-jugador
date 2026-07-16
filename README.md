# Práctica universitaria de C# (2022): que la cámara siga al jugador de manera fija (Unity)
01/2022
## PASOS PREVIOS AL SCRIPT
- Si la cámara va a ser fija: debemos colocarla bien donde queramos.
- Si la cámara va a seguir al jugador: hay que vincularla y asociarla.
- Para ello, en la Jerarquía, arrastramos la cámara (Main Camera) hacia dentro del Jugador.
* PROBLEMA: si el jugador gira, la cámara también girará. Para evitar esto, tenemos que añadirle el script.
- El script se ha vinculado con el jugador, pero todavía hay que asociarlo: en el Inspector, abajo en script, pone Jugador --> click (así conseguiremos que la cámara no dé vueltas).

## ALTERNATIVAS
- Si queremos jugar en primera persona: tenemos que usar la Main Camera como “jugador” y asociarle el script de movimiento del jugador.
- Si descargamos paquetes, se pueden arrastrar <<ciclos de animación>> al personaje (desde project a la jerarquía) y así se aplican las animaciones en el movimiento.

## CONTEXTO
- Motor gráfico Unity 2018
- Lenguaje C#
