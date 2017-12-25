## Solomining proxy for equihash coins like Zclassic and Zcash.
## (READY FOR TESTING)

[![Join the chat at https://gitter.im/equihash-solomining/Lobby](https://badges.gitter.im/equihash-solomining/Lobby.svg)](https://gitter.im/equihash-solomining/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Made by the Zclassic community, configuration and documentation is [here](https://zdeveloper.org/equihash-solomining)

![picture alt](http://i.imgur.com/xB9XdVF.png)

Requirements
------------
* node v7+
* coin daemon

Install
-------------

```bash
sudo apt-get install build-essential libsodium-dev npm
sudo npm install n -g
sudo n stable
git clone https://github.com/Snowgem/snowgem-solo-mining
cd snowgem-solo-mining
npm update
npm install
```

Configure
-------------
Go to config.json and change it to your setup. Change the wallet address to your local address
![picture alt](https://i.imgur.com/a/jB5iV.png)

Run
------------
```bash
npm start
```

Update
-------------
Get rid of the node_modules folder then 
```bash
npm install
```

Differences between this and Z-NOMP
------------
* This is meant for solo mining
* There is no share system; Every "share" is the block solution
* No payments

Upcoming Feautures
-------------
* More API

Support
-------------
https://gitter.im/equihash-solomining

License
-------
Released under the GNU General Public License v2
http://www.gnu.org/licenses/gpl-2.0.html

_Forked from [z-classic/node-stratum-pool](https://github.com/z-classic/node-stratum-pool) which is licensed under GNU GPL v2_
