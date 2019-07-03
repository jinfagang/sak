# sak

*sak* 更新继续。先列举一下peeper目前的功能：
- 局域网设备的ip地址扫描，这个很方便了，每次连树莓派直接扫描一下就知道当前局域网的所有设备；

接下来需要实现的功能：
- 监听从某个局域网发出来的网络请求包，这个有点像ettercap的嗅探行为？但是我想做到peeper里面，以后方便很多啊，反正是自己的工具。

这是用golang写的一个黑客工具。吊炸天必备，鄙人没事喜欢收集一些工具当做瑞士军刀，在急需的时候可以用用。那这个**偷窥者**便是其中的一把，也是最尖锐最锋利的一把。这个工具将让具有神一般的能力。具体来说它具有这么一些功能：

- 查看当前局域网的设备ip，并监视新加入局域网的设备ip；
- 中间人攻击，伪装为一个站点，当别人访问的时候向别人展示我们偷天换日的网站，设想一下当别人打开百度的时候，跳出一个黄色图片…;
- 捕捉局域网信息流，可以指定一个需要攻击的ip，监视从该ip发出的所有请求，比如淘宝用户名，密码等，对于没有加密的信息可以直接查看，比如对方在搜索的时候就可以捕捉搜索关键词下来；


除此之外，peeper还有许多不断在增加的新东西。欢迎大家star！持续更新！

![](https://i.loli.net/2018/03/11/5aa51b6765514.jpeg)


## What's sak?

I always got some issue and no where to find a solution:

- I need wifi passwords of next door wifi;
- I want to scrap package which send from my target computer and so that I can see what he is looking;
- I need gather information of a certain person throught a attack;

With all those commands, I decide to write a **Swiss Army Knife** contains all edge tools to finish all things above. This project is under construction now, welcome star and fork.


## Updates

**2019.07.03**: we opensource **sak**.
**2019.01.01**: **sak** now supports scan all devices ip from local network under same wifi;

**note**: this tools written in go, if you also interested in modern languages, you can checkout an editor written in rust: [m editor](https://github.com/jinfagang/m)

## Install

目前支持源码编译，直接：

```
go build -o peeper *.go
```



## Usage

使用方式也很简单，直接接上对应的模块即可。



## Copyright

**peeper**由*jinfagang*开发，under MIT license. 使用本软件造成的后果由当事人承担，仅供学习用。