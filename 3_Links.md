# Links de interés
_______________________________
## Exploradores
#### de Bitcoin
- https://dcabtc.com/
- https://live.blockcypher.com/btc/
- https://symphony.iohk.io/  <= 3D muy llamativo
- https://howmanyconfs.com/  <= Comparativa de seguridad entre blockchains


#### de Lightning Network
- __Lista:__ https://gist.github.com/bretton/798ec38165ffabc719d91e0f4f67552d
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
- __Neutrino:__ (nodo "ligero" o podado)
https://neutrinojs.org/installation/
- __Bitcoin Core:__ (cliente más utilizado) https://bitcoincore.org/en/download/
- __Bitcoin Testnet Privada:__ (más útil que la testnet general para enseñar y hacer pruebas) https://en.bitcoin.it/wiki/Signet
- __Bitcoin Daemon:__ btcd https://github.com/btcsuite/btcd/tree/master/rpcclient

#### de Lightning Network:
- __LND:__ (en GO) https://github.com/lightningnetwork/lnd
- __c-lightning:__ (en C) https://github.com/ElementsProject/lightning
- __Eclair:__ (en Scala) https://github.com/ACINQ/eclair
- __Ptarmigan:__ (en C y C++) https://github.com/nayutaco/ptarmigan
- __Lit:__ (en GO) https://github.com/mit-dci/lit
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
- __Blue Wallet:__
- __Breez:__
- __Eclair:__
- __Eclair Testnet:__

#### Móvil (Iphone)
- __Lightning Labs:__ Lleva Nodo podado => Neutrino  
https://github.com/lightninglabs/lightning-app  
https://github.com/lightninglabs/lightning-app/releases/tag/v0.1.5-alpha


_______________________________
## Faucets
#### de Bitcoin testnet
- __LA faucet:__ https://coinfaucet.eu/en/btc-testnet/
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
- __Bitcoin __WhitePapper:__ https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf
- __Learning Bitcoin from the Command Line:__ https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line/blob/master/README.md
- __Mastering Bitcoin:__ https://bitcoinbook.info/wp-content/translations/es/book.pdf
- __Bitcoin with Python:__
- __Documentación de la Consola:__ https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list
- __Developer Guide - Bitcoin:__ https://bitcoin.org/en/developer-guide#block-chain
- __Become A Bitcoin Developer:__ Basic 101 (Bitcoin developer) https://blockgeeks.com/guides/bitcoin-developer/
- __Lista muy completa de lecturas:__ https://github.com/jashmenn/bitcoin-reading-list
- __Hipercomoleto link con recursos de aprendizaje sobre bitcoin:__ https://lopp.net/bitcoin.html
- __Bitcoin Script:__ lenguaje de programación de smart contracts en BTC https://en.bitcoin.it/wiki/Script
- __Programming Bitcoin:__ de Jimmy Song, Learning hoy to program Bitcoin from scratch
- __The Bitcoin Standard:__ Saifedean Ammous, The decentralized alternative to Central Banking
- __Librería Python:__ https://github.com/petertodd/python-bitcoinlib

#### de Lightning Network
- __WhitePapper de Lightning Network:__ https://lightning.network/lightning-network-paper.pdf)
- __Lightningloop:__ https://lightningloop.io/
- __LND:__ (lightning network daemon) https://api.lightning.community/
- __Lightning RFC:__ https://github.com/lightningnetwork/lightning-rfc
- __c-lightning:__ (cliente de BlockStream) https://elementsproject.org/
- __Plugin para WooCommerce:__ https://github.com/ElementsProject/woocommerce-gateway-lightning
- __Plugin para Wordpress:__ https://github.com/ElementsProject/wordpress-lightning-publisher
- __Aaron van Wirdum:__ https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791
- __Tutorial LN en Simnet:__ https://dev.lightning.community/tutorial/index.html
- __Otro tutorial:__ https://medium.com/@bitstein/setting-up-a-bitcoin-lightning-network-test-environment-ab967167594a

