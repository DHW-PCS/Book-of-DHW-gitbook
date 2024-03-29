---
description: 如果你从未用过第三方登录，且准备使用 DHW Passport 验证登录，请依照本提示设定好你的启动器。
---

# DHW Passport 使用须知

Inf 支持使用多种验证方式登入服务器，本文将讲述如何使用 DHW Passport 来进行登录。

{% hint style="info" %}
你首先得是 DHW 成员或 DHW Inf 玩家才能使用该系统登入服务器。在通过审核后你将获得一个一次性的邀请码，它将用于注册你的服务台账户。DHW Inf 审核QQ群：[873305382](https://jq.qq.com/?\_wv=1027\&k=CLcpAiWK)
{% endhint %}

### 1 注册

打开 Inf 服务台（地址见群公告），按照提示填入邀请码和各项必要信息来注册你的账户 （如果访问较慢，请将所有提到的地址换成备用地址再试）

### 2 配置启动器

![登录后点击"用户中心"，你将看到如图所示的"快速配置启动器"卡片。](</.gitbook/assets/快速配置启动器.png>)

* **如果你使用HMCL：**

1. 将服务台用户界面中“将此按钮拖动到启动器”按钮拖动到HMCL窗口中，点击“完成”
2. 点击窗口左上角的“账户”
3. 点击窗口右下角的加号，登录方式选外置登录，认证服务器选择“Inf 服务台”（在某些版本则会显示为“Inf Service Center”）
4. 使用你的邮箱和密码登录

![HMCL 的设定图示（更详细的图示请在群文件寻找“配置图解”）](</.gitbook/assets/HMCL外置登录.png>)

* **如果你使用BakaXL：**

1. **点击**“将此按钮拖动到启动器”按钮
2. 进入**启动器的“开始菜单”**-本体设置-账户与档案-新增一个账户
3. 点击“游戏启动方式”直到切换为“**外置登录(authlib-injector)**”
4. 在“验证服务器地址(API Root)”中粘贴先前复制的地址
5. 使用邮箱和密码登录
6. **点击“进行验证和返回”**

![在 BakaXL 中设置外置登录](</.gitbook/assets/BakaXL外置登录.png>)

* **如果你使用 PCL 2：**

1. **点击**“将此按钮拖动到启动器”按钮
2. 回到启动器主界面，进入1.15.2的**版本设置-独立设置**
3. 在底部的**服务器选项**中将登录方式改成“第三方登录：Authlib-Injector”
4. 在“认证服务器”和“注册链接”一栏粘贴先前复制的地址
5. **请将“注册链接”一栏地址中的“api/yggdrasil”改为“auth/register”**
6. 返回到主界面并使用邮箱和密码登录

![在 PCL 2 中设置第三方登录](</.gitbook/assets/PCL2外置登录.png>)

### 3 启动游戏

**HMCL、Nsiso：**

请在账户中选择**外置登录**账户，然后启动游戏

**BakaXL：**

请启动游戏，然后在“哪个用户将用于启动Minecraft？”中选择**第三方登录**账号

**PCL 2：**

请直接启动设置好第三方登录的游戏版本

### 4 进入服务器

请将群公告中的服务器地址添加到你的多人游戏中，之后进入服务器。你将获得类似正版验证的登录体验。而皮肤或披风可以自行上传至服务台后装配至你的玩家。

{% hint style="info" %}
验证服务器使用 Let's Encrypt X3 进行连接加密，请留意启动器是否存在开启时报错的情况，有则请更新 Java 到更新的版本（Java 8 Update 101 以上）再进行尝试。
{% endhint %}

### 5 无效的会话

虽然使用通行证不需要你每次输入密码，但如果进入服务器多次看到“无效的会话”警告，常用的方法是在启动器删除帐户并再次重新添加。若安装了切换登录方式的模组，你也可以使用它在游戏中尝试重新登录你的服务台账户，在此不再赘述。

### 建议你在选取地址时从前往后尝试，或是将其中的几个加入到你的服务器列表中。

### 6 启动器下载

如需下载上文提到的启动器，请到[资源下载](downloads.md)页面。
