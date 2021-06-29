  # StuntStorm's Easy to use **Op Commands NPM**

Op Commands for Administrators to maintain and protect the server from hackers and raiders

![@stuntstormmath (2)](https://user-images.githubusercontent.com/56226566/123737198-2cb03d00-d8c0-11eb-8e53-724367f28395.png)



## Installation ⚒️

### ``` npm i @stuntstorm/op-commands --save```

## Usage

### Require with any Variable
```
const package = require("@stuntstorm/op-commands")
```

### Over-Powered Commands 🐱‍🏍

#### NUKE COMMAND : 
#### Use this if the raiders or anyone has leaked your private info/ or just want to clear the chat
Nukes the Channel (Removes all the Chats in that channel and replaces with clear Channel) 
```
package.nuke(message,client,args);
```
#### LOCKDOWN COMMAND : 
#### Use this if you think theres possible attack from raiders or hackers
Locks down the entire server with a simple command and once the threat is handled unlock the server at your wish

```
package.lockdown(message,client,args)
```
#### OP-BAN COMMAND : 
#### Use this if you get info that certain user id is a hacker or raider
Use this command to op-ban someone who isnt in your server. Remove Raiders/Hackers and keep your server protected!
```
package.opban(message,client,args)
```

## Setup 🛠️

#### Setting Up Nuke Command
```
const package = require("@stuntstorm/op-commands")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!nuke") {
    package.nuke(message,client,args);
  }
});

client.login("token");
```
#### Setting Up Lockdown Command
```
const package = require("@stuntstorm/op-commands")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!lockdown") {
    package.lockdown(message,client,args);
  }
});

client.login("token");
```
#### Setting Up Op-Ban Command
```
const package = require("@stuntstorm/op-commands")
const Discord = require('discord.js');
const client = new Discord.Client();

client.on("message", message => {
  if(message.content == "!opban") {
    package.opban(message,client,args);
  }
});

client.login("token");
```
## Example Scenerio 💻

#### Index.js Code : 
![image](https://user-images.githubusercontent.com/56226566/123736718-4a30d700-d8bf-11eb-9549-cd644c6f7023.png)
#### Discord Output : 
![image](https://user-images.githubusercontent.com/56226566/123736827-7fd5c000-d8bf-11eb-9f17-7c090987ed3e.png)
#### Ban Logs Output : 
![image](https://user-images.githubusercontent.com/56226566/123736875-9a0f9e00-d8bf-11eb-8464-dd9f56da58a9.png)


## Support 🐱‍💻

Feel free to join the support server : https://discord.gg/u6XzUFkKTn

StuntStorm's Github : https://github.com/StuntStorm

More NPM Packages : https://www.npmjs.com/~stuntstorm

## NOTE 🗃️

This package is protected under MIT license. 🔒

## Bots using this Project 👾
### [StuntStorm Discord bot](https://discord.com/oauth2/authorize?client_id=850011982777417759&scope=bot&permissions=268443702) by StuntStorm#7231

### Created and Published by StuntStorm
