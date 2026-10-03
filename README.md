<div align="center">

# VIPFucker

### 面向已适配 Android 应用的 LSPosed 模块

[![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84?logo=android&logoColor=white)](https://www.android.com/) [![LSPosed](https://img.shields.io/badge/LSPosed-API%20102-blue)](https://github.com/LSPosed/LSPosed) [![Download](https://img.shields.io/badge/APK-Releases-orange)](https://github.com/qianqi32/vipfucker/releases)

**[下载安装包](https://github.com/qianqi32/vipfucker/releases) · [Telegram 频道](https://t.me/VIPFuckerApp)**

</div>

---

VIPFucker 为已适配的应用加载对应规则，并在模块界面展示应用安装情况、推荐版本和 LSPosed 作用域状态。

## ✨ 主要功能

| 功能 | 说明 |
| --- | --- |
| **应用适配** | 按目标应用加载对应规则；实际效果以目标应用版本及设备环境为准 |
| **状态查看** | 集中查看已适配应用、安装版本和作用域状态 |
| **作用域申请** | 在模块界面发起申请，并通过 LSPosed 通知确认授权 |
| **更新与外观** | 在应用内检查更新，并调整界面风格、主题色和深浅色模式 |

## 📱 已适配应用

下表是当前模块界面标注的推荐版本和功能。目标应用更新后，规则可能不再适用；列表不代表所有版本都经过验证。

| 应用 | 推荐版本 | 模块界面标注的功能 |
| --- | --- | --- |
| CapyPlayer | 1.1.6 | 解锁终生会员 |
| Hills | 1.9.1 | 解锁 Hills Pro |
| Yamby | 2.1.0.11 | 解锁 Yamby Pro |
| 囧次元 | 2.3.0.7 | 去广告、播放解锁 |
| 口袋写作 | 3.3.7 | 解锁永久会员 |
| 一木记账 | 6.6.8 | 解锁永久会员 |
| 阅读记录 | 4.17.2 | 解锁永久会员 |
| 记得日子 | 0.16.10 | 解锁会员功能 |
| AppShare | 5.1.5 | 解锁会员、免广告 |
| 记得记账 | 0.59.4 | 解锁会员功能 |
| Todo清单 | 5.0.0 | 解锁高级账户 |

## 🚀 安装与使用

**安装条件：**Android 8.0（API 26）或更新版本、支持模块 API 102 的 LSPosed 环境，以及所需的目标应用。

1. 从本仓库的 [Releases](https://github.com/qianqi32/vipfucker/releases) 下载并安装 APK。若页面暂时没有附件，请等待新版发布。
2. 在 LSPosed 中启用 VIPFucker，并为需要使用的目标应用授权作用域。
3. 打开模块查看安装版本与作用域状态。若在模块内申请作用域，请在 LSPosed 通知中确认。
4. 重启目标应用进程，再检查对应功能；部分规则只在应用启动时生效。

更新模块时应使用相同签名的安装包。不同签名无法直接覆盖安装；如果设备上装过版本编号更高的开发包，也无法直接降级覆盖。

## ❓ 常见问题

**显示“LSPosed 服务未连接”？** 确认已在 LSPosed 中启用模块，然后重新打开 VIPFucker。

**应用在列表中，却没有生效？** 检查作用域是否已经授权、目标应用版本是否符合推荐版本，再重启目标应用。显示在列表中不代表作用域已获授权。

**更新模块后仍未生效？** 重启目标应用进程。切换界面并不能让所有规则即时重新加载。

## ⚠️ 使用须知

- 模块会影响目标应用的运行行为，系统、框架或目标应用更新后可能失效或引发异常。使用前请自行备份重要数据。
- 使用前请确认已取得必要授权，并遵守目标应用的用户协议及适用的法律法规。
- 安装包以本仓库 Releases 附件为准，请勿从不明来源获取。项目动态见 [Telegram 频道](https://t.me/VIPFuckerApp)。

---

<div align="center">

如果这个项目对你有帮助，欢迎点一个 ⭐ Star。

</div>