_______________________________
## Explicaciones (probablemente mejores que las nuestras)
#### de Lightning Network
- __por Alejandro Echeverría de Buda.com:__ https://www.youtube.com/watch?v=L-fNLA2t85g
- __Varias opciones simples y avanzadas de instalación:__ https://guggero.github.io/lightning-workshop/
- __Explicación general:__ https://medium.com/coinmonks/intro-to-lightning-network-apps-lapps-b548c96ec13f
- __Lista de lapps:__ https://dev.lightning.community/lapps/
- __Lista muy completa de todo lo relacionado con LN:__ https://www.lopp.net/lightning-information.html
- __Tutorial para Windows:__ https://medium.com/coinmonks/guide-setup-a-lightning-network-node-on-windows-8475206807f
- __Instalación en unix:__ https://github.com/bitcoin/bitcoin/blob/master/doc/build-unix.md
- __Eclair nodo completo:__ https://medium.com/coinmonks/guide-setup-a-lightning-network-node-on-windows-8475206807f
- __Video Explicativo fácil:__ https://m.youtube.com/watch?v=rrr_zPmEiME
- __Video HTLC:__ Hashed Time Locked Contracts https://m.youtube.com/watch?v=Ol12GrAy8yk
_______________________________
## Tutoriales con Raspberry PI
#### de Lightning Network
- __Nodo__ ___muy___ __Completo:__ https://stadicus.github.io/RaspiBolt/
- __Bicicleta Eléctrica de pago:__ https://github.com/leblitzdick/lightning-bike


_______________________________
## Lightning Apps
- __Tipo CryptoKitties:__  
https://btcdragons.lightningplayground.co/  
Wallet especial solo para el juego https://chrome.google.com/webstore/detail/btc-ln-collectibles/kafdhdbejepkebcinmpkhnkiiecccknk/related
- __Satoshi Place:__ muro de pintadas https://satoshis.place/
- __Y'alls:__ Sitio de post de (micro)pago https://yalls.org/
- __Test E-commerce:__ tienda de prueba para LN https://bitcoin-lightning.de/
- __E-commerce:__ https://www.coinmall.com/
- __Exchange:__ https://zigzag.bitlum.io/#/


_______________________________
## Otras cadenas laterales sobre BTC
- __Liquid:__  
Blockchain pública, permissionless, con Proof of Autorithy, donde Exchanges y grandes fondos de inversión hacen de validadores. Permite grandes movimientos de fondos entre Exchanges en 2 min. Creada por ___BlockStream___ como una capa de transmisión de grandes cantidades de dinero entre unos pocos usuarios. Sirve para el correcto funcionamiento de ___exchanges___ y otras autoridades que se estan creando en _CryptoLand_ Viene a ser __Ripple__ sobre __Bitcoin__. Los "usuarios" tienen que inscribirse en el sistema montado por ___BlockStream___, lo que lo convierte en un sistema de __Proof of Authority__
https://blockstream.com/liquid/  
https://docs.blockstream.com/liquid/technical_overview.html

- __RSK:__  
Con Merged Minning y la EVM. Rootstock fue creada antes y funciona sin __Segwit__, y permite la creación de __Smart Contracts__ con la __EVM__ sobre __Bitcoin__. Esto nos da la flexibilidad  que ofrece ___Solidity___ (y en el futuro ___WASM___), cediendo la seguridad por completo al __PoW__ de __Bitcoin__.


- __DriveChain__: proyecto en fase conceptual, pero muy interesante, también llamado State-Chains

- __Elastos__: https://github.com/elastos/Elastos.ELA.SideChain/tree/master/blockchain

_______________________________
## Futuras mejoras
#### de Bitcoin
- __MASK, Taproot, Grassroot, Schnoor Signatures:__

- __State Chain:__  
Permitirá el cambio de propietario de un UTXO sin realizar ninguna _tx onchain_
[Explicación: Diferencia entre sidechain y state chanel](https://hackernoon.com/difference-between-sidechains-and-state-channels-2f5dfbd10707)

#### de Lightning Network
- __Loop:__  
Saca fondos a BTC automáticamente para liberar el canal al cobrarse un invoice:  
https://blog.lightning.engineering/announcement/2019/06/25/loop-in.html

- __WatchTowers:__  
Servicios que guardan el historial de los canales para que no ocurra _doble gasto_ y no se puedan perder los fondos de los usuarios al borrar la wallet (y no conservar la BD)


_______________________________
## Principales empresas detrás de LN
- __Lightning Labs:__  
Son los "inventores" iniciales de la idea y han sido sus principales desarrolladores. Recibieron varios millones de $ por el CEO de Twitter

- __ACINQ:__  
Desarrolladores de Eclair

- __BlockStream:__  
Entre su plantilla se encuentran algunos de los desarrolladores de Bitcoin Core. Son los desarrolladores de Liquid.

- __Bitrefill:__
