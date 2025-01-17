#  🚀DarKnuclei 

## 🔺目标

1. 对目标的测绘资产快速打点
2. 一堆目标快速打点
3. 扫描红队基础设施与服务

## 前言
DarKnuclei是一款适合针对红蓝对抗的一款工具，不仅仅可以在红队视角下的快速打点，还可以在蓝队视角下针对红队基础设施与服务进行探针扫描。

:white_check_mark:	强特征

:ballot_box_with_check:	弱特征
## 平台/服务
| 名字                        | 类型     | 特征               | 计划中                  | 备注                                  |
| --------------------------- | -------- | ------------------ | ----------------------- | ------------------------------------- |
| ARL(灯塔)                   | platform | :white_check_mark: |                         |                                       |
| Scope Sentry                | platform | :white_check_mark: |                         |                                       |
| NPS                         | platform | :white_check_mark: |                         |                                       |
| AWVS                        | platform | :white_check_mark: |                         |                                       |
| Nessus                      | platform | :white_check_mark: |                         |                                       |
| XSS平台                     | platform | :white_check_mark: |                         |                                       |
| BeEF                        | platform | :white_check_mark: |                         |                                       |
| H                           | platform | :white_check_mark: |                         |                                       |
| LangSrcCurise               | platform | :white_check_mark: |                         |                                       |
| Medusa                      | platform | :white_check_mark: |                         |                                       |
| NextScan                    | platform | :white_check_mark: |                         |                                       |
| prismx                      | platform | :white_check_mark: |                         |                                       |
| CyberEdge                   | platform | :white_check_mark: |                         |                                       |
| SerializedPayloadGenerator  | platform | :white_check_mark: |                         |                                       |
| web-chains                  | platform | :white_check_mark: |                         |                                       |
| RevSuit                     | platform | :white_check_mark: |                         |                                       |
| MemShellParty               | platform | :white_check_mark: |                         |                                       |
| vulfocus                    | platform | :white_check_mark: |                         |                                       |
| gophish                     | platform | :white_check_mark: |                         |                                       |
| testnet                     | platform | :white_check_mark: |                         |                                       |
| rengine                     | platform | :white_check_mark: |                         |                                       |
| JNDI-Injection-Exploit-Plus | Tools    | :white_check_mark: |                         | 只针对ldap强特征，rmi,jetty等端口弱特征 |
| JNDI-Injection-Exploit      | Tools    | :white_check_mark: |                         | 只针对ldap强特征，rmi,jetty等端口弱特征 |
| rogue-jndi                  | Tools    | :white_check_mark: |                         | 只针对ldap强特征，rmi,jetty等端口弱特征 |
| JNDIMap                     | Tools    | :white_check_mark: |                         | 只针对ldap强特征，rmi,jetty等端口弱特征 |
| ysoserial                   | Tools    |                    | :heavy_check_mark:	    |                                       |

## C2
| 名字           | 版本        | 登录/连接          | 监听端口           | UDP            | TCP            | HTTP/S         | 计划中             | 备注 |
| -------------- | ----------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ---- |
| vshell         | 4.9.3~4.6.0 |                    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |                    |      |
| Cobalt Strike  |             | :white_check_mark: |                    |                    |                    | :white_check_mark: |                    |      |
| Metasploit     |             |                    |                    |                    | :white_check_mark: | :white_check_mark: |                    |      |
| Supershell     | 2.0.0       | :white_check_mark: | :white_check_mark: |                    |                    |                    |                    |      |
| Daybreak       |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| chisel         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Viper          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| sliver         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Havoc          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Iom            |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Villain        |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| VenomRA        |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| ShadowPad      |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Shad0w         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Remcos RAT     |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| QuasarRAT      |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Pupy-C2        |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| PoshC2         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| PlugX RAT      |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Orcus-RAT      |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Ninja          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Mythic         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Havoc          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Hak5 Cloud     |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Gh0st          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Empire         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| DeimosC2       |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| DcRAT          |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Covenant       |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| Brute Ratel C4 |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| BitRAT         |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| AsyncRAT       |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |
| manjusaka      |             |                    |                    |                    |                    |                    | :heavy_check_mark: |      |

## 将于20251月27推出正式版本2.0【优先内测】
提交平台或C2或服务等提交至issus，提交格式：ARL，Asset Reconnaissance Lighthouse，https://github.com/xxxx/ARL

三个工作日进行审核，通过则加入内测群。

### TODO：

- [ ] 搜索引擎js文件路径，以及ico图片hash搜索【手动导入，输入ico图标地址在线搜索】。
- [ ] 导出格式Excel报表。
- [ ] 对蜜罐识别进行识别调研，以及安全设备指纹。
- [ ] 针对其它资产测绘平台。
- [ ] 通过测绘得到IP资产，对IP资产进行端口扫描指纹识别。
- [ ] 钉钉企业微信漏洞扫描结果通知。
- [ ] 覆盖国内外C2。

## 📢 使用
#### 环境配置：

