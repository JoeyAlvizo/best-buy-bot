<h1 align="center">best-buy-bot 🎯</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
  <img src="https://img.shields.io/badge/npm-%3E%3D5.5.0-blue.svg" />
  <img src="https://img.shields.io/badge/node-%3E%3D9.3.0-blue.svg" />
</p>

## Dev Project Statment
Another deleted there repo for this initiasl project. 
I added best buy log in functionality and sped up some of the process of buying but i am still not getting hits for GPUs. 
I can work on this more if others are interested. 


## Install
`npm install`

## Usage

1. FIll in all the data in `config/prod/` and remove the string `template_` from the file extenstions
  
Add or remove the desired cards you want to purchase in `config/prod/tasks.json`

You must have discord notifcation set in order for the bot to work. If you do not want to use it, you must comment out any line of code that has `sendDiscordMessage` in `main.ts` and `bestbuy.ts`.

2. Use `npm run start` to run the bot

3. Now wait for the item to come in stock

4. Stop the bot at any time with `npm run stop`

Note: the bot will no longer run once a purchase has been made. To be able to use the bot again, delete `purchase.json` from the main folder.
