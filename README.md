![Logo](admin/nfa.png)
# ioBroker.nfa

[![NPM version](http://img.shields.io/npm/v/iobroker.nfa.svg)](https://www.npmjs.com/package/iobroker.nfa)
[![Downloads](https://img.shields.io/npm/dm/iobroker.nfa.svg)](https://www.npmjs.com/package/iobroker.nfa)
![Number of Installations (latest)](http://iobroker.live/badges/template-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/template-stable.svg)
[![Dependency Status](https://img.shields.io/david/Author/iobroker.nfa.svg)](https://david-dm.org/Dreamboy74de/iobroker.nfa)
[![Known Vulnerabilities](https://snyk.io/test/github/Author/ioBroker.nfa/badge.svg)](https://snyk.io/test/github/Author/ioBroker.nfa)

[![NPM](https://nodei.co/npm/iobroker.nfa.png?downloads=true)](https://nodei.co/npm/iobroker.nfa/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/Dreamboy74de/ioBroker.nfa/master.svg)](https://travis-ci.org/Dreamboy74de/ioBroker.nfa)

## Notifications for FireTV Adapter

Ein Adapter zur Texteinblendung auf einen FireTV Stick..

Inspiriert von der derzeitigen eingeschränkten Möglichkeit, Nachrichten in Textform direkt auf den Bildschirm eines mit FireTV Stick betriebenen TV anzuzeigen.
Das Original entwickelte App für Android hat folgende Funktion : Position / Größe / Farbe / Einblendezeit. Sämtliche Meldungen(Notifications) das ein Androidhandy bekommt werden an den mit dem Gleichlautenden App das auf den FireTV Stick ausgeführt wird weitergeleitet.

Für ioBroker bedeutet die JETZIGE Vorgehensweise : 
- Ein Telegram Bot mit dem Telegram Adapter anlegen
- Diesen Bot auf einem Androidhandy ebenfalls anlegen (somit werden schonmal alle erdenklichen Meldungen von ioBroker zum Handy geleitet.
- Das App im Playstore suchen "Notifications for FireTV" und ebenfalls auf den FireTV Stick installieren.
- Handy und FireTV darüber koppeln. 
- In der Handy App in Einstellungen auf "Aktiv bleiben" Stellen sowie unter Anwendungen dort Telegram auswählen.
- Optische Einstellungen über Position/Größe/Farbe/Einblendezeit ebenfalls festlegen.

Von nun an werden Meldungen die der Telegram Bot empfängt umgehend auf den Bildschirm eines TV mit FireTV eingeblendet.

Dieser Adapter hier soll den ganzen Part über den Telegram-Bot und dem Handy übergehen, und direkt die Meldungen auf den TV einblenden.... 


## Changelog

### 0.0.1
* (Dreamboy74de) initial release

## License
MIT License

Copyright (c) 2020 Dreamboy74de <heiko.reyer@mail.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
