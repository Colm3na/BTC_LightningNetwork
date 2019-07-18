# Links de interés
_______________________________

- [Bici eléctrica activada con LN](https://github.com/leblitzdick/lightning-bike)
_______________________________
### Otros recursos:

- [WhitePapper de Lightning Network](https://lightning.network/lightning-network-paper.pdf)
- [Visualizador de Nodos en Testnet](https://explorer.acinq.co/)
- [Visualizador de Nodos Mainnet](https://graph.lndexplorer.com/)
- [Otro visualizador de Nodos Mainnet](https://rompert.com/recksplorer/)
- [Visualizador de Nodos Mainnet en 3D](https://lnd3.vanilla.co.za/multinodegraphs/index.html)
- [Explicación: Diferencia entre sidechain y state chanel](https://hackernoon.com/difference-between-sidechains-and-state-channels-2f5dfbd10707)
_______________________________
## Exploradores
#### De Lightning Network
- https://explorer.acinq.co/

- https://1ml.com/

- http://lnd.fun/   <= dashboard para manejar tu nodo completo de LN

- https://demo1.lndexplorer.com/  
https://github.com/altangent/lnd-explorer <= ejemplo de Web de nodo LN

- https://github.com/mably/lncli-web <= otro visualizador web de tu nodo LN

#### De Bitcoin
- https://dcabtc.com/

- https://live.blockcypher.com/btc/

- https://symphony.iohk.io/  <= 3D muy llamativo

- https://howmanyconfs.com/  <= Comparativa de seguridad entre blockchains


_______________________________
## Implementaciones de Bitcoin
#### Neutrino (nodo "ligero" o podado)
- https://neutrinojs.org/installation/

#### Bitcoin Core (cliente más utilizado)


_______________________________
## Implementaciones de Lightning Network:
#### LND (go)
- https://github.com/lightningnetwork/lnd

#### c-lightning (C)
- https://elementsproject.org/

#### Eclair (Scala)
- https://github.com/ACINQ/eclair


_______________________________
## Faucet de Bitcoin testnet
#### Mempool
- https://testnet-faucet.mempool.co/

#### Faucets (rotas)
- (rota) https://testnet.help/en/btcfaucet/testnet

- (sin fondos) https://testnet.qc.to/send

- (no pilla el captch) https://kuttler.eu/en/bitcoin/btc/faucet/

- (pura mierda) https://bonusbitcoin.co/


_______________________________
## Faucet de Lightning Network testnet (permite crear canales directamente)
#### Community
- https://faucet.lightning.community/

#### LnRoute
- https://lnroute.com/testnet-faucets/


_______________________________
## Lightning Apps
- __Tipo CryptoKitties__:  
https://btcdragons.lightningplayground.co/

	Wallet especial solo para el juego
	https://chrome.google.com/webstore/detail/btc-ln-collectibles/kafdhdbejepkebcinmpkhnkiiecccknk/related

- __Satoshi Place__: muro de pintadas  
https://satoshis.place/

- __Yalls__: Sitio de post de (micro)pago  
https://yalls.org/

- __E-commerce__  
https://www.coinmall.com/

- __Exchange__  
https://zigzag.bitlum.io/#/


_______________________________
## Documentación BTC
#### Learning Bitcoin from the Command Line
- https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line/blob/master/README.md

#### Mastering in bitcoin

#### Bitcoin with Python

#### Documentación de la Consola
- https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list


_______________________________
## Documentación LN
#### Lightningloop
- https://lightningloop.io/

#### LND (lightning network daemon)
- https://api.lightning.community/

#### Lightning RFC
- https://github.com/lightningnetwork/lightning-rfc

#### c-lightning (cliente de BlockStream)
- https://elementsproject.org/

#### Plugin para WooCommerce
- https://github.com/ElementsProject/woocommerce-gateway-lightning

#### Plugin para Wordpress
- https://github.com/ElementsProject/wordpress-lightning-publisher

#### Aaron van Wirdum
- https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791


_______________________________
## Explicaciones (probablemente mejores que las nuestras)
#### por Alejandro Echeverría de Buda.com
- https://www.youtube.com/watch?v=L-fNLA2t85g

#### Varias opciones simples y avanzadas de instalación
- https://guggero.github.io/lightning-workshop/

#### Explicación general
- https://medium.com/coinmonks/intro-to-lightning-network-apps-lapps-b548c96ec13f

#### Lista de lapps
- https://dev.lightning.community/lapps/

#### Tutorial para windows
- https://medium.com/coinmonks/guide-setup-a-lightning-network-node-on-windows-8475206807f


_______________________________
## Tutoriales con Raspberry PI
#### Sadicus
- https://stadicus.github.io/RaspiBolt/


_______________________________
## Wallets: nodo oculto
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


_______________________________
## Otras cadenas laterales sobre BTC
- Liquid
Blockchain pública, permissionless, con Proof of Autorithy, donde Exchanges y grandes fondos de inversión hacen de validadores. Permite grandes movimientos de fondos entre Exchanges en 2 min
https://blockstream.com/liquid/  
https://docs.blockstream.com/liquid/technical_overview.html

- RSK
Con Merged Minning y la EVM


_______________________________
## Futuras mejoras de LN
- __Loop__  
Saca fondos a BTC automáticamente para liberar el canal al cobrarse un invoice:  
https://blog.lightning.engineering/announcement/2019/06/25/loop-in.html

- __WatchTowers__  
Servicios que guardan el historial de los canales para que no ocurra _doble gasto_ y no se puedan perder los fondos de los usuarios al borrar la wallet (y no conservar la BD)


_______________________________
## Futuras mejoras en BTC
- __MASK, Taproot, Grassroot, Schnoor Signatures__

- __State Chain__  
Permitirá el cambio de propietario de un UTXO sin realizar ninguna _tx onchain_


_______________________________
## Principales empresas detrás de LN
- __Lightning Labs__  
Son los "inventores" iniciales de la idea y han sido sus principales desarrolladores. Recibieron varios millones de $ por el CEO de Twitter

- __ACINQ__  
Desarrolladores de Eclair

- __BlockStream__  
Entre su plantilla se encuentran algunos de los desarrolladores de Bitcoin Core. Son los desarrolladores de Liquid.
