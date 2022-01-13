<div align="right">
  语言:
  中文 | 
  <a title="English" href="/README.md">ENG</a>
</div>

# EZ4H
[![7MoKHO.png](https://s4.ax1x.com/2022/01/13/7MoKHO.png)](https://imgtu.com/i/7MoKHO)

[![releases](https://img.shields.io/github/v/release/FillAmeaPixelNetWork/EZ4H?display_name=tag&color=%231ab1ad)](https://github.com/FillAmeaPixelNetWork/EZ4H/releases)
[![players](https://img.shields.io/bstats/players/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![servers](https://img.shields.io/bstats/servers/10109)](https://bstats.org/plugin/bukkit/EZ4H/10109)
[![license](https://img.shields.io/github/license/FillAmeaPixelNetWork/EZ4H)](https://github.com/FillAmeaPixelNetWork/EZ4H/blob/main/LICENSE)

打破MC服务器壁垒，让Java版玩家进入基岩版服务器！

版本支持：JE 1.12.2 连接 BE1.16.210

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
如果没有这些开源项目，基本上就不可能有EZ4H！无论是对其反编译以查看实现原理，还是使用些许它们的代码，我们都感谢所有这些项目。❤
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
**`je_host` 和 `je_port`** 是JE玩家连接服务器时使用的IP和端口（局域网），可按照个人需要配置。

**`be_host` 和 `be_port`** 是所连接BE服务器的IP和端口。EZ4H支持代理外部服务器。你既可以填写局域网IP，即本地的BE服务器地址；也可以填写网络服务器的IP（如EaseCation的IP），以此通过EZ4H进入你想玩的BE服务器。（懂得都懂![img](https://www.mcbbs.net/static/image/smiley/tong/....png))

**`player-list`** 是JE玩家按tab键显示的文本内容。

**`xbox-auth`** 表示是否开启xbox验证。开启可防止JE玩家离线登录，但会带来一些限制；若设置为false关闭，则需要确保所要连接的BE服务器的xbox验证也是关闭状态。

## 游玩

配置好后，确保EZ4H和你想要连接的BE服务端或服务器都启动，打开你的Java版Minecraft，输入你刚刚在je_host配置的IP和端口，然后就能连接你在be_host那里填写的的BE服务器地址啦！

