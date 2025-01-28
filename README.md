#  🚀DarKnuclei 

## 🔺目标

1. 对目标的测绘资产快速打点
2. 一堆目标快速打点
3. 扫描红队基础设施与服务

## 前言
DarKnuclei是一款适合针对红蓝对抗的一款工具，不仅仅可以在红队视角下的快速打点，还可以在蓝队视角下针对红队基础设施与服务进行探针扫描，DarKnuclei在针对红队基础设施进行扫描针对C2，采用强/弱特征，通过C2一些特征值去识别探针，在保证准确率的情况下去尽可能识别多C2，内置`yaml`语法，使用者可以自己编写`yaml`文件，识别特定的C2。

使用文档：[使用文档](https://ruoji6.github.io/posts/33805.html)

# 特征覆盖
✅	强特征

☑️	弱特征
## 平台/服务
| 名字                        | 类型     | 特征 | 计划中 | 备注                              |
| --------------------------- | -------- | ---- | ------ | --------------------------------- |
| ARL(灯塔)                   | platform | ✅    |        |                                   |
| Scope Sentry                | platform | ✅    |        |                                   |
| NPS                         | platform | ✅    |        |                                   |
| AWVS                        | platform | ✅    |        |                                   |
| Nessus                      | platform | ✅    |        |                                   |
| XSS平台                     | platform | ✅    |        |                                   |
| BeEF                        | platform | ✅    |        |                                   |
| H                           | platform | ✅    |        |                                   |
| LangSrcCurise               | platform | ✅    |        |                                   |
| Medusa                      | platform | ✅    |        |                                   |
| NextScan                    | platform | ✅    |        |                                   |
| prismx                      | platform | ✅    |        |                                   |
| CyberEdge                   | platform | ✅    |        |                                   |
| SerializedPayloadGenerator  | platform | ✅    |        |                                   |
| web-chains                  | platform | ✅    |        |                                   |
| RevSuit                     | platform | ✅    |        |                                   |
| MemShellParty               | platform | ✅    |        |                                   |
| vulfocus                    | platform | ✅    |        |                                   |
| gophish                     | platform | ✅    |        |                                   |
| testnet                     | platform | ✅    |        |                                   |
| rengine                     | platform | ✅    |        |                                   |
| JNDI-Injection-Exploit-Plus | Tools    | ✅    |        | 只针对ldap强特征，rmi,jetty弱特征 |
| JNDI-Injection-Exploit      | Tools    | ✅    |        | 只针对ldap强特征，rmi,jetty弱特征 |
| rogue-jndi                  | Tools    | ✅    |        | 只针对ldap强特征，rmi,jetty弱特征 |
| JNDIMap                     | Tools    | ✅    |        | 只针对ldap强特征，rmi,jetty弱特征 |
| ysoserial                   | Tools    |      | ✔️      |                                   |

## C2
| 名字           | 版本        | 登录/连接 | 监听端口 | UDP流量 | TCP流量 | HTTP/S流量 | 计划中 | 备注 |
| -------------- | ----------- | --------- | -------- | ------- | ------- | ---------- | ------ | ---- |
| vshell         | 4.9.3~4.6.0 |           | ✅        | ✅       | ✅       | ✅          |        |      |
| Cobalt Strike  |             | ✅         |          |         |         | ✅          |        |      |
| Metasploit     |             |           |          |         | ✅       | ✅          |        |      |
| Supershell     | 2.0.0       | ✅         | ✅     |         |         |            |        |      |
| Viper          |             | ✅        |          |         | ☑️        |            | ✔️      |      |
| Daybreak       |             |           |          |         |         |            | ✔️      |      |
| chisel         |             |           |          |         |         |            | ✔️      |      |
| sliver         |             |           |          |         |         |            | ✔️      |      |
| Havoc          |             |           |          |         |         |            | ✔️      |      |
| Iom            |             |           |          |         |         |            | ✔️      |      |
| Villain        |             |           |          |         |         |            | ✔️      |      |
| VenomRA        |             |           |          |         |         |            | ✔️      |      |
| ShadowPad      |             |           |          |         |         |            | ✔️      |      |
| Shad0w         |             |           |          |         |         |            | ✔️      |      |
| Remcos RAT     |             |           |          |         |         |            | ✔️      |      |
| QuasarRAT      |             |           |          |         |         |            | ✔️      |      |
| Pupy-C2        |             |           |          |         |         |            | ✔️      |      |
| PoshC2         |             |           |          |         |         |            | ✔️      |      |
| PlugX RAT      |             |           |          |         |         |            | ✔️      |      |
| Orcus-RAT      |             |           |          |         |         |            | ✔️      |      |
| Ninja          |             |           |          |         |         |            | ✔️      |      |
| Mythic         |             |           |          |         |         |            | ✔️      |      |
| Havoc          |             |           |          |         |         |            | ✔️      |      |
| Hak5 Cloud     |             |           |          |         |         |            | ✔️      |      |
| Gh0st          |             |           |          |         |         |            | ✔️      |      |
| Empire         |             |           |          |         |         |            | ✔️      |      |
| DeimosC2       |             |           |          |         |         |            | ✔️      |      |
| DcRAT          |             |           |          |         |         |            | ✔️      |      |
| Covenant       |             |           |          |         |         |            | ✔️      |      |
| Brute Ratel C4 |             |           |          |         |         |            | ✔️      |      |
| BitRAT         |             |           |          |         |         |            | ✔️      |      |
| AsyncRAT       |             |           |          |         |         |            | ✔️      |      |
| manjusaka      |             |           |          |         |         |            | ✔️      |      |


## 📢 使用
#### 环境配置：

1. 如果需要进行漏洞扫描需要将[nuclei](https://github.com/projectdiscovery/nuclei)加入环境变量【同时需要下载[nuclei-templates](https://github.com/projectdiscovery/nuclei-templates)，并在config.ini中配置】。
2. 如需使用测绘功能请修改`config.ini`添加key。
3. python版本：`python3.9`。
4. 如果是mac或linux请下载对于的执行程序在plugin目录，并配置`config.ini`。
   1. [observer_ward](https://github.com/emo-crab/observer_ward)
   2. [gogo](https://github.com/chainreactors/gogo)
   3. [tlsx](https://github.com/projectdiscovery/tlsx)
  
### 🔰技巧
DarKnuclei 分为红队蓝队模块

红队：快速对目标进行打点【测绘资产，WEB扫描，GOGO扫描】

蓝队：扫描红队基础设施与服务【扫描红队基础设施】
```
>python39 main.py -h

.__       .  .         .
|  \ _.._.|_/ ._ . . _.| _ *
|__/(_][  |  \[ )(_|(_.|(/,|
    DarKnuclei Scan v2.0 by RuoJi
    https://github.com/RuoJi6/DarKnuclei

usage: main.py [-h] {NSM,WEB,GOGO,RTSCAN} ...

红队快速打点利器

positional arguments:
  {NSM,WEB,GOGO,RTSCAN}
                        主命令帮助
    NSM                 测绘资产
    WEB                 WEB扫描
    GOGO                GOGO扫描
    RTSCAN              扫描红队基础设施与服务

optional arguments:
  -h, --help            show this help message and exit
```

## 【优先内测】
提交平台或C2或服务等提交至issus【在上面C2，平台/服务**表格**中没有的】，提交格式：ARL，Asset Reconnaissance Lighthouse，https://github.com/xxxx/ARL

三个工作日进行审核，通过则加入内测群。

## TODO：

- [ ] 搜索引擎js文件路径，以及ico图片hash搜索【手动导入，输入ico图标地址在线搜索】。
- [ ] 导出格式Excel报表。
- [ ] 对蜜罐识别进行识别调研，以及安全设备指纹。
- [ ] 针对其它资产测绘平台。
- [ ] 通过测绘得到IP资产，对IP资产进行端口扫描指纹识别。
- [ ] 钉钉企业微信漏洞扫描结果通知。
- [ ] 覆盖国内外C2。
- [ ] 编写`yaml`文件编写教程

## 关于/演示
关于 DarKnuclei，DarKnuclei专注于红蓝对抗一款工具，不仅可以扫描漏洞，快速打点，还可以扫描红队基础设施与服务，拥有高扩展的yaml格式指纹文件，方便自己编写红队基础设施指纹。
![image](https://github.com/user-attachments/assets/f585eabe-b85c-4350-838e-e3296d0c1e4a)
![image](https://github.com/user-attachments/assets/93cc0b5a-cf11-4b84-b161-3c1d33719624)
![image](https://github.com/user-attachments/assets/32d09dfc-d96b-4945-928c-d0a1f6aa5a74)





