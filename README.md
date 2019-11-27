[TOC]

# Perseus-All-In-One

**英仙座指南将告诉您绝大部分发生在远行星号(Starsector)游戏进程之外的应急事件的解决方法。**

这一则指南并不会教您如何玩远行星号，而是提供类似于**如何正常地进入游戏，如何安装MOD，如何分配内存以及如何解决错误**的方法。

*当然，远不仅限于此。*

注：各个链接可以ctrl+左键打开

注2：请不要直接编辑此文档，请到本文档的[Github链接](https://github.com/1847905557/Guidance-in-Perseus)参与编辑

***

## 进入游戏之前

在进入游戏之前，您需要下载游戏，购买正版并安装汉化。

### 下载游戏本体

**远行星号(Starsector)**目前的最新版本为**0.91a RC-8**，您可以在本群群文件中找到资源，下载后安装即可。

除此之外，您可以在群文件找到例如0.90a RC-10，0.81a RC-8的较老游戏资源，但依然推荐游玩最新版。



### 购买激活码

远行星号正版采取**激活码**制，为了正常进入游戏，您需要购买一份激活码对作者进行支持。

[官方购买链接](http://fractalsoftworks.com/preorder/)：需要PayPal或银联等支付手段。

[议长代购链接](https://item.taobao.com/item.htm?spm=a1z10.1-c-s.w4004-21088071351.3.41681269UWwZrj&id=582273883513)：基于淘宝的代购渠道，请务必阅读代购须知，**下单时备注邮箱**。

无论是从官方渠道购买还是代购，均有不可避免的数小时发货延迟，请耐心等待。

**支持正版，请不要下载盗版游戏或购买盗版激活码。**

在获取激活码后，将其输入游戏启动器即可。



### 安装汉化

远行星号的汉化包由**远星汉化组**制作，该汉化包为**远行星号中文论坛独占**。

为了下载汉化包，您需要在 [远行星号中文论坛](https://www.fossic.org) 注册账号，然后在 [汉化下载帖](https://www.fossic.org/thread-383-1-1.html) 回复后下载汉化包。

在获得汉化包后，将其复制到游戏安装目录下。如复制途中有提示替换文件或覆盖文件，点击全部确定即可。



*在完成上述事项后，您即完成了远行星号的安装和汉化，可以进入游戏开始体验了。*



***

## 使用MOD之前

仅游玩原版内容显然不能满足大部分玩家的需求，而远行星号的一大特点即为对**MOD(模组)**的强大支持能力。

*然而，在安装MOD之前，建议您先对原版体验有较为深入的理解，这样才能更好体验各个MOD内容。*

### 下载MOD

您可以在本群、以及论坛内找到MOD。

在下载MOD之前，请先确认：

  1)  您想要下载的MOD是否对应您的游戏版本(如0.9.0、0.9.1等等)
  2)  您想要下载的MOD是否为当前最新版(最新版的MOD通常具有相比旧版更多的内容、更合理的数据、以及更稳定)
  3)  您想要下载的MOD是否为独立mod，或者是否有明确标出与哪些MOD存在不兼容(独立MOD只可单独运行，同时运行不兼容的MOD则可能导致无法进入游戏，或是出现严重的bug,*尽管这种情况非常少见*)

下载到本地的MOD文件通常为以.rar、.zip、.7z为后缀名的**压缩文件**。

此外，从论坛下载的MOD因为格式问题，可能会出现与**论坛中显示的文件名不符**，以及**丢失文件后缀**的情况。此时，**请按照论坛上的文件名与后缀重命名文件**。



**关于前置MOD**

前置MOD，即为在安装其他MOD之前通常需要安装的MOD，一般所提到的前置MOD为**LazyLib**、**GraphicsLib**、与**MagicLib**(即3前置)。

与通常的MOD直接为游戏添加势力或舰船等不同，前置MOD的作用则是为这些通常的MOD服务，给这些MOD带来或是更简单的制作、或是更优良的视觉效果。

现在绝大多数的MOD都必须以安装了前置MOD中的部分甚至是全部为前提才能正常工作。

请保证在**安装了这三个前置MOD**的前提下再安装其他MOD，并确保这三个MOD处于最新的版本。



### 安装MOD

在游戏目录下寻找**mods**文件夹，如果没有则创建一个。

将您下载到的MOD**解压为文件夹**，然后放入mods文件夹即可完成安装。

因为MOD的压缩方式以及解压软件或者方式的不同，解压后可能会出现：

  1)  解压出的MOD存在多重文件夹(俗称套包)
  2)  将MOD根目录中的文件直接解压到了mods文件夹中
  
的情况。通常来说一个正常解压的MOD文件夹的名称通常为全英文，并且一般不会带有版本号(部分国产MOD如*打击者佣兵团*等MOD则为例外)。而打开MOD的文件夹后则均能看到mod_info.json文件，通常能看到data等文件夹。

如果解压后的MOD文件夹情况如上述不符，则MOD很可能无法正常运作。请重新解压MOD，或者将MOD文件夹修正为正确的形式。

