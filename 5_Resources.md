# Links de interés
_______________________________
## Exploradores
#### de Bitcoin
- https://dcabtc.com/
- https://live.blockcypher.com/btc/
- https://symphony.iohk.io/  <= 3D muy llamativo
- https://howmanyconfs.com/  <= Comparativa de seguridad entre blockchains

#### de Lightning Network
- https://explorer.acinq.co/
- https://1ml.com/
- https://graph.lndexplorer.com/
- https://rompert.com/recksplorer/
- https://lnd3.vanilla.co.za/multinodegraphs/index.html) <= Visualizador de Nodos Mainnet en 3D
- http://lnd.fun/   <= dashboard para manejar tu nodo completo de LN
- https://demo1.lndexplorer.com/  
https://github.com/altangent/lnd-explorer <= ej de Web de nodo LN
- https://github.com/mably/lncli-web <= otro visualizador web de tu nodo LN


_______________________________
## Implementaciones (nodo público)
#### de Bitcoin
- __Neutrino__ (nodo "ligero" o podado)
https://neutrinojs.org/installation/
- __Bitcoin Core__ (cliente más utilizado)  

#### de Lightning Network:
- __LND__ (en Go) https://github.com/lightningnetwork/lnd
- __c-lightning__ (en C) https://elementsproject.org/
- __Eclair__ (en Scala) https://github.com/ACINQ/eclair


_______________________________
## Wallets (nodo oculto)
#### Escritorio
- __Lightning Labs:__ Lleva Nodo podado => Neutrino  
https://github.com/lightninglabs/lightning-app  
https://github.com/lightninglabs/lightning-app/releases/tag/v0.1.5-alpha
- __Node Launcher:__ Requiere nodo de Bitcoin  
https://medium.com/lightning-power-users/windows-macos-lightning-network-284bd5034340
- __Zap:__ Requiere nodo de Bitcoin  
https://zap.jackmallers.com/

#### Web
- __Joule:__ Requiere nodo de Bitcoin  
https://chrome.google.com/webstore/detail/joule/aejmoogjdllanidlpfjmmmmimfaficio
- __HTLC.me:__ para prueba rápida  
https://htlc.me/

#### Móvil (Android)
- __Blue Wallet__
- __Breez__
- __Eclair__
- __Eclair Testnet__


_______________________________
## Faucets
#### de Bitcoin testnet
- https://testnet-faucet.mempool.co/

#### de Lightning Network testnet (permiten crear canales directamente)
- __Community:__ https://faucet.lightning.community/
- __LnRoute:__ https://lnroute.com/testnet-faucets/


#### Rotas o que no merecen la pena
- (rota) https://testnet.help/en/btcfaucet/testnet
- (sin fondos) https://testnet.qc.to/send
- (no pilla el captcha) https://kuttler.eu/en/bitcoin/btc/faucet/
- (pura mierda) https://bonusbitcoin.co/


_______________________________
## Documentación
#### de Bitcoin
- __Learning Bitcoin from the Command Line__ https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line/blob/master/README.md
- __Mastering in Bitcoin__
- __Bitcoin with Python__
- __Documentación de la Consola__ https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list

#### de Lightning Network
- __WhitePapper de Lightning Network__ https://lightning.network/lightning-network-paper.pdf)
- __Lightningloop__ https://lightningloop.io/
- __LND__ (lightning network daemon) https://api.lightning.community/
- __Lightning RFC__ https://github.com/lightningnetwork/lightning-rfc
- __c-lightning__ (cliente de BlockStream) https://elementsproject.org/
- __Plugin para WooCommerce__ https://github.com/ElementsProject/woocommerce-gateway-lightning
- __Plugin para Wordpress__ https://github.com/ElementsProject/wordpress-lightning-publisher
- __Aaron van Wirdum__ https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791


_______________________________
## Explicaciones (probablemente mejores que las nuestras)
#### de Lightning Network
- __por Alejandro Echeverría de Buda.com__ https://www.youtube.com/watch?v=L-fNLA2t85g
- __Varias opciones simples y avanzadas de instalación__ https://guggero.github.io/lightning-workshop/
- __Explicación general__ https://medium.com/coinmonks/intro-to-lightning-network-apps-lapps-b548c96ec13f
- __Lista de lapps__ https://dev.lightning.community/lapps/
- __Tutorial para Windows__ https://medium.com/coinmonks/guide-setup-a-lightning-network-node-on-windows-8475206807f


_______________________________
## Tutoriales con Raspberry PI
#### de Lightning Network
- __Nodo__ ___muy___ __Completo__ https://stadicus.github.io/RaspiBolt/
- __Bicicleta Eléctrica de pago__ https://github.com/leblitzdick/lightning-bike


_______________________________
## Lightning Apps
- __Tipo CryptoKitties__:  
https://btcdragons.lightningplayground.co/  
Wallet especial solo para el juego https://chrome.google.com/webstore/detail/btc-ln-collectibles/kafdhdbejepkebcinmpkhnkiiecccknk/related
- __Satoshi Place__: muro de pintadas https://satoshis.place/
- __Yalls__: Sitio de post de (micro)pago https://yalls.org/
- __E-commerce__ https://www.coinmall.com/
- __Exchange__ https://zigzag.bitlum.io/#/


_______________________________
## Otras cadenas laterales sobre BTC
- __Liquid:__  
Blockchain pública, permissionless, con Proof of Autorithy, donde Exchanges y grandes fondos de inversión hacen de validadores. Permite grandes movimientos de fondos entre Exchanges en 2 min
https://blockstream.com/liquid/  
https://docs.blockstream.com/liquid/technical_overview.html

- __RSK:__  
Con Merged Minning y la EVM


_______________________________
## Futuras mejoras
#### de Bitcoin
- __MASK, Taproot, Grassroot, Schnoor Signatures__

- __State Chain__  
Permitirá el cambio de propietario de un UTXO sin realizar ninguna _tx onchain_
[Explicación: Diferencia entre sidechain y state chanel](https://hackernoon.com/difference-between-sidechains-and-state-channels-2f5dfbd10707)

#### de Lightning Network
- __Loop__  
Saca fondos a BTC automáticamente para liberar el canal al cobrarse un invoice:  
https://blog.lightning.engineering/announcement/2019/06/25/loop-in.html

- __WatchTowers__  
Servicios que guardan el historial de los canales para que no ocurra _doble gasto_ y no se puedan perder los fondos de los usuarios al borrar la wallet (y no conservar la BD)


_______________________________
## Principales empresas detrás de LN
- __Lightning Labs__  
Son los "inventores" iniciales de la idea y han sido sus principales desarrolladores. Recibieron varios millones de $ por el CEO de Twitter

- __ACINQ__  
Desarrolladores de Eclair

- __BlockStream__  
Entre su plantilla se encuentran algunos de los desarrolladores de Bitcoin Core. Son los desarrolladores de Liquid.
