La primera blockchain, creada por Satoshi Nakamoto, fue hecha con un objetivo concreto, específico y único, crear una alternativa digital al sistema Financiero.

Es bastante probable que su fundador y sus precursores no tuviese ni idea de la nueva rama del conocimiento que estaban creando.

Aunque desde el principio se crearon múltiples alternativas, no fue hasta la llegada de Ethereum, que el mundo "entendió" que la blockchain podía utilizarse para mucho más.

![Con titulo](pictures/BCconPoWvsBCconSC "De la capa 1 a la 1,5")

Su objetivo principal era: crear dinero "efectivo" digital. Que pudiese ser producido, progresivamente, por los mantenedores de la red _(mineros)_. Y poseído por los propios usuarios directamente, en lugar de mediante bancos o intermediarios.

Para ello uso varias soluciones ya existentes, en algunos casos, creadas con el mismo objetivo en intentos fallidos anteriores, y alguna nueva "herramienta". Las principales son:

- __El cliente o nodo__: La implementación de un cliente para leer y participar en el proceso de mantener la red. Con el tiempo ha acabado, en lo que se conoce como: [Bitcoin Core](http://joedicastro.com)

![Con titulo](pictures/Bitcoin_Core "Implementación de Bitcoin Core")

- __Bitcoin Script__: Un lenguaje de programación completamente tipado, determinístico y redundante. Pensado para asegurar la correcta transmisión de activos: sin perdidas ni posibilidades de doble gasto. Además de no ser _Turing Complete_ para impedir la creación de bucles que saturaran la red.

![Con titulo](pictures/Bitcoin_Script "Bitcoin Script")

- Y el más importante, es lo que conocemos como __blockchain__.

![Con titulo](pictures/Diagrama_Blockchain "Cadena de Bloques de Bitcoin")

Es bastante fácil críticar a la blockchain en general y a Bitcoin en particular. Por ser demasiado lento, limitado, difícil de actualizar, etcétera. Pero esa es, precisamente, la intención de la blockchain a la hora de representar más que un programa __un protocolo sobre el que construir__.

Y es este probablemente, uno de los puntos fuertes de __Bitcoin__.

La implementación de [Bitcoin Core](http://joedicastro.com), muy criticada por tener solo a unos 15 desarrolladores detrás, se ha limitado (casi en exclusiva) a la retirada de partes innecesarias. Para realizar su cometido con menos probabilidad de errores.

El lenguaje de Bitcoin Script se ha ido podando con los años y es increíblemente complejo construir cosas con él, precisamente porque se diseñó para ser lo más robusto y seguro posible.

Y su blockchain no ha cambiado las reglas ni siquiera para aumentar el número de transacciones. Sigue teniendo la misma capacidad por bloque que tenía cuando Satoshi la diseño.

El funcionamiento consiste en una competición basada en la _Prueba de Trabajo_ para ganar el premio en la creación de bloques. Estos están formados por nuevas transacciones (válidas),  y el encadenamiento de lo anterior mediante __Árboles de Merkle__ entre sí de manera sucesiva, para facilitar la comprobación de inmutabilidad.

En esta competición se va liberando progresivamente las unidades de medida llamadas bitcoin (con minúsculas). De una manera qué a demostrado ser completamente segura y fiable.

![Con titulo](pictures/Diagrama_Blockchain_2 "Cadena de Bloques de Bitcoin")

Está prueba de trabajo, es probablemente el punto de mayor crítica. Incluso entre los expertos de blockchain. Sin embargo es defendida a capa y espada por ser considerada, de momento, la única manera __completamente segura, descentralizada y, sobre todo, sin permisonado__, para permitir la entrada en esta competición de cualquier participante.