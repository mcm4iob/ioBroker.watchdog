![Logo](admin/watchdog.png)

# ioBroker.watchdog

[![NPM version](https://img.shields.io/npm/v/iobroker.watchdog.svg)](https://www.npmjs.com/package/iobroker.watchdog)
[![Downloads](https://img.shields.io/npm/dm/iobroker.watchdog.svg)](https://www.npmjs.com/package/iobroker.watchdog)
![Number of Installations](https://iobroker.live/badges/watchdog-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/watchdog-stable.svg)

[![NPM](https://nodei.co/npm/iobroker.watchdog.png?downloads=true)](https://nodei.co/npm/iobroker.watchdog/)

**Tests:** ![Test and Release](https://github.com/mcm1957/ioBroker.watchdog/workflows/Test%20and%20Release/badge.svg)

## watchdog adapter for ioBroker

Monitor the values and updates of ioBroker states

## Note

This adapter is currently at state of investigation / prototyping. No real functionality is available.
Do NOT install this datapter until a stable version is released.

## General Description

This adapter monitores a configurable number of states. Depending on configuration the adapter can perform actions if

-   a state is not updated or changed during a configurable timeframe
-   if the value of a state does not match configured limits
-   if the value of a state changes faster / slower than a configured limit

... more to come ...

## Changelog

<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->

### 0.0.1-alpha.2 (2023-01-16)

-   (mcm1957) initial dummy release

## License

MIT License

Copyright (c) 2023 mcm1957 <mcm57@gmx.at>

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
