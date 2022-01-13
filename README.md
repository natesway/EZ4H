<div align="right">
  Languages:
  English
  <a>| </a><a title="中文" href="/README_CN.md">中文</a>
</div>

# EZ4H

[![7MTSGd.png](https://s4.ax1x.com/2022/01/13/7MTSGd.png)](https://imgtu.com/i/7MTSGd)

[![releases](https://img.shields.io/github/v/release/FillAmeaPixelNetWork/EZ4H?display_name=tag&color=%231ab1ad)](https://github.com/FillAmeaPixelNetWork/EZ4H/releases)
[![players](https://img.shields.io/bstats/players/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![servers](https://img.shields.io/bstats/servers/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![license](https://img.shields.io/github/license/FillAmeaPixelNetWork/EZ4H)](https://github.com/FillAmeaPixelNetWork/EZ4H/blob/main/LICENSE)


Allow Minecraft:JE(1.12.2) connect to Minecraft:BE(1.16.210) servers!  

## 🎉Features
- [x] Login
- [x] Chat
- [x] Command
- [X] Xbox Auth
- [X] Chunks
- [X] Move
- [X] Players
- [X] Entitys
- [X] Block Entitys
- [X] Item Entitys
- [X] Entity Metadata
- [X] Entity Interact
- [X] Block Interact
- [X] Titles and other Messages
- [X] Inventory Action
- [ ] UIes
- [ ] Particles
- [x] Form UI
- [X] Level Events
- [ ] Sounds

## 👍Credits
It would basically be impossible to have EZ4H without these open source projects, wheather its just looking how thing works inorder to reverse translate them, looking at their code to see how thing work or copying a little bit of their code. We apperiate all these projects. ❤
- [MCProtocolLib](https://github.com/Steveice10/MCProtocolLib)
- [Bedrock-Protocol](https://github.com/CloudburstMC/Protocol)
- [TunnelMC](https://github.com/THEREALWWEFAN231/TunnelMC)
- [Nukkit](https://github.com/CloudburstMC/Nukkit/)

# How to use?
As with most servers written in Java, you need a startup `.BAT` to start it.  
~~~  
@echo  
java -jar ez4h.jar  
pause
~~~
Double click to run it. 
When there is a `Done!` It was started successfully. 

After this, you will see some files generated under the EZ4H root directory.Let's open the Config. 

~~~json
{
  "je_host": "127.0.0.1",
  "je_port": 25565,
  "be_host": "127.0.0.1",
  "be_port": 19132,
  "player-list": "A §bEZ§a4§bH§f§r Proxyed Server!\nhttps://github.com/MeditationDev/EZ4H",
  "advanced": {
    "debug": 0,
    "save-authdata": false,
    "xbox-auth": false
  }
}
~~~
(Yes, it's a JSON file)  
I think you already know how to configure this, but I'm going to go through it briefly.
