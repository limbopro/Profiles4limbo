![Quantumult x for limbopro][1]
![Quantumult x for limbopro-newest][2]

⬆️ 新旧版本界面；

## Profiles4limbo
毒奶预配置文件（Quantumult X）懒人一键配置，在你进行下一步操作之前请耐心把本文档看完以免造成不必要的麻烦，包含但不限于有可能存在的报错及规避方法，如何删除 ♻️故障切换 策略组下的无用节点（删除该无用节点的同时务必新增2个以上节点才能进行保存）；

## 及时收讯与反馈交流（遇到问题如何解决）
0. ⚠️ 关于本预配置文件在使用过程中如有问题请务必优先参考本文档 具体操作 步骤部分以及 尾部的FAQ部分 进行解决，更多问题或建议请加入我们的电报群组；（FAQ存在的已知问题请勿重复提问）
1. 文末 FAQ / 附注部分将会为大家提供一些Quantumult X 进阶使用方法教程；
2. [TG 电报频道](https://t.me/limboprossr)；
3. [TG 电报群组](https://t.me/Adblock4limbo)；
4. [Twitter](https://twitter.com/limboprossr)；

# 说明

## 历史更新说明 

### 12.27.2020 更新说明

<details>
<summary>展开查看</summary>

Tiktok 最新版 v.18.2.1 可以解锁啦！记得备份啊笨蛋！个性化解锁参考 [如何使用Quantumult X解锁 TikTok 区域限制（免拔卡）](https://limbopro.xyz/archives/11773.html)
</details>

### 11.13.2020 更新说明

<details>
<summary>展开查看</summary>
更新了分流规则至神机规则最新库；
</details>

### 10.25.2020 更新说明

<details>
<summary>展开查看</summary>

1. 更新 预配置文件中分流规则至 **神机规则（更新中）**；
2. 更新 **本预配置文件所引用到的仓库**；
3. 新增毒奶去广告 [Rewrite] 跟 [filter]；参阅 https://t.me/limboprossr/1952 配置；可去除[奈菲影视](https://www.nfmovies.com/) /[低端影视](https://ddrk.me/)/[Jable.tv](https://jable.tv/)/[netflav](https://netflav.com)/[片库网](https://m.pianku.me/)/[嘀哩哩网站](https://www.dililitv.com/) 上的广告（内页广告以及片头广告）。
</details>


## 毒奶预配置文件说明
<details>
<summary>展开查看</summary>
0. 利用 Quantumult X 自带的 [配置文件] - [下载] 功能对 Quantumult X 各个模块进行预配置；
1. 包括但不限于[分流]/[重写]；
2. 利用 NobyDa 贡献的脚本解锁🔓各项事务，VSCO，~~Termius~~，网易蜗牛读书会员等；
3. **Surge/Clash** 用户可使用由毒奶提供的 订阅转换 API，亦能获得相同的效果；https://limbopro.xyz/archives/subconverter.html
</details>

## 本预配置文件所引用到的仓库说明

<details>
<summary>展开查看</summary>

0. 在此毒奶对大家的付出表示感谢
1. [NobyDa](https://github.com/NobyDa/Script/tree/master) 脚本仓库（*如删库可替换 NobyDa 为 limbopro，其他同理）
2. [NobyDa-AD](https://github.com/NobyDa/ND-AD) 野比去广告分流；（10w+）
2. [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master) 神机规则（停止更新）
3. [DivineEngine](https://github.com/DivineEngine/Profiles/tree/master) 神机规则（更新中），包含 `YouTube APP`去广告/`Tiktok` 解锁的重写，请自行查看；
3. [limbopro](https://github.com/limbopro/Profiles/tree/master/limbopro) 机场专线
4. [Qure](https://github.com/Koolson/Qure/tree/master/IconSet) 开源图标
5. [chavyleung](https://github.com/chavyleung/scripts) 签到脚本

</details>

## 关于策略组及分流的说明

<details>
  <summary>展开查看</summary>

⚠️ 本预配置文件默认8个策略，如上方**预览图**中所示；按以下 **具体操作** 操作完毕后即可在 Quantumult X 主界面看见。

- **故障切换**：该策略自动会自动从下到下检测该策略下所选用节点的可用情况，然后自动切换到可用节点（surge 会切换选中最低延迟节点）；；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- **社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram/Telegram 等，**流量消耗小，但需要稳定**；
- **苹果服务**：苹果服务相关分流规则；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；
- **广告拦截**：默认选择 `Reject`，广告拦截可能会造成某些错误🙅，届时 将 **广告拦截** 的 **策略偏好** 修改为 PROXY 或 Direct 即可；
- **Final**： 排除以上已知的分流规则的其他未知；

</details>

# 具体操作（如何使用QX懒人配置文件）

📢 如果你此前已经开始使用 Quantumultx 并已配置多个机场订阅，则可参考 本文档的 **FAQ** 部分说明进行备份机场订阅； 

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
;limbopro.xyz
;02.19.2021   
;https://t.me/limboprossr 关注更新
;https://t.me/Adblock4limbo 群组反馈与讨论交流

[general]

#解析器作者 @XIAO_KOP 
resource_parser_url=https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/resource-parser.js
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/limbopro/QuantumultX/master/Scripts/IP_API.js


[dns]
server=223.5.5.5
server=114.114.114.114
server=119.29.29.29
server=8.8.8.8


[policy]
available=♻️ 故障切换, 无用节点1, 无用节点2, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Available.png
static=✈️ 机场专线, 🎥 其他国外流媒体, ♻️ 故障切换, PROXY, DIRECT, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/rocket.png
static=📲 社交媒体, 🎥 其他国外流媒体,  ♻️ 故障切换, PROXY, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Telegram.png
static=🍎 苹果服务, DIRECT, 🎥 其他国外流媒体, ♻️ 故障切换, PROXY, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Apple.png
static=🎥 Netflix, 🎥 其他国外流媒体, PROXY, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Netflix_Letter.png
static=🎥 其他国外流媒体, ♻️ 故障切换, PROXY, img-url=https://raw.githubusercontent.com/limbopro/Qure/master/IconSet/GlobalMedia.png
static=🛑 广告拦截, REJECT, PROXY, DIRECT, img-url=https://raw.githubusercontent.com/limbopro/Qure/master/IconSet/Advertising.png
static=🐟 Final, 🎥 其他国外流媒体, ♻️ 故障切换, PROXY, DIRECT, 🛑 广告拦截, img-url=https://raw.githubusercontent.com/limbopro/Zure/master/IconSet/Final.png


[server_remote]
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/unlesssub.txt, tag=无用节点（❌请不要动它）, enabled=true
# 无用订阅（请勿删除）

[filter_remote]
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/airports.list, tag=机场专线, force-policy=✈️ 机场专线, enabled=true
https://limbopro.xyz/Adblock4limbo.list, tag=毒奶特供, force-policy=🛑 广告拦截, enabled=true
#https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRule.list, tag=野比去广告（稳定版）, force-policy=🛑 广告拦截, enabled=false
#https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRuleTest.list, tag=野比去广告（测试版）, force-policy=🛑 广告拦截, enabled=false
https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block.txt, tag=野比(4W+), force-policy=🛑 广告拦截, enabled=true
https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block_Plus.txt, tag=野比(6W+), force-policy=🛑 广告拦截, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Video/Netflix.list, tag=Netflix, force-policy=🎥 Netflix, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Streaming.list, tag=其他国外流媒体, force-policy=🎥 其他国外流媒体, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list, tag=社交媒体, force-policy=📲 社交媒体, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/Apple.list, tag=苹果服务, force-policy=🍎 苹果服务, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/China.list, tag=大陆媒体, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/ChinaIP.list, tag=GEOIP(CN), enabled=true

[rewrite_remote]
https://limbopro.xyz/Adblock4limbo.conf, tag=毒奶特供, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/YouTubeAds.conf, tag=DivineEngine (Youtube AdsBlock), enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/Advertising.conf, tag=DivineEngine (Advertising), enabled=true
#https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Rewrite.conf, tag=ConnersHua （DivineEngine Rewrite）, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Rewrite_lhie1.conf, tag=NoByDa（lhie1 Rewrite）, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Js.conf, tag=NoByDa（NoByDa Rewrite）, enabled=true
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/tiktok.conf, tag=TikTok ublock, enabled=true

[server_local]


[filter_local]
geoip, cn, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 224.0.0.0/24, direct
final, 🐟 Final


[rewrite_local]

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

> 1. 订阅你的机场节点；（📢如果对Quantumult X 操作不熟悉，请不要删除名为“无用节点”的节点订阅链接；）
> 2. 一切就绪后进入 QuantumultX 主界面，长按各个 **策略组对应的图标或策略组名字**（如`♻️故障切换`/`🛬机场专线`..）就可以为该策略组添加+/或删除-不需要的节点了；
> 3. 注意！📢若策略下如`故障切换`，出现有红色感叹号❕标注的节点务必删除，并添加2个以上节点后保持；

## 第四步 为机场专线分流选择策略偏好
> 1. 进入QuantumultX，在主界面找到名为`🛬机场专线`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
> 2. 如果你的机场订阅仍然无法更新，在主界面找到名为`🐟Final`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
> 3. 更多疑问请查看  **FAQ** 部分；

# 出现错误及解决 Faq（已知问题及其解决方法）

## 未知错误 - 未知策略或节点

>> ⚠️  未知错误 - 未知策略或节点
>> ✅ 解决办法：删除失效的节点；

![未知错误 - 未知策略或节点解决办法.png][5]

## Youtube会员

>> ⚠️ Youtube app 出现黑屏或无法观看问题；
>> ✅ 解决办法：1.如果你是YouTube 会员，则应该进 `重写`- `引用` - 找到并禁用 `DivineEngine (Youtube AdsBlock)`

## 附注
### 网络活动
![QuantumultX - 网络活动.png][4]

>在反馈问题前，请多看看 **网络活动日志模块**（QuantumultX 主界面 **橘红色** 的日记本标识，里面📝了你的各个网络请求）；多熟悉一下 QuantumultX 操作界面，可能帮助你解决很多常见问题。

> 1. **Tiktok 免拔卡解锁**：https://limbopro.xyz/archives/3629.html
> 2. **加入毒奶去广告计划**：https://limbopro.xyz/archives/12904.html
> 3. **解析器过滤节点以及regex**（**新**）**参数的用法**：https://limbopro.xyz/archives/11131.html

### 备份你的机场订阅链接🔗
> 1. 进入 QuantumultX ，点击右下角 [三菱按钮]
> 2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
> 3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
> 4. 届时 恢复时 重新在 [server_remote] 下方 粘贴即可

### 进阶玩法和深入理解
QuantumultX 使用教程：策略组&分流规则&自定义图标&过滤节点的进阶玩法
https://limbopro.xyz/archives/3846.html

Quantumult X 资源解析器 - 以及正则表达式，无需API转换即可在本地过滤节点
https://limbopro.xyz/archives/11131.html#%E4%BD%BF%E7%94%A8QuantumultX_%E5%86%85%E7%BD%AE_regex_%E5%8F%82%E6%95%B0%E4%BB%A5%E5%8F%8A%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F%E7%AD%9B%E9%80%89%E8%8A%82%E7%82%B9%E5%B9%B6%E7%94%9F%E6%88%90%E7%AD%96%E7%95%A5%E7%BB%84

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


