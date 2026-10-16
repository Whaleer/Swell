# Swell 使用指南与支持

[English](support.en.md) · 简体中文 · [返回 Swell](../README.zh-CN.md)

Swell: Art & Clock 是一款适用于 Apple Silicon Mac、要求 macOS 15 或更新版本的数字艺术应用，提供动态艺术、时钟、可选音乐与天气信息，以及本地照片和视频播放。

## 安装测试版

先在 Mac 上安装 Apple 的 TestFlight 应用，再打开 [Swell 测试邀请](https://testflight.apple.com/join/nZGUq3mh)，按提示安装。后续可在 TestFlight 中检查测试版更新。

不同构建的测试版可能有所变化。如果无法安装，请查看邀请页面的可用状态，并确认 Mac 满足上述系统要求。

## 选择播放内容

| 模块 | 开始使用 |
| --- | --- |
| **Lumina** | 从底部缩略图条选择内置主题，打开 **Adjust** 查看该主题提供的设置。 |
| **Cinema** | 使用 **Import** 导入 macOS 可播放的 MP4 或 MOV 视频。选择视频预览，用文件夹整理媒体库。 |
| **Pixellery** | 使用 **Import** 导入 JPEG、PNG 或 HEIC 图片，选择一张作为像素画廊的起点。媒体库为空时显示内置画作。 |

## 全屏、切换与退出

点击 **Full Screen** 或按 **Command-Return** 开始播放；按 **Escape** 返回画廊。全屏播放期间，使用 **Page Up** 或 **Page Down** 切换到上一个或下一个可用主题或媒体项目。

Mac 键盘没有独立 Page Up、Page Down 键时，可使用 **Fn-上箭头** 和 **Fn-下箭头**。

Swell 是全屏应用，不会安装或替换 macOS 系统屏幕保护程序。

## 设置时钟

在 Lumina 或 Pixellery 中打开 **Adjust → Clock**，开启 **Show Clock**，选择 **Flip** 或 **Clear Glass**。你还可以调整时间格式、秒数、日期与大小。

Lumina 与 Pixellery 共用时钟样式，但分别记忆时钟是否显示。Cinema 使用自己的时钟布局。Dot Progress 以独立方式呈现时间，不叠加时钟。

Clear Glass 在 macOS 26 及更新版本使用原生 Liquid Glass，在 macOS 15 使用材质兼容外观；它也会响应系统辅助功能中的透明度、对比度与动态效果设置。

全屏播放期间修改设置后，请返回画廊并重新进入全屏，以使用新设置。

## 音乐信息或封面没有出现

为当前模块开启 **Show Clock** 与 **Music Widget**，在 Music 应用中播放曲目，并在 macOS 提示时允许 Swell 访问 Music。权限可在 **系统设置 → 隐私与安全性 → 自动化** 中查看。

小组件从这台 Mac 的 Music 读取信息，不读取其他音乐应用的播放内容。封面来自当前曲目或本机 Music 资料库中的匹配项目，失败时会有限重试；部分曲目不提供可用封面，此时显示占位图，不会联网搜索缺失封面。

关闭音乐小组件或拒绝授权，不影响艺术画面与本地媒体播放。

## 天气没有出现

在支持的 Lumina 主题或 Pixellery 中打开 **Adjust → Weather**，开启 **Show Weather**。搜索并选择城市，或点击 **Use Current Location**，在 macOS 提示时允许定位。Dot Progress 不叠加天气。

城市搜索可离线使用，手动选择城市不需要定位权限。点击 **Use Current Location** 时才会请求一次定位；Swell 不会持续追踪位置。

天气更新需要联网。网络异常时，近期缓存可能继续显示，并附上观测时间；恢复网络后可点击刷新。使用已分发应用的天气功能不需要自行提供 API Key 或开发者账号。

## 导入媒体与磁盘空间

Swell 会在本地保存导入图片与视频的副本，因此导入会额外占用磁盘空间。移动原始文件不会删除应用保存的副本。

移除导入项目会删除 Swell 的副本，不会删除原始文件。正在全屏播放中使用的项目，可能保留到播放结束后才删除。

如果文件无法导入，请确认其他 Mac 应用能打开它，并检查磁盘剩余空间。MP4 与 MOV 是容器格式，其中的视频编码也需要受 macOS 支持。

## 多显示器与保持唤醒

在 Adjust 的播放设置中开启 **All Displays**，即可在连接的显示器上播放。时钟与信息位于主显示器，副显示器显示艺术画面。

**Keep Display Awake** 为可选功能，仅在全屏播放期间生效。按 Escape 结束播放后会释放保持唤醒状态。

## 哪些功能可以离线使用？

内置艺术、本地照片和视频播放均可离线使用，城市搜索也可离线使用；天气更新需要联网。音乐信息来自本机 Music，Music 自身播放部分曲目时可能需要网络。

Swell 在本地保存偏好与导入媒体，不向开发者上传导入照片或视频，也没有广告或使用情况分析 SDK。

## 联系与反馈

使用问题、Bug、功能建议或隐私请求，可发送至 [1004707367@qq.com](mailto:1004707367@qq.com)。开发者为 Bingxi Liu。

也可以通过 [GitHub Issues](https://github.com/Whaleer/Swell/issues)提交问题或建议，支持英文与中文。Issue、评论和附件均为公开内容；私人请求请使用邮件。

反馈 Bug 时，请尽量提供：

- Swell 版本，以及可获取的 TestFlight 构建号。
- macOS 版本与 Mac 型号。
- 涉及的模块或主题，以及相关的显示器配置。
- 复现步骤、预期结果与实际结果。
- 有助于定位问题的截图或完整报错。

发送附件前请移除私人信息。无需提供 Apple 账户密码或付款资料。

关于本地存储、音乐、天气、定位与支持消息的详细说明，请阅读[隐私政策](privacy.zh-CN.md)。
