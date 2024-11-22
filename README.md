# ajedrezV1
Repositorio de lector de archivos PGN - POO

El programa es una aplicación diseñada para analizar y visualizar partidas de ajedrez almacenadas en archivos PGN (Portable Game Notation). PGN es un formato estándar ampliamente utilizado para compartir partidas de ajedrez, que incluye información como los jugadores, la fecha, el resultado y la secuencia de movimientos. Este programa permite a los usuarios cargar y explorar partidas de manera interactiva con diversas funcionalidades accesibles a través de botones en la interfaz gráfica. A continuación, se describen las opciones disponibles:

1. Abrir archivo PGN
Este botón permite al usuario cargar un archivo PGN desde el sistema de archivos. Una vez cargado, el programa procesa el archivo para extraer información relevante como etiquetas (jugadores, evento, fecha, etc.) y la lista de movimientos de la partida.

2. Iniciar partida
Este botón inicializa la partida en el programa. Resetea cualquier progreso actual, coloca las piezas en la posición inicial y prepara la interfaz para navegar a través de los movimientos.Se activa después de cargar un archivo PGN.

3. Jugada anterior y Siguiente jugada
Estos botones permiten al usuario moverse hacia atrás o adelante en la lista de jugadas completas (que incluyen movimientos de ambos jugadores).

- Jugada anterior: Retrocede una jugada, restaurando la posición del tablero al estado anterior.
- Siguiente jugada: Avanza a la siguiente jugada, actualizando el tablero en consecuencia.

4. Primera jugada y Última jugada
Estos botones facilitan saltar directamente al comienzo o al final de la partida.

- Primera jugada: Restablece el tablero a su posición inicial.
- Última jugada: Muestra la posición final de la partida, útil para analizar el desenlace.

5. Buscar jugada por número
Permite a los usuarios ingresar el número de una jugada específica y saltar directamente a ella. Esto es útil para analizar un momento concreto de la partida.
