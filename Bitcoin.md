La primera blockchain, creada por Satoshi Nakamoto, fue hecha con un objetivo concreto, específico y único, crear una alternativa digital al sistema Financiero.

Es bastante probable que su fundador y sus precursores no tuviese ni idea de la nueva rama del conocimiento que estaban creando.

Aunque desde el principio se crearon múltiples alternativas, no fue hasta la llegada de Ethereum, que el mundo "entendió" que la blockchain podía utilizarse para mucho más.

![Con titulo](pictures/BCconPoWvsBCconSC "De la capa 1 a la 1,5")

Su objetivo principal era crear dinero "efectivo" digital, que pudiese ser producido progresivamente por los mantenedores de la red (mineros) y poseído por los propios usuarios directamente en lugar de mediante bancos o intermediarios.

Para ello uso varias soluciones ya existentes, en algunos casos creados con el mismo objetivo en intentos fallidos anteriores, y alguna nueva "herramienta":

- La implementación de un cliente para leer y participar en el proceso que con el tiempo ha acabado en lo que se conoce como [Bitcoin Core](http://joedicastro.com)

![Con titulo](pictures/Bitcoin_Core "Implementación de Bitcoin Core")

- __Bitcoin Script__: Un lenguaje de programación completamente tipado y determinístico. Pensado para asegurar la correcta transmisión de activos: sin perdidas ni posibilidades de doble gasto. Además de no ser _Turing Complete_ para impedir la creación de bucles que saturaran la red.

![Con titulo](pictures/Bitcoin_Script "Bitcoin Script")

- Y el más importante es el que conocemos como __blockchain__.

![Con titulo](pictures/Diagrama_Blockchain "Cadena de Bloques de Bitcoin")

Es bastante fácil críticar a la blockchain en general y a Bitcoin en particular. Por ser demasiado lento, demasiado limitado, demasiado difícil de actualizar, etcétera. Pero esa es, precisamente, la intención de la blockchain a la hora de representar más que un programa __un protocolo sobre el que construir__.

Y este es probablemente uno de los puntos fuertes de Bitcoin.

La implementación de Bitcoin Core, muy criticada por tener solo a unos 15 desarrolladores detrás, se ha limitado casi en exclusiva, a la retirada de partes innecesarias. Para realizar su cometido con menos probabilidad de errores.

El lenguaje de Bitcoin Script se ha ido podando con los años y es increíblemente complejo construir cosas con él, precisamente porque se diseñó para ser lo más robusto y seguro posible.

Y su blockchain no ha cambiado ni ha aumentado. Sigue teniendo la misma capacidad por bloque que tenía cuando Satoshi la diseño.

El funcionamiento consiste en la creación de bloques mediante _Prueba de Trabajo_, encadenandolos entre sí de manera sucesiva. En una competición que va liberando progresivamente las unidades de medida llamadas bitcoin (con minúsculas). De una manera qué a demostrado ser completamente segura y fiable

Está prueba de trabajo, es probablemente el punto de mayor crítica. Incluso entre los expertos de blockchain. Sin embargo es defendida a capa y espada por ser considerada, de momento, la única manera __completamente segura, descentralizada y sin permisonado__, para permitir la entrada en esta competición de cualquier participante.
