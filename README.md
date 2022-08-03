Tokenomixs
=======



Description
===========

Tokenomixs is an empire-building game written in Javascript with the help of the jQuery library.

Features
========

- Over 35 types of buildings, each intertwined in the chain of production.
- Custom climate zone, each with specific buildings.
- Global market, player can trade goods with other settlements.
- Army! Navy! Soldiers! Ships!
- Fame system that allows your city to level up via trades, conquers and special buildings.
- Prestige system that affects diplomacy.
- Each city in the game world is linked via a influence system that needs to be maintained for diplomacy to work.
- Random events that can change your diplomacy status with the other cities, give you coins or
random resources.
- Espionage, subvert cities, destroy buildings, sabotage.
- Ranking screen, where cities get ranked according to their status in the world.
- Declare war, propose alliances and pacts, ask other settlements to join your city, propose cease fire.

Playing
=======

## 1. With Docker

	$ docker build -t civitas .

	$ docker run --name civitas-dev -d -p 10082:80 civitas

And point your browser to `http://localhost:10082`.



Dependencies
============

- [jQuery 3.2.1](https://jquery.com/)
- [jQuery UI 1.11.2](https://jqueryui.com/)
- [jQuery Tipsy 1.0.0a](https://github.com/jaz303/tipsy)
- [jQuery scrollTo 1.4.14](https://github.com/flesler/jquery.scrollTo)
- [CryptoJS 3.1.9](https://github.com/brix/crypto-js)

Thanks
======
