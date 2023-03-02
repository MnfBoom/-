碧蓝航线反和谐 AzurLaneUncensored
旨在打造更方便 更Geek 的碧蓝航线反和谐。

本仓库文件所有立绘文件均来自于 azurlane_uncensored。该仓库实际是空项目，仅在 Releases 发布更新。每次更新不发布新 Release，而是直接替换已有 Release 的 Assets，给版本控制带来了极大的不便。AzurLaneUncensored 将这些文件添加进 git 中，并提供自动反和谐的方法。

另外，这里需要讲解一些反和谐方式和纠正原仓库中的错误认识。

localization.txt 反和谐。将下面的内容写入 com.bilibili.azurlane/files/localization.txt 即可解锁特殊触摸和取消一些由代码控制的和谐，比如长岛 ”干物三连！“ 皮肤中的安全裤。

Localization = true
Localization_skin = true
目前认为，这是游戏开发者故意留的后门。你可以大胆地认为，使用 localization.txt 反和谐是安全的。

替换立绘反和谐。localization.txt 并不能取消所有的和谐，因为一些和谐是直接画在了立绘图片上，比如矶风的 “新年合战“ 皮肤。因此，需要替换这些立绘图片。这些用来替换的立绘，并不是原仓库所说的 "废案"，而是外服的未和谐的立绘。

修改立绘文件有潜在风险的。

舰船名称反和谐。舰船名称反和谐，以上方式均不能实现，只能通过修改 scripts 文件实现（com.bilibili.azurlane/files/AssetBundles/scripts32），本仓库和原仓库均不会提供修改过的 scripts 文件。scripts 文件包含各种游戏数据，修改它等同于制作科技，也就是外挂。同时，你也无法保证他人制作的 scripts 是否有修改其他内容 有脏东西。

修改 scripts 文件存在风险。

光环助手反和谐。大部分公司不会在没有利益的情况下，持续地免费地发布内容，而光环助手恰恰有着持续的免费的内容更新。作为一个 Geek，你不应该使用第三方游戏客户端，以免帐号密码泄漏或造成更严重的后果。

使用第三方游戏客户端反和谐，风险最高。
