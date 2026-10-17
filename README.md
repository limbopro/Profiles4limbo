![Quantumult x for limbopro-newest][2]

⬆️ 新旧版本界面；

## Profiles4limbo
毒奶预配置文件（Quantumult X）懒人一键配置，在你进行下一步操作之前请耐心把本文档看完以免造成不必要的麻烦，包含但不限于有可能存在的报错及规避方法，如何删除 ♻️故障切换 策略组下的无用节点（删除该无用节点的同时务必新增2个以上节点才能进行保存）；  

### Mihomo 内核 / Clash系列 订阅转换工具🔧（可自定义基础配置）  

![FlClash for Mac.jpg](https://limbopro.com/usr/uploads/2026/09/2769266601.jpg)  
![FlClash for Android / iOS Clash MI.jpg](https://limbopro.com/usr/uploads/2026/09/2867279337.jpg)  


**地址**：https://limbopro.com/tools/2yaml  
Mihomo, Clash, Clash Meta, 节点合并, 订阅转换, 订阅合并, 节点追加, YAML解析, KV托管；支持 YAML 配置文件自定义、多机场订阅节点去重追加、跨域拉取与一键生成托管订阅链接；  

自定义基础配置（自定义分流如X以及电报和油管ChatGPT等等/策略组/DNS/==），想要什么自己加？了解更多：https://limbopro.com/archives/36088.html  

### Surge 懒人配置（without api）

如果你是 Surge 用户，但又不想使用 订阅转换api，可以试试这个 https://github.com/limbopro/Profiles4limbo/tree/main/Surge ；

## 及时收讯与反馈交流（遇到问题如何解决）
0. ⚠️ 关于本预配置文件在使用过程中如有问题请务必优先参考本文档 具体操作 步骤部分以及 尾部的FAQ部分 进行解决，更多问题或建议请加入我们的电报群组；（FAQ存在的已知问题请勿重复提问）
1. 文末 FAQ / 附注部分将会为大家提供一些Quantumult X 进阶使用方法教程  
2. 直接联系博主电报：http://t.me/limboprobot / Gmail： service.limbopro.com@gmail.com  
3. 关注TG 电报频道：https://t.me/limboprossr  
4. 加入TG 电报群组：https://t.me/Adblock4limbo  
5. 关注 Twitter https://twitter.com/limboprossr


## 毒奶预配置文件说明

## 本预配置文件所引用到的仓库说明

0. 在此毒奶对大家的付出表示感谢
1. [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script) 分流规则/重写/去广告（持续更新，涵盖时下流行的大多数海外App/大陆App分流规则，适用于 Surge/QuantumultX/Loon/Clash/Shadowrocket...）
2. [NobyDa](https://github.com/NobyDa/Script/tree/master) 脚本仓库（*如删库可替换 NobyDa 为 limbopro，其他同理）
3. [NobyDa-AD](https://github.com/NobyDa/ND-AD) 野比去广告分流；（10w+） 停止更新
2. [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master) 神机规则（停止更新）
3. [DivineEngine](https://github.com/DivineEngine/Profiles/tree/master) 神机规则（停止更新），包含 `YouTube APP`去广告/`Tiktok` 解锁的重写，请自行查看；
3. [limbopro](https://github.com/limbopro/Profiles/tree/master/limbopro) 机场专线
4. [Qure](https://github.com/Koolson/Qure/tree/master/IconSet) 开源图标
5. [chavyleung](https://github.com/chavyleung/scripts) 签到脚本


## 关于策略组及分流的说明

⚠️ 本预配置文件默认10个策略，如上方**预览图**中所示；按以下 **具体操作** 操作完毕后即可在 Quantumult X 主界面看见。

- **故障切换**：该策略自动会自动从下到下检测该策略下所选用节点的可用情况，然后自动切换到可用节点（surge 会切换选中最低延迟节点）；；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- ~~**社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram/Telegram 等，**流量消耗小，但需要稳定**；~~
- **苹果服务**：苹果服务相关分流规则；
- **Ai Platforms**：：chatGPT/OpenAI/Google Bard/Claude2...分流规则（2023热门）；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **Disney+**：鉴于大家喜欢看 Disney+（较少数，英文生肉较多）；
- **Tiktok**：鉴于大家喜欢看 Tiktok（嘿嘿嘿）；大家可以刷[网页版TikTok](https://www.tiktok.com/foryou)哦；
- ~~**其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；~~
- **广告拦截**：默认选择 `Reject`，广告拦截可能会造成某些错误🙅，届时 将 **广告拦截** 的 **策略偏好** 修改为 PROXY 或 Direct 即可；
- **Final**： 排除以上已知的分流规则的其他未知；

> 如果大家想为其他App配置分流，如 YouTube/Twitter/Telegram... 可在 blackmatrix7 的Github 仓库尝试自行查找，引用；

**大陆/海外App分流规则整理来自blackmatrix7**：https://github.com/blackmatrix7/ios_rule_script （持续更新，涵盖时下流行的大多数海外App/大陆App分流规则，适用于 Surge/QuantumultX/Loon/Clash/Shadowrocket...）
**大陆/海外App分流规则整理来自神机（花姐）规则**：https://github.com/DivineEngine/Profiles/tree/master （已停更）
~~**去广告规则来自NobyDa（野比）规则**：https://github.com/NobyDa/~~
**机场专线规则来自博主（毒奶）**：https://github.com/limbopro/Profiles4limbo

# 具体操作（如何使用QX懒人配置文件）

📢 如果你此前已经开始使用 Quantumultx 并已配置**多个机场订阅**，则可参考 本文档的 **FAQ** 的相关说明对**机场订阅**进行**备份**； 

## 第一步 下载毒奶预配置文件
> 1. 复制 https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf 预配置文件链接（大家也可以在浏览器内打开该预配置文件链接以查看具体配置详情，好做进一步的理解）；
> 2. 进入 QuantumultX ，点击右下角 [三菱按钮/设置按钮]
> 3. 找到 [配置文件] 模块下的 [下载] 点击
> 4. 粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
> 5. 确认，届时 QuantumultX 已添加 8个策略

>> ⚠️ 如下载毒奶预配置文件时 app 出现 `无效的自变量` 提示，请复制 `https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf`  链接并在你的手机浏览器上打开，如不能打开则说明当前手机环境已被墙需要代理才能下载本预配置文件；

>> ✅ 解决办法：1.复制以下内容（ 其实就是 full.conf 预配置文件内的内容 ）；2.打开 Quantumult X ，点击 右下角 三菱按钮🔘，往下滑，找到 `配置文件`，点击`编辑`，长按任意位置，出现`选择/全选/粘贴`按钮，点击`全选`，然后点击`粘贴`；3.点击右上角完成按钮保存；

```
#从这里开始复制 包括开头这个#井号
;预配置作者
;毒奶博主
;limbopro.com
;09.11.2024 更新   
;https://t.me/limboprossr 关注更新
;https://t.me/Adblock4limbo 群组反馈与讨论交流

[general]

#解析器作者 @XIAO_KOP 
resource_parser_url=https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/resource-parser.js

#IP_API 改自 @XIAO_KOP
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/limbopro/QuantumultX/master/Scripts/IP_API.js


[dns]
;no-ipv6
no-system
server=223.5.5.5
server=114.114.114.114
server=119.29.29.29
server=[2400:3200:baba::1]
server=[2400:3200::1]

[policy]
static=🛑 广告拦截, REJECT, PROXY, DIRECT, img-url=https://raw.githubusercontent.com/limbopro/Qure/master/IconSet/Advertising.png
available=♻️ 故障切换, 无用节点1, 无用节点2, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Available.png
static=✈️ 机场专线, PROXY, DIRECT, ♻️ 故障切换, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/rocket.png
static=🍎 苹果服务, DIRECT, PROXY, ♻️ 故障切换, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Apple.png
static=🤖 AI Platforms, PROXY, DIRECT, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/AI%20Platforms.png
static=🎥 Netflix, PROXY, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Netflix_Letter.png
static=🐭 Disney+, PROXY, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Disney+.png
static=🎵 TikTok, PROXY, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/TikTok.png
static=🐟 Final, PROXY, ♻️ 故障切换, DIRECT, 🛑 广告拦截, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Final.png

[server_remote]


[filter_remote]
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/airports.list, tag=机场专线, force-policy=✈️ 机场专线, enabled=true
https://limbopro.com/Adblock4limbo.list, tag=毒奶特供(去网页广告计划), force-policy=🛑 广告拦截, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Netflix/Netflix.list, tag=🎥 Netflix, force-policy=🎥 Netflix, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Disney/Disney.list, tag=🐭 Disney+, force-policy=🐭 Disney+, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/TikTok/TikTok.list,tag=🎵 TikTok, force-policy=🎵 TikTok, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Apple/Apple.list, tag=🍎 苹果服务, force-policy=🍎 苹果服务, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/OpenAI/OpenAI.list, tag=🤖 AI Platforms, force-policy=🤖 AI Platforms, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/BardAI/BardAI.list, tag=🤖 AI Platforms, force-policy=🤖 AI Platforms, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Claude/Claude.list, tag=🤖 AI Platforms, force-policy=🤖 AI Platforms, enabled=true
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/AI_Platforms_qx.list, tag=🤖 AI Platforms, force-policy=🤖 AI Platforms, enabled=true

[rewrite_remote]
https://limbopro.com/Adblock4limbo.conf, tag=毒奶特供(去网页广告计划), enabled=true
https://raw.githubusercontent.com/Peng-YM/Sub-Store/master/config/QX.snippet, tag=Sub-store(高级订阅管理器), enabled=true

[server_local]
shadowsocks=example.com:80, method=aes-128-gcm, password=pwd, obfs=ws, fast-open=false, tag=无用节点1
shadowsocks=example.com:80, method=aes-128-gcm, password=pwd, obfs=ws, fast-open=false, tag=无用节点2

[filter_local]
geoip, cn, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 224.0.0.0/24, direct
final, 🐟 Final

[rewrite_local]

[task_local]

[http_backend]

[mitm]
#到这里结束
```

>> ⚠️ Quantumult X 最新版本中在你还没有**订阅机场节点**（即第三步完成）前，APP主界面可能不会直接出现这8个策略；（02.19.2021）

>> ✅ 解决办法：在第三步完成后会自行出现；

## 第二步 生成并配置证书
> 0. 如果再此之前已经生成并信任证书则 **生成并配置证书**这一步可选择忽略；
> 1. 进入 QuantumultX ，点击右下角 [三菱按钮]
> 2. 找到 [MitM] 模块 - 生成并配置证书📄 

>> - 进入QuantumultX，点击页面右下角三菱`按钮`，找到`MinM`模块，点击`生成证书`，提示生成成功，点击`安装证书`此时会跳转至` Safari`，提示`此网站...下载一个配置描述文件。您要允许吗？`，点击`允许`，网页提示`已下载描述文件`；
>> - 进入 iOS 系统`设置`-` 通用`-`描述文件`-`已下载的描述文件`-选中，并安装，输入密码...完成描述文件安装；
>> - 进入 iOS 系统`设置`-` 通用`-`关于本机`-`证书信任设置`-`针对根证书启用完全信任`-选中刚刚安装的并启用即可；

> 3. 找到 [重写] 模块 - 开启按钮 🔘
> 4. 找到 [MitM] 模块 - 开启按钮 🔘

>> ⚠️ `点击安装证书`后不是在 `Safari` 打开，而是在其他浏览器打开，导致证书无法安装；

>> ✅ 解决办法：打开 iPhone `设置` app - 搜索或下滑找到 `Safari浏览器` 点击 ， -找到 `默认浏览器App` ，选择 `Safari浏览器`， 然后重试第二步即可。  

## 第三步 订阅机场节点并为各个策略添加或删除节点

![Quantumult X PROXY/POLICY/延迟/节点可用性测试/操作界面认识/名称编辑/背景编辑.png][3]
![Quantumult X 网络活动.png][119]

> 1. 订阅你的机场节点；（📢如果对Quantumult X 操作不熟悉，请不要删除名为“无用节点”的节点订阅链接；）
> 2. 一切就绪后进入 QuantumultX 主界面，长按各个 **策略组对应的图标或策略组名字**（如`♻️故障切换`/`🛬机场专线`..）就可以为该策略组添加+/或删除-不需要的节点了；
> 3. 注意！📢若策略下如`故障切换`，出现有红色感叹号❕标注的节点务必删除，并添加2个以上节点后保持；

## 第四步 为机场专线分流选择策略偏好
> 1. 进入QuantumultX，在主界面找到名为`🛬机场专线`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
> 2. 如果你的机场订阅仍然无法更新，在主界面找到名为`🐟Final`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
> 3. 更多疑问请查看  **FAQ** 部分；

## 设置策略组图标颜色

![QuantumultX_icon_backgroundcolor.png][11]

根据个人喜好修改**图标/背景**，以及给**策略**组排序；

# 出现错误及解决 Faq（已知问题及其解决方法）

## 分流问题

问:“你好请问一下问什么我的分流规则没没起作用 小红书依旧走代理，tiktok 设置了专门的节点但看活动还是用的通用代理？”

问:“毒奶老师，我在看毒奶自用，懒人配置文件（Quantumult X）这个文档。我一步一步按照文档操作下来全都添加成功了，但是我的quan的网络活动还是显示全局，好像没有根据proxy分流，可以帮帮我吗”

答:进入qx，**长按右下角按钮**(一直在顺时针转的那个按钮)，然后选择**规则分流**(点选含有**三种颜色**那个，代表按规则分流。全是黄色代表全部网络活动走直链。全是蓝色代表全部网络活动走代理)。

## 未知错误 - 未知策略或节点

>> ⚠️  未知错误 - 未知策略或节点
>> ✅ 解决办法：删除失效的节点；

![未知错误 - 未知策略或节点解决办法.png][5]

## Youtube会员

>> ⚠️ Youtube app 出现黑屏或无法观看问题；
>> ✅ 解决办法：1.如果你是YouTube 会员，则应该进 `重写`- `引用` - 找到并禁用 `DivineEngine (Youtube AdsBlock)`

## 附注


blackmatrix7 分流/重写项目仓库地址：https://github.com/blackmatrix7/ios_rule_script/tree/master （目前全网更新较为勤奋，且包含App最为齐全的分流...OpenAI/ChatGPT分流..） 本 QuantumultX 懒人配置目前仅涵盖较少部分常用海外App分流规则，大家如需可进行查阅仓库，并在 Quantumult X 引用；

神机规则分流项目仓库地址：https://github.com/DivineEngine/Profiles/tree/master (已停更8个月)

### 网络活动
![QuantumultX - 网络活动.png][4]

>在反馈问题前，请多看看 **网络活动日志模块**（QuantumultX 主界面 **橘红色** 的日记本标识，里面📝了你的各个网络请求）；多熟悉一下 QuantumultX 操作界面，可能帮助你解决很多常见问题。

### 其他解锁玩法

> 1. **Tiktok 免拔卡解锁**：https://limbopro.com/archives/3629.html
> 2. **加入毒奶去广告计划**：https://limbopro.com/archives/12904.html
> 3. **VSCO 会员VIP解锁破解**：QX - 重写 - 引用：https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/vsco_crack.conf
> 4. **解析器过滤节点以及regex**（**新**）**参数的用法**：https://limbopro.com/archives/11131.html

### 备份你的机场订阅链接🔗
> 1. 进入 QuantumultX ，点击右下角 [三菱按钮]
> 2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
> 3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
> 4. 届时 恢复时 重新在 [server_remote] 下方 粘贴即可

### 进阶玩法和深入理解
QuantumultX 使用教程：策略组&分流规则&自定义图标&过滤节点的进阶玩法
https://limbopro.com/archives/3846.html

Quantumult X 资源解析器 - 以及正则表达式，无需API转换即可在本地过滤节点
https://limbopro.com/archives/11131.html#%E4%BD%BF%E7%94%A8QuantumultX_%E5%86%85%E7%BD%AE_regex_%E5%8F%82%E6%95%B0%E4%BB%A5%E5%8F%8A%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F%E7%AD%9B%E9%80%89%E8%8A%82%E7%82%B9%E5%B9%B6%E7%94%9F%E6%88%90%E7%AD%96%E7%95%A5%E7%BB%84

## 及时更新
*保持更新。

1. [分流] - [引用] 更新
2. [重写] - [引用] 更新

# 最后 BTW
因为这个配置文件也是我自用的，会保持更新，但一般无太大问题不建议大家每次跟随更新。

## 关注频道
https://t.me/limboprossr

[1]: https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/QuantumultX4limbopro.PNG
[2]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Quantumult%20X%20v1.0.18.PNG
[3]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Quantumult%20X%20%E4%B8%BB%E9%A1%B5%E4%BB%8B%E7%BB%8D.png
[4]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/%E6%97%A5%E5%BF%97.png
[5]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/%E2%99%BB%EF%B8%8F%20%E6%95%85%E9%9A%9C%E5%88%87%E6%8D%A2.png
[11]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/QuantumultX_icon_backgroundcolor.png
[119]: https://limbopro.com/usr/uploads/2021/02/753438643.png
