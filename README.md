## Hi there 👋
 
I love programming. It is a creative process and it feels so good to see something growing under your fingertips. It is even better when someone finds value in it. I'm glad I chose this direction. I am keen on learning new things. There is always something to discover - new language, new library or framework, new pattern or a way to do stuff. It is only natural that I tried many languages and types of apps throughout the course of my programming career. And I know it is just the beginning 💖.
 
### My past projects
 
#### Beginnings
I am a gamer. Well at least I was once... Still enjoying occasional gaming session but you know... time and all that. Anyway, games had a big impact on my life. And that is also how I got to programming on a "serious level". 
 
##### TwinStar core
Back in 2010 when I was in my second year of Applied Informatics at a university I played WoW a lot. Specifically on a free server [TwinStar](https://www.twinstar-wow.com/). Free server generally means you are going to use an official game client but the backend is built from ground up (at first it was based on [Trinity Core](https://github.com/TrinityCore/TrinityCore)). To be honest quaility of the server was not good at the beginning. So I decided to contact the TwinStar team and started to help them with fixes and improvements. Work consisted of programming in `C++` (server core and complex behaviour scripts) and `SQL` (world content and simple scripts). We also did some `reverse engineering` of the client app (data mining) and `sniffing communication` between client and server. Fun stuff. You could feel those improvements as you could play through them yourself.
 
##### Web presentation and CMS
After a year or so I picked up another project. [A company](https://sindlar.eu/en/) `web presentation` with a custom `CMS` and `DMS` system on the backend. I was captivated by web development since we scratched its surface during highschool and this was a great opportunity to learn more. I have used a server-side page rendering using `PHP`, [Nette framework](https://nette.org/), [Latte](https://latte.nette.org/) templating engine, [Dibi](https://dibiphp.com/) database layer and other technologies.
 
##### Orbital Devastation - the game
In the spring of 2012 me and my friend Jakub said to ourselves: Why don't we make a game? It's a great time for us - we love games, we love coding and we have some spare time during college. Let's team-up and make it happen! 
And so we started working on **[Orbital Devastation](../../../orbital-devastation)**. We didn't have much experience but we had passion. I was learning `C#` at that time so we picked that as a programming language.
And as for the learning experience we intentionally didn't pick up any game framework or engine. We have started from the ground - building engine, rendering, scene objects, AI scripts, UI, networking (_multiplayer - yeah!_), shaders, collision detection... We also touched other areas as we had to make our own textures, sprites, sounds.
Even though we never _completely finished_ it - it is still a **playable** alpha version with _working bots, matchmaking, tournaments with up to six players, dedicated server, own lobby and a lot of assets_. Just **[try it yourself](../../../orbital-devastation/releases/tag/0.8.2)**, it doesn't even require installing - just download and run! We were working on it for about 16 months and with over 1200 commits I am proud of what we managed to create.
 
##### E-commerce project Ixipixi
In 2013 I worked for a half a year on an eshop-like project which featured _community-created art selling_. It was a `PHP` website based on [PrestaShop](https://www.prestashop.com/). Sadly it didn't make it to the production phase. But I swear it wasn't my fault 😀.
 
##### TwinStar websites
After the last project I have returned to TwinStar. This time I was asked to pick up their major web projects and to _push them up and beyond_. Those projects are [TwinHEAD](https://twinhead.twinstar.cz/) and [Armory](http://armory.twinstar.cz/).
* **Armory** is a website showcasing all players' characters with their equipment, achievements, stats, PvP rankings and much more. Site is written in `PHP` and behaves as an API providing character data in `XML` format from live databases. Raw XML data is then processed in a browser using `XSLT templates` which creates an HTML page as a result. While this may seem as a good idea (_client rendering, separation of concerns - data vs view_) it is a nightmare to maintain and extend as you can't easily debug it and find the problem. Can't recommend it for bigger projects. It is based on [wowarmory](https://github.com/Shadez/wowarmory/) project.
* **TwinHEAD** is the second website. It serves mainly two purposes: searchable database of everything in game (items, NPCs, spells, locations, achievements, dungeons...) and [bugtracker](https://cata-twinhead.twinstar.cz/?issues) which we built from ground up, connected it to previously mentioned database and tailored it for our specific needs. It is based on [AoWoW](https://github.com/Brueggus/aowow) project. Pages are mostly generated in `PHP` backend and partially constructed by `JavaScript` on client (tables and other more interactive bits). I have rewritten the site to use `MVC architecture` for better separation of concerns. It also employs [Smarty 3](https://www.smarty.net/) templating engine for view separation. Biggest challenges were: adding support for three latest game datadiscs (which required data mining from newer client apps and from other sources), creation of bugtracker and integration to other TwinStar services and infrastructure.
 
I have worked for Twinstar on-and-off for eight years.
 
 
#### Fulltime
##### TescoSW
In 2014 I have graduated from college and landed a fulltime job - **junior fullstack developer** in TescoSW. The product is labeled as an _"enterprise information system"_ and I have become a member of a team working on an in-house built `framework` which most of the company's products are using. Framework is based on a `model-driven architecture` and contains many tools for automatization and also a _custom WYSIWYG GUI editor_. Backend consists of multiple services (application service, cryptography, autentization, DMS...) and custom `ORM`. Everything written mostly in `C#`. There are also many _client apps_ consuming these APIs and I have started to work on a client in the `Silverlight` technology. It is something like a `WPF` app run in a browser in the .NET runtime provided by the _Silverlight plugin_ (Heard of FlashPlayer? This is the Microsoft's clone.).
 
After a year or two I have moved from backend and Silverlight to the development of a brand new `SPA` `HTML5` client written in `TypeScript`. _Client app_ is a part of the framework. The app basically just takes a _definition of a page_ created in WYSIWYG editor and _business data_ and renders interactive web page in the browser. Without any coding.
 
Shortly after the transition I have taken up a role of a **frontend software designer** which included responsibilities like definition of used technologies and principles used throughout the codebase and also management responsibilities regarding other developers working on the codebase.
 
**SPA**s are fun. It is a really challenging area as it is nowadays becoming as complex as the backend might be. But on the other hand you can create an app which is really ergonomic and great to work with. And you can feel it and users can feel it. We are using the newest technologies and bleeding-edge features introduced in browsers like `Service Worker`, `Web Workers`, `Web Components` and others. Lately we are transitioning from vanilla JavaScript and `Custom Elements` to `React` components and `Redux` state management. 
 
I believe in web technologies, they will be with us for a long time.
 
 
### Currently working on a personal project
_FireFairy_ is a personal _wishlist_ `PWA` (_progressive web app_). I am building it with `TypeScript` (_ofcourse_) and the `React/Redux` combo. I am aiming for full capabilities presented as [PWA pillars](https://web.dev/progressive-web-apps/) (e.g. the _installability_ and _desktop-app-like feel_).
Backend provides a `REST API` build on `serverless functions` powered by `Google Cloud Platform`. Data is persisted in a `Firebase NOSQL database`.
Not sure if I'm going to release sources to the public yet. Time will tell.
 
### Currently learning React/Redux
I am working on improving my functional and composition skills. `React` and `Redux` are built on quite simple principles but an overall design of an app using these principles is something else. There is always a way to design it better. And there is always one more gotcha or a feature to learn!
 
 
### My open source projects
 
#### Games
 
##### [orbital-devastation](../../../orbital-devastation)
Fast-paced 2D action single and multiplayer arcade-like game.
**`C#`** `indie-game` `game` `2d-game` `multiplayer-game` `arcade-game` 
 
##### [tribal-wars-helper](../../../tribal-wars-helper)
Desktop app which aids with various tedious tasks in a game _Tribal Wars_.
**`Java`** `bot` `tribal-wars` 
 
##### [zerg-rush](../../../zerg-rush)
Variation of Google's minigame Zerg Rush. Defend your Cargo and kill all Zergs!
**`TypeScript`** `typescript-course` `zerg-rush` `gamification` `es6` 
 
 
#### Tools
 
##### [subtitle-broom](../../../subtitle-broom)
App for management of subtitles in a video library.
**`C#`** `subtitles` `subtitles-files` `kodi` `plex` 
 
##### [periodic-backup](../../../periodic-backup)
Tool for frequent backups of a few files.
**`C#`** `backup` `backup-utility` `backup-tool` 
 
##### [encoding-converter](../../../encoding-converter)
Batch text file charset re-encoding CLI utility
**`C#`** `encoding` `text-encoding` `cli-utility` 
 
 
#### Azure DevOps Tools
 
##### [tfs-bug-printer](../../../tfs-bug-printer)
Chrome extension creating a HTML page formatted for print from any Azure DevOps Server query.
**`JavaScript`** `tfs` `azure-devops` `chrome-extension` `workitem` `print` 
 
##### [tfs-pr-validator](../../../tfs-pr-validator)
Deno web service which can validate the title of a pull request in Azure DevOps Services and informs it about pull request's validity.
**`TypeScript`** `deno` `pullrequest` `tool` `azure-devops` `pullrequest-validation`
 
##### [pr-watchdog](../../../pr-watchdog)
 
Pullrequest Watchdog is a web app for watching pullrequests in Azure DevOps repository.
**`TypeScript`** `azure-devops` `apollo` `react` `graphql` `mongodb` 
 
 
#### Templates
 
##### [wp-multiple-tsconfigs](../../../wp-multiple-tsconfigs)
WebPack configuration template for building TypeScript apps with multiple target environments.
**`TypeScript`** **`JavaScript`** `webpack` `configuration` `example`
 
##### [vsts-react-extension](../../../vsts-react-extension)
Configuration template for Azure DevOps extension development with the use of TypeScript and React. Also enables local development.
**`TypeScript`** `azure-devops-extension` `vss-extension` `vsts-extension` `typescript` `react` `local-development` `template` 
 
 
#### Other
 
##### [fish-feeder-controller](../../../fish-feeder-controller)
 
Script controlling a servo motor in a DYI fish feeder.
**`Python`** `raspberry-pi` `fish-feeder` `servo-motor`

