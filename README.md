![Completion 1.0.0](https://img.shields.io/badge/completion%20v1.0.0-3%25-red) ![Help Wanted](https://img.shields.io/badge/%20-help--wanted-%23159818)  ![Version 0.9.3](https://img.shields.io/badge/version-v0.9.5-blue) ![Sponsors](https://img.shields.io/badge/sponsors-0-red)

## qDesk Quests

## Description

qDesk Quests is a module for qDesk. It's accessible across qDesk, you can use it with qDesk Messages and other qDesk modules.

It's the core module of the Quest Network and allows to create and to join quests. 

If you are using [Quest OS](https://github.com/QuestNetwork/quest-os-js) in your applications, you can even use the underlying channels and data in your own application by booting with [Quest Engine JS](https://github.com/QuestNetwork/quest-engine-js).

qDesk Quests offers the ability to share and join quests shared by peers on the network. qDesk Quests is connected to [qDesk Social](https://github.com/QuestNetwork/qd-social-js) and uses the station supplied by qDesk Social. qDesk Quest and qDesk Social are modules for [qDesk](https://github.com/QuestNetwork/qDesk) and it's built on [Quest OS](https://github.com/QuestNetwork/quest-os-js) which makes use of the [Interplanetary Filesystem](https://ipfs.io), [IPFS GossipSub](https://blog.ipfs.io/2020-05-20-gossipsub-v1.1/), [IPFS DAGs](https://docs.ipfs.io/concepts/merkle-dag/), and [qDesk](https://github.com/QuestNetwork/qDesk), our example app based on [Angular10](https://angular.io/).

We have chosen Angular/Electron as an example environment because we believe it offers the best accessibility for developers coming from any other language/framework. The Quest Network is already being used in Python on PyQt5 and we aim to provide the underlying library in Go and wherever possible in Rust as well.

[qDesk](https://github.com/QuestNetwork/qDesk) works in the browser, as an Electron on Windows, Mac and Linux and Android using Cordova.

Check out other [Awesome Quest Network dApps](https://github.com/QuestNetwork/awesome/blob/master/README.md)!

## Security
![Completion 1.0.0](https://img.shields.io/badge/OAEP-4096%20Bit-green) ![EC](https://img.shields.io/badge/EC-P&#8208;521-green) ![AES](https://img.shields.io/badge/AES-256%20Bit-yellow)

[Quest OS](https://github.com/QuestNetwork/quest-os-js) uses [4096 Bit RSA-OAEP](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Operation) encryption, [256 Bit AES-CBC](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) encryption and [NIST P-521 EC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography#Fast_reduction_(NIST_curves)) signatures.

## Manual & Documentation

See our automated documentation for more information: https://questnetwork.github.io/docs

## Lead Maintainer

[StationedInTheField](https://github.com/StationedInTheField)

## Support Us
Please consider supporting us, so that we can build a non-profit for this project (ツ)

| Ethereum| Bitcoin |
|---|---|
| `0xBC2A050E7B87610Bc29657e7e7901DdBA6f2D34E` | `bc1qujrqa3s34r5h0exgmmcuf8ejhyydm8wwja4fmq`   |
|  <img src="https://github.com/QuestNetwork/qDesk/raw/master/doc/images/eth-qr.png" >   | <img src="https://github.com/QuestNetwork/qDesk/raw/master/doc/images/btc-qr.png" > |

## Development

### Planning 

See our [Kanban](https://github.com/orgs/QuestNetwork/projects/1) for the development of 0.9.5, feel free to add or pick up features!

### Building

qDesk Quests is a module of [qDesk](https://github.com/QuestNetwork/qDesk), so please see https://github.com/QuestNetwork/qDesk#development for instructions.

### Commands

**Prepare Package**

``npm run inst`` Removes `package-lock.json` and runs ``npm install``

We added an example ```swarm.json``` to the ```src/app``` folder with an example node to make reproduction easier, but we strongly recommend to use our [Quest CLI](https://github.com/QuestNetwork/quest-cli) to test and build the app.

Pro Tip: Put a file in your `/bin` that runs the quest-cli like so `node /path/to/quest-cli/index.js` from any folder on your system. It's much nicer.

## Roadmap

**0.9.5**
- Basic functionality

## License
GNU Affero GPLv3
