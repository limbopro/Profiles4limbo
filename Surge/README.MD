## 准备工作

1. 了解Sub-Store 高级订阅管理工具：https://limbopro.com/archives/Sub-Store.html 或 博主提供的订阅转换工具：https://limbopro.com/archives/subconverter.html

2. 从你的机场找到 Surge 托管配置链接，复制到备忘录；

3. 未来你可以自行添加策略组及分流规则集；

## 下载配置文件（预配置分流、策略组）

```
https://limbopro.com/Surge/Surge4limbo.conf
```

1.复制上述链接，即懒人配置文件对应，进入 Surge 主界面，点击左上角配置切换按钮； 

2.找到**导入**，点击**从URL下载配置**，粘贴刚刚复制的配置文件链接🔗；

## 安装模块（Tiktok解锁、YouTubeApp去广告、毒奶去网页广告计划）

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

## 配置 Surge.list（订阅你的机场）

下载后配置文件后 1.进入主界面 - 出站模式 - 选择规则模式 - 点击进入代理服务器；

2.分别找到如下策略组，♻️故障切换、🐟 final、Netflix；滑至底部，找到**外部代理列表**，粘贴你的 **surge.list**。

3.配置证书📄；

## FAQ 如何获得机场订阅的Surge.list?（订阅转换API的使用）
如果机场不直接提供，或可使用订阅转换API；可以使用 Sub-Store；高级订阅管理器：https://limbopro.com/archives/Sub-Store.html 

### 1个机场订阅的情况
1.点击 https://www.urlencoder.org/ 进入编码页面，粘贴你的机场订阅，点击 ENCODE按钮，得到编码后的链接；

2.https://limbopro.cyou/sub?target=surge&ver=4&url=这里粘贴编码后的链接&list=true

3.以上，粘贴第2点得到的全新链接到**外部代理列表**处；

### 多个机场订阅的情况（合并为1个订阅）

这就涉及到正则表达式的使用了。

**使用** `|` **将两个订阅分隔开**：

```
你的第1个订阅|你的第2个订阅|你的第3个订阅
```

1.点击 https://www.urlencoder.org/ 进入编码页面，粘贴，点击 ENCODE按钮，得到编码后的链接；

2.https://limbopro.cyou/sub?target=surge&ver=4&url=这里粘贴编码后的链接&list=true

3.以上，粘贴第2点得到的全新链接到外部代理处；

### 小知识

#### 如何新建策略组以及策略组互相嵌套

1.进入主界面 - 出站模式 - 选择规则模式 - 点击进入代理服务器 ，这里有已经建立好的各个策略组（你可以点击它的名称进去进一步设置）；

2.继续往下滑，找到 **新建策略组** 按钮，点击它；然后设置好策略组的**组名称**，**组类型**，你可以看到 **包含的策略**，它的下方目前是 空的，你还可以看到 **可用的策略**，你可以选择拖拽这些 **可用的策略** 到 **包含的策略** 下方，这样就完成了一个基本的策略组嵌套；好了，往下滑，你会看到 **外部代理列表**，很熟悉吧，选择 **开启**，粘贴 你的 Surge.list；

3.Surge/QuantumultX/Clash 的策略组都是如此嵌套在一起的，可以是单独的策略，如 DIRECT/REJECT/PROXY，我们命名一个策略名称为B，并把一个机场订阅的节点放在下面，就得到了一个新的策略，你可在策略A下嵌套B。

## 附注

blackmatrix7 分流/重写项目仓库地址：https://github.com/blackmatrix7/ios_rule_script/tree/master （目前全网更新较为勤奋，且包含App最为齐全的分流...OpenAI/ChatGPT分流..） 本 QuantumultX 懒人配置目前仅涵盖较少部分常用海外App分流规则，大家如需可进行查阅仓库，并在 Quantumult X 引用；

神机规则分流项目仓库地址：https://github.com/DivineEngine/Profiles/tree/master (已停更8个月)
