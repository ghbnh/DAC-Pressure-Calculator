# DAC Pressure Calculator PWA

适用于 iPhone、Windows 11、macOS 的简易渐进式网页应用（PWA）。

## 功能
- 金刚石 Raman 高频边缘：Akahama–Kawamura (2006), P=547x(1+1.375x), x=(ω-ω0)/ω0
- Ruby R1 荧光：Mao et al. (1986), P=(1904/7.665)*[(λ/λ0)^7.665-1]
- 输入实测峰位实时计算压力（GPa）；反算指定压力下的预期峰位
- 自定义常压参考峰位、复制结果、警告、25 GPa 示例
- 支持安装到 iPhone 主屏幕以及在首次成功缓存后的离线使用

## GitHub Pages 发布
仓库 Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save。
使用公开仓库最为简单；仓库私有时可能受到 GitHub 账户 Pages 权限与方案限制。
访问 https://ghbnh.github.io/DAC-Pressure-Calculator/ 。

## iPhone 安装
Safari 打开 Pages 地址 → 分享 → 添加到主屏幕 → 添加。
首次联网打开后完成缓存，开启飞行模式进行离线测试。

## 限制
常温经验压力标定，不直接考虑高温及非静水压修正。Ruby 在 80 GPa 以上为原始标定范围外推。
金刚石应定位高波数边缘而不是简单峰顶。
