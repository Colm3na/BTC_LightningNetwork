La idea se planteó hace más de 3 años y fue implementada finalmente en verano del 2017 coincidiendo también con el nacimiento de Bitcoin cash precisamente como alternativa a segwit.

Fue implementada como un soft fork lo que significa que ningún minero o nodo tuvo que cambiar nada para ser compatible. La transición ha sido progresiva y aún ahora sigue sin ser completamente usada por todos los clientes

La única actualización real en bitcoin hay que entenderla desde lo que es un bloque

   Imagen de bloque de UTXO

Cuándo Satoshi creo bitcoin creo un parámetro en la cabecera del bloque llamado block site pensando precisamente en la necesidad de crear bloques más grandes que permitieran la transmisión de más transacciones

Sin embargo Satoshi abandona bitcoin al menos públicamente en 2011 debido a que se estaba especulando con el valor mucho antes y de manera mucho más profesional de lo que él había imaginado. Antes de que bitcoin fuese algo realmente usable y usado se habían creado empresas basadas en el concepto de Minería a través de la realización de pruebas de trabajo mediante Asics.

Eso hizo pensar a los desarrolladores de Bitcoin que sí y van aumentando el blog site constantemente siendo para ello necesario un hard fork enterarían de manera irremediable la dispersión de información por la red favoreciendo a las concentraciones creadas por las empresas de minería

Todo esto estaba planteado desde un principio en bitcoin y aunque en eterium y en muchas otras blockchain se considera un error lo de los Asics en bitcoin es el camino que se decidió tomar desde un principio

Sin embargo esta profesionalización se ha realizado de manera más salvaje y mucho antes de lo que hubiese sido correcto para que la función del blog site fuese algo progresivo y natural para no perder la descentralización

Es por eso que aunque el proceso de aumentar el tamaño del bloque es algo que se hará y resultaba un paso evidente para todos se decidió implementar antes una solución de escalabilidad diferente es esto a lo que se le llama segwit o vulnerabilidad segregada

En realidad es un cambio en las reglas a la hora de medir el peso del bloque.

Hasta segwit el bloque se media incluyendo el timestamp el origen el destino la cantidad y el campo de notas. Consequir el campo de notas se apilan en la primera transaccion mediante un separador que permite después al cliente volver a desplegar lo ha pirado y colocarle cada nota a su transacción original

Eso deja el resto de campos de notas libres y no contabilizados como peso en el bloque.

En primer lugar se puede utilizar el campo de notas para añadir nuevas transacciones en este caso utilizando entre sus partes separadores de nuevo para que el cliente vuelva a hacer el despliegue. Esto hace que un bloque que utiliza segwit o minado mediante segwit utilicé un blog site de 1 MB pero en realidad pese 2 MB o un poco más. Y por tanto que se lleven el doble de transacciones por bloque.

Lógicamente esto parece no tener ninguna utilidad y ese fue el cabreo principal de los seguidores de Bitcoin cash se estaban cambiando las reglas creadas por Satoshi cuando había una solución más sencilla ya planteada para conseguir lo mismo.

Sin embargo como ahora veremos con lightning network, segwit permite algo mucho más potente pues en ese espacio que queda libre utilizando, eso sí, bitcoin script, se pueden crear otros Smart contracts que no sean transacciones sencillas.

Segwit convierte a la capa de Bitcoin con su proof of work en una capa base sobre la qué anidar side chains en la mitad del espacio de cada bloque, la otra mitad es para mandar transacciones, probablemente en el futuro estas transacciones pagarán una cantidad de tasas muy grandes (de cientos de €). Precisamente para mandar cantidades ingentes de dinero de una forma ultra segura y quedando las sidechains para todo lo demás.

Eso si estás side chains presentan dos "problemas":
El primero es que DEBEN ser escritas con bitcoin script el cual es un lenguaje bastante complicado. Sin embargo esto puede no ser tan problema como parece en un principio, debido a qué Bitcoin a diferencia de Ethereum está pensado para sustituir al sistema financiero, no para sustituir al sistema mercantil. Y en el sistema financiero lo que es obligatorio es la seguridad y no la flexibilidad. Por poner un ejemplo el sistema similar a ethereum pero pensado para el mundo financiero es Cardano que está creando una máquina virtual para un derivado de Haskell, Plutus. Que viene a ser un lenguaje intermedio entre bitcoin script y solidity. Es decir, Turing Complete pero ultra seguro y deterministico.
El segundo problema es que a diferencia del concepto de token dónde con un poquito de ether creamos la cantidad que queramos de nuestro nuevo dinero. En el caso de las sidechains sobre Bitcoin tenemos que congelar la misma cantidad de Bitcoin que aquello que queramos utilizar en nuestras sidechain, aunque la llamemos liquid bitcoin o lightning bitcoin, siempre tendremos un valor de 1 a 1 entre el Token y la criptomoneda base. Esto hace que no sirva como sistema de financiación, sino que traspasa o directamente aumenta el valor especulativo sobre la criptomoneda base, bitcoin.

Es por tanto que en realidad estos dos problemas son en realidad, de la misma forma que la lentitud y rigidez, el principal punto fuerte de Bitcoin cómo sistema financiero digital.
