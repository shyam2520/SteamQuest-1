# SteamQuest
A website to analyze and predict steam community market prices.

## Setting up the environment
```
cd App
```
 - Create a .env file.
 - Put your steam api key as STEAM_API_KEY inside it. Get your own API KEY from [here](https://steamcommunity.com/dev/apikey).
 - Log into steam from your favourite browser.
 - Copy the steamLoginSecure cookie from the browser into your .env as STEAM_LOGIN_SECURE.
 - Also write your base URL (it will be ```http://localhost:8080/``` if you are running it locally) as REALM in .env
```
npm install
```

## Start the server
```npm start``` 
Server starts in port 8080 by default. Have fun.

## Team

- Vishal
- Ashwin
- Shyam
- Robin

## Deployed at

https://steam-quest.herokuapp.com
