<h1 align="center">
  <a href="https://github.com/fuwu99/yugen"><img src="https://github.com/fuwu99/yugen/blob/main/assets/logo.png" alt="Yugen Selfbot" width="175"></a>
  <br>
  [ Yūgen Selfbot ]
  <br>
</h1>

<h4 align="center">[ Advanced - Safe - Performant ]</h4>

<p align="center">
  <a href="https://badge.fury.io/js/electron-markdownify">
    <img src="https://badge.fury.io/js/electron-markdownify.svg"
         alt="Gitter">
  </a>
  <a href="https://gitter.im/amitmerchant1990/electron-markdownify"><img src="https://badges.gitter.im/amitmerchant1990/electron-markdownify.svg"></a>
  <a href="https://saythanks.io/to/bullredeyes@gmail.com">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://www.paypal.me/AmitMerchant">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

<p align="center">
  <a href="#main-features">Features</a> •
  <a href="#pricings">Pricings</a> •
  <a href="#selfbot-wiki">Wiki</a> •
  <a href="#faq">FAQ</a> •
  <a href="#changelogs">Changelog</a>
</p>

<p align="center">♡<br></p>

* This is a selfbot project for a discord bot called Pokemeow!
* This is a **paid** product, and there's no demo!
* Reimagined from [Primrose](https://github.com/fuwu99/primrose-pokemeow).

## Main Features
![banner-main](https://github.com/fuwu99/yugen/blob/main/assets/banner/main-features.png)
* 🕷️ Automates everything a Pokemeow player does!
  - Hunting `(/pokemon)`
  - Fishing `(/fish spawn)`
  - Battling `(/battle)`
  - Explore `(/explore)`
  - Swapping `(/swap)`
  - Purchase balls `(/shop buy)`
  - Automatic release locking `(/release lock)`
  - Event tickets `(/event buy)`
  - Checklist tasks `(/daily, /hunt, /quest, /catchbot, /swap)`
  - Player tasks `(/egg, /lootbox, /grazz, /repel, /release duplicate)`
  - Research items exchange `(/research exchange)`
* 🥋 Accurate human imitation!
  - Custom browser user-agent!
  - Completely random interaction times
  - Coffee breaks ☕ with random durations
  - Random commands `(/pc, /stats, ...)`
* ⌛ Solves captchas automatically with ~99% accuracy & retries if fail!
* 🔧 Extensive & individualized configuration system!
* 🧈 Buttery-smooth execution & easy installation
* 🔔 Sends webhooks & windows notifications to let you know about events!
* ✨ Previously premium features are now integrated into main ones!
  - Battle AI is now part of `battle`!
  - Multi upgrade is now free!
* 📡 Full code revamp & game-changing features added!
  - WebUI 🖥️ (upgrade) 
  - Queue system -> Multiple modes at once `(/pokemon, /fish spawn, /battle)`
  - Fully functional `egg / quest claim` handler!
  - Battle revamp:
    * Autobattler (AI).
    * Blazing-fast API calls!
    * 100% accurate battle DMG calculation.
    * Automatic league progress completer!
    * Battle script system for special event NPCs!
  - User commands rework!
  - Inactivity detector & better error handling!

## Pricings
![banner-price](https://github.com/fuwu99/yugen/blob/main/assets/banner/pricings.png)
![prices](https://github.com/fuwu99/yugen/blob/main/assets/prices.png)

|               | Hunt | Fish | Battle | Explore | Swap | WebUI/GUI | Autobuy | ;cl & tasks | Research |
|---------------|------|------|--------|---------|------|-----------|---------|-------------|----------|
| Apprentice    | ✔️   | ❌  | ❌    | ❌      | ❌   | ❌       | ✔️      | ✔️         | ✔️      |
| Master        | ✔️   | ✔️  | ❌    | ❌      | ❌   | ❌       | ✔️      | ✔️         | ✔️      |
| Champion      | ✔️   | ✔️  | ✔️    | ❌      | ❌   | ✔️       | ✔️      | ✔️         | ✔️      |
| Completionist | ✔️   | ✔️  | ✔️    | ✔️      | ✔️   | ✔️       | ✔️      | ✔️         | ✔️      |

> Note: Captcha solver is now readily included in every purchase!
* Current discounts! (they STACK!) (Explained in [FAQs](#faq))
  - `[ACTIVE]` Yugen birthday 🎉 (5% off)
  - `[ACTIVE]` Referral codes (5% | 7.5% | 10% off) 

## Selfbot Wiki
![banner-wiki](https://github.com/fuwu99/yugen/blob/main/assets/banner/selfbot-wiki.png)
* The WebUI upgrade comes with an in-built wiki!
* The selfbot wiki is public for everyone to see! [Wiki](https://github.com/fuwu99/yugen/wiki)
  
## FAQ
![banner-faqs](https://github.com/fuwu99/yugen/blob/main/assets/banner/faqs.png)

## Changelogs
![banner-clgs](https://github.com/fuwu99/yugen/blob/main/assets/banner/changelogs.png)
```
 == NOTES == 
 - i forget stuff, so this might not be all the changes that happened
 - Between v1.1.0 and 1.1.8, I added so many stuff i cant remember the specific changes, so I dumped all into 1.1.8
 
 == TO DO ==
 * General
 - Add cash transferring
 - Add hunt tracker
 - Fix webhooks
 - Fix & clean up startup cog
 * Hunt
 - Fix custom pokemon
 * Battle
 - Add cache update for battle counts and wins

 == UPDATE 1.1.8 ==
 - Much faster program startup!
 * General
 - Added Streamer mode
 - Added option to disable pinning
 - Added console window title changer
 - Added asyncio queue getter
 - Added hard-coded user-agent instead of API fetching
 - Added customizability for bot durations
 - Fixed new account creation
 - Fixed RAM & performance issues
 - Fixed pinning permission error
 - Fixed user commands
 - Fixed command locks
 - Removed redundant util files
 * Captcha
 - Added immediate command enqueue after captcha
 - Added reconnect fallback captcha answer
 - Added captcha answer send error handlers
 - Removed suppressor 'with' clauses
 * Hunt
 - Added extra quest claiming for "completed the quest"
 - Fixed attribute error for held_item
 - Fixed hanging problem in [176, 80]
 * Fish
 - Added extra quest claiming for "completed the quest"
 * Battle
 - Added scripting system to turn your most complex battle strats into action! (tested on xmas_lance)
 - Added type convert for npc id (forgot :sobs:)
 - Added data for aegislash forms
 - Fixed critical damage multiplier 2 -> 1.5

 . . .
```
> Full changelog available @ [versions.txt](https://github.com/fuwu99/yugen/blob/main/versions.txt)


