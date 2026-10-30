# LPCL
https://github.com/你的用户名/LPCL
LPCL（创想起源）是一个面向 Minecraft Java 版的免费 Windows 第三方启动器。
玩家使用自己的微软账号登录，启动器只调用官方 Microsoft OAuth、Xbox Live、
XSTS 和 Minecraft Services API 来验证玩家是否拥有 Java 版并启动游戏。

启动器不共享账号、不绕过正版验证、不分发游戏本体，也不提供盗版下载。
目前 Microsoft OAuth、Xbox Live、XSTS 均成功，仅在
POST /authentication/login_with_xbox 返回 403 Invalid app registration。

申请将该 Client ID 加入 Minecraft Services 白名单，让合法拥有 Minecraft
Java 版的玩家可以在 LPCL 中正常登录。应用会遵守 Minecraft EULA 和使用指南，
并提供公开下载页面与隐私政策，配合审核。
