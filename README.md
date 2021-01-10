![Quantumult x for limbopro][1]
![Quantumult x for limbopro-newest][2]

⬆️ 新旧版本界面；

# Profiles4limbo
毒奶预配置文件（Quantumult X）懒人一键配置；

# 及时收讯与反馈交流
1. [TG 电报频道](https://t.me/limboprossr)；
2. [TG 电报群组](https://t.me/Adblock4limbo)；
3. [Twitter](https://twitter.com/limboprossr)；

# 说明

## 历史更新说明 

### 12.27.2020 更新说明

Tiktok 最新版 v.18.2.1 可以解锁啦！记得备份啊笨蛋！个性化解锁参考 [如何使用Quantumult X解锁 TikTok 区域限制（免拔卡）](https://limbopro.xyz/archives/11773.html)

### 11.13.2020 更新说明

更新了分流规则至神机规则最新库；

### 10.25.2020 更新说明

<details>
<summary>展开查看</summary>

1. 更新 预配置文件中分流规则至 **神机规则（更新中）**；
2. 更新 **本预配置文件所引用到的仓库**；
3. 新增毒奶去广告 [Rewrite] 跟 [filter]；参阅 https://t.me/limboprossr/1952 配置；可去除[奈菲影视](https://www.nfmovies.com/) /[低端影视](https://ddrk.me/)/[Jable.tv](https://jable.tv/)/[netflav](https://netflav.com)/[片库网](https://m.pianku.me/)/[嘀哩哩网站](https://www.dililitv.com/) 上的广告（内页广告以及片头广告）。
</details>


## 毒奶预配置文件说明

0. 利用 Quantumult X 自带的 [配置文件] - [下载] 功能对 Quantumult X 各个模块进行预配置；
1. 包括但不限于[分流]/[重写]；
2. 利用 NobyDa 贡献的脚本解锁🔓各项事务，VSCO，~~Termius~~，网易蜗牛读书会员等；
3. **Surge/Clash** 用户可使用由毒奶提供的 订阅转换 API，亦能获得相同的效果；https://limbopro.xyz/archives/subconverter.html

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

## 关于策略及分流的说明

<details>
  <summary>展开查看</summary>

⚠️ 本预配置文件默认8个策略，如上方**预览图**中所示；按以下 **具体操作** 操作完毕后即可在 Quantumult X 主界面看见。

- **故障切换**：该策略组自动检测组内节点可用情况（surge 会切换选中最低延迟节点）；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- **社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram/Telegram 等，**流量消耗小，但需要稳定**；
- **苹果服务**：苹果服务相关分流规则；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；
- **广告拦截**：默认选择 `Reject`，广告拦截可能会造成某些错误🙅，届时 将 **广告拦截** 的 **策略偏好** 修改为 PROXY 或 Direct 即可；
- **Final**： 排除以上已知的分流规则的其他未知；

</details>

# 具体操作

## 第一步 下载毒奶预配置文件

1. 复制 https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf 预配置文件链接；
2. 进入 QuantumultX ，点击右下角 [三菱按钮]
3. 找到 [配置文件] 模块下的 [下载] 点击
4. 粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
5. 确认，届时 QuantumultX 已添加 8个策略

## 第二步 生成并配置证书
0. 如果再此之前已经生成并信任证书则 **生成并配置证书**这一步可选择忽略；
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [MitM] 模块 - 生成并配置证书📄 

- 进入QuantumultX，点击页面右下角三菱`按钮`，找到`MinM`模块，点击`生成证书`，提示生成成功，点击`安装证书`此时会跳转至` Safari`，提示`此网站...下载一个配置描述文件。您要允许吗？`，点击`允许`，网页提示`已下载描述文件`；
- 进入 iOS 系统`设置`-` 通用`-`描述文件`-`已下载的描述文件`-选中，并安装，输入密码...完成描述文件安装；
- 进入 iOS 系统`设置`-` 通用`-`关于本机`-`证书信任设置`-`针对根证书启用完全信任`-选中刚刚安装的并启用即可；

3. 找到 [重写] 模块 - 开启按钮 🔘
4. 找到 [MitM] 模块 - 开启按钮 🔘

## 第三步 订阅并为各个策略添加或删除节点
1. 机场怎么订阅就不说了
2. 进入 QuantumultX 主界面，可长按各个 **策略组对应图标** 以 为该策略添加/减少节点；
3. 有红色感叹号❕标注的节点务必删除；

# Faq 
在反馈问题前，请多看看 **网络活动日志模块**（QuantumultX 主界面 **橘红色** 的日记本标识，里面📝了你的各个网络请求）；多熟悉一下 QuantumultX 操作界面，可能帮助你解决很多常见问题。

 1. **Tiktok 免拔卡解锁**：https://limbopro.xyz/archives/3629.html
 2. **加入毒奶去广告计划**：https://limbopro.xyz/archives/12904.html
 3. **解析器过滤节点以及regex**（**新**）**参数的用法**：https://limbopro.xyz/archives/11131.html

## 备份你的机场订阅链接🔗
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
4. 届时 恢复时 重新再 [server_remote] 下方 粘贴即可

## 使用毒奶预配置文件后的一些检查
1. 如果出现错误提示，不要慌
2. 进入 QuantumultX 主界面 - 各个图标点一下 看一下
3. 熟悉一下

## Faq 

1.如果你是YouTube 会员，则应该进 `重写`- `引用` - 找到并禁用 `DivineEngine (Youtube AdsBlock)`

## 及时更新
*保持更新。

1. [分流] - [引用] 更新
2. [重写] - [引用] 更新

# 最后 BTW
因为这个配置文件也是我自用的，会保持更新，但一般无太大问题不建议大家每次跟随更新。

## 进阶玩法
https://limbopro.xyz/archives/3846.html

## 关注频道
https://t.me/limboprossr

[1]: https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/QuantumultX4limbopro.PNG
[2]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Quantumult%20X%20v1.0.18.PNG

