# zdiscord

[![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=opensourceinitiative)](https://opensource.org/licenses/MIT)
[![Donate on PayPal](https://img.shields.io/badge/Donate-PayPal-%2300457C?style=for-the-badge&logo=paypal)](https://paypal.me/zfbx)
[![Sub on Patreon](https://img.shields.io/badge/Support-Patreon-%23FF424D?style=for-the-badge&logo=patreon)](https://www.patreon.com/zfbx)

A Discord whitelist (allowlist) and moderation tool

I've not seen many decent whitelist systems out there that connect with discord and the good ones seem to use oauth but I wanted more.. specifically I wanted to be able to have a full blown bot built in and be able to have bi-directional communication between the server and discord, so here it is!

## Features

- Completely standalone, no dependencies or need for running external applications
- Commands to see online users, info, etc
- Moderation commands to kick someone or everyone
- Send server wide announcements from a command in discord
- Easy to translate and customize with locales!
- Built in `!help` command for discord (prefix may be different if you changed it in your config)
- Easy to expand and customize with modular commands!
- Supports QBCore! Included: `!revive, !jail, !giveitem, !kill, !setjob` and more!

## Support

Before we get into the setup I just want to say, I've built and polished this resource from the ground up for free and open sourced it for you. If you enjoy it and would like to send a thanks I have a [ko-fi](https://ko-fi.com/zfbx8), [Paypal](https://paypal.me/zfbx) and I even have a [Patreon](https://www.patreon.com/zfbx)! Any and all support is greatly appreciated but in no way manditory, all my resources will be free and open source :)


## How to use

All the config options for this module are to be set inside your server .cfg file

1. Copy the inner `zdiscord` directory into your fiveM resources directory
2. Add `ensure zdiscord` (or whatever you renamed it to) to your server's .cfg
3. Adjust the `config.js` variables to how you'd like them.


## Languages

- en - English - By zfbx
- de - Deutsch / German - By Anonymous


## FAQ

Moved to [FAQ Wiki Page](https://github.com/zfbx/zdiscord/wiki/Frequently-Asked-Questions)

## Change log

**3.2.0 - Convars everywhere!**

- Convar hooks added for nearly every config option [Read More](https://github.com/zfbx/zdiscord/wiki/Convars)
- Slimmed up locales by removing console log messages
- Added {{prefix}} to the global variables


**3.1.0 - QBCore (potential ESX) support added**

- Commands starting with `qb-` will load automatically if QBCore is detected.
- Placeholders for `esx-` commands have been added.
    

**3.0.0 - Modular commands!**

- Commands are now loaded dynamically from the `/commands` folder
- Help command now has sub commands `!help commandName`
- New DM command
- various Error checks and fixes
    

**2.0.0 - Github Release**

- polished standalone
- Added translation support


**1.0.0 - First unsupported build**

- A lot.



## License

I'm releasing this under the **MIT License** asking only that you preserve my credit (zfbx) in whatever you do with it :)