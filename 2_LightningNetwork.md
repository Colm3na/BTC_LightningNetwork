__LN__ es la primera implementación de __Segwit__, que ha llevado más de 3 años _(un poco como el huevo y la gallina)_ en el que han participado no solo la Start-Up que la pensó llamada ___Lightning Labs___. Sino muchas otras empresas. _Como dato curioso, se creó un consorcio temporal a principios de año entre los departamentos de calculo computacional de las 70 universidades más potentes del mundo con la intención de valorar la viabilidad del proyecto._

El funcionamiento es el siguiente: utilizando el espacio, del campo de notas, que nos da __SegWit__, abrímos una transacción y metemos un trozo de Smart contract. En un bloque futuro cerraremos la transacción con el resto del Smart contract. Eso significa que gastaremos el doble en tasas para realizar una transacción. Lógicamente esto solo es perder dinero y encima de manera más complicada.

La primera utilidad viene porque: entre uno y otro paso, podremos hacer múltiples transacciones, en una u otra dirección, en lugar de realizar una transacción única. _Por ejemplo imaginemos un contrato dónde se paga por comisión y se cobra algún tipo de material gastado durante el proceso. Se abriría un canal por ejemplo de 1000 € y cada vez que se cumplirá el objetivo se traspasaría el beneficio directamente y cada vez que se rompiera una herramienta por ejemplo se cobraría en la dirección contraria la cantidad de la reparación. Al terminar un periodo se cerraría el contrato quedando ajustado al final la cantidad exacta que se ha traspasado de una dirección a la otra y eliminando todas las transacciones intermedias que no son necesarias para terceros._

La utilidad real, viene dada, por el enrutamiento de todos los canales entre sí. De esta forma, al crear un canal entre dos personas, no solo pueden transmitir dinero entre ellas, sino entre las comunidades que ambas personas tienen detrás. Además el dinero no tiene que ir por un solo camino, de manera que si el canal no permite transmitirlo todo, se dividirá y parte recorrerá caminos más largos para transmitirlo completamente.

Todo el dinero que pase por un canal que tú has creado te da unas tasas por hacerlo. De esta forma, se están creando núcleos que están muy bien conectados y qué esperan cobrar un buen dinero en tasas, de una manera similar a como ocurre con las empresas de minería. Sin embargo, en este caso, no estamos hablando de la necesidad de comprar equipo o gastar electricidad, pues solo es necesario tener cantidades congeladas haciendo ___stake___ en forma de canales.

Como creador de un canal: aseguras que como máximo moverás esa cantidad de dinero que tienes en ___stake___, a la cual se le deben restar la apertura y cierre del __State Channel__. En caso de que hagas algo malicioso, es ese dinero el que responderá en tu lugar.

Son los mineros de la Capa 1, es decir de __Bitcoin__, los que aseguran mediante __Proof of Work__ la apertura y cierre de canal.

Esto significa que tenemos una capa 1 con una seguridad desproporcionada y una capa 2 con una seguridad completamente disgregada y asegurada. No hay necesidad de montar capas de proof of work encima o detener nuevos dispositivos haciendo caros procesos.

_______________________________
# PRÁCTICA
_______________________________

Hay dos formas de usarlo la  y más fácil es la que vamos a utilizar hoy qué consiste en descargarse una aplicación llamada [Eclair](http://joedicastro.com) que permite usarlo directamente tirando de un nodo completo que está en otra parte.
1. Descargaremos la aplicación de [Eclair](http://joedicastro.com) en nuestro móvil y la abriremos para que se sincronice
2. Cargamos la cuenta con unos 2 € en bitcoin _(bloqueando BTC y obteniendo LBTC)_
3. Creamos un canal con la dirección de la __Colm3na__
4. Transmitimos unos pocos ___satoshis___ _(que van a ser milésimas de céntimo)_  
5. Nos pasamos la dirección por __Telegram__
6. Y listo, ya podemos hacer transacciones entre nosotros _(todo ello lightning)_
7. En el futuro cuando queramos, solo tenemos que cerrar el canal __unidireccionalmente__ para volver a cambiar los __lightning bitcoin__ por __bitcoin normales__.

La otra forma es la versión purista, os la dejo aquí desarrollada para el que le interese despegarla después, qué consiste en:
1. Descargarse el cliente de [Bitcoin Core](http://joedicastro.com)
2. Sincronizar la blockchain de Bitcoin en nodo completo _(2-3 días, unos 40 GB)_
3. Descargarse el cliente de Lightning Network también de [Eclair](http://joedicastro.com)
4. Operar desde ahí _(seguir desde el paso 2 anterior)_

___Por una cuestión de tiempo, realizaremos lo primero hoy y así podremos poner en marcha canales y probar cómo funciona.___
