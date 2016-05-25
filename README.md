# Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of [packages](#packages) and [resources](#resources) regarding Steam development.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

The purpose of this document is to provide a quick overview over existing packages (libraries, modules etc.) and resources available regarding Steam client automation and WebAPI usage. Whenever you need to start a new project, have a look at the list of packages and see if there is anything useful for your use case. If you need technical details or tutorials, check out the resources section.

## Table of Contents

- [Packages](#packages)
  - [C#](#c)
  - [Node.js](#nodejs)
  - [PHP](#php)
  - [Go](#go)
  - [Python](#python)
  - [C++](#c-1)
  - [Java](#java)

- [Resources](#resources)
  - [General](#general-1)
  - [Tutorials](#tutorials)
  - [Posts](#posts)
  - [Standalone tools](#standalone-tools)
  - [Discussion boards](#discussion-boards)

## Packages

> 💡 Many of these package repositories provide helpful READMEs and wiki pages, which explain the usage and/or provide examples. Do not forget to check them out when using particular package.

### C&#35;

- [SteamKit2](https://github.com/SteamRE/SteamKit) - .NET library designed to interoperate with Valve's Steam network.
- [SteamAuth](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality.
- [SteamBot](https://github.com/Jessecar96/SteamBot) - Automated bot software for interacting with steam trade.
- [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) - SteamBot fork which focuses on trade offers.

### Node.js

#### General

- [steam](https://github.com/seishun/node-steam) - Interface directly with Steam servers from Node.js.
- [steam-client](https://github.com/DoctorMcKay/node-steam-client) - API-compatible fork of node-steam's SteamClient.
- [steam-user](https://github.com/DoctorMcKay/node-steam-user) - Feature-rich easy-to-use Steam client.
- [vapor](https://github.com/scholtzm/vapor) - Lightweight Steam client framework.
- [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) - Simple base class for a Steam bot.

#### WebAPI

- [steam-web-api](https://github.com/seishun/node-steam-web-api) - Lightweight WebAPI wrapper.
- [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) - WebAPI wrapper with support for extra HTTP headers sent by Steam.

#### Trading

- [steam-trade](https://github.com/seishun/node-steam-trade) - Node.js wrapper around Steam live trading.
- [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) - Steam Trade Offers for Node.js.
- [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - Simple and sane Steam trade offer management.

#### Game interaction

- [tf2](https://github.com/DoctorMcKay/node-tf2) - Interact directly with TF2 game coordinator.
- [csgo](https://github.com/joshuaferrara/node-csgo) - Interact directly with CS:GO game coordinator.
- [dota2](https://github.com/RJacksonm1/node-dota2) - Interact directly with Dota 2 game coordinator.

#### Community & store automation

- [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity) - Interact with steamcommunity.com. Also allows to confirm trade offers.
- [steamstore](https://github.com/DoctorMcKay/node-steamstore) - Interact with store.steampowered.com.
- [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) - Retrieve SteamCommunity cookies if you are running Steam network client.
- [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) - Automatically registers and retrieves Steam API key.
- [steam-parental](https://github.com/Alex7Kom/node-steam-parental) - Disable parental lock.

#### Authentication

- [steam-login](https://github.com/cpancake/steam-login) - Simple Connect / Express Steam authentication library.
- [passport-steam](https://github.com/liamcurry/passport-steam) - Steam (OpenID) authentication strategy for Passport and Node.js.
- [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) - Steam OpenID integration for Meteor Accounts.

#### Misc

- [steam-resources](https://github.com/seishun/node-steam-resources) - Steam's enums, protobufs and structs.
- [steam-crypto](https://github.com/seishun/node-steam-crypto) - Node.js implementation of Steam crypto.
- [steam-groups](https://github.com/scholtzm/node-steam-groups) - Custom node-steam handler which provides group functions.
- [steamid](https://github.com/DoctorMcKay/node-steamid) - SteamID usage and conversion made easy.
- [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) - Easily generate 2FA codes used by Steam.
- [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - Simplified interface for a steam chat bot.
- [vdf](https://github.com/RJacksonm1/node-vdf) - vdf to object and vice versa.
- [steamrep](https://github.com/scholtzm/node-steamrep) - Check user's SteamRep reputation.
- [reptf](https://github.com/scholtzm/node-reptf) - Check user's rep.tf reputation.

### PHP

- [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) - A PHP library for interacting with the Steam Community website.

### Go

- [steam](https://github.com/Philipp15b/go-steam) - Steam's protocol in Go.
- [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) - Port of SteamAuth in Go.

### Python

- [steam](https://github.com/ValvePython/steam) - Module for various interactions with Steam.
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) - Python port of SteamKit.
- [steamodd](https://github.com/Lagg/steamodd) - Steam tools library.

### C++

- [SteamPP](https://github.com/seishun/SteamPP) - C++ library to interoperate with Steam servers.

### Java

- [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) - Java port of SteamKit.

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xpaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam as OpenID provider](http://steamcommunity.com/dev)
- [Steam API key registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - List of `EResult` codes with possible explanations.

### Tutorials

- [Creating a Steam Trade Bot with Node.js](https://firepowered.org/developer/create-a-steam-trade-bot-with-nodejs-iojs-updated-for-node-steam-v1-0/)

### Posts

- [Item IDs explained](https://dev.doctormckay.com/topic/332-identifying-steam-items/)
- [Everything related to Escrow](https://github.com/DoctorMcKay/node-steam-totp)
- [Understanding avatar hash](https://www.reddit.com/r/SteamBot/comments/3cv6k7/problem_downloading_an_avatar_using/)

### Standalone tools

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - Intercept Steam client's network messages.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - Inspect messages dumped by NetHook2.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - Generate 2FA codes directly in your web browser.

### Discussion boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum](https://github.com/steam-forward/node-steam-forum)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.