在此之后，打开游戏启动器，点击启动器界面的正下方**MOD 管理**，点击勾选您安装的MOD，然后点击保存，即在游戏中启动您安装的MOD。



### 分配内存

远行星号将在游戏开始加载时给自己设定内存占用的上限。然而较低的上限将在MOD较多时造成卡顿，显著影响游戏体验。所以您需要给游戏分配更多内存。

根据电脑配置不同，推荐您分配**(电脑内存 / 2) G**内存到游戏中。

推荐使用对新手友好的 [内存修改工具](https://tieba.baidu.com/p/5219527443) 进行内存分配。

在一些情况下，内存修改工具可能会出现无法正常工作的情况，此时建议您手动修改内存分配。

在游戏根目录中找到vmparams文件，用记事本打开，在其中找到**-Xms1536m -Xmx1536m**的字段，这一段即为现在给游戏分配的内存。

游戏默认分配的内存即为1526m，约1.5g。将**这两个数值均修改为**您想分配的数值后保存，即完成了对内存分配的手动修改。*请注意不要把文件保存为txt格式。*



*在完成上述事项后，您即完成了MOD的安装，可以进入游戏体验更多内容。*



***

## 游戏出现了错误

有许多原因可能导致游戏错误，例如**内存不足，显存不足，MOD本身存在的问题**等。

在解决问题之前，您需要对出现频率最高的几类错误有基本的认识。

### Out Of Memory

如果游戏闪退后弹出窗口，含有**Out Of Memory**字样，这代表着**您的内存不足**。

您可以通过**关闭部分MOD**或**分配更多内存**解决这个问题。



### Array Index Out Of Bounds

如果游戏闪退后弹出窗口，含有**Array Index Out Of Bounds**字样，这代表着出现了**数组越界**错误。

在绝大部分情况下，您可以通过**更新前置MOD**解决这个问题。

如果您在做了正确的尝试后依然无法解决这个问题，请参照**Null Pointer Exception**部分的建议。



### Null Pointer Exception

如果游戏闪退后弹出窗口，含有**Null Pointer Exception**字样，这代表着出现了**空指针**错误。

您无法解决这个问题，请按照以下流程提交**log(错误报告)**：

暂时**不要重新启动游戏**。进入您的游戏安装目录，使用记事本或其他文本编辑器打开**Starsecto\starsector-core\starsector.log**文档，此文件为log。

拉到文档的末尾，将光标移动至于文档的末尾，按Ctrl+f呼出搜索窗口，向上搜索**ERROR**。

当您搜索到一段**与其他段落的明显格式不同的文字**时，将这一整段文字以任何可能的方式发送给群内管理员或其他能够帮助您解决问题的群友。

这段文字看上去像是这样的：

`179855 [Thread-4] ERROR com.fs.starfarer.combat.CombatMain - java.lang.NullPointerException`
`java.lang.NullPointerException`
​     `at src.lt.data.scripts.campaign.Lt_CampaignSpawnSpecialFleet.advance(Lt_CampaignSpawnSpecialFleet.java:60)`
​     `at com.fs.starfarer.campaign.CampaignEngine.advance(Unknown Source)`
​     `at com.fs.starfarer.campaign.CampaignState.advance(Unknown Source)`
​     `at com.fs.starfarer.BaseGameState.traverse(Unknown Source)`
​     `at com.fs.state.AppDriver.begin(Unknown Source)`
​     `at com.fs.starfarer.combat.CombatMain.main(Unknown Source)`
​     `at com.fs.starfarer.StarfarerLauncher$1.run(Unknown Source)`
​     `at java.lang.Thread.run(Unknown Source)`

然后耐心等待问题的解决方案。

*建议在每次游戏正常结束后删除log文档，如果这样，报错时的log就只储存了本次报错的日志，便于解决问题。*



### 通过回档解决部分问题

在一些情况下，您可以通过**加载曾经的存档备份**以避开一些错误的触发，或**修复无法加载的存档**。

您的存档在**Starsector\saves\save_[存档角色名]**文件夹内。

为了回档，您需要删除其中的campaign.xml文件和descriptor.xml文件，然后将campaign.xml.bak文件改名为campaign.xml，将descriptor.xml.bak文件改名为descriptor.xml文件。



***

## 游戏内容参考资料

了解更多游戏机制内容或阅读更多教程能助力您提升在远行星号的游戏水平。

### 部分远行星号社区

[远行星号官方论坛](http://fractalsoftworks.com/)

[远行星号中文论坛](https://www.fossic.org/)

[远行星号吧](https://tieba.baidu.com/f?kw=%E8%BF%9C%E8%A1%8C%E6%98%9F%E5%8F%B7&fr=index&fp=0&ie=utf-8)



### 部分精选参考资料

[武器机制科普](http://tieba.baidu.com/p/5351676528)

[装甲机制科普](http://tieba.baidu.com/p/5459369406)

[术语界定](https://www.fossic.org/thread-180-1-1.html)

[设置文件settings](https://tieba.baidu.com/p/5916648546)





***

Sort by AnyIDElse
