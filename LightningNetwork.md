
[Cliente de Lightning Network: Eclair](http://joedicastro.com)

LN es la primera implementación de Segwit, que ha llevado más de 3 años ( un poco como el huevo y la gallina) en el que han participado no solo la startup que la pensó llamada Lightning Labs. Sino muchas otras empresas. Como dato curioso, se creó un consorcio temporal a principios de año entre los departamentos de calculo computacional de las 70 universidades más potentes del mundo con la intención de valorar la viabilidad del proyecto.

El funcionamiento es el siguiente: utilizando los dos espacios del campo de notas que nos da segwit abrímos una transacción y metemos un trozo de Smart contract. En un bloque futuro cerraremos la transacción con el resto del Smart contract. Eso significa que gastaremos el doble de tasas para realizar una transacción. Lógicamente esto solo es perder dinero y encima de manera más complicada.

La primera utilidad viene porque entre uno y otro paso podremos hacer múltiples transacciones en una u otra dirección en lugar de realizar una transacción única. Por ejemplo imaginemos un contrato dónde se paga por comisión y se cobra algún tipo de material gastado durante el proceso. Se abriría un canal por ejemplo de 1000 € y cada vez que se cumplirá el objetivo se traspasaría el beneficio directamente y cada vez que se rompiera una herramienta por ejemplo se cobraría en la dirección contraria la cantidad de la reparación. Al terminar un periodo se cerraría el contrato quedando ajustado al final la cantidad exacta que se ha traspasado de una dirección a la otra y eliminando todas las transacciones intermedias que no son necesarias para terceros.
La utilidad real, viene dada por el enrutamiento de todos los canales entre sí de esta forma al crear un canal entre dos personas no solo puede transmitirse dinero entre ellas sino entre las comunidades que ambas personas tienen detrás. Además el dinero no tiene que ir por un solo camino de manera que si el canal no permite transmitirlo todo se dividirá y parte recorrerá caminos más largos para transmitirlo completamente.

Todo el dinero que pase por un canal que tú has creado te da unas tasas por hacerlo. De esta forma se están creando núcleos que están muy bien conectados y qué esperan cobrar un buen dinero en tasas de una manera similar a como ocurre con las empresas de minería. Sin embargo en este caso no estamos hablando de la necesidad de comprar equipo o gastar electricidad pues solo es necesario tener cantidades congeladas haciendo stake en forma de canales.

Como creador de un canal aseguras que como máximo moverás esa cantidad de dinero que tienes en steak a la cual se le deben restar la apertura y cierre del state Channel. En caso de que hagas algo malicioso es ese dinero el que responderá en tu lugar.
Y son los mineros de la Capa 1 es decir de Bitcoin los que aseguran mediante proof of work la apertura y cierre de canal.
Esto significa que tenemos una capa 1 con una seguridad desproporcionada y una capa 2 con una seguridad completamente disgregada y asegurada y no hay necesidad de montar capas de proof of work encima o detener nuevos dispositivos haciendo caros procesos.

_______________________________

Hay dos formas de usarlo la  y más fácil es la que vamos a utilizar hoy qué consiste en descargarse una aplicación llamada Eclair que permite usarlo directamente tirando de un nodo completo que está en otra parte.

Descargaremos la aplicación de Eclair en nuestro móvil la abriremos para que se sincronice, cargamos la cuenta con unos 2 € en bitcoin, creamos un canal con la dirección de la colmena transmitimos unos pocos satoshis que van a ser milésimas de céntimo,  bloqueando bitcoin y obteniendo lightning, nos pasamos la dirección por telegram y podemos hacer transacciones entre nosotros todo ello lightning, y en el futuro cuando queramos solo tenemos que cerrar el canal unidireccionalmente para volver a cambiar los Lightning bitcoin por bitcoin normales.

La otra forma es la versión purista os la dejo aquí desarrollada para el que le interese despegarla después qué consiste en descargarse el cliente de Bitcoin core actualizar la blockchain de Bitcoin en modo completo y descargarse el cliente de Lightning Network también de eclair y operar desde ahí, siendo tú el que realiza todos los pasos.

Por una cuestión de tiempo realizaremos lo primero hoy y así podremos poner en marcha canales y probar cómo funciona.

_______________________________
