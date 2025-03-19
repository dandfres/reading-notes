# Lectura y Debate 10: Funciones y Callbacks en JavaScript

## Reflexiones para Analizar Críticamente
1. Funciones como valores:
¿Qué ventajas tiene el tratar a las funciones como valores en JavaScript? ¿En qué situaciones esta característica puede generar código difícil de depurar?

    - Algunas de las ventajas es que se pueden almacenar en variables, pasar como argumentos y devolver desde otras funciones, lo que permite mayor flexibilidad.

    - Por otro lado si abusamos podriamos tener dificultades. Si una función se pasa como argumento o se devuelve dinámicamente, puede ser difícil rastrear su origen. Ademas al tratar a una funcion como un valor, el contexto puede cambiar y confundirnos.

2. Uso de Callbacks:
¿Cuándo es recomendable usar callbacks en vez de ejecutar directamente una función? ¿Cómo afectan los callbacks a la legibilidad del código?

    - Cuando se necesita ejecutar una funcion despues de una funcion asincronica.

    - Pueden hacer el codigo dificil de entender por el exceso de anidacion.

3. Callback Hell:
¿Por qué el uso excesivo de callbacks puede llevar a código difícil de entender? ¿Qué alternativas existen para evitar este problema?

    - Ocurre cuando hay multiples funciones callbacks anidados y dificultan su mantenimiento y lectura.
    
    - Definir las funciones para evitar niveles de anidacion excesivos.

4. Funciones de Orden Superior en la Práctica:
¿Cómo el uso de funciones de orden superior puede hacer que el código sea más modular y reutilizable? ¿Puedes mencionar un ejemplo donde una función de orden superior simplifique una tarea común?

    - Permiten separar la logica en funciones mas reutilizables y favorece la reutilizacion al aplicar a diferentes partes del codigo sin necesidad de repetir logica.

    - Por ejemplo en `filter()` que recibe y devuelve una funcion.

5. Eficiencia y Performance:
¿Las funciones de orden superior y los callbacks afectan el rendimiento de una aplicación? ¿Cuándo es mejor evitar su uso?

    - Funciones de orden superior y callbacks agregan capas de ejecución, lo que podría afectar el rendimiento en funciones que se ejecutan muchas veces.

    - En operaciones que demandan alto rendimiento.

6. Aplicación en el Editor de Markdown:
¿Cómo podríamos aprovechar funciones de orden superior en la implementación del editor? ¿En qué parte del código sería más útil su uso?

    - Se podría usar una función de orden superior para aplicar diferentes transformaciones al texto de forma modular.

    - En lugar de escribir múltiples manejadores, podríamos usar una función genérica que tome un modificador y lo aplique.