<p align="center">
  <img src="assets/icon.png" width="128" alt="Sunny">
</p>
<h1 align="center">Sunny Releases</h1>
<p align="center">Sunny 各平台安装包的发布仓库 · 源码不在此仓，只有产物</p>

<p align="center">
  <a href="https://github.com/sundayfun/siuper-releases/releases?q=mac-"><img src="https://img.shields.io/github/v/release/sundayfun/siuper-releases?filter=mac-*&include_prereleases&label=macOS" alt="macOS"></a>
  <a href="https://github.com/sundayfun/siuper-releases/releases?q=android-"><img src="https://img.shields.io/github/v/release/sundayfun/siuper-releases?filter=android-*&include_prereleases&label=Android" alt="Android"></a>
  <img src="https://img.shields.io/github/downloads/sundayfun/siuper-releases/total" alt="Downloads">
  <img src="https://img.shields.io/badge/license-Proprietary-lightgrey" alt="License">
</p>

<p align="center">
  <a href="#下载">下载</a> · <a href="README.en.md">English</a> · <a href="#版本规则">版本规则</a> · <a href="#反馈">反馈</a>
</p>

---

## 下载

| 平台 | 最新 | 安装 | 自动更新 |
|---|---|---|---|
| macOS | [Sunny.dmg](https://github.com/sundayfun/siuper-releases/releases/download/latest/Sunny.dmg) · [mac.json](https://github.com/sundayfun/siuper-releases/releases/download/latest/mac.json) | 拖到 Applications | 内置，每小时检查 |
| Android | [Sunny.apk](https://github.com/sundayfun/siuper-releases/releases/download/latest/Sunny.apk) · [android.json](https://github.com/sundayfun/siuper-releases/releases/download/latest/android.json) | 允许「安装未知应用」 | App 内检查 |

上表是**固定链接**：`releases/download/latest/<平台包>` 永远指向当前 stable，`<platform>.json` 描述它（version、build、channel、url、archive_url、tag、sha256、size、notes、published_at），客户端应用内更新读同一形状。历史版本按 tag 存档：https://github.com/sundayfun/siuper-releases/releases

## 版本规则

- Tag 形如 `<platform>-<version>+<build>`，例：`mac-1.0.13+10478`
- 每次出包都会上传一个 **Pre-release**，仅供存档与定向测试
- 只有被 promote 的版本才进入自动更新与固定链接；当前推送版本以 `mac/appcast.xml` 为准，其 commit 历史即发布历史
- `latest` 是滚动 release，不代表任何一次构建；不要引用它的 tag 做回滚，用 `mac-<version>+<build>`

## 历史版本

见 [Releases](https://github.com/sundayfun/siuper-releases/releases)。

## 反馈

请在本仓 [Issues](https://github.com/sundayfun/siuper-releases/issues) 提交，附平台、版本号（`关于` 页可见）与复现步骤。

## 协议

仓内文件为专有软件，仅授权安装使用，禁止再分发、修改与逆向。详见 [LICENSE](LICENSE)。
