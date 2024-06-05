## 准备工作

0. 了解 Surge 中文手册：https://surge.mitsea.com/policy
1. 了解Sub-Store 高级订阅管理工具：https://limbopro.com/archives/Sub-Store.html ；
2. 从你的机场找到 Surge 托管配置链接，复制到备忘录；

## 1.下载配置文件（预配置分流、策略组）

```
https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Surge/Surge4limbo.conf
```

1.复制上述链接，即懒人配置文件对应，进入 Surge 主界面，点击左上角配置切换按钮； 

2.找到**导入**，点击**从URL下载配置**，粘贴刚刚复制的配置文件链接🔗；

## 2.配置 Surge.list（订阅你的机场）

1.下载后配置文件后 1.进入主界面 - 出站模式 - 选择规则模式 - 点击进入代理服务器；

2.分别找到如下策略组，♻️故障切换、🐟 final、Netflix；滑至底部，找到**外部代理列表**，粘贴你的 **surge.list**（即你的机场提供的Surge 托管配置链接；?如粘贴后保存失败，请参阅FAQ Sub-Store 高级订阅管理器，就可以把你机场提供的订阅转换为Surge支持的格式；）。

3.P.S. 如何**新建策略组/新建分流**，以及**策略组**之间互相嵌套，**分流嵌套策略**？可参考本文末尾 **小知识**处；

4.配置证书📄：

> 4.1. 进入 Surge - **首页** - 点击 **修改** ，**配置根证书**，**生成新的 CA 证书**，生成后，点击**安装证书**，此时会跳转至** Safari**，提示**此网站...下载一个配置描述文件。您要允许吗？**，点击**允许**，网页提示**已下载描述文件**；

> 4.2. 进入 iOS 系统 **设置** - **通用** - **描述文件** - **已下载的描述文件** -选中，并安装，输入密码...完成描述文件安装；

> 4.3. 进入 iOS 系统**设置** - **通用** - **关于本机** - **证书信任设置**-**针对根证书启用完全信任**-选中刚刚安装的并启用即可；

> 4.4. 进入 Surge - **首页** - 点击 **修改** ，开启 MitM/Rewrite/脚本 三个功能；

### FAQ 如何获得机场订阅的Surge.list?（订阅转换API的使用）

这里为方便 将 Surge node list 简称为 Surge.list，即 适用于 Surge 的节点列表；

如果机场不直接提供，或可使用订阅转换API：https://limbopro.com/archives/subconverter.html ； 也可以使用 Sub-Store 高级订阅管理器：https://limbopro.com/archives/Sub-Store.html ；如 Sub-Store 无法配置使用，请先使用由 毒奶博客 提供的订阅转换工具 进行获取 Surge node list，之后 再配置 Sub-Store（因为配置 Sub-store 需要使用到代理）；

## 4.安装模块（Tiktok解锁、YouTubeApp去广告、毒奶去网页广告计划）

### Sub-Store 高级订阅管理工具

```
https://raw.githubusercontent.com/Peng-YM/Sub-Store/master/config/Surge.sgmodule
```

### YoutubeApp去广告

YoutubeApp去广告 重写** （由 [神机规则制作人-花姐](https://github.com/DivineEngine/Profiles/tree/master) 维护）

```
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Module/Block/YouTubeAds.sgmodule
```

### Tiktok解锁重写

Tiktok解锁重写** (由 [Tartarus2014](https://github.com/Tartarus2014/Surge-Script/tree/master/Unlock) 维护)

```
https://raw.githubusercontent.com/Tartarus2014/Surge-Script/master/Unlock/TikTokUS.sgmodule
```

### 毒奶去网页广告计划

毒奶去网页广告计划** (由 [毒奶博主](https://limbopro.com/archives/12904.html) 维护)

```
https://limbopro.com/Adblock4limbo.sgmodule
```

1.依次复制 上述模块的链接🔗，进入 Surge 主界面，下滑，找到**模块**项目，点击**模块**按钮；

2.**安装的模块**，点击**安装新模块**；

3.粘贴刚刚复制的模块链接，点击**好**，下滑，点击**安装**；

4.任何时候，都可以通过**左滑模块名称**进行模块内容更新；

##小知识

### 如何新建策略组以及策略组互相嵌套

1.进入主界面 - **出站模式** - 选择**规则模式** - 点击进入**代理服务器** ，这里有已经建立好的各个策略组（你可以点击它的名称进去进一步设置）；

2.或**继续往下滑**，找到 **新建策略组** 按钮，点击它；然后设置好策略组的**组名称**，**组类型**，你可以看到 **包含的策略**，它的下方目前是 空的，你还可以看到 **可用的策略**，你可以选择拖拽这些 **可用的策略** 到 **包含的策略** 下方，这样就完成了一个基本的策略组嵌套；好了，往下滑，你会看到 **外部代理列表**，很熟悉吧，选择 **开启**，粘贴 你的 Surge.list；

3.Surge/QuantumultX/Clash 的策略组都是如此嵌套在一起的，可以是单独的策略，如 DIRECT/REJECT/PROXY，我们命名一个策略名称为B，并把一个机场订阅的节点放在下面，就得到了一个新的策略，你可在策略A下嵌套B。

3.关于策略知识扩展可以**参阅 Surge 中文手册**：https://surge.mitsea.com/policy

### 如何新建分流以及分流匹配策略

1.进入主界面 - **出站模式** - 选择**规则模式** - 点击进入 **代理规则**，这里有已经建立好好几个分流，你可以分别点击进去**查看它们的设置细节**；

2.**尝试新建分流**：点击  **+ 新增** 按钮 - 然后有三个选项，你可以分别点击看看；现在，我们点击 **增加新规则** - **规则类型**选 DOMAIN-SUFFIX - 策略 - 按需选策略；各个代理规则类型及作用**使用说明**可以参阅 Surge 中文手册：https://surge.mitsea.com/rule

## 附注

Surge 使用手册：https://surge.mitsea.com/overview 分流规则/策略组/DNS/Http重写进阶/脚本/...

blackmatrix7 分流/重写项目仓库地址：https://github.com/blackmatrix7/ios_rule_script/tree/master （目前全网更新较为勤奋，且包含App最为齐全的分流...OpenAI/ChatGPT分流..） 本 QuantumultX 懒人配置目前仅涵盖较少部分常用海外App分流规则，大家如需可进行查阅仓库，并在 Quantumult X 引用；

神机规则分流项目仓库地址：https://github.com/DivineEngine/Profiles/tree/master (已停更8个月)
