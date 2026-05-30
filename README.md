# 隐私浏览器配置指南

配置浏览器在代理环境下最大化隐私保护。

## Firefox 隐私配置

### about:config 高级配置

```
privacy.trackingprotection.enabled = true
network.cookie.cookieBehavior = 1
privacy.resistFingerprinting = true
```

### 推荐扩展

- uBlock Origin - 广告拦截
- NoScript - JavaScript 控制
- Canvas Blocker - Canvas 指纹防护
- HTTPS Everywhere - 强制 HTTPS

## Chrome / Ungoogled Chromium

推荐使用 Ungoogled Chromium：

```bash
# Linux
sudo pacman -S ungoogled-chromium
```

## 代理配置 - SwitchyOmega

只让浏览器走代理，系统其他流量直连：

1. 安装 SwitchyOmega 扩展
2. 配置代理规则
3. 按网站自动切换

## 反指纹技术

- **Fingerprint Defender** - 随机化指纹
- **User-Agent Switcher** - 切换 UA
- **Canvas Blocker** - 阻止 Canvas 指纹

---

推荐工具：

- [Clash for Windows](https://clashforwindows.site/)
- [ClashMI](https://clashmi.site/)
- [FlClash](https://flclash.us/)
