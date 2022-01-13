<div align="right">
  语言:
  中文
  <a title="English" href="/README.md">ENG</a>
</div>

# EZ4H
![icon](/EZ4H_icon.png)

[![releases](https://img.shields.io/github/v/release/FillAmeaPixelNetWork/EZ4H?display_name=tag&color=%231ab1ad)](https://github.com/FillAmeaPixelNetWork/EZ4H/releases)
[![players](https://img.shields.io/bstats/players/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![servers](https://img.shields.io/bstats/servers/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![license](https://img.shields.io/github/license/FillAmeaPixelNetWork/EZ4H)](https://github.com/FillAmeaPixelNetWork/EZ4H/blob/main/LICENSE)

打破MC服务器壁垒，让Java版玩家进入基岩版服务器！

版本支持：JE 1.12.2 连接 BE1.16.200

## 🎉特性
- [x] 登录
- [x] 聊天
- [x] 命令
- [x] Xbox验证
- [x] 区块加载
- [x] 移动
- [x] 玩家
- [x] 实体
- [x] 方块
- [x] 物品
- [x] 实体元数据
- [x] 实体交互
- [x] 方块交互
- [x] 服务器标题及信息
- [x] 物品栏操作
- [ ] UI
- [ ] 粒子
- [x] GUI表单
- [x] 等级事件
- [ ] 声音

## 👍鸣谢
如果没有这些开源项目，基本上就不可能有EZ4H！无论是对其反编译以查看实现原理，还是复制一点它们的代码，我们都感谢所有这些项目。❤
- [MCProtocolLib](https://github.com/Steveice10/MCProtocolLib)
- [Bedrock-Protocol](https://github.com/CloudburstMC/Protocol)
- [TunnelMC](https://github.com/THEREALWWEFAN231/TunnelMC)
- [Nukkit](https://github.com/CloudburstMC/Nukkit/)

# 使用教程

## 运行

与大多数用 Java 编写的服务端一样， 你需要一个 `.BAT` 批处理文件来启动。  
~~~  
@echo  
java -jar ez4h.jar  
pause
~~~
双击运行。当屏幕上显示 `Done!` 即启动成功。

## 配置

之后，你会看到EZ4H在安装根目录下生成了一些文件。让我们打开其中的配置文件 `config.json` 。

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
**je_host和je_port**顾名思义也就是你想让JE玩家连接服务器时使用的IP和端口（注意是**内网ip和内网端口**），按照你个人需要来配置。

**be_host和be_port**指的是你想让JE玩家进入的那个BE服务器的IP和端口。这里注意，EZ4H是支持连接外部服务器的。什么意思呢？你既可以在ip那里填写本地ip，也就是让玩家连到同一台主机上的BE服务器；也可以填写一个其他服务器的ip（比如EaseCation等等）让你可以通过EZ4H进入一个你想玩的BE服务器。（一般这么做是想干什么的就⑧用我多说了吧，懂得都懂![img](https://www.mcbbs.net/static/image/smiley/tong/....png)）

**player-list**就是玩家按tab显示的内容，

**xbox-auth**则是是否开启xbox验证（如果设置为false关闭，则你所要连接的BE服务器的xbox验证也必须是关闭状态），开启的话可以防止一些JE玩家用离线登录搞♂事情，但是也会带来一些限制。

按照你的需求来进行配置。配置好了之后，将EZ4H服务端和你想要连接的BE服务端都启动，现在打开你的JE版Minecraft，输入你刚刚在je_host那里填入的内网ip、端口对应的外网ip、端口，然后就能连接你在be_host那里填写的的BE服务器啦！

