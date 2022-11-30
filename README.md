## INFO:
This is the good template ever made for Aoi.js replit.

It has so many features like commands, variables, statues, bot handlers, updated versions of packages, and a clean main file `index.js`.

- HTTP
- Installed discord.js and discord.py
- This template is made by: `@! ^• xKurty. •^#9669`
- Node version: `17.0.0`
- Aoi.js Version: `5.1.0`
- Stitchy Bot: `https://dsc.gg/stitchy`
- Support Server: `https://dsc.gg/stitchy-supp`
- Database: default
- Statues handler
- Variables handler
- Callbacks handler
- New Music
- Installed Lavalink for music functions
- Loader handler
- And many more handlers


## Setting up with Aoi.js:
This project has nodejs 17.0.0 already built-in and is pre-setup for your uses.

- `index.js` - *main file*
- `command handler` - disabled by default, you can enable it by removing `/*` and  `*/` from the start and at the end.


## IMPORTANT:
`SECRETS (ENV)`

- On the left side of the navigation, there should be a section for SECRETS aka Environment variables. 
- Add `TOKEN` and value = `(YOUR DISCORD BOT TOKEN)`


## 24/7 Online
Want to host your bot for 24 hours? Well here you go.

1. Get the link of your bot's website (you can get the link when you run your repl, then there will be pop up a website then you can get the link like `https://projectName.creatorName.repl.co`)
2. Go to [Uptimerobot](https://uptimerobot.com)'s website create an account (or login if you have already), then create new monitor and choose `HTTPs` for the type of your monitor then put your link (the link that you get in your repl website).
3. Then you're good to go, your bot will be now online for 24/7.


## Begin your Coding journey:
Read Aoi.js' [Documentation](https://akarui.leref.ga/v/aoi.js/).


## Command Handler:
By default it's disabled by comments.
Remove `/*` and `*/` to enable.

```js
 bot.cmd is object of Collections where the command data will be stored.

 "./commands/" is the path of folder where all the commands code will be present.
 ```

`commands` directory can be changed into any name you want.
- Make sure to update inside the loader.
```js
`loader.load(bot.cmd,'./PATH/')`
```


## Note:
You can modify any of the files, but there might be an error if you don't fix some directories.

You can run your repl manually, go to your shell or terminal then you can type these commands, just choose one. `node .`, `node index.js`, `npx node .`, and `npx node index.js`.