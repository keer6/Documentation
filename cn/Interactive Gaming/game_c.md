
---
title: Cocos Creator 快速开始
description: 
platform: Cocos Creator
updatedAt: Tue Mar 19 2019 14:42:06 GMT+0000 (UTC)
---
# Cocos Creator 快速开始
## 前提条件

请确保满足以下开发环境要求：

- Cocos Creator v2.0.7 及以上版本（v2.1.0 除外）
- 移动端需要 Android 或 iOS 真机
- Web 端浏览器需满足[特定要求](https://docs.agora.io/cn/Audio%20Broadcast/web_prepare?platform=Web)
- 没有连接 VPN

## 创建新的项目

如果你的项目已存在，请略过本节内容。

1. 打开 Cocos Creator，选择**新建项目**。

	 ![](https://web-cdn.agora.io/docs-files/1551852700055)

2. 在**新建项目**页面，选择**空白项目**，设置项目所在路径，点击**新建项目**。

	 ![](https://web-cdn.agora.io/docs-files/1551852902872)

至此，一个新项目就创建成功了。你会看到如下界面：

![](https://web-cdn.agora.io/docs-files/1551852922649)

## 集成 Agora 服务

1. 在 Cocos Creator 中，打开你的项目。选中**面板**，在下拉菜单中选择**服务**。
   ![](https://web-cdn.agora.io/docs-files/1552018474387)

屏幕右边区域会出现**服务**面板。
![](https://web-cdn.agora.io/docs-files/1551928921523)
   

2. 选中声网服务，点击启用按钮。
   ![](https://web-cdn.agora.io/docs-files/1551928334719)
   
   Cocos Creator 会自动下载和配置所有声网服务依赖的资源。Cocos Creator 中的 Agora 对象暴露和提供[主要 API 功能](../../cn/Interactive%20Gaming/game_cocoscreator.md)。
	 > Cocos Creator 提供的 JavaScript API 为方便使用仅实现了主要功能，如果需要其他扩展功能，请参考各平台完整版 API 文档。

3. 在你的项目中，调用 API 实现游戏通话。关键 API 的调用方法及逻辑可参考 `HelloAgora` Demo。
![](https://web-cdn.agora.io/docs-files/1551929077432)
