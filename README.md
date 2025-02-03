![Logo](admin/worx.png)

# ioBroker.worx

[![NPM version](https://img.shields.io/npm/v/iobroker.worx.svg)](https://www.npmjs.com/package/iobroker.worx)
[![Downloads](https://img.shields.io/npm/dm/iobroker.worx.svg)](https://www.npmjs.com/package/iobroker.worx)
![Number of Installations](https://iobroker.live/badges/worx-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/worx-stable.svg)

[![NPM](https://nodei.co/npm/iobroker.worx.png?downloads=true)](https://nodei.co/npm/iobroker.worx/)

**Tests:** ![Test and Release](https://github.com/iobroker-community-adapters/ioBroker.worx/workflows/Test%20and%20Release/badge.svg)

## Sentry

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Required

- Node 20 or 22
- JS-Controller >= 6.0.11
- Admin >= 7.0.23

## Worx (Kress, Landxcape and Ferrex) adapter for ioBroker

Control via cloud and mqtt

This adapter connects IoBroker with your Landroid Kress Landxcape or Ferrex mower via Cloud.
Temperatures, mowing times, battery level and various other data are read out from the mower.
The adapter can control the mower and you can change config params like mowtimes.

## Description

🇬🇧 [Description](/docs/en/README.md)</br>
🇩🇪 [Beschreibung](/docs/de/README.md)

## Discussion und Questions

🇩🇪 [Fragen](https://forum.iobroker.net/topic/4834/adapter-worx-landroid/)

<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->

## Changelog

### **WORK IN PROGRESS**

- (Lucky-ESA) Migration to ESLint9
- (Lucky-ESA) Node 20 required

### 3.1.1 (2024-11-04)

- (Lucky-ESA) Added JS-Controller Notification
- (Lucky-ESA) Dependencies updated
- (Lucky-ESA) New design for settings page added

### 3.1.0 (2024-09-10)

- (Lucky-ESA) Added Landroid IP
- (Lucky-ESA) Fixed interval
- (Lucky-ESA) Fixed Vision Edgecut

### 3.0.2 (2024-05-12)

- (Lucky-ESA) mowTimeExtend restricted input
- (Lucky-ESA) Fixed TypeError

### 3.0.1 (2024-05-08)

- (Lucky-ESA) Preperation mission Kress new API
- (Lucky-ESA) Fixed TypeError
- (Lucky-ESA) Fixed missing activity states
- (Lucky-ESA) Added update interval in instance setting
- (Lucky-ESA) Added last update

### 3.0.0 (2024-04-25)

- (Lucky-ESA) Fixed Sentry messages
- (Lucky-ESA) Catch publish crash
- (Lucky-ESA) Added Vision completely
- (Lucky-ESA) Node 18 required
- (Lucky-ESA) JS-Controller >= 5.0.19 required
- (Lucky-ESA) Admin >=6.13.16 required
- (Lucky-ESA) Catch aws_cer error and use old mqtt connection
- (Lucky-ESA) Delete ping

## License

MIT License

Copyright (c) 2023-2025 TA2k <tombox2020@gmail.com>

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
