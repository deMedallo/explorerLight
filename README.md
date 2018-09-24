# DM Block deMedallo based off github.com/etherparty/explorer

![DM Block deMedallo Screenshot](https://i.imgur.com/FHtPef2.jpg)

## Demo
...

## License

The code in this branch is licensed under GPLv3 (see LICENSE file)
Feel free to modify or reuse the code here.

## Donations

ETH Address: 0x0cb159875098ad4ee77b5c3d4f6de636c823235b

## Installation

```
git clone https://github.com/deMedallo/explorerLight
npm install
bower install
npm start
```

Make sure to install geth as well for the DM explorer to be able to function. Then run:
```
geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"
```

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer
