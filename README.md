# TypeBridge

Phone to PC wireless input tool.

- Input text on phone
- Receive instantly on PC
- QR code connection
- Android TV support
- PPT remote support

English documentation coming soon.

手机输入，电脑接收。  
让手机变成电脑的无线输入面板。

---

## 功能介绍

TypeBridge 可以让你：

- 手机输入文字
- 电脑实时接收
- 自动复制到剪贴板
- 一键粘贴到当前输入框
- 局域网低延迟连接
- 支持 PPT 遥控
- 支持 Android TV 输入

适用于：

- 客厅电视输入
- PPT 演讲控制
- 跨设备快速传文本
- 临时替代键盘
- 直播 / 演示场景

---

# 软件截图
<img width="764" height="327" alt="image" src="https://github.com/user-attachments/assets/866eab7d-821a-4f44-a3ac-5b4f0ce94e56" />

- 电脑端主界面

  
<img width="345" height="609" alt="image" src="https://github.com/user-attachments/assets/08ff1ec4-7a78-422a-9769-6b088e64c7cb" /> 

- 手机输入页面(手机扫码进入)

  
<img width="337" height="567" alt="image" src="https://github.com/user-attachments/assets/f7c818f6-e16d-4e09-9704-06f51062f44c" />

- 文字输入页面


<img width="344" height="607" alt="image" src="https://github.com/user-attachments/assets/8c764727-f171-4c51-8c94-2cc1db47d7e4" />

- PPT 遥控页面

---

# 下载

## Windows

前往 Releases 页面下载：

[Download TypeBridge](../../releases)

下载后直接运行：

```bash
TypeBridge.exe

无需安装 Python。

使用方法
第一步

打开电脑端 TypeBridge。
首次使用需要激活,激活码在本文最下面。

第二步

使用手机扫描二维码。

第三步

手机打开输入页面。

第四步

输入文字并发送。

电脑会实时收到内容。

激活说明

当前版本需要输入激活码。

主要原因：

防止接口被恶意刷请求
避免公开传播后服务器压力过大
保证正常用户的连接稳定性

目前激活码默认有效期为：

10 天

到期后：

重新激活一次即可继续使用。

不影响本地数据，也不会删除配置。

为什么不是永久激活？

TypeBridge 目前仍在持续开发和调整中。

作者本人也每天都在实际使用，因此会持续维护：

连接稳定性
消息传输
局域网兼容
新版本更新
远程连接策略

当前采用短周期激活，主要是为了：

降低服务器滥用
控制异常请求
保证整体可用性

并不是订阅收费模式。

功能说明
文本输入

手机输入 → 电脑接收。

支持：

中文
英文
Emoji
长文本
剪贴板模式

收到内容后自动复制到剪贴板。

适合：

微信
浏览器
聊天软件
搜索框
PPT 遥控

支持：

下一页
上一页
全屏
Android TV 模式

电视显示二维码。

手机扫码即可输入文字到电视。

适合：

搜索视频
登录账号
客厅输入
网络说明

默认使用：

局域网直连

部分版本支持：

Cloudflare Tunnel
远程连接
安全说明
默认不上传输入内容
文本优先本地传输
不保存聊天记录
不收集隐私数据
开发计划
 消息历史记录
 多设备连接
 Mac 支持
 Linux 支持
 Android APP
 iOS APP
 WebSocket 稳定传输
 输入法模式
常见问题
手机打不开页面？

请检查：

手机和电脑是否在同一网络
防火墙是否拦截
是否开启代理 / VPN
为什么偶尔会丢消息？
后续会专门处理一个网络检测工具。

当前版本仍在持续优化：

WebSocket 连接
消息确认机制
自动重发逻辑
技术架构

电脑端：

Python
Flask
WebSocket
PyInstaller

手机端：

HTML
JavaScript

网络：

HTTP
WebSocket
Cloudflare Tunnel
License

Personal Use Only.

Commercial license required for business usage.

作者

TypeBridge Project

激活码：TypeBridge-OFF-20260526-27A55ACA
目前有效期设置的比较短,但是不用担心,作者自己也在用，一般到期24小时左右,作者就会重新设置时间,用户只需要点 重新激活授权 即可以。

AndriodTV接收端,即将发布,敬请关注。
根据用户的反馈决定是否开发更多的键盘,比如指令模式，全键盘指令或者将某些指定 按键 独立放在一页。


