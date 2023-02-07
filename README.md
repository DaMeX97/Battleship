# BattleShip

Project for [Web technologies and applications][taw] course. This project has been done by:
- Dametto Alex
- Volpe Davide
- Zanatta Filippo

This repository is a copy of [Westfox-5](https://github.com/westfox-5/BattleShip) original repository.

## Introduction
This project consists in a multiplayer version of the classic game  _BattleShip_.

~~The game is available to play at: xxxxx.~~ Edit: our deployment has been removed for inactivity. The previous URL is not valid anymore. 

## Get Started
This guide lets you install the game and play with your local server. This means you can only play with other users connected to your server. You cannot see real time changes (like new games added from other players). 

    cd ~/Desktop
    git clone https://github.com/westfox-5/BattleShip
    cd BattleShip
---

#### Install all dependencies
   
    npm run install

Or choose what to install

    npm run install-server
    npm run install-web
    npm run install-desktop
    npm run install-android
---
#### Start the local Database

    npm run start-db

#### Start the server
    
    npm run start-server
Server runs at [localhost:8080][s]

---

#### Build & Execute clients
Choose what to execute
    
* Web:  [localhost:4200][c]

        npm run start-web

* Desktop:
  
        npm run build-desktop
        npm run start-desktop
        npm run generate-desktop :: generete an executable file in `releases/desktop` folder.


* Android:
        
        npm run build-android
        npm run generate-android :: generate an APK file in `releases/android` folder.


[taw]:http://www.dsi.unive.it/~bergamasco/webtech.html
[s]: localhost:8080
[c]: localhost:4200