1. 如果需要进行漏洞扫描需要将`nuclei`加入环境变量。
2. 如需使用测绘功能请修改`config.ini`添加key。
3. python版本：`python3.9`。
4. 如果是mac或linux请下载对于的执行程序在plugin目录，并配置`config.ini`。
   1. [observer_ward](https://github.com/emo-crab/observer_ward)
   2. [nuclei](https://github.com/projectdiscovery/nuclei)
   3. [gogo](https://github.com/chainreactors/gogo)
   4. [tlsx](https://github.com/projectdiscovery/tlsx)
  
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


---------------------------------------------------------------------------------
>python39 main.py RTSCAN -h

.__       .  .         .
|  \ _.._.|_/ ._ . . _.| _ *
|__/(_][  |  \[ )(_|(_.|(/,|
    DarKnuclei v2.0 by RuoJi
    https://github.com/RuoJi6/DarKnuclei

usage: main.py RTSCAN [-h] [-f FILE] [-i IP] [-p GOGO_PORT] [-gt GOGO_THREAD] [-ev] [-t TAGS] [-fy FILE_YAML] [-all]
                      [-np PROXY]

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  扫描文件
  -i IP, --ip IP        扫描指定ip
  -p GOGO_PORT, --gogo_port GOGO_PORT
                        gogo扫描指定端口
  -gt GOGO_THREAD, --gogo_thread GOGO_THREAD
                        gogo线程，默认1000
  -ev, --gogo_poc       gogo自带漏洞验证
  -t TAGS, --tags TAGS  扫描指定的tags
  -fy FILE_YAML, --file_yaml FILE_YAML
                        扫描指定的yaml文件
  -all, --all_yaml      查看可扫描的yaml
  -np PROXY, --proxy PROXY
                        扫描代理【socks5,http】


---------------------------------------------------------------------------------
>python39 main.py RTSCAN -a

.__       .  .         .
|  \ _.._.|_/ ._ . . _.| _ *
|__/(_][  |  \[ )(_|(_.|(/,|
    DarKnuclei v2.0 by RuoJi
    https://github.com/RuoJi6/DarKnuclei

[+] Red Team Infrastructure Scan Template
|type            | name | tags
---------------------------------------------
|C2              | Cobalt Strike | Cobalt Strike,CS,cs,Fortra,C2
|C2              | Metasploit Framework HTTP/S | msf,Metasploit Framework,msf,Rapid7,http,https,C2
|C2              | Metasploit Framework TCP | msf,Metasploit Framework,msf,Rapid7,tcp,C2
|C2              | Supershell | Supershell,C2
|C2              | vshell | vshell,C2
|platform        | ARL | Asset Reconnaissance Lighthouse,ARL,arl,platform
|platform        | Acunetix | Acunetix,awvs,AWVS,platform
|platform        | BeEF | XSS,xss,beef,platform
|platform        | CyberEdge | CyberEdge,platform
|platform        | DBJ | DBJ,dbj,WgpSec,platform
|platform        | gophish | gophish,platform
|platform        | H | H,SiJiDo,h,platform
|platform        | LangSrcCurise | LangSrcCurise,platform
|platform        | Medusa | Medusa,mds,platform
|platform        | MemShellParty | MemShellParty,shell,java,JavaWeb,platform
|platform        | Nessus | Nessus,nessus,platform
|platform        | NextScan | NextScan,fr,platform
|platform        | NPS | NPS,nps,proxy,platform
|platform        | prismx | prismx,platform
|platform        | rengine | rengine,platform
|platform        | revsuit | revsuit,dnslog,platform
|platform        | Scope Sentry | Scope Sentry,platform
|platform        | SerializedPayloadGenerator | SerializedPayloadGenerator,payload,platform
|platform        | testnet | testnet，platform
|platform        | vulfocus | vulfocus,Vulhub,Vulapps,platform
|platform        | XSS platform | XSS,xss,platform
|tools           | JETTYSERVER | java,jndi,jettyserver,jetty,JETTYSERVER,tools
|tools           | JNDI-Injection-Exploit-LDAP | java,jndi,ldap,JNDI-Injection-Exploit-LDAP,tools
|tools           | JNDI-Injection-Exploit-Plus-LDAP | java,jndi,ldap,JNDI-Injection-Exploit-Plus-LDAP,tools
|tools           | JNDIMap-LDAP | java,jndi,ldap,JNDIMap-LDAP,JNDIMap,tools
|tools           | LDAPSERVER | java,jndi,ldap,LDAPSERVER,tools
|tools           | RMISERVER | java,jndi,rmi,RMISERVER,tools
|tools           | rogue-jndi-LDAP | java,jndi,ldap,rogue-jnd,rogue,Groovy,rogue-jnd-ldap,tools
```

## 关于/演示
关于 DarKnuclei，DarKnuclei专注于红蓝对抗一款工具，不仅可以扫描漏洞，快速打点，还可以扫描红队基础设施与服务，拥有高扩展的yaml格式指纹文件，方便自己编写红队基础设施指纹。
![image](https://github.com/user-attachments/assets/f585eabe-b85c-4350-838e-e3296d0c1e4a)
![image](https://github.com/user-attachments/assets/11579282-63eb-4fe3-823c-419673340ef1)
![image](https://github.com/user-attachments/assets/3018d5bc-f9be-4e1a-8059-7831d49078dc)



